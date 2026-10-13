# Pixel Prisoner

**Drei Gefängnis-Tamagotchis im Retro-Handheld-Look, die in Echtzeit weiterlaufen – auch wenn die App geschlossen ist.**

> ⚠️ **Experimentelles, nicht-kommerzielles Hobbyprojekt.** Pixel Prisoner ist ein künstlerisches Experiment mit historischen Stoffen und schwarzem Humor. Es wird nicht verkauft, enthält keine Werbung, sammelt keine Daten und verfolgt keinerlei kommerzielle Absichten. Funktionen, Spielbalance und Inhalte können sich jederzeit ändern.

## Worum geht es?

Pixel Prisoner ist ein kleines Browserspiel nach dem Prinzip virtueller Haustiere: Werte sinken mit der Zeit, und du musst dich regelmäßig kümmern. Die Zeit läuft dabei in **Echtzeit** weiter. Wer die Seite schließt und später zurückkommt, bekommt eine Zusammenfassung dessen, was in der Zwischenzeit passiert ist.

Statt eines Haustiers betreust du historische Häftlinge in drei Szenarien:

| Szenario | Ort & Jahr | Deine Aufgabe |
|---|---|---|
| **Cellmate** | Turi, 1928 | Halte den inhaftierten Philosophen Antonio Gramsci mit Suppe, Papier und Medizin am Leben, damit er seine *Gefängnishefte* schreiben kann. |
| **The Nuremberg Nightshift** | Nürnberg, 1946 | Als alliierter Wärter vor Hermann Görings Zelle verhinderst du seinen Suizid durch Zyankali, bis das Urteil gefällt ist. |
| **29 Minutes Later** | New York, MCC, 2019 | Schwarze Satire auf das Kontrollversagen der Wärter in der Nacht von Jeffrey Epsteins Tod: Übersteh möglichst viele 72-Stunden-Schichten. |

### Bedienung

- Drei Tasten **A**, **B** und **C** – per Touch, Maus oder Tastatur (`A`/`B`/`C` bzw. `1`/`2`/`3`).
- **MENÜ** (oben links) führt zurück zur Szenario-Auswahl, **INFO** erklärt das aktuelle Szenario.
- Im Hauptmenü: A = Szenario wählen, B = starten, C = Erklärung.

### Spielen

Die gesamte App besteht aus einer einzigen Datei, [`index.html`](index.html). Einfach im Browser öffnen – oder über GitHub Pages aufrufen, falls für dieses Repository aktiviert. Auf iPhone/Android lässt sich die Seite über „Zum Home-Bildschirm“ wie eine App ablegen.

Der Spielstand wird ausschließlich lokal im Browser (`localStorage`) gespeichert. Es werden keine Daten an einen Server übertragen.

## Technik

- Reines HTML, CSS und JavaScript, **ohne externe Bibliotheken, Frameworks, Schriftarten oder Dateien**.
- Grafik: selbst gezeichnete Pixel-Sprites, die im Code definiert und auf ein `<canvas>` (160 × 128 Pixel) gerendert werden.
- Sound: Töne werden zur Laufzeit mit der Web Audio API des Browsers erzeugt – es werden keine Audiodateien verwendet.
- Schrift: die jeweils vorinstallierte Monospace-Systemschrift des Geräts (z. B. SF Mono, Menlo, Consolas).

## Verwendete Elemente Dritter, Marken & Danksagungen

**Pixel Prisoner bindet keinen Code, keine Grafiken, Sounds oder Schriften Dritter ein.** Es gibt daher keine fremden Lizenzen, deren Hinweise hier wiedergegeben werden müssten. Folgende Bezüge und Inspirationen seien dennoch transparent genannt:

- **Tamagotchi** ist eine eingetragene Marke der BANDAI Co., Ltd. Der Begriff wird hier nur beschreibend für das Spielprinzip „virtuelles Haustier“ verwendet. Pixel Prisoner steht in keiner Verbindung zu BANDAI und wird von BANDAI weder unterstützt noch autorisiert.
- **Game Boy** ist eine eingetragene Marke von Nintendo. Die grüne Vierfarb-Palette und das Handheld-Design sind lediglich von der Optik früher Handheld-Konsolen inspiriert. Es werden keine Nintendo-Assets verwendet; es besteht keine Verbindung zu Nintendo.
- **Antonio Gramscis *Quaderni del carcere*** (Gefängnishefte) werden nur als historischer Bezug genannt, nicht zitiert.

## Hinweis zu historischen Personen und Inhalten

Die Szenarien beziehen sich auf reale historische Personen und Ereignisse, darunter Haft, Krankheit, Suizid und Tod. Die Darstellung ist stark vereinfacht, fiktionalisiert und teils bewusst satirisch zugespitzt. Sie erhebt keinen Anspruch auf historische Genauigkeit und soll weder Opfer verhöhnen noch Täter verherrlichen. Die Satire richtet sich gegen institutionelles Versagen, nicht gegen Betroffene.

Wenn dich Themen wie Suizid belasten: In Deutschland erreichst du die Telefonseelsorge rund um die Uhr kostenlos unter **0800 111 0 111** oder **0800 111 0 222**.

## Lizenz

© 2026 lepettre

Dieses Projekt steht unter der Lizenz **[Creative Commons Namensnennung – Nicht kommerziell 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.de)**. Du darfst das Projekt teilen und bearbeiten, solange du den Urheber nennst, auf die Lizenz verweist, Änderungen kenntlich machst und es **nicht für kommerzielle Zwecke** nutzt. Details siehe [`LICENSE`](LICENSE).

Die Software wird ohne jegliche Gewährleistung bereitgestellt.
