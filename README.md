# 🎌 ikigai — AI Coach หาเส้นทางชีวิต

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green)]()
[![Category](https://img.shields.io/badge/category-life--coaching-orange)]()
[![Language](https://img.shields.io/badge/language-Thai-brightgreen)]()
[![Files](https://img.shields.io/badge/files-15-orange)]()

> **Ikigai (生き甲斐)** — "เหตุผลที่ตื่นขึ้นมาทุกเช้า"  
> จุดตัดของ **สิ่งที่ชอบ ❤️ · สิ่งที่เก่ง ✅ · สิ่งที่โลกต้องการ 🌍 · และสิ่งที่ทำเงินได้ 💰**

Skill นี้ใช้กับ [opencode](https://opencode.ai), Claude Code, Cursor หรือ AI agent ที่รองรับ custom skills เหมาะสำหรับคนไทยที่รู้สึกหลงทาง เบื่อชีวิต หรืออยากหาทางเดินที่ใช่

---

## 📖 สารบัญ

- [🧠 Ikigai คืออะไร](#-ikigai-คืออะไร)
- [🚀 วิธีใช้](#-วิธีใช้)
- [🗺️ 5 ขั้นตอนค้นหา Ikigai](#-5-ขั้นตอนค้นหา-ikigai)
- [📦 สิ่งที่ได้จาก skill นี้](#-สิ่งที่ได้จาก-skill-นี้)
- [📂 โครงสร้างโฟลเดอร์](#-โครงสร้างโฟลเดอร์)
- [👤 ตัวอย่างจริง](#-ตัวอย่างจริง)
- [🔗 ระบบที่เกี่ยวข้อง](#-ระบบที่เกี่ยวข้อง)
- [📥 ติดตั้ง](#-ติดตั้ง)
- [📄 License](#-license)

---

## 🧠 Ikigai คืออะไร

Ikigai เป็นปรัชญาญี่ปุ่นจากโอกินาว่า — หนึ่งใน Blue Zones ที่ประชากรอายุยืนที่สุดในโลก มันคือ **จุดตัดของ 4 วงกลม** ที่เมื่อคุณหามันเจอ คุณจะตื่นขึ้นมาทุกเช้าด้วยความรู้สึกว่า "ชีวิตนี้มี meaning"

| วงกลม | คำถามที่ต้องตอบ | วงซ้อน = |
|-------|----------------|----------|
| ❤️ **Love** — อะไรที่ชอบทำ | "อะไรรทำให้ลืมเวลา?" | Love + Good At → **Passion** |
| ✅ **Good At** — อะไรที่ถนัด | "คนอื่นมักชมเราเรื่องอะไร?" | Good At + Paid For → **Profession** |
| 🌍 **World Needs** — โลกต้องการอะไร | "ปัญหาอะไรที่อยากแก้?" | World Needs + Love → **Mission** |
| 💰 **Paid For** — อะไรทำเงินได้ | "คนยอมจ่ายเงินเพื่ออะไร?" | World Needs + Paid For → **Vocation** |
| | **ทั้ง 4 วงกลม** | **→ IKIGAI** |

👉 ดู Venn diagram แบบภาพได้ที่ [`assets/ikigai-map.svg`](assets/ikigai-map.svg)

---

## 🚀 วิธีใช้

บอก AI agent ของคุณตามนี้:

### พื้นฐาน — ไม่มีข้อมูลอะไรเลย

```
อ่าน ikigai/SKILL.md แล้วช่วยหา Ikigai ให้หน่อย
```

### มีข้อมูลเบื้องต้น

```
อ่าน ikigai/SKILL.md แล้วช่วยหา Ikigai ให้หน่อย
ผมอายุ 28 เป็นโปรแกรมเมอร์ แต่รู้สึกเบื่อ
ไม่รู้ว่าชีวิตควรไปทางไหน
```

### อยากให้ช่วยแค่สะท้อนตัวเอง (Phase 1-2)

```
อ่าน ikigai/SKILL.md แล้วช่วยถามคำถามสะท้อนตัวเอง
ผมอายุ 35 เป็นผู้จัดการ รู้สึก burnout
อยากรู้ว่าจริงๆ แล้วชอบอะไร
```

### Follow-up — หลังทำ Experiment

```
อ่าน ikigai/SKILL.md แล้วช่วยเช็คความคืบหน้า
สัปดาห์ที่แล้วลองสอนเพื่อนใช้ Notion แล้วสนุกดี
อยากปรับ Ikigai Statement
```

---

## 🗺️ 5 ขั้นตอนค้นหา Ikigai

| Step | ชื่อ | เวลา | กิจกรรมหลัก | ผลลัพธ์ |
|------|------|------|------------|--------|
| **1** | 🪞 **สะท้อนอดีต** | 1-2 วัน | ทบทวนช่วงที่มีความสุข vs พลังงานหมด ใช้คำถาม 40+ ข้อจาก `scripts/self-reflections.md` | รู้จักตัวเองมากขึ้น — ค่านิยม, จุดแข็ง, ความสนใจ |
| **2** | 🎯 **หา Ikigai** | 1 วัน | ใส่ข้อมูลใน 4 วงกลม (ใช้ `template/ikigai-map.md`) → หาจุดตัด | Ikigai Statement ร่างแรก |
| **3** | 🧪 **ทดสอบ** | 14 วัน | เลือก 1 Mini-experiment (จาก `scripts/mini-experiments.md`) สังเกตว่าสนุกมั้ย ได้ผลมั้ย | ข้อมูลจริงว่าใช่หรือเปล่า |
| **4** | 🔄 **สังเคราะห์** | 1 วัน | ปรับ Ikigai Statement ตามผล experiment | Ikigai Statement ฉบับจริง |
| **5** | 🚀 **ลงมือ 90 วัน** | 90 วัน | วางแผน 3 Milestones + Weekly check-in (ใช้ `template/action-plan-90.md`) | ทำให้ Ikigai เป็นจริง |

---

## 📦 สิ่งที่ได้จาก skill นี้

| หมวด | ไฟล์ | จำนวน | ใช้ตอนไหน |
|------|------|-------|----------|
| ❓ **คำถามสะท้อน** | `scripts/self-reflections.md` | 40+ ข้อ 4 หมวด | Phase 1 |
| 🧪 **Mini-experiments** | `scripts/mini-experiments.md` | 10+ ไอเดียทดสอบ | Phase 3 |
| 🧱 **Obstacle buster** | `scripts/obstacle-buster.md` | 10 อุปสรรค + วิธีฝ่า | Phase 5-6 |
| 🗺️ **Ikigai map template** | `template/ikigai-map.md` | 1 blank venn diagram | Phase 2 |
| 📝 **Ikigai statement** | `template/ikigai-statement.md` | 1 template | Phase 2, 4 |
| 📅 **Action plan 90 วัน** | `template/action-plan-90.md` | 1 template + check-in | Phase 5 |
| 📖 **Ikigai deep-dive** | `reference/ikigai-deep-dive.md` | 1 หลักการละเอียด | ต้องการความเข้าใจลึก |
| 🔄 **Frameworks อื่น** | `reference/other-frameworks.md` | Wheel of Life, StrengthsFinder ฯลฯ | มุมมองเสริม |
| ⚡ **Cheatsheet** | `reference/cheatsheet.md` | 1 หน้าสรุป | อ่านเร็ว |
| 📊 **Venn diagram** | `assets/ikigai-map.svg` | 1 ภาพ | ประกอบความเข้าใจ |
| 👤 **ตัวอย่างจริง** | `example/` | 3 กรณี | ดูแนวทาง |

---

## 📂 โครงสร้างโฟลเดอร์

```
ikigai/
│
├── SKILL.md              ← 🧠 Entry point หลัก — ให้ AI agent อ่าน
│
├── workflow/
│   └── workflow.md       ← 5 ขั้นตอนค้นหา Ikigai แบบละเอียด
│
├── scripts/              ← 💬 คำถาม + ไอเดียสำหรับ Phase 1, 3, 5
│   ├── self-reflections.md   ← 40+ คำถาม 4 หมวด
│   ├── mini-experiments.md   ← 10+ ไอเดียทดสอบ 14 วัน
│   └── obstacle-buster.md    ← 10 อุปสรรค + วิธีฝ่า
│
├── template/             ← 📋 แม่แบบสำหรับ Phase 2, 4, 5
│   ├── ikigai-map.md         ← Blank Venn diagram
│   ├── ikigai-statement.md   ← Ikigai 1 บรรทัด
│   └── action-plan-90.md     ← แผน 90 วัน + weekly check-in
│
├── example/              ← 👤 ตัวอย่างคนไทยที่ค้นหาเจอ
│   ├── 01-sales-to-teacher.md  ← พนักงานขาย → ครู
│   ├── 02-dev-to-farmer.md     ← โปรแกรมเมอร์ → เกษตรกร
│   └── 03-cs-to-artist.md      ← คอลเซ็นเตอร์ → ศิลปิน
│
├── reference/            ← 📚 ข้อมูลลึก + frameworks เสริม
│   ├── ikigai-deep-dive.md     ← หลักการ Ikigai แบบละเอียด
│   ├── other-frameworks.md     ← Wheel of Life, StrengthsFinder ฯลฯ
│   └── cheatsheet.md           ← สรุป 1 หน้า
│
└── assets/
    └── ikigai-map.svg          ← 🖼️ Venn diagram 4 วงกลม
```

---

## 👤 ตัวอย่างจริง

| # | จาก | สู่ | ปัญหา | Ikigai ที่ค้นพบ |
|---|-----|-----|-------|----------------|
| 1 | 💼 พนักงานขาย | 👨‍🏫 ครู | ขายของไม่มีความหมาย | สอนทักษะการขายให้น้องๆ ที่เริ่มต้น |
| 2 | 💻 โปรแกรมเมอร์ | 🌾 เกษตรกร | จอแบนไม่ตอบโจทย์ชีวิต | ผสมเทคโนโลยีกับการเกษตร |
| 3 | 📞 คอลเซ็นเตอร์ | 🎨 ศิลปิน | งานซ้ำซาก ไม่ได้ใช้ความคิดสร้างสรรค์ | ทำอาร์ตที่สื่อสารความรู้สึกคน |

อ่านเต็มๆ ได้ที่ `example/` ค่ะ

---

## 🔗 ระบบที่เกี่ยวข้อง

| Skill | ใช้คู่กันยังไง |
|-------|--------------|
| ⚡ **[zecision](https://github.com/hartkitsak/zecision)** | ถ้าค้นหา Ikigai แล้วเจอหลายทาง — zecision ช่วยเลือกทาง |
| 📚 **Viktor Frankl — Man's Search for Meaning** | ปรัชญาชีวิตที่ complement Ikigai |
| 🎯 **Simon Sinek — Start with Why** | กรอบคิด "Why → How → What" ที่สอดคล้อง |
| 🔄 **Design Thinking** | Experiment → Learn → Iterate (เหมือน Ikigai Phase 3-4) |

---

## 📥 ติดตั้ง

```bash
git clone https://github.com/hartkitsak/ikigai.git
```

แล้วบอก AI agent ว่า:

```
อ่าน ikigai/SKILL.md แล้วช่วยหา Ikigai ให้หน่อย
```

---

## 📄 License

MIT — free to use, modify, and share.

Built by [hartkitsak](https://github.com/hartkitsak)
