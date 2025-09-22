# 🚀 Soft Drive – Cloud Storage Management App

A **Google Drive–like clone** built with **Next.js 15, Appwrite, and TailwindCSS**.
Soft Drive allows users to **securely upload, organize, and manage files** in the cloud with a sleek and responsive UI.

---

## ✨ Features

✅ User authentication (sign up, login, OTP verification)
✅ Upload & preview files (images, videos, documents, etc.)
✅ Categorize files by type (documents, media, others)
✅ Search and sort functionality
✅ Real-time file management using **Appwrite SDK**
✅ Responsive UI with **TailwindCSS & ShadCN UI**
✅ Secure storage using **Appwrite Buckets**

---

## 🛠️ Tech Stack

* **Frontend**: [Next.js 15](https://nextjs.org/), React, TypeScript
* **Backend & Storage**: [Appwrite](https://appwrite.io/)
* **Styling**: TailwindCSS, ShadCN UI
* **Version Control**: Git & GitHub

---

## ⚡ Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/afrithanahamed/soft-drive.git
cd soft-drive
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Setup environment variables

Create a `.env.local` file in the root:

```env
NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
NEXT_PUBLIC_APPWRITE_PROJECT="your_project_id"
NEXT_PUBLIC_APPWRITE_DATABASE="your_database_id"
NEXT_PUBLIC_APPWRITE_USERS_COLLECTION="users"
NEXT_PUBLIC_APPWRITE_FILES_COLLECTION="files"
NEXT_PUBLIC_APPWRITE_BUCKET="your_bucket_id"
NEXT_APPWRITE_KEY="your_secret_key"
```

### 4️⃣ Run the development server

```bash
npm run dev
```

Your app will be live at [http://localhost:3000](http://localhost:3000) 🎉

---

## 👨‍💻 Author

Built with ❤️ by **[Afrith Ahamed](https://github.com/afrithanahamed)**

---

Do you want me to also **add badges (like build status, stars, tech stack icons)** at the top to make it look more eye-catching on GitHub?
