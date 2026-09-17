Website ini merupakan proyek pembelajaran

kolaborasi Git dan GitHub.

## Anggota Tim

1. Nayla Mutiara - Project Manager

2. Diego Abdul Jabbar - Developer Profil

3. M. Naufal Al-Imtiyaaz - Developer Anggota 

4. Nida - Developer Anggota Kontak


Website dikembangkan menggunakan HTML5.
Berikut adalah jawaban dan refleksi singkat untuk LKPD 4 Kolaborasi Tim Menggunakan Git & GitHub:

---

## I. Pertanyaan Challenge 2: Clone Repository

Apa arti hasil `git status`?
Menunjukkan informasi status branch saat ini, apakah ada file yang berubah, atau apakah working directory sudah bersih (*clean*).

---

## J. Pertanyaan Analisis Challenge 3: Membuat Branch

Mengapa setiap developer tidak langsung bekerja pada `main`?
Agar branch utama (`main`) tetap bersih dan stabil dari kode yang belum diuji, serta menghindari bentrokan (*konflik*) langsung antar pekerjaan developer.

---

## N. Pertanyaan Challenge 5: Commit

Apa perbedaan pesan commit `git commit -m "update"` dan `git commit -m "Menambahkan halaman profil kelas"`?
`"update"` terlalu umum dan tidak jelas. Sedangkan `"Menambahkan halaman profil kelas"` secara spesifik menjelaskan perubahan apa yang dilakukan pada kode tersebut.
Mana yang lebih baik?
Lebih baik menggunakan pesan yang spesifik (`"Menambahkan halaman profil kelas"`) agar riwayat revisi mudah dibaca.

---

## U. Pertanyaan Analisis Challenge 11: Sinkronisasi

1. Apa fungsi `git pull`?
Mengambil pembaruan (kode terbaru) dari repository remote di GitHub dan menggabungkannya ke branch lokal.
2. Apa yang terjadi jika programmer tidak melakukan `git pull`?
Developer akan bekerja menggunakan kode lama dan berisiko besar mengalami konflik kode saat melakukan push atau merge.
3. Mengapa `main` harus dijaga agar tetap stabil?
Karena branch `main` adalah versi utama atau versi rilis yang siap digunakan atau di-deploy.

---

## X. Pertanyaan Conflict

1. Mengapa conflict terjadi?
Karena dua orang atau lebih mengubah baris kode yang sama pada file yang sama dan Git bingung versi mana yang harus dipilih.
2. Apakah conflict berarti Git rusak?
Tidak, konflik adalah hal yang normal dalam kolaborasi tim untuk memberitahu developer bahwa ada perubahan yang harus digabungkan secara manual.
3. Siapa yang harus menentukan versi kode yang benar?
Developer yang bersangkutan atau tim melalui diskusi bersama.
4. Mengapa komunikasi antar programmer penting?
Agar pembagian tugas jelas dan tidak ada anggota tim yang mengubah bagian file yang sama secara bersamaan tanpa koordinasi.

## AC. Refleksi Individu

1. Apa perbedaan bekerja sendiri dengan bekerja menggunakan Git dan GitHub?
Bekerja sendiri lebih mudah tanpa koordinasi, tetapi rentan hilang jika file rusak. Dengan Git/GitHub, pekerjaan bisa dicadangkan, dilacak riwayatnya, dan dikerjakan bersama tim secara rapi.
2. Apa manfaat branch?
Memungkinkan kita membuat fitur baru tanpa merusak kode utama yang sedang berjalan.
3. Mengapa Pull Request diperlukan?
Sebagai wadah untuk mendiskusikan, memeriksa, dan menyetujui perubahan kode sebelum dimasukkan ke branch utama.
4. Apa manfaat Code Review?
Meningkatkan kualitas kode, menemukan kesalahan atau bug lebih awal, dan berbagi ilmu antar anggota tim.
5. Error apa yang paling sulit kalian selesaikan?
Konflik saat *merge* atau error rejected non-fast-forward.
6. Bagaimana kalian menemukan solusinya?
Membaca pesan error dengan teliti, mencari solusinya di internet/AI, dan berdiskusi dengan kelompok.


7. Apa kontribusi terbesar kalian dalam kelompok?
Menyelesaikan tugas koding halaman sesuai peran dan aktif berkoordinasi saat *merge* serta memperbaiki kode.
8. Jika menjadi programmer profesional, kebiasaan apa dari kegiatan ini yang akan kalian pertahankan?
Tidak langsung mengubah kode di branch utama, menulis pesan commit yang jelas, dan melakukan code review.

---

## AE. Refleksi Akhir

* Sebelum belajar GitHub, saya berpikir bahwa menggabungkan kode banyak orang dalam satu proyek adalah hal yang sangat rumit dan membingungkan.
* Setelah melakukan kolaborasi dengan GitHub, saya memahami bahwa dengan sistem branch dan pull request, kerja tim menjadi jauh lebih terstruktur, aman, dan rapi.
* Kesalahan/error yang saya alami mengajarkan saya bahwa error bukanlah kegagalan, melainkan petunjuk untuk mencari tahu dan memperbaiki sistem.


* Jika saya bekerja sebagai programmer dalam sebuah tim, saya akan selalu berkomunikasi dengan baik, membuat branch khusus untuk setiap fitur, dan rajin melakukan pull serta commit yang jelas.