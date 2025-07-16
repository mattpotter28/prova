# Prova

**Prova** is a platform to securely upload and share media files with guarantees that they are **not AI-generated** and **cannot be used for training AI models**. It enables users and third parties (e.g., immigration offices, legal entities) to verify the authenticity of media through cryptographic hashing and digital certificates.

---

## ✨ Project Overview

In the era of generative AI, the ability to prove that a photo, video, or audio is authentic and not AI-created is increasingly important. Prova empowers creators and consumers by:

- Accepting media uploads with hashing and metadata extraction
- Generating a cryptographic proof of authenticity
- Providing public verification URLs for trusted third parties
- Applying anti-AI protections to prevent unauthorized AI training use

---

## 🚀 Features

- Upload media files via a clean, responsive React UI  
- Automatically hash uploaded files (SHA-256)  
- Extract and display media metadata (EXIF, duration, format)  
- Issue verifiable certificates linked to media  
- Dynamic verification pages at `/file/[id]`  
- API endpoints for upload, verification, and protection workflows  
- Designed for integration with AI detection services (Glaze, Nightshade, etc.)  
- Serverless deployment ready via Vercel  

---

## 🔧 Tech Stack

- **Next.js (App Router) + React + TypeScript**  
- **Vercel** for serverless deployment and hosting  
- **Tailwind CSS** for styling  
- **Supabase** (PostgreSQL + Storage) for database and file metadata  
- Crypto libraries for hashing  
- Placeholder hooks for AI detection integration  

---

## 📦 Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)  
- Git  
- Supabase account for backend services (optional at MVP stage)  

### Setup

1. Clone the repo:

```bash
git clone https://github.com/mattpotter28/prova.git
cd prova
```

2. Install dependencies:

```bash
npm install
```

3. Set environment variables in .env.local:

```ini
SUPABASE_URL=your-supabase-url
SUPABASE_ANON_KEY=your-supabase-anon-key
CLOUDINARY_URL=your-cloudinary-url
```

4. Run the development server:

```bash
npm run dev
```

5. Open http://localhost:3000 in your browser

---

## 🌐 Live Demo
https://prova-wkgn.vercel.app
