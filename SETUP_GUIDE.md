# SRM AI Study Hub - Complete Setup Guide

## 🚀 Quick Start

This guide contains ALL the code you need. Follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/siddharth-1118/srm-ai-study-hub.git
cd srm-ai-study-hub
```

### 2. Install dependencies
```bash
npm install
```

### 3. Set up environment variables
Create `.env.local` file in root:
```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your-secret-key
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your-nextauth-secret
OPENAI_API_KEY=sk-your-openai-key
ADMIN_EMAIL=saisiddharthwooka@gmail.com
```

### 4. Run development server
```bash
npm run dev
```

Open http://localhost:3000

---

## 📁 Complete Project Structure

You need to create this structure:

```
srm-ai-study-hub/
├── package.json (✓ already created)
├── .env.example (✓ already created)
├── .env.local (create this yourself with real values)
├── next.config.js
├── tailwind.config.js
├── postcss.config.js
├── jsconfig.json
├── public/
│   └── uploads/  (create this folder for file uploads)
├── src/
│   ├── lib/
│   │   ├── mongodb.js
│   │   ├── subjects.js
│   │   └── auth.js
│   ├── models/
│   │   ├── User.js
│   │   ├── Subject.js
│   │   └── Material.js
│   ├── pages/
│   │   ├── _app.js
│   │   ├── index.js
│   │   ├── dashboard.js
│   │   ├── auth/
│   │   │   ├── login.js
│   │   │   └── signup.js
│   │   ├── subject/
│   │   │   └── [code].js
│   │   └── api/
│   │       ├── auth/
│   │       │   ├── [...nextauth].js
│   │       │   └── signup.js
│   │       ├── materials/
│   │       │   ├── upload.js
│   │       │   └── [id].js
│   │       └── ai/
│   │           └── chat.js
│   └── components/
│       ├── Navbar.js
│       ├── SubjectCard.js
│       ├── MaterialUpload.js
│       └── ChatInterface.js
└── README.md
```

---

## 📝 I WILL CREATE ALL REMAINING FILES IN NEXT COMMITS

Since creating 30+ files one-by-one through GitHub web is slow, I'll add them in batches.

**What's included:**
- ✅ Authentication (signup/login) with admin role
- ✅ All 8 semesters with complete subject list
- ✅ Admin-only upload for PYQs and materials  
- ✅ Subject-wise AI chat powered by OpenAI
- ✅ Beautiful UI with Tailwind CSS
- ✅ MongoDB database for users and materials
- ✅ Ready to deploy on Vercel

## 🎯 Features

### For You (Admin)
- Upload PYQs, notes, syllabus for any subject
- Manage all materials
- Full access to AI assistant

### For Students
- Browse materials by semester/subject
- Download PYQs and notes
- Ask doubts to subject-wise AI
- No upload permission (read-only)

---

## 🗂️ All 8 Semesters Subjects

The app includes all your listed subjects organized by semester. Students can filter by semester and access subject-specific materials and AI.

---

## 🔐 How Admin Works

1. When you sign up with email `saisiddharthwooka@gmail.com`, you automatically become admin
2. Only admin sees "Upload" buttons on subject pages
3. Students see only "View" and "Download" options

---

## 🤖 AI Integration

Each subject has its own AI chat that:
- Knows the subject context
- Can answer doubts based on general knowledge
- Students can ask unlimited questions

---

## 📦 Next Steps

1. Wait for me to commit all remaining code files
2. Clone the repo locally
3. Run `npm install`
4. Create `.env.local` with your API keys
5. Run `npm run dev`
6. Sign up with your email to become admin
7. Start uploading materials!

---

Stay tuned! All code files coming in next commits. 🚀
