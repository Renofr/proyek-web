
[README.md](https://github.com/user-attachments/files/22555568/README.md)
# Praktikum Git & GitHub

Repository ini dibuat untuk menyelesaikan **Tugas Praktikum 01 - Praktikum Berbasis Web**.  
Disusun oleh:

- **Nama** : Reno Fatullah Rifai  
- **NPM** : 4522210021  
- **Program Studi** : S1 Teknik Informatika, Fakultas Teknik, Universitas Pancasila  
- **Tahun** : 2025  

Link Repository: [GitHub - proyek-web](https://github.com/Renofr/proyek-web)

---

## 🎯 Tujuan Praktikum
- Mengenal dasar penggunaan Git untuk version control.  
- Membuat repository lokal dan menghubungkannya dengan GitHub.  
- Melakukan operasi dasar Git: inisialisasi, add, commit, push.  
- Melakukan pengelolaan perubahan file melalui branch dan merge.  

---

## ⚙️ Langkah Praktikum

### 1. Konfigurasi Awal Git
```bash
git config --global user.name "Reno Fatullah"
git config --global user.email "oficialreno@gmail.com"
```

### 2. Membuat Repository Lokal
```bash
mkdir proyek-web
cd proyek-web
git init
```

### 3. Membuat File Awal
```bash
echo "<h1>Selamat Datang</h1>" > index.html
mkdir css
echo "body { font-family: sans-serif; }" > css/style.css
```

### 4. Staging & Commit Pertama
```bash
git add .
git commit -m "feat: Inisialisasi proyek dengan file index dan style.css"
```

### 5. Hubungkan ke GitHub
```bash
git remote add origin https://github.com/Renofr/proyek-web.git
git branch -M main
git push -u origin main
```

### 6. Uji Commit Kedua (Update File)
```bash
echo "<h1>Selamat Datang, Reno!</h1><p>Ini commit kedua.</p>" > index.html
git status
git add index.html
git commit -m "update: menambahkan paragraf ke index.html"
git push
```

---

## ✅ Hasil
- Repository lokal berhasil dibuat dengan Git (`proyek-web`).
  <img width="975" height="194" alt="image" src="https://github.com/user-attachments/assets/a6b48bcc-de7b-4d66-964d-24caf5c67a37" />

- File `index.html` dan `style.css` berhasil ditambahkan dan dicommit.
  <img width="975" height="196" alt="image" src="https://github.com/user-attachments/assets/50ca1092-843a-4c7a-96b3-41a5eaa928d7" />

- Repository berhasil dihubungkan ke GitHub (`proyek-web`).
  <img width="975" height="232" alt="image" src="https://github.com/user-attachments/assets/17b93f40-78c3-4138-a739-7132eaaba200" />

- Perubahan pada file `index.html` berhasil dicatat sebagai commit kedua dan di-push ke GitHub.
  <img width="975" height="239" alt="image" src="https://github.com/user-attachments/assets/4fda7437-9659-4706-93be-f9657830c33d" />


---
