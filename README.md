# Küresel Kalkınma ve Refah Analizi: Veri Görselleştirme Projesi

Üniversite **Veri Görselleştirme** dersi ödevim için hazırladığım; Python kullanarak verileri temizlediğim, akademik ilkelere uygun şekilde görselleştirdiğim ve sonuçlarını yorumladığım uçtan uca bir veri analizi çalışmasıdır.

---

## Proje Hakkında
Bu projede, Hans Rosling'in kurucusu olduğu Gapminder Vakfı'na ait küresel sosyo-ekonomik veri seti kullanılmıştır. Çalışma boyunca şu temel adımlar gerçekleştirilmiştir:

**Temel Adımlar:**
* Veri ön işleme, eksik veri kontrolleri
* Dağılım, zaman serisi, ilişki ve kompozisyon analizleri
* Seaborn ve Plotly ile grafik tasarımı
* Tasarım seçimlerinin akademik gerekçelendirilmesi
* Bilerek yapılan hatalı grafiklerin eleştirisi

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

## Yanlış Grafik Eleştirisi
Projenin sonunda, veri görselleştirme etiğine aykırı klasik bir hatayı bilerek tasarladım ve eleştirdim:
* **Kalabalık Pasta Grafiği:** Onlarca kategoriyi tek pastaya sığdırmanın okunabilirliği nasıl yok ettiğini açıkladım.

---

## Kullanılan Teknolojiler
* **Python**
* **Pandas & NumPy** 
* **Matplotlib & Seaborn** 
* **Plotly Express** 

---

## Projeyi İncele
Kodların tamamını ve interaktif grafikleri çalıştırmak için `.ipynb` uzantılı dosyayı inceleyebilir veya Colab üzerinde açabilirsiniz.
