# Med4U
Med4U is a modern web app for managing personal medical records, uploading and summarizing lab reports, and visualizing health trends. It features secure authentication, AI-powered OCR and summarization, and a beautiful, responsive UI.

# 🩺 Med4U – Medical Records & Lab Report Summarizer

![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-Active-blue)

**Med4U** is a modern web application designed for managing personal medical records, uploading and summarizing lab reports using AI, and visualizing health trends. It features secure user authentication, OCR-based report parsing, and a responsive, elegant UI.

## ✨ Features

- 🔐 **User Authentication** – Secure sign up and login with Firebase
- 📊 **Dashboard** – Overview of health stats and recent activity
- 📁 **Medical Records Management** – Upload, organize, and view documents (PDF)
- 🤖 **OCR & Report Summarization** – AI-powered with Tesseract.js + HuggingFace API
- 📈 **Lab Result Tracking** – Visual trend analysis using charts
- 📄 **PDF Export** – Download summaries as shareable PDFs
- ☁️ **Cloud Storage** – Secure file handling with Cloudinary
- 💻 **Responsive Design** – Mobile-friendly + dark mode support

## 🛠️ Tech Stack

| Category         | Technologies |
|------------------|--------------|
| Frontend         | React, Tailwind CSS, Chart.js |
| Backend          | Node.js, Express, Tesseract.js |
| Authentication   | Firebase Auth |
| Database         | Firebase Firestore |
| Storage          | Cloudinary |
| AI/NLP           | HuggingFace Transformers API |
| PDF Tools        | pdf.js, html2pdf.js |
| Deployment       | Render, Vercel |

## 🚀 Live Demo

- 🔗 Frontend (Render): https://med4u-frontend.onrender.com  
- 🔗 Fullstack (Render): https://med4u.onrender.com  
- 🔗 Frontend (Vercel): http://med4u.vercel.app  

## 🧾 Project Structure
med4u_beta/
├── public/ # Public assets
├── src/
│ ├── components/ # UI components
│ ├── pages/ # Main pages (Dashboard, Reports, etc.)
│ ├── services/ # API, OCR, summarizer logic
│ ├── hooks/ # Custom React hooks
│ ├── context/ # React context providers
├── ocr-summary-api/ # Express backend for OCR (Tesseract.js)
├── package.json # Project metadata
└── tailwind.config.js # Tailwind CSS config


## ☁️ Deployment Instructions

### Frontend on Render:
- **Build Command**: `npm run build`
- **Publish Directory**: `build`

### Backend on Render:
- **Start Command**: `node app.js` *(inside `ocr-summary-api/`)*
- Add environment variables via the Render dashboard.

> Also compatible with Vercel, Netlify, and Firebase Hosting (frontend only)

## 📝 Firebase Setup

- Enable **Email/Password** sign-in
- Set up **Firestore collections**: `users`, `medications`, `cases`, `conditions`, `reports`
- Configure **Firebase Storage** and security rules

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](./LICENSE) file for details.

## 🙏 Acknowledgments

- [Heroicons](https://heroicons.com/) – For elegant icons
- [Tailwind UI](https://tailwindui.com/) – UI inspiration
- [Render](https://render.com/) – Free fullstack hosting
- [HuggingFace](https://huggingface.co/) – Summarization API

