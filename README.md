# 🍳 Inimei's Kitchen

**Dein persönliches digitales Kochbuch — mit eingebautem Einkaufsplaner, Wochenbudget und Preisgedächtnis.**

![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![PWA](https://img.shields.io/badge/PWA-ready-5BBFB5?style=flat-square)
![No Framework](https://img.shields.io/badge/framework-none-2D2D2D?style=flat-square)
![No Backend](https://img.shields.io/badge/backend-none-9B2556?style=flat-square)
![Made in Pfalz](https://img.shields.io/badge/made%20in-Pfalz%20🍇-orange?style=flat-square)

> Kostenlos. Kein Abo. Keine Cloud. Alle Daten bleiben auf deinem Gerät.

🌐 **Live:** [inimeiskitchen.com](https://inimeiskitchen.com) &nbsp;·&nbsp; ⭐ **Star** wenn dir die App gefällt! &nbsp;·&nbsp; 🍵 [Buy me a tea](https://inimei.kit.com/products/support-a-trobadour)

---

<!-- Screenshot hier einfügen sobald live:
![Inimei's Kitchen Screenshot](screenshot.png)
-->


---

## ✨ Features

| Feature | Beschreibung |
|---|---|
| 🛒 **Einkaufsliste** | 230+ Artikel mit Preisgedächtnis aus echten Kassenbons |
| 📖 **Digitales Kochbuch** | 43+ Rezepte, eigene hinzufügbar |
| 📅 **Wochenplaner** | Mahlzeiten planen, alle Zutaten auf einmal auf die Liste |
| 💰 **Budget-Optimierung** | Wochenplan automatisch aus deinem Budget generieren |
| 📷 **Belegscanner** | Bon fotografieren → KI liest Preise → Datenbank aktualisiert |
| 🍽 **Schnell kochen** | Rezept wählen → Zutaten sofort auf die Einkaufsliste |
| 📱 **PWA** | Als App auf dem iPhone speichern — kein App Store nötig |

---

## 🚀 Installation

### Option 1 — Direkt nutzen (empfohlen)
👉 [inimeiskitchen.com](https://inimeiskitchen.com) öffnen → Safari → Teilen → **Zum Home-Bildschirm**

### Option 2 — Selbst hosten
```bash
git clone https://github.com/inimei-tech/inimeis-kitchen.git
cd inimeis-kitchen
# Einfach index.html in einem Webserver-Ordner ablegen
# oder lokal öffnen: open index.html
```

### Option 3 — Fork & Anpassen
Fork dieses Repo, passe Rezepte und Preise an deine Region an!

---

## 📷 Belegscanner einrichten (optional)

Der Belegscanner nutzt die [Anthropic Claude API](https://console.anthropic.com).

1. Kostenlosen API Key holen: [console.anthropic.com](https://console.anthropic.com)
2. In der App: Einstellungen → API Key eintragen
3. Der Key wird **nur lokal** auf deinem Gerät gespeichert — nie auf einem Server

> **Hinweis für Entwickler:** Trage den Key niemals direkt in den Code ein und checke ihn nie in Git ein. Nutze stattdessen `.env` Dateien oder den localStorage-Mechanismus der App.

---

## 🛠 Technik

- **Pure HTML/CSS/JS** — kein Framework, kein Build-Prozess
- **localStorage** — alle Daten lokal, kein Server
- **PWA** — installierbar, offline-fähig
- **Anthropic Claude API** — nur für Belegscanner (optional)
- **Mobile-first** — optimiert für iPhone/Safari

---

## 🗂 Projektstruktur

```
inimeis-kitchen/
├── index.html          # Die komplette App (eine Datei!)
├── README.md           # Diese Datei
├── LICENSE             # MIT License
└── CONTRIBUTING.md     # Wie du mitmachen kannst
```

---

## 🤝 Mitmachen

Beiträge sind herzlich willkommen! Besonders:

- 🥘 **Neue Rezepte** hinzufügen
- 🏪 **Preise** aus deiner Region ergänzen
- 🌍 **Übersetzungen** (Türkisch, Englisch, etc.)
- 🐛 **Bugs** melden

Bitte lies zuerst [CONTRIBUTING.md](CONTRIBUTING.md).

---

## 💝 Unterstützen

Inimei's Kitchen ist und bleibt kostenlos.  
Wenn dir die App hilft, freue ich mich über eine kleine Unterstützung:

[![Buy me a tea](https://img.shields.io/badge/Buy%20me%20a%20tea-5BBFB5?style=flat-square&logo=buymeacoffee&logoColor=white)](https://inimei.kit.com/products/support-a-trobadour)
[![Newsletter](https://img.shields.io/badge/Newsletter-FF6719?style=flat-square&logo=substack&logoColor=white)](https://inimeitech.substack.com)

---

## 👩‍💻 Über die Entwicklerin

Gebaut von einer Hustling Mother, Musikerin und Bloggerin — und mit viel Geduld bestimmt auch bald Gründerin.

> *Inimei — „A little Humanist's Manifesto"*

[![Website](https://img.shields.io/badge/inimei.de-2D2D2D?style=flat-square&logo=safari&logoColor=white)](https://inimei.de)
[![PalzCare](https://img.shields.io/badge/PalzCare-9B2556?style=flat-square&logo=heart&logoColor=white)](https://palzcare.de)
[![Instagram](https://img.shields.io/badge/@inimei__01-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/inimei_01)
[![X](https://img.shields.io/badge/@inimei10-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/inimei10)
[![Substack](https://img.shields.io/badge/Substack-FF6719?style=flat-square&logo=substack&logoColor=white)](https://inimeitech.substack.com)

---

## 📄 Lizenz

MIT License — siehe [LICENSE](LICENSE)

Du darfst den Code frei nutzen, verändern und weitergeben.  
Eine Erwähnung freut mich natürlich! 😊
