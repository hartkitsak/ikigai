# ikigai 🎯

**AI coach ที่ช่วยคนไทยค้นหา Ikigai** — จุดตัดของสิ่งที่ชอบ สิ่งที่เก่ง สิ่งที่โลกต้องการ และสิ่งที่ทำเงินได้ พาคุณออกจากความหลงทาง สู่เส้นทางที่มีความหมาย

## Features

- ❤️ สะท้อนตัวเองด้วย 40+ คำถาม 4 หมวด (ชอบ, เก่ง, โลกต้องการ, ทำเงิน)
- 🧩 สร้าง Ikigai Map + Statement ส่วนตัว
- 🧪 Mini-experiment 14 วัน — พิสูจน์ก่อนทุ่มเต็ม
- 📋 Action Plan 90 วัน + Weekly check-in
- 🧠 วิเคราะห์อุปสรรคและวิธีฝ่า

## Installation

```powershell
git clone https://github.com/hartkitsak/ikigai.git "$HOME\.config\opencode\skills\ikigai"
```

## Usage

```
/ikigai ช่วยหา Ikigai ให้หน่อย
ผมอายุ 28 เป็นโปรแกรมเมอร์ แต่รู้สึกเบื่อ ไม่รู้ว่าชีวิตควรไปทางไหน
```

## Structure

```
ikigai/
├── SKILL.md                    ← Entry point (อ่านอัตโนมัติ)
├── workflow/workflow.md        ← 6 Phase: ฟัง → สะท้อน → map → experiment → plan → check-in
├── scripts/
│   ├── self-reflections.md     ← 40+ คำถาม 4 หมวด
│   ├── mini-experiments.md     ← 10 ไอเดียทดสอบ Ikigai
│   └── obstacle-buster.md      ← 10 อุปสรรค + วิธีฝ่า
└── template/
    ├── ikigai-map.md           ← Blank Venn diagram
    ├── ikigai-statement.md     ← Statement 1 บรรทัด
    └── action-plan-90.md       ← แผน 90 วัน
```

## Example

**User**: "ผมอายุ 28 เป็นโปรแกรมเมอร์ แต่รู้สึกเบื่อ ไม่รู้ว่าชีวิตควรไปทางไหน"

**Agent จะ**: ฟัง → ถามคำถามสะท้อน 4 หมวด → สร้าง Ikigai Map → เขียน Statement ร่างแรก → เสนอ Mini-experiment 14 วัน → Action Plan

## Requirements

- [Claude Code](https://claude.ai) หรือ [opencode](https://opencode.ai)

## License

MIT
