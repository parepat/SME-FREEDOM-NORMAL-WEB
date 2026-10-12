# KKP SME FREEDOM NORMAL — GitHub Pages Bridge V5

ใช้สำหรับเปิด NORMAL Calculator ผ่าน GitHub Pages
โดยข้อมูล MLR / Rate Table ยังอ่านจาก Google Sheet ผ่าน Apps Script

## ก่อน Upload
ต้องใส่ NORMAL Apps Script `/exec` URL ใน `index.html`

หา:
```js
const APPS_SCRIPT_API_URL =
  'PASTE_NORMAL_APPS_SCRIPT_EXEC_URL_HERE';
```

แล้วเปลี่ยนเป็น:
```js
const APPS_SCRIPT_API_URL =
  'https://script.google.com/macros/s/XXXXXXXX/exec';
```

## Apps Script Backend
นำไฟล์ใน `apps-script-backend` ไปแทน Apps Script Project เดิม แล้ว Deploy New Version

## GitHub Pages
Upload ที่ root:
- `index.html`
- `.nojekyll`
- `README.md`

Settings > Pages:
- Source: Deploy from a branch
- Branch: main
- Folder: / (root)

## NORMAL V5 รองรับ
- ลูกค้าใหม่ & TOP UP B03
- TOP UP B01 & B02
- Single rate
- MLR จาก C2
- หลาย Section
- ตารางผ่อน Desktop / Mobile
