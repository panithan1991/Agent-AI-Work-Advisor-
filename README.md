# 🧠 Advisor

> **Know What to Do Next.**

**Advisor** คือระบบ **Agent-Native Second Brain สำหรับการทำงาน** ที่ออกแบบมาให้ใช้งานร่วมกับ Agentic AI เช่น **Antigravity, Codex, Claude** หรือ AI Agent อื่น ๆ ที่สามารถอ่านและทำงานกับไฟล์ภายใน Project Folder ได้

Advisor ช่วยเปลี่ยน **เอกสาร งานเก่า ประสบการณ์ Timeline ขั้นตอนการทำงาน Template และ Lessons Learned** ให้กลายเป็นคลังความรู้ที่ Agent สามารถนำมาใช้เป็น **ที่ปรึกษาการทำงาน**

เป้าหมายคือทำให้ Agent สามารถตอบคำถามสำคัญได้ เช่น

> ตอนนี้ฉันควรทำอะไรต่อ?

> งานนี้ควรเริ่มเมื่อไร?

> ปีที่แล้วเราทำอย่างไร?

> หลังจากงานนี้ต้องทำอะไรต่อ?

> มี Template หรืองานเก่าที่นำกลับมาใช้ได้หรือไม่?

> ช่วยอธิบายขั้นตอนและช่วยทำงานนี้ต่อให้หน่อย

---

# ✨ แนวคิดหลัก

Advisor **ไม่ใช่ Chatbot ตัวใหม่**

และไม่จำเป็นต้องสร้าง

* Server
* Web Application
* API
* Database Server
* Cloud Infrastructure
* AI Model ของตัวเอง

ผู้ใช้ยังคงทำงานผ่าน Agentic AI ที่ใช้อยู่ตามปกติ

```text
                         USER
                           │
                           │
                    สนทนากับ Agent
                           │
          ┌────────────────┼────────────────┐
          │                │                │
          ▼                ▼                ▼
     Antigravity         Codex            Claude
          │                │                │
          └────────────────┼────────────────┘
                           │
                           ▼
                    Project Workspace
                           │
                           ▼
                    ┌─────────────┐
                    │   Advisor   │
                    └──────┬──────┘
                           │
          ┌────────────────┼────────────────┐
          │                │                │
          ▼                ▼                ▼
   Current Work       Work History      Procedures
          │                │                │
          ├────────── Timeline ─────────────┤
          │                │                │
          └──────── Lessons Learned ────────┘
                           │
                           ▼
                    Agent วิเคราะห์
                           │
                           ▼
                  Practical Work Advice
```

Advisor ทำหน้าที่เป็น **หน่วยความจำและบริบทของการทำงาน**

ส่วน Agentic AI ทำหน้าที่

* อ่านข้อมูล
* วิเคราะห์สถานการณ์
* ค้นประสบการณ์ในอดีต
* เปรียบเทียบ Timeline
* วางแผน
* ให้คำปรึกษา
* และช่วยลงมือทำงาน

---

# 🎯 Advisor ช่วยอะไรได้บ้าง

คุณสามารถถาม Agent ได้ด้วยภาษาปกติ เช่น

```text
ตอนนี้ผมควรทำอะไรต่อ?
```

```text
วันนี้มีงานอะไรที่ควรรีบทำ?
```

```text
สัปดาห์นี้ควรเตรียมอะไรไว้ล่วงหน้า?
```

```text
งานนี้ปีที่แล้วเราทำช่วงไหน?
```

```text
หลังจาก Task นี้ ปกติมีงานอะไรตามมา?
```

```text
งานนี้ต้องใช้เอกสารอะไรบ้าง?
```

```text
ช่วยอธิบายขั้นตอนการทำงานนี้ทีละขั้น
```

```text
ค้นงานเก่าและ Template ที่สามารถนำกลับมาใช้ได้
```

```text
เปรียบเทียบสถานะปีนี้กับ 2 ปีก่อน
ตอนนี้เราเร็วหรือช้ากว่าปกติ?
```

```text
จากข้อมูลทั้งหมด ช่วยวิเคราะห์ความเสี่ยงของงานปัจจุบัน
```

```text
ช่วยทำงานนี้ต่อให้ผมโดยอ้างอิงจากงานเก่า
```

---

# 🧠 Advisor ทำงานอย่างไร

Advisor ใช้แนวคิด

```text
Historical Knowledge
        +
Current Work State
        +
Timeline
        +
Procedures
        +
Dependencies
        +
Templates
        +
Lessons Learned
        │
        ▼
    Agentic AI
        │
        ▼
 Analysis & Planning
        │
        ▼
 Practical Work Advice
```

Agent ไม่ควรค้นหาเพียงข้อความที่ตรงกับคำถาม

แต่ควรพยายามทำความเข้าใจว่า

1. ตอนนี้ผู้ใช้อยู่ตรงไหนของงาน
2. งานใดเสร็จแล้ว
3. งานใดกำลังดำเนินการ
4. งานใดยังไม่เริ่ม
5. มี Deadline อะไร
6. งานใดขึ้นอยู่กับงานอื่น
7. ในอดีตเคยทำอย่างไร
8. งานถัดไปตามปกติคืออะไร
9. มี Procedure หรือ Template หรือไม่
10. เคยเกิดปัญหาอะไร
11. มี Lessons Learned อะไร
12. จากข้อมูลทั้งหมดควรทำอะไรต่อ

---

# 🚀 Quick Start

## 1. Clone Repository

```bash
git clone https://github.com/<your-username>/advisor.git
cd advisor
```

หรือ Download Repository เป็น ZIP แล้วแตกไฟล์ก็ได้

---

## 2. เปิด Project Folder ด้วย Agentic AI

เปิด Folder `advisor` ด้วย Agent ที่คุณใช้งานอยู่ เช่น

* Antigravity
* Codex
* Claude
* Agentic AI อื่นที่สามารถอ่านและแก้ไขไฟล์ใน Workspace ได้

จากนั้นให้ Agent อ่าน

```text
AGENTS.md
```

ก่อนเริ่มทำงาน

`AGENTS.md` คือ Operating Instructions ของ Advisor ซึ่งกำหนดว่า Agent ควร

* อ่านข้อมูลอย่างไร
* ตรวจ Current State อย่างไร
* ค้นงานเก่าอย่างไร
* ใช้ Historical Cases อย่างไร
* วิเคราะห์ Timeline อย่างไร
* แยกข้อมูลจริงออกจากการคาดการณ์อย่างไร
* ใช้ Procedure และ Template อย่างไร
* บันทึก Lessons Learned อย่างไร

---

# 📥 3. เพิ่มความรู้เดิม

นำเอกสารที่เกี่ยวข้องกับงานมาใส่ใน

```text
00_inbox/
```

ตัวอย่าง

```text
00_inbox/

├── project_report_2024.pdf
├── project_report_2025.pdf
├── timeline.xlsx
├── old_request_letter.docx
├── meeting_notes.docx
└── workflow.pdf
```

รองรับความรู้หลายรูปแบบ เช่น

* PDF
* Word
* Excel
* CSV
* PowerPoint
* Markdown
* Text
* Image
* รายงาน
* หนังสือราชการ
* Meeting Notes
* Timeline
* Checklist
* Template
* เอกสารงานเก่า

จากนั้นสั่ง Agent เช่น

```text
ตรวจสอบไฟล์ใหม่ใน 00_inbox

วิเคราะห์และจัดเก็บความรู้ที่มีประโยชน์เข้าสู่ Advisor
โดยเก็บข้อมูลสำคัญ เช่น

- วันที่
- Timeline
- Task
- ขั้นตอน
- Deadline
- หน่วยงานที่เกี่ยวข้อง
- ปัญหา
- วิธีแก้
- Template
- Lessons Learned
```

---

# 🔴 4. ระบุสถานะงานปัจจุบัน

ไฟล์ที่สำคัญที่สุดไฟล์หนึ่งคือ

```text
01_current/current_state.md
```

ตัวอย่าง

```markdown
# Current Work State

Last Updated: 2026-08-19

## Active Project

Project: Annual Assessment 2026

Current Phase:
Preparation

## Completed

- DONE — Prepare project plan
- DONE — Collect previous-year documents

## In Progress

- IN_PROGRESS — Prepare evidence

## Waiting

- WAITING — Information from Department A

## Upcoming

- Prepare internal review
- Prepare submission package

## Important Deadlines

- 2026-09-15 — Internal Review

## Risks

- Department A has not submitted required information.
```

Advisor จำเป็นต้องรู้ว่า **ตอนนี้กำลังเกิดอะไรขึ้น**

เพราะข้อมูลในอดีตเพียงอย่างเดียวไม่เพียงพอสำหรับตอบคำถามว่า

> ตอนนี้ควรทำอะไรต่อ?

---

# 💬 5. เริ่มถาม Advisor

เมื่อมี Knowledge และ Current State แล้ว สามารถถาม Agent ได้ทันที

```text
จากข้อมูลทั้งหมดใน Advisor

ช่วยวิเคราะห์ว่าตอนนี้ผมควรทำอะไรต่อ
เรียงลำดับตามความสำคัญ
พร้อมบอกเหตุผลและวิธีทำ
```

Agent ควรวิเคราะห์ตามลำดับประมาณนี้

```text
Current State
      │
      ▼
Official Deadlines
      │
      ▼
Dependencies
      │
      ▼
Historical Cases
      │
      ▼
Previous Timelines
      │
      ▼
Procedures
      │
      ▼
Templates
      │
      ▼
Lessons Learned
      │
      ▼
Risk Analysis
      │
      ▼
Recommended Next Actions
```

---

# 📁 Folder Structure

โครงสร้างเริ่มต้นของ Advisor

```text
advisor/

├── AGENTS.md
├── README.md
│
├── 00_inbox/
│
├── 01_current/
│   ├── current_state.md
│   ├── active_projects.md
│   └── upcoming_work.md
│
├── 02_knowledge/
│   ├── general/
│   └── domains/
│
├── 03_history/
│   ├── cases/
│   ├── timelines/
│   └── previous_years/
│
├── 04_procedures/
│   ├── playbooks/
│   └── checklists/
│
├── 05_templates/
│
├── 06_lessons/
│   └── lessons_learned.md
│
├── 07_projects/
│   ├── active/
│   └── archived/
│
├── 08_index/
│   ├── knowledge_index.md
│   └── timeline_index.md
│
├── scripts/
│
└── archive/
```

ไม่จำเป็นต้องใช้ทุก Folder ตั้งแต่วันแรก

หลักการคือ

> **Start simple. Add complexity only when needed.**

---

# 📥 `00_inbox`

พื้นที่สำหรับรับความรู้ใหม่

```text
New Document
      │
      ▼
  00_inbox/
      │
      ▼
Agent วิเคราะห์
      │
      ▼
Extract Knowledge
      │
      ▼
จัดหมวดหมู่
      │
      ▼
Update Advisor
```

ควรเก็บเอกสารต้นฉบับไว้เพื่อเป็นหลักฐานสำหรับตรวจสอบย้อนหลัง

---

# 🔴 `01_current`

เก็บข้อมูลว่า

> **ตอนนี้กำลังเกิดอะไรขึ้น**

ประกอบด้วย

* Active Project
* Current Phase
* Completed Tasks
* In Progress
* Waiting
* Blocked
* Upcoming Work
* Deadlines
* Risks

สถานะ Task ที่แนะนำ

```text
TODO
READY
IN_PROGRESS
WAITING
BLOCKED
DONE
CANCELLED
```

---

# 📚 `02_knowledge`

เก็บความรู้ที่สามารถนำกลับมาใช้ได้

ตัวอย่าง

```text
02_knowledge/

├── general/
│
└── domains/
    ├── ita/
    ├── governance/
    ├── procurement/
    ├── research/
    ├── project_management/
    └── other/
```

Advisor ไม่ยึดติดกับงานประเภทใดประเภทหนึ่ง

สามารถเพิ่ม Domain ใหม่ได้โดยไม่ต้องสร้างระบบใหม่

---

# 🕒 `03_history`

เก็บประวัติงานที่ผ่านมา

```text
03_history/

├── cases/
│   ├── project_2024.md
│   └── project_2025.md
│
├── timelines/
│
└── previous_years/
```

Historical Case ที่ดีควรมี

```markdown
# Historical Case

## Project

## Year

## Objective

## Important Dates

## Sequence of Work

## Documents Used

## Responsible Units

## Problems

## Solutions

## Outcome

## Lessons Learned

## What Happened Next
```

เป้าหมายคือเปลี่ยน **เอกสารเก่า** ให้กลายเป็น **ประสบการณ์ของ Advisor**

---

# 📖 `04_procedures`

เก็บวิธีการทำงานที่สามารถนำกลับมาใช้ซ้ำได้

```text
04_procedures/

├── playbooks/
│   ├── prepare_report.md
│   ├── collect_information.md
│   └── internal_review.md
│
└── checklists/
```

Procedure ควรมีโครงสร้างประมาณนี้

```text
Task
 │
 ▼
Prerequisites
 │
 ▼
Required Inputs
 │
 ▼
Step-by-Step Procedure
 │
 ▼
Verification
 │
 ▼
Expected Output
 │
 ▼
Next Task
```

Advisor จึงไม่ได้ตอบเพียงว่า

> ต้องทำอะไร

แต่ควรตอบได้ด้วยว่า

> ต้องทำอย่างไร

---

# 📄 `05_templates`

เก็บสิ่งที่สามารถนำกลับมาใช้ใหม่ เช่น

* หนังสือ
* รายงาน
* Checklist
* ตาราง
* Form
* Presentation
* Spreadsheet
* Email Template
* Project Template

ก่อนสร้างงานใหม่ Agent ควรค้นหางานเก่าและ Template ก่อนเสมอ

หลักการคือ

> **Reuse before recreate.**

---

# 💡 `06_lessons`

พื้นที่สำหรับเก็บ Lessons Learned

```text
สิ่งที่คาดไว้
      │
      ▼
สิ่งที่เกิดขึ้นจริง
      │
      ▼
    ปัญหา
      │
      ▼
    วิธีแก้
      │
      ▼
    ผลลัพธ์
      │
      ▼
สิ่งที่ควรทำครั้งหน้า
```

ตัวอย่าง

```markdown
# Lesson Learned

## Situation

หน่วยงานส่งข้อมูลล่าช้า

## Impact

การจัดทำรายงานล่าช้า 7 วัน

## Solution

ส่ง Reminder ก่อน Deadline 14 วัน

## Recommendation

ในรอบถัดไปควรเริ่มขอข้อมูลเร็วกว่าปีก่อนอย่างน้อย 2 สัปดาห์
```

นี่คือหนึ่งในส่วนสำคัญที่ทำให้ Advisor มีประสบการณ์มากขึ้นเมื่อใช้งานไปเรื่อย ๆ

---

# 📊 `07_projects`

ใช้แยก Project ปัจจุบันออกจากโครงการเก่า

```text
07_projects/

├── active/
│   └── project_2026/
│
└── archived/
    ├── project_2024/
    └── project_2025/
```

ช่วยให้ Agent แยกได้ชัดเจนระหว่าง

```text
Current Work
```

และ

```text
Historical Work
```

---

# 🔎 `08_index`

สร้าง Index แบบง่ายเพื่อช่วยให้ Agent ค้นความรู้ได้เร็วขึ้น

ตัวอย่าง

```markdown
| Topic | Type | Year | Location |
|---|---|---:|---|
| Annual Assessment | Historical Case | 2025 | 03_history/cases/assessment_2025.md |
| Prepare Report | Procedure | - | 04_procedures/playbooks/prepare_report.md |
| Request Letter | Template | 2025 | 05_templates/request_letter.docx |
```

Index เป็นเพียง **แผนที่ของความรู้**

ไม่ใช่ Source of Truth

---

# 🔄 Recommended Workflow

Workflow หลักของ Advisor

```text
                มีงาน / เอกสารใหม่
                        │
                        ▼
                 Add to Inbox
                        │
                        ▼
               Agent วิเคราะห์ข้อมูล
                        │
                        ▼
             Update Knowledge / History
                        │
                        ▼
              Update Current State
                        │
                        ▼
                    ถาม Agent
                        │
                        ▼
            ┌─────────────────────┐
            │  Analyze Current    │
            │  State + History    │
            └──────────┬──────────┘
                       │
                       ▼
             Recommend Next Action
                       │
                       ▼
              User / Agent ทำงาน
                       │
                       ▼
              Update Current State
                       │
                       ▼
                   งานเสร็จ
                       │
                       ▼
              Record Lesson Learned
                       │
                       ▼
                Better Knowledge
                       │
                       ▼
                 Better Advice
```

---

# 🤖 ตัวอย่าง Prompt

## ถามว่างานต่อไปคืออะไร

```text
อ่าน Current State และข้อมูลที่เกี่ยวข้อง

ช่วยวิเคราะห์ว่าตอนนี้ผมควรทำงานอะไรต่อ

เรียงตามความสำคัญ พร้อมอธิบาย

1. ต้องทำอะไร
2. ทำไมต้องทำตอนนี้
3. ต้องทำอย่างไร
4. ต้องเตรียมอะไร
5. หลังจากนั้นต้องทำอะไรต่อ
```

---

## ดูจาก Timeline เก่า

```text
ตรวจสอบ Timeline และ Historical Cases ในอดีต

หลังจาก Task ที่ผมเพิ่งทำเสร็จ
ปกติจะมีงานอะไรตามมา?

ใช้เวลาประมาณกี่วัน?

แยกให้ชัดเจนระหว่าง
Official Deadline กับ Historical Pattern
```

---

## ขอวิธีทำงาน

```text
ผมต้องทำ Task นี้

ค้นหา

- Procedure
- Historical Case
- Template
- Lessons Learned

ที่เกี่ยวข้อง

แล้วอธิบายวิธีทำให้ผมทีละขั้น
```

---

## ให้ Agent ช่วยทำงาน

```text
จากข้อมูลทั้งหมดใน Advisor

ช่วยจัดทำงานนี้ให้ผม

ก่อนเริ่มให้ตรวจสอบ
งานเก่า Template Procedure และข้อมูลปัจจุบันที่เกี่ยวข้อง

นำสิ่งที่สามารถ Reuse ได้กลับมาใช้
และอย่าสร้างข้อมูลที่ไม่มีหลักฐาน
```

---

## เปรียบเทียบกับปีก่อน

```text
เปรียบเทียบสถานะ Project ปัจจุบัน
กับ Project ในอดีต 2-3 รอบล่าสุด

วิเคราะห์ว่า

- ตอนนี้เราเร็วหรือช้ากว่าปกติ
- งานอะไรควรเริ่มเตรียม
- งานใดมีโอกาสล่าช้า
- มีปัญหาอะไรที่เคยเกิดซ้ำ
```

---

# ⚠️ Official Information vs Historical Pattern

Advisor ต้องแยกข้อมูลอย่างน้อย 3 ประเภท

```text
1. OFFICIAL INFORMATION
   ข้อมูลจากเอกสารหรือคำสั่งอย่างเป็นทางการ

2. HISTORICAL PATTERN
   สิ่งที่เคยเกิดขึ้นในอดีต

3. AGENT INFERENCE
   การวิเคราะห์หรือคาดการณ์จากหลักฐาน
```

ตัวอย่าง

❌ ไม่ควรตอบ

> Deadline ปีนี้คือ 15 กันยายน

เพียงเพราะปีที่แล้ว Deadline คือ 15 กันยายน

✅ ควรตอบ

> ปีที่แล้ว Deadline คือวันที่ 15 กันยายน และช่วงเวลาดังกล่าวสามารถใช้เป็นข้อมูลประกอบการวางแผนได้ แต่ขณะนี้ยังไม่พบเอกสารที่กำหนด Deadline ของปีปัจจุบันอย่างเป็นทางการ

หลักสำคัญคือ

> **History is evidence, not truth.**

---

# 🔍 Evidence First

คำแนะนำสำคัญควรสามารถตรวจสอบย้อนหลังได้

ผู้ใช้ควรสามารถถามว่า

```text
ทำไมถึงแนะนำให้ผมทำงานนี้?
```

```text
ข้อมูลมาจากไฟล์ไหน?
```

```text
ปีไหนเราเคยทำแบบนี้?
```

```text
นี่คือข้อมูลทางการ หรือเป็นการคาดการณ์?
```

```text
มีหลักฐานอะไรสนับสนุนคำแนะนำนี้?
```

หลักการคือ

> **Evidence before inference.**

---

# 🌱 Advisor เก่งขึ้นอย่างไร

Advisor ไม่ได้เก่งขึ้นจากการ Train AI Model ใหม่ทุกครั้ง

แต่พัฒนาจากการสะสม **ประสบการณ์การทำงาน**

```text
New Documents
      +
New Projects
      +
New Historical Cases
      +
New Timelines
      +
New Procedures
      +
New Templates
      +
New Lessons
      +
Corrections
      │
      ▼
Better Work Memory
      │
      ▼
Better Agent Context
      │
      ▼
Better Analysis
      │
      ▼
Better Advice
```

ยิ่งใช้งานนาน Advisor ยิ่งมี Context และประสบการณ์มากขึ้น

---

# 🌐 Domain Independent

Advisor ไม่ได้ถูกสร้างมาเพื่องานประเภทเดียว

สามารถใช้ได้กับหลาย Domain

```text
Advisor
│
├── ITA
├── Governance
├── Compliance
├── Research
├── Procurement
├── Project Management
├── HR
├── Finance
├── Academic Work
├── Administration
└── Personal Work
```

Domain ใหม่สามารถเพิ่มเข้าไปได้โดยไม่ต้องสร้าง Advisor ใหม่

---

# 🧭 Design Principles

## Agents are replaceable. Knowledge is persistent.

เปลี่ยน Agent ได้ แต่ Knowledge Workspace ยังคงอยู่

---

## Current State matters.

ข้อมูลในอดีตอย่างเดียวไม่เพียงพอ

Agent ต้องรู้ว่างานปัจจุบันอยู่ตรงไหน

---

## History is evidence, not truth.

สิ่งที่เกิดขึ้นปีที่แล้วไม่ได้หมายความว่าจะเกิดเหมือนเดิมในปีนี้

---

## Evidence before inference.

ค้นหาหลักฐานก่อนคาดการณ์

---

## Reuse before recreate.

ค้นงานเก่าและ Template ก่อนสร้างใหม่

---

## Learn from completed work.

ทุก Project ควรสร้าง Knowledge กลับคืนสู่ Advisor

---

## Keep it simple.

ไม่สร้าง Infrastructure ที่ยังไม่มีความจำเป็น

---

# 🔐 Privacy

Advisor เป็น Workspace ที่อาจมีข้อมูลเกี่ยวกับงานและองค์กร

ก่อนนำเอกสารเข้าสู่ Agentic AI ภายนอก ควรตรวจสอบนโยบาย Privacy และ Data Handling ของบริการที่ใช้งาน โดยเฉพาะเอกสารที่มี

* ข้อมูลส่วนบุคคล
* ข้อมูลภายในองค์กร
* ข้อมูลลับ
* ข้อมูลทางการเงิน
* เอกสารที่มีข้อจำกัดด้านการเปิดเผย

Advisor ไม่ได้บังคับให้ใช้ AI Provider รายใดรายหนึ่ง

---

# 🛠️ Requirements

## Required

ต้องการเพียง

* Git หรือ Download ZIP จาก GitHub
* Agentic AI ที่สามารถอ่าน Project Folder ได้

ตัวอย่าง

* Antigravity
* Codex
* Claude
* Agent อื่นที่มี Workspace / File Access

## Optional

สามารถใช้ Python สำหรับ Helper Scripts เช่น

* สร้าง Index
* ตรวจ Duplicate
* วิเคราะห์ Timeline
* จัดหมวดหมู่ไฟล์
* วิเคราะห์ข้อมูล
* สร้างกราฟ
* Extract Metadata

แต่ Python **ไม่จำเป็นสำหรับการใช้งาน Advisor ขั้นพื้นฐาน**

---

# 🧩 ไม่จำเป็นต้องใช้ Vector Database

สำหรับ Knowledge Base ขนาดเล็กถึงกลาง สามารถเริ่มจาก

```text
Folder Structure
      +
Markdown
      +
File Search
      +
Index
      +
Metadata
```

ก่อน

หากข้อมูลมีขนาดใหญ่ขึ้น จึงค่อยพิจารณา

* Vector Search
* Database
* Knowledge Graph
* Automated Indexing

หลักการคือ

> **Start simple. Add complexity only when needed.**

---

# 🗺️ Roadmap

แนวทางพัฒนาในอนาคต

* [ ] Automated Inbox Processing
* [ ] Automatic Knowledge Index
* [ ] Timeline Extraction
* [ ] Historical Case Generator
* [ ] Duplicate Detection
* [ ] Smart Current-State Updates
* [ ] Task Dependency Analysis
* [ ] Project Comparison
* [ ] Timeline Forecasting
* [ ] Risk Detection
* [ ] Template Recommendation
* [ ] Lessons Learned Generator
* [ ] Optional Vector Search
* [ ] Optional Knowledge Graph
* [ ] Additional Agent Compatibility

Roadmap นี้ไม่ใช่ Requirement ทั้งหมดตั้งแต่วันแรก

เพิ่ม Complexity เมื่อมี Use Case ที่ต้องการจริงเท่านั้น

---

# 🤝 Contributing

Contributions, suggestions และ experiments are welcome.

หากต้องการพัฒนา Advisor

1. Fork Repository
2. Create a Branch
3. Make your changes
4. Add documentation or tests where appropriate
5. Submit a Pull Request

ควรรักษาหลักการของ Advisor ให้

* simple
* readable
* reusable
* agent-independent
* domain-independent

---

# 📜 License

ก่อนเผยแพร่ Repository ควรเพิ่มไฟล์

```text
LICENSE
```

สามารถเลือก Open Source License เช่น

* MIT License
* Apache License 2.0

ตามวัตถุประสงค์ของโครงการ

---

# 🧠 Advisor

Advisor ไม่ได้พยายามสร้าง AI ตัวใหม่

Advisor พยายามสร้าง

> **ความทรงจำ ประสบการณ์ และบริบทในการทำงานที่ดีขึ้น ให้กับ AI ที่คุณใช้อยู่แล้ว**

เป้าหมายไม่ใช่เพียง

> **“AI สามารถค้นหาไฟล์ของฉันได้”**

แต่คือ

> **“AI เข้าใจว่างานของฉันเคยทำอย่างไร ตอนนี้อยู่ตรงไหน และควรทำอะไรต่อ”**

---

## Know What to Do Next.

**Advisor — An Agent-Native Second Brain and Work Strategy Advisor.**
