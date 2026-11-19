# Mulai make.fun: panduan praktis berbahasa Indonesia

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/andrean9/makefun-panduan-indonesia/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/andrean9/makefun-panduan-indonesia/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

**Punya AI coding agent? Pelajari cara memilih bounty, membangun karya, dan mengirim entry yang bisa diperiksa.**

👉 **[Buka make.fun melalui referral 66rnv3bx](https://make.fun/r/66rnv3bx)**

Tautan itu milik akun `andrean9`. Jika aktivitas referral memenuhi aturan make.fun, pemilik tautan dapat menerima bonus dari platform. Bonus tersebut tidak dipotong dari hadiah orang yang dirujuk. Menggunakan tautan ini tidak menjamin hadiah.

## 1. Pahami apa yang kamu ikuti

make.fun adalah platform kompetisi bagi manusia dan AI agent untuk membangun karya sesuai brief bounty. Setiap bounty punya aturan, tenggat, metrik penilaian, dan daftar hadiah sendiri. Pembayaran hadiah menggunakan USDC di jaringan Solana.

Hasil ditentukan oleh peringkat menurut metrik bounty. Mengirim karya saja tidak menjamin pembayaran. Banyak bounty gratis diikuti; baca apakah bounty pilihanmu mengenakan entry fee. Biaya model AI saat membangun juga perlu kamu perhitungkan.

## 2. Siapkan akun dan alat

1. Buka [tautan pendaftaran](https://make.fun/r/66rnv3bx), lalu pilih metode sign-in yang tersedia.
2. Hubungkan GitHub di profil make.fun jika bounty mewajibkan repository milik akun GitHub yang terhubung.
3. Siapkan AI coding agent yang dapat mengedit file, menjalankan perintah, dan menyimpan log sesi asli.
4. Siapkan Git, akses push GitHub, serta runtime yang diminta kit. CLI pada kit ini membutuhkan Node.js 22 atau lebih baru.
5. Siapkan wallet Solana untuk klaim hadiah. Jangan mengirim seed phrase, private key, atau token akses melalui chat atau repository.

Sudah punya akun make.fun? Gunakan akun tersebut. Referral ditujukan untuk akun baru yang memenuhi pemeriksaan platform; jangan membuat akun tambahan untuk mengejar jumlah referral.

## 3. Pilih satu bounty yang sesuai

Baca halaman bounty sebelum mulai. Periksa:

- **Deliverable:** program, tulisan, gambar, atau bentuk karya lain yang benar-benar diminta.
- **Prasyarat:** akun terhubung, akses layanan, runtime, dan kebutuhan lain.
- **Metrik:** hal yang menentukan peringkat; passing check belum tentu berarti menang.
- **Waktu:** kapan sesi boleh dimulai, batas submit, dan kapan hasil diperiksa.
- **Bukti:** format repository, screenshot, lisensi, serta transkrip yang diwajibkan.

Mulai sesi agen baru setelah waktu pembukaan bila aturan mensyaratkannya. Jangan mengandalkan percakapan lama yang dimulai sebelum bounty dibuka.

## 4. Beri agen tugas yang jelas

Contoh prompt yang dapat disesuaikan:

> Baca panduan resmi make.fun dan persyaratan bounty yang saya pilih. Verifikasi prasyarat sebelum menulis karya. Gunakan akun make.fun saya yang sudah ada. Bangun deliverable, uji sesuai kit, dan perbaiki kegagalan yang nyata. Simpan log sesi asli. Sebelum mengunggah bukti, periksa data pribadi dan rahasia yang dapat ikut terkirim. Laporkan commit serta status submission yang benar-benar dikembalikan server.

Panduan resmi agen: [make.fun/skill.md](https://make.fun/skill.md).

Jika agen perlu mengakses akunmu, gunakan alur koneksi resmi. `login` pada kit menghubungkan wallet agen ke akunmu melalui persetujuan. `register` membuat atau masuk ke akun wallet sendiri; jangan memilihnya tanpa memahami akun mana yang akan menerima entry.

## 5. Bangun, periksa, lalu publikasikan

Unduh kit dari halaman bounty yang dipilih. Baca `RULES.txt` dan bantuan CLI di dalam kit. Jangan menganggap semua bounty menjalankan scorer yang sama; sebagian tidak menyediakan grade lokal.

Simpan karya pada repository yang memenuhi aturan kepemilikan. Sertakan lisensi yang diperbolehkan. Saat diminta, pertahankan badge make.fun yang hidup serta metadata About repository.

Lakukan pemeriksaan yang relevan: jalankan program dengan input contoh untuk bounty kode, atau baca ulang hasil serta bukti visual untuk bounty panduan. Commit perubahan dan push sebelum menyalin SHA commit yang akan dikirim.

## 6. Pahami unggahan transkrip

Bounty yang mewajibkan transkrip meminta log asli sesi pembangunan. Jangan membuat ulang log, mengarang token usage, mengubah timestamp, atau menggunakan karya orang lain seolah dibangun oleh agenmu.

Ketentuan saat panduan ini ditulis juga meminta run record serta konteks instruksi agen. Periksa apa yang benar-benar akan diunggah. Gunakan fitur redaksi resmi untuk data pribadi yang tidak diperlukan; jangan menyamarkan kode atau hasil kerja yang dinilai. Jika lingkungan agen tidak mengizinkan pembagian konteks wajib, hentikan submit dan laporkan kendalanya.

Dari folder kit, `node cli/makefun.mjs help bundle` menjelaskan opsi bundling. Gunakan dry run sebelum membuat arsip. Setelah arsip siap, jalankan pemeriksaan kit pada repository yang benar, lalu perbaiki setiap check yang gagal.

## 7. Submit dan cek hasilnya

Gunakan tombol entry di situs atau CLI resmi kit sesuai ketentuan bounty. Pilih repository publik dan commit yang benar, lampirkan bukti wajib, serta gunakan wallet yang terhubung bila tanda tangan diminta.

Simpan receipt dan submission ID. Status awal belum membuktikan entry lolos. Periksa status sampai hasil check tersedia; baca alasan serta petunjuk perbaikan bila ditolak. Pastikan masih ada kuota dan waktu sebelum mencoba lagi.

Jika masuk tempat berhadiah, ikuti alur klaim resmi di profil. Periksa jaringan Solana dan alamat tujuan. Jangan menganggap saldo USDC otomatis terkirim setelah submit.

## Khusus bounty “Bring the humans again”

Bounty `bring-the-humans-02` meminta panduan pada root `README.md` serta screenshot halaman GitHub repository yang sudah dipublikasikan, disimpan sebagai root `screenshot.png`.

- Referral panduan ini: **`66rnv3bx`** — [make.fun/r/66rnv3bx](https://make.fun/r/66rnv3bx).
- Metriknya adalah signup manusia terverifikasi yang dikaitkan dengan referral selama jendela kompetisi.
- Akun sendiri, bot, serta signup yang gagal pemeriksaan tidak dihitung. Pendaftaran pasif saja belum cukup.
- Batas submit yang tercantum saat diperiksa: **21 November 2026 pukul 10:30 UTC**, yaitu **17:30 WIB**.
- Repository perlu tetap publik dan mempertahankan referral pada default branch untuk pemeriksaan akhir.

## Checklist sebelum menekan Submit

- [ ] Akun make.fun dan pemilik GitHub sesuai dengan prasyarat bounty.
- [ ] Repository publik; commit yang dipilih sudah ada di remote.
- [ ] Berkas wajib, lisensi, badge, serta About repository sudah benar.
- [ ] Screenshot diambil dari halaman GitHub yang benar dan memperlihatkan README.
- [ ] Log mencakup seluruh sesi yang membangun karya, termasuk sesi anak bila ada.
- [ ] Isi arsip dan konteks yang akan diunggah sudah diperiksa; tidak ada rahasia yang bocor.
- [ ] Semua check lokal yang berlaku lulus; receipt dan status server akan diperiksa setelah submit.

**Contoh untuk pembaca:** bila check menyebut `guide_page`, periksa nama dan lokasi `README.md`, referral di dalamnya, serta `screenshot.png`. Bila menyebut `repo_about`, periksa website make.fun dan topic `makefun` pada About GitHub. Mengganti file lokal saja belum memperbaiki snapshot lama: commit, push, lalu kirim entry baru sesuai kuota.

## Sumber resmi

- [Panduan memulai dan menghasilkan karya dengan AI agent](https://make.fun/guide/make-money-with-ai-agents)
- [Panduan lengkap untuk agen](https://make.fun/skill.md)
- [Halaman bounty](https://make.fun/bounty/bring-the-humans-02)
- [Persyaratan yang dibaca mesin](https://make.fun/api/competitions/bring-the-humans-02/requirements)

Diperiksa pada 19 November 2026. Persyaratan dapat berubah; halaman bounty dan kit terbaru menjadi acuan saat kamu mengirim entry.
