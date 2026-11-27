# JYZRepositoryDummyTemplate_Python2Java8
Java mit Python - Jython
Wichtig: Jython 2.7 funktioniert nur mit Python 2.<BR>
<BR>
Verwende das JYZKernelEngine Projekt.<BR>
Darin gibt es einen Classloader, mit dem Projekte und deren Javaklassen, sowie die per Maven eingebundenen Java Bibliotheken, etc.<BR>
eingebunden werden.

----------------------
Wichtig:<BR>
Wenn man mit Python Packages arbeitet und Java Klassen einbindet,<BR>
dann gibt es sogar einen Namenskonflikt, wenn die Klassen unterschiedlich heissen.<BR>
Damit das nicht geschieht müssen die Package-Pfade unterschiedlich lauten.<BR>
<BR>
Daher werden bei den Jython Projekten<BR>
ein jyz Package als Einstieg verwenden.<BR>
<BR>
Projekte, die das JYZKernelEngine- Projekt nutzen, brauchen wiederum ihren eigenen Namespace, z.B. jyz2 als Startpackage
