# 🚀 MoneyFlow - Web App บันทึกรายรับรายจ่าย สไตล์ GenZ

## 📋 ภาพรวมโปรเจกต์
เว็บแอปพลิเคชันสำหรับบันทึกรายรับรายจ่าย ออกแบบมาเพื่อวัยรุ่น GenZ โดยเฉพาะ ด้วย UI/UX ที่ทันสมัย สวยงาม และใช้งานง่าย

---

## ✨ ฟีเจอร์หลัก

### หน้าเว็บที่พัฒนาแล้ว
1. **หน้าแรก (index.html)** 
   - Hero Section พร้อม Animation
   - แสดงฟีเจอร์เด่นของแอป
   - สถิติผู้ใช้งาน
   - Call-to-Action

2. **หน้าเข้าสู่ระบบ (login.html)**
   - ฟอร์ม Login สวยงาม
   - รองรับ Social Login (Google, Facebook)
   - Remember Me
   - Forgot Password Link

3. **หน้าสมัครสมาชิก (register.html)**
   - ฟอร์มลงทะเบียนครบถ้วน
   - Validation พื้นฐาน
   - ยอมรับเงื่อนไขการใช้งาน
   - Social Register

4. **หน้าแดชบอร์ด (dashboard.html)**
   - สรุปยอดคงเหลือ รายรับ รายจ่าย
   - ตารางรายการล่าสุด
   - สถิติการใช้จ่ายตามหมวดหมู่
   - เป้าหมายการออม

---

## 🎨 Design Highlights

### สีและ Gradient
- **Primary:** Purple to Blue (#667eea → #764ba2)
- **Secondary:** Pink to Red (#f093fb → #f5576c)
- **Accent:** Cyan to Blue (#4facfe → #00f2fe)
- **Success:** Green (#00d9a5)
- **Danger:** Red (#fc8181)

### Typography
- **Thai Font:** Kanit
- **English Font:** Poppins

### Visual Effects
- ✨ Glassmorphism Design
- 🎭 Smooth Animations & Transitions
- 🌈 Gradient Text & Buttons
- 💫 Floating Cards Animation
- 📱 Responsive Design
- 🎯 Hover Effects

---

## 📁 โครงสร้างไฟล์

```
/workspace
├── Skills.md              # คู่มือทักษะที่ต้องเตรียม
├── README.md              # ไฟล์นี้
└── src/
    ├── index.html         # หน้าแรก
    ├── login.html         # หน้าเข้าสู่ระบบ
    ├── register.html      # หน้าสมัครสมาชิก
    ├── dashboard.html     # หน้าแดชบอร์ด
    ├── styles.css         # CSS ทั้งหมด
    └── script.js          # JavaScript
```

---

## 🛠️ การติดตั้งและรันโปรเจกต์

### วิธีที่ 1: เปิดด้วย Browser โดยตรง
```bash
cd /workspace/src
# แล้วเปิดไฟล์ index.html ด้วย browser ของคุณ
```

### วิธีที่ 2: ใช้ Python HTTP Server
```bash
cd /workspace/src
python3 -m http.server 8000
# เปิด browser ที่ http://localhost:8000
```

---

## 🎯 การทดสอบการทำงาน

### ทดสอบการลงทะเบียน
1. เปิด `register.html`
2. กรอกข้อมูลในฟอร์ม
3. กดปุ่ม "สร้างบัญชีฟรี"
4. ระบบจะ redirect ไป dashboard อัตโนมัติ

### ทดสอบการเข้าสู่ระบบ
1. เปิด `login.html`
2. กรอก email และ password
3. กดปุ่ม "เข้าสู่ระบบ"
4. ระบบจะ redirect ไป dashboard อัตโนมัติ

---

## 📚 Skills ที่ต้องเรียนรู้

ดูรายละเอียดเพิ่มเติมได้ที่ [`Skills.md`](./Skills.md)

---

**Made with ❤️ for GenZ by MoneyFlow Team**
💸 *จัดการเงินง่ายๆ สไตล์วัยรุ่น!*
