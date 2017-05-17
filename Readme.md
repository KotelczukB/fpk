# Fortgeschrittene Programmierkonzepte

_Lehrveranstaltung im 2. Semester des Bachelorstudiengangs Wirtschaftsinformatik an der Hochschule Rosenheim._

# Inhalt

0. Git und IntelliJ
1. Klassen und Vererbung
2. Annotationen und JUnit
3. Interfaces, ABC und Reflection
    - States als Beispiel für ABC
    - Factory Pattern?
4. Container und Iteratoren
    1. Liste
        - einfache ArrayList
        - geblockte ArrayList
        - LinkedList
    2. Iteration
        - Eingeführt mit `for` auf Array
        - `for -> while` auf ArrayList
        - `for -> while` auf LinkedList
        - Abstraktion in den Iterator; Iterator steht "zwischen" den Elementen
            - Iterator als DesignPattern -> UML
            - Iterator als inner class
    2. Map
        - Nicht-sequenzieller Zugriff: Gib mir Student X
        - Konkrete StudentenMap, mit `get(int matr)`
        - Abstraktion 1: `Predicate` -> allgemeine `get(Predicate)`
        - Abstraktion 2: `Map<K, V>.{put,get}`
        - Implementierung als `LinkedHashMap`
        - Iterator -> sequenzieller Zugriff auf entryset/keyset/valueset
    3. Set
        - Via LinkedList -> zu aufwaendig!
        - Via BinBaum (TreeSet)
            - Insert
            - Contains
            - Remove
        - Iteration: Agenda! DFS, BFS
5. Rekursion
    - Einfache (for/while->rekursion)
    - MergeSort
    - BinarySearch?
6. Threading
7. Generics: Bounds and Wildcards
8. Observer Pattern
9. HashMap als Kombi von BinBaum und List