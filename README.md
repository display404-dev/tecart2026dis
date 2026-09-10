NAMA : I WAYAN PANDE NESCARI

NIM : 260530911152

DIVISI : CYBER SECURITY

CTF : WEB EXPLOIT

TOOLS : WSL KALI, Burp Suit, Git Hub, Python

KALI

<img src="Screenshot 2026-09-09 224745.png" alt="Teks Alternatif" width="500"/>
<img src="Screenshot 2026-09-10 184136.png" alt="Teks Alternatif" width="500"/>

Burp Suit

<img src="Screenshot 2026-09-09 021326.png" alt="Teks Alternatif" width="500"/>

GitHub

<img src="Screenshot 2026-09-10 184854.png" alt="Teks Alternatif" width="500"/>

Python

<img src="Screenshot 2026-09-09 144216.png" alt="Teks Alternatif" width="500"/>

CHALANGE : 

undo  
<img src="Screenshot 2026-09-09 020753.png" alt="Teks Alternatif" width="500"/>

langkah-langkah :

step 1 ; mennggunakan  prompt base64 -d untuk mengembalikan string CHARACTER yang berisi versi string sumber yang telah dienkode base64.

step 2 : menggunakan command rev unntuk merevers atau memutar balikan text .

step 3 : menggunakan command tr '-' '_' untuk merubah semua simbol - menjadi _

step 4 : menggunakan command tr '()' '{}' untuk merubah semua simbol () menjadi simbol {}

step ke 5 / terakhir : menggunakan command tr 'a-zA-Z' 'n-za-mN-ZA-M' yang berfungsi untuk mengenkripsi atau mendekripsi teks menggunakan metode ROT13 (Rotate 13). 
Perintah ini akan menggeser setiap huruf alfabet sebanyak 13 posisi ke kanan. Karena total alfabet ada 26 huruf, jadi ketika kita menjalankan perintah ini dua kali pada teks yang sama, teks tersebut akan kembali ke bentuk aslinya.

WEB EXPLOIT :  

<img src="Screenshot 2026-09-09 021344.png" alt="Teks Alternatif" width="500"/>

**Langkah 1:** Salin *link* yang di berikan di chalange, kemudian buka *tools* Burp.

**Langkah 2:** Setelah *tools* Burp terbuka, aktifkan fitur **"Intercept On"**, kemudian buka *browser* di burp.

**Langkah 3:** Setelah halaman web berhasil terbuka, kembali ke *tools* Burp, kemudian pilih **"Forward All"** untuk meneruskan seluruh permintaan.

**Langkah 4:** Selanjutnya, lakukan proses registrasi dengan mengisi data yang diperlukan pada halaman web.

**Langkah 5:** Setelah proses registrasi selesai, kembali ke *tools* Burp, kemudian pilih **"Forward All"**. Setelah itu, kembali ke halaman web.

**Langkah 6:** Selanjutnya, masukkan kode OTP pada kolom yang telah disediakan.

**Langkah 7:** Setelah kode OTP dimasukkan, kembali ke *tools* Burp, kemudian hapus kode OTP tersebut.

**Langkah 8:** Setelah kode OTP dihapus, pilih **"Forward All"** untuk meneruskan permintaan. Setelah proses selesai, key akan ditampilkan.

