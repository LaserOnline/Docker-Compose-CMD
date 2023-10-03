# คู่มือคำสั้ง Docker-Compose

`docker-compose` เป็นเครื่องมือที่ใช้ในการกำหนดและเริ่มต้นแอปพลิเคชัน Docker ที่ประกอบด้วยหลายคอนเทนเนอร์ นี่คือคำอธิบายสั้น ๆ ของคำสั้ง `docker-compose` ที่พบบ่อย:

### 1. `docker-compose up`
- **การใช้งาน:** `docker-compose up [options] [--scale SERVICE=NUM...] [SERVICE...]`
- **คำอธิบาย:** สร้าง, (สร้างใหม่) เริ่มต้น, และเชื่อมต่อไปยังคอนเทนเนอร์สำหรับบริการต่าง ๆ

### 2. `docker-compose down`
- **การใช้งาน:** `docker-compose down [options]`
- **คำอธิบาย:** หยุดและลบคอนเทนเนอร์, เน็ตเวิร์ค, วอลลูม, และอิมเมจที่สร้างโดยคำสั้ง `up`

### 3. `docker-compose build`
- **การใช้งาน:** `docker-compose build [options] [SERVICE...]`
- **คำอธิบาย:** สร้างหรือสร้างบริการใหม่ที่ระบุในไฟล์ Compose

### 4. `docker-compose ps`
- **การใช้งาน:** `docker-compose ps [options] [SERVICE...]`
- **คำอธิบาย:** แสดงรายการคอนเทนเนอร์ที่เกี่ยวข้องกับบริการที่ระบุ

### 5. `docker-compose logs`
- **การใช้งาน:** `docker-compose logs [options] [SERVICE...]`
- **คำอธิบาย:** แสดงข้อมูล log จากบริการ

### 6. `docker-compose exec`
- **การใช้งาน:** `docker-compose exec [options] SERVICE COMMAND [ARGS...]`
- **คำอธิบาย:** ดำเนินการคำสั้งในคอนเทนเนอร์ที่กำลังทำงาน

### 7. `docker-compose pull`
- **การใช้งาน:** `docker-compose pull [options] [SERVICE...]`
- **คำอธิบาย:** ดึง images ของบริการจาก Docker Hub หรือ registry ที่กำหนดเอง

### 8. `docker-compose push`
- **การใช้งาน:** `docker-compose push [options] [SERVICE...]`
- **คำอธิบาย:** พุช images ของบริการไปยัง Docker Hub หรือ registry ที่กำหนดเอง

### 9. `docker-compose rm`
- **การใช้งาน:** `docker-compose rm [options] [SERVICE...]`
- **คำอธิบาย:** ลบคอนเทนเนอร์ที่หยุดทำงานของบริการ

### 10. `docker-compose config`
- **การใช้งาน:** `docker-compose config [options]`
- **คำอธิบาย:** ตรวจสอบและแสดง Compose file

### 11. `docker-compose top`
- **การใช้งาน:** `docker-compose top [options] [SERVICE...]`
- **คำอธิบาย:** แสดง process ที่กำลังทำงาน

### 12. `docker-compose pause`
- **การใช้งาน:** `docker-compose pause [SERVICE...]`
- **คำอธิบาย:** หยุดคอนเทนเนอร์ที่กำลังทำงานของบริการ

### 13. `docker-compose unpause`
- **การใช้งาน:** `docker-compose unpause [SERVICE...]`
- **คำอธิบาย:** ดำเนินการคอนเทนเนอร์ที่หยุดไว้ของบริการ

### 14. `docker-compose restart`
- **การใช้งาน:** `docker-compose restart [options] [SERVICE...]`
- **คำอธิบาย:** เริ่มต้นบริการที่หยุดทำงานและทำงานอีกครั้ง

### 15. `docker-compose version`
- **การใช้งาน:** `docker-compose version [options]`
- **คำอธิบาย:** แสดงข้อมูลเวอร์ชันของ Docker-Compose

### 16. `docker-compose create`
- **การใช้งาน:** `docker-compose create [options] [SERVICE...]`
- **คำอธิบาย:** สร้างคอนเทนเนอร์ของบริการโดยไม่เริ่มต้นคอนเทนเนอร์เหล่านั้น

### 17. `docker-compose start`
- **การใช้งาน:** `docker-compose start [SERVICE...]`
- **คำอธิบาย:** เริ่มต้นคอนเทนเนอร์ที่มีอยู่สำหรับบริการ

### 18. `docker-compose stop`
- **การใช้งาน:** `docker-compose stop [options] [SERVICE...]`
- **คำอธิบาย:** หยุดคอนเทนเนอร์ที่กำลังทำงานโดยไม่ลบคอนเทนเนอร์เหล่านั้น
