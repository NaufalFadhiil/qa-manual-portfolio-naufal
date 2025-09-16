# 🎭 Fake REST API - Books Testing

Project ini merupakan bagian dari **tugas pelatihan MySkill - Software Quality Assurance (QA Test Activity: Test Planning)**. <br>
Pengujian berfokus pada fitur **Books** di Fake REST API dengan metode manual testing menggunakan **Postman**. <br>
Pengujian dilakukan secara manual menggunakan **Postman**, dengan tujuan memverifikasi fungsionalitas **CRUD (Create, Read, Update, Delete),** validasi data, serta penanganan error.

## 📌 Tujuan
- Memverifikasi fungsi CRUD pada endpoint `/api/v1/Books`.
- Memastikan data yang dikirim dan diterima konsisten.
- Menguji respon API terhadap skenario negatif (invalid data, duplicate ID, dll).

## 📌 Scope
- **In Scope**: Semua operasi terkait endpoint `/api/v1/Books` (GET, POST, PUT, DELETE).
- **Out of Scope**: Pengujian performa, pengujian keamanan lanjutan, dan integrasi dengan endpoint lain.

## 📌 Tools
- **Postman v10**
- **Fake REST API**: [https://fakerestapi.azurewebsites.net/api/v1/Books](https://fakerestapi.azurewebsites.net/api/v1/Books)

## 🗂️ Link Google Drive
Dokumen lengkap bisa diakses di Google Drive:  
🔗 [Link Drive Portfolio Test Planning (MySkill) - Fake REST API Books](https://drive.google.com/drive/folders/1jynIsETRC1gyUjRLEwxO1Vt7nBHjBSIi?usp=sharing) <br>

Isi dokumen:  
- **Test Plan dan Test Case** – strategi, ruang lingkup, dan daftar test case.  
- **Bug Report** – laporan detail temuan bug selama pengujian.  
- **Test Summary Report** – ringkasan hasil pengujian, metrik, serta analisis kualitas. 

## 📊 Hasil Pengujian Singkat
- **Total Test Cases**: 8  
- **PASS**: 1  
- **FAIL**: 7  
- **Pass Rate**: 12.5%  
- **Fail Rate**: 87.5%  

Mayoritas fungsi CRUD mengalami kegagalan, terutama pada **POST, PUT, dan DELETE**.  
Kualitas API dinilai **buruk** dan tidak layak dirilis tanpa perbaikan menyeluruh.

---
✍️ **Penulis**: Naufal Fadhiil  
📅 **Tanggal**: September 2025 <br>
🎓 **Tugas**: MySkill – Software Quality Assurance (Test Planning)
