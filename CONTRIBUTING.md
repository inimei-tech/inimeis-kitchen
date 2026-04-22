# 🤝 Mitmachen bei Inimei's Kitchen

Danke dass du zum Projekt beitragen möchtest! 💚

## Wie du helfen kannst

### 🥘 Rezepte hinzufügen
Öffne `index.html` und suche nach `const RECIPES = [`.  
Füge dein Rezept in diesem Format hinzu:

```javascript
{
  "name": "Mein Rezept",
  "tags": "Schnell, Vegetarisch",
  "zutaten": ["Zutat 1", "Zutat 2", "Zutat 3"],
  "custom": false
}
```

### 🏪 Preise ergänzen
Suche nach `const BASE_CATALOG = {` und ergänze Artikel:

```javascript
"Artikelname": { "price": 1.99, "shop": "Lidl", "cat": "Gemüse" }
```

Kategorien: `Gemüse`, `Obst`, `Milchprodukte`, `Fleisch&Fisch`, `Backwaren`, `Trockenwaren`, `Getränke`, `Süßigkeiten`, `Kosmetik`, `Haushaltsartikel`, `Sonstiges`

### 🐛 Bug melden
Erstelle ein [Issue](https://github.com/inimei-tech/inimeis-kitchen/issues) mit:
- Was hast du erwartet?
- Was ist passiert?
- Welches Gerät/Browser?

### 💡 Feature vorschlagen
Auch dafür gerne ein Issue öffnen mit dem Label `enhancement`.

## Pull Request Prozess

1. Fork das Repo
2. Erstelle einen Branch: `git checkout -b feature/mein-feature`
3. Commit: `git commit -m 'Add: Neues Rezept XYZ'`
4. Push: `git push origin feature/mein-feature`
5. Pull Request öffnen

## Wichtige Regeln

- ❌ Niemals API Keys in den Code einchecken
- ❌ Keine persönlichen Daten von echten Personen
- ✅ Nur Lebensmittel und Haushaltsartikel in den Katalog
- ✅ Preise aus echten deutschen Supermärkten

## Fragen?

📬 [inimei.de](https://inimei.de) oder GitHub Issues
