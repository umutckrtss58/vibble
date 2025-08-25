# 🎯 Vibble - Karar Yardımcısı Sosyal Uygulama

Modern, responsive ve interaktif web sitesi. Karar anında yalnız kalmamak için tasarlanmış sosyal karar yardımcısı platformu.

## ✨ Özellikler

- 🎨 **Modern Tasarım**: Gradient renkler, smooth animasyonlar ve responsive layout
- 📱 **Mobile First**: Tüm cihazlarda mükemmel görünüm
- 🚀 **Performance**: Optimize edilmiş kod ve lazy loading
- 🎭 **Animasyonlar**: Scroll-based animasyonlar ve interaktif elementler
- 📝 **Form Handling**: İletişim formu ve validation
- 🔍 **SEO Optimized**: Meta tags ve structured data
- ♿ **Accessibility**: Keyboard navigation ve screen reader desteği

## 🚀 Hızlı Başlangıç

### Gereksinimler
- Modern web tarayıcısı
- Web sunucusu (Apache, Nginx, Vercel, Netlify, vb.)

### Kurulum

1. **Dosyaları indirin**
   ```bash
   git clone [repository-url]
   cd vibble-website
   ```

2. **Web sunucusuna yükleyin**
   - Tüm dosyaları web sunucunuzun root dizinine kopyalayın
   - Veya modern hosting platformlarından birini kullanın

3. **Tarayıcıda açın**
   - Web sitenizi tarayıcıda açın
   - Tüm özellikler çalışır durumda olmalı

## 📁 Proje Yapısı

```
vibble-website/
├── index.html          # Ana HTML dosyası
├── styles.css          # CSS stilleri
├── script.js           # JavaScript fonksiyonları
├── images/             # Resim dosyaları
│   ├── logo.svg        # SVG logo
│   └── ...            # Diğer resimler
├── README.md           # Bu dosya
├── package.json        # NPM scripts
└── vercel.json         # Vercel deployment
```

## 🌐 Deployment Seçenekleri

### 1. Vercel (Önerilen)
```bash
npm install -g vercel
vercel
```

### 2. Netlify
- Netlify Dashboard'a gidin
- "New site from Git" seçin
- Repository'nizi bağlayın
- Otomatik deploy

### 3. GitHub Pages
- Repository Settings > Pages
- Source: Deploy from a branch
- Branch: main, folder: / (root)

### 4. Traditional Hosting
- FTP/SFTP ile dosyaları yükleyin
- Apache/Nginx konfigürasyonu yapın

## 🎨 Özelleştirme

### Renkleri Değiştirme
`styles.css` dosyasında CSS değişkenlerini güncelleyin:

```css
:root {
  --primary-color: #6a11cb;
  --secondary-color: #2575fc;
  --accent-color: #ffd700;
}
```

### Logo Değiştirme
- `images/logo.svg` dosyasını kendi logonuzla değiştirin
- Favicon için `.ico` formatında dosya oluşturun

### İçerik Güncelleme
- `index.html` dosyasında metinleri güncelleyin
- Resimleri `images/` klasöründe değiştirin

## 📱 Responsive Breakpoints

- **Desktop**: 1024px+
- **Tablet**: 768px - 1023px
- **Mobile**: 320px - 767px

## 🔧 Teknik Detaylar

### CSS Framework
- Custom CSS (Framework kullanılmadı)
- CSS Grid ve Flexbox
- CSS Variables
- Media Queries

### JavaScript
- Vanilla JavaScript (ES6+)
- Intersection Observer API
- Event Delegation
- Performance optimizations

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🚀 Performance Optimizations

- Lazy loading images
- Debounced scroll events
- CSS animations (GPU accelerated)
- Minified assets
- Preload critical resources

## 📊 SEO Features

- Meta tags (title, description, keywords)
- Open Graph tags
- Twitter Card support
- Structured data
- Semantic HTML
- Alt text for images

## 🎯 Özellikler

### Hero Section
- Gradient background
- Floating decision cards
- Animated statistics
- Call-to-action buttons

### How It Works
- 3-step process
- Interactive cards
- Hover effects

### Features Grid
- 6 main features
- Icon-based design
- Responsive layout

### Contact Form
- Form validation
- Success/error notifications
- Responsive design

## 🐛 Sorun Giderme

### Resimler Yüklenmiyor
- `images/` klasörünün doğru yerde olduğundan emin olun
- Dosya yollarını kontrol edin

### CSS Çalışmıyor
- `styles.css` dosyasının `index.html` ile aynı dizinde olduğundan emin olun
- Browser console'da hata olup olmadığını kontrol edin

### JavaScript Çalışmıyor
- `script.js` dosyasının `index.html` ile aynı dizinde olduğundan emin olun
- Browser console'da JavaScript hatalarını kontrol edin

## 📞 Destek

Herhangi bir sorun yaşarsanız:
- GitHub Issues açın
- E-posta: info@vibble.app
- Telefon: +90 (212) 555 0123

## 📄 Lisans

© 2025 Vibble. Tüm hakları saklıdır.

## 🙏 Teşekkürler

- Inter font family
- Modern CSS features
- Web standards community

---

**Vibble** - Karar anında yalnız değilsin! 💜 