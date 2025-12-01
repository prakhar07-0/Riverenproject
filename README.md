# Riveren - Premium Packaged Drinking Water

**Riveren – Pure. Safe. Refreshing.**

A complete brand launch package for Riveren packaged drinking water, including landing page, brand identity, and marketing materials.

---

## 📁 Project Structure

```
Riverenproject/
├── index.html              # Main landing page
├── images/                 # Product images
│   ├── hero-bottle.png
│   ├── bottle-250ml.png
│   ├── bottle-500ml.png
│   └── bottle-1l.png
├── BRAND_IDENTITY.md       # Brand guidelines
├── MARKETING_CONTENT.md    # Marketing materials
└── README.md              # This file
```

---

## 🚀 Quick Deployment Options

### Option 1: Netlify (Recommended - Easiest)

**Steps:**
1. Go to [netlify.com](https://www.netlify.com/)
2. Sign up for a free account
3. Click "Add new site" → "Deploy manually"
4. Drag and drop the entire `Riverenproject` folder
5. Your site will be live in seconds!
6. Custom domain: Site settings → Domain management → Add custom domain

**Pros:** Free, instant SSL, automatic deployments, easy custom domain setup

---

### Option 2: Vercel

**Steps:**
1. Install Vercel CLI: `npm install -g vercel`
2. Navigate to project folder: `cd d:\Riverenproject`
3. Run: `vercel`
4. Follow the prompts
5. Your site is deployed!

**Pros:** Free, excellent performance, automatic HTTPS

---

### Option 3: GitHub Pages

**Steps:**
1. Create a GitHub account at [github.com](https://github.com)
2. Create a new repository named `riveren-website`
3. Upload all files from `Riverenproject` folder
4. Go to Settings → Pages
5. Select branch: `main`, folder: `/ (root)`
6. Click Save
7. Your site will be live at `https://yourusername.github.io/riveren-website`

**Pros:** Free, version control included, reliable

---

### Option 4: Traditional Web Hosting

**Requirements:**
- Web hosting account (Hostinger, Bluehost, GoDaddy, etc.)
- FTP client (FileZilla)

**Steps:**
1. Purchase hosting plan and domain
2. Connect via FTP using credentials from hosting provider
3. Upload all files to `public_html` or `www` folder
4. Access your site at your domain

---

## 🔧 Pre-Deployment Checklist

### Required Updates

- [ ] **Update contact information** in `index.html` (footer section):
  - Email address (currently: `info@riveren.com`)
  - Phone number (currently: `+91 1800-RIVEREN`)
  - Physical address (currently: `Your City, India`)

- [ ] **Update social media links** in footer (currently placeholder `#`)

- [ ] **Test contact form** - Currently shows alert, consider integrating:
  - [Formspree](https://formspree.io/) (free)
  - [EmailJS](https://www.emailjs.com/) (free)
  - [Web3Forms](https://web3forms.com/) (free)

### Optional Enhancements

- [ ] Add Google Analytics tracking code
- [ ] Add Facebook Pixel for ad tracking
- [ ] Set up custom 404 error page
- [ ] Add robots.txt and sitemap.xml for SEO
- [ ] Compress images for faster loading

---

## 📱 Testing Before Deployment

1. **Local Testing:**
   - Open `index.html` in multiple browsers (Chrome, Firefox, Safari, Edge)
   - Test on mobile devices or use browser dev tools (F12 → Device toolbar)

2. **Check Responsiveness:**
   - Desktop (1920px, 1366px)
   - Tablet (768px)
   - Mobile (375px, 414px)

3. **Verify All Links:**
   - Navigation links work
   - CTA buttons function
   - Social media icons (update with real links)

4. **Test Contact Form:**
   - All fields required
   - Form submission works

---

## 🌐 Custom Domain Setup

After deploying, connect your custom domain:

### For Netlify:
1. Purchase domain from Namecheap, GoDaddy, or Google Domains
2. In Netlify: Site settings → Domain management → Add custom domain
3. Update DNS records at your domain registrar:
   - Add A record: `185.199.108.153`
   - Add CNAME: `www` → `your-site.netlify.app`

### For Vercel:
1. In Vercel dashboard: Settings → Domains
2. Add your domain
3. Update DNS records as instructed

---

## 📊 Post-Deployment Steps

1. **Set up Google Search Console**
   - Submit sitemap
   - Monitor search performance

2. **Set up Google Analytics**
   - Track visitor behavior
   - Monitor conversions

3. **Social Media Integration**
   - Update footer links with real profiles
   - Add Open Graph meta tags for better sharing

4. **Performance Optimization**
   - Run Google PageSpeed Insights
   - Optimize images if needed
   - Enable caching

---

## 🛠️ Technical Details

- **Framework:** Pure HTML/CSS/JavaScript (no build process needed)
- **Fonts:** Google Fonts (Poppins, Inter)
- **Images:** PNG format, stored in `/images` folder
- **Browser Support:** All modern browsers (Chrome, Firefox, Safari, Edge)
- **Mobile:** Fully responsive design

---

## 📞 Support & Maintenance

### Updating Content

- **Text changes:** Edit `index.html` directly
- **Images:** Replace files in `/images` folder (keep same filenames)
- **Styling:** Modify CSS in `<style>` section of `index.html`

### Common Issues

**Images not loading:**
- Ensure `/images` folder is uploaded
- Check file paths are correct
- Verify image filenames match exactly

**Contact form not working:**
- Integrate a form service (see Pre-Deployment Checklist)
- Update JavaScript in `index.html`

---

## 📄 License & Credits

**Brand:** Riveren  
**Tagline:** Pure. Safe. Refreshing.  
**Created:** December 2025

---

## 🎯 Next Steps

1. Choose a deployment platform (Netlify recommended)
2. Update contact information
3. Deploy the site
4. Set up custom domain
5. Launch marketing campaigns!

For questions or support, refer to the deployment platform's documentation.

**Good luck with your launch! 🚀**
