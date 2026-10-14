# BRIEF · Smart Mülltonne (scroll-craft build)

**Status:** Brief aus der Anfrage des Teams übernommen (Design-Vorgaben wörtlich), fehlende Punkte unter ausdrücklicher Gestaltungsvollmacht ergänzt. Kein separates Interview.

## Die acht Themen

1. **Vibe:** "extraordinar de luxury și profesionist", Clean-Tech. Dark Slate `#0B0F17 / #0F172A`, Neon-Emerald `#10B981`. Keine lila KI-Verläufe.
2. **Reise (Worte des Teams):** Straßenniveau (Sonne, PV-Dach) → durch den KI-Scan-Schlitz → in den unterirdischen Schacht (Cutaway) → Sensor meldet Füllstand → logistischer Alarm an das Müllfahrzeug → Business Model.
3. **Energiekurve:** ruhig an der Oberfläche, Spannung im Scan, Tiefe und Schwere im Untergrund, Dringlichkeit beim Alarm, Ruhe und Überblick am Ende.
4. **Gefühl pro Stufe / der eine Moment:** siehe Gefühlskurve. Der Moment: die Flasche wird gescannt und physisch ins richtige Fach gelenkt.
5. **Was keine andere Seite tut:** Der Scroll *ist* der Weg des Mülls: Flasche → Laser-Scan → Klappe → versiegelter Sack → Weiche → Tonne → Funkmeldung → Fahrzeug.
6. **Ästhetik:** Premium-minimal in Clean-Tech-Dunkel, technische Zeichnung als Welt (Schnittdarstellung, ehrlich als Diagramm).
7. **Eine Welt oder Szenen:** Split Stage: links eine durchgehende Schnitt-Welt (sticky), rechts der akademische Text.
8. **Assets:** drei eigene 3D-Visualisierungen (aus dem Dokument), vier technische Zeichnungen (SVG). Keine generierten Bilder.

## Inhalt

Der gesamte deutsche Text des Dokuments "Smart Mülltonne Produktdesign" (Stand 14.10.2026) bleibt wörtlich erhalten. Werte, die im Prompt standen, aber dem Dokument widersprechen, folgen dem Dokument:

| Prompt | Dokument | Verwendet |
|---|---|---|
| Alarm bei 90 % | Meldung bei etwa 80 % | 80 % (`ALERT_AT` in index.html) |
| LoRaWAN | NB-IoT/LTE-M (Urban) | NB-IoT / LTE-M |
| Genauigkeit 99,4 % | "nichts ist gemessen" | 99,4 % nur als *Konfidenz eines simulierten Einwurfs*, als Simulation gekennzeichnet |
| EcoSort AI, Akzeptanzanalyse, Blue Ocean | nicht im Dokument | nicht erfunden |

## Grammatik

**Split Stage** (angepasst: "Schnitt-Bühne"). Links die Welt, rechts das Dokument. Beide Spalten tragen echten Inhalt. Navigation: Punktnavigation mit fünf Kapiteln plus Höhenlineal an der Bühnenkante. Schluss: die Bühne gibt frei, das Fazit "Wo wir stehen" nimmt die volle Breite ein.

Warum nicht die anderen: Filmic one-shot verbietet Sprungnavigation (gefordert). Continuous world verbietet Abschnitte (das Dokument hat 21). Chaptered editorial verbietet den durchgehenden Bühnen-Scrub. Live surface, Poster, Galerie, Cutlist passen nicht zu einem technischen Dokument mit Zeichnungen und Tabellen.

## Gefühlskurve

```
1  Ruhe          Sonne auf dem Solardach, Park, das Gerät steht still
2  Spannung      Flasche im Schlitz, Laser fährt über sie, Konfidenz steigt   ← PEAK
3  Schwere       Schnitt öffnet sich, der versiegelte Sack fällt durch die Weiche
4  Dringlichkeit Füllstand steigt, Puls, Funklinie zur Oberfläche, Fahrzeug kommt
5  Überblick     ganze Anlage, Business Model, ehrliche Einschätzung
```

**Peak:** "Die Seite, auf der man eine Flasche scannt, indem man scrollt." Kapitel 2, längste Spur (300 vh).

**Tell-someone:** "Es ist die Seite, auf der du dem Müll bis in die Tonne unter dem Gehweg folgst."

**Bewusste Stille:** die Kapitel-Titelkarten (je 100 dvh) rechts, während links die Kamera fährt.

## Signature Move

Scroll-gesteuerter Weg eines Gegenstands durch eine durchgehende Schnitt-Welt: Laser-Scan mit Live-Konsole (aus Daten im Code berechnet), Drehtrichter und Weiche lenken physisch, Füllstand löst Puls und Funklinie aus. Auf Touch: Schritt-Buttons und Schieberegler statt Scroll-Hijacking.

## Fingerprint

| Grammatik | Nav | Hero | Aktfolge | Schluss | Signature |
|---|---|---|---|---|---|
| Split Stage (Schnitt-Bühne) | Punktnavigation + Höhenlineal | Sticky-Schnittwelt links, Titel rechts | 5 Kapitel, 3 Spuren (300/240/260 vh) zwischen Fließtext | Bühne gibt frei, Fazit volle Breite | Müll-Weg durch Schnitt-Welt mit Scan-Konsole |
