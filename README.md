# dungcony.github.io

# 🎨 Portfolio Cá Nhân - GitHub Pages

Portfolio website hiện đại và responsive được xây dựng với HTML, CSS, JavaScript thuần và triển khai trên GitHub Pages.

## ✨ Tính Năng

- 🎯 **Responsive Design**: Hoạt động tốt trên mọi thiết bị
- 🚀 **Performance**: Tốc độ tải nhanh, tối ưu SEO
- 💫 **Animations**: Hiệu ứng mượt mà và chuyên nghiệp
- 📱 **Mobile-First**: Thiết kế ưu tiên mobile
- 🎨 **Modern UI**: Giao diện hiện đại với gradient và shadow
- ⚡ **Lightweight**: Không sử dụng framework nặng

## 🛠️ Công Nghệ Sử Dụng

- **HTML5**: Semantic markup
- **CSS3**: Flexbox, Grid, Animations, Custom Properties
- **JavaScript ES6+**: Modern JavaScript features
- **Font Awesome**: Icons
- **GitHub Pages**: Hosting miễn phí

## 📂 Cấu Trúc Thư Mục

```
portfolio/
├── index.html          # Trang chính
├── styles.css          # Styles chính
├── script.js           # JavaScript functionality
├── README.md           # Documentation
└── assets/             # Hình ảnh và tài nguyên
    ├── images/
    └── icons/
```

## 🚀 Hướng Dẫn Cài Đặt

### Bước 1: Tạo Repository GitHub
```bash
# Tạo repo mới với tên: username.github.io
# Thay 'username' bằng GitHub username của bạn
```

### Bước 2: Clone và Setup
```bash
git clone https://github.com/username/username.github.io.git
cd username.github.io

# Copy các files template vào thư mục
cp -r portfolio-template/* .
```

### Bước 3: Tùy Chỉnh Nội Dung
1. **Thông tin cá nhân** trong `index.html`:
   - Tên, title, mô tả
   - Thông tin liên hệ
   - Links social media

2. **Dự án** trong section `#projects`:
   - Thêm hình ảnh dự án
   - Mô tả và công nghệ sử dụng
   - Links demo và source code

3. **Kỹ năng** trong section `#skills`:
   - Cập nhật danh sách kỹ năng
   - Thêm/bớt công nghệ

### Bước 4: Deploy lên GitHub Pages
```bash
git add .
git commit -m "Initial portfolio setup"
git push origin main

# Vào Settings > Pages > Source: Deploy from a branch > main
```

## 🎨 Tùy Chỉnh Theme

### Màu Sắc
Chỉnh sửa CSS variables trong `styles.css`:
```css
:root {
  --primary-color: #4f46e5;
  --secondary-color: #fbbf24;
  --text-color: #333;
  --bg-color: #f9fafb;
}
```

### Font Chữ
```css
body {
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
}
```

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px  
- **Desktop**: > 1024px

## 🔧 Tính Năng JavaScript

- ✅ Mobile navigation toggle
- ✅ Smooth scrolling
- ✅ Active navigation highlighting
- ✅ Scroll animations
- ✅ Contact form validation
- ✅ Typing animation
- ✅ Scroll to top button
- ✅ Lazy loading images
- ✅ Performance optimization

## 🌐 Cấu Hình Custom Domain

### Tại GitHub:
1. Settings > Pages > Custom domain: `yourdomain.com`
2. Check "Enforce HTTPS"

### Tại Tenten:
```
A Record: @ → 185.199.108.153
A Record: @ → 185.199.109.153  
A Record: @ → 185.199.110.153
A Record: @ → 185.199.111.153
CNAME: www → username.github.io
```

## 📈 SEO Optimization

### Meta Tags
```html
<meta name="description" content="Portfolio của [Tên] - Web Developer">
<meta name="keywords" content="portfolio, web developer, frontend, backend">
<meta property="og:title" content="[Tên] - Portfolio">
<meta property="og:description" content="Nhà phát triển web chuyên nghiệp">
```

### Structured Data
```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "Tên của bạn",
  "jobTitle": "Web Developer",
  "url": "https://yourdomain.com"
}
</script>
```

## 🚀 Performance Tips

1. **Optimize Images**: 
   - Sử dụng WebP format
   - Lazy loading
   - Responsive images

2. **Minify Code**:
   ```bash
   # CSS
   csso styles.css -o styles.min.css
   
   # JavaScript  
   terser script.js -o script.min.js
   ```

3. **Enable Caching**: Thêm `.htaccess`:
   ```apache
   <IfModule mod_expires.c>
     ExpiresActive on
     ExpiresByType text/css "access plus 1 year"
     ExpiresByType application/javascript "access plus 1 year"
   </IfModule>
   ```

## 📊 Analytics

### Google Analytics
```html
<!-- Global site tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🔒 Security

- ✅ HTTPS enforced
- ✅ Content Security Policy
- ✅ XSS Protection
- ✅ Input validation

## 📝 Checklist Trước Khi Deploy

- [ ] Cập nhật thông tin cá nhân
- [ ] Thêm dự án thực tế
- [ ] Test responsive trên các thiết bị
- [ ] Kiểm tra links hoạt động
- [ ] Tối ưu hình ảnh
- [ ] Setup Google Analytics
- [ ] Test performance (GTMetrix, PageSpeed)
- [ ] Cấu hình custom domain

## 🆘 Troubleshooting

### GitHub Pages không hiển thị:
1. Kiểm tra Settings > Pages
2. Đảm bảo file `index.html` ở root
3. Chờ 10-15 phút để propagate

### Custom domain không hoạt động:
1. Kiểm tra DNS records
2. Xóa và thêm lại domain
3. Chờ DNS propagation (24-48h)

## 📞 Hỗ Trợ

Nếu gặp vấn đề, hãy:
1. Kiểm tra GitHub Pages status
2. Xem logs trong Developer Tools
3. Tham khảo GitHub Pages documentation

## 📄 License

MIT License - Sử dụng tự do cho dự án cá nhân và thương mại.

---

**🌟 Chúc bạn thành công với portfolio mới!**

Đừng quên ⭐ star repo nếu thấy hữu ích!