# WINA SUSANTI R.// NIM : 352310473 (PRAKTIKUM 6)
# Deskripsi Program Daftar Nilai Mahasiswa

Program ini digunakan untuk mengelola data mahasiswa, menghitung nilai akhir, dan menampilkan daftar mahasiswa dalam format tabel. berikut perintah programnya : 

![praktikum 6 satu](https://github.com/user-attachments/assets/9686ba51-63ff-429b-ba67-4204db83768e)
![praktikum 6 dua](https://github.com/user-attachments/assets/fc376783-a732-4f82-b202-c4f98ce8185b)

## Fungsi `hitung_nilai_akhir`

### Tujuan
Menghitung nilai akhir mahasiswa berdasarkan nilai tugas, UTS, dan UAS.

### Parameter
- **nilai_tugas**: Nilai tugas mahasiswa (float).
- **nilai_uts**: Nilai UTS mahasiswa (float).
- **nilai_uas**: Nilai UAS mahasiswa (float).

### Rumus
Nilai akhir dihitung dengan rumus:
Akhir = (Tugas * 0.3) + (UTS * 0.35) + (UAS * 0.35)

### Return
Mengembalikan nilai akhir yang telah dihitung (float).

## Inisialisasi Data

- data_mahasiswa : Menyimpan data mahasiswa dengan NIM sebagai kunci dan informasi mahasiswa (nama, nilai tugas, UTS, UAS, dan nilai akhir) sebagai nilai.

## Input Data Mahasiswa

Program meminta pengguna untuk memasukkan data mahasiswa dalam format berikut:
1. **Nama**: Nama lengkap mahasiswa.
2. **NIM**: Nomor Induk Mahasiswa.
3. **Nilai Tugas**: Nilai yang diperoleh dari tugas.
4. **Nilai UTS**: Nilai yang diperoleh dari Ujian Tengah Semester.
5. **Nilai UAS**: Nilai yang diperoleh dari Ujian Akhir Semester.

Setelah data dimasukkan, program akan menghitung nilai akhir menggunakan fungsi `hitung_nilai_akhir`.

## Menyimpan Data

Data mahasiswa disimpan dalam format dictionary di dalam `data_mahasiswa`, di mana setiap NIM menjadi kunci dan informasi mahasiswa menjadi nilai.

## Menanyakan Tambah Data

Setelah memasukkan data mahasiswa, program menanyakan kepada pengguna apakah ingin menambah data mahasiswa lagi. Jika pengguna memasukkan 'y', program akan kembali ke awal loop. Jika tidak, program akan melanjutkan untuk menampilkan daftar mahasiswa.

## Menampilkan Daftar Mahasiswa

Setelah pengguna memilih untuk tidak menambah data lagi, program menampilkan daftar semua mahasiswa yang telah dimasukkan dalam format tabel. Tabel mencakup:
- **No**: Nomor urut mahasiswa.
- **Nama**: Nama lengkap mahasiswa.
- **NIM**: Nomor Induk Mahasiswa.
- **Tugas**: Nilai tugas mahasiswa.
- **UTS**: Nilai Ujian Tengah Semester.
- **UAS**: Nilai Ujian Akhir Semester.
- **Akhir**: Nilai akhir yang telah dihitung.

### Contoh Output

![hasil pemograman praktikum 6](https://github.com/user-attachments/assets/bcbc5920-8f6e-4f58-904a-88e11e18ac33)


### Flowchart 

![program phyton](https://github.com/user-attachments/assets/1bbeb674-3b5b-4025-8ba0-1825c2f4817a)


