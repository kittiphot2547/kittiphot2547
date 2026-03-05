# 📈 FX-Macro AI: AI-Powered Forex Sentiment Analyzer

![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue)
![AI Model](https://img.shields.io/badge/Model-FinBERT-orange)
![License](https://img.shields.io/badge/License-MIT-green)

**FX-Macro AI** คือเครื่องมือวิเคราะห์ทิศทางตลาด Forex จากข่าวเศรษฐกิจมหภาค (Macroeconomics) โดยใช้ปัญญาประดิษฐ์ (AI) ระดับโลกอย่าง **FinBERT** ซึ่งถูกฝึกฝนมาเพื่ออ่านและทำความเข้าใจภาษาทางการเงินโดยเฉพาะ โปรแกรมนี้ช่วยให้นักลงทุนรายย่อยสามารถตีความนโยบายของธนาคารกลาง (Hawkish/Dovish) และแปลงเป็นสัญญาณเทรด (Trade Signals) ได้อย่างรวดเร็วและแม่นยำ

---

## 🎯 ปัญหาที่โปรเจกต์นี้เข้ามาแก้ไข (Pain Points)
1. **Information Overload:** เทรดเดอร์ต้องรับมือกับข่าวสารภาษาอังกฤษจำนวนมหาศาลในแต่ละวัน ทำให้วิเคราะห์ตามไม่ทัน
2. **Complexity of Central Bank Speak:** ถ้อยแถลงของธนาคารกลาง (เช่น FED, ECB) มักมีความซับซ้อน AI ทั่วไปไม่สามารถตีความได้แม่นยำว่าข่าวไหนส่งผลให้ค่าเงิน "แข็งค่า" หรือ "อ่อนค่า"

## ✨ ฟีเจอร์เด่น (Key Features)
* 🧠 **Financial NLP Processing:** ใช้โมเดล `ProsusAI/finbert` ในการวิเคราะห์ Sentiment (Positive/Negative/Neutral) ของข่าว
* 🔎 **Auto-Currency Detection:** มีระบบ Rule-based กรองหา Keyword อัตโนมัติ เพื่อระบุว่าข่าวนี้กำลังส่งผลกระทบต่อสกุลเงินใด (เช่น USD, EUR, JPY, THB)
* ⚡ **Actionable Trade Signals:** ไม่ใช่แค่บอกอารมณ์ของข่าว แต่แปลงผลลัพธ์เป็นคำแนะนำการเทรด (LONG/SHORT/WAIT & SEE) พร้อมเหตุผลประกอบทางเศรษฐศาสตร์

---

## 🛠️ เทคโนโลยีที่ใช้ (Tech Stack)
* **Language:** Python 3.8+
* **AI/ML Library:** `transformers` (Hugging Face), `PyTorch`
* **Model:** FinBERT (Financial Bidirectional Encoder Representations from Transformers)

---

## 🚀 วิธีการติดตั้งและใช้งาน (Installation & Usage)

1. **ติดตั้งไลบรารีที่จำเป็น:**
   เปิด Terminal หรือ Command Prompt แล้วพิมพ์คำสั่ง:
   ```bash
   pip install transformers torch
   📊 ตัวอย่างการทำงาน (Example Output)
Input (ใส่พาดหัวข่าว):

Federal Reserve surprises markets with a 50 basis point rate hike to combat sticky inflation.

Output (ผลลัพธ์จาก AI):

Plaintext
------------------------------------------------------------
📊 REPORT: ผลการวิเคราะห์จาก FX-MACRO AI
------------------------------------------------------------
🏳️ สกุลเงินที่ได้รับผลกระทบ : USD (ดอลลาร์สหรัฐ)
🤖 ผลวิเคราะห์ AI       : POSITIVE (ความมั่นใจ 96.45%)
🎯 ทิศทางค่าเงิน        : Hawkish (ค่าเงินแข็งค่า 📈)
⚡ สัญญาณเทรด         : 🟢 แนะนำ: LONG (BUY) สกุลเงินนี้
💡 เหตุผลประกอบ       : สะท้อนถึงสภาวะเศรษฐกิจที่แข็งแกร่งหรือนโยบายการเงินแบบเข้มงวด ดึงดูดเงินทุนไหลเข้า ส่งผลให้มีความต้องการซื้อสกุลเงินนี้สูงขึ้น
------------------------------------------------------------
💡 แผนการพัฒนาในอนาคต (Future Enhancements)
[ ] เชื่อมต่อ API ดึงข่าวอัตโนมัติ (เช่น ForexFactory API หรือ NewsAPI)

[ ] บันทึกผลการวิเคราะห์ลงในไฟล์ CSV/Excel อัตโนมัติ (Database Logging)

[ ] พัฒนา User Interface (UI) แบบ Web Application ด้วย Streamlit

Developed as a Data Analytics Project.


---

### 💡 ขั้นตอนการเอาขึ้น GitHub ฉบับรวบรัด

1. สมัครสมาชิกและล็อกอินเข้าเว็บ **[GitHub](https://github.com/)**
2. กดปุ่ม **New** (สีเขียว) มุมซ้ายบนเพื่อสร้าง Repository (คลังเก็บโปรเจกต์) ใหม่
3. ตั้งชื่อ Repository ว่า `FX-Macro-AI` (หรือชื่ออื่นๆ ตามชอบ)
4. เลื่อนลงมาติ๊กถูกที่ช่อง **"Add a README file"** แล้วกดปุ่ม **Create repository** สีเขียวด้านล่างสุด
5. เมื่อได้หน้าโปรเจกต์มาแล้ว ให้คลิกที่รูปดินสอ ✏️ บริเวณไฟล์ `README.md` เพื่อแก้ไข
6. **ก๊อปปี้ข้อความ Markdown ด้านบนทั้งหมด** ไปวางทับลงไป แล้วกดปุ่ม **Commit changes...** (สีเขียวมุมขวาบน)
7. กดปุ่ม **Add file -> Upload files** แล้วลากไฟล์ `fx_macro.py` ของคุณมาวาง เพื่ออัปโหลดโค้ดขึ้นไปเก็บไว้

แค่นี้คุณก็จะได้ลิงก์ GitHub เท่ๆ (เช่น `github.com/ชื่อคุณ/FX-Macro-AI`) เอาไว้ส่งอาจารย์แล้วครับ! 

ถ้าต้องการเพิ่มส่วนไหนใน GitHub เช่น ใส่ชื่อสมาชิกในกลุ่ม หรือชื่อวิชา แจ้งผมได้เลยนะครับเดี๋ยวผมปรับ Markdown ให้ครับ
