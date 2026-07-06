# 🖥️ [PrimePC] : เว็บไซต์จำหน่ายอุปกรณ์คอมพิวเตอร์

> โครงงานพัฒนาเว็บไซต์อีคอมเมิร์ซสำหรับจำหน่ายอุปกรณ์คอมพิวเตอร์ (คล้าย ihavecpu.com)
> จัดทำสำหรับรายวิชา **CSI204 : Digital Platform for Software Development**

---

## 📌 เกี่ยวกับโครงงาน

[PrimePC] เป็นเว็บไซต์ร้านค้าออนไลน์สำหรับจำหน่ายอุปกรณ์คอมพิวเตอร์ เช่น CPU, Mainboard,
การ์ดจอ, RAM, SSD/HDD, พาวเวอร์ซัพพลาย, เคส, จอมอนิเตอร์ และอุปกรณ์เสริมอื่น ๆ โดยระบบรองรับ
การเลือกซื้อสินค้า ตะกร้าสินค้า ระบบสมาชิก การชำระเงิน และการติดตามสถานะคำสั่งซื้อ

## ✨ ฟีเจอร์หลัก (Features)

| ฟีเจอร์ | รายละเอียด |
|---|---|
| 🛒 แคตตาล็อกสินค้า | แสดงรายการสินค้าตามหมวดหมู่ (CPU, GPU, Mainboard, RAM, Storage ฯลฯ) พร้อมค้นหา/กรองสเปก |
| 👤 ระบบสมาชิก | สมัครสมาชิก / เข้าสู่ระบบ / จัดการโปรไฟล์ |
| 🛍️ ตะกร้าสินค้า | เพิ่ม/ลบ/แก้ไขจำนวนสินค้าในตะกร้าก่อนชำระเงิน |
| 💳 ระบบชำระเงิน | รองรับบัตรเครดิต / โอนเงิน / PromptPay ผ่าน Payment Gateway |
| 🧩 ตัวช่วยเช็คสเปคเข้ากันได้ | ตรวจสอบความเข้ากันได้ของอุปกรณ์ก่อนสั่งซื้อ (เช่น Socket CPU กับ Mainboard) |
| 📦 ติดตามคำสั่งซื้อ | ดูสถานะคำสั่งซื้อ/การจัดส่งแบบเรียลไทม์ |
| 🛠️ Admin Dashboard | จัดการสินค้า สต๊อก คำสั่งซื้อ และสมาชิกฝั่งผู้ดูแลระบบ |

## 🧱 เทคโนโลยีที่ใช้ (Tech Stack)

| ส่วนงาน | เทคโนโลยีที่เลือกใช้ |
|---|---|
| Frontend | React.js / Next.js, Tailwind CSS |
| Backend | Node.js + Express.js (REST API) |
| Database | MySQL / PostgreSQL (ข้อมูลธุรกรรม), Redis (Cache/Session) |
| Payment Gateway | Omise / 2C2P / PromptPay |
| Version Control | Git + GitHub + Sourcetree |
| Deployment | GitHub Pages (เอกสารประกอบ) / Cloud Hosting (ตัวระบบจริง) |

## 📂 โครงสร้างโปรเจกต์ (Repository Structure)

```
[PrimePC]/
├── README.md                  # เอกสารแนะนำโครงงาน (ไฟล์นี้)
├── index.html                 # หน้าเว็บสำหรับ GitHub Pages (แสดงเอกสารประกอบ)
├── docs/
│   ├── analysis-design.md     # เอกสาร Analysis & Design (SRS)
│   └── architecture.mmd       # System Architecture Diagram (Mermaid)
└── src/                       # (โค้ดของระบบจริง เพิ่มเติมภายหลัง)
```

## 🚀 การติดตั้งและใช้งาน (Getting Started)

```bash
# 1. Clone repository
git clone https://github.com/<username>/[PrimePC].git
cd [PrimePC]

# 2. ติดตั้ง dependencies (ฝั่ง Frontend/Backend ตามที่พัฒนาจริง)
npm install

# 3. รันโปรเจกต์
npm run dev
```

## 📑 เอกสารประกอบโครงงาน

- 📋 [Analysis & Design (SRS)](docs/analysis-design.md)
- 🗺️ [System Architecture Diagram](docs/architecture.mmd)
- 🌐 GitHub Pages: `https://<username>.github.io/[PrimePC]/`

## 👨‍💻 ผู้จัดทำ

[ธเนศวร ศรีทับทิม] | [67157971] 

---

📘 จัดทำเพื่อประกอบการเรียนวิชา **CSI204 ดิจิทัลแพลตฟอร์มสำหรับพัฒนาซอฟต์แวร์**
