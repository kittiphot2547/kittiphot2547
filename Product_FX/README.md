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
