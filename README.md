# วิธีติดตั้งแอปผ่าน GitHub Pages

1. ลิงก์เว็บแอป Apps Script ถูกใส่ใน `index.html` (`var APP_URL`) แล้ว ถ้าเปลี่ยนลิงก์ภายหลังให้แก้ตรงนั้น
2. สร้าง Repository ใหม่บน GitHub (เช่น `materials-app`) แล้วอัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ขึ้นไปที่ราก (root) ของ repo:
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `icon-512-maskable.png`
3. ที่ repo เลือก **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / (root) → Save**
4. รอ 1–2 นาที จะได้ลิงก์ `https://ชื่อผู้ใช้.github.io/materials-app/`
5. ในเว็บแอป เข้า **Admin → แดชบอร์ด → "ลิงก์ติดตั้งแอป (GitHub Pages)"** วางลิงก์ข้างต้น แล้วกดบันทึก
6. ผู้ใช้มือถือ/แท็บเล็ตกด **เฟือง → ติดตั้งแอป** จะเปิดหน้า GitHub แล้วกด "ติดตั้งแอป" (iPhone: ปุ่มแชร์ → เพิ่มไปยังหน้าจอโฮม)
