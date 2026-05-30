# VR-AR
### **Erweiterte Beispielklausur: VR & AR (SoSe 2026)**
**Dauer:** 90 Minuten | **Gesamtpunktzahl:** ca. 100 Punkte | **Hilfsmittel:** Keine

#### **Kapitel 1: Einleitung (12 Punkte)**
1.  **Mixed-Reality-Kontinuum (3 Pkt):** Ordnen Sie AR und Augmented Virtuality (AV) in das Kontinuum nach Milgram ein. Was ist das kennzeichnende Merkmal von AV?
2.  **Immersion vs. Präsenz (2 Pkt):** Unterscheiden Sie beide Begriffe. Welcher bezieht sich auf das „Eintauchen“ durch technische Reize und welcher auf das psychologische „Daseins-Gefühl“?
3.  **Willing Suspension of Disbelief (2 Pkt):** Erklären Sie das Prinzip und nennen Sie ein Beispiel aus einem anderen Medium (z. B. Roman oder Film).
4.  **Uncanny Valley (3 Pkt):** Definieren Sie diesen Effekt. Warum werden Avatare in VR oft bewusst cartoonhaft gestaltet?
5.  **AR-Arten (2 Pkt):** Nennen Sie zwei Beispiele für unterschiedliche AR-Ansätze (z. B. markerbasiert).

#### **Kapitel 2: Menschliche Wahrnehmung (16 Punkte)**
6.  **Reafferenzprinzip (4 Pkt):** Was versteht man unter einer *Efferenzkopie*? Warum ist der Abgleich mit der *Afferenz* für eine stabile Wahrnehmung in VR wichtig?
7.  **Laterale Hemmung (3 Pkt):** Erklären Sie das Phänomen anhand der Cornsweet-Illusion oder der Mach-Bänder. Welchen biologischen Zweck erfüllt dieser Prozess?
8.  **Visuelles System (2 Pkt):** Was ist die *Fovea* und wie viel Grad des menschlichen Sichtfelds (FOV) deckt sie in etwa ab?
9.  **Weber’sches Gesetz (2 Pkt):** Wie verhält sich die wahrgenommene Änderung eines Reizes zur absoluten Intensität des Reizes?
10. **Tiefenhinweise (3 Pkt):** Unterscheiden Sie monokulare und binokulare Tiefenhinweise und nennen Sie jeweils ein Beispiel.
11. **Vergenz-Akkommodations-Konflikt (2 Pkt):** Beschreiben Sie kurz die zwei beteiligten Prozesse der Augenmuskulatur, die bei aktuellen HMDs im Konflikt stehen.

#### **Kapitel 3: Beeinträchtigende Effekte (14 Punkte)**
12. **Sensorkonflikt-Theorie (3 Pkt):** Erklären Sie die Hauptursache für Cyber Sickness (CS). Welche Rolle spielen dabei das visuelle und das vestibuläre System?
13. **Vektion (2 Pkt):** Definieren Sie diesen Begriff und geben Sie ein Beispiel aus dem Alltag (z. B. Bahnhof-Szenario).
14. **Evolutionäre Theorie (2 Pkt):** Warum reagiert unser Körper auf Sensorkonflikte oft mit Übelkeit oder Schwitzen?
15. **Bewegung & CS (2 Pkt):** Warum ist das Risiko für CS bei virtuellen Rotationen oder Beschleunigungen höher als bei konstanter geradliniger Bewegung?
16. **Rest Frame-Hypothesis (3 Pkt):** Was ist ein „Bezugsrahmen“ und wie kann ein virtuelles Cockpit helfen, CS zu reduzieren?
17. **Gegenmaßnahmen (2 Pkt):** Nennen Sie zwei technische Maßnahmen, die Entwickler ergreifen können (z. B. FOV-Einschränkung).

#### **Kapitel 4: Virtuelle Welten – Technik (14 Punkte)**
18. **3D-Rekonstruktion (3 Pkt):** Vergleichen Sie die *Photogrammetrie* mit dem *Gaussian Splatting*. Was ist ein Vorteil von Gaussian Splatting bei der Darstellung komplexer Szenen?
19. **Gaussian Splatting & KI (3 Pkt):** Warum wird dieses Verfahren oft im Kontext von KI genannt, obwohl es keine klassische KI ist? Nennen Sie zwei Aspekte (z. B. Loss-Funktion).
20. **SLAM (3 Pkt):** Wofür steht die Abkürzung? Welche zwei Aufgaben löst der Algorithmus gleichzeitig?
21. **Optimierung (3 Pkt):** Erklären Sie das Prinzip von *Level of Detail* (LOD). Warum ist dies für die Performance von VR-Anwendungen kritisch?
22. **Kollisionserkennung (2 Pkt):** Erklären Sie den Unterschied zwischen der *Broad Phase* (Bounding Boxes) und der *Narrow Phase*.

#### **Kapitel 5: Interaktion (14 Punkte)**
23. **Normans Designprinzipien (3 Pkt):** Erklären Sie die Begriffe *Affordanz* und *Signifier* im Kontext eines virtuellen Schalters.
24. **Agency (2 Pkt):** Warum erhöht die maximale Handlungsfreiheit des Nutzers die Immersion?
25. **Komfortzone im FOV (3 Pkt):** In welchem horizontalen Winkelbereich (Grad) sollten wichtige UI-Elemente idealerweise platziert werden und warum?
26. **Textlesbarkeit (3 Pkt):** Was bedeutet die Einheit *dmm*? Nennen Sie zwei Faustregeln für gut lesbaren Text in VR (z. B. Schriftart, Kontrast).
27. **Aufmerksamkeitssteuerung (3 Pkt):** Nennen Sie zwei Techniken, um den Blick des Nutzers auf ein wichtiges Objekt außerhalb des aktuellen Sichtfelds zu lenken.

#### **Kapitel 6: Hardware & Rendering-Artefakte (10 Punkte)**
28. **Latenz (3 Pkt):** Ab wie vielen Millisekunden (ms) wird Latenz in VR/AR kritisch wahrgenommen? Nennen Sie eine Ursache für Latenz.
29. **OST vs. VST (3 Pkt):** Erklären Sie den Unterschied zwischen *Optical-See-Through* und *Video-See-Through*. Nennen Sie ein Gerät als Beispiel für einen Typ.
30. **Display-Fehler (2 Pkt):** Was ist *Frame Cancellation* und wie wirkt es sich auf die Tiefenwahrnehmung aus?
31. **Pupillenabstand (2 Pkt):** Was ist der durchschnittliche IPD eines Erwachsenen und was passiert bei einer falschen Einstellung am Headset?

#### **Praktikum & Unity (10 Punkte)**
32. **Unity Basics (3 Pkt):** Welches Koordinatensystem nutzt Unity (links- oder rechtshändig)? In welche Richtung zeigt die positive Z-Achse standardmäßig?
33. **GameObjects (3 Pkt):** Welches Component besitzt *jedes* GameObject zwingend? Welche drei Transformationseigenschaften werden dort definiert?
34. **Interaktionstechniken (4 Pkt):** Erklären Sie das Prinzip des *Ray-castings* zur Selektion von Objekten.

#### **Freie Frage: Konzeption einer MR-Lösung (10 Punkte)**
35. **Szenario: „Virtueller Montage-Assistent“**
    Entwerfen Sie grob eine AR-Anwendung, die einen Mechaniker bei der Reparatur einer komplexen Maschine unterstützt.
    *   **Hardware:** Wählen Sie ein passendes Gerät (Handheld vs. Brille) und begründen Sie dies kurz mit Blick auf die Arbeitsanforderungen (z. B. freie Hände).
    *   **Registrierung:** Wie stellen Sie sicher, dass die virtuellen Pfeile exakt auf den richtigen Bauteilen der realen Maschine liegen?
    *   **Ergonomie:** Nennen Sie ein potenzielles Problem bei einer 4-stündigen Nutzung (z. B. „Gorilla Arm“ oder Erschöpfung) und schlagen Sie eine Design-Gegenmaßnahme vor.

# VR/AR Antworten

#### **Kapitel 1: Einleitung (12 Punkte)**
1. **Unterschied AR vs. AV im Milgram-Kontinuum (3 Pkt):**
    *   **AR:** Realität ist dominant, wird durch virtuelle Objekte ergänzt.
    *   **AV:** Virtuelle Umgebung ist dominant, reale Objekte werden eingebettet.
2. **Immersion vs. Präsenz (3 Pkt):**
    *   **Immersion:** Technisch/objektiv; Maß, wie gut das System Sinne anspricht (z. B. FOV, Auflösung).
    *   **Präsenz:** Psychologisch/subjektiv; das Gefühl des „Daseins“ („Being there“).
3. **Willing Suspension of Disbelief (2 Pkt):**
    *   Bereitschaft, Ungläubigkeit willentlich auszusetzen und sich trotz technischer Fehler auf Illusion einzulassen (Beispiel: Kino, Roman).
4. **Uncanny Valley (2 Pkt):**
    *   Akzeptanz sinkt stark, wenn Avatare fast wie Menschen aussehen, aber kleine Fehler im Realismus haben (wirken gruselig).
5. **XR Definition (2 Pkt):**
    *   Überbegriff für alle Umgebungen, die reale und virtuelle Elemente kombinieren (VR, AR, MR).

#### **Kapitel 2: Menschliche Wahrnehmung (15 Punkte)**
6. **Reafferenzprinzip & Efferenzkopie (4 Pkt):**
    *   **Efferenzkopie:** ZNS erstellt Vorhersage der sensorischen Folgen einer Bewegung.
    *   **Reafferenz:** Sensorische Rückmeldung der tatsächlichen Bewegung.
    *   **Abgleich:** Wenn Vorhersage ≠ Rückmeldung, wird Umweltänderung wahrgenommen (wichtig für Stabilität in VR).
7. **Laterale Hemmung (3 Pkt):**
    *   Aktive Nervenzelle hemmt Nachbarzellen zur Kontrastverstärkung.
    *   Zweck: Kanten- und Konturenerkennung (Beispiel: Mach-Bänder).
8. **Fovea & Sehschärfe (3 Pkt):**
    *   Ort der höchsten Sehschärfe auf der Netzhaut.
    *   Deckt nur ca. 2–3° des Gesichtsfeldes ab.
    *   Foveated Rendering: Nur Fokusbereich hochauflösend rendern.
9. **Monokulare Tiefenhinweise (3 Pkt):**
    *   Infos aus 2D-Bildern: Linearperspektive, Verdeckung, relative Größe, Schatten.
10. **Binokulare Disparität (2 Pkt):**
    *   Räumlicher Unterschied zwischen linkem/rechtem Augenbild.
    *   Basis für Stereosehen (Stereopsis).

#### **Kapitel 3: Beeinträchtigende Effekte (15 Punkte)**
11. **Sensorkonflikt-Theorie (3 Pkt):**
    *   Widerspruch zwischen visuellem (sieht Bewegung) und vestibulärem System (spürt keine Beschleunigung).
12. **Evolutionäre Theorie zu CS (2 Pkt):**
    *   Körper interpretiert Sensorkonflikt als Vergiftung (Halluzination) und reagiert mit Übelkeit/Erbrechen.
13. **Rest-Frame-Hypothese (3 Pkt):**
    *   Fehlender statischer Bezugsrahmen löst Übelkeit aus.
    *   Lösung: Einblendung eines Cockpits oder HUDs als Ruhepol.
14. **V-A-Konflikt (3 Pkt):**
    *   **Vergenz:** Augen „schielen“ auf virtuelles Objekt in der Tiefe.
    *   **Akkommodation:** Linse fokussiert starr auf die Displayebene.
15. **Latenzreduktion (2 Pkt):**
    *   Maßnahmen: Hohe FPS (min. 90), Polygonanzahl reduzieren, Warping (Zeitversatz-Korrektur).
16. **Frame Cancellation (2 Pkt):**
    *   Objekt mit negativer Parallaxe wird am Bildschirmrand abgeschnitten; Tiefeneindruck bricht zusammen.

#### **Kapitel 4: Virtuelle Welten – Technik (14 Punkte)**
17. **Gaussian Splatting & KI (4 Pkt):**
    *   Gradientenbasierte Optimierung/Training einer Loss-Funktion (ähnlich neuronalen Netzen).
    *   Anpassung von Millionen Gauß-Verteilungen zur 3D-Darstellung.
18. **SLAM-Algorithmus (3 Pkt):**
    *   **S**imultaneous **L**ocalization **a**nd **M**apping.
    *   Aufgaben: Zeitgleiches Bestimmen der eigenen Position und Kartieren der Umgebung.
19. **Level of Detail (LOD) (3 Pkt):**
    *   Reduzierung der Geometrie-Komplexität weit entfernter Objekte zur Performance-Steigerung.
20. **Broad Phase vs. Narrow Phase (4 Pkt):**
    *   **Broad Phase:** Grober Kollisions-Check über einfache Bounding Volumes (Boxen/Kugeln).
    *   **Narrow Phase:** Exakte Kollisionsberechnung auf Mesh-/Polygon-Ebene.

#### **Kapitel 5: Interaktion (14 Punkte)**
21. **Affordanz vs. Signifier (4 Pkt):**
    *   **Affordanz:** Angebotscharakter/mögliche Handlung (z. B. Knopf kann gedrückt werden).
    *   **Signifier:** Signal für die Handlung (z. B. Aufschrift „Drücken“ oder Leuchten).
22. **Agency (2 Pkt):**
    *   Gefühl der Selbstwirksamkeit/Kontrolle über Aktionen.
    *   Erhöht Immersion und reduziert Cyber Sickness.
23. **Komfortzone (FOV) (3 Pkt):**
    *   Wichtige UIs horizontal innerhalb von ±30° platzieren.
    *   Vermeidet unnötige Nackenbewegungen/Ermüdung.
24. **Aufmerksamkeitssteuerung – Halo (3 Pkt):**
    *   Ring um ein Off-Screen Objekt, der das Sichtfeld schneidet.
    *   Leitet Blick des Nutzers zum Ziel außerhalb des FOV.
25. **Textlesbarkeit (2 Pkt):**
    *   Nutze Einheit **dmm** (distance-independent mm).
    *   Platziere Text auf leicht konkaven Flächen.

#### **Praktikum & Unity (10 Punkte)**
26. **Unity Basics (3 Pkt):**
    *   Linkshändiges Koordinatensystem (+Z zeigt nach vorne).
    *   Jedes Objekt hat eine **Transform-Komponente**.
27. **Transform-Komponente (3 Pkt):**
    *   Eigenschaften: Position, Rotation (Orientation), Skalierung (Scale).
28. **Ray-casting (4 Pkt):**
    *   Strahl wird in Zeigerichtung „geworfen“; das erste/nächste getroffene Objekt wird selektiert.

#### **Freie Frage: Konzeption (20 Punkte)**
29. **Szenario: AR-Wartungssystem für Techniker**
    *   **Hardware (5 Pkt):** **OST-AR-Brille** (z. B. Hololens/Quest 3), da Hände frei bleiben müssen und reale Maschine sichtbar sein muss.
    *   **Registrierung (5 Pkt):** Nutzung von **Phantom-Objekten** (Z-Buffer only) zur korrekten Verdeckung realer Teile durch virtuelle Anweisungen.
    *   **Interaktion (5 Pkt):** **Kombination aus Gesten und Sprache** für freihändiges Arbeiten; **Halo-Cues** für Bauteile außerhalb des FOV.
    *   **Ergonomie-Problem (5 Pkt):** **Gorilla-Arm-Effekt** (Ermüdung durch Gesten); Lösung: Kurze Interaktionen oder Blicksteuerung nutzen.

---

