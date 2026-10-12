# NORMAL GitHub Pages - Ready to Upload

Apps Script URL ถูกใส่ให้แล้ว:
https://script.google.com/macros/s/AKfycbwmBlGIIJ_HMcMSloYrCKF3-2g18fAwAni41jxi86EaqfHEYt7x3j87ly8MLHrmddyu/exec

## ขั้นตอนใช้งาน

### 1. อัปเดต Apps Script Backend
1. เปิด Google Sheet ของ NORMAL
2. Extensions > Apps Script
3. เปิดโฟลเดอร์ `apps-script-backend`
4. Copy `Code.gs` ทั้งหมด
5. ไปแทน `Code.gs` เดิมใน Apps Script
6. Save
7. Deploy > Manage deployments > Edit
8. Version > New version
9. Deploy

### 2. ทดสอบ Apps Script ก่อน
เปิด:
https://script.google.com/macros/s/AKfycbwmBlGIIJ_HMcMSloYrCKF3-2g18fAwAni41jxi86EaqfHEYt7x3j87ly8MLHrmddyu/exec

เช็กว่า:
- MLR แสดง
- ตาราง Rate แสดงครบ
- ลูกค้าใหม่ & TOP UP B03
- TOP UP B01 & B02
- Single rate
- Calculator ทำงาน

### 3. สร้าง GitHub Repo ใหม่
แนะนำชื่อ:
`SME-FREEDOM-NORMAL-WEB`

### 4. Upload ไฟล์ Root
- `index.html`
- `.nojekyll`
- `README.md`
- `INSTALL_GUIDE_TH.md`

### 5. Commit message
`Deploy SME Freedom NORMAL Web V5`

### 6. เปิด GitHub Pages
Settings > Pages
- Source: Deploy from a branch
- Branch: main
- Folder: / (root)

### 7. ทดสอบหน้า GitHub Pages
ต้องเห็น:
- MLR ไม่เป็น -
- Rate Table ครบทุก Section
- Calculator ทำงาน
- Payment Schedule แสดง Desktop / Mobile

## ในอนาคต
ถ้าเปลี่ยนแค่ MLR / Rate ใน Google Sheet:
- แก้ Google Sheet
- Refresh GitHub Pages

ไม่ต้อง Upload GitHub ใหม่ ถ้า Logic/UI ไม่เปลี่ยน
