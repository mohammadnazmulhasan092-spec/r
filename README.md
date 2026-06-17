# Dadar Shop 🛍️
**Your Trusted Online Marketplace**

## ✅ এই ফাইলগুলো GitHub-এ আপলোড করুন

**সব ফাইল সরাসরি root-এ আছে — কোনো subfolder নেই।**
প্রতিটি HTML ফাইলে CSS এবং JS সম্পূর্ণ inline embedded।

---

## 🚀 GitHub-এ Upload করার নিয়ম

### Method 1: GitHub Website (Drag & Drop)
1. GitHub.com → New repository → `dadar-shop`
2. "uploading an existing file" click করুন
3. **সব ফাইল একসাথে** drag করে ছেড়ে দিন
4. "Commit changes" click করুন
5. Settings → Pages → Branch: main → Save

### Method 2: Git Command Line
```bash
git init
git add .
git commit -m "Dadar Shop - Production Build"
git branch -M main
git remote add origin https://github.com/USERNAME/dadar-shop.git
git push -u origin main
```

---

## 🌐 Cloudflare-এ Deploy

**Cloudflare Pages:**
1. pages.cloudflare.com → Create project → Connect to Git
2. Build command: (empty)
3. Output directory: /
4. Save and Deploy ✅

---

## 📁 ফাইল তালিকা (সব root-এ, কোনো folder নেই)

| ফাইল | বিবরণ |
|------|--------|
| `index.html` | হোম পেজ |
| `product.html` | পণ্যের বিবরণ |
| `category.html` | ক্যাটাগরি পেজ |
| `categories.html` | সব ক্যাটাগরি |
| `cart.html` | কার্ট |
| `checkout.html` | চেকআউট |
| `wishlist.html` | উইশলিস্ট |
| `search.html` | সার্চ রেজাল্ট |
| `account.html` | অ্যাকাউন্ট |
| `orders.html` | অর্ডার হিস্ট্রি |
| `login.html` | লগইন |
| `register.html` | রেজিস্ট্রেশন |
| `blog.html` | ব্লগ |
| `blog-post.html` | ব্লগ পোস্ট |
| `about.html` | আমাদের সম্পর্কে |
| `contact.html` | যোগাযোগ |
| `help.html` | সাহায্য কেন্দ্র |
| `tracking.html` | অর্ডার ট্র্যাকিং |
| `seller.html` | বিক্রেতা পোর্টাল |
| `404.html` | পেজ না পাওয়া |
| `_headers` | Cloudflare MIME fix |
| `_redirects` | Cloudflare routing |
| `robots.txt` | SEO |
| `sitemap.xml` | SEO sitemap |

© 2025 Dadar Shop. All Rights Reserved.
