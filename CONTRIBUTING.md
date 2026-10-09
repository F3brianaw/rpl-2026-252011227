# Panduan Kontribusi

Dokumen ini menjelaskan aturan kontribusi dan pengelolaan perubahan pada repository RPL 2026.

## 1. Membuat Branch

Gunakan branch terpisah untuk setiap perubahan yang dikerjakan.

Contoh:

* `docs/update-readme`
* `docs/add-ai-policy`
* `docs/task-01-analysis`
* `fix/correct-documentation`

Hindari menggabungkan perubahan yang tidak berkaitan dalam satu branch jika perubahan tersebut cukup besar untuk dipisahkan.

## 2. Format Commit

Gunakan format berikut:

`type: deskripsi singkat perubahan`

Jenis commit yang digunakan:

* `docs:` untuk menambahkan atau memperbarui dokumentasi.
* `feat:` untuk menambahkan fitur.
* `fix:` untuk memperbaiki kesalahan.
* `refactor:` untuk merapikan struktur tanpa mengubah fungsi utama.

Contoh:

* `docs: add project README`
* `docs: add work commitments`
* `docs: document task 01 findings`
* `fix: correct problem statement`

Pesan commit harus menjelaskan perubahan yang benar-benar dilakukan.

## 3. Pull Request

Jika perubahan dikerjakan melalui branch, ajukan Pull Request (PR) menuju branch utama. Jelaskan tujuan perubahan, bagian yang diubah, serta pemeriksaan yang telah dilakukan.

Sebelum perubahan digabungkan, pastikan isi dokumen sudah diperiksa dan tidak ada informasi pribadi atau bukti yang tidak semestinya dibagikan.

## 4. Review dan Penggabungan

Periksa perbedaan perubahan (*diff*) sebelum menggabungkan PR. Perbaiki temuan yang relevan dan pastikan hasil akhirnya sesuai dengan tujuan perubahan.

Untuk perubahan kecil yang dikerjakan sendiri, perubahan dapat dilakukan langsung pada branch utama jika sesuai dengan kebutuhan tugas. Panduan ini tetap digunakan sebagai acuan jika alur branch dan PR diperlukan.
