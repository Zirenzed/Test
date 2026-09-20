# ก๊อก ก๊อก (แมวดำ)

หน้าเว็บเดียว (`index.html`) ไม่ต้อง build เปิดได้ทั้งคอมและมือถือ

## ขึ้น GitHub Pages
1. สร้าง repo ใหม่บน GitHub (เช่นชื่อ `knock-knock`) ตั้งเป็น Public
2. อัปโหลด `index.html` (Add file > Upload files) แล้ว Commit
3. Settings > Pages > Source: Deploy from a branch > Branch: `main` / `(root)` > Save
4. รอ 1-2 นาที ลิงก์จะเป็น `https://<ชื่อ-github>.github.io/<ชื่อ-repo>/`

## หรือใช้ git
```
git init
git add index.html README.md
git commit -m "knock knock"
git branch -M main
git remote add origin https://github.com/<ชื่อ-github>/<ชื่อ-repo>.git
git push -u origin main
```
