(python-infos)= 
# Infos zu Python

```{figure} ../img/python-logo.png
    :figclass: margin
    :width: 150px   
```

Python ist eine der weltweit bekanntesten und am häufigsten verwendeten Programmiersprachen. Sie wurde in den frühen 1990er Jahren von Guido van Rossum entwickelt und ist seitdem stetig gewachsen. Van Rossum entwarf Python mit dem Ziel, eine einfache, leicht lesbare und dennoch leistungsstarke Sprache zu schaffen. Python ist bekannt für seine klare Syntax, die es Programmierer:innen ermöglicht, Konzepte mit weniger Codezeilen auszudrücken, als dies bei anderen Sprachen der Fall ist. Das macht sie zu einer sogenannte *höhere Programmiersprache*, da sie näher an der menschlichen Sprache und weiter entfernt von der Maschinensprache ist, die Computer direkt verstehen. Durch diesen höheren Abstraktionsgrad ist Python leicht erlernbar und besonders bei Einsteigern beliebt.

Ein großer Vorteil von Python ist, dass es interpretiert und nicht kompiliert wird. Das bedeutet, dass Python-Code direkt Zeile für Zeile von einem speziellen Programm, dem sogenannten Interpreter, ausgeführt wird. Im Gegensatz dazu müssen bei kompilierten Sprachen, wie [C](https://de.wikipedia.org/wiki/C_(Programmiersprache)) oder [Java](https://de.wikipedia.org/wiki/Java_(Programmiersprache)), die Programme zunächst vollständig in Maschinensprache übersetzt werden, bevor sie ausgeführt werden können. Das erleichtert den Entwicklungsprozess und ermöglicht es, schnell Ergebnisse zu sehen und Fehler zu beheben.

Python wird in einer Vielzahl von Bereichen eingesetzt, darunter Webentwicklung, Datenanalyse, maschinelles Lernen, wissenschaftliches Rechnen und sogar im Bereich der künstlichen Intelligenz. Die Vielseitigkeit der Sprache, zusammen mit ihrer großen Gemeinschaft und der riesigen Sammlung von Bibliotheken und Tools, macht Python zu einer hervorragenden Wahl für verschiedenste Anwendungen. Ein Grund für Pythons weitreichenden Einsatzmöglichkeiten sind die umfangreichen [Standardbibliothek](https://docs.python.org/3/library/), welche größtenteils plattformunabhängig verwendbar sind und für zahlreiche Anwendungsfälle bereits die passenden Lösungen bieten.

Der Name *Python* stammt nicht, wie man vielleicht vermuten könnte, von der Schlange, sondern von der britischen Comedy-Gruppe Monty Python. Der Entwickler der Sprache, Guido van Rossum, war ein großer Fan der Serie Monty Python’s Flying Circus. Als er Ende der 1980er Jahre eine neue Programmiersprache entwickelte, suchte er nach einem Namen, der kurz, einzigartig und einprägsam war. Dabei fiel seine Wahl auf *Python* als humorvolle Anspielung auf die berühmte Comedy-Gruppe.



(installationsempfehlungen)=
# Python installieren

Damit wir in der ersten Kurseinheit direkt starten können, bitten wir Sie, im Vorfeld die benötigte Entwicklungsumgebung zu installieren. Wir werden die Anaconda Distribution verwenden. Anaconda ist eine Python-Distribution, was bedeutet, dass es neben Python auch eine Vielzahl nützlicher Bibliotheken und Werkzeuge, wie **Jupyter Notebook** und ein eigenes System für virtuelle Umgebungen, mitbringt – all das, was wir in diesem Kurs verwenden möchten.

Anaconda bietet eine All-in-One-Lösung, die sowohl Python als auch wichtige Bibliotheken und Werkzeuge umfasst. Das **Jupyter Notebook** ist für diesen Kurs besonders praktisch, da es uns ermöglicht, in einer einzigen Datei sowohl Programmcode als auch Texte, Formeln und Bilder zu integrieren. So können wir beispielsweise die Aufgabenstellung direkt über dem Code platzieren und mit erläuterndem Text versehen. Dies schafft eine übersichtliche und interaktive Arbeitsumgebung, die das Lernen und die Bearbeitung der Übungen erleichtert.

Für die Installation von Anaconda gehen Sie bitte wie folgt vor:

## Schritt 1 - Anaconda herunterladen
Laden Sie Anaconda [hier](https://www.anaconda.com/download) herunter. Dazu müssen Sie zunächst Ihre E-Mail im rot umrandeten Rechteck eingeben und danach auf **Submit** drücken.
```{figure} ../img/anaconda/anaconda_installation_1.png
```

Anschließend erhalten Sie eine E-Mail, bei der Sie den Button **Download Now** drücken müssen.
```{figure} ../img/anaconda/anaconda_installation_2.png
```
Sie werden zu einer Seite weitergeleitet, auf der Sie zunächst ihr Betriebssystem auswählen müssen, um dann die entsprechende Datei herunterzuladen. Für jedes Betriebssystem haben wir die richtige Wahl rot umrandet. 
```{figure} ../img/anaconda/anaconda_installation_3.png
```
Nun haben Sie die aktuelle Version von Python (Python 3.12) heruntergeladen.

## Schritt 2 - Anaconda installieren
Starten Sie den heruntergeladenen Installer. Klicken Sie so lange **Next >** und **I Agree** bis Sie den Dateipfad wählen
müssen. Unter Windoes wählt Anaconda zum Beispiel den Pfad `C:\Users\Username\anaconda3` als Standard. 
```{figure} ../img/anaconda/anaconda_installation_4.png
```
Wir empfehlen diesen Standardpfad nicht zu ändern. Falls Sie dies dennoch tun möchten, achten Sie darauf, dass am Ende des Dateipfades `[…]\anaconda3` bzw.  `[…]\anaconda` steht. Ansonsten wird das übergeordnete Verzeichnis, in unserem Beispiel `Username`, mit diversen Dateien zugemüllt.


Abschließend müssen Sie Einstellungen auswählen, bevor Sie den Download durchführen. Wir empfehlen die Standardeinstellungen nicht zu ändern. Ihre Auswahl sollte wie folgt aussehen:
```{figure} ../img/anaconda/anaconda_installation_5.png
```
Nun können Sie **Install** drücken. Anaconda wird nun installiert.

## Schritt 3 - Anaconda starten
Zum Abschluss möchten wir noch sicherstellen, dass der Download tatsächlich einwandfrei verlaufen ist. Starten Sie dazu den Anaconda Navigator. Sie finden ihn, wenn Sie in ihrem Computer/Laptop nach Anaconda suchen.
```{figure} ../img/anaconda/anaconda_installation_6.png
```

\
Hier starten Sie das bereits mitinstallierten Jupyter Notebook:
```{figure} ../img/anaconda/anaconda_installation_7.png
```
Jupyter Notebook funktioniert für die Standardbrowser Google Chrome, Mozilla Firefox und Microsoft Edge sehr gut. In dem entsprechenden Browser öffnet sich ein Fenster das wie folgt aussehen sollte:
```{figure} ../img/anaconda/anaconda_installation_8.png
```
Wenn Sie hier angekommen sind, ist der Download erfolgreich gewesen. Genaueres zur Funktionsweise von **Jupyter Notebooks** finden Sie im [kommenden Kapitel](./funktionsweise_jupyter_notebook.md). Falls Sie Probleme beim Download haben, nutzen Sie Ihre bevorzugte Suchmaschine (oder ChatGPT). Ansonsten versuchen wir die Probleme gemeinsam in der ersten Kurseinheit zu lösen. 




