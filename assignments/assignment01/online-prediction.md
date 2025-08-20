# Online Prediction

<!-- Online Prection ทำงานอย่างไร  -->
ทุกครั้งที่ sensor ส่งข้อมูลมา → โมเดลจะทำนายความเร็วพัดลมออกมาก่อน → แล้วพอได้รับ label จะอัพเดทข้อมูลใหม่เข้าโมเดลทันทีแบบ online learning ไม่ต้อง retrain ใหม่ทั้งหมด

## ปิดการใช้งานของ Batch ML ดังนี้

1. Kafka-to-Jsonl
2. Train-from-data
3. Predict-then-influxdb


## เริ่มใช้งาน Online ML ดังนี้

1. docker cmpose down batch ML
2. edit file .env ของ online-ml-predict
3. docker compose up online ML

## ผลที่ได้จากการใช้ ML มีดังนี้

<!-- แนบรูป Grafana  พร้อมอธิบาย -->
![MLIoT](../../assets/images/Screenshot%202025-08-13%20145803.png)