# ✨ Erchat - app

Hai! 👋 Selamat datang di ChatApp, aplikasi chatting modern yang bikin kamu bisa ngobrol real-time sama teman-teman kamu, plus cari teman baru dengan mudah. Simpel, cepat, dan tampilannya kece abis! 🚀

Lihat Aplikasi : [Sigma-Todolist](https://sigma-todolist.vercel.app/)

- ✨ Fitur Kece di ChatApp
- ⚡ Chat Real-Time: Pesan langsung nyampe tanpa nunggu lama.
- 🧑‍🤝‍🧑 Tambah Teman: Cari teman pakai nomor HP atau email mereka. Mudah banget!
- 📱 Tampilan Responsif: Desainnya cakep banget, cocok buat di HP, tablet, atau laptop.
- 🔒 Login Aman: Pakai Firebase biar akun kamu tetap aman.

## 🛠️ Teknologi Utama

- ⚛️ **[Next.js](https://nextjs.org/) (App Router):** Framework React untuk membangun aplikasi web.
- 🔥 **[Firebase](https://firebase.google.com/):** Backend untuk autentikasi, database, dan lainnya.
- 🎨 **[Tailwind CSS](https://tailwindcss.com/):** Library CSS untuk styling.

## 🚀 Instalasi

Ikuti langkah-langkah di bawah ini untuk menjalankan proyek ini secara lokal.

### ⚙️ Prasyarat

Pastikan Anda sudah menginstal:

- 🟢 [Node.js](https://nodejs.org/) versi terbaru.
- 🟡 [Git](https://git-scm.com/).
- 🔵 Akun [Firebase](https://firebase.google.com/) untuk konfigurasi backend.

### 📦 Langkah Instalasi

1. **Clone repositori ini:**

   ```bash
   git clone https://github.com/riobima222/erchat-app.git
   cd erchat-app
Instal dependensi:

bash
Copy code
npm install
Konfigurasi Firebase:

🔧 Buat proyek di Firebase Console.

Aktifkan Cloud Firestore untuk menyimpan data tugas.
Buat file .env.local di root folder proyek dan tambahkan konfigurasi Firebase Anda:


```bash
NEXT_PUBLIC_FIREBASE_API_KEY=your-api-key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your-auth-domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your-project-id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your-storage-bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
NEXT_PUBLIC_FIREBASE_APP_ID=your-app-id
```
Konfigurasi NextAuth:
🔑 Tambahkan secret key untuk NextAuth di file .env.local:

```bash
NEXTAUTH_SECRET=your-secret-key
NEXTAUTH_URL=http://localhost:3000
```
Sesuaikan provider autentikasi di file NextAuth jika diperlukan.

Jalankan aplikasi:

bash
Copy code
npm run dev
Akses aplikasi di browser:

🌐 Buka http://localhost:3000 di browser Anda.

💡 Dibuat Oleh : Patrio Bimasuci. 💻✨

Semoga Bisa gan ! 😊
