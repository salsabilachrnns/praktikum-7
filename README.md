## Salsabila - NIM : 352310495
# Penjelasan Program Daftar Nilai Mahasiswa

Program ini dibuat untuk mengelola dan menampilkan daftar nilai mahasiswa dengan menggunakan dictionary. Pengguna dapat melakukan berbagai operasi seperti menambah, mengubah, menghapus, melihat, dan mencari data mahasiswa. Nilai akhir mahasiswa dihitung berdasarkan nilai tugas, UTS, dan UAS. Berikut ini gambar perintah program yang sudah dibuat dalam phyton:


![tampilan kedua](https://github.com/user-attachments/assets/48d05d9d-1991-405e-bfad-548cf79a5b11)
![tampilan kedua part 2](https://github.com/user-attachments/assets/f5e57947-f01a-4d0c-b969-e073a735e0e6)


## Alur perintah program

### 1. `hitung_nilai_akhir(nilai_tugas, nilai_uts, nilai_uas)`
- **Deskripsi**: Menghitung nilai akhir mahasiswa berdasarkan komponen nilai.
- **Parameter**:
  - `nilai_tugas`: Nilai tugas mahasiswa.
  - `nilai_uts`: Nilai UTS mahasiswa.
  - `nilai_uas`: Nilai UAS mahasiswa.
- **Rumus**:
  \[
  \text{Akhir} = (\text{Tugas} \times 0.3) + (\text{UTS} \times 0.35) + (\text{UAS} \times 0.35)
  \]
- **Return**: Mengembalikan nilai akhir yang telah dihitung.

## Struktur Data

### Dictionary `data_mahasiswa`
- **Kunci**: NIM mahasiswa.
- **Nilai**: Dictionary yang berisi:
  - `nama`: Nama mahasiswa.
  - `nilai_tugas`: Nilai tugas.
  - `nilai_uts`: Nilai UTS.
  - `nilai_uas`: Nilai UAS.
  - `nilai_akhir`: Nilai akhir yang dihitung.

## Menu Interaksi

Pengguna diberikan pilihan untuk melakukan operasi berikut:

1. **L. Lihat Data**
   - Menampilkan seluruh data mahasiswa dalam format tabel.

2. **T. Tambah Data**
   - Meminta input dari pengguna untuk menambahkan data mahasiswa baru, termasuk nama, NIM, nilai tugas, nilai UTS, dan nilai UAS. Data yang dimasukkan akan dihitung nilai akhirnya dan disimpan.

3. **U. Ubah Data**
   - Meminta NIM mahasiswa yang ingin diubah. Jika data ditemukan, pengguna dapat memperbarui nilai tugas, UTS, dan UAS. Nilai akhir akan diperbarui sesuai dengan perubahan.

4. **H. Hapus Data**
   - Meminta NIM mahasiswa yang ingin dihapus. Jika data ditemukan, maka data mahasiswa tersebut akan dihapus dari daftar.

5. **C. Cari Data**
   - Meminta NIM mahasiswa yang ingin dicari. Jika data ditemukan, program akan menampilkan informasi mahasiswa tersebut.

6. **K. Keluar**
   - Mengakhiri program.

## Contoh Interaksi

Berikut adalah tampilan dari perintah pengguna dengan program:

![hasil akhir](https://github.com/user-attachments/assets/7bac1052-dbe8-47fb-b8e2-37b769cb0a29)

