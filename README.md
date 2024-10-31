# แนวทางการทำงาน ESP32_ESP-IDF_WiFi-STA cook book
## 1. ระบุตัวอย่างที่ใช้ ว่าเอามาจากตัวอย่างไหน
เลือกโปรเจค Wi-Fi Station Example จาก show examples แล้วกด create
![image](https://github.com/user-attachments/assets/15a7effc-4edb-4af2-9795-ba5344dac798)

## 2. ระบุว่า จะแก้ไขตรงไหนบ้าง เพื่ออะไร
แก้ไขที่ idf.py menuconfig ไปที่ example config ตั้งค่ารหัส wifi
![image](https://github.com/user-attachments/assets/a394d032-cade-4545-86a8-66681b14ca8d)

## 3. แสดงขั้นตอนการทำ project
แก้ไข เพิ่มข้อมูลรหัส wifi ที่ example config กด save แล้วกด build

## 4. แสดงผลการทำ project
![image](https://github.com/user-attachments/assets/5d5f5618-d92d-4e6f-9614-959a3afe14bb)

## 5. สรุปผลการทำ project
โปรเจคนี้จะตรวจสอบถ้าการเชื่อมต่อสำเร็จ terminal จะแสดงข้อมูล IP Address ที่ได้รับ
