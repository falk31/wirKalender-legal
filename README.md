# WirKalender – Rechtliches (GitHub Pages)

Enthält ausschließlich die öffentlich verlinkbare Fassung der Datenschutzerklärung und des
Impressums der App [WirKalender](https://github.com/falk31/Kalender) – benötigt u.a. für das
Feld „Datenschutzrichtlinie“ in der Google Play Console (dort reicht die In-App-Anzeige allein
nicht aus, Play verlangt eine öffentlich erreichbare URL).

**Quelle der Texte:** `lib/screens/datenschutz_screen.dart` und
`lib/screens/impressum_screen.dart` im Haupt-Repo. Bei inhaltlichen Änderungen dort **beide
Stellen** synchron halten – dieses Repo hier wird nicht automatisch generiert.

## Struktur

- `index.html` – Übersichtsseite mit Links zu beiden Dokumenten
- `datenschutz.html` – Datenschutzerklärung (das ist die URL fürs Play-Console-Feld)
- `impressum.html` – Impressum
- `style.css` – gemeinsames, minimales Stylesheet (hell/dunkel je nach Systemeinstellung)
- `icon.png` – App-Icon, übernommen aus `android/app/src/main/res/mipmap-xxxhdpi/ic_launcher.png`

## Hosting

Statisch über GitHub Pages, Branch `main`, Root-Verzeichnis. Nach Aktivierung erreichbar unter
`https://falk31.github.io/wirkalender-legal/` (siehe Repo-Settings → Pages).
