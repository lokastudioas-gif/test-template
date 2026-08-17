# Loka Studio – Projekt-Template

Basis-Grundgerüst für neue Kundenprojekte von Loka Studio (Stapper & Albrecht GbR).

## Neues Kundenprojekt starten

1. Auf GitHub oben auf **Use this template** klicken.
2. Neues Repository in der Organisation `loka-studio` anlegen, benannt nach dem Schema `kundenname-ort` (z. B. `friseur-mueller-buehl`).
3. Repository lokal klonen:
   ```
   git clone https://github.com/loka-studio/<repo-name>.git
   cd <repo-name>
   ```
4. In `index.html` und `style.css` die Platzhalter durch die echten Kundeninhalte ersetzen.
5. Änderungen committen und pushen:
   ```
   git add .
   git commit -m "Grundgerüst an Kunden angepasst"
   git push
   ```

## Struktur

```
index.html      Hauptseite mit Platzhalter-Inhalten
style.css       Zentrale Styles, Farben/Schriften über CSS-Variablen oben anpassen
assets/         Bilder, Icons, Logo des Kunden
.github/workflows/  Automatisches Deployment auf GitHub Pages
```

## Vorschau-Link (GitHub Pages)

Sobald das Repository auf GitHub liegt und der Actions-Workflow einmal gelaufen ist, ist die Seite automatisch erreichbar unter:

```
https://loka-studio.github.io/<repo-name>/
```

Diesen Link können wir dem Kunden als Vorschau vor dem eigentlichen Go-Live schicken.

## Vor der Übergabe / dem Go-Live prüfen

- [ ] Alle Platzhaltertexte ersetzt
- [ ] Impressum und Datenschutzerklärung eingefügt
- [ ] Kontaktdaten korrekt (Telefon, E-Mail, Adresse)
- [ ] Bilder optimiert (Dateigröße, Alt-Texte)
- [ ] Mobile-Ansicht geprüft
- [ ] SEO: Title, Meta-Description pro Seite gesetzt
- [ ] Eigene Domain verbunden (falls gewünscht, statt github.io-Link)
