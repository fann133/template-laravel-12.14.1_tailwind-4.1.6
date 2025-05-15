# 👉 Template Laravel^12.14.1 pakai Tailwind^4.1.6

Versi Laravel yang digunakan: [Laravel^12.14.1](https://laravel.com/docs/12.x)

Template yang digunakan: [Tailwind^4.1.6](https://v3.tailwindcss.com/docs/guides/laravel)

---

## 🎥 Sambil Ngoding Wajib Hukumnya Mendengarkan lagu ini

[![Lihat Video Demo](https://img.youtube.com/vi/CtRIsakAgjQ/0.jpg)](https://youtu.be/CtRIsakAgjQ?si=Durnh1AAhMHUqCLS "Klik untuk menonton di YouTube")

---

## ⚙️ Cara Instalasi

```bash
# 1. Clone project
git clone https://github.com/fann133/template-laravel-12.14.1_tailwind-4.1.6.git

# 2. Masuk ke folder project
cd template-laravel-12.14.1_tailwind-4.1.6

# 3. Install dependencies Laravel
composer install

# 4. Install npm
npm install

# 5. Salin file .env dan sesuaikan konfigurasi database
cp .env.example .env

# 6. Generate app key
php artisan key:generate

# 7. Jalankan npm
npm run dev    //Saat lokal atau ngoding
npm run build //Saat mau upload ke hosting

# 8. Jalankan server lokal
php artisan serve
