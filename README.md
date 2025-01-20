💬 ChatApp - Aplikasi Chatting Real-Time
Hai! 👋 Selamat datang di ChatApp, aplikasi chatting modern yang bikin kamu bisa ngobrol real-time sama teman-teman kamu, plus cari teman baru dengan mudah. Simpel, cepat, dan tampilannya kece abis! 🚀

✨ Fitur Kece di ChatApp
⚡ Chat Real-Time: Pesan langsung nyampe tanpa nunggu lama.
🧑‍🤝‍🧑 Tambah Teman: Cari teman pakai nomor HP atau email mereka. Mudah banget!
📱 Tampilan Responsif: Desainnya cakep banget, cocok buat di HP, tablet, atau laptop.
🔒 Login Aman: Pakai Firebase biar akun kamu tetap aman.
🛠️ Teknologi di Balik ChatApp
Ini nih teknologi keren yang bikin ChatApp jalan:

🖥️ Framework: Next.js 14 (Pages Router)
🗃️ Database: Firebase Firestore
🔐 Autentikasi: Firebase Authentication
🎨 Styling: Tailwind CSS
🚀 Mulai Pakai ChatApp
Persiapan Awal
Sebelum mulai, pastikan:

Kamu udah instal Node.js.
Udah punya proyek Firebase (aktifin Firestore dan Authentication).
Langkah Instalasi
Clone repo ini ke komputer kamu:
bash
Copy
Edit
git clone https://github.com/username/chatapp.git  
cd chatapp  
Install semua dependensinya:
bash
Copy
Edit
npm install  
Bikin file .env.local di folder utama, terus tambahin konfigurasi Firebase kayak gini:
env
Copy
Edit
NEXT_PUBLIC_FIREBASE_API_KEY=your-api-key  
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your-auth-domain  
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your-project-id  
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your-storage-bucket  
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id  
NEXT_PUBLIC_FIREBASE_APP_ID=your-app-id  
Jalankan Aplikasi
Start server-nya:
bash
Copy
Edit
npm run dev  
Buka http://localhost:3000 di browser kamu buat lihat aplikasinya.
📸 Tampilan ChatApp
Nih, sneak peek tampilannya (tambahin screenshot di sini):


🤝 Bantu Kembangin ChatApp
Pengen bantu nambah fitur atau ngasih ide? Caranya gampang banget:

Fork repo ini.
Bikin branch baru: git checkout -b fitur/nama-fitur-kamu.
Commit perubahan: git commit -m "Tambah fitur ini itu".
Push ke branch: git push origin fitur/nama-fitur-kamu.
Buat pull request.
📜 Lisensi
Santai aja, proyek ini open-source di bawah MIT License. Jadi bebas mau dipake buat belajar atau dikembangin lagi.

📬 Kontak
Ada ide, saran, atau cuma mau ngobrol? Yuk, kontak aku:

📧 Email: your-email@example.com
🐙 GitHub: @yourusername
