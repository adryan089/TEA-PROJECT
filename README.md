
## Tutorial TEA TESTNET


Pertama Regist di [https://gitpod.io/]

 - Klik demo/trial
-  Daftar isi nama belakang dan depan 
 - Klik Continue 10 hour / bisa connect akun linkedln agar dapat 50 hour

Lanjut Ke github dulu

Bikin repository
Copy code nya 

Kembali Ke gitpod

Paste kode nya

Setelah di terminal

Paste kode ini `npx create-next-app@latest`
 
Muncul ini 

What is your project named? my-app (bisa di ganti pakai namamu atau projectmu) 
Would you like to use TypeScript? No / Yes
Would you like to use ESLint? No / Yes
Would you like to use Tailwind CSS? No / Yes
Would you like to use src/ directory? No / Yes
Would you like to use App Router? (recommended) No / Yes
Would you like to customize the default import alias (@/*)? No / Yes
What import alias would you like configured? @/*

Enter enter aja

selanjutnya

- `git add .`
- `git init`
- `git add README.md`
- `git commit -m "first commit"`
- `git branch -M main`
- `git remote add origin` **https://github.com/pakekoderepositorikalian**

contoh **https://github.com/adryan/adryan.git**
kalian bisa copy di github pas udah bikin repository baru kalau ada tulisan already exists lanjut ke step berikutnya

- `git push -u origin main`

Kalau eror masuk ke setting user ada di sebelah kanan atas terus ke git provider lanjut permision di github nya centang semua

Setelah itu 

- `npm init`

pergi ke [https://npmjs.com]
create akun
Lanjut 
- `npm adduser`
Copy Kode yg ada di terminal ( catatan sudah login di npmjs.com) contohnya seperti ini [https://www.npmjs.com/login?next=/login/cli/f] paste di browser 
- `npm publish`   


Catatan Kalau misalkan Eror gak kedetek package.json cek di sebelah kiri ada berjejer folder 
nah cek klw ada 2 folder misalkan
skydash
skydashnew

Nah Kalian Run cd skydashnew (ini hanya contoh) 



Atau Kalau Misalkan Error nya Ada kata private
Maka solusinya buka file package.json 
cari kata private lalu hapus trus save

Run Ulang `npm publish`

DONE! 
tunggu 4 hari agar masuk dan terverifikasi di TEA PROJECT

**Update tea :**
Ubah version package json kalian ke 1.1.4

Caranya ? 
- Ke Gitpod kalian
- Cari file Package.json
- Ubah version
- Cari kata "type"
- hapus kata git dan .git diawal dan diakhir "url"="git+https://github.com/repositorimu.git"
- Pojok kanan titik tiga klik, terus close saved.
- Lanjut running npm publish ulang
- Done

**SOLUSI KETIKA MENGALAMI SCORE MERAH**
*dengan catatan project harus kedetek di TEA*
- buka [https://gitpod.io/]
- tambahin perintah ini satu-persatu
`npm i nama package`
`npm init --scope=@your-username NPM`
`npm adduser`
`npm publish --access public`

DONE!,

**Update!**
jika project kalian sudah terdeteksi dan berhasil.. 
- klik manual registration
- download file **tea.yaml**
- buka repository github kalian
- upload file **tea.yaml** di luar direktory project
- kembali ke [https://app.tea.xyz]
- klik validate
- kalau sudah jangan lupa stake point kalian untuk menyelesaikan misi stake
- Done
