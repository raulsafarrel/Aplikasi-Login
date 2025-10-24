# Project Owl

## Apa itu Project Owl ?

Project Owl adalah aplikasi pelacak tidur (sleep tracker) berbasis Flutter. Aplikasi ini dirancang untuk membantu pengguna memahami hubungan antara kualitas tidur, durasi tidur, dan tingkat stres harian mereka.

Pengguna dapat mencatat jam tidur, jam bangun, dan tingkat stres harian mereka. Aplikasi kemudian akan memberikan skor Kualitas Tidur yang diprediksi oleh model Machine Learning, membantu pengguna mengidentifikasi pola untuk meningkatkan produktivitas dan kesehatan mereka.

## Latar Belakang

Di era yang serba cepat, banyak orang, terutama pelajar dan pekerja, mengorbankan waktu tidur yang berdampak langsung pada produktivitas dan kesehatan mental. Seringkali, kita tidak menyadari seberapa besar pengaruh tidur satu malam terhadap kinerja kita keesokan harinya. Project Owl dibuat untuk menjembatani kesenjangan informasi tersebut, memberikan data nyata kepada pengguna tentang bagaimana tidur mereka memengaruhi kehidupan sehari-hari mereka.

## Penjelasan Fitur & Alur

Aplikasi ini memiliki beberapa fitur utama yang saling terhubung:

Personalisasi Nama: Saat pertama kali membuka aplikasi, pengguna akan diminta memasukkan nama panggilan untuk sapaan yang personal ("Selamat Pagi, [Nama]").

Onboarding: Pengguna baru akan disambut dengan serangkaian layar orientasi yang menjelaskan fungsi utama aplikasi.

Input Data Harian:

Jam Tidur & Bangun: Pengguna memilih waktu mereka mulai tidur dan waktu bangun.

Tingkat Stres: Pengguna memberikan input tingkat stres (skala 1-5) untuk hari itu.

Prediksi Kualitas Tidur: Data (durasi tidur & tingkat stres) dikirim ke API back-end, di mana model Machine Learning memprosesnya dan mengembalikan prediksi skor kualitas tidur (0-100%).

Visualisasi Data: Hasil prediksi ditampilkan dalam bentuk lingkaran progres yang menarik secara visual, beserta detail durasi tidur.

Cara Menjalankan/Duplikasi Proyek

Jika Anda ingin menjalankan atau menduplikasi proyek ini di mesin lokal Anda, ikuti langkah-langkah berikut:

## Prasyarat:

Pastikan Anda telah menginstal Flutter SDK (versi 3.x.x atau lebih baru).

Memiliki editor kode seperti Visual Studio Code.

Perangkat (Emulator Android, iOS Simulator, atau perangkat fisik) untuk menjalankan aplikasi.

Langkah-langkah Instalasi:

Clone repositori ini ke komputer lokal Anda:

git clone [https://github.com/trunxl0g1c/capstone-flutter.git](https://github.com/trunxl0g1c/capstone-flutter.git)


Masuk ke direktori proyek:

cd capstone-flutter


Instal semua dependensi yang diperlukan:

flutter pub get


Jalankan aplikasi:

flutter run


(Catatan: Aplikasi ini memerlukan back-end API Machine Learning untuk menjalankan fitur prediksi. Untuk fungsionalitas penuh, pastikan Anda juga menjalankan server API secara lokal dan memperbarui URL endpoint di lib/data/api/api_service.dart.)




Credits & Teknologi

Berikut adalah teknologi utama yang digunakan untuk membangun aplikasi Flutter ini:

Framework: <a href="https://flutter.dev/">Flutter</a>

Bahasa: <a href="https://dart.dev/">Dart</a>

State Management: <a href="https://pub.dev/packages/provider">Provider</a>

UI Components: <a href="https://pub.dev/packages/shadcn_flutter">shadcn_flutter</a>

Fonts: <a href="https://pub.dev/packages/google_fonts">google_fonts</a>

Local Storage: <a href="https://pub.dev/packages/shared_preferences">shared_preferences</a>

Networking: <a href="https://pub.dev/packages/http">http</a>

Onboarding: <a href="https://pub.dev/packages/introduction_screen">introduction_screen</a>
