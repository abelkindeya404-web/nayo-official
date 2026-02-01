# Nayo Bag - Official Website

Ethiopia's Leading Industrial Eco-Bag Manufacturer

## 🌍 About

Nayo Bag is Ethiopia's premier manufacturer of eco-friendly non-woven bags, supporting the national plastic ban with 100% recyclable solutions.

## ✨ Features

- **React-Based Bulk Quote Generator** with Priority Partner status (15% discount for 5,000+ bags)
- **Dual Location Mapping** (Sales Office & Production Facility)
- **Mobile-First Quick Connect** (Telegram & Phone floating buttons)
- **Technical Product Catalog** (Box Bags, T-shirt Bags, D-cut Bags)
- **Fabric Texture Design** representing non-woven material (40-70 GSM)
- **Fully Responsive** mobile and desktop design

## 📍 Locations

### Sales Office
- **Address:** Megenagna Grace City Mall, 2nd Floor, Shop #206
- **City:** Addis Ababa, Ethiopia
- **Hours:** Mon-Sat: 8:00 AM - 6:00 PM

### Production Workshop
- **Address:** Goro, Opposite St. Gebriel Church
- **City:** Addis Ababa, Ethiopia
- **Hours:** Mon-Fri: 7:00 AM - 5:00 PM

## 📞 Contact

- **Phone:** +251 99 636 3636
- **Telegram:** @nayobag

## 🚀 Deployment to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top-right corner
3. Select **New repository**
4. Name it: `nayo-bag-website` (or your preferred name)
5. Set to **Public**
6. Click **Create repository**

### Step 2: Upload Files

#### Option A: Via GitHub Web Interface (Easiest)

1. On your new repository page, click **uploading an existing file**
2. Drag and drop ALL files from this folder:
   - `index.html`
   - `README.md`
   - `images/` folder (with all images inside)
3. Scroll down and click **Commit changes**

#### Option B: Via Git Command Line

```bash
cd nayo-bag-website
git init
git add .
git commit -m "Initial commit: Nayo Bag website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/nayo-bag-website.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Click **Pages** (left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

### Step 4: Access Your Website

After 1-2 minutes, your site will be live at:

```
https://YOUR-USERNAME.github.io/nayo-bag-website/
```

## 🎨 Customization

### Update Contact Information

Edit `index.html` and search for:
- Phone numbers: `+251 99 636 3636`
- Telegram: `@nayobag`
- Addresses: Update in the `Locations` component

### Update Images

Replace images in the `images/` folder:
- `logo.png` - Header logo
- `icon.png` - Favicon and footer
- `bulk_offer.jpeg` - Hero background
- Product images: `black_tote_png.png`, `blue_tote_png.png`, etc.

### Modify Pricing

In `index.html`, find the `calculatePrice` function:
```javascript
const materialCost = bagArea * gsm * 0.08; // Adjust 0.08
const productionCost = 0.65; // Adjust base cost
```

## 📱 Mobile Optimization

The site is optimized for mobile-first experience:
- Floating quick-connect buttons (90% of traffic is mobile)
- Responsive grid layouts
- Touch-friendly navigation
- Fast loading with CDN resources

## 🛠️ Technology Stack

- **React 18** - Interactive components
- **Tailwind CSS** - Utility-first styling
- **Google Fonts** - Inter & Space Grotesk
- **Pure HTML/CSS/JS** - No build process required

## 📊 Performance

- ✅ Mobile responsive
- ✅ Fast loading (CDN resources)
- ✅ SEO optimized
- ✅ Cross-browser compatible

## 📄 License

© 2026 Nayo Bag. All rights reserved.

## 🤝 Support

For technical support or business inquiries:
- 📞 Call: +251 99 636 3636
- ✈️ Telegram: @nayobag

---

**Built for Nayo Bag** - Supporting Ethiopia's Plastic Ban with 100% Recyclable Solutions