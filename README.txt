KAMERA WEB JARAK JAUH — DEMO WEBRTC

Isi:
- index.html: halaman untuk HP 1 (pemantau) dan HP 2 (kamera).
- Tidak perlu instal aplikasi pada HP 2.
- HP 2 harus membuka link undangan, menekan "Setujui & mulai kamera", lalu menyetujui izin browser.

CARA MENCOBA:
1. Unggah index.html ke hosting statis yang menyediakan HTTPS (mis. GitHub Pages, Netlify, atau Cloudflare Pages).
2. Buka URL website di HP 1, pilih "HP 1 — Saya melihat kamera".
3. Salin link undangan yang muncul dan kirim ke HP 2.
4. Di HP 2, buka link dengan Chrome, tekan "Setujui & mulai kamera", dan izinkan kamera/mikrofon.
5. Video akan tampil di HP 1. Tombol "Ganti depan / belakang" ada di HP 2.

BATASAN PENTING:
- Ini prototipe/demo, bukan layanan produksi atau APK.
- Kamera browser memerlukan HTTPS dan persetujuan pengguna. Browser/OS dapat menghentikan kamera saat tab ditutup, layar terkunci, atau browser berjalan di latar belakang.
- Sesi harus dimulai dari HP 1 dan halaman HP 1 tetap terbuka.
- Koneksi peer menggunakan layanan pensinyalan PeerJS cloud. Koneksi langsung WebRTC bisa gagal pada jaringan tertentu; penggunaan lintas jaringan yang andal biasanya memerlukan TURN server yang dikelola dengan benar.
- Jangan gunakan untuk memantau orang tanpa sepengetahuan dan persetujuannya.
