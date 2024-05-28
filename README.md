# APBO_SI_DAYCARE
APBO_SI_Daycare
# USE CASE DIAGRAM
![Usecasedaycare drawio](https://github.com/momocipaw/APBO_SI_DAYCARE/assets/167399698/2d158421-6710-47af-a3b5-c8931f860847)

Penjelasan : 

• Mendaftarkan anak : Orang tua mengisi formulir pendaftaran, staff memverifikasi data, anak terdaftar di sistem.

• Membayar Biaya : Orang tua memilih metode pembayaran, staff menerima pembayaran, administrasi memproses pembayaran, sistem mencatat transaksi.

• Mengantar Anak : Orang tua mengantar anak, staff menerima anak, mencatat waktu kedatangan.

• Menjemput Anak : Orang tua menjemput anak, staff menyerahkan anak, mencatat waktu penjemputan.

• Orang tua melihat laporan perkembangan anak melalui sistem atau aplikasi.

• Mengelola Data : Administrator menambahkan, mengedit, dan menghapus data anak, orang tua/wali, staff, jadwal, kehadiran, dan laporan.

• Membuat Laporan : Administrator generate laporan kehadiran, perkembangan anak, dan keuangan.

# CLASS DIAGRAM


# ERD (Entity Relationship Diagram)
![ERDdaycare](https://github.com/momocipaw/APBO_SI_DAYCARE/assets/167399698/a9eb155c-4117-4590-a724-6b3799c0833b)
• Orang Tua > Anak (One(1) to Many(M)) : Seorang orang tua dapat memiliki banyak anak.

• Anak > Kehadiran (One(1) To many(M)) : Seorang anak dapat menghadiri semua jadwal.

• Staf > Jadwal (One(1) To Many(M)) : Seorang staff memiliki banyak jadwal.

• Orang Tua > Pembayaran (One(1) To One(1)) : Seorang orang tua dapat melakukan sekali pembayaran

• Pembayaran > Administrator(Many(M) to One(1)) : Banyak Pembayaran dapat diproses oleh satu administrator

• Administrator > Laporan (One To Many(1)) : Seorang administrator dapat mengolah banyak data.

• Jadwal > Kehadiran : Sebuah Jadwal Memiliki banyak catatan Kehadiran
