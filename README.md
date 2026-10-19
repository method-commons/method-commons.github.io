# method-commons.github.io

Übersichtsseite der GitHub-Organisation **Method Commons**: erprobte Methoden aus dem erweiterten Projektmanagement – je Methode eine Kurzschulung (`*-site`) und eine passende Web-App (`*-app`).

Veröffentlicht unter <https://method-commons.github.io/>. Eine einzelne statische `index.html`, keine Build-Schritte.

Alle Inhalte sind KI-generiert (Vibe-Coding mit Claude Code).

## Neue Methode ergänzen

1. In `index.html` einen Block `<article class="card project" id="…">` nach dem Muster der vorhandenen anlegen, einen Eintrag in der Navigation (`#navMenu`) ergänzen (die Überschrift des Abschnitts enthält keine Zahl und bleibt unverändert).
2. In die neue Schulungsseite den Verweis auf diese Übersicht einbauen: [`_bausteine/method-commons-link.html`](_bausteine/method-commons-link.html), Anleitung in [`_bausteine/README.md`](_bausteine/README.md).

## Empfehlung (externer Link) ergänzen

Im Abschnitt `#empfehlungen` von `index.html` ein `<li>` mit einer `ext-card` nach dem Muster von Retromat kopieren und Anfangsbuchstabe, Name, Domain, Beschreibung und Tags anpassen. Das Raster ordnet neue Karten automatisch an.
