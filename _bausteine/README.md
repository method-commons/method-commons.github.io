# Bausteine für die Schulungsseiten

Wiederverwendbare Stücke für die Kurzschulungen (`*-site`). Der Ordner beginnt mit `_`, damit GitHub Pages (Jekyll) ihn nicht veröffentlicht.

## `method-commons-link.html` – Verweis auf die Übersichtsseite

Karte „Weitere Methoden entdecken“, die auf <https://method-commons.github.io/> verlinkt. Eingebaut in allen Schulungsseiten (Klasse `mc-link`).

Einbau in eine neue Schulungsseite:

1. Die Regeln aus dem `<style>`-Block der Datei an das Ende des vorhandenen `<style>`-Blocks im `<head>` anhängen.
2. Den `<aside class="mc-link">`-Block direkt vor `</main>` einfügen, also nach dem CTA-Abschnitt und vor dem Footer.

Der Baustein nutzt nur Tokens, die alle Schulungsseiten haben (`--surface`, `--line`, `--text`, `--muted`, `--accent`, `--logo`, `--radius`, `--shadow`) und folgt damit hell/dunkel automatisch. Der Text nennt bewusst keine einzelnen Methoden, damit er bei neuen Methoden nicht angepasst werden muss.
