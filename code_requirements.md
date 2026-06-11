# Code requirements

Damit der Code übersichtlich, lesbar, wartbar, qualitativ hochwertig und sicher ist und bleibt, gelten folgende Anforderungen an den Code:

- Typisierung: Alle Variablen, Parameter, Konstanten, Funktionen und Methoden müssel typisiert sein.
- Namen:
  - Alle Namen müssen genau beschreiben, was die Klasse repräsentiert, die Variable speichert oder die Funktion ausführt bzw. speichert, dürfen aber auch keinen unnötigen Kontext enthalten.
  - Alle Namen müssen auf Englisch verfasst sein.
  - Alle Namen müssen den Naming-Conventions der jeweiligen Sprache entsprechen (z.B. snake_case für Variablen, Parameter, Funktionen und Methoden, UPPER_SNAKE_CASE für Konstanten und PascalCase für Klassen bei Python oder camelCase für Variablen, Parameter, Konstanten, Funktionen und Methoden und PascalCase für Klassen bei Dart).
- Funktionen und Methoden: Jede Funktion und jede Methode muss 1) möglichst kurz sein, darf 2) nur eine Aufgabe erfüllen, 3) möglichst wenige Abhängigkeiten haben
  - Jede Funktion und jede Methode muss möglichst kurz sein.
  - Jede Funktion und jede Methode muss möglichst wenige Abhängigkeiten haben.
  - Jede Funktion und jede Methode darf nur eine Aufgabe erfüllen und keine "Nebeneffekte" haben.
  - Code-Wiederholungen müssen durch wiederverwendbare Funktionen, Klassen und Methoden auf ein absolutes Minimum reduziert werden.
  - Eine Funktion darf immer nur entweder etwas ausführen oder etwas zurückgeben, aber nicht beides.
- Ausnahmen: Der Code muss mit jedem Szenario und jedem User-Input zurechtkommen, ohne abzustürzen. Stattdessen sollen Fehlermeldungen ausgegeben werden, und, wenn ein ungültiger User-Input der Fehler ist, ausgegeben werden, was der Fehler ist. Wenn es sich um einen Fehler im Code an anderer Stelle handelt, muss der Fehler gespeichert werden, sodass alle aufgetretenen Fehler von den Entwicklern eingesehen werden können.
- Kommentare: Kommentare dürfen nur dort eingesetzt werden, wo sie unbedingt benötigt werden. Sie dürfen nicht beschreiben, was der Code macht, sondern warum er es macht. Im Allgemeinen sollte der Code so verständlich sein, dass man keine Kommentare benötigt.
- Tests: Jede Einheit (Funktion, Methode, Klasse) des Codes muss testbar sein und durch einen Test abgedeckt werden, der alle möglichen Szenarien abdeckt. Der Testcode muss mit denselben Qualitätsstandards wie der Produktionscode geschrieben werden.
- Effizienz: Der Code sollte möglichst effizient und schnell gestaltet werden, indem unter Anderem, wo möglich, Konstanten statt Variablen verwendet oder möglichst wenige Datenbank- oder API-Aufrufe gemacht werden. Beim Produktionscode ist diese Effizienz entscheidend, beim Testcode ist sie zweitrangig.

All diese Guidelines orientieren sich an dem Buch "Clean Code - Refactoring, Patterns, Testen und Techniken für sauberen Code" von Robert C. Martin. Die dort aufgeführten Regeln sollten, genau wie die oben aufgeführten Regeln, unbedingt eingehalten werden.
