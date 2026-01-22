---
hidden: true
---

# Graph Notes

## Document Graph

***

* Add props <mark style="color:$danger;">`epicId`</mark> when inserting content Document in Graph. halooo
* Add filtering by <mark style="color:$danger;">`epicId`</mark> if document belongs to <mark style="color:$danger;">EPIC</mark>
*   When rendering database column table, if data master empty, table not rendered. Instead render table ony column with empty data.

    <figure><img src=".gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>
* untuk table dengan catatan kaki atau semacanya -> grid / table
* sub dalam sub -> Text (limitasi 1 sub dalam job) , eg:
  * Job \[canvas] -> Job 1 -> akan masuk dalam Table of Content
    * Job \[text] -> Job 1.1 -> akan masuk dalam nested Table of Content
* Hyperlink text di dalam table mode view gabisa diklik (teks biasa)
* tambah hyperlink ke editor

BUG List :

{% hint style="danger" %}
UNTUK CANVAS TEMPLATE, belum bisa insert bersamaan job tipe = canvas dan childnya, harus save job nya dulu baru insert childnya.
{% endhint %}

{% hint style="info" %}
UNTUK CANVAS di Table, Minimal 2 kolom
{% endhint %}

NEED Improvement :

* Belum bisa isi template di semua job bersamaan, masih per-section / per-job
* Hapus Job di SOP -> soft delete di graph -> menimbulkan ketika re-create baru job yg direstore tidak muncul
* Input table document -> tambahan catatan kaki
* Setiap job berikan sebuah inputan deskripsi berbeda dengan content
* Kalau job pakai referensi

## CaseReport

***

* adding Group column status, priority
* filter tanggal permintaan -> range filtering
