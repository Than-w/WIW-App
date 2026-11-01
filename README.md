# Ready-to-Deploy Progressive Web App (PWA)

ชุดไฟล์ PWA ที่แก้ไข Path (`./`) เรียบร้อยแล้ว สำหรับนำขึ้น GitHub Pages โดยเฉพาะ

## ไฟล์ทั้งหมดใน ZIP นี้:
1. `index.html` - หน้าแอปหลัก พร้อมระบบ UI, แท็ก Manifest และ Service Worker
2. `manifest.webmanifest` - กำหนดค่าการติดตั้งแอป (Relative path)
3. `sw.js` - เครือข่ายการจัดการแคชและการทำงานแบบออฟไลน์
4. `icon.svg` - ไอคอนแอปพลิเคชัน
5. `.gitignore` - กำหนดการข้ามไฟล์ขยะ

## วิธีใช้งาน:
1. แตกไฟล์ ZIP ทั้งหมดออกมา
2. ลากไฟล์ทั้ง 5 ไฟล์ไปวางใน GitHub Repository (วางไว้หน้าแรกสุด / Root directory)
3. เข้าไปตั้งค่า **Settings > Pages** เลือก branch `main` แล้วกด **Save**
