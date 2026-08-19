# FJ Production — Website Spec (with ALL images)

> The complete website build prompt, plus the full list of owner images to use.

---

## BRAND NAME

**FJ Production**

## BUSINESS TYPE

Beauty & Skincare Products Production and Sales

## CONTACT

WhatsApp / Phone: **0333 4105708**

## BUSINESS ADDRESS

Sabih Beauty Salon, Main Bazar, Fatehgarh, Lahore, Pakistan

## GOOGLE BUSINESS PROFILE

https://maps.app.goo.gl/DVWHDLgLYU5bQCsbA

---

## IMAGES TO USE (ALL owner images)

### A. Owner product photos already in the website (63 images — `assets/products/`)

IMG-20260816-WA0006.jpg, IMG-20260817-WA0005.jpg, IMG-20260817-WA0018.jpg,
IMG-20260817-WA0019.jpg, IMG-20260817-WA0020.jpg, IMG-20260817-WA0021.jpg,
IMG-20260817-WA0022.jpg, IMG-20260817-WA0023.jpg, IMG-20260817-WA0024.jpg,
IMG-20260817-WA0025.jpg, IMG-20260817-WA0026.jpg, IMG-20260817-WA0027.jpg,
IMG-20260817-WA0028.jpg, IMG-20260817-WA0029.jpg, IMG-20260817-WA0030.jpg,
IMG-20260817-WA0031.jpg, IMG-20260817-WA0032.jpg, IMG-20260817-WA0033.jpg,
IMG-20260817-WA0034.jpg, IMG-20260817-WA0035.jpg, IMG-20260817-WA0036.jpg,
IMG-20260817-WA0037.jpg, IMG-20260817-WA0038.jpg, IMG-20260817-WA0039.jpg,
IMG-20260817-WA0040.jpg, IMG-20260817-WA0041.jpg, IMG-20260817-WA0042.jpg,
IMG-20260817-WA0043.jpg, IMG-20260817-WA0044.jpg, IMG-20260817-WA0045.jpg,
IMG-20260817-WA0046.jpg, IMG-20260817-WA0047.jpg, IMG-20260817-WA0048.jpg,
IMG-20260817-WA0049.jpg, IMG-20260817-WA0050.jpg, IMG-20260817-WA0051.jpg,
IMG-20260817-WA0052.jpg, IMG-20260817-WA0053.jpg, IMG-20260817-WA0054.jpg,
IMG-20260817-WA0055.jpg, IMG-20260817-WA0056.jpg, IMG-20260817-WA0057.jpg,
IMG-20260817-WA0058.jpg, IMG-20260817-WA0059.jpg, IMG-20260817-WA0060.jpg,
IMG-20260817-WA0061.jpg, IMG-20260817-WA0062.jpg, IMG-20260817-WA0063.jpg,
IMG-20260817-WA0064.jpg, IMG-20260817-WA0065.jpg, IMG-20260817-WA0066.jpg,
IMG-20260817-WA0067.jpg, IMG-20260817-WA0068.jpg, IMG-20260817-WA0069.jpg,
IMG-20260817-WA0070.jpg, IMG-20260817-WA0071.jpg, IMG-20260817-WA0072.jpg,
IMG-20260817-WA0073.jpg, IMG-20260817-WA0074.jpg, IMG-20260817-WA0075.jpg,
IMG-20260817-WA0076.jpg, IMG-20260817-WA0077.jpg, IMG-20260817-WA0078.jpg

### B. New owner images shared in chat (47 images — add to `assets/products/`)

1000003277.png, 1000003303.png, 1000003278.png, 1000003276.png,
1000003305.png, 1000003302.png, 1000003301.png, 1000003294.png,
1000003296.png, 1000003298.png, 1000003299.png, 1000003300.png,
1000003309.png, 1000003293.png, 1000003308.png, 1000003322.png,
1000003306.png, 1000003307.png, 1000003330.png, 1000003331.png,
1000003332.png, 1000003328.png, 1000003329.png, 1000003325.png,
1000003326.png, 1000003327.png, 1000003337.png, 1000003338.png,
1000003340.png, 1000003341.png, 1000003339.png, 1000003323.png,
1000003324.png, 1000003336.png, 1000003350.png, 1000003333.png,
1000003334.png, 1000003335.png, 1000003349.png, 1000003346.png,
1000003347.png, 1000003348.png, 1000003345.png, 1000003359.png,
1000003342.png, 1000003343.png, 1000003344.png

> These names are already registered in `assets/js/products.js` (OWNER_GALLERY_IMAGES).
> As soon as the PNG files are placed in `assets/products/`, they appear in the
> "Product gallery" section automatically. Missing files are hidden automatically.

### C. Brand hero banner

`assets/brand-hero-banner.jpg` — premium skincare showcase banner (hero section).

---

## WEBSITE REQUIREMENTS

Develop a premium, professional online skincare store for FJ Production that
exclusively showcases and sells beauty and skincare products.

Customers should be able to:

- Browse skincare products
- View product images
- View product names
- View product prices
- Read product descriptions
- Select products
- Place orders directly via WhatsApp

### IMPORTANT — No online payment gateway

Do NOT include credit/debit cards, PayPal, Stripe, JazzCash, Easypaisa, or any
form of online checkout. All orders are completed exclusively through WhatsApp.

### Product data rules

- Use ONLY the product images provided by the business owner.
- Do NOT generate or replace images with stock photos.
- Use only exact owner-provided names, prices, and descriptions.
- Do NOT invent prices, fake discounts, or promotions.
- Each product must include a clearly visible "ORDER ON WHATSAPP" button that
  opens WhatsApp (0333 4105708) with a pre-filled order message:

```
Hello FJ Production, I would like to place an order:

Product: [Product Name]
Price: [Product Price]
Quantity: [Quantity]

Kindly confirm my order.
```

Works across Android, iPhones, desktop and all mobile browsers.

### Design direction

Luxury, elegant, clean, feminine, premium skincare brand aesthetic:
soft premium background tones, elegant modern typography, high-quality product
presentation, rounded refined product cards, smooth subtle animations, premium
CTAs, balanced white space, modern intuitive navigation, mobile-first layout.
Subtle, smooth, performance-friendly animations.

### Hero section

- Title: FJ Production — "Premium Beauty & Skincare Products"
- Supporting text: "Discover high-quality skincare products designed to become
  an essential part of your daily beauty routine."
- Primary button: "SHOP SKINCARE"
- Secondary button: "ORDER ON WHATSAPP"
- Authentic product imagery provided by the business.

### Category system

Only display categories that correspond to actual products provided by the
owner (e.g., Face Care, Serums, Face Wash, Moisturizers, Creams, Toners,
Face Masks, Sunscreen, Other Skincare).

### Product grid & detail pages

Product card: image, name, price, short description, category label,
"View Details" and "Order on WhatsApp" buttons.

Product page: high-resolution image, name, exact price, full description,
key features and usage instructions (only if provided), size/quantity details,
prominent "ORDER ON WHATSAPP" button.

Do NOT add or assume any product specifications not provided by the owner.

### Search & filtering

Search by name; filter by category, price range, and product type.
Smooth performance across all devices.

### Shopping flow (no checkout)

Browse products → open product details → select quantity →
click "Order on WhatsApp" → WhatsApp opens with pre-filled order →
customer sends message → FJ Production confirms via WhatsApp.

### About section

Describe FJ Production as a dedicated beauty and skincare brand using clear,
professional, trustworthy language. Avoid unverified claims (dermatologist
approved, guaranteed results, chemical-free, medical-grade, FDA approval)
unless explicitly provided and verified by the owner.

Display: FJ Production, WhatsApp/Phone 0333 4105708,
Address: Sabih Beauty Salon, Main Bazar, Fatehgarh, Lahore, Pakistan.
Buttons: "Chat on WhatsApp" and "Get Directions"
(→ https://maps.app.goo.gl/DVWHDLgLYU5bQCsbA).

### Floating WhatsApp button

Persistent across all pages → opens WhatsApp for 0333 4105708 with pre-filled
message: "Hello FJ Production, I would like to learn more about your skincare products."

### Navigation & footer

Sticky modern navigation: Home, Shop, Categories, About, Contact +
prominent "Order on WhatsApp" button + mobile hamburger menu.

Footer: FJ Production, Premium Beauty & Skincare Products,
WhatsApp 0333 4105708, address, links: Home, Shop, About, Contact,
WhatsApp Order, Google Business Profile.

### Responsiveness & quality

Fully responsive (Android, iPhone, tablets, laptops, desktop), touch-friendly
buttons, flawless WhatsApp ordering, fast loading, lightweight structure,
SEO optimization (title: "FJ Production | Premium Beauty & Skincare Products",
meta description and keywords as provided), accessibility, lazy loading,
simple admin panel (add/edit/delete products, upload images, manage
categories, enable/disable, update prices).

### Final rules

1. FJ Production sells only beauty and skincare products.
2. Use only owner-provided images.
3. Use only owner-provided prices.
4. Never invent product data.
5. No fake reviews or testimonials.
6. No false certifications or medical claims.
7. No online payment systems.
8. All orders must go through WhatsApp only (0333 4105708).
9. Maintain a premium, professional design standard.
10. Ensure full responsiveness and usability.
11. Keep product management simple and reliable.

Deliver a fully polished, production-ready e-commerce website with complete
functionality, refined design, and professional user experience.
