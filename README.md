# Assignment 3 HCI
- - - -

## TEAM I ##

  1. Muhammad Bagas Pradana (1313618015)
  2. Adi Rahman (1313618037)
  3. Moh. Falend Wandamen (1313618027)

## Web App ##
* Nama Web App : SIPKU (Sistem Presensi KPM UNJ).
* Tipe User : Fixed 
* Scope : organisasi 
* User : seluruh anggota organisasi

## 1st phase requirement gathering ##

### proofs : [wawancara bersama perwakilan KPM (Zuhri Ramadhan)](https://www.youtube.com/watch?v=FTx2rQYrC_k) ###

### Mini Report ###

Kami melakukan interview untuk mendapatkan data gathering dari organisasi KPM UNJ. KPM (Kelompok Peneliti Muda) adalah Unit Kegiatan Mahasiswa yang bergerak dalam bidang keilmiahan berbasis penalaran dan penelitian yang ada di Universitas Negeri Jakarta (UNJ). KPM UNJ memiliki berbagai kegiatan, seperti kegiatan nalar ilmiah (nalari), training of trainer (tot), pengabddian masyarakat, expo, program pendanaan penelitian, dan seminar hasil penelitian KPM UNJ. Zuhri Ramadhan selaku narasumber dari interview yang dilakukan, menuturkan bahwa KPM UNJ telah memiliki website, yang mana pada website KPM UNJ saat ini hanya digunakan sebatas pengenalan KPM UNJ. Kemudian kami menanyakan terkait siklus internal organisasinya, kemudian Zuhri menuturkan bahwa KPM UNJ masih  menggunakan pendekatan manual dalam menjalankan kegiatannya. Seperti pengerjaan administrasi, perancangan serta pelaksanaan program kerja.

Kemudian, saat kami menanyakan terkait kendala KPM UNJ saat ini, zuhri menuturkan bahwa dari tahun ke tahun KPM UNJ memiliki masalah terkait pendataan presensi acara yang telah dibuat oleh KPM UNJ. KPM UNJ memiliki program kerja yang cukup banyak, dimana setiap anggota organisasi KPM diharapkan selalu mengikuti rangkaian agenda program kerja yang telah KPM buat. Zuhri mengutarakan opininya terkait pendataan presensi, berdasarkan pengalaman yang telah dirasakan Zuhri selaku kepala biro kerestari (Kesekretariatan) bahwa pada masa-masa berjalannya kegiatan organisasi, terkait presensi ini masih belum terasa problemnya. Namun saat sudah memasuki masa akhir kepengurusan organisasi yang mana melakukan penyusunan Laporan Pertanggung Jawaban akhir kepengurusan, masalah presensi ini tidak bisa dihindarkan. hasil akhirnya yaitu data pada Laporan Pertanggung Jawaban akhir ini tidak selalu akurat. 

Berdasarkan interview yang telah kami lakukan, zuhri selaku perwakilan KPM UNJ memiliki pesan untuk web app SIPKU agar fitur-fitur ini dapat ditambahkan / digunakan, sehingga dapat menyelesaikan masalah terkait presensi ini, yaitu diantaranya :

1. Admin dapat mendaftarkan anggotanya sehingga setiap anggota organisasi memiliki akun pribadinya masing-masing.
2. Admin dapat memilih apakah user / anggota organisasi dapat diizinkan hadir atau tidak diizinkan hadir dalam mengikuti agenda acara.
3. Admin dapat melihat data hasil presensi setiap anggotanya, sehingga diakhir masa kepengurusan organisasi, Admin tinggal melihat history data dalam melakukan pendataan.
4. Karena setiap anggota KPM memiliki Unik ID nya masing-masing. Diharapkan Admin dapat membuat / mendaftarkan anggotanya berdasarkan Unik ID. Sehingga setiap anggota memiiki akun khusus / unik nya masing-masing. Kode unik ini bisa menggunakan Nomor Tanda Anggota.
5. Pada halaman login, setiap User harus login menggunakan Kode Unik dan passwordnya masing-masing.
6. Tidak perlu adanya halaman register. Agar tidak sembarangan orang bisa membuat akun diluar kendali admin.

## 2nd Phase Requirement Gathering ##
### proofs : [Conference bersama perwakilan KPM (Zuhri Ramadhan)](https://youtu.be/SSmty-wAsoc) ###

## Mini Report ##

Pada tahap ini, kami telah melakukan konferensi bersama perwakilan KPM UNJ untuk menjelaskan hasil rancangan app yang sedang kita bangun. Kami menjelaskan kepada perwakilan KPM bahwa aplikasi yang kita bangun ini full responsive, artinya web app yang kami rancang ini mendukung segala tampilan jika diakses menggunakan perangkat yang memiliki ukuran layar yang berbeda. Kemudian kami menjelaskan bahwa user dapat mengubah data profil di halaman dashboard profil di akun mereka masing-masing, hal ini bertujuan agar user dapat mengganti keterangan data mereka jika sewaktu-waktu admin salah memasukan data pribadi mereka. Namun setiap user tidak dapat merubah keterangan terkait nomor anggota mereka, dikarenakan nomor anggota ini sebagai unique ID mereka masing-masing yang didapatkan saat mereka mendaftarkan diri kedalam keanggotaan KPM UNJ.
