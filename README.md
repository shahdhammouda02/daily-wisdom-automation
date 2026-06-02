# 🌟 Daily Wisdom Bot — حكمة يومية تلقائية

## ما هو المشروع؟
Automation workflow بيبعت حكمة يومية على Telegram كل صباح تلقائياً باستخدام AI.

## الأدوات المستخدمة
- **n8n** — منصة الأتمتة
- **Groq AI** — توليد الحكمة مجاناً (llama-3.3-70b)
- **Telegram Bot** — إرسال الرسالة

## كيف يشتغل؟
1. كل يوم الساعة 8 الصبح Schedule Trigger يشتغل
2. HTTP Request يطلب من Groq AI حكمة عربية
3. Telegram يبعت الحكمة للمستخدم

## كيف تشغله؟
1. حمّل الـ JSON file
2. افتح n8n وأضف الـ workflow عن طريق Import from file
3. أضف Groq API Key
4. أضف Telegram Bot Token و Chat ID
5. اضغط Publish
