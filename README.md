# Pronounceable String Generator (PSG)

Ein benutzerfreundliches Webtools zur Generierung aussprechbarer, zufälliger Zeichenketten. Ideal für die Erstellung von Domainnamen, Produktbezeichnungen oder kreativen Wortschöpfungen. Der Generator erzeugt Strings durch intelligente Alternierung von Vokalen und Konsonanten, was zu leicht lesbaren und einprägsamen Ergebnissen führt.

## Projektbeschreibung

PSG ist eine clientseitige Webanwendung, die ohne Server-Backend auskommt. Sie generiert zufällige, aber aussprechbare Zeichenketten nach definierten Regeln und bietet eine benutzerfreundliche Oberfläche mit Material Design.

## Setup-Anweisungen

### Windows
1. Laden Sie das Repository herunter (ZIP-Download oder git clone)
2. Entpacken Sie die Dateien falls nötig
3. Navigieren Sie zum Projektverzeichnis
4. Option A: Doppelklicken Sie auf `index.html`
5. Option B: Führen Sie in der Kommandozeile aus:
   ```
   start index.html
   ```
   
Hinweis: Stellen Sie sicher, dass JavaScript in Ihrem Browser aktiviert ist.

### Linux
1. Klonen Sie das Repository:
   ```
   git clone [repository-url]
   cd psg
   ```
2. Öffnen Sie die Anwendung:
   ```
   xdg-open index.html
   ```
   oder
   ```
   firefox index.html
   ```

## Verfügbare Tools und Funktionen

### String-Generator
- Generierung mehrerer Strings gleichzeitig
- Anpassbare Stringlänge (1 bis n Zeichen)
- Alternierendes Vokal-Konsonanten-Muster
- Domain-kompatible Ausgabe (inkl. Bindestriche)

### Such-Integration
- Direkte Google-Suche für generierte Strings
- Überprüfung der Verfügbarkeit/Verwendung

### Zeichensätze
- **Vokale**: a, e, i, o, u
- **Konsonanten**: b-z (ohne Vokale), Bindestrich (-)

## Generierungsregeln
1. **Alternierendes Muster**: Wechsel zwischen Vokalen und Konsonanten
2. **Zufälliger Start**: Beginnt zufällig mit Vokal oder Konsonant
3. **Domain-Regeln**:
   - Keine Bindestriche am Anfang oder Ende
   - Keine aufeinanderfolgenden Bindestriche
   - Nur Buchstaben und Bindestriche erlaubt

## Technische Abhängigkeiten

### Frontend-Frameworks
- Materialize CSS (v1.0.0)
- Google Material Icons
- Google Fonts (Roboto)

### Browser-Kompatibilität
- Chrome (empfohlen)
- Firefox
- Safari
- Edge

### Erforderliche Browser-Funktionen
- JavaScript aktiviert
- LocalStorage (optional)
- Internetverbindung für CDN-Ressourcen

## Lizenz

MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
