# Project Breakdown: Mars Bansiti Portfolio Website

**Repository:** Marsbansiti/marsbansiti.github.io  
**Type:** Portfolio/Personal Website  
**Language:** HTML (100%)  
**Created:** April 2, 2026  
**Current Status:** Active  
**Live Site:** https://marsbansiti.github.io

---

## 📋 Executive Summary

A sophisticated, full-featured architectural visualization artist portfolio website built with pure HTML and vanilla JavaScript. The site showcases **28 architectural projects** across Vietnam and the Netherlands, with multilingual support (English & Vietnamese), advanced animations, and interactive project filtering.

---

## 🏗️ Architecture & Technical Stack

### Core Technology
- **Language:** HTML5 with embedded CSS3 & Vanilla JavaScript (No frameworks)
- **File Structure:** Single-file monolithic application (79.4 KB)
- **Rendering:** Client-side only
- **Browser Compatibility:** Modern browsers with ES6+ support

### Key Technical Features
1. **Page System:** Custom page routing (Home, Projects, About)
2. **Smooth Navigation:** SPA-like transitions with CSS animations
3. **Modal System:** Project detail modals with image galleries
4. **Drag Functionality:** Horizontal reel scrolling with mouse drag
5. **Language Toggle:** Bilingual interface (EN/VN)
6. **Responsive Design:** Mobile-first with breakpoints at 1100px, 768px, 480px
7. **Custom Cursor:** Interactive hover-state cursor styling
8. **Intersection Observer:** Lazy reveal animations on scroll

---

## 📁 Content Structure

### 1. **Navigation System**
- **Fixed Header Navigation** with:
  - Logo/Brand ("Mars.Bansiti")
  - Three main page links (Home, Projects, About)
  - Language toggle button (EN/VI)
  - Custom cursor visibility control

### 2. **Home Page** (Landing & Content Hub)
Vertical scrolling page with multiple sections:

#### Scene 1 - Hero Section
- Full-viewport hero with background image
- Giant typographic "PORTFOLIO" text (ghost bleed effect)
- Animated headline and subtitle entrance animations
- Geographic coordinates (Amsterdam, NL)
- Project count stat (28 projects)
- Scroll-to-explore CTA
- Navigation dots for scene jumping

#### Scene 2 - Introduction
- Portrait image with gradient overlay
- Introductory text about Mars Bansiti as architect/ArchViz artist
- Brief professional summary

#### Scene 3 - Manifesto/Philosophy
- Large background image
- Bold manifesto text: "Architecture is materiality, structural clarity, and the poetics of light"
- Signature section
- Scroll indicator to content below

#### Index Reel (Below Scenes)
- Horizontal scrollable carousel of 28 featured projects
- Hover reveals project info overlay
- Drag-to-scroll functionality
- Bilingual project names

#### Home Feature Section
- Two-column layout (text + image grid)
- Design philosophy headline
- Featured project images (3-image grid with different aspect ratios)
- CTA to view all projects

#### Disciplines Section
- Three-column grid showcasing expertise areas:
  1. Architectural Visualization
  2. Market Narrative Strategy
  3. Tropical & Dutch Expertise

#### Marquee Bar
- Animated scrolling text with keywords and project locations
- Gold accent bar with rotating key terms

---

### 3. **Projects Page**
Filterable grid portfolio layout

#### Header Section
- Page title: "Selected Works"
- Project count: 28

#### Filter Bar (Sticky)
- Buttons for filtering by:
  - All (default)
  - Vietnam
  - Netherlands
  - Ho Chi Minh City
  - Da Nang
  - Amsterdam

#### Project Grid
- 3-column responsive grid (changes to 2 columns at 768px, 1 column at 480px)
- Masonry-style layout with some items spanning 2 columns (wider)
- Hover effects: image zoom + brightness filter + info overlay
- Project metadata shown on hover:
  - Index number (001-028)
  - Project name
  - Location
  - Tools used (tags)

#### Modal/Detail View
- Triggered by clicking project tile
- Contains:
  - Project title
  - Project index
  - Location metadata
  - Studio attribution
  - Tools/software used
  - Detailed description (English/Vietnamese)
  - Gallery of 4-6 project images in masonry grid

---

### 4. **About Page**
Professional profile & background

#### Hero Section (Split Layout)
- **Left:** Large portrait image with decorative gold corner frame accents
- **Right:** Name, title, stats, tagline
  - Name: "Mars Bansiti" (large display typography)
  - Title: "Lead 3D Artist & Architectural Visualization Specialist"
  - Stats: 5+ Years International, 28 Projects, 4 Countries

#### Three-Column Content Section

**Column 1: Profile**
- Bio paragraph highlighting experience
- Professional quote: *"Every render is a decision about what to feel — not just what to see."*
- Contact section with email and message CTA

**Column 2: Experience Timeline**
Six positions chronologically listed:
1. **Fjord Arkitekter Studio** (Dec 2024 – Feb 2026) - 3D Artist / ArchViz Specialist
2. **Nordic Civic Architects** (Apr 2023 – Sep 2024) - 3D Artist / Architectural Visualizer
3. **Gardern Studio** (Nov 2021 – Mar 2023) - 3D Artist
4. **Nhà Xinh Design Studio** (Nov 2020 – Mar 2022) - 3D Artist
5. **Yuconvr Studio** (Nov 2019 – Aug 2020) - 3D Artist
6. **ArchWiz Studio** (May 2019 – Dec 2019) - Freelance 3D Artist

**Column 3: Skills & Education**

*Software Skills:*
- 3ds Max, SketchUp, AutoCAD, Corona Renderer, V-Ray, Photoshop, Forest Pack, RailClone, Fusion 360

*Expertise Areas:*
- Composition & Lighting
- Material Creation
- Retouching
- Tropical Architecture
- Dutch Housing
- Cinematic Rendering

*Education:*
- B.Arch from CEPT University (2017)
- Diploma in Architectural Visualization - SMEC Labs (2018)
- Masterclass in ArchViz - SOA Academy

#### Footer
- Copyright notice
- Software toolkit summary

---

## 🎨 Design System & Styling

### Color Palette
- **Background:** #08080A (dark navy-black)
- **Secondary BG:** #0D0D0F, #131315
- **Text Primary:** #EDE8DF (warm cream)
- **Text Dim:** rgba(237,232,223,0.5)
- **Text Muted:** rgba(237,232,223,0.22)
- **Accent Gold:** #C8A96E (primary call-to-action)
- **Gold Secondary:** #7A5E35 (secondary elements)
- **Border:** rgba(255,255,255,0.07) (subtle)

### Typography
- **Serif Font:** Cormorant Garamond (headings, body text)
- **Monospace:** Space Mono (UI, captions)
- **Display:** Bebas Neue (logo, large headlines)
- **Weights:** 200, 300, 400, 600, 700

### Animation Principles
- **Easing Function:** Custom cubic-bezier(.16,1,.3,1)
- **Page Transitions:** 550ms opacity + transform
- **Hover Effects:** 250-600ms smooth transitions
- **Reveal Animations:** Staggered fade-up on scroll
- **Marquee:** 30s infinite linear scroll
- **Ken Burns:** 20s infinite parallax on background images

---

## 📊 Project Database

### Total Projects: 28
Organized by geography:

#### Vietnam (21 projects)
- **Ho Chi Minh City (9):**
  - Terra Urban Residences
  - The K Residence
  - Sunlight Neo-Classical Villa
  - Layered Eco-Townhouse
  - Sky Garden Townhouse
  - The Interwoven Brick House
  - Prosperity Breeze Townhouse
  - Strata Frame Residences (split region)
  - *+ more*

- **Da Nang (9):**
  - Terracotta Veil House
  - Sunlit Garden House
  - Wind Vault House
  - Zen Light Townhouse
  - The Green Flow House
  - The Peaceful Retreat
  - Tropical Light Townhouse
  - Tropical Sunlight Townhouse
  - Tropical Terracotta House

- **Hoi An (1):**
  - Brick Vault House

#### Netherlands (7 projects)
- **Amsterdam:**
  - Strata Frame Residences
  - Het Veemhof Wonen

- **Other Dutch Cities:**
  - Forest Edge Living Zeist (Zeist)
  - Courtyard of the Timber District (Haarlem)
  - De Lindehof Residences (Amersfoort)
  - TRIÁS Havenkwartier Residences (Rotterdam)
  - De Lindehof Residences Utrecht (Utrecht)
  - De Waterweide Residences (Utrecht)
  - De Groene Erfwoningen (Amersfoort)

### Project Metadata Per Entry
Each project contains:
- Unique ID (1-28)
- Index number (001-028)
- English title
- Vietnamese title
- Location (city, country)
- Region/Subregion tags
- Studio attribution
- Tools/software used
- Thumbnail image
- Gallery images (4-6 images)
- English description
- Vietnamese description
- Wide/featured flag

---

## 🔧 JavaScript Functionality

### 1. **Language System**
```javascript
- toggleLang(): Switch between EN/VI
- applyLang(): Apply language data attributes to DOM
- Current language: 'vn' (Vietnamese default)
```

### 2. **Page Navigation**
```javascript
- showPage(name): Switch between home/projects/about
- Current page tracking: cp variable
- Smooth transitions with exit animations
```

### 3. **Scene Management** (Home Page)
```javascript
- goScene(n): Navigate to specific scene (0-2)
- nextScene() / prevScene(): Sequential navigation
- scrollBelow(): Jump below hero scenes
- Keyboard support: Arrow Up/Down
- Touch support: Swipe up/down
- Scroll synchronization: Auto-update scene dots
```

### 4. **Reel (Carousel)**
```javascript
- renderReel(): Generate horizontal project carousel
- initDrag(el): Enable mouse drag scrolling
- Drag events track mousedown/move/up
- Visual feedback: grab cursor on interaction
```

### 5. **Project Grid**
```javascript
- renderGrid(filter): Generate filterable grid
- Filter options: all, vietnam, netherlands, hcmc, danang, amsterdam
- Current filter tracking: cf variable
```

### 6. **Modal System**
```javascript
- openModal(id): Open project detail view
- closeModal(): Close modal
- Escape key support
- Scroll lock (body overflow:hidden)
- Gallery image loading (lazy)
```

### 7. **Custom Cursor**
```javascript
- Track mouse position globally
- Expand ring on interactive elements hover
- Apply easing to ring position
- Interactive elements: links, buttons, reels, grids, CTAs, arrows, navigation
```

### 8. **Reveal Animations**
```javascript
- initReveal(): Setup Intersection Observer
- .reveal elements fade up when 15% visible
- Runs on page load and page change
```

### 9. **Marquee Text**
```javascript
- Dynamic marquee items array (tools, locations, titles)
- Animated horizontal scroll (30s loop)
- Duplicate for seamless looping
```

---

## 📱 Responsive Breakpoints

### 1100px and below
- 2-column About grid layout changes to 2-col with last item spanning full width
- Home feature section becomes single column
- Hero portrait percentage adjustments

### 768px and below
- Navigation padding reduced
- All padding reduced from 52px to 24px
- Reel item width: 265px → 210px
- Disciplines: 3 columns → 1 column
- Projects grid: 3 columns → 2 columns
- About: Hero layout changes to vertical stacking
- About content: 3 columns → 1 column (stacked)
- Footer flex direction: row → column
- Modal gallery: 2 columns → 1 column

### 480px and below
- Projects grid: 2 columns → 1 column
- Large typography scaled down with clamp()
- Home feature padding further reduced
- Text sizing optimized for small screens

---

## 🎬 Animation & Interaction Timeline

### Page Load
1. Cursor elements initialize (hidden by default)
2. Reveal observer sets up
3. Reel carousel renders
4. Project data loads into memory
5. Language applied (Vietnamese default)
6. Hero animations trigger:
   - Golden eye (0.6s delay, fade-up)
   - Headline (0.6s delay, fade-up)
   - Subtitle (0.7s delay, fade-up)
   - Divider line (0.95s delay, fade-in)
   - Side stat (1s delay, fade-in)
   - Scroll CTA (1.1s delay, fade-in)
   - Coordinates (1.3s delay, fade-in)

### User Interactions
- **Hover on Interactive Elements:** Cursor ring expands (4px dot → 52px ring)
- **Scene Navigation:** Smooth scroll to scene top
- **Reel Drag:** Momentum-based horizontal scroll
- **Project Click:** Modal opens with fade-in
- **Modal Close:** Escape key or click backdrop
- **Language Toggle:** All text attributes swap + reel/grid re-render
- **Page Navigation:** 550ms cross-fade transition

---

## 📈 Performance Characteristics

### File Size
- **Total:** 79.4 KB (single HTML file)
- **CSS:** Embedded, minified within style tag
- **JavaScript:** Minified inline
- **No external dependencies** (fonts loaded from Google Fonts CDN)

### Optimization Features
- Lazy loading on images (`loading="lazy"`)
- CSS minification (compact selectors)
- JavaScript minification (compact variable names)
- Smooth scrolling (native `behavior:'smooth'`)
- Passive event listeners for scroll performance
- Efficient DOM queries and updates

---

## 🌐 Internationalization (i18n)

### Supported Languages
1. **English (EN)**
2. **Vietnamese (VN)** — Default

### Implementation
- Data attributes: `data-en` and `data-vn` on HTML elements
- Language toggle in navigation header
- Affects:
  - Navigation links
  - Section headings
  - Body copy
  - Button labels
  - Form labels
  - Modal content
  - All UI text

### Coverage
Approximately 80+ text elements translated bilingual

---

## 🔗 External Resources

### CDN Resources
1. **Google Fonts:**
   - Cormorant Garamond (serif)
   - Space Mono (monospace)
   - Bebas Neue (display)

2. **Image Hosting:**
   - iili.io image service for project thumbnails and gallery images

3. **Email Protection:**
   - Cloudflare email obfuscation (`/cdn-cgi/l/email-protection`)

---

## 📊 Data Structure

### Projects Array
Contains 28 project objects with structure:
```javascript
{
  id: Number,
  index: String (e.g., "001"),
  en: String (English title),
  vn: String (Vietnamese title),
  location: String,
  region: String (vietnam|netherlands),
  subregion: String (hcmc|danang|amsterdam|netherlands),
  studio: String,
  tools: String (tools/software),
  thumb: String (thumbnail image URL),
  images: Array<String> (gallery URLs),
  en_desc: String (English description),
  vn_desc: String (Vietnamese description),
  wide: Boolean (optional, 2-column span)
}
```

---

## 🎯 Key Features Summary

| Feature | Status | Details |
|---------|--------|---------|
| Multilingual | ✅ | EN/VN toggle |
| Responsive | ✅ | 3 breakpoints |
| Dark Theme | ✅ | Sophisticated dark palette |
| Animations | ✅ | Staggered, smooth, easing |
| Project Filter | ✅ | 6 filter options |
| Modal Gallery | ✅ | Image-heavy detail view |
| Custom Cursor | ✅ | Interactive ring + dot |
| Drag Interaction | ✅ | Reel horizontal scroll |
| Mobile Touch | ✅ | Swipe scene navigation |
| Keyboard Nav | ✅ | Arrow keys, Escape |
| Lazy Loading | ✅ | Images load on demand |
| SEO Meta | ⚠️ | Basic (title, charset, viewport) |

---

## 🚀 Future Enhancement Opportunities

1. **Performance:**
   - Convert to static site generator for better optimization
   - Implement image optimization/WebP format
   - Consider Service Worker for offline support

2. **Features:**
   - Project search functionality
   - Client testimonials section
   - Contact form integration
   - Blog/case study articles

3. **Accessibility:**
   - ARIA labels for interactive elements
   - Better keyboard navigation
   - Screen reader optimization
   - Color contrast verification

4. **SEO:**
   - Meta descriptions per page
   - Open Graph tags
   - Structured data (JSON-LD)
   - Sitemap

5. **Analytics:**
   - Integration with Google Analytics
   - Heatmap tracking
   - Conversion tracking

---

## 📝 Project Metadata

- **Repository:** marsbansiti/marsbansiti.github.io
- **Repo ID:** 1198294148
- **Language:** HTML (100%)
- **Size:** 196 KB (uncompressed)
- **Visibility:** Public
- **Last Updated:** April 2, 2026
- **Created:** April 1, 2026
- **Owner:** Marsbansiti (User ID: 194808391)

---

**Document Generated:** April 25, 2026  
**Portfolio Status:** Active & Maintained
