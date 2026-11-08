# Misi Bakul Nombor

Game matematik 3M Tahun 1 (DSKP 2.2): kira, isi bakul, susun menaik dan menurun.
Murid pilih haiwan dan aksesori, kemudian haiwan itu memberi arahan dengan suara.

## Letak di GitHub Pages
1. Muat naik semua fail dalam folder ini ke root repo (`index.html`, `README.md`, `.nojekyll`).
2. Settings > Pages > Deploy from branch > main > / (root) > Save.
3. Buka `https://NAMA.github.io/NAMA-REPO/` (mesti HTTPS supaya webcam dibenarkan).

## Cara bermain
- Sentuhan atau mouse: seret dan sentuh seperti biasa.
- Webcam: tekan 📷 Webcam. Tahan jari di atas butang kira-kira 1 saat untuk memilih; cubit (ibu jari + telunjuk) untuk pegang dan lepaskan untuk letak.
- Butang atas: 🏠 pilih misi, 🔁 ulang arahan, 🔊 bisu, ⚙️ julat nombor, ⛶ skrin penuh.
- Sentuh gelembung chat atau banner misi untuk langkau suara.

## Pilihan luar talian (webcam)
Pustaka MediaPipe dimuat dari internet. Untuk internet lemah, letak fail `hand_landmarker.task`
(~8MB, model MediaPipe Hand Landmarker) di sebelah `index.html`.
