# Med4U
Med4U is a modern web app for managing personal medical records, uploading and summarizing lab reports, and visualizing health trends. It features secure authentication, AI-powered OCR and summarization, and a beautiful, responsive UI.

✨ Features
User Authentication – Secure sign up and login (Firebase)
Dashboard – Overview of your health and recent activity
Medical Records Management – Upload, organize, and view medical documents (PDF)
OCR & Report Summarization – AI-powered OCR (Tesseract.js) and medical report summarization (HuggingFace API)
Lab Result Tracking – Visual trend analysis of lab results over time
PDF Export – Export summaries as PDF documents for sharing
Cloud Storage – Secure document storage (Cloudinary)
Responsive Design – Works on desktop and mobile
Dark Mode – Beautiful in both light and dark themes

🛠️ Technical Stack
Frontend: React (functional components, hooks), Tailwind CSS
Backend: Node.js, Express, Tesseract.js (OCR), Deployed on Render
State Management: React Context API
Authentication: Firebase Auth
Database: Firebase Firestore
Storage: Cloudinary
AI Services: HuggingFace API (summarization)
PDF Processing: pdf.js, html2pdf.js
Data Visualization: Chart.js (react-chartjs-2)

🚀 Live Demo
Frontend (Render): https://med4u-frontend.onrender.com
Fullstack (Render): https://med4u.onrender.com
Frontend (Vercel): http://med4u.vercel.app

🏗️ Project Structure
med4u_beta/
├── public/            # Public assets
├── src/
│   ├── components/    # UI components
│   ├── pages/         # Main pages (Dashboard, Reports, etc.)
│   ├── services/      # API, OCR, summarizer logic
│   ├── hooks/         # Custom React hooks
│   ├── context/       # React context providers
│   └── ...            # Other app logic
├── ocr-summary-api/   # Express backend for OCR (Tesseract.js)
├── package.json       # Project metadata
└── tailwind.config.js # Tailwind CSS config

☁️ Deployment
Med4U can be deployed for free on Render:

Frontend: Deploy as a Static Site (build command: npm run build, publish directory: build)
Backend: Deploy as a Web Service (start command: node app.js in ocr-summary-api/)
Set environment variables in the Render dashboard for both services
See the Render deployment guide for more details
Other supported platforms: Netlify, Vercel, Firebase Hosting, GitHub Pages (frontend only)

📝 Firebase Setup
Enable Email/Password sign-in in Firebase Auth
Set up Firestore collections: users, medications, cases, conditions, reports
Configure Firebase Storage security rules

🙏 Acknowledgments
Heroicons for icons
Tailwind UI for UI inspiration
Render for free hosting
