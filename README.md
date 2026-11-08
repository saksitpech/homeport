# Gott Portfolio Website

เว็บไซต์ Portfolio 3 หน้า สร้างด้วย HTML, CSS และ JavaScript แบบไม่ใช้ framework

## โครงสร้างไฟล์

```text
gott-portfolio-github/
├── index.html
├── about.html
├── mywork.html
├── style.css
├── script.js
└── assets/
    └── gott-profile.jpg
```

## เปิดใช้งานในเครื่อง
เปิด `index.html` ด้วย Browser หรือใช้ VS Code + Live Server

## Deploy ด้วย GitHub Pages
1. สร้าง GitHub repository ใหม่
2. อัปโหลดไฟล์และโฟลเดอร์ทั้งหมด โดยให้ `index.html` อยู่ที่ root ของ repository
3. เข้า Settings → Pages
4. ใน Build and deployment เลือก Deploy from a branch
5. เลือก branch `main` และ folder `/ (root)` แล้วกด Save
6. รอ GitHub สร้างเว็บไซต์ จากนั้นเปิด URL ที่ GitHub Pages แสดงให้

หมายเหตุ: ลิงก์ CSS, JavaScript และรูปภาพใช้ relative path เพื่อให้ทำงานบน GitHub Pages รวมถึง repository ที่เผยแพร่จาก subpath ได้
