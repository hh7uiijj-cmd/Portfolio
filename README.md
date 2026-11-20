# Daonuea Portfolio

พอร์ตโฟลิโอของ Thanawat Sangnon (เว็บบน GitHub Pages + Firebase สำหรับล็อกอินและเก็บข้อมูล)

## เปิดเว็บ (GitHub Pages)
Settings → Pages → Deploy from a branch → `main` / `(root)` → Save

## เปิดโหมดแก้ไขบนเว็บ (Firebase)
1. สร้างโปรเจกต์ใน Firebase Console แล้วเปิด Authentication (Google), Firestore Database, Storage
2. Project settings → Your apps → เพิ่ม Web app → คัดลอก config มาใส่ใน `firebase-config.js`
3. Authentication → Settings → Authorized domains → เพิ่ม `hh7uiijj-cmd.github.io`
4. คัดลอกกฎใน `firebase-rules/firestore.rules` ไปวางที่ Firestore → Rules และ `firebase-rules/storage.rules` ไปวางที่ Storage → Rules แล้วกด Publish
5. เปิดเว็บ → ท้ายหน้ากด "เจ้าของเว็บ: เข้าสู่ระบบ" → ล็อกอินด้วยอีเมลเจ้าของ → "แก้ไขพอร์ต"

ก่อนตั้งค่า Firebase เว็บจะแสดงผลงานจาก `data.json` ได้ตามปกติ แต่แก้ไขบนเว็บไม่ได้
