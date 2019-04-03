# Übung - 02: Perzeptron und neuronale Netze

## Ziel der Übung

Das Ziel der Übung ist , das ein tieferes Verständnis für das Perzeptron und für neuronale Netze entwickelt wird. Dabei geht es darum die Funktionsweise und Aufbau einmal selber nachzubauen.

---

## Aufgabe 1

Gegeben sind die Mengen  M+={(0, 1.5),(2,0.25),(1,1)} und M-={(-1.0, 0.75),(-0.4,1),(0.5,-1.0)}

1. Zeigen Sie graphisch, dass diese linear separierbar sind.
2. Wenden Sie die Perzeprtron-Lernregel auf diese Mengen an und geben Sie eine mögliche Folge der Werte für den Gewichtsvektor an. Starten sie mit dem Gewichstvektor w=(1,1).
3. Programmieren Sie die Perzeptron-Lernregel in einem Jupyter Notebook in Python und wenden Sie ihr Programm auf die Menegn M+ und M- an. Unterscheidet sich die Lösung von ihrer Berechnung?

## Aufgabe 2

In dieser Augabe wird versucht eine 3 schichtiges-NN zu erstellen (Input-1 Hidden Layer - Output) und zu berechnen. Als Datensatz dienen hierzu die Ziffern (1-3) in einem Raster (4x5) als Beispiel fuer handgeschriebene Zahlen.

Importieren Sie das ([Naive-MNIST-KNN](Naive-MNIST-KNN.ipynb)) in ihre Jupyter Notebook Umgebung und versuchen sie die Aufgabe zu lösen. Hierbei geht es darum ein einfaches Neuronales Netz incl. Hidden-Layer zu beschreiben und den Backprogation-Algorithmus zu implementieren.