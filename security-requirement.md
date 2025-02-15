# OWASP Application Security Verification Standard

**2.8.1 One Time Verifier**

Detail : Verify that time-based OTPs have a defined lifetime before expiring

**Chat-GPT**
> ตรวจสอบให้แน่ใจว่า OTP มีระยะเวลาที่กำหนด และหมดอายุเมื่อครบกำหนด เพื่อป้องกันการใช้ซ้ำและเพิ่มความปลอดภัย

**Gemini**
> ต้องตรวจสอบว่า OTPs แบบอิงตามเวลามีอายุการใช้งานที่จำกัดก่อนหมดอายุ เพื่อความปลอดภัย 
 ทำไมต้องตรวจสอบ OTP ต้องหมดอายุ เพื่อป้องกันการนำ OTP ที่ถูกขโมยไปใช้ซ้ำ

**Summary**
> ตรวจสอบว่า OTP ที่สร้างตามเวลา (TOTP) มีอายุการใช้งานที่กำหนด เช่น 30 หรือ 60 วินาที และหมดอายุเมื่อครบกำหนด เพื่อป้องกันการใช้รหัสซ้ำ   ลดความเสี่ยงจากการดักจับ และเพิ่มความปลอดภัยในการยืนยันตัวตน หรือ ป้องกันการโดนขโมย OTPs จากผู้ประสงค์ร้าย :D

**Member**

1. [Nakorn Tungprapaporn](https://taedate.github.io/boardgame)
2. [Supakrit Somritjinda](https://jekoflash.github.io/boardGame)