# AcademicAdvisor
### **_(Ubah file README.md ini setelah program diselesaikan)_**

## Latar Belakang
Kalian tentunya sudah tidak asing dengan akademik SI-X ITB. Namun, pengesahan mata kuliah harus melalui dosen wali, dan terdapat beberapa perbedaan antara satu dosen wali dengan dosen wali lainnya dalam menyikapi pengambilan mata kuliah yang diambil mahasiswa. Selain itu, ada beberapa mahasiswa yang tidak dapat bertemu dosen wali dengan tatap muka langsung karena berbagai kendala yang ada. Kalian tahu bahwa ada beberapa mata kuliah yang bisa diambil secara paralel tetapi tidak dimungkinkan dalam kurikulum. Kalian juga berpikir bahwa pengambilan mata kuliah juga tidak bisa diambil sembarangan karena ada *prerequisite* tertentu. Pada tugas kali ini kalian diminta untuk membuat *Website academic advisor* **khusus Informatika ITB** yang mirip dengan SI-X untuk membantu mengatasi permasalahan-permasalahan tersebut.

## Spesifikasi
1. *Website* dibuat dalam bahasa pemrograman, *framework*, dan *library* bebas.  
  
2. *Website* memiliki *register* yang terdiri dari *username*, nama, NIM, email, *password*, dan konfirmasi *password*. *Password* diharuskan untuk minimal terdiri dari 8 alfanumerik, dengan minimal 1 angka, minimal 1 huruf besar, minimal 1 huruf kecil, dan minimal 1 karakter spesial.  

3. *Website* memiliki fitur *login*.  
  
4. Setelah *login*, *Website* memiliki *dashboard* yang berisi grafik IP dan IPK setiap semester, tabel pengambilan mata kuliah setiap semester yang berisi kode mata kuliah, nama mata kuliah, SKS, dan indeks. Tabel pengambilan mata kuliah dalam semester terakhir dapat memiliki indeks kosong, jika belum dinilai.
 
5. Terdapat laman untuk memilih mata kuliah setiap semester, sesuai dengan semester terakhir yang ditampilkan di *dashboard* + 1. Misalkan semester terakhir yang ditampilkan di *dashboard* adalah 4. Ketika memilih mata kuliah, semester yang ditampilkan(beserta mata kuliah wajibnya) adalah semester 5. Mata kuliah yang dapat dipilih hanyalah **_mata kuliah wajib prodi dan mata kuliah pilihan dalam untuk kurikulum 2013 yang dibuka untuk angkatan 2016_**, sesuai dengan *prerequisite* yang tersedia pada prerequisite.txt. Silahkan perhatikan akademik.itb.ac.id untuk daftar mata kuliah yang sesuai. Untuk mata kuliah TPB, disamakan kode mata kuliah, nama mata kuliah, dan SKSnya. Asumsikan tidak ada semester pendek yang dibuka dan semua mata kuliah jika memenuhi *prerequisite*-nya dapat diambil. Mata kuliah dari jurusan lain yang diambil di Informatika ITB(dan dijadwalkan oleh Informatika ITB) tidak perlu dimasukkan.

6. Terdapat laman untuk melihat mata kuliah yang belum dipilih tiap semesternya. Tampilannya berbentuk tabel per semester dengan isi kode mata kuliah, nama mata kuliah, dan SKS.  

7. Terdapat laman untuk memberikan bantuan akademik yang terbaik untuk mahasiswa. Bantuan ini berisi daftar mata kuliah **terbaik** yang harus diambil mahasiswa sesuai ketentuan pengambilan maksimum SKS dalam satu semester berdasarkan IPnya dan *prerequisite* setiap mata kuliah. Laman ini dapat dibuka ketika semua indeks dalam semester yang paling terakhir diambil sudah diisi(kecuali pada semester pertama).  

8. Batas pengambilan mata kuliah adalah 4 semester untuk TPB dan 8 semester untuk jurusan, dengan batas minimum D untuk TPB dan C untuk jurusan. Mata kuliah yang belum lulus dapat diambil kembali di semester-semester berikutnya, tidak seperti pada Informatika ITB yang hanya bisa dipilih pada semester ganjil/semester genap saja.

9. Validasi masukan dibuat selengkap mungkin, dengan syarat-syarat yang semirip mungkin dengan dunia nyata. Silahkan beri komentar di program kalian untuk setiap validasi yang kalian lakukan.  

10. *Website* dapat menampilkan pesan kesalahan dan sebagainya secara intuitif.  

11. Tampilan *Website* dibebaskan, sehingga silahkan beri kreativitas terbaik kalian.

12.	Program memiliki *Readme* yang berisi:
- *Environment* pembuatan program(termasuk bahasa pemrograman, *framework*, dan *library* yang digunakan)
- Asumsi dalam pembuatan program(jika ada)
- Deskripsi **semua** algoritma yang digunakan untuk setiap fitur. Tuliskan algoritma-algoritma pentingnya saja
- Validasi yang dilakukan
- Aksi-aksi yang dilakukan ketika ada sesuatu di luar hal yang normal yang terjadi(seperti pesan kesalahan atau yang lainnya)
- Cara menggunakan program
- Data diri

13. Bonus:
- Autentifikasi dengan email std. Silahkan tambahkan autentifikasi dengan email std dan hubungkan dengan *register* biasa dengan email std tersebut(sebuah email std dapat di-*register* dengan autentifikasi Google dan *register* biasa).
- Tambahkan permasalahan semester genap/ganjil(ada beberapa mata kuliah yang hanya bisa diambil di semester ganjil/semester genap saja) dan pengubahan definisi *prerequisite* yang sebelumnya artinya "sudah pernah diambil" menjadi "sudah lulus"
  
12. **_Program harus ditulis dengan menggunakan nama-nama variabel, fungsi, dan prosedur yang dapat dimengerti. Program perlu memasukkan komentar pada beberapa bagian yang mungkin tidak mudah ditangkap dengan baik oleh saya._**  
  
13. **_Jika memiliki asumsi, tanyakan terlebih dahulu kepada saya. Asumsi yang dituliskan dalam *Readme* adalah setiap pertanyaan yang saya jawab, “Asumsikan sendiri.”_**  
  
14. **_Penilaian tugas ini dalam bentuk fitur-fitur, sehingga jika ada yang ingin mengirimkan program yang tidak lengkap, silahkan dikumpulkan saja._**  

## Penilaian
1. Fitur yang diuji adalah sebagai berikut:
- *Register*
- *Login*
- Pemilihan mata kuliah
- Tampilan mata kuliah yang belum diambil
- *Akademik Advisor*
- Kelengkapan validasi
- Kelengkapan respon atas kejadian yang tidak normal
- Kreativitas
- Bonus
  
2. *Deliverable* utama akan memberikan nilai 6000 per orangnya, dan setiap bonus bernilai 1000 sehingga total nilai yang bisa didapat adalah 8000.
