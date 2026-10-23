# Küresel Kalkınma ve Refah Analizi: Uçtan Uca Veri Görselleştirme Projesi

Üniversite **Veri Görselleştirme** dersi ödevim için hazırladığım; Python kullanarak verileri temizlediğim, akademik ilkelere uygun şekilde görselleştirdiğim ve sonuçlarını yorumladığım uçtan uca bir veri analizi çalışmasıdır.

---

## Proje Hakkında
Bu çalışmada Hans Rosling'in kurucusu olduğu **Gapminder** veri setini kullandım. Proje boyunca temel amacım; verideki sayısal, kategorik ve zamansal boyutları doğru grafik türleriyle eşleştirmek, veri estetiği kurallarına (`data-ink ratio`) dikkat etmek ve yanlış görselleştirme tuzaklarını incelemek oldu.

**Temel Adımlar:**
* Veri ön işleme, eksik veri ve tip kontrolleri
* Dağılım, zaman serisi, ilişki ve kompozisyon analizleri
* Seaborn (statik) ve Plotly (interaktif) ile grafik tasarımı
* Tasarım seçimlerinin akademik gerekçelendirilmesi
* Bilerek yapılan hatalı grafiklerin (*bad visualization*) eleştirisi

---

## Oluşturduğum Grafikler ve Temel Bulgular

1. **Dağılım Analizi (Seaborn Boxplot):** 
   * *Soru:* 2007 yılında kıtalara göre yaşam süreleri nasıl dağılıyor?
   * *Bulgu:* Avrupa ve Okyanusya'da yaşam standartları yüksek ve homojenken, Afrika'da hem medyan düşük hem de ülkeler arası eşitsizlik çok fazla.
2. **Zaman Serisi (Seaborn Line Plot):** 
   * *Soru:* 1952-2007 arasında kıtaların ortalama yaşam süreleri nasıl değişti?
   * *Bulgu:* Tüm kıtalarda yaşam süresi artarken, Afrika'da 1980'lerden sonra HIV/AIDS salgını nedeniyle eğrinin bir süre durakladığı net şekilde görülüyor.
3. **Gelir ve Yaşam İlişkisi (Plotly Bubble Chart):** 
   * *Soru:* Kişi başı gelir ile yaşam süresi arasında nasıl bir ilişki var?
   * *Bulgu:* Gelir arttıkça yaşam süresinin de arttığını (Preston Eğrisi), nüfus büyüklüklerini de hesaba katarak interaktif bir düzlemde inceledim.
4. **Nüfus Kompozisyonu (Plotly Treemap):** 
   * *Soru:* Dünya nüfusunun kıtalara ve ülkelere göre oranı nasıldır?
   * *Bulgu:* Asya kıtasının ve özellikle Çin ile Hindistan'ın küresel nüfustaki baskın payını ağaç haritası ile görselleştirdim.

---

## Yanlış Grafik (Bad Visualization) Eleştirisi
Projenin sonunda, veri görselleştirme etiğine aykırı iki klasik hatayı bilerek tasarladım ve eleştirdim:
* **Y Ekseni Kesik Sütun Grafiği:** Eksenin sıfırdan başlatılmamasının (*Lie Factor*) kıtalar arası farkları nasıl yapay olarak abarttığını gösterdim.
* **Kalabalık Pasta Grafiği:** Onlarca kategoriyi tek pastaya sığdırmanın okunabilirliği nasıl yok ettiğini açıkladım ve doğru alternatiflerini önerdim.

---

## Kullanılan Teknolojiler
* **Python**
* **Pandas & NumPy** (Veri ön işleme)
* **Matplotlib & Seaborn** (Statik ve akademik grafikler)
* **Plotly Express** (İnteraktif web görselleştirmeleri)

---

## Projeyi İncele
Kodların tamamını ve interaktif grafikleri çalıştırmak için `.ipynb` uzantılı dosyayı inceleyebilir veya Colab üzerinde açabilirsiniz.
