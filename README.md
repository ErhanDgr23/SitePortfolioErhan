# Portfolio Sitesi - GitHub Pages Deployment

Bu klasör, GitHub Pages'da yayınlanmak üzere hazırlanmış build dosyalarını içerir.

## GitHub Pages'da Yayınlama

1. GitHub'da `SitePortfolioErhan` adında bir repository oluşturun
2. Bu klasördeki tüm dosyaları repository'ye yükleyin
3. Repository ayarlarından GitHub Pages'ı etkinleştirin:
   - Settings > Pages > Source > Branch: main

## Önemli Notlar

- Site, HashRouter kullanılarak SPA yönlendirmeleri için yapılandırılmıştır
- 404.html dosyası, GitHub Pages'da SPA yönlendirmelerini desteklemek için eklenmiştir
- Tüm asset yolları `/SitePortfolioErhan/` base path'i ile yapılandırılmıştır

## Sorun Giderme

Eğer 404 hataları alıyorsanız:

1. Repository adının tam olarak `SitePortfolioErhan` olduğundan emin olun
2. Tüm dosyaların repository'nin root dizinine yüklendiğinden emin olun
3. GitHub Pages'ın etkinleştirildiğinden ve doğru branch'in seçildiğinden emin olun