---
description: Berisi Dokumentasi Panduan Dokumen Jalan Kerja
---

# Dokumen Jalan Kerja

## Konsep

<div align="center"><figure><img src=".gitbook/assets/image (1).png" alt="" width="563"><figcaption></figcaption></figure></div>

Sebuah **Dokumen** memiliki **Lembar Kerja** yang berisi beberapa _section_ pekerjaan. Pekerjaan tersebut dapat dipilih berdasarkan **SOP** yang tersedia atau disusun tanpa mengacu pada SOP, sesuai dengan kebutuhan pelaksanaan kerja.

<figure><img src=".gitbook/assets/image (7).png" alt="" width="497"><figcaption></figcaption></figure>

**Lembar Kerja** merupakan _**pre-document**_ yang dikerjakan sebelum sebuah dokumen dirilis, berfungsi sebagai wadah perencanaan dan penyusunan isi pekerjaan sebelum ditetapkan menjadi dokumen final. Untuk merilis sebuah Lembar Kerja menjadi **Dokumen Hasil**, perlu dilakukan aksi _**publish**_ sebagai tahap finalisasi agar dokumen resmi diterbitkan.

<figure><img src=".gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

**Dokumen Hasil** merupakan dokumen final yang dihasilkan dari proses **publish** Lembar Kerja, yang berisi pekerjaan yang telah disusun, disetujui, dan siap digunakan sebagai referensi resmi pelaksanaan kerja.

<figure><img src=".gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

## Struktur

Secara struktural, dokumen dapat terikat pada hierarki **Project → Product → Epic → Feature**, sehingga setiap dokumen dapat dikaitkan dengan konteks pekerjaan pada salah satu atau beberapa tingkat tersebut untuk menjaga keterkaitan dan keterlacakan.

{% embed url="https://www.loom.com/share/30d4dfc9251b430d9c0295ff8c1eed09" %}

## Template Dokumen

<figure><img src=".gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

Untuk menambahkan dokumen ke dalam menu **Lembar Kerja /** **Dokumen Hasil,** perlu menambahkan dokumen melalui menu template. Untuk merubah template sebuah dokumen dengan klik tombol mata untuk masuk ke _detail_ page.

<figure><img src=".gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

Setiap pekerjaan dalam dokumen memiliki **aktor** yang bertanggung jawab atas pelaksanaannya. Aktor dapat ditentukan berdasarkan **SOP** (terikat SOP) atau ditetapkan secara mandiri apabila section atau pekerjaan tersebut tidak merupakan bagian dari SOP.&#x20;

Section atau pekerjaan pada dokumen dapat memiliki beberapa tipe sebagai berikut:

1. Text
2. Table
3. Canvas

### Text

<figure><img src=".gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Section akan berupa inputan teks
{% endhint %}

### Table

<figure><img src=".gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

Untuk membuat tabel, perlu menstrukturkan kolom terlebih dahulu, di mana setiap kolom memiliki **tipe node** :&#x20;

1. Text\
   Kolom akan berupa inputan teks.
2. Option / Multi-Option\
   <img src=".gitbook/assets/image (20).png" alt="" data-size="original">\
   Kolom akan berupa inputan `select` dengan pilihan opsi statis.
3. Database\
   ![](<.gitbook/assets/image (21).png>)\
   Kolom akan berupa inputan `select` dengan pilihan opsi dinamis yang bersumber dari sebuah database.
4. Date\
   Kolom akan berupa inputan tanggal
5. Document\
   ![](<.gitbook/assets/image (22).png>)\
   Kolom akan berupa aksi tombol yang mengarah ke sebuah dokumen lain.

<figure><img src=".gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

`Set Data Master` digunakan untuk menambahkan Table terkait ke dalam daftar source `Database` pada template kolom database.

{% hint style="info" %}
Section akan berupa _table_&#x20;
{% endhint %}

### Canvas

<figure><img src=".gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Section akan me-list sub pekerjaan
{% endhint %}

## Publish Document

{% embed url="https://www.loom.com/share/0d307949f27846f5a6e49d1a9d9213d2" %}

Untuk mempublish sebuah dokumen perlu dipastikan bahwa progress Lembar Kerja sudah mencapai 100%. Dan untuk mem-_publish_ bisa memilih opsi :&#x20;

1. Semua Pekerjaan
2. Pilih Pekerjaan
3. Rangkuman
