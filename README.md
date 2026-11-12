<div align="center">

# 🔵 NEWHINDIMOVIES WAPKA

### HD MOVIES • WEB SERIES

**A clean, responsive and mobile-first Wapka movie catalogue theme**

<br>

[![Wapka](https://img.shields.io/badge/Platform-Wapka-0A84FF?style=for-the-badge)](#)
[![Responsive](https://img.shields.io/badge/UI-Responsive-0A84FF?style=for-the-badge)](#)
[![Mobile First](https://img.shields.io/badge/Design-Mobile--First-18A558?style=for-the-badge)](#)
[![License](https://img.shields.io/badge/License-MIT-18A558?style=for-the-badge)](LICENSE)

</div>

---

## 🔷 About

**NEWHINDIMOVIES WAPKA** is a mobile-first Wapka movie catalogue theme focused on a clean **blue + white** interface, responsive movie cards, category navigation and a smooth browsing experience.

The theme is designed around the existing Wapka logic and keeps the important Wapka variables and listing systems intact.

> **Theme style:** Royal Blue / White  
> **Primary:** `#0A84FF`  
> **Accent:** `#18A558`

---

## ✨ Features

| Feature | Details |
|---|---|
| 🔥 Trending | Top 5 most-viewed movies |
| 🎞️ Featured Movies | 2 featured movies |
| 🏷️ Quality | Uses existing `VAR(q)` |
| 🆕 Latest Releases | 20 movies per page |
| 🔢 Pagination | Page numbers + navigation |
| 📂 Categories | Category & sub-category support |
| 🔎 Search | Existing Wapka search logic |
| 📱 Mobile UI | Mobile-first responsive layout |
| 🖥️ Desktop UI | Responsive desktop grid |
| ⬇️ Downloads | Existing Wapka download URL logic |
| ⚡ Slider | 16:9 trending banner with 6-second auto-scroll |

---

## 🔥 Trending — Most Viewed

The homepage includes a **Trending / Most Viewed** banner.

### Configuration

- Top **5** movies
- Uses Wapka File Lister
- Most-viewed sorting
- **16:9** responsive banner
- Horizontal touch scrolling
- Automatic next-slide every **6 seconds**
- Continuous looping
- Existing movie/download links are preserved

---

## ⭐ Featured Movies

The Featured Movies section displays exactly **2 movies**.

Quality is taken dynamically from the existing Wapka variable:

```text
{{VAR(q)}}
```

No hard-coded quality value is required.

---

## 🆕 Latest Releases

Latest Releases is configured for:

```text
20 movies / page
```

Pagination:

```text
1  2  3  4  5  ...  Next
```

The existing Wapka File Lister and pagination logic are preserved.

---

## 📂 Categories & Sub-Categories

The theme supports:

- Main categories
- Sub-categories
- Category movie listings
- Category pagination
- Category breadcrumbs

The **Browse Categories** heading is displayed only once instead of repeating for every category item.

---

## 🎨 UI Design

The visual language follows a clean blue-and-white fintech-style interface:

```text
Primary Blue   #0A84FF
Accent Green   #18A558
White          #FFFFFF
```

### Design goals

- Clean cards
- Rounded corners
- Responsive spacing
- Touch-friendly controls
- Mobile-first layout
- Minimal visual clutter
- No unnecessary horizontal overflow

---

## 🧩 Wapka Variables Preserved

The theme keeps the existing Wapka variables used by the project, including:

```text
%name%
%id%
%thumb%
%filenum%
%q%
{{VAR(q)}}
{{GET(page)}}
{{PAGING(...)}} 
```

These variables should be used only in their supported Wapka contexts.

---

## 📁 Project Structure

```text
NEWHINDIMOVIES-WAPKA/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── docs/
│   └── SETUP.md
│
└── theme/
    └── NEWHINDIMOVIES_WAPKA_THEME.json
```

---


---

## 🌐 Demo Website

<div align="center">

### NEWHINDIMOVIES — Theme Preview

<img src="https://i.postimg.cc/HTn7X7qc/Screenshot-20261112-124713.jpg" alt="NEWHINDIMOVIES Wapka Theme Demo" width="900">

<br><br>

**Mobile-first Wapka movie catalogue interface preview**

</div>

---

## 🚀 Installation

### 1. Download the project

Download or clone this repository.

### 2. Open the theme folder

Go to:

```text
theme/
```

### 3. Import the Wapka theme

Use:

```text
NEWHINDIMOVIES_WAPKA_THEME.json
```

as the primary Wapka theme/configuration file.

### 4. Test before publishing

Check:

- Homepage
- Trending slider
- Featured Movies
- Latest Releases
- Pagination
- Categories
- Sub-categories
- Search
- Download pages
- Mobile layout
- Desktop layout

---

## 📱 Responsive Layout

### Mobile

```text
┌─────────────────────────┐
│      NEWHINDIMOVIES     │
├─────────────────────────┤
│   🔥 TRENDING 16:9      │
├─────────────────────────┤
│  FEATURED   FEATURED    │
├─────────────────────────┤
│  MOVIE  │  MOVIE        │
│  MOVIE  │  MOVIE        │
│  MOVIE  │  MOVIE        │
├─────────────────────────┤
│      PAGINATION         │
├─────────────────────────┤
│   BROWSE CATEGORIES     │
└─────────────────────────┘
```

---

## 🛠️ Customization

You can customize:

- Branding
- Logo
- Site title
- Colors
- Banner
- Category names
- Footer text
- Navigation labels

When modifying the theme, keep the existing Wapka variables and File/Folder Lister logic intact.

---

## ⚠️ Important

This repository contains the **theme, interface and configuration**, not copyrighted movie/video files.

Only publish, link to or distribute movies, videos and other content that you are legally authorized to distribute.

Do not remove or bypass copyright, DRM, access controls or platform restrictions.

---

## 📄 License

This project is released under the **MIT License**.

See [LICENSE](LICENSE) for details.

---

<div align="center">

### 🔵 NEWHINDIMOVIES

**HD MOVIES • WEB SERIES**

Made for a clean, fast and mobile-first Wapka experience.

</div>
