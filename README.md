# Panduan OCR Plat Nomor Kendaraan dengan VLM + LM Studio

Program ini melakukan OCR (Optical Character Recognition) untuk membaca plat nomor kendaraan secara otomatis dari gambar menggunakan Visual Language Model (VLM) seperti Qwen-VL atau LLaVA, dijalankan secara lokal melalui LM Studio, dan diakses menggunakan Python di Jupyter Lab.

## Persiapan Awal
1. Unduh dataset https://www.kaggle.com/datasets/juanthomaswijaya/indonesian-license-plate-dataset
2. Unduh LM Studio di: https://lmstudio.ai
3. Install dan jalankan LM Studio

## Jalankan Model VLM
1. Buka LM Studio
2. Download model yang ingin digunakan di bagian User
3. Pilih dan jalankan model multimodal (yang mendukung teks + gambar), misalnya:
   - `Qwen/Qwen1.5-VL`
   - `llava-llama-3-8B`
4. Pergi ke power_user di bagian bawah lalu pilih menu developer di bagian kiri
5. Hidupkan server dengan menekan toggle di bagian tengah
7. Tunggu hingga muncul tulisan: API available at http://localhost:1234/v1/chat/completions

> ⚠️ Biarkan LM Studio tetap terbuka saat menjalankan program Python

## 2. Eksekusi Python

### Jalankan program .ipynb di Jupyter Lab
1. Buka Anaconda Prompt dan jalankan env
2. Buka Jupyter Lab dan jalankan program secara berurutan
