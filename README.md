# 📦 E-Inventory System - UAS Web 2

Aplikasi **E-Inventory System** adalah *Single Page Application* (SPA) berbasis web yang dikembangkan untuk memenuhi tugas Ujian Akhir Semester (UAS) mata kuliah Web 2. Aplikasi ini dirancang menggunakan arsitektur *Full-Stack* modern untuk manajemen barang dan kategori secara *real-time*, aman, dan responsif.

## 🚀 Tech Stack Utama
Proyek ini dipisah menjadi dua *environment* utama: **Frontend** (Client-side) dan **Backend** (Server-side & API).

### Frontend (User Interface)
*   **Framework:** Vue 3 (Composition API / `<script setup>`)
*   **Build Tool:** Vite (Super-fast HMR)
*   **Styling:** Tailwind CSS (Premium Glassmorphism UI)
*   **Routing:** Vue Router

### Backend (RESTful API)
*   **Framework:** CodeIgniter 4 (CI4)
*   **Database:** SQLite 3 (Auto-migration via Controller)
*   **Authentication:** Firebase JWT (JSON Web Token - HS256)
*   **CORS:** Fully configured for Frontend-Backend separation

## ✨ Key Features
1.  **Secure JWT Authentication:** Sistem *login* yang diamankan menggunakan Token JWT dengan standar kunci rahasia yang kuat (51-character length).
2.  **Relational CRUD Management:** Manajemen data "Barang" yang terelasi secara dinamis dengan "Kategori".
3.  **Auto-Database Generation:** Backend dikonfigurasi untuk membuat tabel SQLite secara otomatis ketika API pertama kali dipanggil (*zero-config database*).
4.  **Premium Glassmorphism UI:** Antarmuka modern dengan efek kaca buram (*frosted glass*), *smooth hover physics*, dan layout yang responsif.
5.  **Anti-Silent Error Validation:** Sistem penanganan *error* terintegrasi dari CI4 hingga notifikasi interaktif di Vue UI.

## 🛠️ Installation & Setup Guide
Ikuti panduan berikut untuk menjalankan aplikasi secara lokal. Pastikan **PHP 8+**, **Composer**, dan **Node.js** sudah ter-install di mesin Anda.

### 1. Backend Setup (CodeIgniter 4 API)
Buka terminal dan arahkan ke folder `backend-api`:
\`\`\`bash
cd backend-api
composer install
php spark serve --port 8080
\`\`\`
*(Server API akan berjalan di `http://localhost:8080`)*

### 2. Frontend Setup (Vue 3 SPA)
Buka tab terminal baru dan arahkan ke folder `frontend-spa`:
\`\`\`bash
cd frontend-spa
npm install
npm run dev
\`\`\`
*(Aplikasi web akan berjalan di `http://localhost:5174` atau *port* yang disediakan oleh Vite)*

## 🔐 Default Login Credentials
Gunakan akses berikut untuk masuk ke dalam *Dashboard* (jika *database* baru saja di-generate):
*   **Email:** `admin@test.com`
*   **Password:** `password123`



---

## Hasil Prototype 

* link video : https://youtu.be/eyrUDYq3Ik8?si=d9fgllb6r0UAJ-G9

* link demo web : https://uas-web2-312410144-enrico.vercel.app/dashboard

*Developed by Enrico - UAS Web 2 Final Project.*