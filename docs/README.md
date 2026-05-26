# 📚 Katalog Artikel Literasi Keamanan Informasi

Folder ini berisi kumpulan artikel literasi mendalam dan regulasi pendukung untuk memperkaya wawasan teknis Anda di bidang keamanan informasi dan siber.

---

## 📄 Daftar Dokumen & Artikel Tersemat

### 1. Mengenal Cyber Kill Chain (Framework Serangan Siber)
*   **Nama Berkas:** [`kamsib.id - Artikel Nomor 002 Mengenal Cyber Kill Chain, Framework Serangan Siber.pdf`](kamsib.id%20-%20Artikel%20Nomor%20002%20Mengenal%20Cyber%20Kill%20Chain%2C%20Framework%20Serangan%20Siber.pdf)
*   **Ringkasan:**
    Artikel ini membedah konsep **Cyber Kill Chain**, sebuah model metodologi pertahanan siber yang dikembangkan oleh Lockheed Martin untuk mengidentifikasi dan mencegah aktivitas serangan siber terstruktur. Anda akan mempelajari 7 tahapan serangan penyerang:
    1.  *Reconnaissance* (Pengintaian)
    2.  *Weaponization* (Pembuatan Senjata Siber)
    3.  *Delivery* (Pengiriman Umpan)
    4.  *Exploitation* (Eksploitasi Celah Keamanan)
    5.  *Installation* (Pemasangan Pintu Belakang/Backdoor)
    6.  *Command & Control* (Pembentukan Jalur Komunikasi)
    7.  *Actions on Objectives* (Eksekusi Tujuan Utama/Pencurian Data)
*   **Manfaat:** Membantu tim analis keamanan siber (*Blue Team*) untuk mendeteksi, memutus rantai serangan, dan menghentikan penyerang sedini mungkin sebelum mereka mencapai tujuan akhir.

---

### 2. Mengenal XXE (XML External Entity) Injection
*   **Nama Berkas:** [`kamsib.id_-_Artikel_Nomor_003_-_Mengenal_XXE_XML_External_Entity_Injection.pdf`](kamsib.id_-_Artikel_Nomor_003_-_Mengenal_XXE_XML_External_Entity_Injection.pdf)
*   **Ringkasan:**
    Artikel teknis ini membahas salah satu kerentanan keamanan aplikasi web yang sangat populer, yaitu **XML External Entity (XXE) Injection**. Materi mencakup:
    *   Pengenalan format dokumen XML dan entitas eksternal.
    *   Bagaimana penyerang memanfaatkan parser XML yang tidak dikonfigurasi dengan aman untuk membaca berkas internal server (seperti `/etc/passwd`).
    *   Eksploitasi tingkat lanjut untuk melakukan serangan *Server-Side Request Forgery* (SSRF).
    *   Langkah-langkah penulisan kode pemrograman yang aman (*Secure Coding*) untuk menutup celah XXE di berbagai bahasa pemrograman (PHP, Java, Python).
*   **Manfaat:** Diperuntukkan bagi pengembang web (*Web Developers*) dan penguji keamanan (*Pentester*) untuk membangun aplikasi web yang kebal terhadap serangan injeksi entitas luar.
