# Pralhad Vaishnav - Portfolio Website

A modern, responsive portfolio website showcasing Product Manager expertise in emerging technologies including AI/ML, IoT, RegTech, and cloud platforms.

## 🚀 Features

- **Responsive Design**: Optimized for all devices and screen sizes
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, mobile navigation
- **Performance Optimized**: Fast loading with optimized assets
- **SEO Ready**: Proper meta tags and semantic HTML structure
- **Accessibility**: WCAG compliant with keyboard navigation support

## 📁 Files Structure

```
static-site/
├── index.html          # Main HTML file
├── styles.css          # All CSS styling
├── script.js           # Interactive JavaScript
└── README.md          # This file
```

## 🌐 Free Deployment Options

### Option 1: GitHub Pages (Recommended)

1. **Create a GitHub repository**
2. **Upload files**: Copy all files to your repository
3. **Enable Pages**: Go to Settings > Pages, select "Deploy from a branch"
4. **Custom domain**: Add your domain in Pages settings
5. **Update DNS**: Point your domain to GitHub Pages

**DNS Records for GitHub Pages:**
```
Type: A
Name: @
Value: 185.199.108.153

Type: A
Name: @
Value: 185.199.109.153

Type: A
Name: @
Value: 185.199.110.153

Type: A
Name: @
Value: 185.199.111.153

Type: CNAME
Name: www
Value: yourusername.github.io
```

### Option 2: Netlify

1. **Sign up** at netlify.com
2. **Drag and drop** the static-site folder
3. **Configure domain** in site settings
4. **Update DNS** as instructed by Netlify

### Option 3: Vercel

1. **Sign up** at vercel.com
2. **Import project** from GitHub or upload files
3. **Configure domain** in project settings
4. **Update DNS** as instructed by Vercel

### Option 4: Firebase Hosting

1. **Install Firebase CLI**: `npm install -g firebase-tools`
2. **Initialize project**: `firebase init hosting`
3. **Deploy**: `firebase deploy`
4. **Configure domain** in Firebase console

## 🛠️ Customization

### Adding Your Resume PDF

1. Add your resume PDF file to the static-site folder
2. Update the resume link in index.html:
   ```html
   <a href="your-resume.pdf" class="contact-link" download>
       Download PDF Resume
   </a>
   ```

### Adding Your Profile Photo

1. Add your photo to the static-site folder
2. Replace the placeholder in index.html:
   ```html
   <img src="your-photo.jpg" alt="Pralhad Vaishnav" class="profile-image">
   ```

### Updating Content

- **Personal Information**: Edit the content in index.html sections
- **Styling**: Modify styles.css for visual changes
- **Functionality**: Update script.js for interactive features

## 📊 Analytics Integration

To add Google Analytics:

1. **Get tracking code** from Google Analytics
2. **Add to head section** of index.html:
   ```html
   <!-- Google Analytics -->
   <script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
   <script>
     window.dataLayer = window.dataLayer || [];
     function gtag(){dataLayer.push(arguments);}
     gtag('js', new Date());
     gtag('config', 'GA_TRACKING_ID');
   </script>
   ```

## 🔧 Performance Tips

- **Optimize images**: Use WebP format when possible
- **Enable compression**: Configure gzip on your hosting platform
- **CDN**: Use a CDN for faster global loading
- **Caching**: Set appropriate cache headers

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 SEO Features

- Semantic HTML structure
- Meta descriptions and Open Graph tags
- Proper heading hierarchy
- Alt text for images
- Fast loading speeds
- Mobile-friendly design

## 📞 Support

For any issues or customizations needed, contact:
- **Email**: pralhadrvaishnav@gmail.com
- **LinkedIn**: [linkedin.com/in/pralhadvaishnav](https://www.linkedin.com/in/pralhadvaishnav/)

## 📄 License

This portfolio template is created for Pralhad Vaishnav. Feel free to use as inspiration for your own portfolio.

---

**Total Cost: $0** - This static website can be hosted completely free on any of the recommended platforms with your custom domain.