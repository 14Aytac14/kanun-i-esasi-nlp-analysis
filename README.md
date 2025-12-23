# 1876-1909-1918 Kanun-ı Esasî NLP Analizi

Bu proje, Osmanlı Anayasal metinlerindeki (Kanun-ı Esasî) kavramsal değişimi inceleyen akademik çalışma için geliştirilen **Veri İşleme ve Analiz Algoritmasını** içerir.

## Proje Hakkında
Çalışma, 1876, 1909 ve 1918 tarihli anayasa metinlerini Doğal Dil İşleme (NLP) yöntemleriyle analiz ederek; yürütme, yasama ve vatandaşlık kavramlarındaki anlamsal kaymaları nicel verilerle ortaya koymaktadır.

## Kullanılan Yöntemler ve Kütüphaneler
Bu analizde aşağıdaki Python kütüphaneleri ve yöntemleri kullanılmıştır:
* **Ön İşleme:** Tokenizasyon (spaCy/Stanza), Morfolojik Analiz (Zemberek), Stop-word temizliği.
* **İstatistiksel Analiz:** N-gram ve Kolokasyon (Bağlam Penceresi) algoritmaları.
* **Metin Madenciliği:** TF-IDF, K-Means Kümeleme ve Jaccard Benzerlik (Diff) Analizi.

## Dosya İçeriği
* `kanun_nlp_main.py`: Makaledeki (Tablo 1-6) sonuçları üreten, metodolojiyi doğrulayan kaynak kod.

## İletişim
Bu çalışma akademik "reproducibility" (tekrarlanabilirlik) amacıyla açık erişime sunulmuştur.
