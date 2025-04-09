# Leitfaden: Vom Projektbericht/Thesis zum wissenschaftlichen Paper

*Zusammengestellt von Julian Rosenberger ([julian.rosenberger@ur.de](mailto:julian.rosenberger@ur.de)), basierend auf Erfahrungen und häufigem Feedback in der White-box AI Forschungsgruppe.*

---

**Ziel:** Dieser Leitfaden soll Studierenden helfen, ihre Ergebnisse aus Projektarbeiten oder Abschlussarbeiten erfolgreich in Form eines wissenschaftlichen Papers (z.B. für Konferenzen wie die WI oder Journals) aufzubereiten. Er basiert auf häufigem Feedback und typischen Herausforderungen.

**1. Grundstruktur eines wissenschaftlichen Papers**

Ein typisches Paper folgt einer etablierten Struktur, die dem Leser hilft, die Arbeit nachzuvollziehen:

* **Abstract:** Kurze Zusammenfassung (Problem, Methode, wichtigste Ergebnisse, Implikation).
* **Introduction:** Hinführung zum Thema, Motivation, Problemstellung, Forschungsfragen, kurzer Überblick über den Ansatz und die wichtigsten Beiträge/Ergebnisse, Struktur des Papers.
* **Related Work:** Einordnung der Arbeit in den Forschungsstand, Abgrenzung zu bestehenden Arbeiten, Aufzeigen der Forschungslücke.
* **Methods/Methodology:** Detaillierte Beschreibung des Vorgehens (Datenerhebung, -aufbereitung, Modellentwicklung, Evaluationsmethoden), sodass die Arbeit replizierbar ist.
* **Results:** Präsentation der Ergebnisse der Analysen (z.B. Modellperformances, statistische Auswertungen, Visualisierungen) – noch ohne tiefgehende Interpretation.
* **Discussion:** Interpretation der Ergebnisse, Beantwortung der Forschungsfragen, Vergleich der Ergebnisse mit dem Related Work, Diskussion von Implikationen (theoretisch/praktisch), kritische Reflexion und Limitationen der Arbeit.
* **Conclusion:** Kurze Zusammenfassung der wichtigsten Erkenntnisse und Ausblick auf zukünftige Forschung.
* **References:** Literaturverzeichnis.
* **(Optional) Appendix:** Zusätzliches Material (z.B. detaillierte Plots, Fragebögen).

**2. Häufige Fallstricke & Best Practices**

Basierend auf typischem Feedback gibt es einige Bereiche, auf die **ihr** besonders achten solltet:

**a) Struktur & Logischer Fluss:**

* **Klare Trennung:** Haltet die Abschnitte (insbesondere Methods, Results, Discussion) klar getrennt. Vermeidet es, Ergebnisse in der Methodik vorwegzunehmen oder Methoden erst in der Diskussion zu erklären.
* **Roter Faden:** Sorgt für einen klaren Argumentationsfluss innerhalb der Abschnitte und zwischen ihnen. Die Introduction sollte klar machen, wohin die Reise geht, und die Discussion sollte die in der Introduction aufgeworfenen Fragen beantworten.
* **Beitrag klarstellen:** Formuliert explizit (oft am Ende der Introduction), was der einzigartige Beitrag eurer Arbeit zur Forschung ist (z.B. neue Methode, neue empirische Erkenntnisse, neue Theorie).
* **Related Work:** Strukturiert das Related Work thematisch oder chronologisch, nicht als lose Aneinanderreihung von Studien. Zeigt klar die Forschungslücke auf, die eure Arbeit adressiert.

**b) Klarheit & Präzision:**

* **Motivation:** Macht von Anfang an klar, *warum* das Thema relevant ist und welches spezifische Problem **ihr** löst.
* **Terminologie:** Definiert zentrale Begriffe und verwendet sie präzise und konsistent.
* **Methodenbeschreibung:** Beschreibt euer Vorgehen so detailliert, dass es nachvollziehbar und idealerweise replizierbar ist. Begründet methodische Entscheidungen (z.B. Wahl eines bestimmten Algorithmus oder einer Metrik).
* **Datenaufbereitung:** Erklärt genau, wie die Daten erhoben, gefiltert und vorverarbeitet wurden. Unklare Angaben hier führen oft zu Interpretationsproblemen bei den Ergebnissen.
* **Vermeidet Jargon (wo möglich):** Schreibt klar und verständlich, auch für Leser, die nicht tief in *exakt* eurem Spezialgebiet stecken.

**c) Konsistenz:**

* **Abkürzungen:** Definiert jede Abkürzung bei der ersten Verwendung und nutzt sie dann einheitlich.
* **Formatierung:** Achtet auf einheitliche Formatierung von Zahlen (Dezimalstellen, Tausendertrennzeichen), Überschriften, Tabellen- und Abbildungsbeschriftungen.
* **Labels & Bezeichnungen:** Verwendet für dieselben Konzepte (z.B. Topic-Labels, Variablennamen) immer exakt dieselben Bezeichnungen im Text, in Tabellen und Abbildungen.
* **Übersetzungen:** Stellt sicher, dass spezifische Begriffe (Eigennamen, Positionen etc.) korrekt und einheitlich ins Englische (oder die Zielsprache des Papers) übersetzt werden.

**d) Wissenschaftliche Sorgfalt & Rigor:**

* **Metriken:** Wählt Evaluationsmetriken, die zur Aufgabe passen (z.B. Genauigkeit/Accuracy ist bei unbalancierten Klassen oft irreführend -> F1-Score, AUROC prüfen). Begründet eure Wahl.
* **Begriff "Signifikanz":** Verwendet "significant" nur, wenn ihr tatsächlich statistische Signifikanztests durchgeführt und deren Ergebnisse berichtest. Ansonsten nutzt beschreibende Worte ("substantial", "noticeable", "remarkable", "high").
* **Belege:** Jede Behauptung oder Interpretation sollte durch Daten (aus euren Results), Referenzen (Related Work) oder logische Argumentation gestützt sein. Fügt alle notwendigen Quellen an.
* **Limitationen:** Jede Studie hat Grenzen. Diskutiert diese offen und ehrlich. Das zeigt wissenschaftliche Reife. Erklärt, wie sie die Ergebnisse beeinflussen könnten.

**e) Einordnung in den Forschungsstand:**

* **Positionierung:** Macht im Related Work klar, wie sich eure Arbeit von bestehender Forschung unterscheidet und welche Lücke sie füllt.
* **Diskussion:** Vergleicht eure *konkreten Ergebnisse* in der Diskussion mit den Ergebnissen relevanter Studien aus dem Related Work. Wo gibt es Übereinstimmungen, wo Widersprüche? Was bedeutet das? (Dieser Punkt fehlt oft!)
* **Quellenqualität:** Achtet bei der Literaturrecherche und Zitation auf hochwertige und relevante Quellen. Im IS-Bereich orientiert euch idealerweise an Top-Journals (z.B. "Basket of Eight", FT50) und führenden Konferenzen (z.B. ICIS, ECIS, WI, AMCIS, PACIS, HICSS) sowie ACM-Quellen. Wenn ihr Preprints (z.B. von arXiv) findet, prüft immer, ob bereits eine begutachtete Version in einem Journal oder Konferenzband erschienen ist und zitiert diese.

**f) Präsentation von Daten (Tabellen & Abbildungen):**

* **Professionalität:** Erstellt Grafiken und Tabellen in hoher Qualität (keine unscharfen Screenshots). Achtet auf Lesbarkeit (Schriftgrößen in Legenden/Achsen!).
* **Informationsgehalt:** Jede Tabelle und Abbildung sollte für sich verständlich sein (aussagekräftige Caption, Legende, Achsenbeschriftungen, Einheiten).
* **Vollständigkeit:** Zeigt alle relevanten Informationen (z.B. alle wichtigen Metriken in Ergebnistabellen).
* **Barrierearmut:** Denkt an Farbfehlsichtigkeit (vermeidet reine Rot/Grün-Unterscheidungen) und gute Kontraste.

**g) Vollständigkeit & Transparenz:**

* **Alle Infos:** Stellt sicher, dass alle nötigen Details genannt sind (z.B. Größe von Datensets/Subsets, Details zur Hyperparameteroptimierung, Infos zum Labeling-Prozess inkl. Inter-Annotator Agreement, falls relevant).
* **Quellen:** Zitiert alle verwendeten Quellen korrekt und vollständig.
* **Code/Daten teilen (optional, aber empfohlen):** Wenn möglich, stellt Code und Daten zur Verfügung (z.B. über GitHub) und verweist im Paper darauf. Das erhöht die Transparenz und Nachnutzbarkeit.

**h) Projektmanagement & Teamarbeit:**

* **Klare Rollen:** Besonders bei Gruppenarbeiten ist eine klare Rollenverteilung wichtig. Bestimmt EINE/N Hauptverantwortliche/n ("Lead"), oft die/der Erstautor/in.
* **Koordination:** Die Lead-Person sollte die Arbeitspakete verteilen, den Überblick über das Gesamtprojekt behalten ("das große Ganze") und als zentrale Ansprechperson für die Betreuenden fungieren.
* **Kommunikation:** Regelmäßige Absprachen im Team und mit den Betreuenden sind entscheidend, um auf Kurs zu bleiben und Probleme frühzeitig zu erkennen.

**i) Akademischer Schreibstil & Korrekturlesen:**

* **Stil:** Achtet auf einen präzisen, sachlichen und formalen Schreibstil. Vermeidet Umgangssprache. Baut klare, verständliche Sätze.
* **Korrekturlesen:** Lasst das Paper unbedingt von mehreren Personen (auch außerhalb eures Teams/Fachgebiets) Korrektur lesen, um Tipp-, Grammatik- und Verständlichkeitsfehler zu finden. Plant dafür ausreichend Zeit ein!

**j) Ethische Aspekte:**

* **Plagiat:** Vermeidet Plagiate unter allen Umständen durch korrektes Zitieren und Paraphrasieren. Nutzt ggf. Plagiatssoftware zur Überprüfung.
* **Datenschutz:** Wenn ihr mit personenbezogenen Daten arbeitet, beachtet strikt die Datenschutzgrundverordnung (DSGVO) und anonymisiert/pseudonymisiert Daten entsprechend.
* **Ethikvotum:** Bei Forschungsvorhaben, die menschliche Teilnehmer involvieren (Umfragen, Interviews, Experimente), kann ein positives Votum einer Ethikkommission (IRB Approval) notwendig sein. Klärt dies frühzeitig mit euren Betreuenden.

**k) Zielgruppe & Outlet:**

* **Anpassung:** Berücksichtigt die Zielgruppe und die spezifischen Anforderungen des Ziel-Outlets (Konferenz/Journal).
* **Vorgaben:** Beachtet Seitenlimits, Formatierungsvorgaben (Templates!), Einreichungsfristen und den thematischen Fokus des Outlets. Passt Sprache und Detailgrad eures Papers entsprechend an.

**3. Kurze Checkliste für Studierende**

* Ist die Struktur klar und logisch? Sind die Abschnitte sauber getrennt?
* Ist die Motivation klar? Ist die Forschungsfrage präzise? Ist der Beitrag klar formuliert?
* Ist die Methodik detailliert und nachvollziehbar beschrieben? Sind Entscheidungen begründet?
* Sind alle Begriffe definiert und konsistent verwendet?
* Sind Abkürzungen korrekt eingeführt und einheitlich genutzt?
* Sind Formatierungen (Zahlen, Überschriften etc.) konsistent?
* Sind die Evaluationsmetriken passend und begründet?
* Wird "signifikant" korrekt verwendet?
* Sind alle Behauptungen belegt (Daten, Quellen)?
* Werden die Ergebnisse in der Diskussion mit dem Related Work verglichen? Sind hochwertige Quellen zitiert?
* Sind Tabellen und Abbildungen professionell, verständlich und vollständig?
* Sind Limitationen ehrlich diskutiert? Sind ethische Aspekte berücksichtigt?
* Sind alle Quellen angegeben? Ist Code/Daten-Verfügbarkeit erwähnt?
* Gibt es eine klare Projektleitung und regelmäßige Kommunikation im Team/mit Betreuenden?
* Ist der Schreibstil angemessen? Wurde gründlich Korrektur gelesen?
* Sind die Vorgaben des Ziel-Outlets berücksichtigt?

**4. Fazit**

Der Weg von einem Projektbericht oder einer Thesis zu einem guten wissenschaftlichen Paper erfordert oft eine andere Denkweise und Strukturierung. Achtet auf die oben genannten Punkte, holt euch frühzeitig Feedback und plant genug Zeit für Überarbeitungen ein. Viel Erfolg!
