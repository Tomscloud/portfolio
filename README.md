# Portfolio Projekt – Thomas Stillebacher

**Live-URL:** [https://tomscloud.github.io/portfolio/](https://tomscloud.github.io/portfolio/)  
**Fokus:** IT-Infrastruktur, Netzwerke, Medientechnik & Gebäudetechnik (25 Jahre Praxiserfahrung)

---

## 🛠️ Technische Kernkomponenten

### 1. 3D-Plexus Maus-Animation (Three.js)
* **Geometrie:** `TetrahedronGeometry(0.7, 2)` für eine unregelmäßige, technische Form.
* **Deformation:** Dynamisches Atmen der Knotenpunkte über Sinus-Wellen.
* **Visuals:** Weiß leuchtende Punkte mit cyanfarbenen Verbindungslinien.

```javascript
// Geometrie-Definition
const baseGeometry = new THREE.TetrahedronGeometry(0.7, 2);

// Organische Deformation in animate()
const distortion = Math.sin(time + orig.x * 3.0 + orig.y * 2.0) * 0.18;

// Knotenpunkte
const pointMaterial = new THREE.PointsMaterial({
  color: 0xffffff,
  size: 0.03,
  transparent: true,
  opacity: 0.7
});
```

---

### 2. Header & SEO Metadata setup (`index.html`)

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Technischer Infrastruktur-Experte mit 25 Jahren IT-Erfahrung in Österreich. Spezialisiert auf Netzwerke, Gebäudetechnik und Medientechnik.">
    
    <!-- Favicon Integration -->
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
    <link rel="icon" type="image/png" sizes="32x32" href="favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="favicon-16x16.png">
    <link rel="apple-touch-icon" sizes="180x180" href="apple-touch-icon.png">
    <link rel="manifest" href="site.webmanifest">
    <meta name="theme-color" content="#0f172a">
    <meta name="robots" content="index, follow">
    
    <title>Thomas Stillebacher | IT-Infrastruktur & Gebäudetechnik Experte Österreich</title>
    <link rel="stylesheet" href="style.css">
    <link rel="canonical" href="https://tomscloud.github.io/portfolio/">
</head>
```

---

### 3. Favicon Package Struktur
Dateien im Root-Verzeichnis des GitHub Repositories:
* `favicon.ico`
* `favicon-32x32.png` & `favicon-16x16.png`
* `apple-touch-icon.png`
* `android-chrome-192x192.png` & `android-chrome-512x512.png`
* `site.webmanifest`
