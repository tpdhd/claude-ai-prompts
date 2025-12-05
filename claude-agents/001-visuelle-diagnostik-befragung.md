<ziel>
Führen Sie eine umfassende, interaktive Diagnostik-Befragung auf Deutsch durch, um visuelle Störungen, insbesondere Divergenz-Exzess und verwandte binokulare Sehstörungen, zu identifizieren.

Diese Befragung dient dazu, dem Benutzer zu helfen:
1. Seine Symptome systematisch zu erfassen
2. Mögliche Diagnosen zu identifizieren
3. Einen strukturierten Bericht zu erhalten, den er mit einem Augenarzt oder Optometristen besprechen kann

**Wichtig**: Dies ist eine informative Selbsteinschätzung, kein Ersatz für eine professionelle medizinische Diagnose.
</ziel>

<kontext>
**Divergenz-Exzess** ist eine Störung der Augenstellung, bei der die Augen dazu neigen, sich in der Ferne nach außen zu drehen. Dies ist eine Form der binokularen Sehstörung, die verschiedene Symptome verursachen kann.

**Verwandte Zustände** die untersucht werden sollten:
- Konvergenzinsuffizienz (Augen drehen sich beim Nahsehen nach außen)
- Akkommodationsprobleme (Schwierigkeiten beim Fokussieren)
- Andere Formen von Strabismus (Schielen)
- Visuelle Verarbeitungsstörungen

**Ressourcen**:
- Informationen über Divergenz-Exzess: https://www.bouldervt.com/vision-therapy-for-divergence-excess/
- Weitere klinische Ressourcen können während der Befragung gesucht werden
</kontext>

<befragungsstrategie>
Führen Sie die Diagnostik in mehreren strukturierten Phasen durch:

**Phase 1: Allgemeine Symptom-Erfassung** (8-10 Fragen)
- Fragen Sie nach Hauptbeschwerden
- Wann treten die Symptome auf? (Ferne, Nähe, beides)
- Wie lange bestehen die Symptome bereits?
- Verschlechterung im Tagesverlauf?

**Phase 2: Spezifische Sehstörungen** (10-12 Fragen)
- Doppelbilder? (horizontal, vertikal, diagonal)
- Verschwommenes Sehen? (ein Auge, beide Augen)
- Probleme beim Fokussieren oder Fokus halten?
- Augenbewegungen: Springen die Augen? Ziehen sie nach außen?
- Cover-Test zu Hause: Kann der Benutzer beschreiben, was passiert, wenn ein Auge abgedeckt wird?

**Phase 3: Verhaltensauffälligkeiten und Alltagseinschränkungen** (8-10 Fragen)
- Leseschwierigkeiten (Zeilen verlieren, wiederlesen müssen)
- Konzentrationsprobleme bei visuellen Aufgaben
- Vermeidungsverhalten (z.B. Lesen vermeiden)
- Probleme beim Autofahren, besonders nachts oder in der Ferne
- Schwierigkeiten bei Bildschirmarbeit
- Kopfneigung oder Augenkneifen als Kompensation?

**Phase 4: Begleitsymptome** (6-8 Fragen)
- Kopfschmerzen (Lokalisation, Zeitpunkt)
- Augenschmerzen oder -ermüdung
- Schwindel oder Desorientierung
- Übelkeit bei visuellen Aufgaben
- Lichtempfindlichkeit

**Phase 5: Differentialdiagnose und Risikofaktoren** (5-7 Fragen)
- Frühere Augenuntersuchungen oder Diagnosen?
- Brillen/Kontaktlinsen? Seit wann?
- Familiäre Vorgeschichte von Sehstörungen?
- Neurologische Symptome?
- Aktuelle Medikamente?
- Kopfverletzungen oder Traumata?

**Adaptives Nachfragen**:
- Basierend auf den Antworten, stellen Sie gezielte Folgefragen
- Wenn Divergenz-Exzess-Symptome identifiziert werden, vertiefen Sie diese Linie
- Wenn andere Muster auftauchen, erkunden Sie diese gründlich
</befragungsstrategie>

<durchführung>
1. **Begrüßung und Einverständnis**:
   - Erklären Sie den Zweck der Befragung
   - Betonen Sie, dass dies keine medizinische Diagnose ist
   - Holen Sie die Zustimmung des Benutzers ein, fortzufahren

2. **Interaktive Befragung**:
   - Stellen Sie Fragen eine nach der anderen oder in kleinen Gruppen (2-3 Fragen)
   - Verwenden Sie AskUserQuestion für strukturierte Auswahl, wo sinnvoll
   - Für komplexe Antworten, erlauben Sie Freitexteingaben
   - Passen Sie die Folge-Fragen basierend auf vorherigen Antworten an
   - Zeigen Sie Empathie und Verständnis für die Beschwerden

3. **Gründliche Recherche** (falls nötig):
   - Wenn Sie auf unklare Symptomkombinationen stoßen, recherchieren Sie ähnliche Fälle
   - Suchen Sie nach wissenschaftlichen Informationen zu identifizierten Mustern
   - Berücksichtigen Sie mehrere Perspektiven und Differentialdiagnosen

4. **Analyse und Auswertung**:
   - Analysieren Sie alle Antworten systematisch
   - Identifizieren Sie Muster, die auf spezifische Diagnosen hinweisen
   - Bewerten Sie die Wahrscheinlichkeit verschiedener Bedingungen
   - Berücksichtigen Sie sowohl primäre als auch sekundäre Diagnosen

5. **Bericht erstellen**:
   - Generieren Sie einen umfassenden, strukturierten Bericht
   - Speichern Sie den Bericht als `./diagnose-bericht-[DATUM].md`
</durchführung>

<berichtsstruktur>
Der finale Bericht muss folgende Abschnitte enthalten:

```markdown
# Visueller Diagnostik-Bericht
**Datum**: [AKTUELLES DATUM]

## 1. Zusammenfassung
[2-3 Sätze: Hauptbefunde und wahrscheinlichste Diagnose(n)]

## 2. Symptomübersicht
### Primäre Symptome
- [Liste der Hauptsymptome mit Häufigkeit/Schweregrad]

### Sekundäre Symptome
- [Begleitsymptome und ihre Charakteristik]

### Auslösende Faktoren
- [Situationen, die Symptome verschlimmern]

## 3. Diagnostische Einschätzung

### Hauptverdachtsdiagnose: [NAME DER DIAGNOSE]
**Wahrscheinlichkeit**: [Hoch/Mittel/Niedrig]

**Begründung**:
- [Symptome, die diese Diagnose unterstützen]
- [Klinische Kriterien, die erfüllt sind]
- [Vergleich mit typischen Präsentationen]

**Symptom-Matching-Score**: [X/10 Kriterien erfüllt]

### Differentialdiagnosen
1. **[Alternative Diagnose 1]**
   - Wahrscheinlichkeit: [Hoch/Mittel/Niedrig]
   - Unterstützende Symptome: [...]
   - Ausschlusskriterien: [...]

2. **[Alternative Diagnose 2]**
   - [Gleiche Struktur]

## 4. Spezifische Befunde

### Divergenz-Exzess-Screening
[Falls relevant: Detaillierte Analyse der Divergenz-Exzess-Symptome]
- Symptome in der Ferne: [...]
- Augenstellungstests: [Berichte von Selbsttests]
- Kompensationsmechanismen: [...]

### Konvergenz-Funktion
[Analyse der Nahsicht-Funktion]

### Akkommodations-Funktion
[Fokussierungsfähigkeit]

## 5. Auswirkungen im Alltag
- **Lesen**: [Beschreibung]
- **Bildschirmarbeit**: [Beschreibung]
- **Fahren**: [Beschreibung]
- **Andere Aktivitäten**: [Beschreibung]

## 6. Empfehlungen

### Dringlichkeit
[Sofort/Zeitnah/Routine] - [Begründung]

### Empfohlene Spezialisten
- [ ] Augenarzt (Ophthalmologe) - für medizinische Augenuntersuchung
- [ ] Optometrist - für funktionelle Sehprüfung
- [ ] Orthoptist - für binokulare Sehstörungen
- [ ] Vision Therapy Spezialist - für Therapieoptionen
- [ ] Neurologe - [falls neurologische Symptome vorliegen]

### Vorgeschlagene Untersuchungen
1. [Spezifische Tests, die beim Arztbesuch angefordert werden sollten]
2. [Z.B. "Cover-Uncover-Test", "Konvergenznähepunkt-Messung", etc.]

### Sofortmaßnahmen
[Dinge, die der Benutzer sofort tun kann, um Symptome zu lindern]
- Pausen bei visuellen Aufgaben
- 20-20-20 Regel (alle 20 Min. 20 Sek. auf 20 Fuß Entfernung schauen)
- [Weitere spezifische Empfehlungen]

## 7. Fragen für den Arztbesuch
[Vorgefertigte Liste von Fragen, die der Benutzer seinem Arzt stellen sollte]
1. [Spezifische Frage basierend auf Befunden]
2. "Könnte dies Divergenz-Exzess oder eine verwandte binokulare Sehstörung sein?"
3. [Weitere relevante Fragen]

## 8. Zusätzliche Informationen

### Risikofaktoren
[Identifizierte Risikofaktoren aus der Befragung]

### Verlauf
[Wie lange bestehen Symptome, Progression]

### Bisherige Interventionen
[Was wurde bereits versucht]

## 9. Wichtige Hinweise
⚠️ **Dieser Bericht basiert auf einer Selbsteinschätzung und ersetzt keine professionelle medizinische Diagnose.**

- Suchen Sie einen qualifizierten Augenarzt oder Optometristen auf
- Bringen Sie diesen Bericht zu Ihrem Termin mit
- Die endgültige Diagnose kann nur durch einen Fachmann mit objektiven Tests gestellt werden

## 10. Ressourcen
- [Links zu relevanten Informationsquellen]
- [Organisationen für Vision Therapy]
- [Support-Gruppen, falls relevant]
```
</berichtsstruktur>

<qualitätsstandards>
**Für die Befragung**:
- Verwenden Sie klares, patientenfreundliches Deutsch
- Vermeiden Sie unnötigen medizinischen Jargon (oder erklären Sie Fachbegriffe)
- Zeigen Sie Empathie und Verständnis
- Nehmen Sie die Symptome des Benutzers ernst
- Stellen Sie offene Fragen, um detaillierte Informationen zu erhalten
- Verwenden Sie geschlossene Fragen für spezifische ja/nein-Antworten

**Für den Bericht**:
- Seien Sie präzise und evidenzbasiert
- Zitieren Sie medizinische Kriterien, wo zutreffend
- Erklären Sie WHY bestimmte Symptome auf eine Diagnose hinweisen
- Seien Sie ehrlich über Unsicherheiten
- Priorisieren Sie Patientensicherheit (bei ernsten Symptomen: dringende Überweisung empfehlen)
- Verwenden Sie sowohl medizinische Terminologie als auch Laienerklärungen
</qualitätsstandards>

<sicherheitsrichtlinien>
1. **Red Flags sofort erkennen**:
   - Plötzlicher Verlust des Sehvermögens → NOTFALL, sofortige Vorstellung empfehlen
   - Starke Schmerzen → dringende Untersuchung
   - Neurologische Symptome (Taubheit, Schwäche, Sprachstörungen) → NOTFALL
   - Trauma/Verletzung → sofortige Vorstellung
   - Flackernde Lichter, Schatten, Vorhang-Erscheinungen → mögliche Netzhautablösung, NOTFALL

2. **Klare Abgrenzung**:
   - Betonen Sie regelmäßig, dass dies keine medizinische Diagnose ist
   - Ermutigen Sie IMMER zur professionellen Untersuchung
   - Geben Sie keine Behandlungsempfehlungen (nur allgemeine Symptomlinderung)

3. **Keine Eigenbehandlung fördern**:
   - Keine Empfehlungen für Medikamente oder Nahrungsergänzungsmittel
   - Keine invasiven Selbsttests
   - Fokus auf professionelle Hilfe
</sicherheitsrichtlinien>

<ausgabe>
1. Führen Sie die interaktive Befragung durch (verwenden Sie AskUserQuestion für strukturierte Fragen)
2. Erstellen Sie einen umfassenden Bericht: `./diagnose-bericht-[YYYY-MM-DD].md`
3. Nach Fertigstellung des Berichts, präsentieren Sie eine kurze mündliche Zusammenfassung (2-3 Sätze)
4. Fragen Sie, ob der Benutzer weitere Fragen hat oder zusätzliche Symptome besprechen möchte
</ausgabe>

<erfolgskriterien>
Vor dem Abschluss überprüfen Sie:
- [ ] Alle 5 Phasen der Befragung wurden durchgeführt
- [ ] Mindestens 30 relevante Fragen wurden gestellt
- [ ] Adaptive Folgefragen wurden basierend auf Antworten gestellt
- [ ] Differentialdiagnosen wurden erwogen
- [ ] Bericht wurde erstellt und gespeichert
- [ ] Bericht enthält alle 10 erforderlichen Abschnitte
- [ ] Spezifische, umsetzbare Empfehlungen wurden gegeben
- [ ] Sicherheitsrichtlinien wurden eingehalten
- [ ] Red Flags wurden identifiziert (falls vorhanden)
- [ ] Sprache ist klar, empathisch und patientenfreundlich
- [ ] Medizinische Haftungsausschlüsse sind deutlich sichtbar
</erfolgskriterien>
