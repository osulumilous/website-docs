---
title: "ลงใบ Certificate เอง"
reference_version: e9d09b54391383cc05c872daeb34f543
---
ถ้าหากว่ามีปัญหาจากการเชื่อมต่อ Server หรือว่า Switcher มีปัญหาเกี่ยวกับการลงใบรับรอง ลองอ่านได้จากที่นี่

### Instructions
- อย่างแรก โหลดใบรับรองจาก [ที่นี่](https://cdn.discordapp.com/attachments/685761830223872040/697367968589545512/cert.crt)
- หลังจากนั้นเปิด **certificate.cer**
- กด **Install certificate...**
- กด **Next**
- เลือก **Place all certificates in the following store** (second option), then กด **Browse...**
- จะมีหน้าต่างใหม่ขึ้นมา ให้เลือก **Trusted root certification authorities** แล้วกด **Ok**
- กด **Next**
- กด **Finish**

### วิธีการทดสอบใบรับรอง
หลังจากลงใบรับรองเรียบร้อยแล้ว สามารถลองได้จากการทดลองต่อไปนี้  

- เปิดตัวสลับเซิพเวอร์แล้วกด **ตรวจสอบ**.  
- หลังจากนั้นอีกแปปนึงจะเห็นช่อง "การเชื่อมต่อไปยังเซิพเวอร์" แล้วจะเห็นมีการรายงานมาว่า "ผ่าน" หลังจากนั้นลองเชื่อมต่อไปยัง osu!lumilous ดู  
- ถ้าหากว่าคุณได้ **CERT ERROR** ลองลงใบรับรองให้เรียบร้อยก่อนนะ **ลองอ่านข้างบน**  
- ถ้าหากว่าคุณได้ **"..."** และถ้าหากว่าไม่ได้เชื่อมต่อไปยัง osu!lumilous ปิดหน้าต่างการตรวจสอบแล้วกดที่ **สลับไปยังเซิพเวอร์ osu!lumilous** แล้วลองอีกครั้ง  

### ทุกอย่างมีปัญหา?
คุณลองลบใบรับรองของ *ppy.sh แล้วลองลงใบรับรองขึ้นมาใหม่โดยติดตามจากข้างล่างนี้:

- กด **Win+R**  
- พิมพ์ `mmc certmgr.msc` ใน run แล้วกด **enter** เพื่อเปิด Certificate Manager  
- เลือก **Intermediate Certification Authorites** ทางซ้าย
- เลือก **Certificates** ทางขวา
- คุณจะเห็น **[*ppy.sh](https://i.imgur.com/EL6jLZC.png)** จากใน list แล้ว **คลิกขวา** แล้วกด **Delete**  
- เลือก all the positive options (Ok/Yes etc)  
- เปิด Switcher ใหม่แล้วกด **ตรวจสอบ** แล้วเลือก **ติดตั้งใบรับรอง** หลังจากนั้นกด **Yes**  
- กด **Test connection** แล้วจะเห็นคำว่า "ผ่าน" สำหรับทุก Domain  

**ถ้ายังมีปัญหาให้ลองเปิดด้วย Run as Admin ดู**
