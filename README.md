# PTW-accelerometer-dataset
This dataset contains accelerometer and gyroscope readings of a Powered Two -wheeler during various riding intervals.
# Two-Wheeler Fall Detection Dataset

This repository contains a labeled dataset collected from a single-person-ridden two-wheeler to analyze and classify different riding conditions: **Fall**, **Near Fall**, and **Normal** scenarios. The data is especially useful for research and development in the fields of **vehicular safety**, **accident detection systems**, and **smart mobility solutions**.

---

## 📂 Dataset Description

The dataset includes sensor readings captured during various two-wheeler ride scenarios using an onboard device. It features time-series data from:

- **Accelerometer** on three axes: `Accel_X`, `Accel_Y`, `Accel_Z`
- **Gyroscope** on three axes: `Gyro_X`, `Gyro_Y`, `Gyro_Z`

Each reading is labeled as one of the following:
- `Fall`: Complete fall or crash of the two-wheeler
- `Near Fall`: Skidding, slipping, or near-fall situations
- `Normal`: Normal riding or idling conditions

---

## 📊 Features

| Feature Name | Description                     |
|--------------|---------------------------------|
| Accel_X      | Accelerometer reading on X-axis |
| Accel_Y      | Accelerometer reading on Y-axis |
| Accel_Z      | Accelerometer reading on Z-axis |
| Gyro_X       | Gyroscope reading on X-axis     |
| Gyro_Y       | Gyroscope reading on Y-axis     |
| Gyro_Z       | Gyroscope reading on Z-axis     |
| Label        | Activity Label (Fall, Near Fall, Normal) |

---

## 🧪 Use Cases

This dataset can be used for:
- Training ML models for fall detection in two-wheelers
- Creating smart accident response systems
- Real-time safety monitoring systems
- Motion analysis and activity classification

---

## ⚙️ Data Format

The dataset is stored in CSV format:

```csv
Accel_X,Accel_Y,Accel_Z,Gyro_X,Gyro_Y,Gyro_Z,Label
-0.123,0.456,9.812,0.01,0.02,0.00,Normal
...
## Source & Collection
Data collected using onboard IMU sensors (accelerometer + gyroscope)

Single rider on a two-wheeler under controlled and real-world conditions

Labels were manually annotated based on video observation and ride context.
This dataset is released for academic and research purposes only. For commercial use, please contact the author.  
