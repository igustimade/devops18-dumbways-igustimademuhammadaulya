# 1. Deploy Aplikasi wayshub-frontend (NodeJS)
<img width="599" alt="Screenshot 2023-08-31 at 00 09 27" src="https://github.com/igustimade/devops18-dumbways-igustimademuhammadaulya/assets/143378795/921f873b-ef1c-4b8a-86d6-27c16043410d">

- Menginstall NVM dengan curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
<img width="559" alt="Screenshot 2023-08-31 at 00 09 08" src="https://github.com/igustimade/devops18-dumbways-igustimademuhammadaulya/assets/143378795/b8aeaa1a-6513-4242-a1f1-7fa689a79490">

- Menggunakan nvm install 16 untuk memakai NodeJS versi 16, tetapi terjadi kegagalan dikarenakan nvm belum terdeteksi.
<img width="523" alt="Screenshot 2023-08-31 at 00 12 01" src="https://github.com/igustimade/devops18-dumbways-igustimademuhammadaulya/assets/143378795/e8653c0a-f942-4a44-8a48-ae37e6ef244f">

- Memakai perintah exec bash sudah dipastikan bahwa nvm sudah terdeteksi
<img width="1146" alt="Screenshot 2023-08-31 at 00 12 23" src="https://github.com/igustimade/devops18-dumbways-igustimademuhammadaulya/assets/143378795/64ea0cea-7bb5-4fe5-b2b8-8064fe510232">

- Nvm install 16 sudah bisa di install
<img width="250" alt="Screenshot 2023-08-31 at 01 32 18" src="https://github.com/igustimade/devops18-dumbways-igustimademuhammadaulya/assets/143378795/d1671d80-038f-4b84-9fd8-18470f156a9f">

- Dengan nvm use 16 untuk pengecekan versi apa yang sedang kita pakai
<img width="456" alt="Screenshot 2023-08-31 at 01 30 58" src="https://github.com/igustimade/devops18-dumbways-igustimademuhammadaulya/assets/143378795/727ceb53-f03c-466d-b4b1-1b325c741069">

- Jika sudah beres dengan penginstallan kita bisa lanjut dengan git clone https://github.com/dumbwaysdev/wayshub-frontend
<img width="544" alt="Screenshot 2023-08-31 at 01 41 14" src="https://github.com/igustimade/devops18-dumbways-igustimademuhammadaulya/assets/143378795/32d628be-f0ad-45de-a718-72a036ad1163">

- Pertama melihat list apa saja yang ada di directory dengan perintah ls, kedua masuk kedalam directory dengan perintah cd wayshub-frontend, dan bila sudah memasuki directory langsung menggunakan perintah npm install -y
<img width="359" alt="Screenshot 2023-08-31 at 01 52 17" src="https://github.com/igustimade/devops18-dumbways-igustimademuhammadaulya/assets/143378795/15be63c3-8f2b-4992-ac33-841878a070e3">

- Untuk menjalankan npm harus menggunakan perintah npm start
<img width="1440" alt="Screenshot 2023-08-30 at 23 48 55" src="https://github.com/igustimade/devops18-dumbways-igustimademuhammadaulya/assets/143378795/8e290416-a0ce-41c5-aaa2-68a51b0a2b16">

- Langkah terakhir harus melakukan pengecekan terhadap browser dengan menambahkan :3000 dibelakang ip server yang kita miliki (contoh: 192.168.1.5:3000).

# 2. Deploy Golang & Python dengan menampilkan nama masing-masing
