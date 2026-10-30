# Jurnal Proses — Tugas 6

## Implementasi find_successor
- Kesalahan pertama yang ditemui (mis. lupa wrap-around di ring): Kesalahan pertama yang ditemui (mis. lupa wrap-around di ring): Pada awalnya, logika pencarian hanya melakukan iterasi untuk mencari node dengan ID yang lebih besar atau sama dengan (>=) dari key_hash. Akibatnya, ketika nilai key_hash lebih besar daripada seluruh ID node yang ada di dalam ring, fungsi gagal menemukan penanggung jawab karena tidak memperhitungkan sifat melingkar (wrap-around) dari topologi Chord.
- Cara memperbaikinya: ...

## Skenario join/leave
- Hasil sebelum & sesudah node baru bergabung: ...
- Hasil sebelum & sesudah node keluar: ...

## Log Penggunaan AI (Level 2)

> Wajib diisi sesuai kebijakan Level 2 di [`../RUBRIK-UMUM.md`](../RUBRIK-UMUM.md). Tulis "Tidak memakai AI" pada baris pertama jika memang tidak dipakai. Hanya untuk brainstorming ide/outline — bukan untuk kode/analisis/teks akhir.

| Tanggal | Tool AI | Prompt yang diberikan | Ringkasan saran/ide AI | Bagaimana diolah jadi tulisan/kode sendiri |
|---|---|---|---|---|
| ... | ... | ... | ... | ... |
