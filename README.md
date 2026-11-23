# Wallpapers CDN

A collection of **1516** web-optimized wallpapers (76 categories across 3 collections), ready for instant CDN delivery in any website or application.

---

## 📦 Collections Overview

| Collection | Categories | Wallpapers | Path Pattern |
|:---|:---:|:---:|:---|
| **Gradients** | 55 | 1003 | `gradients/{category}/{filename}` |
| **macOS** | 9 | 91 | `macos/{category}/{filename}` |
| **Nature** | 12 | 422 | `nature/{category}/{filename}` |
| **Total** | **76** | **1516** | |

---

## 🚀 CDN Usage

### 1. jsDelivr (Recommended)
```text
https://cdn.jsdelivr.net/gh/Jebrik12/wallpapers@main/{collection}/{category}/{filename}
```

**Examples:**
```html
<!-- Gradients -->
<img src="https://cdn.jsdelivr.net/gh/Jebrik12/wallpapers@main/gradients/3d-chrome/3d-chrome-01.jpg" alt="3D Chrome" />

<!-- macOS -->
<img src="https://cdn.jsdelivr.net/gh/Jebrik12/wallpapers@main/macos/mojave/desert-1.jpg" alt="Mojave Desert" />

<!-- Nature -->
<img src="https://cdn.jsdelivr.net/gh/Jebrik12/wallpapers@main/nature/mountains/0007.jpg" alt="Mountains" />
```

### 2. Statically CDN
```text
https://cdn.statically.io/gh/Jebrik12/wallpapers/main/{collection}/{category}/{filename}
```

### 3. API Manifest Access
You can fetch [`manifest.json`](manifest.json) directly to get all collections, categories, titles, and pre-built CDN URLs:
```javascript
const res = await fetch("https://cdn.jsdelivr.net/gh/Jebrik12/wallpapers@main/manifest.json");
const data = await res.json();

console.log(data.collections.gradients);
console.log(data.collections.macos);
console.log(data.collections.nature);
```

---

## 📁 Categories

### 🍏 macOS (9)
- **El Capitan** (`macos/el-capitan`) — 2 wallpapers
- **High Sierra** (`macos/high-sierra`) — 2 wallpapers
- **Lion** (`macos/lion`) — 19 wallpapers
- **Mavericks** (`macos/mavericks`) — 9 wallpapers
- **Mojave** (`macos/mojave`) — 30 wallpapers
- **Monterey** (`macos/monterey`) — 1 wallpapers
- **Mountain Lion** (`macos/mountain-lion`) — 17 wallpapers
- **Sierra** (`macos/sierra`) — 6 wallpapers
- **Yosemite** (`macos/yosemite`) — 5 wallpapers

### 🌲 Nature & Thematic (12)
- **City Architecture** (`nature/city-architecture`) — 45 wallpapers
- **Desert Dunes** (`nature/desert-dunes`) — 8 wallpapers
- **Flora Plants** (`nature/flora-plants`) — 3 wallpapers
- **Forest Trees** (`nature/forest-trees`) — 31 wallpapers
- **Lakes Waterfalls** (`nature/lakes-waterfalls`) — 41 wallpapers
- **Lifestyle Art** (`nature/lifestyle-art`) — 9 wallpapers
- **Mountains** (`nature/mountains`) — 119 wallpapers
- **Ocean Beach** (`nature/ocean-beach`) — 18 wallpapers
- **Sky Space** (`nature/sky-space`) — 47 wallpapers
- **Vehicles Aviation** (`nature/vehicles-aviation`) — 47 wallpapers
- **Wildlife Animals** (`nature/wildlife-animals`) — 33 wallpapers
- **Winter Snow** (`nature/winter-snow`) — 21 wallpapers

### 🎨 Gradients (55)
- **3D Chrome** (`gradients/3d-chrome`) — 15 wallpapers
- **3D Fluid Iridescent A** (`gradients/3d-fluid-iridescent-a`) — 14 wallpapers
- **3D Fluid Iridescent B** (`gradients/3d-fluid-iridescent-b`) — 8 wallpapers
- **3D Fluid Iridescent C** (`gradients/3d-fluid-iridescent-c`) — 11 wallpapers
- **3D Glass Wave** (`gradients/3d-glass-wave`) — 9 wallpapers
- **3D Liquid Metal** (`gradients/3d-liquid-metal`) — 23 wallpapers
- **Abstract Glow** (`gradients/abstract-glow`) — 13 wallpapers
- **Abstract Gradients** (`gradients/abstract-gradients`) — 21 wallpapers
- **Abstract Wave** (`gradients/abstract-wave`) — 15 wallpapers
- **Aurora Mist** (`gradients/aurora-mist`) — 14 wallpapers
- **Chill Ocean** (`gradients/chill-ocean`) — 22 wallpapers
- **Chromatic Waves** (`gradients/chromatic-waves`) — 24 wallpapers
- **Cobalt Glass** (`gradients/cobalt-glass`) — 8 wallpapers
- **Cosmic Glass** (`gradients/cosmic-glass`) — 17 wallpapers
- **Cosmic Horizon** (`gradients/cosmic-horizon`) — 6 wallpapers
- **Crimsonillium** (`gradients/crimsonillium`) — 19 wallpapers
- **Cyber Trails** (`gradients/cyber-trails`) — 7 wallpapers
- **Fluid Blurs** (`gradients/fluid-blurs`) — 33 wallpapers
- **Fractal Labyrinth A** (`gradients/fractal-labyrinth-a`) — 37 wallpapers
- **Fractal Labyrinth B** (`gradients/fractal-labyrinth-b`) — 12 wallpapers
- **Glossy Metallic Flows** (`gradients/glossy-metallic-flows`) — 16 wallpapers
- **Glowic Glass** (`gradients/glowic-glass`) — 26 wallpapers
- **Gradient Studio** (`gradients/gradient-studio`) — 48 wallpapers
- **Grainy Mesh** (`gradients/grainy-mesh`) — 31 wallpapers
- **Hero Wave Gradients** (`gradients/hero-wave-gradients`) — 44 wallpapers
- **Ios 18 Gradients** (`gradients/ios-18-gradients`) — 8 wallpapers
- **Iridescent Fluid** (`gradients/iridescent-fluid`) — 23 wallpapers
- **Iridescent Silk** (`gradients/iridescent-silk`) — 8 wallpapers
- **Light Leaks** (`gradients/light-leaks`) — 19 wallpapers
- **Liquid Glass** (`gradients/liquid-glass`) — 15 wallpapers
- **Liquid Iridescence** (`gradients/liquid-iridescence`) — 12 wallpapers
- **Luminous Grain** (`gradients/luminous-grain`) — 39 wallpapers
- **Lumishade** (`gradients/lumishade`) — 23 wallpapers
- **Metallic Flow** (`gradients/metallic-flow`) — 18 wallpapers
- **Metallic Fluid** (`gradients/metallic-fluid`) — 14 wallpapers
- **Mist Novax** (`gradients/mist-novax`) — 22 wallpapers
- **Moon** (`gradients/moon`) — 6 wallpapers
- **Motion Silk** (`gradients/motion-silk`) — 10 wallpapers
- **Neon Aura** (`gradients/neon-aura`) — 18 wallpapers
- **Novara** (`gradients/novara`) — 18 wallpapers
- **Novion** (`gradients/novion`) — 12 wallpapers
- **Obsidian Silk** (`gradients/obsidian-silk`) — 8 wallpapers
- **Ocean Flow** (`gradients/ocean-flow`) — 15 wallpapers
- **Painterly Texture** (`gradients/painterly-texture`) — 20 wallpapers
- **Painterly Texture B** (`gradients/painterly-texture-b`) — 21 wallpapers
- **Pink Fuchsia** (`gradients/pink-fuchsia`) — 16 wallpapers
- **Pixel Waves** (`gradients/pixel-waves`) — 9 wallpapers
- **Prism Soft** (`gradients/prism-soft`) — 14 wallpapers
- **Radiant Shutters** (`gradients/radiant-shutters`) — 7 wallpapers
- **Silky Smooth 3D** (`gradients/silky-smooth-3d`) — 11 wallpapers
- **Spectrum Flow** (`gradients/spectrum-flow`) — 46 wallpapers
- **Tangerine Orange** (`gradients/tangerine-orange`) — 18 wallpapers
- **Velvet Fog** (`gradients/velvet-fog`) — 15 wallpapers
- **Vivid Spectrum** (`gradients/vivid-spectrum`) — 25 wallpapers
- **Watercolor Whispers** (`gradients/watercolor-whispers`) — 20 wallpapers
