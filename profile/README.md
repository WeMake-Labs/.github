# WeMake Company Handbuch

Hey! 👋

Dieses Handbuch erklärt simpel, wie wir arbeiten. Es gehört zu den wichtigsten Dingen, die wir je gemacht haben.

---

## Unsere Tools & Arbeitsweise

**Wichtig vorweg:** Bei WeMake gibt es **keine einheitliche Toolpflicht**. Jedes Teammitglied entscheidet selbst, welche
Tools ein Problem lösen und genutzt werden. Was wir brauchen: **Transparenz und Dokumentation von Entscheidungen** –
nicht eine bestimmte Software.

### Verfügbare Tools

Wir stellen folgende Tools zur Verfügung:

**Kommunikation & Produktivität:**

- **Google Workspace Business Plus** (Email, Calendar, Drive, Docs, Meet)
- **Superhuman Mail Business** (für die, die Email-Produktivität maximieren wollen)

**Development & Dokumentation:**

- **GitHub Enterprise** (Code, Issues, Discussions, Wiki, Actions, Projects)

**Infrastruktur & Security:**

- **Cloudflare Enterprise** (Performance, Security, Reliability)
- **1Password Business** (Secrets, Passwörter, sensitive Daten)

**Design & Website:**

- **Framer Pro** (Website, Prototyping, Design)

### Wie wir Entscheidungen treffen und dokumentieren

**Kernprinzip:** Entscheidungen müssen transparent und für alle zugänglich sein – das "Wie" ist flexibel.

**Optionen für Entscheidungsdokumentation:**

1. **GitHub Issues & Pull Requests** (für die, die damit arbeiten)
   - Issues für Diskussionen und Entscheidungen
   - PRs für konkrete Änderungsvorschläge
   - GitHub Discussions für breitere Themen

2. **Google Docs** (für Nicht-Technical-Members oder komplexere Entscheidungen)
   - Shared Docs für RFCs (Request for Comments)
   - Kommentarfunktion für Diskussion
   - Link zum Doc wird in relevanten Channels geteilt

3. **Öffentliche Dokumentation** (für wichtige strategische Entscheidungen)
   - Veröffentlichung als Markdown im GitHub Wiki
   - Export als PDF auf Website
   - Changelog-Updates

**Wichtige Regel:** Entscheidungen, die andere betreffen, müssen dokumentiert sein. Das Medium ist zweitrangig, die
Transparenz ist primär.

### Kommunikationswege (ohne Slack)

**Wir nutzen KEIN Slack.** Stattdessen:

**Asynchron (bevorzugt):**

- **GitHub Discussions** – für Projektdiskussionen, Ideen, breitere Themen
- **GitHub Issues** – für konkrete Probleme, Bugs, Features
- **Email** (Google Workspace/Superhuman) – für wichtige Ankündigungen, externe Kommunikation
- **Pull Request Comments** – für Code-bezogene Diskussionen
- **Google Docs Comments** – für Dokumenten-bezogene Diskussionen

**Synchron (wenn nötig):**

- **Google Meet** – für Videocalls (aber: async first!)
- **Ad-hoc Pairing** – nach Absprache

**Priorität:**

```
Pull Requests > GitHub Issues/Discussions > Email > Docs > Meetings
```

**Warum keine Chat-Tool (Slack/Discord)?**

- Chat ist synchron, unterbricht Deep Work
- Wichtiges geht in Chat-Historie verloren
- Entscheidungen sind schwer nachvollziehbar
- Async-first fördert bessere Dokumentation

**Wenn du schnell jemanden erreichen musst:** Email. Aber: "Schnell" ist relativ. Async bevorzugen.

---

<details>

<summary>2. Wie wir hierher gekommen sind</summary>

## Wie wir hierher gekommen sind

### Dinge, die uns beeinflusst haben

#### Bücher und Denkweisen (Typus, nicht Checkliste)

- Systems Thinking und komplexe Systeme
- Antifragile Organisationen
- Ethik in der Technik
- Menschen in komplexen Systemen
- Kognitionswissenschaft und Human-Computer Interaction
- Praktiken: RFCs, Design Docs, Postmortems, operatives Lernen, Entscheidungsjournal

#### Andere Unternehmen (als Lernfelder)

- Open-Source-Communities (Governance, Reviews, Contribution-Kultur)
- Sicherheits- und Cloud-Pioniere (Zero Trust, Resilienz, Automatisierung)
- Produktteams, die Dokumentation wie ein Produkt behandeln
- Forschung zu kognitiver Last und Produktivität (Microsoft, McKinsey, UC Irvine)

#### Handbuch (als Werkzeug)

- Dieses Handbuch ist lebendig. Wir committen es. Wir versionieren es. Wir reviewen es.
- Es existiert nicht, um recht zu haben, sondern um besser zu werden.
- Wenn Realität und Handbuch divergieren, gewinnt die Realität – und wir passen das Handbuch an.

#### Prinzipien, die uns prägen

- **Problem First**: Wir beginnen beim echten Problem (kognitive Überlastung), nicht bei Lösungen
- **Augmentation über Automation**: Technologie verstärkt Menschen, ersetzt sie nicht
- **Systeme über Tools**: Mehr Tools sind selten die Antwort
- **Open Process**: Öffentlich, nachvollziehbar, Beiträge willkommen
- **Outcome über Output**: Wirkung schlägt Lieferung
- **Verantwortung ist operativ**: Sichtbar in Code, Verträgen, Support

</details><br/>

<details>

<summary>3. Wie wir Nutzer:innen gewinnen</summary>

## Wie wir Nutzer:innen gewinnen

### Warum wir so sind, wie wir sind

- Wir beginnen mit dem Problem, nicht der Lösung
- Wir sprechen über kognitive Überlastung, bevor wir über unsere Antwort sprechen
- Wir adressieren das fundamentale Design-Problem, nicht Symptome
- Vertrauen ist unsere Währung: Transparenz, Sicherheit, Klarheit in Erwartungen

### Marketing = Problem-Verständnis + nützliche Inhalte

**Das Problem artikulieren:**

- 2,6 Stunden/Tag in E-Mails verloren (McKinsey, 2022)
- 23 Minuten Refokussierung nach Unterbrechung (UC Irvine, 2021)
- 47% fühlen sich von Tool-Fragmentierung überwältigt (Asana, 2024)

**Warum traditionelle Lösungen scheitern:**

- Sie verteilen Last um, reduzieren sie nicht
- Sie perpetuieren Industrieära-Workflows mit moderner Infrastruktur
- Sie erhöhen Komplexität statt sie zu reduzieren

**Unsere Inhalte:**

- Von Deep-Dives zur Kognitionswissenschaft bis zu Praxisguides
- Kein "Hype as a Service" – wir erklären, wie Dinge funktionieren und wie nicht
- Wir teilen: Benchmarks, Metriken, Trade-offs, Entscheidungen und ihre Kosten (öffentlich dokumentiert)
- Problem-Definition vor Solution-Selling

### Wir investieren in unsere Website

- Die Website ist die erste Erfahrung mit WeMake – sie muss das Problem verstehen helfen
- Sie ermöglicht Self-Serve: Problem-Verständnis, Lösungs-Kontext, Demos, Docs, Sandboxen
- Sie ist schnell, barrierearm, suchbar, verständlich, aktualisiert
- Sie sagt, was wir tun – und was nicht
- Sie erklärt das "Warum" vor dem "Was"

### Es einfach machen, mit uns zu arbeiten

- Freemium/Trials für Problem-Exploration
- Klare Nutzungsmodelle
- Einfache Verträge
- Abkürzungen statt Hürden: Direktkauf, Pilot, Pay-as-you-go
- Keine versteckten Gebühren
- Preise werden erklärt, nicht verschleiert

</details><br/>

<details>

<summary>4. Für wen wir entwickeln</summary>

## Für wen wir entwickeln

### Das eigentliche Problem

Organisationen mit hoher kognitiver Last auf Knowledge Workers, die unter:

- E-Mail-Überlastung und ständigen Unterbrechungen
- Tool-Fragmentierung und Context-Switching
- Langsamer Entscheidungsfindung trotz Datenflut
- Verlust von Deep Work und strategischem Denken

### Unser aktuelles ICP (Ideales Kundenprofil)

**Organisationsmerkmale:**

- DACH-Raum mit klarem Anspruch an Qualität, Sicherheit, Ethik
- Bereitschaft, mit KI operativ zu arbeiten (nicht nur zu diskutieren)
- Regulierte Domänen: Gesundheit, Finanz, Industrie, öffentliche Hand, Bildung

**Team-Merkmale:**

- Klare Pain Points durch kognitive Überlastung
- Datenzugang und operative Bereitschaft
- Sponsor mit Ownership
- Ernstnehmen von Gleichheit, Empowerment, Sinnhaftigkeit

### Häufig gestellte Fragen (FAQ)

#### An wen denken wir beim Kreieren besonders?

- Die Praktiker:innen, die mit fragmentierten Workflows kämpfen
- Menschen, die in E-Mails und Meetings ertrinken
- Entscheider:innen, die schneller und besser entscheiden müssen
- Teams, die mehr Zeit für wertschöpfende Arbeit brauchen
- Kolleg:innen, die später onboarden – Dokumentation als Willkommenspaket

#### Was ist ein:e Kunde:in mit hohem Potenzial?

**Hohes Potenzial bedeutet:**

- Klare Pain Points (messbare kognitive Überlastung)
- Datenzugang und technische Bereitschaft
- Operative Bereitschaft (will wirklich arbeiten, nicht nur reden)
- Sponsor mit Ownership und Budget

**Wichtig, weil:**

- Wir wollen echte Ergebnisse: Reduktion kognitiver Last
- Schnelle Lernzyklen über Wirksamkeit
- Wiederholbare Muster für Skalierung

#### Was ist ein Hobbyist und warum wichtig?

**Hobbyist:in bedeutet:**

- Experimentiert, aber ohne echte Anwendung/Verbindlichkeit
- Kein messbares Problem mit kognitiver Überlastung
- Keine operative Umsetzungsbereitschaft

**Wichtig, um:**

- Freundlich zu sein, aber fokussiert zu bleiben
- Zeit auf High-Impact-Arbeit zu konzentrieren
- Wir helfen gern, aber priorisieren Wirkung

#### Warum das KI-Team?

Weil Umsetzung zählt. Augmentation statt Automation erfordert:

- Verständnis für kognitive Prozesse
- Integration in existierende Workflows
- Sicherheit, Governance, Ethik
- Das KI-Team sorgt für wiederholbare Qualität, nicht bunte Demos

#### Was ist mit Marketing?

- Marketing ist Teil des Problem-Verständnisses
- Inhalte, Demos, Dokumentation erklären das "Warum"
- Ziel: Verstehen ermöglichen, Hürden senken
- Sales ist Beratung, nicht Druck

</details><br/>

<details>

<summary>5. Wie wir Nutzer:innen glücklich machen</summary>

## Wie wir Nutzer:innen glücklich machen

### Lösungen schaffen, die wirklich wirken

**Wir starten beim Problem:**

- Wie viel Zeit geht in fragmentierten Workflows verloren?
- Wie sehr leiden Entscheidungen unter Information Overload?
- Wo geht Deep Work verloren?

**Wir messen Wirkung:**

- Zeitersparnis durch reduzierte kognitive Last
- Verbesserte Entscheidungsqualität
- Mehr Zeit für wertschöpfende Arbeit
- Zufriedenheit und Produktivität

**Unser Prozess:**

- Wir bauen klein und lernen schnell
- Proof → Pilot → Produktion
- Wir dokumentieren Learnings – öffentlich, wenn möglich

### Expert:innen sprechen mit Nutzer:innen

- Keine Support-Warteschlange mit Skript
- Du sprichst mit den Menschen, die Systeme entworfen haben
- Review/Support-Calls sind kurz, konkret, lösungsorientiert
- Async-first; nachvollziehbar dokumentiert
- Wir sind ehrlich über Trade-offs zwischen Augmentation-Ansätzen

### Feedback als Lernquelle

- Nutzer-Feedback informiert System-Design
- Wir fragen: "Reduziert das echte kognitive Last?"
- Wir tracken Nutzung und Wirkung
- Transparenz über Tests und Experimente

</details><br/>

<details>

<summary>6. Wie wir Geld verdienen</summary>

## Wie wir Geld verdienen

### Vertrieb = Problem-Verständnis zuerst

**Unser Ansatz:**

- Self-Serve und Low-Touch, wo möglich
- High-Touch nur, wo systemische Integration nötig
- Wir verkaufen zuerst das Problem, dann die Lösung
- Inhalte, Demos, Readiness-Checks senken Akquisekosten

**Was wir nicht tun:**

- Luftschlösser verkaufen
- Feature-Listen präsentieren ohne Problem-Kontext
- Auf Hype setzen statt auf Verständnis

### Preise als Teil der Lösung

**Grundprinzip:** Wenn wir kognitive Last wirklich reduzieren und Effektivität erhöhen, sollte der Wert evident sein.

**Unsere Praxis:**

- Transparente Modelle, Einstieg ohne Kapitalblocker
- Wir stellen Nutzen vor Margenmaximierung – nachhaltig, nicht naiv
- Wir investieren in Effizienz, um Preise dauerhaft niedrig zu halten
- Total Cost of Ownership: Implementation + Betrieb + Risiken

### Abrechnung nach Wirkung

- Pay-as-you-go mit Kontrolle: Caps, Limits, Alarmierungen
- Nutzende kontrollieren ihre Kosten
- Exportierbarkeit von Daten und Metriken ist Standard
- Kündigen ist so leicht wie Buchen

### TCO-optimiert sein

- Wir optimieren Total Cost of Ownership
- Implementation, laufende Kosten, Risiken
- Wenn Open-Source besser passt und gut genug ist, empfehlen wir es
- Vertrauen verdienen, bevor Umsatz maximieren

### Prinzipien für Enterprise

- **Deals verlieren ist okay**: Wir bleiben Prinzipien treu
- **Ergebnisse, nicht Features**: Wir sagen keine spezifischen Liefergegenstände zu, wir liefern Wirkung
- **Develop mit Wiederverwendung**: Wenn überzeugt, dass es mehr als eine Org nutzen kann
- **Testen vor Ändern**: Kund:innen müssen Systeme ausprobieren – Lernen schlägt Hypothesen
- **PM/CSM nur bei Bedarf**: Temporär, leichtgewichtig bei Enterprise-Komplexität
- **Non-negotiables**: Sicherheit und Ethik

</details><br/>

<details>

<summary>7. Dauerhaft niedrige Preise</summary>

## Dauerhaft niedrige Preise

### Unsere Kostenstruktur

**Mehrere Lösungen, ein System:**

- Probleme kommen selten allein – unsere Lösungen adressieren systemische Überlastung
- Gemeinsame Infrastruktur senkt Kosten
- Integration ist eingebaut, nicht nachträglich

**Self-Serve reduziert Sales-Kosten:**

- Problem-Dokumentation ist öffentlich
- Demos, Sandboxen, Online-Buchung ermöglichen Selbst-Evaluation
- Sales ist Beratung bei Bedarf, nicht Druck

**Ein System, integrierte Daten:**

- Zentrale Orchestrierung, einheitliche Identitäten
- Governance über Lösungen hinweg
- Weniger Integration = weniger Kosten

**Technisch versierte Zielgruppe:**

- Dokumentation über Tickets
- How-tos, Playbooks, Architekturen, Entscheidungsleitfäden
- Selbst-Onboarding wo möglich

**Open-Source-Nutzung:**

- Wir nutzen, was gut ist – und geben zurück
- Open Source als Governance-Modell
- Community-getriebene Qualität

</details><br/>

<details>

<summary>8. Entscheidung über neue Lösungen</summary>

## Entscheidung über neue Lösungen

### Wie wir Verbesserungen innerhalb bestehender Systeme auswählen

**Leitfrage:** Reduziert das echte kognitive Last? Ist es systemische Verbesserung oder Feature-Bloat?

**Kriterien:**

- **Problem-Fit**: Löst es ein echtes Problem oder ein Symptom?
- **Systemische Integration**: Fügt es sich nahtlos ein oder addiert es Komplexität?
- **Augmentation-Qualität**: Verstärkt es menschliche Kapazität messbar?
- **Wiederverwendbarkeit**: Hilft es mehreren Kontexten?
- **Sicherheit und Ethik**: Erfüllt es unsere Standards?
- **Pflegeaufwand**: Ist es nachhaltig wartbar?
- **Dokumentierbarkeit**: Können andere es verstehen und nutzen?

**Dokumentationsformate (wähle das passende):**

- **RFCs** (Request for Comments) – als GitHub Issue, Discussion, oder Google Doc
- **ADRs** (Architecture Decision Records) – im GitHub Wiki oder als Markdown-Docs
- **Kleine Experimente** mit klaren Hypothesen – dokumentiert wo sinnvoll
- **Öffentliche Changelogs** – auf Website, im GitHub, als Email-Update

**Der Prozess:**

1. **Vorschlag erstellen** (GitHub Issue, Discussion, oder Google Doc)
2. **Diskussion** (Comments, Meetings wenn nötig)
3. **Entscheidung dokumentieren** (ADR, Update im Wiki)
4. **Öffentlich machen** (Changelog, je nach Relevanz)

### Wie wir neue Lösungen auswählen

**Wir wählen dann neu, wenn:**

- Ein Problem nicht sinnvoll in bestehende Systeme integrierbar ist
- Ein neues Fähigkeitsbündel entsteht, das kognitive Last anders adressiert
- Systemische Verbesserung Tool-Addition schlägt

**Vermeidung von Produktfriedhöfen:**

- **Klarer Owner**: Wer trägt Verantwortung?
- **Klare Metriken**: Welche Wirkung erwarten wir?
- **Klare Exit-Kriterien**: Wann stoppen wir?
- **Dokumentation first**: Schreibe vor dem Bauen die Doks, die später nötig sind (Install, Runbook, Troubleshooting,
  Security, Ethics, Metrics)

**Die Fragen, die wir stellen:**

- Löst es ein fundamentales Problem oder ein Symptom?
- Reduziert es kognitive Last oder verteilt sie um?
- Augmentiert es Menschen oder automatisiert nur?
- Passt es in unsere System-Architektur?
- Können wir es nachhaltig betreiben?

</details><br/>

<details>

<summary>9. Ein breites Unternehmen mit kleinen Teams</summary>

## Ein breites Unternehmen mit kleinen Teams

### Geschwindigkeit durch Lernen

#### Geschwindigkeit = kurze Batch-Größen + klare Verantwortung + öffentliche Entscheidungen

- Wir optimieren nicht auf Auslastung, sondern auf Durchsatz und Lerngeschwindigkeit
- Problem verstehen → Hypothese bilden → Testen → Lernen → Iterieren
- Schnelle Lernzyklen über perfekte Planung

**Dokumentation:**

- Learnings werden öffentlich gemacht (GitHub, Docs, Changelog)
- Entscheidungen sind nachvollziehbar dokumentiert
- Jeder kann sehen, warum etwas entschieden wurde

### Kleine Teams, End-to-End

**Charakteristik:**

- Kleine, autonome Zellen mit End-to-End-Verantwortung
- Teams haben alles, was sie brauchen, oder sie bauen es
- Reduzieren von Abhängigkeiten
- Problem → Lösung → Betrieb → Lernen

**Ownership bedeutet:**

- Systemverständnis, nicht nur Feature-Delivery
- Verantwortung für Wirkung
- Kontext selbst holen, entscheiden, dokumentieren

### Minimale Hierarchie

**Prinzip:** Führung ist Tätigkeit, kein Rangabzeichen

- Wir führen über Klarheit und Kontext, nicht Kontrolle
- Entscheidungen werden dort getroffen, wo Kontext ist
- Transparenz ermöglicht Autonomie

### Titel = tatsächliche Tätigkeit

- Nenn dich so, wie du wirkst
- Titel spiegeln Impact und Rolle, nicht Wunsch
- Karrierewege sind Pfade des Könnens und der Wirkung

### Zielsetzung

**Ansatz:**

- Klare, messbare Ziele mit Feedback-Loops
- "Ship small, learn big": Kleine Releases, große Lerneffekte
- Outcomes über Outputs
- Wirkung auf kognitive Last ist zentrale Metrik

</details><br/>

<details>

<summary>10. Wie wir ein erstklassiges Team aufbauen</summary>

## Wie wir ein erstklassiges Team aufbauen

### Persönlichkeitsmerkmale, die zum Erfolg führen

#### Problem-Löser:innen, nicht Feature-Builder

- Du denkst in Systemen, nicht Tickets
- Du verstehst, dass mehr Tools selten die Antwort sind
- Du kannst fundamentale Probleme von Symptomen unterscheiden
- Du baust Systeme, die Menschen besser machen

#### Systemdenker:innen

- Du siehst, wie Teile zusammenwirken und emergente Eigenschaften erzeugen
- Du verstehst Feedback-Loops und zweite Ordnungseffekte
- Du bevorzugst Integration über Isolation
- Du denkst in TCO, nicht nur Implementation

#### Verantwortungsbewusste Gestalter:innen

- Du verstehst, dass Technologie Verstärker ist – gut oder gefährlich
- Du denkst über ethische Implikationen nach
- Verantwortung ist für dich operativ, nicht theoretisch
- Du hinterfragst "Können wir?" mit "Sollten wir?"

#### Unkomplizierte Zusammenarbeit

- Du kommunizierst klar, freundlich, präzise
- Du arbeitest async und respektierst Fokuszeiten
- Du teilst Kontext proaktiv
- Du dokumentierst Entscheidungen

#### Treiber:innen, nicht Mitfahrer:innen

- Du wartest nicht auf Erlaubnis
- Du holst Kontext und legst los
- Du verantwortest Outcomes, nicht nur Outputs
- "Warum nicht jetzt?" ist deine Frage

### Gute Gründe, bei uns anzufangen

- Du willst fundamentale Probleme lösen, nicht Symptome bekämpfen
- Du willst an der vordersten Linie von KI, Org-Design und kognitiver Wissenschaft arbeiten
- Du willst remote, eigenverantwortlich, mit klarem Impact arbeiten
- Du arbeitest gerne **async-first** und dokumentierst Entscheidungen öffentlich
- Du willst lernen, dokumentieren, teilen – und andere mitziehen
- Du willst Systeme bauen, die Menschen stärken

### Warum du nicht zu uns kommen solltest

- Wenn du lieber Features baust als Probleme löst
- Wenn dir Tool-Komplexität lieber ist als systemische Einfachheit
- Wenn dir Transparenz unangenehm ist
- Wenn du lieber **synchron in Chat-Tools** arbeitest statt async dokumentiert
- Wenn du lieber verwaltet wirst als zu führen
- Wenn du Komfort über Verantwortung stellst

### Eine kleine Gruppe starker Menschen

**Team-Philosophie:**

- Wenige, starke Menschen schlagen große, durchschnittliche Teams
- Tiefes Problem-Verständnis über breite Feature-Kenntnis
- Systemdenker:innen über Spezialisten

**Vergütung:**

- Fair, transparent, kompetitiv
- Mit Ownership-Optionen, wenn sinnvoll
- Wir vergüten Wirkung, nicht Präsenz

</details><br/>

<details>
<summary>11. Was wir wertschätzen</summary>

## Was wir wertschätzen

### Du steuerst selbst

- **Kontext > Kontrolle**: Wir geben Problem-Verständnis, du findest den Weg
- **Ownership bedeutet**: Problem verstehen, Systemkontext greifen, entscheiden, dokumentieren, iterieren
- **Toolwahl**: Du entscheidest, welche Tools du nutzt (GitHub, Docs, Email – was für dich funktioniert)
- **Wir erwarten**: Du triffst Entscheidungen und dokumentierst sie öffentlich nachvollziehbar

### Mach es öffentlich

- **Public by default**: Issues, Docs, Changelogs, Wiki, Entscheidungen
- **Warum**: Öffentlichkeit ist Qualitätsfilter und Lehrmeister
- **Ausnahme**: Was vertraulich sein muss (Security, Customer-Data, Secrets in **1Password**)
- **Wie**: GitHub Issues/Discussions, Docs exports, Wiki, Website-Updates – wähle das passende Medium

### Async-first, nicht Chat-first

- **Warum kein Chat-Tool**: Unterbricht Deep Work, Wichtiges geht verloren, schlechte Dokumentation
- **Async bevorzugen**: Durchdachte Kommunikation, bessere Dokumentation, respektiert Fokuszeiten
- **Synchron nur wenn nötig**: Google Meet für Pairing, komplexe Diskussionen
- **Dokumentiere immer**: Auch nach Meetings → Summary in Issue/Doc

### Systemdenken über Feature-Denken

- **Die Frage**: Löst das das fundamentale Problem oder ein Symptom?
- **Wir bevorzugen**: Systemische Verbesserungen über Tool-Addition
- **Wir suchen**: Integration über Isolation
- **Emergenz verstehen**: Systeme sind mehr als die Summe ihrer Teile

### Warum nicht jetzt?

- **Heute ist besser als demnächst**: Klein anfangen, schnell lernen
- **MVP bedeutet**: Minimum Viable Problem-Solution-Fit
- **Risiken klar benennen**: Nicht vermeiden, sondern transparent machen

### Mehr Mut zum Ungewöhnlichen

- **Konventionen sind bequem**: Fortschritt ist oft unbequem
- **Wir suchen**: Wo andere nicht hinschauen
- **Wir hinterfragen**: "Das haben wir immer so gemacht"
- **Wir erklären**: Was wir anders machen und warum (z.B. kein Chat-Tool)

### Grundsätzlich optimistisch

- **Realist:innen mit Blick nach vorne**: Komplexe Probleme sind lösbar
- **Probleme als Einladung**: Zu besserem System-Design
- **Menschen können mehr**: Als ihre Rollen erlauben

</details><br/>

<details>

<summary>12. Ein erstklassiges Arbeitsumfeld schaffen</summary>

## Ein erstklassiges Arbeitsumfeld schaffen

### Standardmäßig kein Produktmanagement

**Unsere Default-Einstellung:**

- Engineers, Researchers, Designer:innen sprechen direkt mit Nutzer:innen
- Problem-Verständnis kann man nicht delegieren
- Weniger Übersetzungsschichten = besseres Verstehen = bessere Systeme

**Wann aktivieren wir PM/CSM:**

- Leichtgewichtig, temporär
- Wo Enterprise-Kontext, Koordination oder Compliance es erfordern
- Als Unterstützung, nicht als Gatekeeper
- Ziel: Mehr geteiltes Verständnis, schnellere Lernschleifen

### Transparenz ist der Treibstoff für Autonomie

**Wie wir dokumentieren (individuell wählbar):**

- **Jede Entscheidung**: Hat Issue, Doc, oder Wiki-Eintrag
- **Problem-Definition**: Ist öffentlich (GitHub, Website)
- **Lösungsansätze**: Sind dokumentiert (PRs, RFCs, ADRs)
- **Metriken und Learnings**: Sind teilbar (Docs, Changelog)
- **Protokolle, Postmortems**: Sind Standard (Format ist flexibel)
- **Sicherheit und Ethik**: Sind mitdokumentiert

**Deine Tool-Wahl:**

- Manche bevorzugen GitHub Issues → das ist ok
- Manche bevorzugen Google Docs → das ist ok
- Wichtig: Entscheidung ist öffentlich nachvollziehbar

### Es beginnt mit der Einstellung

**Wen wir einstellen:**

- Menschen, die **async-first** denken und dokumentieren
- Die zwischen Problemen und Symptomen unterscheiden können
- Die Verantwortung wollen und können
- Die Augmentation über Automation stellen
- Die **öffentliche Transparenz** leben

**Wie wir prüfen:**

- Systemdenken und Problem-Verständnis
- Haltung und Lernfähigkeit
- Praktische Tests: Build something meaningful, small
- Cultural Fit: Werte und Arbeitsweise

### Hoher Anteil Tech-Talente aller Geschlechter

**Warum wichtig:**

- Augmentation erfordert tiefes technisches Verständnis
- Systemische Lösungen brauchen systemisches Denken
- Vielfalt ist unser Verstärker für bessere Lösungen

**Wie wir das sichern:**

- Sprache, Chancen, Räume bewusst gestalten
- Kompetenz sichtbar machen
- Inclusive by design

### Konzentriertes Arbeiten

**Unsere Kultur:**

- **Async-first** für Deep Work
- Tiefe Fokuszeiten, **keine ständigen Unterbrechungen durch Chat**
- Kommunikation ist **schriftlich, durchdacht, dokumentiert**
- Email/Discussions für Koordination; Entscheidungen in Issues/PRs/Docs
- "Maker Schedule" wird respektiert

**Konkrete Praktiken:**

- **GitHub Discussions** statt Chat für asynchrone Konversationen
- **Email** (Google Workspace/Superhuman) für wichtige Ankündigungen
- **Issues/PRs** für konkrete Arbeit
- **Docs** für kollaboratives Schreiben
- **Meetings** nur wenn async nicht funktioniert

</details><br/>

<details>

<summary>13. Nicht das Geld ausgehen lassen</summary>

## Nicht das Geld ausgehen lassen

### Ruhe bewahren und auf Überleben ausgerichtet sein

- **Runway-Fokus**: Wir priorisieren Nachhaltigkeit über Wachstum um jeden Preis
- **Szenarien-Planung**: Wir betreiben Szenarien und Frühwarnsysteme
- **Wirkung pro Euro**: Effizienz ist Teil unserer DNA

### Prinzipien zur Kapitalbeschaffung

**Grundsatz:** Kapital ist Werkzeug für Mission, kein Ziel an sich

- Wir nehmen Geld nur zu Bedingungen, die Prinzipien schützen
- Mission und Werte sind nicht verhandelbar
- Transparenz gegenüber Team und Community hat Priorität
- Langfristige Nachhaltigkeit über schnelles Wachstum

### Wie wir es ausgeben

**Prioritäten:**

- In Infrastruktur, die systemische Lösungen ermöglicht
- In Menschen, die Systeme bauen und Probleme verstehen
- In Inhalte, die Problem-Verständnis schaffen: Docs, Playbooks, Forschung
- In Forschung zu kognitiver Last und Augmentation
- In Sicherheit, Ethik, Qualität

**Nicht ausgeben für:**

- Feature-Bloat ohne Problem-Fit
- Marketing ohne Substanz
- Overhead ohne Wirkung

</details><br/>

<details>

<summary>14. Wohin geht die Reise?</summary>

## Wohin geht die Reise?

### Die Zukunft der Arbeit

**Unsere Vision:** Die Zukunft der Arbeit sind nicht mehr Tools, sondern bessere Systeme. Wir bauen die Infrastruktur
für organisationale Intelligenz.

**Was das bedeutet:**

- Systeme, die kognitive Last wirklich reduzieren
- Augmentation wird Standard, nicht Ausnahme
- Menschen fokussieren auf Deep Work, Systeme auf Koordination
- German Engineering für KI-gestützte Org-Transformation

### Wird WeMake verkauft werden?

- Wir bauen auf Eigenständigkeit
- Verkauf ist mögliches Ereignis, kein Ziel
- Nur falls es Mission und Menschen stärkt
- Sekundärverkäufe bevorzugt über vollständige Übernahmen

### 1 Mio. € bis 2027

**Das Ziel:**

- Nicht nur Umsatz: Wiederkehrender Wert und messbare Wirkung
- Metriken: Reduzierte kognitive Last, verbesserte Outcomes, Nutzerzufriedenheit
- Wir veröffentlichen Impact-Kennzahlen (ohne Vertrauliches)

**Der Weg:**

- Fokus auf High-Impact-Probleme
- Wiederholbare, systemische Lösungen
- Nachhaltige Kundenbindung durch echte Wirkung

### Sekundärverkäufe statt Übernahme

**Präferenz:**

- Mitarbeiter:innen sollen partizipieren können
- Kultur und Mission bleiben erhalten
- Optionen für Stabilität + Wachstum

</details><br/>

<details>

<summary>15. Wie du helfen kannst</summary>

## Wie du helfen kannst

### Dich schnell einarbeiten

- **Lies**: Dieses Handbuch + Manifesto
- **Verstehe**: Das fundamentale Problem der kognitiven Überlastung
- **Starte klein**: Verbessere eine Doku, schreibe einen Test, dokumentiere ein Pattern
- **Denke systemisch**: Wie fügt sich dein Beitrag ins größere Ganze?
- **Wähle deine Tools**: Nutze was für dich funktioniert (GitHub, Docs, Email)

### Um Hilfe bitten, aber erst nach eigenem Versuch

**Zeig deinen Versuch:**

- Was hast du versucht?
- Was hast du beobachtet?
- Was hat nicht funktioniert?
- Welchen Kontext brauchst du noch?

**Stelle spezifische Fragen:**

- Damit wir gezielt helfen können
- In Issue, Discussion, Email, oder Doc – wo es passt
- Mit relevanten Links versehen

### Keine Perfektion erwarten

- **"Klar + funktionsfähig + dokumentiert"** ist unser Sweet Spot
- Perfekt ist oft langsam und fragil
- Fehler sind okay; Verschweigen nicht
- Iteration schlägt Perfektion

### Es besser machen

**Das Scout-Prinzip:**

- Hinterlasse alles klarer, einfacher, sicherer
- Refactoring ist Teil der Arbeit
- Dokumentation verbessern ist echter Wert
- Schreibe die Doku, die du dir gewünscht hättest

**Dokumentiere wo sinnvoll:**

- PRs für Code/Docs-Änderungen
- Issues für Probleme
- Wiki für Architecture Decisions
- Docs für kollaborative Texte

### In Systemen denken

- **Frage immer**: Löst das das fundamentale Problem?
- **Systemische Verbesserung**: Über Feature-Addition
- **Integration**: Über Isolation
- **Suche**: Das dritte, vierte, fünfte Lösungsmuster
- **Kombiniere**: Bestehendes neu für systemische Effekte

### Dokumentation > Live-Chat

**Warum async-first:**

- Besseres Denken durch Schreiben
- Nachvollziehbare Historie
- Respektiert Deep Work
- Inklusiver für verschiedene Zeitzonen/Arbeitsweisen

**Statt schnellem Chat:**

- Schreibe ein Issue mit Context
- Erstelle ein Doc mit deinen Gedanken
- Tagge relevante Personen
- Gib Zeit für durchdachte Antworten

### Nicht einfach mergen ohne Review

- **Mindestens ein Review**: Für Code, Docs, Entscheidungen
- **Review bedeutet**: Verantwortung teilen, Qualität sichern
- **Systemischer Check**: Passt es ins große Ganze?

### Öffentlich dokumentieren > Privat chatten

**Hierarchie der Entscheidungsdokumentation:**

- **PRs/Issues** für Code/Docs-Änderungen und Entscheidungen
- **GitHub Discussions** für Ideen, Diskussionen, RFCs
- **Google Docs** für kollaboratives Schreiben (wenn alle Zugang haben)
- **Email** für Ankündigungen und wichtige Updates
- **Meetings** nur, wenn async nicht funktioniert (dann: Summary dokumentieren!)

**Wichtiges steht NICHT nur in:**

- Privaten Chats
- Nicht-dokumentierten Calls
- Persönlichen Notizen

### Dinge standardmäßig öffentlich

- **Default**: Public (Problem-Definitionen, Lösungsansätze, Learnings)
- **Begründet**: Vertraulichkeit (Security, Customer-Data – nutze **1Password**)
- **Für Zukunft schreiben**: Kurz, klar, mit Links
- **Tool-agnostisch**: Hauptsache öffentlich dokumentiert

### Proaktiv bei Community-Fragen

- **Antworte**: Hilfreich, freundlich, ehrlich
- **Bei Unsicherheit**: Sag es und finde es heraus
- **Teile Kontext**: Problem-Verständnis ist Mehrwert
- **Dokumentiere Antworten**: In Issues, Docs, FAQ

### Und wenn du nicht hier arbeitest

- Du darfst dieses Handbuch lesen, zitieren, kritisieren
- Wenn etwas fehlt oder falsch ist: Eröffne ein Issue, schreib uns eine Email
- Wir danken dir für Feedback zu Problem und Lösung

</details><br/>

---

## Technische Details zu unseren Tools

### Google Workspace Business Plus

**Wofür:** Email, Kalender, Dokumente, Drive, Meet **Wer nutzt es:** Jeder im Team hat Zugang **Warum:**
Enterprise-grade, kollaborativ, integriert **Alternativen für individuelle Präferenz:** Superhuman für Email-Power-User

### Superhuman Mail Business

**Wofür:** Schnellere, produktivere Email-Nutzung **Wer nutzt es:** Freiwillig, für die, die Email-Produktivität
maximieren wollen **Warum:** Keyboard-first, extrem schnell, Workflows **Alternative:** Standard Gmail aus Google
Workspace

### Cloudflare Enterprise

**Wofür:** CDN, DDoS-Protection, Performance, Security, Zero-Trust-Access **Wer nutzt es:** Automatisch für alle
Services **Warum:** Best-in-class Performance und Security **Team-Relevanz:** Ops/Infra

### GitHub Enterprise

**Wofür:** Code, Issues, Discussions, Wiki, Actions, Projects, Releases **Wer nutzt es:** Development, Docs, öffentliche
Diskussionen **Warum:** Industry-standard, öffentlich, transparent, CI/CD integriert **Alternative für
Nicht-Technical:** Nutze Issues als Layperson, oder Google Docs

### 1Password Business

**Wofür:** Passwörter, API-Keys, Secrets, Certificates **Wer nutzt es:** Jeder im Team hat Zugang **Warum:** Security,
Shared Vaults, Compliance **Team-Relevanz:** Alle

### Framer Pro

**Wofür:** Website, Landing Pages, Prototyping, Design **Wer nutzt es:** Design, Marketing, Product **Warum:** Modern,
schnell, kollaborativ, Engineering-friendly **Team-Relevanz:** Design, Marketing

---

## Workflow-Beispiele

### Neue Feature-Idee

**Option A (GitHub-User):**

1. Erstelle GitHub Issue
2. Diskussion in Comments
3. Entscheidung dokumentieren
4. PR erstellen
5. Review-Prozess
6. Merge und Changelog

**Option B (Nicht-GitHub-User):**

1. Erstelle Google Doc mit RFC
2. Teile Link per Email/in relevanten Channels
3. Kommentare sammeln
4. Entscheidung dokumentieren
5. Technical Person erstellt Issue/PR
6. Link zu Doc im Issue
7. Merge und Changelog

**Wichtig:** Beide Wege sind valide. Hauptsache transparent dokumentiert.

### Problem-Reporting

**Option A (Technical):**

- GitHub Issue mit Repro-Steps
- Labels setzen
- Diskussion in Comments

**Option B (Non-Technical):**

- Email an Team mit Beschreibung
- Technical Person erstellt Issue
- Link zur Original-Email im Issue

### Entscheidungs-Dokumentation

**Für alle lesbar:**

1. **GitHub Wiki** – für ADRs, dauerhafte Entscheidungen
2. **Changelog** (auf Website) – für User-relevante Änderungen
3. **Google Docs** – für kollaborative RFCs (dann Export zu Wiki)
4. **Email** – für wichtige Updates ans Team

**Sensible Infos:**

- **1Password** für Secrets, Keys, Credentials
- Private Repos in GitHub (wenn nötig)

---

## Onboarding-Checkliste

### Tag 1

- [ ] **Google Workspace** Account erhalten
- [ ] **1Password** Zugang bekommen (via Admin)
- [ ] **GitHub** Account hinzugefügt (zu WeMake Org)
- [ ] Dieses Handbuch + Manifesto gelesen
- [ ] **Framer** Zugang (bei Bedarf)
- [ ] **Superhuman** Trial starten (optional)

### Woche 1

- [ ] Erstes Issue kommentiert oder erstellt
- [ ] Erstes Doc gelesen und kommentiert
- [ ] Team-Members kennengelernt (async!)
- [ ] Erste kleine Contribution (Docs, Test, etc.)
- [ ] Persönliche Tool-Präferenzen definiert

### Monat 1

- [ ] Erstes größeres Problem verstanden
- [ ] Erste dokumentierte Entscheidung getroffen
- [ ] Ersten PR/Change eingereicht (in deinem Format)
- [ ] Feedback-Loop etabliert
- [ ] Workflow gefunden, der für dich funktioniert

---

## FAQ für neue Team-Members

**Q: Muss ich GitHub nutzen?** A: Nein. Aber: Entscheidungen müssen öffentlich dokumentiert sein. GitHub ist eine
Option, Google Docs eine andere. Wähle, was für dich passt. Technical Work läuft primär über GitHub.

**Q: Wie kommuniziere ich schnell?** A: Email (Google Workspace/Superhuman). Aber: "Schnell" überdenken. Async
bevorzugen.

**Q: Wo finde ich Entscheidungen?** A: GitHub Wiki, Issues, Discussions, Docs (je nach Kontext). Wir taggen wichtige
Entscheidungen.

**Q: Kein Chat-Tool? Wirklich?** A: Ja, wirklich. Async-first fördert bessere Kommunikation, Dokumentation und Deep
Work.

**Q: Was wenn ich kein Technical Background habe?** A: Google Docs, Email, kommentiere Issues als Layperson. Technical
Members helfen beim Übersetzen.

**Q: Welche Tools MUSS ich nutzen?** A: **1Password** für Secrets/Credentials. Sonst: Du entscheidest. Google Workspace
ist Standard, Superhuman optional.

**Q: Wo lerne ich die Tools?** A: Docs in GitHub Wiki, interne Guides, Learning by Doing. Frag im Team (async
documentation preferred).

---

**Hinweis zu Secrets & Security:**

- Nutze **1Password** für alle Credentials, API-Keys, Secrets
- Shared Vaults für Team-Ressourcen
- Persönliche Vaults für individuelles
- **NIE** Secrets in Code, Issues, Docs – immer über 1Password teilen

**Cloudflare für Alle:**

- Zero-Trust-Access automatisch konfiguriert
- Nutze für sichere Service-Zugriffe
- Ops-Team hilft bei Setup

---

Dieses Handbuch lebt. Ergänze, was fehlt. Korrigiere, was falsch ist. **Mach es öffentlich** (Issue, PR, Doc – deine
Wahl).
