# Projektchor „Die 80er“ – Website

Informationsplattform (Onepager, Flatfile) für den Projektchor **„Die 80er“** des MGV Altendiez gegr. 1902 e.V.

## Struktur

- `index.html` – die komplette Website (HTML + CSS + Inhalte, keine Build-Schritte, keine Abhängigkeiten)

## Inhalte pflegen

Alle Texte, Termine und Proben stehen direkt in `index.html` und können über Pull Requests oder direkte Bearbeitung auf GitHub von überall geändert werden.

Termine stehen im Abschnitt `<!-- Termine -->` (`<section id="termine">`). Ein Termin folgt immer diesem Muster:

```html
<article class="event">
  <div class="date"><span class="day">24.</span><span class="month">Nov. 26</span></div>
  <div>
    <h3>Infotreffen</h3>
    <p>Beschreibung …</p>
    <p class="meta">Dienstag, 24.11.2026 &middot; 18:30 Uhr</p>
  </div>
</article>
```

## Hosting

Die Seite wird über **GitHub Pages** aus dem `main`-Branch (`root`) ausgeliefert: <https://netbuk.github.io/projektchor-80er/>

## Design

Orientiert am Projekt-Flyer: Neon-Farben (Pink, Cyan, Gelb, Lila, Orange), Retrowave-Typo (Bungee, Monoton) und Grid-Horizont im Hero.
