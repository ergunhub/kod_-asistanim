**Proje Yazarı:** [Ergün DOĞRU]

# Projenin Adı:  Kod-Asistan v0.1

## Projenin Amacı
Bu proje; kullanıcıların günlük işlerinde (selamlama, temel hesaplamalar, karar verme süreçleri vb.) kendilerine yardımcı olacak, modüler ve kararlı bir dijital asistan tasarlamak amacıyla geliştirilmektedir.

## Projenin Hedefleri * **v0.1:** Dijital deponun yapılandırılması, proje vitrininin (README.md) ve temel mimarinin oluşturulması.
* **v1.0 (Akıllı Menü):** Kullanıcı seçimlerini yöneten 'if-elif-else' karar blokları ve temel güvenlik protokollerinin eklenmesi.
* **v2.0 (Veri Saklama ve Döngüler):** 'while' ve 'for' döngü motorlarıyla dinamik liste ve sepet yönetimi altyapısının kurulması.
* **v3.0 (Kalıcı Mimarisi):** JSON/TXT tabanlı dosya yönetimi, hata ayıklama (try-except) ve dijital portfolyo hazırlama.

## Proje Kapsamı (Kritik Eşik Mantığı)
Sistemimizdeki karar mekanizmasının temelini oluşturan **Kritik Eşik** mantığının metinsel sözde kodu aşağıda tanımlanmıştır:
## Algoritma ve Sözde Kod
```
1. BAŞLA
2. saat = 1
3. Sensörden su_seviyesi verisini oku.
4. EĞER su_seviyesi > 50 İSE:
        Ekrana "KRİTİK EŞİK AŞILDI! Tahliye Kapakları Açılıyor." yazdır.
        Ekrana "Tahliye Saati: ", saat yazdır.
        Ekrana "Kritik Su Seviyesi: ", su_seviyesi yazdır.
        ADIM 6'ya GİT.
5. DEĞİLSE:
        Ekrana "Su seviyesi güvenli sınırda. Kapaklar Kapalı." yazdır.
        saat = saat + 1
        ADIM 3'e GİT.
6. DUR
```
## Kaynakça 
* MEB Bilişim Teknolojileri, *Programlama Temelleri 9 Ders Kitabı*, Millî Eğitim Bakanlığı Yayınları, Ankara, 2026.
* GitHub Dokümantasyonu ve Markdown Rehberi (docs.github.com)
