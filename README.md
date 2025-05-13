![Image](https://github.com/user-attachments/assets/09e4c50e-7904-4738-956a-a59c12c6fe3c)

Penjelasan Mengenai Symmetric Multiprocessor (SMP)
1️⃣ Pengertian SMP:
Symmetric Multiprocessor (SMP) adalah arsitektur komputer di mana dua atau lebih prosesor berbagi memori utama dan jalur komunikasi yang sama. Setiap prosesor memiliki akses yang sama terhadap memori, I/O, dan perangkat lainnya secara serempak. Semua prosesor dalam SMP bekerja di bawah satu sistem operasi tunggal, yang mengelola distribusi tugas di antara prosesor-prosesor tersebut.

2️⃣ Komponen Utama pada Diagram:
1. Processor (Pocessor, OProccessor, Poccesuc) - Ini adalah unit pengolah utama yang menjalankan instruksi. Setiap prosesor terhubung secara langsung dengan shared memory.

2. Shared Memory Bus (Shared Menoy Buis) - Jalur utama yang digunakan oleh semua prosesor untuk mengakses memori bersama (Mem Rerius, FA2, etc.).

3. I/O Controller (I/O Controleles) - Mengontrol input dan output dari perangkat keras seperti disk dan perangkat eksternal lainnya.

4. Disk Controller (DisK FXF) - Bertanggung jawab mengelola akses ke perangkat penyimpanan.

5. Cache (Cachire) - Setiap prosesor memiliki cache sendiri untuk mempercepat akses data.

6. Bus (Buus) - Jalur komunikasi antara prosesor dan modul memori serta I/O.

7. Interface Unit (Inncess for nullpitressor) - Mengelola koordinasi antara multiprosesor dalam komunikasi dan pengolahan data.

8. I/O Controller (I/O Controles) - Menghubungkan perangkat eksternal dengan sistem utama.

3️⃣ Kelebihan SMP:
1. Kinerja Tinggi (High Performance):

 - Dapat menjalankan beberapa proses secara bersamaan dengan distribusi beban di antara prosesor.

2. Resource Sharing:

 - Semua prosesor dapat mengakses memori dan I/O secara langsung sehingga meningkatkan efisiensi.

3. Reliabilitas Tinggi:

 - Jika salah satu prosesor gagal, yang lain tetap dapat melanjutkan proses, meningkatkan toleransi terhadap kesalahan.

4. Penskalaan Mudah (Scalability):

 - Penambahan prosesor baru cukup mudah dilakukan tanpa perlu perubahan arsitektur besar.

4️⃣ Kekurangan SMP:
1. Bottleneck pada Shared Memory Bus:

 - Jika banyak prosesor mengakses memori secara bersamaan, dapat terjadi kemacetan (bottleneck).

2. Masalah Konsistensi Cache (Cache Coherence Issue):

 - Setiap prosesor memiliki cache sendiri sehingga perlu mekanisme tambahan untuk menjaga konsistensi data di semua cache.

3. Biaya Tinggi:

 - Implementasi dan perawatan sistem multiprosesor membutuhkan biaya lebih besar dibandingkan single processor.

4. Kompleksitas Manajemen:

 - Mengelola sinkronisasi dan komunikasi antar prosesor membutuhkan manajemen yang rumit.




