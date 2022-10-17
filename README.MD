# Writing Test Week 2 Advance
## **Javascript Intermediet**
### **Git & Github**
- Git adalah Tools para programmer dan Version Control System.
- Version Control System yaitu mencatat perubahan file atau pada saat terjadinya update file pada suatu proyek yang dibuat individu ataupun secara tim.
- Git juga sebagai tempat penyimpanan file pemrograman sehingga lebih efektif
- Dengan Menggunakan Git dan Github programmer bisa bekerja atau berkolaborasi mengerjakan proyek yang sama
- Reporsitory yaitu direktori proyek yang kita buat
- 3 Kondisi file pada GIT :
1. Modified (sudah ditandai) adalah kondisi perubahan yang sudah dilakukan namun belum ditandai(untracked) dan belum disimpan.
2. Stage adalah kondisi revisi yang sudah ditandai namun belum disimpan.
3. Commited adalah kondisi dimana revisi yang sudah disimpan.

- Git Branch adalah fitur yang wajib digunakan untuk berkolaborasi dengan programmer lain, contoh
```
git branch fitur_register
```
Perintah git diatas ini bertujuan untuk membuat git branch yang baru dan juga melihat list branch yang sudah ada.

- Git Branch pun juga terdapat perintah pindah ke branch tertentu dengan perintah :
```
git checkout fitur_register
```
hasilnya switched to 'fitur_register'

- Kalau mau delete branch yaitu perintah git branch -d <branch>

### **Responsive Web Design**
- RWD ini bertujuan membuat desain website dapat diakses dalam device mana saja seperti smartphone atau tablet dll.
- Sebelum membuat suatu aplikasi kita harus memikirkan user yang menggunakannya
- Chrome Dev Tools adalah tools bawaan yang ada pada setiap browser untuk mempermudah proses development website
- Untuk mengakses Chrome Dev Tools  yaitu dengan cara ctrl + Shift + J untuk windows
- Media Query adalah temen RWD.
- Media Query terdapat 2 jenis yaitu rwd menggunakan min-width dan max-width
```
@media screen and (min-width: your pixel){
    /* isi tag element html dan css*/
}

@media screen and (max-width: your pixel){
    /* isi tag element html dan css*/
}
```

- Beberapa styles bergantung pada jenis device yang digunakan dalam menggunakan Media query
- Disini terdapat cara membuat file css untuk masing-masing device yang berbeda :

```
<link rel="stylesheet" media="screen and (max-width: 500px)" href="styles/main.mobile.css">
```
Diatas ini kita bisa menggunakan cara yang sama seperti link css

- Breakpoint adalah tampilan berubah pada saat ganti device atau ukuran width

### **Bootstrap**
- Bootstrap adalah toolkit yang umumnya dipakai oleh para front end untuk framework
- Bootstrap adalah framework HTML, CSS, dan JavaScript yang berfungsi untuk mendesain website responsive dengan cepat dan mudah. 
- Manfaat Bootstrap yaitu :
1. Menjadi Website Mobile Friendly lebih mudah
2. mudah dalam mengubah bentuk gambar atau resize image
3. menambahkan element website tidak ribet
4. membuat website menjadi lebih interaktif
