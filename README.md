# Promillerechner

Ein einfacher Promillerechner als **einzelne HTML-Datei** – ganz ohne Build-Schritt,
Abhängigkeiten oder Anmeldung. Einfach `index.html` im Browser öffnen.

## Was er berechnet

Aus Geschlecht, Körpergewicht, Getränken (Menge + Alkoholgehalt) und der Zeit seit
Trinkbeginn wird die Blutalkoholkonzentration (BAK) in Promille geschätzt – dazu
die ungefähre Zeit bis zum vollständigen Abbau.

## Formel

**Widmark-Formel:**

```
Alkohol (g)  = Menge (ml) × Vol.-% × 0,8
Promille     = Alkohol (g) ÷ (Gewicht (kg) × Verteilungsfaktor) − 0,15 × Stunden
```

Verteilungsfaktor: ca. 0,7 (männlich) bzw. 0,6 (weiblich). Der Abbau von ca.
0,15 ‰ pro Stunde ist ein Durchschnittswert.

## Rechenbeispiel

80 kg, männlich, 2 Bier à 500 ml (5 %) in 2 Stunden:

- Alkohol: 2 × 500 × 0,05 × 0,8 = 40 g
- Promille: 40 ÷ (80 × 0,7) − 0,15 × 2 = 0,71 − 0,30 = **0,41 ‰**

## Mehr Rechner & Ratgeber

- [Promillerechner](https://promillerechneronlne.de/) – ausführlicher Rechner mit allen Getränkearten
- [Alkoholabbau-Rechner](https://promillerechneronlne.de/alkoholabbau-rechner/)
- [Restalkohol-Rechner](https://promillerechneronlne.de/restalkohol-rechner/) – für den Morgen danach
- [Atemalkohol-Umrechner](https://promillerechneronlne.de/atemalkohol-umrechner/)
- [1,1 Promille – welche Strafe droht?](https://promillerechneronlne.de/1-1-promille-strafe/)

## Hinweis

Nur ein Schätzwert – ersetzt keine amtliche Messung. Wer fährt, trinkt am besten
gar nichts.

## Lizenz

MIT – siehe [LICENSE](LICENSE).
