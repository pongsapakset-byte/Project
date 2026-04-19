# 🏨 Sripatum Luxury Hotel Management System
> ระบบจองโรงแรมระดับหรู (Luxury Experience) พร้อม Dashboard จัดการข้อมูลแบบ Real-time

ดูโปรเจกต์จริงได้ที่นี่: [**Live Demo**](https://pongsapakset-byte.github.io/Project/)

---

## 📝 เกี่ยวกับโปรเจกต์ (About This Project)
โปรเจกต์นี้เป็นการพัฒนา Full-stack Web Application สำหรับธุรกิจโรงแรม โดยเน้นความสวยงามระดับพรีเมียม (Luxury Dark Theme) และความสามารถในการจัดการข้อมูลจองห้องพักผ่านระบบ Cloud โดยตรง

### 🏗️ โครงสร้างระบบ
1. **Customer Interface (index.html):** - ระบบเลือกห้องพัก (Standard, Deluxe, Suite)
   - ฟอร์มกรอกข้อมูลการจอง พร้อมคำนวณราคาสุทธิอัตโนมัติ
   - ดีไซน์แบบ Glassmorphism และ Responsive รองรับมือถือ 100%
2. **Admin Management (admin.html):**
   - ระบบ Login ป้องกันความปลอดภัยสำหรับเจ้าหน้าที่
   - Dashboard แสดงรายการจองทั้งหมดแบบ Real-time
   - สรุปยอดรายได้รวม (Total Revenue) และจัดการสถานะการจอง (Confirm/Delete)

---

## 🛠️ เทคโนโลยีที่ใช้ (Tech Stack)

| ส่วนงาน | เทคโนโลยีที่ใช้ |
| :--- | :--- |
| **Frontend** | HTML5, CSS3 (Custom Variables), JavaScript ES6 |
| **Styling** | Bootstrap 5, FontAwesome 6, Google Fonts |
| **Database** | **Google Firebase Firestore** (Real-time Database) |
| **Auth** | Firebase Authentication |
| **Deployment** | GitHub Pages |

---

## 🚀 ฟีเจอร์ที่สำคัญ (Key Features)

- [x] **Real-time Sync:** ข้อมูลการจองอัปเดตจากหน้าเว็บถึง Admin ทันทีโดยไม่ต้องกดรีเฟรช
- [x] **Auto Calculation:** คำนวณราคามัดจำ/ยอดรวม ตามจำนวนคืนที่เข้าพักจริง
- [x] **Luxury UI/UX:** ใช้เอฟเฟกต์ Glassmorphism และ Scroll Animation (Fade-up)
- [x] **Management Logic:** ระบบ Admin สามารถกด Confirm เพื่อเปลี่ยนสถานะ หรือลบข้อมูลที่ผิดพลาดได้

---

## ⚙️ วิธีการนำไปใช้งาน (Local Setup)

1. **Clone Repository**
   ```bash
   git clone [https://github.com/Pongsapakset-byte/Project.git](https://github.com/Pongsapakset-byte/Project.git)
Firebase Configuration

ไปที่ Firebase Console

สร้างโปรเจกต์ใหม่และเปิดใช้งาน Firestore และ Authentication

นำ API Key มาใส่ในไฟล์ index.html และ admin.html ตรงส่วน const firebaseConfig

Open Project

เปิดไฟล์ index.html บน Browser เพื่อเริ่มใช้งาน

👤 ผู้จัดทำ (Author)
นาย พงศภัค เสทิน 68076288
นาย บรรณวัชร บุญเปลี่ยม 6808311
นางสาว เรืองทอง สุดโต 68077841

สถาบัน: มหาวิทยาลัยศรีปทุม (Sripatum University)
