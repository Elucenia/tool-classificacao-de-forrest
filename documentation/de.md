<!-- ELUCENIA technical documentation · classificacao-de-forrest · de · no clinical/professional/rights approval -->

# Forrest-Klassifikation

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/classificacao-de-forrest)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Endoskopisches Erscheinungsbild des Ulkus

`classe`

- `Ia` — Ia – aktive spritzende Blutung
- `Ib` — Ib – aktive Sickerblutung
- `IIa` — IIa – sichtbarer Gefäßstumpf ohne Blutung
- `IIb` — IIb – anhaftendes Koagel
- `IIc` — IIc – flacher pigmentierter Fleck (Hämatin)
- `III` — III – sauberer Grund (Fibrin)

## Fassung der Methode

Forrest 1974: Ia/Ib/IIa/IIb/IIc/III; Kontext ESGE 2021

## Dokumentierte Formel

Forrest I (aktive Blutung): Ia spritzend, Ib sickernd. Forrest II (Zeichen kürzlicher Blutung): IIa sichtbares Gefäß, IIb anhaftendes Koagel, IIc flache Hämatinauflagerung. Forrest III: sauberer Ulkusgrund.

## Grenzen und Population

Forrest klassifiziert das endoskopische Erscheinungsbild eines blutenden peptischen Ulkus, nicht jede gastrointestinale Blutung. Wählen Sie die Klasse anhand der Untersuchung; das Werkzeug analysiert keine Bilder und identifiziert nicht die Blutungsursache. Die ESGE-Leitlinie von 2021 weist auf Grenzen der Übereinstimmung zwischen Untersuchenden hin. Die Klasse und etwaige historische Prozentangaben liefern allein keine individuelle Vorhersage einer erneuten Blutung und bestimmen weder Entlassung noch Behandlung.

## Referenzen

- [Forrest JA, Finlayson ND, Shearman DJ. Endoscopy in gastrointestinal bleeding. Lancet, 1974.](https://doi.org/10.1016/S0140-6736(74)91770-X)

- [Laine L, Peterson WL. Bleeding peptic ulcer. N Engl J Med, 1994.](https://doi.org/10.1056/NEJM199409153311107)

- [Gralnek IM et al. Endoscopic diagnosis and management of nonvariceal upper gastrointestinal hemorrhage (NVUGIH): European Society of Gastrointestinal Endoscopy (ESGE) Guideline – Update 2021. Endoscopy, 2021.](https://doi.org/10.1055/a-1369-5274)

- [ESGE2021](https://www.esge.com/assets/downloads/pdfs/guidelines/2021_a_1369_5274.pdf)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
