# 🛠 Pro-Cut Tools — Professional Catalogue Website

## 📁 Folder Structure
```
procut-catalogue/
├── index.html          ← Main catalogue website
├── admin.html          ← Admin panel to edit products
├── assets/
│   ├── logo-light.jpg  ← Logo on white background
│   └── logo-dark.jpg   ← Logo on dark background
└── data/
    └── products.json   ← All product data (edit this to update catalogue)
```

---

## 🚀 Deploy to GitHub Pages (FREE)

1. Go to [github.com](https://github.com) → Sign up/Login
2. Click **New Repository** → Name: `procut-catalogue` → Public → Create
3. Click **Upload files** → Drag your entire `procut-catalogue/` folder contents
4. Click **Commit changes**
5. Go to **Settings** → **Pages** → Source: `Deploy from a branch` → Branch: `main` / `(root)` → **Save**
6. ✅ Your site is live at: `https://YOUR-USERNAME.github.io/procut-catalogue/`

---

## 📱 WhatsApp Setup

Open `index.html` in any text editor. Find line:
```js
const WA_NUMBER = '919999999999';
```
Replace with your number (country code + number, no + or spaces):
- India: `919876543210`

---

## 💰 Updating Prices / Products

### Option A — Admin Panel (Easiest)
1. Open `admin.html` in your browser
2. Edit prices directly in the table
3. Click **Export JSON** button → downloads `products.json`
4. Replace `data/products.json` in your folder
5. Upload to GitHub → site updates automatically

### Option B — Edit JSON directly
Open `data/products.json` in a text editor (VS Code recommended).
Each product:
```json
{
  "id": 1,
  "name": "Heavy Duty Rubber Mallet",
  "category": "Hand Tools",
  "code": "HT001A",
  "wholesalePrice": 120,
  "endUserPrice": 180,
  "gst": 18
}
```
Change the numbers, save, upload to GitHub.

---

## ✨ Features
- ✅ 1300+ products auto-imported from your Excel
- ✅ 17 product categories
- ✅ Live search with highlighting
- ✅ Category filter bar
- ✅ Price & name sorting
- ✅ Grid and list view
- ✅ Product detail popup/modal
- ✅ WhatsApp enquiry button per product
- ✅ Admin panel to add/edit/delete products
- ✅ Export updated JSON
- ✅ Mobile responsive
- ✅ Fast (no framework, pure HTML/JS)
- ✅ SEO friendly
- ✅ Works on GitHub Pages (100% free)

---

## 🎨 Brand Colors
- Gold: `#FFB800`
- Black: `#0A0A0A`
- Dark Blue: `#2823CC`
