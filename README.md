# WP Broken Assets Scanner & Fixer

WP Broken Assets Scanner & Fixer is a lightweight WordPress plugin that scans your website content and detects broken links, image URLs in posts, pages, and custom post types.

It helps site owners quickly identify and fix broken links, images urls that can hurt SEO, user experience, and site credibility.

---

## 🚀 Features

- Scan **posts, pages, and custom post types**
- Detect broken links, image URLs using HTTP status checks
- AJAX-powered scan (no page reload)
- Persistent scan results
- Clickable post titles (open in new tab)
- Clickable broken URLs (open in new tab)
- Clean admin table with result count
- Displays clear message when no broken assets are found
- Lightweight and fast (no external libraries)

---

## 📸 How It Works

1. Go to **WordPress Admin → Broken Assets Scanner**
2. Click **Scan for Broken Assets**
3. The plugin scans all published content
4. Results are displayed in a table:
   - Post title
   - Broken URL
5. Fix broken urls directly from the source content

---

## 🧩 Supported Content Types

- Posts
- Pages
- Custom Post Types (public & published)

---

## 🔧 Installation

1. Download or clone this repository
2. Upload the folder to `/wp-content/plugins/`
3. Activate **WP Broken Assets Scanner & Fixer** from the Plugins menu
4. Start scanning 🚀

---

## ⚠️ Notes

- The plugin checks broken links, image URLs using `wp_remote_head()`
- Images blocked by firewalls or protected servers may appear as broken
- Best used on staging or during low-traffic periods for large sites

---

## 🛠️ Future Improvements (Planned)

- Auto-fix broken assets
- Replace broken URLs
- Scheduled scans
- Export scan reports
- Media Library integration

---

## 📄 License

GPL v2 or later  
Free to use, modify, and distribute.

---

## 👨‍💻 Author

Developed by **Aminul Sarkar**  
WordPress & PHP Developer  
https://aminulsarkar.com
