---
title: "คำสั่งบอท"
old_id: 4
---
และนี่คือคำสั่งที่สามารถใช้ได้ในเซิพนี้ ลองอ่านจากข้างล่างดู  

### คำสั่งทั่วไป
- `!roll` - สุ่มเลขอะไรก็ได้ 
- `!roll num` - สุ่มเลขกลับจาก 0 ถึงตัวเลข  
- `!help` - แสดงการช่วยเหลือ (การใช้บอทอ่ะแหล่ะ)
- `!pp [mode]` - โชว์ระดับภีภีปัจจุบัน เมื่อที่ `โหมด` นั้นตรง บอทจะทำการบอกปริมาณ PP ในโหมดเกมนั้นๆ (คุณสามารถใช้ได้แค่ `std/taiko/ctb/mania`) บอทจะบอกจำนวน PP ในโหมดนั้น **คำสั่งนั้นใช้กับ PMs ได้เท่านั้น**
- `!update` - อัพเดทบีตแมป ควรใช้ถ้าหากคุณต้องการโหลด beatmap จาก osu!direct แล้วมีการไม่ทันอัพเดทล่าสุดของเพลงนั้นๆ หรือถ้าหากว่าไม่สามารถโหลดได้จาก osu!direct

### คำสั่ง Faq
- `!faq rules`  
- `!faq swearing`  
- `!faq spam`  
- `!faq offend`  
- `!faq english`  
- `!faq github`  
- `!faq discord`  
- `!faq blog`  
- `!faq changelog`  
- `!faq status`  

### คำสั่งที่เหมือนกับ Tillerino
บอทในเซิพเวอร์นั้นมีคำสั่งที่คล้ายๆกับ Tillerino คำสั่งนั้นจะทำงานในเมื่อที่คุณใช้คำสั่งกับบอทโดยการทักหาส่วนตัว จำไว้เสมอว่าระบบ PP นั้นใช้ได้กับ osu!standard และ osu!mania (ยังไม่สามารถแนะนำเพลงได้)

- `/np` - แสดง PP สำหรับเพลงที่กำลังเล่น (ใช้ได้เฉพาะเพลงของ osu! standard)  
- `!last` - แสดงข้อมูล (และ PP ที่เพิ่มขึ้นมาเมื่อที่เป็นคะแนนของ osu! standard) ที่เกี่ยวกับคะแนนที่เล่นล่าสุด  
- `!with <mods>` - แสดง PP สำหรับเพลงและ Mods ที่ขอเพิ่มเติม โดยที่รองรับนั้นสามารถใช้ `NF, EZ, HD, HR, DT, HT, NC, FL, SO.` แต่ไม่สามารถเว้นวรรคเพื่อหลาย Mods ได้นะ (เช่น: `!with HDHR`)

### คำสั่งแอดมิน
- `!system restart` - Restart เซิพเวอร์ใหม่โยที่คนอื่นจะหลุดออกจากเซิพเวอร์
- `!system status` - แสดงสถานะ Server
- `!system reload` - โหลดการตั้งค่าก่อนของ Bancho (จริงๆก็ทำได้จากระบบหลังบ้านเหมือนกัน)  
- `!system maintenance on/off` - เปิดปิดโหมดปรับปรุงเซิพเวอร์
- `!moderated on/off` - เปิดปิดโหมดการควบคุมแชทสำหรับช่องนั้นๆ  
- `!silence <username> <count> <unit (s/m/h/d)> <reason>` - ใบ้ผู้เล่น  
- `!removesilence <target>` - ลบใบ้ออกจากผู้เล่น
- `!kick <username>` - เตะผู้เล่นออกจากเซิพเวอร์  
- `!ban <username>` - แบนแล้วเตะออกจากเซิพ 
- `!unban <username>` - ปลดแบน
- `!restrict <username>` - จำกัดใครซักคน  
- `!unrestrict <username>` - ปลดการจำกัดผู้เล่น  
- `!fokabot reconnect` - เชื่อมต่อบอทใหม่ (ถ้าหากไม่เห็นออนอยู่ในเซิพเวอร์)  
- `!alert <message>` - ส่งการแจ้งเตือนไปยังผู้เล่นทุกคน  
- `!alertuser  <username> <message>` - ส่งการแจ้งเตือนไปยังผู้เล่น