# QR Code Generator

เว็บ Static สำหรับสร้าง QR Code ใช้งานบน GitHub Pages

## Features

- สร้าง QR จาก URL หรือข้อความ
- QR ถูกสร้างใน Browser
- เลือกขนาด 256 / 512 / 1024 px
- Error Correction L / M / Q / H
- Paste จาก Clipboard
- Download PNG
- Copy QR Code
- Responsive รองรับมือถือ

## Deploy บน GitHub Pages

1. สร้าง Repository ใหม่บน GitHub
2. Upload `index.html`, `.nojekyll` และ `README.md`
3. ไปที่ **Settings**
4. เลือก **Pages**
5. Build and deployment:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
6. กด **Save**

URL จะมีรูปแบบ:

`https://USERNAME.github.io/REPOSITORY/`

## Privacy

เว็บไซต์ไม่มี Database และไม่มี backend สำหรับบันทึกข้อความที่ผู้ใช้กรอก

QR Code ถูกสร้างด้วย JavaScript ภายใน Browser

## External dependency

หน้าเว็บโหลด `QRCode.js` จาก cdnjs เพื่อใช้ในการสร้าง QR Code
