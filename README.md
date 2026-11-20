# Daonuea Portfolio

พอร์ตโฟลิโอของ Thanawat Sangnon (เว็บบน GitHub Pages + Firebase สำหรับล็อกอินและเก็บข้อมูล)

## เปิดเว็บ (GitHub Pages)
Settings → Pages → Deploy from a branch → `main` / `(root)` → Save

## เปิดโหมดแก้ไขบนเว็บ (Firebase + รหัสผ่าน)
1. Firebase Console → Authentication → Sign-in method → เปิด **Email/Password** (ไม่ต้องเปิด Email link)
2. Authentication → Users → **Add user** → อีเมล `hh7uiijj@gmail.com` + ตั้งรหัสผ่านที่ต้องการ (รหัสผ่านเก็บอยู่ที่ Firebase ไม่อยู่ในโค้ด)
3. Authentication → Settings → User actions → ปิด **Enable create (sign-up)** เพื่อกันคนอื่นสมัครบัญชีเอง
4. Authentication → Settings → Authorized domains → เพิ่ม `hh7uiijj-cmd.github.io`
5. คัดลอกกฎใน `firebase-rules/firestore.rules` ไปวางที่ Firestore → Rules และ `firebase-rules/storage.rules` ไปวางที่ Storage → Rules แล้วกด Publish
6. เปิดเว็บ → ท้ายหน้ากด "หน้าต่างสำหรับแก้ไข" → ใส่รหัส → "แก้ไขพอร์ต"
