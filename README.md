# APBO_SI_DAYCARE
APBO_SI_Daycare
# USE CASE DIAGRAM
![Usecasedaycare2 drawio (1)](https://github.com/momocipaw/APBO_SI_DAYCARE/assets/167399698/82cedf3f-991b-468f-be49-884e56736bf5)

Penjelasan : 
1. Anak adalah penerima utama layanan daycare. Meskipun anak tidak berinteraksi langsung dengan sistem, data dan aktivitas mereka di daycare dicatat dan diolah dalam sistem.
2. Orang tua atau wali mendaftarkan anak mereka ke daycare, mengakses laporan perkembangan anak, dan menerima informasi terkait anak mereka dari staf daycare.
3. Staff daycare bertanggung jawab atas pengawasan dan perawatan anak-anak, mencatat kehadiran, dan mengelola aktivitas harian anak.
4. Administrator bertanggung jawab atas pengelolaan dan pemeliharaan sistem informasi daycare, termasuk manajemen data pengguna (anak, orang tua/wali, staf), serta memastikan sistem berjalan dengan lancar dan aman.
   
# CLASS DIAGRAM
![Classdiagram DayCare drawio](https://github.com/momocipaw/APBO_SI_DAYCARE/assets/167399698/5fe1b491-4121-46af-93fd-49c599a44e4a)

# ERD (Entity Relationship Diagram)
![ERDdaycare](https://github.com/momocipaw/APBO_SI_DAYCARE/assets/167399698/a9eb155c-4117-4590-a724-6b3799c0833b)
• Orang Tua > Anak (One(1) to Many(M)) : Seorang orang tua dapat memiliki banyak anak.

• Anak > Kehadiran (One(1) To many(M)) : Seorang anak dapat menghadiri semua jadwal.

• Staf > Jadwal (One(1) To Many(M)) : Seorang staff memiliki banyak jadwal.

• Orang Tua > Pembayaran (One(1) To One(1)) : Seorang orang tua dapat melakukan sekali pembayaran

• Pembayaran > Administrator(Many(M) to One(1)) : Banyak Pembayaran dapat diproses oleh satu administrator

• Administrator > Laporan (One To Many(1)) : Seorang administrator dapat mengolah banyak data.

• Jadwal > Kehadiran : Sebuah Jadwal Memiliki banyak catatan Kehadiran
