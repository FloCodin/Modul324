## Dokumentation zu Pull-Requests in Verbindung mit Trunk-based Development

### Funktionsweise von Pull-Requests

Pull-Requests werden genutzt, um Änderungen von sehr kurzlebigen Feature-Branches (oft nur wenige Stunden oder maximal ein bis zwei Tage alt) in den `main` Branch zu integrieren. Dies passt ideal zu Trunk-based Development, bei dem das Ziel ist, möglichst schnell in den Hauptbranch zu mergen.

### Umsetzung im Projekt

- Änderungen erfolgen auf sehr kleinen, kurzlebigen Branches.
- Jeder Pull-Request wird zeitnah reviewed und in den `main` Branch gemerged.
- Dies sichert eine schnelle Integration und reduziert Merge-Konflikte.

### Schritte für erfolgreiche Pull-Requests (Trunk-based)

1. Kurzen Feature-Branch erstellen
2. Änderungen vornehmen und committen (idealerweise unter 1 Tag Arbeit)
3. Pull-Request eröffnen mit kurzer Beschreibung
4. Review von mindestens einem Teammitglied innerhalb weniger Stunden
5. Merge in `main` sobald CI erfolgreich ist

### Nutzen von Pull-Requests in Trunk-based Development

- Unterstützt schnelle Integration in `main`
- Reduziert Konflikte, da Branches sehr kurz leben
- Fördert stetige Code-Qualität durch regelmäßige Reviews
