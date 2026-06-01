# Phoenixtek Website — Project Memory
> Last updated: 2026-05-27

---

## 🏢 Company Info
- **Name:** Phoenixtek Solution
- **Founder:** Supratim Mondal (Founder & Chief Geotechnical Engineer)
- **Partner:** Alfresco Construction Services Pvt. Ltd. (alfresco-bestech.com)
- **Location:** Kolkata, West Bengal, India (Newtown, Diamond Harbour, PIN: 743331)
- **Phone/WhatsApp:** +91 97341 15880
- **Email:** phoenixteksoln@gmail.com
- **Website:** https://phoenixtek.in
- **LinkedIn:** https://www.linkedin.com/in/supratim-mondal9734115880/

---

## 🌐 Hosting & Tech Stack
- **Platform:** GitHub Pages (static HTML/CSS/JS)
- **Repo:** https://github.com/Callmesupratim/Phoenixtek-Website
- **Branch:** `main` (GitHub Pages serves from main)
- **CMS:** Google Sheets (public CSV via gviz/tq endpoint)
- **Domain:** phoenixtek.in (custom domain)
- **Analytics:** Google Analytics 4 — ID: `G-LQZZ7DFTHG`
- **Search Console:** Verified ✅ — sitemap.xml submitted ✅
- **Contact Form:** Formspree (`https://formspree.io/f/xnjrdqjv`)
- **Preview Server:** `npx serve -p 3000 .` (defined in `.claude/launch.json`)

---

## 📁 Key Files
| File | Purpose |
|------|---------|
| `index.html` | Main website (~3200+ lines) |
| `sitemap.xml` | SEO sitemap |
| `robots.txt` | SEO robots file |
| `logo.webp` | Nav logo (compressed 456KB → 18KB) |
| `images/supratim-mondal.webp` | Founder photo (300x300, 6KB) |
| `images/app-icon.webp` | Phoenixtek app icon (1024x1024) |
| `images/surveystar-icon.webp` | SurveyStar app icon (1024x1024) |
| `images/surveystar-blog-1.jpg` | SurveyStar blog image 1 |
| `images/surveystar-blog-2.jpg` | SurveyStar blog image 2 |
| `images/surveystar-blog-3.jpg` | SurveyStar blog image 3 |
| `images/*.webp` | 15 field photos (converted from JPG, avg 96% size reduction) |

---

## 📊 Google Sheets CMS
- **Spreadsheet ID:** (stored in `SPREADSHEET_ID` variable in index.html)
- **Tabs & Columns:**

| Tab | Columns |
|-----|---------|
| SERVICES | Title, Description, Icon |
| PROJECTS | Title, Description, Category, ImageURL |
| GALLERY | ImageURL, Caption |
| VIDEOS | Title, YouTubeURL, Description |
| BLOG | Date, Category, Title, Excerpt, Link, ImageURL |
| DOWNLOADS | Title, Description, FileType, FileSize, DownloadURL, IconURL |
| CONTACT | Field, Value |

---

## 🖼️ Image Rules (IMPORTANT)
| Source | Use for | Works as `<img>`? |
|--------|---------|-------------------|
| GitHub raw (`raw.githubusercontent.com`) | Blog, Portfolio, Gallery photos | ✅ YES |
| Unsplash URLs | Stock photos | ✅ YES |
| Local (`images/` folder) | Logos, icons, portraits | ✅ YES |
| Google Drive | Downloads only (PDF, APK) | ❌ NO (login required) |

> **Rule:** Never use Google Drive links for images displayed on the website.
> Google Drive works ONLY for downloadable files (brochures, APKs, etc.)

---

## 🤖 PhoenixBot (FAQ Chatbot)
- Built in pure JavaScript — no external service, free forever
- Located: bottom-right corner, above WhatsApp button
- **30 Q&A topics** covering all services, contact, projects, instruments, etc.
- **Smart handoff:** After 2 unanswered questions → routes to WhatsApp
- **Quick chips:** Our Services, Contact Us, Get a Quote, About Phoenixtek, Our Projects, Downloads, SHM, IoT Monitoring
- **Update schedule:** Weekly — tell Claude "Update PhoenixBot" after adding new content

---

## 💬 WhatsApp Button
- Number: `+91 97341 15880`
- Link: `https://wa.me/919734115880`
- Position: Fixed, bottom-right (`bottom: 2rem, right: 2rem`)

---

## 🎨 Brand Colors
```css
--primary:   #FF6B35  /* Orange */
--secondary: #F7931E  /* Amber */
--accent:    #00D9FF  /* Cyan */
--dark:      #1A1A2E  /* Navy */
--purple:    #9D4EDD
--green:     #06FFA5
```
- **Fonts:** Archivo Black (headings), DM Sans (body)

---

## 📈 Website Stats (shown on site)
- 50+ Projects Completed
- 10+ Years of Expertise
- 15+ States Served
- 100% Client Satisfaction

---

## 🏗️ Services (6 official services)
1. Geotechnical Instrumentation
2. Structural Health Monitoring (SHM)
3. Bridge Load Testing
4. Slope Stability Analysis
5. Vibration & Settlement Monitoring
6. Road Profiling & Traffic Monitoring

---

## 📱 Apps in Downloads Section
| App | Icon | Description |
|-----|------|-------------|
| SurveyStar | `images/surveystar-icon.webp` | GPS road survey Android app |
| Monitoring Software | `images/app-icon.webp` | Data acquisition software |

---

## 🔗 Social Links
- LinkedIn: https://www.linkedin.com/in/supratim-mondal9734115880/
- Email: phoenixteksoln@gmail.com
- (No Facebook — removed, no page exists)

---

## 📝 Blog Posts (as of 2026-05-27)
| Date | Category | Title |
|------|----------|-------|
| 21-05-2026 | SHM | Structural Health Monitoring: Engineering the Future... |
| 21-05-2026 | Our Journey | From Bridges to Smart Infrastructure... |
| 22-05-2026 | SHM | From Dial Gauges to LVDTs... |
| 23-05-2026 | ComputerVision | Building a Custom YOLOv8 Vehicle Detection System... |
| 25-05-2026 | Development | Building a Production-Ready ERP System from Scratch... |
| 27-05-2026 | Development | SurveyStar: The Smart Road Survey App... |

---

## ✅ SEO Setup
- Google Analytics 4: `G-SELNBT2D0L` ✅
- Google Search Console: Verified ✅
- sitemap.xml: Submitted & Success (1 page discovered) ✅
- robots.txt: Live ✅
- Schema.org LocalBusiness markup: ✅
- OG/Twitter meta tags: ✅

---

## ⚠️ Known Limitations
- **Static site** = no dynamic OG tags per blog post (LinkedIn shares show homepage preview)
- **Blog LinkedIn sharing:** Use `phoenixtek.in/#blog-[slug]` + write caption manually
- **Google Drive images:** Don't work for `<img>` — only for download links
- **PhoenixBot:** Pure FAQ bot — can't answer unexpected questions → falls back to WhatsApp

---

## 🔄 Weekly Tasks
- [ ] Update PhoenixBot Q&A if new services/info added
- [ ] Add new blog posts to Google Sheets (BLOG tab)
- [ ] Upload blog images to `images/` folder → push to GitHub → use raw.githubusercontent.com URL
- [ ] Check Google Analytics for traffic insights
- [ ] Check Google Search Console for search performance

---

## 📋 Pending / Future Ideas
- [ ] Add real Google Drive links for Brochure & Datasheets (when ready)
- [ ] Separate HTML pages per blog post (for better SEO + LinkedIn previews)
- [ ] Google Business Profile (for local SEO)
- [ ] Tawk.to live chat (if real-time chat with visitors needed)
