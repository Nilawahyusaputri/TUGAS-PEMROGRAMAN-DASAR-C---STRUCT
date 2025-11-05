# TUGAS-PEMROGRAMAN-DASAR-C---STRUCT
TUGAS PEMROGRAMAN DASAR C - NILA WAHYU SAPUTRI - 22/500252/TK/54820

Penjelasan Alur Program
1. Input Data Mahasiswa
  Fungsi readStudents() meminta pengguna memasukkan nama depan, nama belakang, dan nilai ujian untuk setiap mahasiswa.
  → Data disimpan dalam array students[].

3. Menentukan Grade
  Fungsi assignGrades() memanggil fungsi scoreToGrade() untuk setiap mahasiswa.
  → Grade ditentukan berdasarkan rentang nilai:
    90–100 = A
    80–89 = B
    70–79 = C
    60–69 = D
    <60 = F

4. Menemukan Nilai Tertinggi
  Fungsi findHighestScore() mencari nilai tertinggi dalam array students[] dengan membandingkan setiap nilai.
  → Nilai tertinggi disimpan dalam variabel highest.

5. Menampilkan Data dan Hasil Akhir
  Fungsi printAll() menampilkan seluruh nama, nilai, dan grade mahasiswa.
  Fungsi printTopScorers() menampilkan nama-nama mahasiswa yang nilainya sama dengan highest.
