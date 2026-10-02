# WA Status HD Pro 2.0

Aplikasi Android untuk menyiapkan foto/video sebelum dibagikan ke WhatsApp.

## Fitur
- Foto: crop 9:16, 1080x1920, JPEG kualitas 95%, sharpening ringan.
- Video: output MP4 H.264/AAC, 1080x1920, maksimum 30 FPS, VBR 6 Mbps.
- Lanczos resampling untuk menjaga detail saat scaling.
- Tombol langsung Bagikan Hasil ke WhatsApp.
- Hasil disimpan di Pictures/WA Status HD Pro dan Movies/WA Status HD Pro.

## Build
Buka folder `WAStatusHD` dengan Android Studio terbaru dan sync Gradle. Project memakai Jetpack Media3 Transformer 1.11.1.

WhatsApp tetap dapat melakukan kompresi ulang setelah upload; aplikasi ini hanya mengoptimalkan file sumber.
