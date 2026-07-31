# AI-Event-Management-Platform

An automated, end-to-end event management platform leveraging **n8n workflows**, **Google Apps Script**, **Google Forms**, **Google Slides**, and **AI Analysis** to handle attendee registration, real-time attendance, automated certificate generation, and AI-driven feedback sentiment analysis.

---

## 📁 Repository Architecture

```
AI-Event-Management-Platform/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── workflows/
│   ├── 01-registration-workflow.json
│   ├── 02-attendance-workflow.json
│   ├── 03-certificate-generation-workflow.json
│   └── 04-feedback-ai-analysis-workflow.json
│
├── apps-script/
│   ├── README.md
│   ├── registration.gs
│   └── feedback.gs
│
├── docs/
│   └── screenshots/
│       ├── registration-workflow.png
│       ├── attendance-workflow.png
│       ├── certificate-workflow.png
│       ├── feedback-workflow.png
│       ├── registration-form.png
│       ├── feedback-form.png
│       ├── qr-email.png
│       ├── certificate-email.png
│       └── ai-report-email.png
│
├── google-slides-template/
│   └── certificate-template-info.md
│
└── forms/
    ├── registration-form.md
    └── feedback-form.md
```

---

## ⚡ Key Modules & Workflows

| Module | Description | Location |
| :--- | :--- | :--- |
| **01. Registration Workflow** | Captures attendee responses via webhook/Form, updates Google Sheets, and sends confirmation emails. | [`workflows/01-registration-workflow.json`](file:///c:/Users/heema/Desktop/repo/workflows/01-registration-workflow.json) |
| **02. Attendance Workflow** | Tracks check-ins (QR code / webhook / manual input) and logs attendance status in real time. | [`workflows/02-attendance-workflow.json`](file:///c:/Users/heema/Desktop/repo/workflows/02-attendance-workflow.json) |
| **03. Certificate Generation** | Dynamically generates customized PDF certificates using Google Slides templates and emails them to attendees. | [`workflows/03-certificate-generation-workflow.json`](file:///c:/Users/heema/Desktop/repo/workflows/03-certificate-generation-workflow.json) |
| **04. Feedback & AI Analysis** | Collects attendee feedback, performs LLM sentiment analysis & key insights extraction, and saves report data. | [`workflows/04-feedback-ai-analysis-workflow.json`](file:///c:/Users/heema/Desktop/repo/workflows/04-feedback-ai-analysis-workflow.json) |
| **Google Apps Script Bridge** | Form submission triggers forwarding payloads to n8n webhooks. | [`apps-script/README.md`](file:///c:/Users/heema/Desktop/repo/apps-script/README.md) |

---

## 🖼️ Workflows & Screenshots

- **Registration Workflow**: [`docs/screenshots/registration-workflow.png`](file:///c:/Users/heema/Desktop/repo/docs/screenshots/registration-workflow.png)
- **Attendance Workflow**: [`docs/screenshots/attendance-workflow.png`](file:///c:/Users/heema/Desktop/repo/docs/screenshots/attendance-workflow.png)
- **Certificate Workflow**: [`docs/screenshots/certificate-workflow.png`](file:///c:/Users/heema/Desktop/repo/docs/screenshots/certificate-workflow.png)
- **Feedback Workflow**: [`docs/screenshots/feedback-workflow.png`](file:///c:/Users/heema/Desktop/repo/docs/screenshots/feedback-workflow.png)
- **Registration Form**: [`docs/screenshots/registration-form.png`](file:///c:/Users/heema/Desktop/repo/docs/screenshots/registration-form.png)
- **Feedback Form**: [`docs/screenshots/feedback-form.png`](file:///c:/Users/heema/Desktop/repo/docs/screenshots/feedback-form.png)
- **QR Email**: [`docs/screenshots/qr-email.png`](file:///c:/Users/heema/Desktop/repo/docs/screenshots/qr-email.png)
- **Certificate Email**: [`docs/screenshots/certificate-email.png`](file:///c:/Users/heema/Desktop/repo/docs/screenshots/certificate-email.png)
- **AI Report Email**: [`docs/screenshots/ai-report-email.png`](file:///c:/Users/heema/Desktop/repo/docs/screenshots/ai-report-email.png)

---

## 🔧 Prerequisites & Setup

1. **n8n Automation Engine**: Import JSON files from the `workflows/` directory into your n8n instance.
2. **Google Apps Script**: Refer to [`apps-script/README.md`](file:///c:/Users/heema/Desktop/repo/apps-script/README.md) and copy script code from `apps-script/` into your Google Sheets Apps Script editor.
3. **Google Forms**: Refer to specifications in `forms/` to build Registration and Feedback forms.
4. **Google Slides Template**: Refer to `google-slides-template/certificate-template-info.md` for certificate layout placeholders.

---

## 📜 License

This project is licensed under the [MIT License](file:///c:/Users/heema/Desktop/repo/LICENSE).
"# -AI-Event-Management-Platform" 
"# AI-Event-Management-Platform" 
