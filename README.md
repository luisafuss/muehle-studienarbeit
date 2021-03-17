# Studienarbeit - Entwicklung einer KI für das Brett-Spiel "Mühle"

Das Spiel Mühle ist ein bekanntes Brettspiel, das sich aufgrund der vergleichsweise einfachen Regeln ohne allzu großen Aufwand implementieren lässt. Ziel der Arbeit ist die Entwicklung eines Jupyter-Notebooks, in dem das Mühle-Spiel implementiert wird. Das Spiel soll mit Hilfe der Sprache Python implementiert werden. Die grafische Oberfläche soll mit Hilfe von [ipywidgets](https://ipywidgets.readthedocs.io/en/latest/) und [ipycanvas](https://ipycanvas.readthedocs.io/en/latest/) gestaltet werden. 

Die eigentliche Spiellogik soll mit Hilfe von alpha-beta-Pruning implementiert werden. Zusätzlich sollten Transpositions-Tabellen verwendet werden. Diese Verfahren sind in dem Skript zur KI dokumentiert. 

Ziel der Arbeit ist die Erstellung eines gut dokumentierten Programms, an Hand dessen die verschiedenen Techniken bei der Erstellung einer Spiele-KI im Rahmen der KI-Vorlesung vorgestellt werden können. 

## Getting started
### erstes Mal
Zunächst sollte das Projekt geklont werden. Darin enthalten ist die Datei `environment.yml`, die genutzt werden kann, um eine virtuelle Umgebung inklusive aller benötigen Libraries zu erhalten.

Um das Environment zu erstellen, muss im Projektordner über die Anaconda Prompt folgender Befehl aufgerufen werden:

```
conda env create -f environment.yml
```
### jedes Mal
Die eingerichtete Umgebung kann mit Hilfe des folgenden Befehls aktiviert werden:
```
conda activate muehle
```

Als nächstes kann Jupyter notebook mit folgendem Befehl gestartet werden:
```
jupyter notebook
```
Das Mühle-Spiel kann über das Notebook `Muehle_Game.ipynb` gestartet werden.

Um den Kernel herunterzufahren kann der Shortcut `Crtl + c` in der Anaconda Prompt genutzt werden.

Zum Verlassen des Environments dient der Befehl

```
conda deactivate
```