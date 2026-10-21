# omnidesk-components

Unduhan opsional untuk **OmniDesk** (aplikasi desktop Windows lokal untuk convert, editing, rekam, dan screenshot).

Repo ini hanya berisi:
- `manifest.json`: daftar versi terbaru aplikasi, komponen, dan model (dengan SHA-256 tiap berkas). OmniDesk membacanya **hanya saat pengguna menekan "Cek pembaruan" atau "Pasang"** dan menyetujui dialog izin.
- **Releases**: installer OmniDesk dan paket komponen buatan OmniDesk (OCR, Transkrip, Pemisah instrumen, Ekstrak dokumen).

Model AI (Whisper, pemisah pembicara, Demucs) **tidak** diunggah di sini. `manifest.json` menunjuk langsung ke sumber aslinya (Hugging Face, GitHub, fbaipublicfiles), dikunci ke revisi dan SHA-256 tertentu.

Tidak ada telemetri: OmniDesk tidak mengirim data apa pun ke repo ini; ia hanya mengunduh berkas yang disetujui pengguna.

Lisensi pihak ketiga yang ada di dalam paket: Tesseract (Apache-2.0), pypdfium2 (BSD/Apache-2.0), faster-whisper dan CTranslate2 (MIT), sherpa-onnx (Apache-2.0), Demucs (MIT), PyTorch (BSD), python-pptx / python-docx / openpyxl (MIT). Installer OmniDesk membawa FFmpeg (GPL v3); teks lisensi ada di folder aplikasi (`_internal\licenses`).
