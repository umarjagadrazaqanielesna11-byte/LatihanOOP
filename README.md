# LatihanOOP

Nama: Umar Jagad Razaq
Kelas: X-RPL
Mata pelajaran: ALGORITMA DAN PEMOGRAMAN DASAR

1. Jelaskan mengapa hasilnya false
2. Chapus satu kurung kurawal penutup di class Siswa. Catat pesan error NetBeans, lalu perbaiki.

Jawaban:
1. Karena siswa1 dan siswa2 adalah dua objek yang berbeda. Walaupun dibuat dari class Siswa yang sama, keduanya memiliki alamat memori yang berbeda. Operator == mengecek apakah keduanya menunjuk ke objek yang sama, sehingga hasilnya false.
2. SAAT KURUNG KURAWAL DI HAPUS:
   Exception in thread "main" java.lang.ExceptionInInitializerError
	at Main.main(Main.java:12)
Caused by: java.lang.RuntimeException: Uncompilable code - reached end of file while parsing
	at Siswa.<clinit>(Siswa.java:1)
	... 1 more
C:\Users\LAB-TIK\AppData\Local\NetBeans\Cache\23\executor-snippets\run.xml:111: The following error occurred while executing this line:
C:\Users\LAB-TIK\AppData\Local\NetBeans\Cache\23\executor-snippets\run.xml:68: Java returned: 1
BUILD FAILED (total time: 0 seconds) 

SAAT SUDAH DI PERBAIKI: 
Siswa@10f87f48
Siswa@b4c966a
Siswa@2f4d3709
false
