**Visualisasi data dan informasi**

NAMA : Vita Anggraini

NIM : 122450046

KELAS : RA

Tugas 1 buat resume artikel

**Membuat visualisasi data lebih efisien dan efektif**

Visualisasi data, yang mengubah data abstrak menjadi visi fisik
(misalnya panjang, posisi, bentuk, warna, dan sebagainya), merupakan
sarana ampuh untuk menyajikan kisah data yang menarik kepada manusia
yang lebih berorientasi visual. Visualisasi data sangat cocok untuk
memberikan gambaran umum yang baik tentang data yang sangat besar, dan
mempermudah interpretasi hasil analisis data kepada ilmuwan data.

Alur Visualisasi Data Data berulang :

1.  Impor data adalah mengambil data yang diperlukan dari yang
    diinginkan sumber data.

2.  Data preparation adalah mempersiapkan data yang diimpor visualisasi,
    misalnya dengan menormalkan nilai, mengoreksi entri yang salah, dan
    menginterpolasi nilai yang hilang.

3.  Data manipulation adalah memilih data yang akan divisualisasikan
    (alias pemfilteran dari komunitas visualisasi) dan mungkin dengan
    operasi umum lainnya seperti bergabung dan pengelompokan

4.  Mapping adalah memetakan data yang diperoleh dari atas proses ke
    primitif geometris (misalnya titik dan garis), beserta atributnya
    (misalnya, warna, posisi, dan ukuran)

5.  Rendering adalah mengubah data geometri di atas menjadi representasi
    visual.

**Spesifikasi visualisasi data**

Secara umum, bahasa visualisasi data terdiri dari tiga bagian: data,
tanda (atau isyarat visual), dan pemetaan di antara keduanya.

> Tanggal:
>
> -- Catatan: data yang perlu divisualisasikan.
>
> -- Transformasi: operasi---seperti grup, bin, filter, dan
> pengurutan--- digunakan untuk mengubah rekaman data tertentu.
>
> Tanda (atau isyarat visual):
>
> -- Tipe: representasi visual untuk rekaman data, seperti batang,
> garis, atau titik.
>
> -- Ukuran: lebar, tinggi visualisasi
>
> -- Legenda: informasi legenda.

**Kategorisasi bahasa visualisasi data:**

Strategi yang umum digunakan untuk mengkategorikan bahasa visualisasi
data didasarkan pada ekspresifnya, semakin rendah tingkat suatu bahasa,
semakin ekspresifnya. Bahasa tingkat yang lebih tinggi merangkum
beberapa detail tingkat rendah dengan memberikan default sensitif dan
menambahkan lebih banyak batasan (misalnya, Excel \[9\] menyediakan
templat untuk visualisasi yang didukung). Dimensi lain untuk memahami
berbagai tingkat spesifikasi visualisasi bahasa adalah melalui
aksesibilitasnya (atau kemudahan penggunaannya): semakin tinggi tingkat
bahasanya, semakin mudah digunakan.

**Bahasa Tingkat Rendah**

sebagai bahasa yang pengguna perlukan untuk menentukan semua elemen
pemetaan. Prefuse dan Flare adalah perpustakaan visualisasi berbasis
Java; mereka merangkum item visual sebagai kelas Java, yang memiliki
banyak atribut visual, dan bahasa memetakan data ke atribut visual ini
dengan mengatur fungsi yang telah ditentukan sebelumnya. Proto-vis
adalah perangkat grafis berbasis JavaScript deklaratif; ia menggunakan
tanda grafis sederhana (batang, area, garis, dll.) dengan atribut visual
tertentu. D3 merupakan pengembangan dari Protovis dan lebih efektif
dalam menangani interaksi pengguna (misalnya menyikat gigi dan
menghubungkan). Vega dan Reaktif Vega mirip dengan Protovis dan D3,
tetapi mereka menyediakan tata bahasa interaksi deklaratif yang dapat
disusun.

**Bahasa Tingkat Tinggi**

merangkum detail konstruksi visualisasi, seperti fungsi pemetaan, serta
beberapa properti untuk tanda seperti kanvas ukuran, legenda, dan
properti lainnya.

**visualisasi data interaktif**

adalah bahwa dalam banyak kasus, visualisasi data adalah proses
eksplorasi, di mana pengguna harus tetap menyimpan data. menyempurnakan
spesifikasi (misalnya, menambah/menghapus/mengubah atribut, mengubah
tipe grafik) dari visualisasi yang sedang dieksplorasi hingga
mendapatkan visualisasi yang diinginkan dalam proses eksplorasi.

**Visualisasi data yang tepat**

Terjemahan Kueri Cara alami untuk menggunakan kembali banyak sistem yang
sudah matang (DBMS) adalah dengan menerjemahkan kueri visualisasi ke
kueri yang diterima sistem tersebut.

**Mengintegrasikan Sistem Visualisasi dengan DBMS**

Meskipun menggunakan terjemahan kueri adalah hal yang wajar, ada
beberapa kelemahan. Salah satu masalah utamanya adalah banyaknya fungsi
yang diulang, sehingga menghasilkan teknik optimasi yang tidak terpadu
dengan asumsi dan kinerja yang berbeda di server (yaitu, sisi database)
dan klien (yaitu, sisi visualisasi)

**Perkiraan visualisasi data**

Ketika volume data tumbuh secara eksponensial data tradisional modul
pemrosesan tidak dapat memberikan hasil pemrosesan interaktif yang
cepat. Untuk menjembatani kesenjangan antara volume data dan
interaktivitas, banyak pekerjaan mempercepat fase pemrosesan data dengan
memanfaatkan perkiraan pemrosesan kueri (AQP) yang memberikan perkiraan
hasil visualisasi.

Berbasis AQP Cara mudah untuk menghasilkan perkiraan visualisasi dalam
waktu interaktif adalah dengan memanfaatkan teknik AQP. Menggunakan
subset representatif dari data dapat memberikan perkiraan visualisasi
kepada pengguna interaksi online dengan mengorbankan kualitas

**Rekomendasi visualisasi**

Spesifikasi tidak lengkap, yaitu spesifikasi elemen visualisasi yang
kosong atau Sebagian.

Setelah menghasilkan visualisasi kandidat (atau valid) dengan memangkas
seluruh ruang pencarian seperti dijelaskan di atas, sistem rekomendasi
visualisasi kemudian akan mengenali visualisasi yang bermakna
berdasarkan metrik atau aturan yang telah ditentukan sebelumnya.
Beberapa sistem mungkin juga memberi peringkat pada visualisasi yang
menarik atau merekomendasikan visualisasi terbaik kepada pengguna.

**Rekomendasi berdasarkan spesifikasi**

**Spesifikasi tidak lengkap:**

Sistem rekomendasi visualisasi dengan spesifikasi kosong tidak
memerlukan masukan pengguna, sedangkan sistem rekomendasi dengan
spesifikasi parsial menerima masukan spesifikasi elemen visualisasi
parsial pengguna untuk visualisasi yang diinginkan. Misalnya, APT
menerima tujuan melihat data pengguna sebelumnya
