# BİLTEK MYO — SEO VE WEB ANALİTİĞİ
## Mavi Fırın Projesi: Haftalık Uygulama ve Soru-Cevap Raporu

* **Öğrenci:** Ekrem Tezcan Sarıdağ
* **GitHub Deposu:** [https://github.com/EkremTezcanSaridag/mavifirin](https://github.com/EkremTezcanSaridag/mavifirin)
* **Canlı Yayın Adresi (GitHub Pages):** [https://ekremtezcansaridag.github.io/mavifirin/](https://ekremtezcansaridag.github.io/mavifirin/)

---

## 1. HAFTA — SEO ve Web Sitesini Tanıma

### Uygulama Soruları ve Çözümleri (U1 – U4)

* **H01-U1 | Bir aramayı yorumlayın:**
  * **Soru:** "Eskişehir tam buğday ekmeği" sorgusunda kullanıcı ne ister?
  * **Cevap:** Kullanıcı belirli bir ürünü (tam buğday ekmeği), yerel bir lokasyonda (Eskişehir) aramaktadır. Ana sayfada veya ürünler sayfasında ürün bilgisi, bulunabilirlik, içerik ve fırının açık adresi net bir şekilde yer almalıdır.

* **H01-U2 | Site sayfalarını sayın:**
  * **Soru:** `site/index.html` ve diğer HTML dosyalarının adlarını bulun.
  * **Cevap:** Sitede 4 ana HTML sayfası yer almaktadır:
    1. `index.html` (Ana sayfa)
    2. `urunler.html` (Ürünlerimiz)
    3. `hakkimizda.html` (Hakkımızda)
    4. `iletisim.html` (İletişim)

* **H01-U3 | Sonuç taslağı yazın:**
  * **Soru:** Mavi Fırın için Google aramasında görünmesini istediğiniz iki satır yazın (Title & Description).
  * **Cevap:**
    * **Başlık (Title):** `Mavi Fırın | Eskişehir Taze Ekmek`
    * **Açıklama (Meta Description):** `Günlük ekmek çeşitlerini, taş fırın lezzetlerimizi ve işletme adresimizi keşfedin.`

* **H01-U4 | Kontrol listesi hazırlayın:**
  * **Soru:** Ziyaretçi siteye geldiğinde hangi 3 bilgiye ulaşmalı?
  * **Cevap:**
    1. Ürün çeşitleri ve tazelik bilgisi,
    2. Açık adres ve iletişim kanalları,
    3. İşletme hakkında güven verici kısa tanıtım bilgisi.

### Sıra Sizde Görevleri ve Çözümleri (S1 – S4)

* **H01-S1 | Bağımsız Görev:**
  * **Soru:** "Yakınımdaki fırın" için hangi bilgi öne çıkmalı?
  * **Cevap:** Güncel açık adres, harita/ulaşım tarifi, çalışma saatleri (açılış-kapanış) ve doğrudan aranabilir telefon numarası öne çıkmalıdır.

* **H01-S2 | Bağımsız Görev:**
  * **Soru:** Her sayfanın tek cümle amacını yazın.
  * **Cevap:**
    * **index.html:** İşletmeyi genel olarak tanıtıp ziyaretçiyi ilgili ürün ve iletişim sayfalarına yönlendirmek.
    * **urunler.html:** Fırında her gün taze üretilen ekmek, simit ve unlu mamul çeşitlerini sergilemek.
    * **hakkimizda.html:** İşletmenin tarihçesini, hijyen anlayışını ve geleneksel üretim felsefesini anlatmak.
    * **iletisim.html:** Fırının fiziki adresini, çalışma gün/saatlerini ve iletişim formunu sunmak.

* **H01-S3 | Bağımsız Görev:**
  * **Soru:** Aynı işi (Google arama sonucu taslağı) ürünler sayfası için yapın.
  * **Cevap:**
    * **Başlık (Title):** `Ekmek ve Unlu Mamul Çeşitleri | Mavi Fırın`
    * **Açıklama (Meta Description):** `Her sabah fırından taze çıkan ekşi mayalı ekmek, çıtır simit ve poğaça çeşitlerimizi inceleyin.`

* **H01-S4 | Bağımsız Görev:**
  * **Soru:** Sitede eksik olabilecek iki bilgi önerin.
  * **Cevap:** 
    1. Ana sayfada belirgin olarak vurgulanan açılış-kapanış çalışma saatleri,
    2. Ürünlerin gerçek ve yüksek çözünürlüklü fotoğrafları ile güncel fiyat listesi.

---

## 2. HAFTA — HTML, CSS ve Sayfa Yapısı

### Uygulama Soruları ve Çözümleri (U1 – U4)

* **H02-U1 | Ana başlığı bulun:**
  * **Soru:** `index.html` içinde `<h1>` etiketini bulun ve anlamını açıklayın.
  * **Cevap:** `<h1>` etiketi, sayfanın ana konusunu ve başlığını belirten en üst düzey başlıktır. SEO açısından arama motorlarına sayfanın ne hakkında olduğunu anlatan en kritik başlıktır ve her sayfada kural olarak bir adet bulunmalıdır.

* **H02-U2 | Bağlantı ekleyin:**
  * **Soru:** `index.html` dosyasında ürünler sayfasına bağlantı oluşturun.
  * **Cevap:** `<a href="urunler.html">Ürünleri Gör</a>` etiketi kullanılarak menü ve hero butonları üzerinden ürünler sayfasına köprü kurulmuştur.

* **H02-U3 | CSS değiştirin:**
  * **Soru:** `style.css` dosyasında `h1` için yazı rengi belirleyin.
  * **Cevap:** `style.css` dosyasına `h1 { color: #163b65; }` kuralı eklenerek ana başlık kurumsal koyu mavi renge ayarlanmıştır.

* **H02-U4 | Mobil test yapın:**
  * **Soru:** Tarayıcı penceresini daraltıp metinleri gözlemleyin.
  * **Cevap:** Tarayıcı penceresi daraltıldığında CSS `@media(max-width:600px)` kuralları sayesinde menü bağlantılarının alt alta/esnek sıralandığı, metinlerin taşmadığı ve mobil cihazlarda okunabilirliğin korunduğu test edilmiştir.

### Sıra Sizde Görevleri ve Çözümleri (S1 – S4)

* **H02-S1 | Bağımsız Görev:**
  * **Soru:** Ana sayfa başlığını daha bilgilendirici yazın.
  * **Cevap:** `index.html` dosyasındaki başlık `<h1>Mavi Fırın | Eskişehir Taze Ekmek</h1>` olarak güncellenmiştir. Ayrıca hero bölümüne `<a class="btn" href="urunler.html">Ürünleri Gör</a>` ve `<a class="btn" href="hakkimizda.html">Hakkımızda</a>` butonları eklenmiştir.

* **H02-S2 | Bağımsız Görev:**
  * **Soru:** Hakkımızda bağlantısı ekleyin.
  * **Cevap:** Gezinme çubuğuna ve sayfa içine `<a href="hakkimizda.html">Hakkımızda</a>` bağlantısı eklenerek göreli yol (relative path) ile sayfalar arası geçiş sağlanmıştır.

* **H02-S3 | Bağımsız Görev:**
  * **Soru:** Bağlantılara altı çizili görünüm verin.
  * **Cevap:** `style.css` dosyasına `a { text-decoration: underline; }` kuralı eklenerek metin içindeki linklerin tıklanabilir olduğu belirginleştirilmiştir.

* **H02-S4 | Bağımsız Görev:**
  * **Soru:** Taşan bir öğe varsa değişikliği tarif edin.
  * **Cevap:** Küçük ekranlarda yatay kaydırma çubuğunun (horizontal scroll) çıkmasını engellemek için öğelere sabit genişlik (`width: 800px`) yerine esnek genişlik (`max-width: 100%`) verilmelidir.

---

## 3. HAFTA — GitHub Pages ile Ücretsiz Yayınlama

### Uygulama Soruları ve Çözümleri (U1 – U4)

* **H03-U1 | Depo açın:**
  * **Soru:** `GitHub > New repository > mavifirin > Public` adımlarını izleyin.
  * **Cevap:** GitHub üzerinde `mavifirin` adıyla herkese açık (Public) bir repository oluşturulmuştur.

* **H03-U2 | Dosyaları yükleyin:**
  * **Soru:** `index.html`, `style.css` ve diğer HTML dosyalarını depoya ekleyin.
  * **Cevap:** Sitenin ana dizininde `index.html`, `style.css`, `hakkimizda.html`, `iletisim.html`, `urunler.html`, `robots.txt` ve `sitemap-ORNEK.xml` dosyaları doğrudan kök dizine yüklenmiştir.

* **H03-U3 | Pages ayarlayın:**
  * **Soru:** `Settings > Pages > Deploy from a branch > main > /(root)` adımlarını uygulayın.
  * **Cevap:** GitHub Pages ayarı yapılarak `main` dalı kök dizinden yayınlanmıştır. Canlı site `https://ekremtezcansaridag.github.io/mavifirin/` adresinden HTTPS güvencesiyle erişilebilir hale gelmiştir.

* **H03-U4 | Hata ayıklayın:**
  * **Soru:** Site açılıyor ancak CSS görünmüyor: ilk neyi incelersiniz?
  * **Cevap:** 
    1. `style.css` dosyasının ana dizinde olup olmadığı,
    2. HTML dosyasındaki `<link rel="stylesheet" href="style.css">` yolunun doğruluğu,
    3. Dosya adındaki büyük/küçük harf uyumu (GitHub Linux tabanlı olduğu için `Style.css` ile `style.css` fark eder) incelenir.

### Sıra Sizde Görevleri ve Çözümleri (S1 – S4)

* **H03-S1 | Bağımsız Görev:**
  * **Soru:** Depo açıklamasını bir cümle yazın.
  * **Cevap:** Reponun About kısmına *"SEO dersi için örnek Türkçe fırın web sitesi."* açıklaması tanımlanmıştır.

* **H03-S2 | Bağımsız Görev:**
  * **Soru:** İkinci commit ile H1 başlığını değiştirin.
  * **Cevap:** H1 başlığı `Mavi Fırın – Günlük Taze Ekmek` olarak değiştirilmiş ve commit mesajı *"Ana sayfa başlığı güncellendi"* şeklinde oluşturulmuştur.

* **H03-S3 | Bağımsız Görev:**
  * **Soru:** Sayfayı telefonunuzda açın.
  * **Cevap:** Yayınlanan GitHub Pages linki akıllı telefon tarayıcısında açılmış; menülerin, kartların ve metinlerin ekrana tam oturduğu, butonların rahatça dokunulabildiği gözlemlenmiştir.

* **H03-S4 | Bağımsız Görev:**
  * **Soru:** Ürün bağlantısı 404 veriyorsa ne yaparsınız?
  * **Cevap:** Linkteki `href="urunler.html"` değeri ile dosya adının (`urunler.html`) birebir aynı yazılıp yazılmadığı (Türkçe karakter veya yazım hatası olup olmadığı) kontrol edilir.
