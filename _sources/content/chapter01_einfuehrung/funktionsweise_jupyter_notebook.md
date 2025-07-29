(jupyter-notebook-nutzung)=
# Wie nutzt man Jupyter-Notebooks?

Da wir zu jedem der ersten 10 Kurseinheiten eine externe .ipynb-Datei mit zusätzlichen Übungen anbieten, geben wir Ihnen eine kurze Einführung wie man Jupyter Notebooks verwendet. Öffnen Sie Jupyter Notebook über den **Anaconda Navigator** wie [Infos zu Python](./installationsguide.md) beschrieben. 

Um eine neue Datei zu erstellen, drücken Sie am rechten Bildrand auf **New** und wählen **Python 3** (siehe rotes Rechteck).
```{figure} ../img/jupyter_notebook/Jupyter_Notebook_1.png
```
Falls Sie eine bereits existierende Datei öffnen möchten, nutzen Sie die **File** und **Open** Taste.
```{figure} ../img/jupyter_notebook/Jupyter_Notebook_2.png
```
Wenn Sie eine neue Datei öffnen sieht diese wie folgt aus:
```{figure} ../img/jupyter_notebook/Jupyter_Notebook_3.png
```
der blaue Streifen auf der linken Seite zeigt eine Zelle an. In dieser Zelle können Sie Code hineinschreiben. Dies funktioniert analog zum Live-Code in diesem Jupyter Book. Fall Sie eine zusätzliche Zeile hinzufügen wollen, nutzen Sie den **Insert** Button. Sie können eine Zelle oberhalb oder unterhalb der aktuell ausgewählten Zelle (mit einem blauen Streifen links hinterlegt) einfügen. Wenn Sie eine Zelle ausführen möchten, Nutzen Sie **Cell** und **Run Cells**. Alternativ können Sie die Zelle auch auswählen und **Strg + Enter** drücken. 
```{figure} ../img/jupyter_notebook/Jupyter_Notebook_4.png
```
Jupyter Notebook besitzt einige Tastenkombinationen, die einen bestimmten Befehl ausführen. Wir möchten Ihnen an dieser Stelle eine Übersicht über die wichtigsten **Shortcuts** geben:

```{list-table}
* - `Shift + Enter`
  - Führt die ausgewählte Zelle aus und wählt anschließend die Zelle darunter aus
* - `Strg + Enter`
  - Führt die ausgewählte Zelle aus
* - `a`
  - Fügt oberhalb der ausgewählten Zelle eine weitere Zelle hinzu
* - `b`
  - Fügt unterhalb der ausgewählten Zelle eine weitere Zelle hinzu
* - `d`
  - löscht (engl. *delete*) die ausgewählte Zelle
* - `m`
  -  Ändert den Zelltyp zu *Markdown*
* - `y`
  - Ändert den Zelltyp zu *Code*
```


Wichtig ist zu bemerken, dass der Befehl immer für die gerade ausgewählte Zelle ausgeführt wird, also die Zelle die am linken Bildrand blau markiert ist. 
Die Shortcuts `m` und `y` ändern die Art der Zelle. Dies kann auch über **Cell Type** gemacht werden.
```{figure} ../img/jupyter_notebook/Jupyter_Notebook_6.png
```
Der Zelltyp ist dafür verantwortlich, was angezeigt wird, wenn man die Zelle ausführt. Code-Zellen verhalten sich genau so wie die Live-Code Zellen dieser Seite. Markdown-Zellen hingegen verhalten sich wie eine Text-Zelle. Das heißt, hier kann man Texte schreiben, die das Notebook strukturieren und erklären. Den Unterschied beider Zellen sehen sie hier:
```{figure} ../img/jupyter_notebook/Jupyter_Notebook_8.png
```
Die rote Markdown-Zelle ist in Text, der erklärt, was im Notebook gemacht wird. Die blaue Code-Zelle ist tatsächlicher Python-Code. In den meisten Fällen werden wir Ihnen bereits Markdown-Zellen bereitstellen, die erklären, was getan werden soll. Manchmal kann es dennoch sinnvoll sein, dass Sie Ihrem Notebook mehr Struktur geben und selbst Markdown-Zellen hinzufügen.


Falls Sie das aktuell ausführende Notebook stoppen möchten, können Sie über den **Kernel** und **Interrupt** den Durchlauf unterbrechen. Außerdem können Sie über den **Restart & Run All** Button den aktuellen Durchlauf stoppen und das Notebook von der ersten Zelle an durchlaufen lassen.
```{figure} ../img/jupyter_notebook/Jupyter_Notebook_7.png
```
