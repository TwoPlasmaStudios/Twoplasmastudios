<style>
/* Dil bölümleri varsayılan olarak gizli */
.lang-section {
  display: none;
}

/* Seçili dil göster */
#lang-en:checked ~ .lang-en,
#lang-tr:checked ~ .lang-tr,
#lang-de:checked ~ .lang-de {
  display: block;
}

/* Radyo butonlarını gizle */
.switcher input[type="radio"] {
  display: none;
}

/* Etiketleri buton gibi biçimlendir */
.switcher label {
  display: inline-block;
  padding: 6px 16px;
  margin: 0 4px 8px 0;
  background: #2d2d2d;
  color: #e0e0e0;
  border-radius: 20px;
  cursor: pointer;
  font-size: 14px;
  transition: 0.2s;
  border: 1px solid #444;
}
.switcher label:hover {
  background: #3a3a3a;
}
#lang-en:checked ~ .switcher label[for="lang-en"],
#lang-tr:checked ~ .switcher label[for="lang-tr"],
#lang-de:checked ~ .switcher label[for="lang-de"] {
  background: #58a6ff;
  color: #fff;
  border-color: #58a6ff;
}
</style>

<!-- Dil seçici -->
<input type="radio" name="lang" id="lang-en" checked>
<input type="radio" name="lang" id="lang-tr">
<input type="radio" name="lang" id="lang-de">

<div class="switcher">
  <label for="lang-en">English</label>
  <label for="lang-tr">Türkçe</label>
  <label for="lang-de">Deutsch</label>
</div>

<!-- ============= İNGİLİZCE ============= -->
<div class="lang-en lang-section">

# Hello, I'm Two Plasma Studios! 👋

🚀 We are a studio developing innovative software and games.  
🎯 Our goal is to produce open-source tools and fun games for everyone.

### 🔧 Skills &amp; Technologies
- **Languages:** Python, HTML, CSS, JavaScript
- **Tools:** GitHub Copilot, VS Code,Android Studio
- **Focus Areas:** Web applications, game development, automation tools

### 📂 Featured Projects
- **myorkslydes** – Interactive slide editor
- **myorktext** – Custom format text editor
- **project-neo-tycoon** – Mini business simulation
- **auto-py-to-apk** – Convert Python to desktop app with one click

### 📈 Stats
![GitHub stats](https://github-readme-stats.vercel.app/api?username=twoplasmastudios&show_icons=true&theme=radical)

---

💬 **Contact:** Reach us via [our website](https://twoplasmastudios.github.io).

</div>

<!-- ============= TÜRKÇE ============= -->
<div class="lang-tr lang-section">

# Merhaba, ben Two Plasma Studios! 👋

🚀 Yenilikçi yazılımlar ve oyunlar geliştiren bir stüdyoyuz.  
🎯 Amacımız, herkesin kullanabileceği açık kaynak araçlar ve eğlenceli oyunlar üretmek.

### 🔧 Yeteneklerimiz &amp; Teknolojiler
- **Diller:** Python, HTML, CSS, JavaScript
- **Araçlar:** GitHub Copilot, VS Code
- **Odak Alanları:** Web uygulamaları, oyun geliştirme, otomasyon araçları

### 📂 Öne Çıkan Projeler
- **myorkslydes** – Etkileşimli slayt editörü
- **myorktext** – Özel formatlı metin editörü
- **project-neo-tycoon** – Mini işletme simülasyonu
- **auto-py-to-apk** – Python’ı tek tıkla masaüstü uygulamasına dönüştür

### 📈 İstatistikler
![GitHub stats](https://github-readme-stats.vercel.app/api?username=twoplasmastudios&show_icons=true&theme=radical)

---

💬 **İletişim:** [Web sitemiz](https://twoplasmastudios.github.io) üzerinden bize ulaşabilirsiniz.

</div>

<!-- ============= ALMANCA ============= -->
<div class="lang-de lang-section">

# Hallo, ich bin Two Plasma Studios! 👋

🚀 Wir sind ein Studio, das innovative Software und Spiele entwickelt.  
🎯 Unser Ziel ist es, Open-Source-Tools und unterhaltsame Spiele für alle zu produzieren.

### 🔧 Fähigkeiten &amp; Technologien
- **Sprachen:** Python, HTML, CSS, JavaScript
- **Tools:** GitHub Copilot, VS Code
- **Schwerpunkte:** Webanwendungen, Spieleentwicklung, Automatisierungstools

### 📂 Ausgewählte Projekte
- **myorkslydes** – Interaktiver Folien-Editor
- **myorktext** – Texteditor mit benutzerdefiniertem Format
- **project-neo-tycoon** – Mini-Unternehmenssimulation
- **auto-py-to-apk** – Python mit einem Klick in Desktop-Anwendung umwandeln

### 📈 Statistiken
![GitHub stats](https://github-readme-stats.vercel.app/api?username=twoplasmastudios&show_icons=true&theme=radical)

---

💬 **Kontakt:** Erreichen Sie uns über [unsere Website](https://twoplasmastudios.github.io).

</div>
