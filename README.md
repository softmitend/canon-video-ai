# Canon Video AI

Repository untuk menyimpan canon visual, prompt karakter, storyboard, dan prompt keyframe AI video agar identitas karakter dan continuity antar-shot tetap konsisten.

## Struktur

- `prompts/character-reference-sheet.md` — master prompt untuk character model sheet / turnaround.
- `prompts/scenes/nightmare-awakening.md` — storyboard + prompt lengkap scene bangun dari mimpi buruk, termasuk character lock, room lock, negative prompt, dan 12 keyframe.

## Aturan penggunaan

1. Jangan mengubah detail identitas karakter di dalam **MASTER CHARACTER LOCK** kecuali memang canon karakter berubah.
2. Untuk setiap keyframe, gunakan MASTER CHARACTER LOCK + MASTER ROOM LOCK + prompt frame terkait.
3. Gunakan GLOBAL NEGATIVE PROMPT pada semua frame jika generator mendukung negative prompt.
4. Gunakan gambar character reference sheet sebagai image reference bila model mendukung reference image / character consistency.
5. Generate frame secara berurutan. Untuk continuity terbaik, gunakan frame sebelumnya sebagai reference image untuk frame berikutnya bila memungkinkan.
6. Jangan mengganti posisi jendela, pencahayaan utama, pakaian, panjang rambut, warna rambut, atau bentuk wajah antar-frame.

## Scene aktif

### Nightmare Awakening
Urutan adegan:

`sleeping → nightmare intensifies → pre-wake panic → eyes snap open → rises → seated shock → hands rise → rubs face → notices storm → turns toward window → watches rain → lightning`

Target durasi akhir: sekitar **15–22 detik**.
