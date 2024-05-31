# APBO_SI_DAYCARE
APBO_SI_Daycare
# USE CASE DIAGRAM
![Usecasedaycare2 drawio (1)](https://github.com/momocipaw/APBO_SI_DAYCARE/assets/167399698/82cedf3f-991b-468f-be49-884e56736bf5)

*Penjelasan :*
1. Anak adalah penerima utama layanan daycare. Meskipun anak tidak berinteraksi langsung dengan sistem, data dan aktivitas mereka di daycare dicatat dan diolah dalam sistem.
2. Orang tua atau wali mendaftarkan anak mereka ke daycare, mengakses laporan perkembangan anak, dan menerima informasi terkait anak mereka dari staf daycare.
3. Staff daycare bertanggung jawab atas pengawasan dan perawatan anak-anak, mencatat kehadiran, dan mengelola aktivitas harian anak.
4. Administrator bertanggung jawab atas pengelolaan dan pemeliharaan sistem informasi daycare, termasuk manajemen data pengguna (anak, orang tua/wali, staf), serta memastikan sistem berjalan dengan lancar dan aman.
   
# CLASS DIAGRAM
![classD drawio](https://github.com/momocipaw/APBO_SI_DAYCARE/assets/167399698/03f227d2-f3ee-4930-9e60-671e9009d7da)

*NOTES*
Primary Key ditandai dengan(*)

Foreign key ditandai dengan(**)

Hubungan Antar Kelas

Orang Tua - Anak: Seorang orang tua/wali dapat memiliki satu atau lebih anak (1 to many).

Anak - Kehadiran: Setiap anak memiliki catatan kehadiran setiap hari (1 to many).

Anak - Jadwal: Setiap anak memiliki jadwal aktivitas harian (1 to many).

Anak - Laporan: Setiap anak memiliki laporan perkembangan (1 to many).

Staf - Anak: Staf daycare mengelola aktivitas, kehadiran, dan perkembangan anak (many to many).

Admin Sistem - Staf, Orang Tua, Anak: Admin sistem mengelola data pengguna termasuk staf, orang tua, dan anak (many to many).

# ERD (Entity Relationship Diagram)
![ERD2](https://github.com/momocipaw/APBO_SI_DAYCARE/assets/167399698/5c6a39d0-038d-451b-b4bf-bbaf3abed328)
*NOTES*
Primary Key ditandai dengan(*)

Foreign key ditandai dengan(**)
