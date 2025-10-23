# CONTRIBUTING

Danke, dass du beitragen möchtest! Hier kurze Regeln und ein Workflow für Beiträge.

Wie beitragen
1. Fork + Branch: Erstelle einen Branch mit `feature/<kurz-beschreibend>` oder `fix/<kurz>`.
2. Commit-Nachrichten: kurz, prägnant; in Englisch oder Deutsch, z. B. `docs: Anleitung zur Kalibrierung ergänzt`.
3. Pull Request: Erkläre kurz was gemacht wurde und verlinke ggf. Issues.

Dokumentationsstil
- Verwende Markdown (.md).
- Abschnittsaufbau bei Anleitungen:
  - Titel, Kurzbeschreibung, Zielgruppe, Schwierigkeitsgrad, Zeitbedarf
  - Benötigtes Material (BOM)
  - Schritt-für-Schritt-Anleitung (nummeriert)
  - Troubleshooting
  - Fotos/Diagramme (relative Pfade)
- Lange Anleitungen: Splitte in Unterseiten innerhalb `docs/`.

Bilder und große Dateien
- Bilder in `images/` ablegen; referenziere sie relativ (`![Alt](../images/foo.jpg)`).
- Große Binärdateien (CAD, STEP) mit Git LFS verwalten.

Qualitätschecks (PR-Checklist)
- [ ] Anleitung getestet (wenn möglich).
- [ ] Fotos/Diagramme angehängt, relevante Dateien im richtigen Ordner.
- [ ] BOM vollständig.
- [ ] Sicherheits-Hinweise vorhanden.
- [ ] Lizenz angegeben (falls nötig).

Code of Conduct
- Bitte respektvoll und konstruktiv zusammenarbeiten. (Ergänze ggf. `CODE_OF_CONDUCT.md`.)

Kontakt
- Bei Fragen: Issue eröffnen oder @giulia anpingen.
