1. Jelaskan maksud void async pada praktikum 1?
   
void async adalah fungsi yang tidak mengembalikan nilai apa pun (karena void) tapi bisa menjalankan tugas-tugas secara asinkron (async). Saat pakai async dapat digunakan untuk menjalankan kode yang mungkin memakan waktu lama, seperti mengambil data dari internet, tanpa membuat aplikasi berhenti sementara. Jadi, fungsi ini bisa melakukan tugas berat tanpa mengganggu bagian lain dari kode.

2. Jelaskan fungsi dari anotasi @immutable dan @override ?
   
@immutable digunakan untuk mendeklarasikan bahwa semua properti dari kelas yang menggunakan bersifat tetap (immutable), artinya nilai properti-propertinya tidak dapat diubah setelah objeknya dibuat. Ini sering digunakan dalam kelas-kelas yang mewakili widget pada Flutter, di mana sekali dibuat, sebuah widget tidak boleh mengalami perubahan untuk menjaga stabilitas UI.
@override digunakan untuk menunjukkan bahwa metode atau properti yang didefinisikan ulang di kelas turunan adalah implementasi dari metode atau properti di kelas induk atau antarmuka (interface). @override membantu memastikan bahwa kode menimpa metode yang ada, bukan secara tidak sengaja mendeklarasikan metode baru dengan nama serupa, serta meningkatkan keterbacaan kode dengan menunjukkan bahwa perilaku kelas induk atau antarmuka telah diubah.
