#1.  เตรียมข้อมูล
- npm i
- npm run publish
#2. เปิด http server (Run Http Server)
- npm run run-server
#3. Run ทดสอบ (Dev Mode (current version 1.0.0))
- copy dist จาก project ออกไป install ก่อน 

#4. Publish exe version ใหม่ขึ้น http-server (แก้ไข version ที่ file package.json เป็น version ใหม่ 1.0.1)
- npm run publish

- http://localhost:8080/

#5. ทดสอบ 
- เปิด Desktop App ที่ Install ไว้ในข้อ 3 อีกครั้ง จะทำการ Download Version 1.0.1 ใหม่มาไว้ 
- แล้วจะขึ้น Popup ให้ผู้ใช้งานเลือกว่าจะติดตั้ง App หรือไม่
- ถ้าเลือกติดตั้งจะทำการ Install Desktop App ใหม่แล้ว Restart Desktop App อัตโนมัติ

#อ้างอิง
- https://medium.com/@anuchamaitripirom/auto-update-%E0%B8%9A%E0%B8%99-desktop-application-%E0%B8%81%E0%B8%B1%E0%B8%9A-electron-updater-de67a04d4ece


#ข้อพึงระวัง
- ** ข้อควรระวัง "http-server": "^0.9.0" version นี้ Start ใน Window10 ได้  Version ^0.11.1" Start ไม่ได้