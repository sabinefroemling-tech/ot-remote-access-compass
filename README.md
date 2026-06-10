# OT-Fernzugriffs-Kriterienkompass · OT Remote Access Criteria Compass

Ein leichtgewichtiges, browserbasiertes und **zweisprachiges (DE/EN)** Werkzeug, das aus wenigen Kontextangaben ein anbieterneutrales Anforderungsprofil für sichere Fernzugriffslösungen in OT-Umgebungen erzeugt — als Begleitmaterial zum Fachbuch **„ISMS für die Industrie. Von ISO 27001 über NIS2 bis OT-Security“**.

Es ist Teil der Companion-Reihe, neben der [Crown-Jewels-Identifikation](https://sabinefroemling-tech.github.io/crown-jewels-companion/), dem [No-Touch-Register](https://sabinefroemling-tech.github.io/no-touch-register/), dem [JIT-Fernwartungs-Fahrplan](https://sabinefroemling-tech.github.io/jit-fernwartung-fahrplan/) und dem [OT-Reifegrad-Profil](https://sabinefroemling-tech.github.io/ot-reifegrad-profil/). Während der JIT-Fernwartungs-Fahrplan den *eigenen* Reifegrad entlang des Vier-Stufen-Modells bestimmt, beantwortet der Kriterienkompass die Anschlussfrage: *Welche Eigenschaften muss ein Werkzeug mitbringen, das die identifizierten Lücken schließt?*

## Was es macht

Der Anwender beantwortet sieben Kontextfragen (Regulierungsstatus EU/DE/USA, Personenkonstellation, Industrieprotokolle im Zugriffspfad, Brownfield-Anteil, Verfügbarkeitsanforderung, Cloud-Zulässigkeit, Ziel-Security-Level nach IEC 62443). Daraus leitet das Werkzeug für **14 anbieterneutrale Kriterien** — von individuellen Identitäten über Just-in-Time-Aktivierung, Credential Vaulting, Protokollbruch und Session-Recording bis Break-Glass und Datenhoheit — eine Gewichtung **Muss / Soll / Optional** ab, jeweils mit Begründung aus dem Kontext.

Jedes Kriterium ist vier Rahmenwerken zugeordnet (Spalten einzeln zuschaltbar):

- **IEC 62443-3-3** (System Requirements, SR) — der internationale OT-Anker
- **ISO/IEC 27001:2022** (Anhang A)
- **NIST CSF 2.0** (für US-Kontexte; Vertiefung über NIST SP 800-82r3)
- **NIS2 Art. 21 Abs. 2** (EU)

Im **Kandidatenvergleich** legt der Anwender bis zu sechs eigene Kandidaten an (Produkt, Eigenbau, Bestandslösung) und bewertet sie je Kriterium (erfüllt / teilweise / nicht erfüllt). Die Auswertung gewichtet Muss=3 / Soll=2 / Optional=1 — mit einer harten Regel: **Eine offene Muss-Lücke führt zum K.-o., unabhängig vom Gesamtscore.** Das verhindert den klassischen Beschaffungsfehler, dass ein hoher Featurescore ein fehlendes Pflichtkriterium überdeckt.

Eine deutschlandspezifische Weiche ist eingebaut: Wird Session-Recording zum Muss-Kriterium und sind interne Mitarbeiter in der Personenkonstellation erfasst, erscheint der Hinweis auf die Mitbestimmung nach §87 Abs. 1 Nr. 6 BetrVG — mit Verweis auf Reihenfolge und Muster im JIT-Fernwartungs-Fahrplan.

## Bewusst ohne Produktnamen

Das Werkzeug bewertet keine Anbieter und enthält keine Produktnamen, Preise oder Rankings. Es liefert die Kriterien und die Prüfsystematik; die Bewertung konkreter Kandidaten nimmt der Anwender selbst vor. Das hält das Werkzeug dauerhaft aktuell (Kriterien altern langsam, Produktdaten schnell) und frei von redaktionellen Werturteilen über einzelne Hersteller.

## Nutzung

Es ist keine Installation nötig. Die Datei `index.html` im Browser öffnen — oder die gehostete Version aufrufen. Alle Daten bleiben ausschließlich im Browser; es findet keine Datenübertragung statt (DSGVO-freundlich), und es wird nichts still gespeichert.

- **Sprachumschaltung DE/EN** — vollständige Oberfläche und Inhalte in beiden Sprachen.
- **Kontextprofil** — Organisation, Datum und die sieben Fragen ausfüllen; das Profil aktualisiert sich sofort.
- **Anforderungsprofil als CSV** — inklusive Normverweisen und Kandidatenbewertung, direkt ausschreibungstauglich.
- **Speichern / Laden (JSON)** — der Stand wird als Datei abgelegt und wieder eingelesen.
- **Drucken / PDF** — Profil und Kandidatenvergleich, personalisiert mit Organisation und Datum.

## Grenzen

Die Zuordnungen zu IEC 62443-3-3, ISO/IEC 27001:2022, NIST CSF 2.0 und NIS2 sind redaktionelle Orientierung der Autorin — keine offiziellen Mapping-Tabellen der Normungsgremien und keine Konformitätsaussage. Normtexte werden referenziert, nicht wiedergegeben.

Der Kompass strukturiert die Anforderungsdefinition, die Ausschreibung und das Anbietergespräch; er ersetzt weder eine Risikoanalyse nach IEC 62443-3-2 noch eine Teststellung (PoC) noch die juristische Prüfung. Der BetrVG-Hinweis ist eine Weiche, keine Rechtsberatung.

## Lizenz

© Sabine Frömling. Veröffentlicht unter [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.de) — Namensnennung, nicht-kommerziell, keine Bearbeitungen. Details in [`LICENSE`](LICENSE).

## Autorin

**Sabine Frömling** — Unabhängige IT-Security- und Compliance-Beraterin (OT-Security, NIS2, ISO 27001, KRITIS, IEC 62443).
[LinkedIn](https://www.linkedin.com/in/sabine-froemiing/)
