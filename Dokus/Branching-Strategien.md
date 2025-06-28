## Vergleich verschiedener Branching-Strategien

|Strategie|Beschreibung|Vorteile|Nachteile|
|---|---|---|---|
|**Git Flow**|Strukturierte Trennung mit vielen Branches.|Klare Release- und Bugfix-Prozesse.|Aufwändig, komplex.|
|**GitHub Flow**|Feature-Branches mit Pull Requests in `main`.|Einfach, Review-basiert.|Weniger geeignet für parallele Releases.|
|**Feature Branching**|Jeder arbeitet auf Feature-Branches.|Gute Trennung.|Merge-Konflikte bei langen Branches.|
|**Trunk-based Development**|Kurze Branches, schneller Merge in `main`.|Einfach, schnelle Integration.|Erfordert hohe Disziplin.|
|**Release Branching Light**|Nur temporäre Release-Branches.|Wenig Aufwand, Flexibilität.|Keine parallelen Langzeit-Releases.|
|**Hotfix Branching**|Separater Branch nur für Hotfixes.|Schnelle Bugbehebung.|Wartung paralleler Branches nötig.|

## Auswahl und Begründung

Ich verwende **Trunk-based Development**, da es wenig Verwaltungsaufwand erfordert, schnelle Integration ermöglicht und für kontinuierliche Verbesserungen geeignet ist.
Ebenfalls ist es meiner Meinung nach für so ein kleines Projekt eher geeignet als bspw GitHubFlow da man sich da nur selbst verwirrt mit mehreren Branches etc. 