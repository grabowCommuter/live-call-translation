# Testprotokoll fuer uebersetzte Anrufe

**Status: Vorlage, noch kein durchgefuehrter Test.**
Jede Kombination aus Geraet, Software, Dienst und Sprachpaar separat erfassen.
Keine echten vertraulichen Gespraechsinhalte in dieses Repository uebernehmen.

## Rahmen

| Feld | Eintrag |
| --- | --- |
| Testdatum / Zeitzone | |
| Dienst / Funktion | |
| Geraet und Betriebssystem, beide Seiten | |
| App-Version, beide Seiten | |
| Land / Region | |
| Sprache A / Sprache B | |
| Anrufart: Rufnummer, Messenger, Link | |
| Ausgehend / eingehend, aus Sicht des Testgeraets | |
| WLAN / Mobilfunk / Headset | |
| Tarif, Minutenpreis und erwartete Gesamtkosten | |
| Hinweise zur Datenverarbeitung geprueft | |
| Beide Personen informiert und einverstanden | |

## Ablauf

1. Sprachpakete und benoetigte Einstellungen vorbereiten.
2. Anruf aufbauen und Uebersetzung aktivieren.
3. Pruefen, ob beide Seiten eine gesprochene Uebersetzung hoeren.
4. Gleiche Inhalte in beide Sprachrichtungen testen.
5. Mit Headset und danach in leichtem Hintergrundlaerm wiederholen.
6. Eingehenden und ausgehenden Anruf getrennt testen, soweit unterstuetzt.
7. Gespraech beenden; Kosten und eventuell gespeicherte Inhalte kontrollieren.

## Testsaetze

Die andere Person verwendet sinngemaess die entsprechende Zielsprache.

- "Ich moechte morgen um 15:30 Uhr einen Tisch fuer vier Personen reservieren."
- "Die Buchungsnummer lautet AB sieben zwei neun."
- "Der Preis betraegt 19 Euro und 90 Cent, nicht 90 Euro."
- "Bitte stornieren Sie die Reservierung nicht."
- "Ich habe Sie nicht verstanden. Koennen Sie das bitte wiederholen?"

## Ergebnisse

Bewertung: 0 = nicht nutzbar, 1 = mit Rueckfragen, 2 = korrekt verstanden.
Verzoegerungen moeglichst messen; Schaetzungen als solche kennzeichnen.

| Kriterium | A nach B | B nach A | Beobachtung |
| --- | --- | --- | --- |
| Allgemeines Verstaendnis | | | |
| Zahlen, Uhrzeit, Betrag | | | |
| Namen / Buchungsnummer | | | |
| Verneinung korrekt | | | |
| Verzoegerung in Sekunden | | | |
| Unterbrechungen / gleichzeitiges Sprechen | | | |
| Audio mit Headset | | | |
| Verhalten bei Netzunterbrechung | | | |

## Abschluss

- Tatsaechliche Kosten:
- Welche Seite brauchte App, Konto oder Link?
- Was wurde gespeichert, wo und wie geloescht?
- Abweichungen von Herstellerangaben:
- Offene Fragen:
- Eignung fuer den getesteten Anwendungsfall:

Keine Rangliste aus einem einzelnen Anruf ableiten. Fehlgeschlagene Versuche
und nicht verfuegbare Funktionen ebenfalls dokumentieren.
