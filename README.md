# *เว็บไซต์อร่อยบอกต่อ*
เป็นเว็บไซต์แนะนำร้านอาหาร

## สารบัญ Table of Contents
* ขั้นตอนการติดตั้ง
* วิธีการใช้งาน

# ขั้นตอนในการติดตั้ง
1. เริ่มติดตั้ง node.js การติดตั้ง Node.js มีขั้นตอนพื้นฐานดังนี้
* ดาวน์โหลด Node.js: เข้าไปที่เว็บไซต์หลักของ Node.js ที่ nodejs.org และดาวน์โหลดตัวติดตั้งสำหรับระบบปฏิบัติการที่เหมาะสม (Windows, macOS, หรือ Linux).
* ติดตั้ง Node.js: เมื่อดาวน์โหลดเสร็จสิ้นแล้ว ให้เปิดไฟล์ติดตั้งที่ดาวน์โหลดขึ้นมา และทำการติดตั้งตามขั้นตอนที่แสดงบนหน้าต่างติดตั้ง
* ตรวจสอบการติดตั้ง: เมื่อติดตั้งเสร็จสมบูรณ์ คุณสามารถตรวจสอบว่า Node.js ถูกติดตั้งได้อย่างถูกต้องหรือไม่โดยเปิด Command Prompt (Windows) หรือ Terminal (macOS, Linux) และพิมพ์คำสั่งต่อไปนี้
`node -v เมื่อทำการติดตั้ง Node.js แล้ว คำสั่งนี้จะแสดงเวอร์ชั่นขึ้นมา`
2. ทำการติดตั้ง git โดยไปที่ https://git-scm.com/downloads เลือก เวอร์ชันที่รองรับ กับระบบปฎิบัติการ
3. ทำการติดตั้ง visual studio code
4. ทำการ clone repository
* Clone ส่วน Frontend :
* คัดลอกได้ที่นี่ : 
จากนั้นทำการเข้าไปใน vs code แล้วเปิด terminal และทำการ clone ไฟล์มาจาก URL ดังกล่าว จากนั้นทำการให้ path ที่เราอยู่คือ web-deverlopment ตาม folder ที่โคลนมา จากนั้นทำการ ติดตั้ง react จากคำสั่ง npm install react react-dom จากนั้นทำการ build run ได้ด้วยคำสั่ง npm start เพื่อนรันหน้าเว็บใส่
`npm i react-router-dom@6.21.3 ลองใส่คำสั่งนี้หากไม่สามารถไปหน้าอื่นได้ จากนั้นหลังจาก Run Code เสร็จขั้นตอนต่อไปให้เข้าหน้านี้`
* Clone ส่วน Backend :
`จากนั้นให้ไปนำ Databases จากการเข้าหน้านี้ https://github.com/Bananakikkok/aroiboktor-sql`
* จากนั้นทำการ download XAMPP และเมื่อดาวโหลดและทำการติดตั้งแล้วเสร็จ ทำการกดปุ่ม start ตรงช่อง mysql เพื่อใช้งาน ฐานข้อมูลในที่นี้ ทางผู้จัดทำได้ทำการใช้ Heidi ในการจัดการข้อมูลต่างๆใน MariaDB จากนั้นให้ นำไฟล์ sql ใน https://github.com/Bananakikkok/aroiboktor-sql สามารถทำได้ทั้ง clone และ download จากนั้นนำข้อมูลในไฟล์ที่ download ไปใส่ Heidi สามารถทำได้ โดยการเปิด cmd และ ทำการ cd..จนกว่าจะอยู่ path C: จากนั้น cd xampp, cd mysql, cd bin จากนั้นทำการ เขียนคำสั่ง mysql -u root <ตามด้วย pathที่เก็บไฟล์ BoktorSql.sql ไว้ เมื่อเข้าไปใน Heidi ทำการ ตั้ง password ใน Query จากคำสั่ง
### *ALTER USER 'root'@'localhost' IDENTIFIED BY 'test123';*
ทำการ build run แต่ละไฟล์ เริ่มต้นเปิด vscode แล้วนนำ folder ที่ได้มากจากการ clone repository  เข้า terminal และทำให้ path ไปอยู่ที่ train และทำการใช้คำสั่ง npm start เพื่อ build run api เมื่อทำการ build run เสร็จจากนั้น ไป ที่ไฟล์ ที่ clone มาจาก
