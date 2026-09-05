# La Taverna Lagos — Visual Asset Research & Inventory

**Project:** La Taverna Lagos Sales Demo  
**Location:** 48 Balarabe Musa Crescent, Victoria Island, Lagos, Nigeria  
**Instagram:** [@la_taverna_lagos](https://www.instagram.com/la_taverna_lagos)  
**Date of Audit & Pass:** September 2026  

---

## 1. Executive Summary

A dedicated visual-asset research pass was conducted to identify, verify, organize, and integrate authentic imagery of **La Taverna Lagos** into the production demo. All generic stock placeholders (including previous Unsplash images and event party stock) have been eliminated from the website.

- **Total Authentic Files Collected & Verified:** 19 local files across food, exterior, interior, events, and gallery.
- **High-Resolution Anchor Images:** Sourced from Niibow platform CDN (direct S3 storage for verified restaurant listing ID 1198) with resolutions up to **1170×1559px**.
- **Authentic Culinary & Ambience Images:** Sourced from verified Lagos culinary publication archives (ViewLagos May 2024 editorial feature).
- **Non-La Taverna Images Discarded:** `viewlagos-4812.jpg` depicting "Ki Bar & Kitchen" was identified during manual inspection and strictly excluded.
- **Unsplash Imagery Status:** **0% remaining** (100% replaced across Hero, Story, Food Grid, Signatures, Spaces, Wine, Events, Gallery, Social, and Reservation).

---

## 2. Directory Structure

All visual assets have been organized into the required project structure:

```
assets/la-taverna/
├── hero/
│   └── hero-courtyard.jpeg              (806 KB, 1170x1559px)
├── food/
│   ├── chicken-fettuccine-pasta.jpeg    (398 KB, 1170x1460px)
│   ├── signature-tapas-pasta-spread.jpeg (361 KB, 1170x1447px)
│   ├── wood-fired-pizza.jpeg            (517 KB, 1170x1444px)
│   ├── seafood-paella-authentic.jpg     (38 KB, 190x136px / web scaled)
│   ├── grilled-red-snapper-seafood.jpg  (51 KB, 190x136px / web scaled)
│   ├── tapas-starter-platter.jpg        (47 KB, 190x136px / web scaled)
│   ├── rosemary-lamb-chops.jpg          (35 KB, 190x136px / web scaled)
│   ├── chocolate-drizzle-dessert-pizza.jpg (41 KB, 190x136px / web scaled)
│   ├── artisan-pizzas-pairing.jpg       (40 KB)
│   ├── braised-beef-vegetables.jpg      (29 KB)
│   ├── ceviche-clay-bowl-tapas.jpg      (29 KB)
│   ├── dining-table-spread.jpg          (44 KB)
│   └── pork-belly-carrots-puree.jpg     (48 KB)
├── exterior/
│   ├── courtyard-pergola-entrance.jpeg  (806 KB, 1170x1559px)
│   ├── courtyard-dining-tables.jpeg     (810 KB, 1170x1545px)
│   ├── courtyard-tree-mural.jpeg        (898 KB, 1170x1550px)
│   ├── courtyard-night-fairy-lights.jpg (45 KB, 190x136px / web scaled)
│   └── exterior-building-daylight.jpg   (55 KB, 190x136px / web scaled)
├── events/
│   └── staff-hospitality-event.jpeg     (120 KB, 1060x774px)
├── gallery/
│   └── [All high-res and editorial captures stored as master references]
├── drinks/
├── logo/
└── menu/
```

---

## 3. Comprehensive Image Inventory & Source Provenance

| Asset Path | Depiction / Subject | Source & Provenance | Date / Resolution | First/Third Party | Site Usage |
|---|---|---|---|---|---|
| `assets/la-taverna/hero/hero-courtyard.jpeg` | Lush courtyard entrance framed by iron gate, flowering bougainvillea and vine pergola looking onto red building | Niibow Verified Listing #1198 CDN | 2024–2026<br>1170×1559px | Third-party verified directory asset | **Hero Section Background** & `<link rel="preload">` |
| `assets/la-taverna/exterior/courtyard-tree-mural.jpeg` | Courtyard circular raised planter tree with fairy light filaments, red walls and prominent Frida Kahlo portrait mural | Niibow Verified Listing #1198 CDN | 2024–2026<br>1170×1550px | Third-party verified directory asset | **Section 01 (Intro) Column** |
| `assets/la-taverna/food/signature-tapas-pasta-spread.jpeg` | Wooden table spread: handmade tomato fettuccine, fresh pizza slice, three octopus/seafood tacos on blue plate, house chili dipping oil | Niibow Verified Listing #1198 CDN | 2024–2026<br>1170×1447px | Third-party verified directory asset | **Section 02 (Story) Main Image** & **Social Grid** |
| `assets/la-taverna/food/chicken-fettuccine-pasta.jpeg` | Handcrafted pasta with tender chicken, creamy tomato emulsion, fresh rosemary sprig and grated parmesan on white tablecloth | Niibow Verified Listing #1198 CDN | 2024–2026<br>1170×1460px | Third-party verified directory asset | **Section 03 (Food Grid Main)** & **Gallery** & **Social Grid** |
| `assets/la-taverna/food/wood-fired-pizza.jpeg` | Full round stone-baked pizza topped with sliced chilies, roasted chicken, melted mozzarella and golden bubbly blistered crust | Niibow Verified Listing #1198 CDN | 2024–2026<br>1170×1444px | Third-party verified directory asset | **Signatures: Pizza**, **Gallery**, **Social Grid** |
| `assets/la-taverna/food/seafood-paella-authentic.jpg` | Traditional Spanish paella in wide pan loaded with saffron rice, king prawns, black mussels and tender calamari | ViewLagos Editorial Archive (IMG_4806) | May 2024 editorial review | Third-party food critic archive | **Section 03 Strip (Paella)**, **Signatures**, **Gallery** |
| `assets/la-taverna/food/grilled-red-snapper-seafood.jpg` | Whole grilled red snapper coated in tomato-bell pepper salsa with roasted plantain cuts on ceramic platter | ViewLagos Editorial Archive (IMG_4801) | May 2024 editorial review | Third-party food critic archive | **Food Grid (Garden & Sea)**, **Signatures: Seafood**, **Gallery** |
| `assets/la-taverna/food/tapas-starter-platter.jpg` | Spanish tapas selection on slate board: fried plantain batons, crispy empanadas, dipping aioli and red chili relish | ViewLagos Editorial Archive (IMG_4800) | May 2024 editorial review | Third-party food critic archive | **Signatures: Tapas**, **Gallery** |
| `assets/la-taverna/food/rosemary-lamb-chops.jpg` | Braised lamb chops / beef cuts with herb rosemary sprig and roast potato wedges | ViewLagos Editorial Archive (IMG_4804) | May 2024 editorial review | Third-party food critic archive | **Food Grid (From the kitchen)** |
| `assets/la-taverna/food/chocolate-drizzle-dessert-pizza.jpg` | Artisan sweet dessert pizza with criss-cross chocolate drizzle on dining table | ViewLagos Editorial Archive (IMG_4807) | May 2024 editorial review | Third-party food critic archive | **Signatures: Desserts**, **Gallery** |
| `assets/la-taverna/exterior/courtyard-dining-tables.jpeg` | Courtyard al fresco tables dressed in red-and-white checkered cloths, palm plants and overhead fairy bulb canopy | Niibow Verified Listing #1198 CDN | 2024–2026<br>1170×1545px | Third-party verified directory asset | **Spaces: The Courtyard**, **Events Section Image** |
| `assets/la-taverna/exterior/courtyard-night-fairy-lights.jpg` | Evening view of courtyard garden with glowing hanging string bulbs and intimate tree canopy lighting | ViewLagos Editorial Archive (IMG_4808) | May 2024 editorial review | Third-party food critic archive | **Spaces: Night Terrace**, **Reservation Background**, **Gallery** |
| `assets/la-taverna/exterior/exterior-building-daylight.jpg` | Daylight exterior of La Taverna's Mediterranean red stucco building with arched window and courtyard seating | ViewLagos Editorial Archive (IMG_4803) | May 2024 editorial review | Third-party food critic archive | **Spaces: The Setting**, **Gallery** |
| `assets/la-taverna/events/staff-hospitality-event.jpeg` | Staff hostess in La Taverna uniform presenting tequila tasting tray and cocktail promotion inside the restaurant | Niibow Verified Listing #1198 CDN | 2024–2026<br>1060×774px | Third-party verified directory asset | **Wine Section Aside Image**, **Wine Background**, **Gallery** |

---

## 4. Website Deployment & Layout Preservation

All images were deployed into index.html with strict adherence to design constraints:
1. **Zero Layout Shifts / Distortion:** Aspect ratios and `object-fit: cover` with custom center positioning were applied to preserve natural proportions.
2. **Editorial Typography Intact:** Cormorant Garamond headings and DM Sans body typography remain untouched.
3. **Interactive Features Tested:**
   - Hero breathe animation functions with local authentic asset.
   - Lightbox opens authentic images dynamically upon clicking any gallery item.
   - Gallery category filter (`All`, `Food`, `Space`, `Nights`) seamlessly toggles authentic items.
   - Performance preloading applied to the primary authentic hero asset.
