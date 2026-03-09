# 🌿 PraQRti — Plant Information System

> **PraQRti** = *Pra* (before/primordial) + *QR* (QR Code) + *ti* — a play on **Prakriti** (Sanskrit: Nature)

A QR-code-powered plant information website for the **Hansraj College** campus. Scan a QR code attached to any tree or plant on campus and instantly access its species name, uses, cultural history, and plantation guide — right in your browser, no app required.

---

## 🔗 Live Site

[https://praqrti.github.io/PraQrti.github.io](https://praqrti.github.io/PraQrti.github.io)

---

## 📋 Pages

| Page | File | Description |
|---|---|---|
| **Home** | `index.html` | Landing page with welcome hero, principal quote, team section, and About Us |
| **Garden** | `garden.html` | Image card catalog of all 45 campus plants with live search |
| **Media** | `media.html` | Media and resources |
| **Feedback** | `feedback.html` | Star-rating feedback form (submitted to Google Sheets) |
| **Plant pages** | `<PlantName>.html` | One page per species (45 total) with uses, cultural importance, and plantation info |

---

## 🌱 Plant Catalog (45 species)

| | | | |
|---|---|---|---|
| Alstonia scholaris | Azadirachta indica | Bougainvillea | Calendula officinalis |
| Caryota urens | Casia auriculata | Cassia fistula | Casuarina equisetifolia |
| Chlorophytum comosum | Cinereria maritima | Clerodendrum inerme | Codiaeum variegatum |
| Cotton plant | Cycas | Dianthus | Dracaena trifasciata |
| Dragon dracaena | Eucalyptus globulus | Ficus | Ficus benjamina |
| Ficus microcarpa | Ficus racemosa | Ficus religiosa | Frangipani |
| Hamelia patens | Hibiscus | Hymenocallis littoralis | Hyophorbe lagenicaulis |
| Lantana camara | Livistona chinensis | Magnolia champaca | Mangifera indica |
| Millettia pinnata | Mimusops elengi | Mitragyna parviflora | Monoon longifolium |
| Petunia | Prosopis juliflora | Psidium guajava | Salvia plant |
| Syzygium cumini | Tecoma stans | Thuja orientalis | Tropaeolum majus |
| Yucca plant | | | |

---

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|---|---|---|
| HTML5 | — | All page structure |
| CSS3 | — | Custom styling (`Trees_files/c1–c6.css`) |
| Bootstrap | 5.3.0-alpha3 | Responsive grid, navbar, utilities |
| Google Fonts | — | Roboto Condensed, Kanit, Signika |
| jQuery | 3.5.1 | AJAX form submission |
| Google Apps Script | — | Feedback form backend (Google Sheets) |

No build tools, bundlers, or frameworks — pure HTML/CSS/JS, deployable directly via GitHub Pages.

---

## 📁 Project Structure

```
PraQrti.github.io/
│
├── index.html                  # Home page
├── garden.html                 # Plant catalog grid
├── media.html                  # Media page
├── feedback.html               # Feedback form
│
├── <PlantName>.html            # 45 individual plant pages
│   ├── Hibiscus.html
│   ├── Ficus religiosa.html
│   └── ... (43 more)
│
├── Trees_files/
│   ├── c1.css                  # Plant detail pages styles
│   ├── c2.css                  # Home page styles
│   ├── c3.css                  # Garden page styles
│   ├── c4.css                  # Feedback page styles
│   ├── c5.css                  # Alt plant page styles (Mitragyna etc.)
│   ├── c6.css                  # Media page styles
│   │
│   ├── campus.jpg              # College campus photo (index.html body bg only)
│   ├── home.jpg                # Nature background (index hero section, feedback bg)
│   ├── garden.jpg              # Garden background (garden page)
│   ├── treebg.jpg              # Tree background (alt plant pages)
│   ├── 699.jpg                 # Foliage background (About Us section)
│   ├── rama.jpg                # Principal photo
│   ├── PraQRti_logo_1-transformed.jpg  # Site logo
│   │
│   ├── <PlantName>.jpg/.jpeg   # Plant photos (one per species)
│   └── gps/                    # GPS data assets
│
└── Team_files/
    ├── WebDeveloper/           # Team member photos
    └── InformationProvider/    # Team member photos
```

---

## 🚀 Running Locally

No build step required. Just open any `.html` file directly in a browser:

```bash
# Option 1 — open directly
start index.html

# Option 2 — serve with VS Code Live Server extension
# Right-click index.html → "Open with Live Server"

# Option 3 — Python simple server
python -m http.server 8000
# Then open http://localhost:8000
```

> **Note:** The feedback form submits to a Google Apps Script endpoint. It works from any origin, including `localhost`.

---

## ✨ Features

- **QR-linked plant pages** — each physical plant on campus has a QR code linking directly to its page
- **Live search** on the Garden page — filters all 45 plant cards instantly by name
- **Image card grid** on Garden page with hover effects
- **Star-rating feedback form** — inline success/error messages, no alert popups
- **Scroll-to-top button** — appears on all pages after scrolling 300px
- **Active nav highlighting** — current page is highlighted in the navbar automatically
- **Mobile responsive** — custom media queries on all pages, iOS `background-attachment` fix
- **Lazy image loading** — all plant images use `loading="lazy"` for fast initial page load
- **No app required** — works in any mobile browser via QR scan

---

## 👥 Team

**Supervisor / Principal**
- Prof. (Dr.) Rama — Principal, Hansraj College

**Teachers**
- Suyash Kumar — Assistant Professor, Department of Computer Science
- Mahaswetta Saikia — Associate Professor, Department of Botany

**Web Developers** *(B.Sc. Hons Computer Science, 2021–2024)*
- Muhammad Husnain A
- Abhinav Praveesh
- Arun Chandra
- Ramavath Bhanu Prasad
- Ankit Kanojiya
- Tanisha Kriplani
- Ashish Shah
- Nitin Dhiman
- Kunusoth Devender

**Information Providers** *(B.Sc. Hons Botany, 2021–2024)*
- Anjay Sanilkumar
- Siham
- Jasaraj Loktongbam
- Gagandeep Singh
- Priyanka Kumari
- Tanya Singh
- Kabir Khanna
- Aanchal
- Ashish Tiwari

---

## 📄 License

© 2023 Hansraj College. All rights reserved.
