# Day-1-Red Dead Redemption 2_Justin Nicholas
Nama: Justin Nicholas

Pengertian singkat:
Repository merupakan tempat menyimpan satu proyek lengkap seperti kode program, file pendukung, dokumentasi, dan riwayat perubahan dari awal proyek sampai versi terbaru. Repository biasanya dikelola dengan sistem kontrol versi seperti Git dan disimpan secara online di platform seperti GitHub, GitLab, atau Bitbucket.

Tujuan atau kegunaan:
Menyimpan proyek di satu tempat, sehingga semua file terorganisir dan tidak tercecer.
Mencatat riwayat perubahan, jadi kamu bisa melihat siapa mengubah apa dan kapan, serta kembali ke versi lama jika terjadi kesalahan.
Memudahkan kerja tim, karena banyak orang bisa mengerjakan proyek yang sama tanpa saling menimpa pekerjaan.

Dokumentasi Workshop Day 1

Nama: Justin Nicholas 
Pemateri: Nugi Farhan
Materi: Building with AI, Managing Change with GitHub

1. Rangkuman Materi

Prompt engineering merupakan langkah-langkah menyusun instruksi supaya AI memberi jawaban yang tepat dan relevan. Prompt yang baik memuat empat unsur: Role (peran AI), Task (tugas), Context (kebutuhan dan batasan), dan Format (bentuk hasil yang diminta). Prompt yang lebih spesifik menghasilkan jawaban yang lebih baik dibanding prompt singkat tanpa konteks.

Git dan GitHub

Git adalah version control system yang berjalan di komputer lokal untuk mencatat perubahan file.
GitHub adalah platform online untuk menyimpan repository Git dan berkolaborasi.
Alur kerja Git: Working Directory → Staging Area → Repository.

Perintah dasar

Perintah	Fungsi
git init	Membuat repository baru
git add .	Memindahkan file ke staging area
git commit -m "pesan"	Menyimpan perubahan ke repository
git remote add origin <url>	Menghubungkan repo lokal ke GitHub
git push origin main	Mengirim commit ke GitHub
git pull origin main	Mengambil perubahan dari GitHub

Setup: install Git dan VS Code, atur identitas (user.name, user.email), buat SSH key, daftarkan ke GitHub, lalu cek dengan ssh -T git@github.com.

Proyek: membuat Student Task Planner dengan AI, lalu git init, commit, push ke GitHub, ubah isi, dan commit serta push lagi.

2. Poin Penting dan Pengetahuan Baru
Kualitas hasil AI bergantung pada kualitas prompt.
Menyertakan batasan (constraints) pada prompt membuat hasil lebih sesuai kebutuhan.
Git dan GitHub berbeda: Git untuk melacak perubahan, GitHub untuk menyimpan dan berkolaborasi.
Ada staging area sebelum commit, jadi kita bisa memilih perubahan yang dimasukkan.
Commit menyimpan riwayat perubahan sehingga bisa kembali ke versi lama.
SSH key membuat koneksi ke GitHub lebih aman dan praktis.

3. Pendapat Pribadi tentang Day 1
Menurut saya, day 1 workshop ini bermanfaat karena menggabungkan penggunaan AI dengan pengelolaan kode menggunakan Git dan GitHub. Saya memahami bahwa hasil AI sangat dipengaruhi oleh cara kita menulis prompt. Bagian tersulit bagi saya adalah penerapan dan pengertian konsep penggunaan Git/Github di awal-awal, tetapi bisa dipahami setelah dipelajari sedikit demi sedikit.