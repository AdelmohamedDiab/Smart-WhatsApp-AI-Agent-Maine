# 🤖 Smart WhatsApp AI Assistant (Single-Agent Edition)

> A lightweight, highly efficient, all-in-one WhatsApp AI Assistant built with n8n. This project utilizes a centralized Single-Agent architecture to process text, voice notes, and images, and executes daily tasks using a suite of integrated tools.

## 📌 Project Overview
This repository contains the `JSON` workflow template for a fully functional WhatsApp AI Assistant. Unlike complex multi-agent systems, this "Mini Edition" relies on a single, powerful AI Agent to handle routing, reasoning, and tool execution. It's designed to be a fast, personal digital assistant that lives right inside your WhatsApp.

<img width="1570" height="830" alt="image" src="https://github.com/user-attachments/assets/4ba6a5ec-0c56-4788-a03d-c99e4cab9d28" />


## 🚀 Key Features
* **Omnichannel Input:** Understands Text messages, Voice notes (transcription), and Images (vision analysis).
* **Smart Tool Execution:** The central agent can autonomously use tools to:
  * 📅 Manage Google Calendar (Create, Delete, Get events).
  * 📧 Send emails via Gmail.
  * 🔍 Search the web for real-time information.
  * 🧮 Perform mathematical calculations.
* **Voice Output:** Responds with synthesized human-like audio (via ElevenLabs) or standard text based on the user's input type.

## ⚙️ Architecture (Single-Agent Setup)
1. **Trigger:** WhatsApp Cloud API.
2. **Processing Nodes:** Downloads and formats media (Audio/Images).
3. **The Core Agent:** A single `AI Agent` node powered by Google Gemini, equipped with memory and a toolbox.
4. **Output:** Dynamic response routing (Text vs. Audio).

## 🛠️ Tech Stack
* **Platform:** n8n
* **Core AI:** Google Gemini Chat Model
* **Integrations:** WhatsApp Cloud API, Gmail, Google Calendar, Google Custom Search, ElevenLabs (TTS).

---

# 🤖 المساعد الذكي المدمج عبر واتساب (النسخة الأحادية)

> مساعد ذكي خفيف وسريع يعمل عبر واتساب، مبني باستخدام منصة n8n. يعتمد هذا المشروع على معمارية "الوكيل الواحد" (Single-Agent) لمعالجة النصوص، الرسائل الصوتية، والصور، وتنفيذ المهام اليومية باستخدام مجموعة من الأدوات المدمجة.

## 📌 نظرة عامة
يحتوي هذا المستودع على قالب العمل (`JSON` Workflow) لمساعد ذكي متكامل. على عكس الأنظمة المعقدة متعددة الوكلاء، تعتمد هذه "النسخة المصغرة" على عقل مركزي واحد لتحليل الطلبات واستخدام الأدوات. تم تصميمه ليكون مساعدك الرقمي الشخصي والسريع داخل واتساب.


<img width="1570" height="830" alt="image" src="https://github.com/user-attachments/assets/825336d6-0664-45da-b391-542ddcb63574" />

## 🚀 المميزات الرئيسية
* **معالجة المدخلات المتعددة:** فهم النصوص، تفريغ الرسائل الصوتية (Voice-to-Text)، وتحليل الصور.
* **استخدام الأدوات الذكي:** يستطيع الوكيل المركزي استخدام الأدوات التالية تلقائياً:
  * 📅 إدارة تقويم جوجل (إضافة، حذف، قراءة المواعيد).
  * 📧 إرسال رسائل البريد الإلكتروني عبر Gmail.
  * 🔍 البحث في الإنترنت عن المعلومات اللحظية.
  * 🧮 إجراء العمليات الحسابية.
* **ردود صوتية:** الرد بصوت بشري (عبر ElevenLabs) أو بنص عادي بناءً على طريقة إرسال المستخدم.

## ⚙️ معمارية النظام
1. **الاستقبال:** واجهة واتساب (WhatsApp Trigger).
2. **عقد المعالجة:** تحميل وتجهيز الميديا (صور/صوت).
3. **الوكيل المركزي:** عقدة `AI Agent` واحدة تعمل بنموذج Google Gemini، مزودة بذاكرة وصندوق أدوات كامل.
4. **الإرسال:** توجيه ديناميكي للردود (رد صوتي أو نصي).

## 📥 كيفية استخدام هذا القالب
1. قم بتحميل ملف الـ `.json` المرفق في هذا المستودع.
2. افتح منصة n8n الخاصة بك واضغط على `Import from File`.
3. قم بإضافة الـ Credentials الخاصة بك (WhatsApp, Google, Gemini, ElevenLabs).
4. فعّل الـ Workflow وابدأ في استخدامه!

## 👨‍💻 تطوير
**عادل محمد محمد دياب**
*طالب تكنولوجيا المعلومات (IT) ومُهتم بأتمتة الأنظمة.*
