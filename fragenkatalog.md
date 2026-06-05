# KI-Kompass — Fragenkatalog für verantwortungsvolle KI-Nutzung

Ein **neutraler, anbieter- und organisationsunabhängiger** Fragenkatalog rund um die Einführung und Nutzung generativer KI in Organisationen. Er bündelt die Fragen, die typischerweise von Datenschutz, IT-Recht, Informationssicherheit und Mitbestimmung gestellt werden — und macht sichtbar, **was sich allgemein orientieren lässt** und **wo eine Entscheidung nötig ist (durch wen, mit welchem Risiko)**.

> **Hinweis:** Dieser Kompass ist eine **Orientierungshilfe, keine Rechtsberatung.** Er nimmt eine EU-Perspektive ein (DSGVO, EU AI Act) und ist bewusst prinzipienbasiert formuliert. Für verbindliche Bewertungen sind qualifizierte Datenschutz-/Rechtsexpertise und die jeweils geltende, aktuelle Rechtslage maßgeblich.

## Wozu

- **Vorbereitung** einer Datenschutz-/IT-rechtlichen Prüfung (strukturierte Fragenliste).
- **Entscheidungsfindung**: je Frage sehen, ob es eine allgemeine Orientierung gibt oder eine Entscheidung getroffen werden muss — und wer dafür zuständig ist.
- **Befähigung**: ein gemeinsames, verständliches Begriffs- und Frageraster für alle Beteiligten.

## Aufbau

`KI-Kompass_Fragenkatalog.md` enthält rund 100 Fragen in 12 Themen. Jede Frage hat:

- **Status** — *Orientierung möglich* (es gibt eine allgemein anerkannte Leitlinie) oder *Entscheidung nötig* (organisationsspezifisch zu klären).
- **Wer** — typische zuständige Rollen (abstrakt): Datenschutzbeauftragte:r (DSB), Justiziariat/IT-Recht, Informationssicherheit (ISB), Betriebsrat/Mitbestimmung, Fachbereich/Dateneigentümer, Leitung, IT-Betrieb.
- **Risiko** — was bei falscher Handhabung auf dem Spiel steht.

| Kürzel | Thema |
|---|---|
| GOV | Grundlagen & Governance |
| DSG | Datenschutz / personenbezogene Daten |
| VER | Vertraulichkeit & Geschäftsgeheimnisse |
| AVV | Auftragsverarbeitung & Anbieter |
| SPE | Persistente Speicherung: Memory, Verlauf, RAG |
| INT | Integrationen & Datenzugriff |
| AIA | EU AI Act |
| OUT | Output: Urheberrecht, Haftung, Qualität |
| MIT | Mitbestimmung & Beschäftigtendatenschutz |
| SEC | Sicherheit |
| AGE | Agentische Nutzung & Automatisierung |
| TRA | Transparenz & Kennzeichnung |

## Lizenz

Vorschlag: **CC BY 4.0** (frei nutzbar mit Namensnennung). Die finale Lizenzwahl trifft die herausgebende Organisation.

## Mitwirken

Vorschläge und Korrekturen willkommen (Pull Request). Der Katalog ist bewusst prinzipienbasiert; bitte keine anbieter- oder organisationsspezifischen Details ergänzen, damit er neutral bleibt.





# KI-Kompass — Fragenkatalog

**Orientierungshilfe, keine Rechtsberatung.** EU-Perspektive (DSGVO, EU AI Act), prinzipienbasiert und anbieterneutral. „KI-Werkzeug" meint ein generatives KI-System; „Anbieter" den Betreiber des Modells/Dienstes; „Organisation" die einsetzende Stelle.

**Legende:** Status = *Orientierung* (allgemeine Leitlinie vorhanden) oder *Entscheidung* (organisationsspezifisch zu klären). Rollen abstrakt: DSB (Datenschutz), IT-Recht, ISB (Informationssicherheit), BR (Mitbestimmung), Fachbereich, Leitung, IT-Betrieb.

---

## GOV · Grundlagen & Governance

**GOV-01 · Welche Definition von „KI" legen wir zugrunde?**
*Orientierung* — An EU AI Act / nationaler Umsetzung ausrichten; eigene Konkretisierungen nur, wo nötig. **Wer:** Leitung, IT-Recht. **Risiko:** uneinheitliches Verständnis, Fehlklassifikation.

**GOV-02 · Was ist in Scope, was nicht (z. B. Assistenz vs. automatisierte Entscheidung)?**
*Entscheidung* — **Wer:** Leitung, Fachbereich. **Risiko:** unkontrollierte Nutzung, falsche Erwartungen.

**GOV-03 · Wer ist wofür verantwortlich (Governance-Modell)?**
*Entscheidung* — Verantwortung sauber verorten (IT, Datenschutz, Sicherheit, Fachbereich, Mitbestimmung). **Wer:** Leitung. **Risiko:** diffuse Verantwortung, Lücken im Ernstfall.

**GOV-04 · Welche Werkzeuge sind freigegeben — und wie kommen neue dazu?**
*Entscheidung* — Nachvollziehbarer Freigabe-/Rolloutpfad (Steckbrief, Prüfung, Liste). **Wer:** IT-Betrieb, ISB, DSB. **Risiko:** Schatten-IT, ungeprüfte Tools.

**GOV-05 · Wie verhindern wir Schatten-KI (eigenmächtige Nutzung nicht freigegebener Tools)?**
*Orientierung* — Ein offizielles, geprüftes Angebot plus Schulung ist wirksamer als Verbote. **Wer:** Leitung, IT. **Risiko:** unkontrollierter Datenabfluss.

**GOV-06 · Welche Dokumentation müssen wir vorhalten (Nachweisbarkeit)?**
*Orientierung* — Verarbeitungsverzeichnis, Berechtigungs-/Verarbeitungskonzept, Schulungsnachweise, Entscheidungen. **Wer:** DSB, IT-Recht. **Risiko:** Rechenschaftspflicht verletzt.

**GOV-07 · Wie und wann werden Freigaben überprüft (Re-Evaluation)?**
*Entscheidung* — Auslöser definieren (wesentliche Änderung, Anbieterwechsel, neue Funktion). **Wer:** DSB, ISB. **Risiko:** veraltete Bewertung.

**GOV-08 · Wer entscheidet im Konflikt zwischen Nutzen und Risiko?**
*Entscheidung* — Eskalations-/Entscheidungsweg festlegen. **Wer:** Leitung. **Risiko:** Blockade oder unkontrollierte Freigabe.

## DSG · Datenschutz / personenbezogene Daten

**DSG-01 · Werden überhaupt personenbezogene Daten verarbeitet — und welche?**
*Entscheidung* — Datenkategorien je Anwendungsfall erfassen. **Wer:** Fachbereich, DSB. **Risiko:** unerkannte Verarbeitung.

**DSG-02 · Welche Rechtsgrundlage trägt die Verarbeitung (z. B. Art. 6 DSGVO)?**
*Entscheidung* — je Zweck zu bestimmen. **Wer:** DSB, IT-Recht. **Risiko:** rechtswidrige Verarbeitung, Bußgeld.

**DSG-03 · Sind besondere Kategorien (Art. 9) betroffen (Gesundheit, u. a.)?**
*Orientierung* — Erhöhte Anforderungen; im Zweifel vermeiden/anonymisieren. **Wer:** DSB. **Risiko:** schwerwiegender Verstoß.

**DSG-04 · Gilt der Zweckbindungsgrundsatz — werden Daten nur für den erhobenen Zweck genutzt?**
*Orientierung* — Eingabedaten dürfen nicht zweckfremd weiterverwendet werden. **Wer:** DSB, Fachbereich. **Risiko:** Zweckentfremdung.

**DSG-05 · Ist eine Datenschutz-Folgenabschätzung (Art. 35) erforderlich?**
*Entscheidung* — Schwellenwertanalyse; viele einfache Anwendungen benötigen keine, KI zur Bewertung/Interaktion mit Personen eher schon. **Wer:** DSB. **Risiko:** fehlende Pflicht-DSFA.

**DSG-06 · Wie werden Betroffenenrechte gewahrt (Auskunft, Löschung)?**
*Entscheidung* — Protokollierung und Prozesse nötig. **Wer:** DSB, IT-Betrieb. **Risiko:** nicht erfüllbare Betroffenenrechte.

**DSG-07 · Erfolgt eine Übermittlung in Drittländer — mit welchen Garantien?**
*Entscheidung* — Speicherort/Transfermechanismen prüfen. **Wer:** DSB, IT-Recht. **Risiko:** unzulässiger Drittlandtransfer.

**DSG-08 · Ist Datenminimierung umgesetzt (so wenig personenbezogene Eingaben wie möglich)?**
*Orientierung* — Vor Eingabe minimieren/anonymisieren; technische Guardrails (z. B. PII-Entfernung) erwägen. **Wer:** Fachbereich, ISB. **Risiko:** unnötige Verarbeitung.

**DSG-09 · Findet eine automatisierte Entscheidung mit Rechtswirkung statt (Art. 22)?**
*Entscheidung* — Bei Einzelentscheidungen über Personen besonders prüfen. **Wer:** DSB, IT-Recht. **Risiko:** unzulässige Automatisierung.

## VER · Vertraulichkeit & Geschäftsgeheimnisse

**VER-01 · Dürfen vertrauliche Inhalte in ein externes KI-Werkzeug eingegeben werden?**
*Entscheidung* — Nur bei vertraglicher Deckung (AVV) und Klassifizierung; sonst vermeiden/anonymisieren. **Wer:** ISB, IT-Recht, Fachbereich. **Risiko:** Verlust von Geschäftsgeheimnissen.

**VER-02 · Existiert eine Datenklassifizierung (öffentlich/intern/vertraulich)?**
*Orientierung* — Voraussetzung für klare Nutzungsregeln. **Wer:** ISB, Fachbereich. **Risiko:** Fehlbehandlung sensibler Daten.

**VER-03 · Sind durch Verträge/NDA bestimmte Inhalte von der KI-Nutzung ausgeschlossen?**
*Entscheidung* — Vertragslage prüfen (Mandanten-/Partnerdaten u. a.). **Wer:** IT-Recht, Fachbereich. **Risiko:** Vertragsbruch.

**VER-04 · Werden Eingaben des Anbieters zum Modelltraining genutzt?**
*Orientierung* — Training mit Eingaben vertraglich ausschließen. **Wer:** IT-Recht, ISB. **Risiko:** Abfluss vertraulichen Wissens ins Modell.

**VER-05 · Können vertrauliche Inhalte über Funktionen Dritter (Plugins/Connectoren) abfließen?**
*Entscheidung* — Datenflüsse je Funktion prüfen. **Wer:** ISB, DSB. **Risiko:** unkontrollierte Weitergabe.

**VER-06 · Dürfen Quellcode oder interne Systemdetails eingegeben werden?**
*Entscheidung* — Häufig sensibel; Regeln festlegen. **Wer:** ISB, Fachbereich. **Risiko:** Sicherheits-/Wettbewerbsnachteil.

**VER-07 · Wie wird Vertraulichkeit bei extern sichtbarem Output gewahrt?**
*Orientierung* — Fachliche/rechtliche Endkontrolle vor Veröffentlichung. **Wer:** Fachbereich. **Risiko:** unbeabsichtigte Offenlegung.

## AVV · Auftragsverarbeitung & Anbieter

**AVV-01 · Liegt ein Auftragsverarbeitungsvertrag (Art. 28) vor, der die Datenkategorien deckt?**
*Orientierung* — Vor Produktiveinsatz abschließen. **Wer:** DSB, IT-Recht. **Risiko:** rechtswidrige Auftragsverarbeitung.

**AVV-02 · Wo werden Daten gespeichert/verarbeitet (Region)?**
*Entscheidung* — EU-Speicherung anstreben/prüfen. **Wer:** DSB, IT-Recht. **Risiko:** Transfer-/Speicherverstoß.

**AVV-03 · Welche Unterauftragsverarbeiter setzt der Anbieter ein?**
*Entscheidung* — Liste und Garantien prüfen. **Wer:** DSB. **Risiko:** intransparente Subverarbeitung.

**AVV-04 · Welche Aufbewahrungs- und Löschfristen sichert der Anbieter zu?**
*Entscheidung* — vertraglich klären; insbesondere Logs/Verlauf. **Wer:** DSB, ISB. **Risiko:** Speicherbegrenzung verletzt.

**AVV-05 · Welche technischen/organisatorischen Maßnahmen (Art. 32) garantiert der Anbieter?**
*Orientierung* — TOMs und Zertifizierungen prüfen. **Wer:** ISB, DSB. **Risiko:** unzureichendes Schutzniveau.

**AVV-06 · Wie unterscheiden sich die Anbieter-Tarife rechtlich (z. B. AVV nur ab bestimmten Plänen)?**
*Entscheidung* — passenden Tarif wählen. **Wer:** IT-Recht, IT-Betrieb. **Risiko:** fehlende vertragliche Basis.

**AVV-07 · Wie lange werden Audit-/Compliance-Logs aufbewahrt — und exportieren wir sie?**
*Orientierung* — Bei kurzer Aufbewahrung regelmäßig exportieren. **Wer:** ISB, IT-Betrieb. **Risiko:** Nachweisverlust.

## SPE · Persistente Speicherung: Memory, Verlauf, RAG

**SPE-01 · Dürfen Informationen ohne konkreten Zweck dauerhaft vorgehalten werden (z. B. „Erinnerungen"/Memory)?**
*Orientierung* — Der Grundsatz der Speicherbegrenzung (Art. 5 Abs. 1 e DSGVO) verlangt Zweck und Frist; zweckloses Dauervorhalten vermeiden. **Wer:** DSB, ISB. **Risiko:** Speicherbegrenzung/Zweckbindung verletzt.

**SPE-02 · Welche Daten landen in persistenter „Memory"-Funktion — und wie werden sie gelöscht?**
*Entscheidung* — Inhalt, Sichtbarkeit und Löschwege klären. **Wer:** DSB, IT-Betrieb. **Risiko:** unkontrollierte Profilbildung.

**SPE-03 · Enthalten RAG-/Wissensbasen personenbezogene oder vertrauliche Inhalte?**
*Entscheidung* — Korpus inventarisieren und klassifizieren. **Wer:** Fachbereich, DSB. **Risiko:** Offenlegung über Suchtreffer.

**SPE-04 · Respektiert der Zugriff auf die Wissensbasis die Berechtigungen (ACL) der Quellsysteme?**
*Orientierung* — Retrieval muss ACL-treu filtern (Least-Privilege). **Wer:** ISB, IT-Betrieb. **Risiko:** Zugriff auf Unbefugtes.

**SPE-05 · Wie lange wird der Gesprächsverlauf gespeichert — und wer kann ihn einsehen?**
*Entscheidung* — Frist und Einsichtsrechte definieren. **Wer:** DSB, BR. **Risiko:** Verhaltensauswertung, Speicherverstoß.

**SPE-06 · Wie werden eingebettete Daten (Vektor-Index) gelöscht/aktualisiert (Recht auf Löschung)?**
*Entscheidung* — Lösch-/Reindex-Prozess vorsehen. **Wer:** IT-Betrieb, DSB. **Risiko:** „unlöschbare" Daten.

**SPE-07 · Werden gespeicherte Inhalte zweckfremd weiterverwendet (z. B. Trainings-/Analysezwecke)?**
*Orientierung* — Zweckbindung sicherstellen, Sekundärnutzung vertraglich/technisch unterbinden. **Wer:** DSB, IT-Recht. **Risiko:** Zweckentfremdung.

**SPE-08 · Wie wird Datensparsamkeit bei persistenter Speicherung umgesetzt (nur das Nötige behalten)?**
*Orientierung* — Standardmäßig wenig speichern, aktiv aufräumen. **Wer:** ISB, DSB. **Risiko:** wachsende Altdatenrisiken.

## INT · Integrationen & Datenzugriff

**INT-01 · Dürfen Funktionen wie Projekte, Erinnerungen, Aufgaben oder Verläufe aktiviert werden?**
*Entscheidung* — Je Funktion Datenfluss und Speicherung prüfen; pauschale Aktivierung vermeiden. **Wer:** ISB, DSB, BR. **Risiko:** unbeabsichtigte Dauerverarbeitung.

**INT-02 · Stellt eine neue Anbindung eine wesentliche Änderung dar (Beteiligungs-/Prüfpflicht)?**
*Orientierung* — Neue autonome Datenzugriffe sind i. d. R. wesentlich → Prüfung/Beteiligung. **Wer:** DSB, BR, ISB. **Risiko:** übergangene Mitbestimmung/Prüfung.

**INT-03 · Erbt die Anbindung die Zugriffsrechte des Nutzers (z. B. via OAuth) — sind diese belastbar?**
*Orientierung* — Das KI-Werkzeug erbt vorhandene Rechte; ein fehlerhaftes Quell-RBAC wird mitgeerbt. **Wer:** IT-Betrieb, ISB. **Risiko:** Zugriff auf Unbefugtes.

**INT-04 · Wer verantwortet das Berechtigungskonzept (RBAC) der angebundenen Quellsysteme?**
*Entscheidung* — Verantwortung benennen. **Wer:** IT-Betrieb, ISB. **Risiko:** ungesteuerte Zugriffe.

**INT-05 · Gibt es ein standardisiertes Freigabeschema für neue Connectoren?**
*Orientierung* — Einmal definieren, dann jede Anbindung gleich durchlaufen. **Wer:** ISB, DSB. **Risiko:** uneinheitliche/ad-hoc-Freigaben.

**INT-06 · Erhält das KI-Werkzeug Schreib-/Änderungsrechte oder nur Lesezugriff?**
*Orientierung* — Read-only als sicherer Einstieg. **Wer:** ISB. **Risiko:** ungewollte Datenänderung.

**INT-07 · Welche Daten verlassen die Organisation durch die Integration — und wohin?**
*Entscheidung* — Datenfluss je Integration dokumentieren. **Wer:** DSB, ISB. **Risiko:** unkontrollierter Abfluss.

**INT-08 · Wie werden Integrationen protokolliert und überwacht?**
*Orientierung* — Audit-Events und Monitoring vorsehen. **Wer:** ISB, IT-Betrieb. **Risiko:** unentdeckter Missbrauch.

## AIA · EU AI Act

**AIA-01 · In welche Risikokategorie fällt der Anwendungsfall (minimal/begrenzt/hoch/unzulässig)?**
*Entscheidung* — je Use Case einordnen. **Wer:** IT-Recht, DSB. **Risiko:** Fehlklassifikation, Sanktionen.

**AIA-02 · Liegt eine unzulässige Praktik vor (z. B. Social Scoring, bestimmte Emotionserkennung)?**
*Orientierung* — Verbotene Praktiken ausschließen. **Wer:** IT-Recht. **Risiko:** schwerwiegender Verstoß.

**AIA-03 · Bestehen Transparenzpflichten (z. B. Kennzeichnung KI-generierter Inhalte)?**
*Orientierung* — Generierte Inhalte (v. a. Medien) kennzeichnen. **Wer:** Fachbereich, IT-Recht. **Risiko:** Transparenzverstoß.

**AIA-04 · Ist eine ausreichende KI-Kompetenz der Mitarbeitenden sichergestellt (AI-Literacy-Pflicht)?**
*Orientierung* — Schulung ist verpflichtend und zu dokumentieren. **Wer:** Leitung, Fachbereich. **Risiko:** Pflichtverstoß, Haftung bei Fehlnutzung.

**AIA-05 · Welche Pflichten treffen uns als Betreiber (Deployer) vs. als Anbieter?**
*Entscheidung* — Rolle bestimmen. **Wer:** IT-Recht. **Risiko:** verkannte Pflichten.

**AIA-06 · Beim Einsatz von Allzweck-KI (GPAI): welche Hinweise/Grenzen des Anbieters gelten?**
*Orientierung* — Anbieter-Dokumentation und Nutzungsgrenzen beachten. **Wer:** IT-Recht, ISB. **Risiko:** Nutzung außerhalb zulässiger Grenzen.

**AIA-07 · Bei Hochrisiko-Anwendungen: sind menschliche Aufsicht und Dokumentation gewährleistet?**
*Entscheidung* — zusätzliche Pflichten prüfen. **Wer:** IT-Recht, DSB. **Risiko:** Nichterfüllung der Hochrisiko-Anforderungen.

## OUT · Output: Urheberrecht, Haftung, Qualität

**OUT-01 · Wem „gehört" der generierte Output — und darf er kommerziell genutzt werden?**
*Entscheidung* — Anbieterbedingungen prüfen. **Wer:** IT-Recht. **Risiko:** unklare/fehlende Nutzungsrechte.

**OUT-02 · Verletzt generierter Output Rechte Dritter (Marken, geschützte Werke)?**
*Orientierung* — Keine realen Personen/Marken/geschützten Werke; prüfen. **Wer:** Fachbereich, IT-Recht. **Risiko:** Rechtsverletzung.

**OUT-03 · Sind verwendete Bilder lizenziert (Generierung vs. Bildersuche)?**
*Orientierung* — Nur lizenzfrei/lizenziert; Quelle/Lizenz dokumentieren. **Wer:** Fachbereich. **Risiko:** Urheberrechtsverstoß.

**OUT-04 · Wer haftet, wenn auf Basis fehlerhaften Outputs entschieden wird?**
*Orientierung* — Menschliche Letztverantwortung; KI ist Assistenz. **Wer:** Leitung, Fachbereich. **Risiko:** Fehlentscheidung, Haftung.

**OUT-05 · Wie wird mit Halluzinationen/Faktenfehlern umgegangen?**
*Orientierung* — Verpflichtende Endkontrolle/Faktencheck. **Wer:** Fachbereich. **Risiko:** Verbreitung falscher Inhalte.

**OUT-06 · Wann ist menschliche Qualitätssicherung verpflichtend (je nach Außenwirkung)?**
*Entscheidung* — Schwellen festlegen (intern/extern). **Wer:** Fachbereich, Leitung. **Risiko:** ungeprüfte Außenwirkung.

**OUT-07 · Bei generiertem Code: erfolgt Review vor Produktiveinsatz?**
*Orientierung* — Code-Review und Lizenz-/Security-Check Pflicht. **Wer:** IT-Betrieb, ISB. **Risiko:** unsicherer/lizenzwidriger Code.

## MIT · Mitbestimmung & Beschäftigtendatenschutz

**MIT-01 · Ermöglicht das Werkzeug Leistungs- oder Verhaltenskontrolle der Beschäftigten?**
*Orientierung* — Verdeckte Kontrolle ausschließen; Mitbestimmung beachten. **Wer:** BR, DSB. **Risiko:** Mitbestimmungsverstoß.

**MIT-02 · Ist die Einführung mitbestimmungspflichtig (Beteiligung der Personalvertretung)?**
*Orientierung* — Häufig ja; frühzeitig beteiligen. **Wer:** BR, Leitung. **Risiko:** unwirksame Einführung.

**MIT-03 · Werden Beschäftigtendaten verarbeitet — auf welcher Grundlage?**
*Entscheidung* — Rechtsgrundlage/Regelung klären. **Wer:** DSB, BR. **Risiko:** unzulässige Verarbeitung.

**MIT-04 · Lassen Nutzungs-/Verlaufsdaten Rückschlüsse auf einzelne Beschäftigte zu?**
*Entscheidung* — Auswertungen begrenzen, ggf. anonymisieren. **Wer:** DSB, BR. **Risiko:** Profilbildung.

**MIT-05 · Regelt eine Betriebs-/Dienstvereinbarung die KI-Nutzung — und was deckt sie ab?**
*Orientierung* — Technologieoffen mit klaren Grenzen; wesentliche Änderungen über Beteiligung. **Wer:** BR, Leitung. **Risiko:** Regelungslücke.

**MIT-06 · Ist die Nutzung freiwillig, und gibt es Schutz vor Sanktionen bei Nichtnutzung?**
*Entscheidung* — Rahmen festlegen. **Wer:** Leitung, BR. **Risiko:** Druck/Akzeptanzprobleme.

## SEC · Sicherheit

**SEC-01 · Wie wird Prompt Injection / Manipulation begegnet?**
*Orientierung* — Tests (inkl. Red-Team), Eingaben/Quellen kontrollieren. **Wer:** ISB. **Risiko:** Manipulation, Datenabfluss.

**SEC-02 · Können Zugangsdaten/Secrets in Eingaben gelangen — wie wird das verhindert?**
*Orientierung* — Keine Secrets in Prompts; technische Filter. **Wer:** ISB. **Risiko:** Kompromittierung.

**SEC-03 · Wird ungeprüfter, KI-erzeugter Code/Inhalt ausgeführt?**
*Orientierung* — Sandbox/Review vor Ausführung. **Wer:** ISB, IT-Betrieb. **Risiko:** Schadcode.

**SEC-04 · Werden sicherheitsrelevante Ereignisse protokolliert (Audit)?**
*Orientierung* — Audit-Trail vorsehen. **Wer:** ISB. **Risiko:** keine Nachvollziehbarkeit.

**SEC-05 · Wie wird ein Datenabfluss über das Werkzeug erkannt und verhindert (DLP)?**
*Entscheidung* — Maßnahmen festlegen. **Wer:** ISB. **Risiko:** unentdeckter Abfluss.

**SEC-06 · Greifen Identitäts-/Zugriffsmanagement (IAM) und Least-Privilege?**
*Orientierung* — Zentrale Identitäten, minimale Rechte. **Wer:** ISB, IT-Betrieb. **Risiko:** Rechteausweitung.

## AGE · Agentische Nutzung & Automatisierung

**AGE-01 · Darf das Werkzeug eigenständig Aktionen ausführen (über reines Antworten hinaus)?**
*Entscheidung* — Autonomiegrad und erlaubte Aktionen festlegen. **Wer:** ISB, Fachbereich. **Risiko:** unkontrollierte Aktionen.

**AGE-02 · Welche Aktionen erfordern eine menschliche Bestätigung (Human-in-the-Loop)?**
*Entscheidung* — Schwellen je Risiko definieren. **Wer:** Fachbereich, ISB. **Risiko:** folgenreiche Fehlhandlung.

**AGE-03 · Dürfen geplante/wiederkehrende Aufgaben (Automatisierungen) laufen — mit welchen Grenzen?**
*Entscheidung* — Zweck, Daten und Frequenz prüfen. **Wer:** ISB, DSB. **Risiko:** unbeaufsichtigte Dauerverarbeitung.

**AGE-04 · Wie werden Werkzeuge/Tools eines Agenten freigegeben und mit Risikostufen versehen?**
*Orientierung* — Tool-Katalog mit Risk-Tier und Policy-Prüfung. **Wer:** ISB. **Risiko:** unkontrollierte Tool-Nutzung.

**AGE-05 · Wie werden agentische Abläufe nachvollziehbar protokolliert?**
*Orientierung* — Schritt-/Tool-Logs und Quellen. **Wer:** ISB. **Risiko:** fehlende Nachvollziehbarkeit.

**AGE-06 · Wer trägt die Verantwortung für Handlungen eines Agenten?**
*Orientierung* — Verantwortung bleibt beim Menschen/der Organisation. **Wer:** Leitung. **Risiko:** Verantwortungslücke.

## TRA · Transparenz & Kennzeichnung

**TRA-01 · Werden KI-generierte Inhalte als solche gekennzeichnet?**
*Orientierung* — Kennzeichnung, insbesondere bei Medien/Außenwirkung. **Wer:** Fachbereich. **Risiko:** Täuschung, Transparenzverstoß.

**TRA-02 · Werden Beschäftigte über Art und Umfang der KI-Nutzung informiert?**
*Orientierung* — Transparente Information vorsehen. **Wer:** Leitung, BR. **Risiko:** Vertrauensverlust, Pflichtverstoß.

**TRA-03 · Werden Betroffene informiert, wenn sie mit KI interagieren?**
*Orientierung* — Interaktion mit KI offenlegen. **Wer:** Fachbereich, DSB. **Risiko:** Transparenzverstoß.

**TRA-04 · Sind Quellen/Fundstellen im Output nachvollziehbar?**
*Orientierung* — Quellen mitliefern (Nachprüfbarkeit). **Wer:** Fachbereich. **Risiko:** nicht überprüfbare Aussagen.

**TRA-05 · Gibt es klare, verständliche Nutzungsregeln und Beispiele für Mitarbeitende?**
*Orientierung* — Konkrete Beispiele („erlaubt/mit Auflagen/untersagt") statt abstrakter Regeln. **Wer:** Fachbereich, DSB. **Risiko:** Unsicherheit, Fehlnutzung.

**TRA-06 · Ist geregelt, wie Output vor externer Veröffentlichung geprüft wird?**
*Orientierung* — Fachliche und ggf. rechtliche QS. **Wer:** Fachbereich, IT-Recht. **Risiko:** fehlerhafte Veröffentlichung.

---

*Dieser Katalog ist bewusst prinzipienbasiert und nicht abschließend. Er ersetzt keine Einzelfallprüfung durch qualifizierte Datenschutz-/Rechtsexpertise.*
