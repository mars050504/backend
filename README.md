🛠️ Job Portal Backend
Ini adalah backend dari aplikasi Job Portal yang dibangun menggunakan Node.js, Express, dan MongoDB. Aplikasi ini mendukung fitur autentikasi pengguna, manajemen pekerjaan, profil pengguna, dan pengunggahan berkas menggunakan Cloudinary.

🔗 Repository
👉 GitHub - backend

🚀 Deployment (Railway)
Backend ini dideploy menggunakan Railway.

Langkah-langkah deploy ke Railway:
Login ke railway.app.

Klik New Project > Deploy from GitHub repo.

Hubungkan dengan repo ini: https://github.com/mars050504/backend.git

Setelah repo berhasil dipilih, Railway akan otomatis:

Menginstall dependensi dengan npm install
Menjalankan server dengan npm run start atau sesuai script pada package.json
Tambahkan environment variables pada Railway:

PORT=8000
MONGO_URL=<URL MongoDB Atlas kamu>
SECRET_KEY=<JWT Secret>
CLOUDINARY_CLOUD_NAME=<cloudinary_name>
CLOUDINARY_API_KEY=<api_key>
CLOUDINARY_API_SECRET=<api_secret>
FRONTEND_URL=https://your-frontend.vercel.app
Setelah deploy berhasil, Railway akan memberikan URL backend, misalnya: https://your-backend.up.railway.app

🧪Jalankan Secara Lokal
#1. Clone Repo git clone https://github.com/mulyani07/backend.git cd backend

2. Install Dependensi
npm install

3. Buat File .env
PORT=8000 MONGO_URL=your_mongo_url SECRET_KEY=your_secret_key CLOUDINARY_CLOUD_NAME=your_cloudinary_name CLOUDINARY_API_KEY=your_api_key CLOUDINARY_API_SECRET=your_api_secret FRONTEND_URL=http://localhost:5173

4. Jalankan Server
npm run dev
