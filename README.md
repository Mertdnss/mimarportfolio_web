# İç Mimar Portfolio Sitesi

Modern ve responsive bir iç mimar portfolio sitesi. Bu site, iç mimarların projelerini sergilemek, hizmetlerini tanıtmak ve potansiyel müşterilerle iletişim kurmak için tasarlanmıştır.

## 🌟 Özellikler

### 📱 Responsive Tasarım
- Tüm cihazlarda (masaüstü, tablet, mobil) mükemmel görünüm
- Modern ve şık kullanıcı arayüzü
- Mobil öncelikli tasarım yaklaşımı

### 🎨 Modern UI/UX
- Gradient renkler ve modern tipografi
- Smooth animasyonlar ve geçişler
- Parallax efektleri
- Hover efektleri ve interaktif elementler

### 📂 Bölümler
1. **Ana Sayfa (Hero)** - Etkileyici giriş bölümü
2. **Hakkımda** - Kişisel bilgiler ve yetenekler
3. **Portfolio** - Proje galerisi ve filtreleme
4. **Hizmetler** - Sunulan hizmetlerin detayları
5. **İletişim** - İletişim formu ve bilgileri

### ⚡ İnteraktif Özellikler
- Portfolio filtreleme sistemi
- Mobil hamburger menü
- Smooth scroll navigasyon
- İletişim formu validasyonu
- Bildirim sistemi
- "Yukarı çık" butonu
- Typing efekti
- Intersection Observer animasyonları

## 🛠️ Teknolojiler

- **HTML5** - Semantik yapı
- **CSS3** - Modern styling ve animasyonlar
  - Flexbox ve Grid Layout
  - CSS Variables
  - Responsive Media Queries
  - Gradient ve Box Shadow efektleri
- **JavaScript (ES6+)** - İnteraktif özellikler
  - DOM Manipulation
  - Event Listeners
  - Intersection Observer API
  - Form Validation
- **Font Awesome** - İkonlar
- **Google Fonts** - Poppins font ailesi

## 📁 Dosya Yapısı

```
icmimar_portfolio/
├── index.html          # Ana HTML dosyası
├── styles.css          # CSS stilleri
├── script.js           # JavaScript fonksiyonları
└── README.md           # Proje dokümantasyonu
```

## 🚀 Kurulum ve Kullanım

1. **Dosyaları İndirin**
   ```bash
   # Proje klasörünü bilgisayarınıza kopyalayın
   ```

2. **Tarayıcıda Açın**
   - `index.html` dosyasını çift tıklayarak açın
   - Veya bir web sunucusu kullanın (önerilen)

3. **Yerel Sunucu (Opsiyonel)**
   ```bash
   # Python ile basit sunucu
   python -m http.server 8000
   
   # Node.js ile live-server
   npx live-server
   ```

## ✏️ Özelleştirme

### Kişisel Bilgileri Güncelleme

1. **index.html** dosyasında aşağıdaki bölümleri düzenleyin:
   - İsim ve başlık
   - Hakkımda metni
   - İletişim bilgileri
   - Sosyal medya linkleri

2. **Renkler** - `styles.css` dosyasında CSS değişkenlerini düzenleyin:
   ```css
   :root {
     --primary-color: #3498db;
     --secondary-color: #2980b9;
     --accent-color: #f39c12;
   }
   ```

3. **Portfolio Projeleri** - Yeni projeler eklemek için:
   ```html
   <div class="portfolio-item" data-category="residential">
     <!-- Proje içeriği -->
   </div>
   ```

### Gerçek Görseller Ekleme

1. `images/` klasörü oluşturun
2. Görselleri bu klasöre ekleyin
3. HTML'deki placeholder'ları gerçek görsellerle değiştirin:
   ```html
   <img src="images/proje1.jpg" alt="Proje Açıklaması">
   ```

## 📧 İletişim Formu Entegrasyonu

İletişim formunu çalışır hale getirmek için:

1. **EmailJS** kullanın (ücretsiz)
2. **Netlify Forms** (Netlify'da host ediyorsanız)
3. **PHP backend** ekleyin
4. **Node.js/Express** sunucusu oluşturun

### EmailJS Örneği:
```javascript
// script.js dosyasına ekleyin
emailjs.send('service_id', 'template_id', {
    name: formData.get('name'),
    email: formData.get('email'),
    message: formData.get('message')
});
```

## 🎯 SEO Optimizasyonu

1. **Meta etiketleri** ekleyin:
   ```html
   <meta name="description" content="Profesyonel iç mimarlık hizmetleri">
   <meta name="keywords" content="iç mimar, tasarım, dekorasyon">
   ```

2. **Open Graph** etiketleri:
   ```html
   <meta property="og:title" content="İç Mimar Portfolio">
   <meta property="og:description" content="Modern iç mimarlık projeleri">
   ```

3. **Structured Data** ekleyin

## 🌐 Hosting Önerileri

- **Netlify** (Ücretsiz, kolay deployment)
- **Vercel** (Ücretsiz, hızlı)
- **GitHub Pages** (Ücretsiz)
- **Firebase Hosting** (Google)

## 📱 Performans Optimizasyonu

1. **Görselleri optimize edin**
   - WebP formatı kullanın
   - Lazy loading ekleyin
   - Responsive images

2. **CSS/JS minify edin**
3. **CDN kullanın**
4. **Caching stratejileri**

## 🔧 Gelecek Geliştirmeler

- [ ] Blog bölümü
- [ ] Çoklu dil desteği
- [ ] Dark mode
- [ ] Proje detay sayfaları
- [ ] Müşteri yorumları
- [ ] Online randevu sistemi
- [ ] 3D model görüntüleyici
- [ ] Sanal tur entegrasyonu

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Ticari ve kişisel projelerinizde özgürce kullanabilirsiniz.

## 🤝 Katkıda Bulunma

Projeyi geliştirmek için:
1. Fork edin
2. Feature branch oluşturun
3. Değişikliklerinizi commit edin
4. Pull request gönderin

## 📞 Destek

Sorularınız için:
- GitHub Issues
- E-posta: [email]
- LinkedIn: [profile]

---

**Not:** Bu template, iç mimarlar için özel olarak tasarlanmış modern bir portfolio sitesidir. Kendi ihtiyaçlarınıza göre özelleştirerek kullanabilirsiniz.

🏠 **İyi tasarımlar!** ✨