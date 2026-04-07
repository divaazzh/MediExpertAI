MediExpert AI - Expert System for Early Disease Diagnosis

MediExpert AI adalah sebuah sistem pakar (Expert System) berbasis web yang dirancang untuk membantu pengguna melakukan diagnosa awal terhadap beberapa penyakit menular umum berdasarkan gejala klinis yang dirasakan. Proyek ini menggabungkan teknik informatika dengan basis pengetahuan medis sederhana.

🚀 Fitur Utama

Inference Engine (Forward Chaining): Menggunakan logika deduktif yang bergerak dari sekumpulan gejala menuju kesimpulan diagnosa.

Confidence Scoring: Menghitung tingkat kecocokan (persentase) gejala yang dialami dengan basis aturan (rule-base) penyakit.

Modern Landing Page: Antarmuka responsif dan bersih menggunakan Tailwind CSS.

Privacy Focused: Semua pemrosesan data dilakukan di sisi klien (client-side), tidak ada data medis sensitif yang dikirim ke server.

🛠️ Tech Stack

Frontend: HTML5, Tailwind CSS

Logic/Engine: Vanilla JavaScript (ES6+)

Icons: Font Awesome

Fonts: Google Fonts (Inter)

🧠 Konsep Algoritma

Sistem ini mengimplementasikan metode Forward Chaining. Proses dimulai dengan mengumpulkan fakta-fakta (gejala yang dipilih pengguna), kemudian fakta tersebut dicocokkan dengan Rule-Base yang ada di sistem:

IF gejala A, B, dan C terpenuhi THEN penyakit X.

📋 Daftar Penyakit (Basis Pengetahuan)

Saat ini sistem mampu mengidentifikasi kemungkinan awal untuk:

Demam Berdarah (Dengue)

COVID-19

Influenza Berat

Gastroenteritis

📸 Tampilan Aplikasi

<img width="1919" height="895" alt="image" src="https://github.com/user-attachments/assets/d34b6971-e306-453c-b9f2-1a167e7d4ee7" />
<img width="1919" height="895" alt="image" src="https://github.com/user-attachments/assets/fe3c6f45-af55-4503-9561-29a96b9721f6" />
<img width="995" height="759" alt="image" src="https://github.com/user-attachments/assets/46febe9c-35fc-4c65-982a-40088ef4f129" />

⚠️ Penafian (Disclaimer)

Aplikasi ini dibuat untuk tujuan edukasi pengembangan sistem pakar. Hasil diagnosa bersifat prediktif dan tidak boleh menggantikan saran, diagnosa, atau perawatan medis profesional.
