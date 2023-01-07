# Notes App w/ Hapi.js

### Pendahuluan

Ini adalah aplikasi catatan web sederhana yang dibangun dengan Hapi.js. Pengguna dapat membuat, membaca, memperbarui, dan menghapus catatan melalui aplikasi.

### Instalasi
1. Pastikan Anda telah memasang Node.js dan npm di komputer Anda.
2. Clone repository:

        git clone https://github.com/tamathecxder/notes-app.git

3. Masuk ke direktori proyek:

        cd notes-app

4. Pasang dependency:

        npm install

5. Menjalankan aplikasi
Jalankan perintah berikut untuk memulai aplikasi:

        npm start

6. Buka browser web Anda dan buka http://localhost:3000 untuk melihat aplikasi.

### Catatan

- Jika Anda ingin menjalankan aplikasi dalam mode pengembangan, Anda dapat menggunakan perintah npm run dev sebagai gantinya. Ini akan mengaktifkan nodemon yang akan otomatis menyalakan ulang server setiap kali Anda membuat perubahan pada kode.

- Aplikasi ini menggunakan file JSON untuk menyimpan catatan. File tersebut terletak di server/data/notes.json. Pastikan Anda memiliki izin tulis untuk file ini jika ingin dapat membuat, memperbarui, dan menghapus catatan melalui aplikasi.

