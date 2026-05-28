# Sistem Penghalang Parkir Otomatis Menggunakan ANPR/ALPR

## Gambaran Proyek

Proyek ini merupakan sistem penghalang parkir otomatis yang memanfaatkan teknologi Automatic Number Plate Recognition (ANPR/ALPR) untuk mendeteksi dan mengenali nomor kendaraan secara otomatis. Sistem digunakan untuk mengontrol akses kendaraan masuk dan keluar area parkir berdasarkan hasil identifikasi plat nomor.

## Arsitektur Sistem

<img width="478" height="257" alt="image" src="https://github.com/user-attachments/assets/f64d2376-5376-404c-8cfe-690ed9dd22b1" />


## Galeri Proyek

[Foto 1]
<img width="1280" height="960" alt="image" src="https://github.com/user-attachments/assets/c763a3c6-ba83-475f-8368-03a253c6df51" />

[Foto 2]
<img width="1280" height="960" alt="image" src="https://github.com/user-attachments/assets/71b6a0e0-23d2-482c-a935-414ff91595ec" />

[Foto 3]
<img width="1280" height="960" alt="image" src="https://github.com/user-attachments/assets/061b90b6-3840-42d2-9352-43fbffb17f83" />

## Hasil Pengujian

[Hasil deteksi kendaraan]
<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/5b6238d4-5712-4238-a6d6-40f9dabb2e2b" />

[Hasil deteksi plat nomor]
<img width="402" height="225" alt="image" src="https://github.com/user-attachments/assets/f3a0a1cb-d132-40ac-b00f-c46c1da95901" />

## Teknologi dan Metode

- Python
- OpenCV
- YOLOv8
- PaddleOCR
- ONNX Runtime
- Raspberry Pi 5
- Flask
- MariaDB

### Image Preprocessing & OCR Optimization

- License Plate Region Cropping (ROI Extraction)
- License Plate Text Filtering
- RGB Color Space Analysis
- Red & Green Channel Enhancement
- Grayscale Conversion
- Deskew Correction
- Gamma Correction
- CLAHE Contrast Enhancement
- Adaptive Thresholding
- Bilateral Noise Reduction
- Image Sharpening
- Highlight Suppression
- OCR Post-processing
- License Plate Format Validation
- Indonesian License Plate Format Correction

### Computer Vision & AI

- Vehicle Detection
- License Plate Detection
- Automatic Number Plate Recognition (ANPR)
- Optical Character Recognition (OCR)
- Real-Time Object Detection
- OCR Optimization
- Edge AI Computing
- Cyber-Physical Systems (CPS)

## Fitur Utama

## Fitur Utama

- Deteksi plat nomor kendaraan secara otomatis menggunakan YOLOv8
- Deteksi plat nomor kendaraan secara real-time
- Pengenalan karakter plat nomor menggunakan PaddleOCR
- Pembukaan palang parkir otomatis berbasis relay
- Pencatatan data kendaraan ke database MariaDB
- Validasi kendaraan keluar melalui antarmuka web
- Monitoring data parkir berbasis Flask

## Penulis

Mabduh Khoer
