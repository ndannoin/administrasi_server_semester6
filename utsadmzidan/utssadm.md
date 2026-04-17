Laporan UTS Administrasi Server
Zaidan Alif Firdaus | 2388010038 | Informatika 6A

Tahap Provisioning & Security
Membuat instance EC2 di region Singapore (ap-southeast-1) dengan nama utszaidan, tipe t2.micro/t3.micro, dan OS Ubuntu 22.04/24.04.
Mengatur Key Pair, storage 8 GB, serta Security Group (SSH: My IP, HTTP: 0.0.0.0/0).
Menjalankan instance hingga running, <img width="1920" height="966" alt="image" src="https://github.com/user-attachments/assets/2e017f69-5952-48ea-9ff9-0420af1220d0" />

Wajib mengaktifkan Detailed CloudWatch Monitoring dan membuat 1 buah Alarm jika penggunaan CPU menyentuh >80%. <img width="1920" height="856" alt="image" src="https://github.com/user-attachments/assets/6ada7f21-53f5-401e-8bc5-862b65e85f82" />


Security Group Inbound Rules (menunjukkan Port 22 hanya diakses oleh My IP). <img width="1911" height="923" alt="image" src="https://github.com/user-attachments/assets/87490f8c-67b9-433c-8396-2e585880f024" />


Mengaktifkan dan menjalankan nginx <img width="930" height="966" alt="WhatsApp Image 2026-04-10 at 09 36 43 (2)" src="https://github.com/user-attachments/assets/e1fe173e-1d90-4676-9a5b-aba51d64d059" />
<img width="635" height="372" alt="Screenshot 2026-04-15 150152" src="https://github.com/user-attachments/assets/02c808bb-b337-4f32-a3a2-236bc8d0b170" />
<img width="1600" height="900" alt="WhatsApp Image 2026-04-10 at 09 36 43 (3)" src="https://github.com/user-attachments/assets/15346ee8-44d0-4c84-8d4f-f2a3d3dc5459" />

Deployment Aplikasi Web

Setelah layanan Nginx berhasil dijalankan, dilakukan pengujian dengan mengakses alamat IP publik (Elastic IP) melalui browser.
Website CV yang telah diunggah kemudian berhasil ditampilkan, menandakan bahwa proses deployment berjalan dengan baik dan server dapat diakses secara online.
Dengan demikian, konfigurasi web server dan proses upload file website telah berhasil dilakukan tanpa kendala. alt text
