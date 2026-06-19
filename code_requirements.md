# Code requirements

Damit der Code übersichtlich, lesbar, wartbar, qualitativ hochwertig und sicher ist und bleibt, gelten folgende Anforderungen an den Code:

- Typisierung: Alle Variablen, Parameter, Konstanten, Funktionen und Methoden müssen typisiert sein.
- Namen:
  - Alle Namen müssen genau beschreiben, was die Klasse repräsentiert, die Variable speichert oder die Funktion ausführt bzw. speichert, dürfen aber auch keinen unnötigen Kontext enthalten.
  - Alle Namen müssen auf Englisch verfasst sein.
  - Alle Namen müssen den Naming-Conventions der jeweiligen Sprache entsprechen (z.B. snake_case für Variablen, Parameter, Funktionen und Methoden, UPPER_SNAKE_CASE für Konstanten und PascalCase für Klassen bei Python oder camelCase für Variablen, Parameter, Konstanten, Funktionen und Methoden und PascalCase für Klassen bei Dart und JavaScript).
- Funktionen und Methoden:
  - Jede Funktion und jede Methode muss möglichst kurz sein.
  - Jede Funktion und jede Methode muss möglichst wenige Abhängigkeiten haben.
  - Jede Funktion und jede Methode darf nur eine Aufgabe erfüllen und keine "Nebeneffekte" haben.
  - Code-Wiederholungen müssen durch wiederverwendbare Funktionen, Klassen und Methoden auf ein absolutes Minimum reduziert werden.
  - Eine Funktion sollte immer entweder etwas ausführen oder etwas zurückgeben, aber nicht beides. Ausnahmen sind explizit zu begründen.
- Ausnahmen: Der Code muss mit jedem Szenario und jedem User-Input zurechtkommen, ohne abzustürzen. Stattdessen sollen Fehlermeldungen ausgegeben werden, und, wenn ein ungültiger User-Input der Fehler ist, ausgegeben werden, was der Fehler ist. Wenn es sich um einen Fehler im Code an anderer Stelle handelt, muss der Fehler gespeichert werden, sodass alle aufgetretenen Fehler von den Entwicklern eingesehen werden können.
- Kommentare: Kommentare dürfen nur dort eingesetzt werden, wo sie unbedingt benötigt werden. Sie dürfen nicht beschreiben, was der Code macht, sondern warum er es macht. Im Allgemeinen sollte der Code so verständlich sein, dass man keine Kommentare benötigt.
- Tests: Jede Einheit (Funktion, Methode, Klasse) des Codes muss testbar sein und durch einen Test abgedeckt werden, die Happy Paths, Edge Cases sowie Fehlerfälle berücksichtigen. Der Testcode muss mit denselben Qualitätsstandards wie der Produktionscode geschrieben werden.
- Effizienz: Der Code sollte möglichst effizient und schnell gestaltet werden, indem unter Anderem, wo möglich, Konstanten statt Variablen verwendet oder möglichst wenige Datenbank- oder API-Aufrufe gemacht werden. Beim Produktionscode ist diese Effizienz entscheidend, beim Testcode ist sie zweitrangig.
- Anführungszeichen: Für Strings müssen in Python standardmäßig doppelte Anführungszeichen, in JavaScript bei einzeiligen Strings doppelte Anführungszeichen und bei mehrzeiligen Backticks verwendet werden. In Dart müssen einfach Anführungszeichen verwendet werden. Wenn das standardmäßig verwendete Zeichen im String vorkommt, müssen bei JavaScript Backticks verwendet werden, bei Python und Dart das jeweils andere Zeichen, esseidenn, auch dieses existiert im String. Ist dies der Fall, muss das standardmäßige Zeichen verwendet und im String escapet werden.
- Parameter müssen *named parameters* sein bzw. als solche behandelt werden.

All diese Guidelines orientieren sich an dem Buch "Clean Code - Refactoring, Patterns, Testen und Techniken für sauberen Code" von Robert C. Martin. Die dort aufgeführten Regeln sollten, genau wie die oben aufgeführten Regeln, unbedingt eingehalten werden.
