# Data-Exploration_Kundensegmentierung
## Segmentierung von Kundendaten

Kundensegmentierung Durchführung einer Kundensegmentierung von Supermarktdaten mit Orientierung an vier Businessfragen zur Verfeinerung der Zielgruppe zum exakteren Einsatz von Werbung. 
Die Segmentierung der Kundendaten kann relevante Informationen über die Kunden liefern und die Zielgruppen für die jeweiligen Produktgruppen oder einzelnen Produkte genauer eingrenzen und beleuchten. Daraus folgt, dass Werbung genauer geschaltet und platziert werden kann. Es könnte Werbung für jeden geschaltet werden, ohne eine Kundensegmentierung durchzuführen, oder es kann Werbung nur für die relevanten potenziellen Käufer erscheinen und das Geld gespart werden, was die Schaltung der Werbung für jeden auch nicht-potentiellen Kunden gekostet hätte. Die Segmentierung von Kundendaten eines Supermarktes liefert dem Supermarkt zusätzlich die Möglichkeit seinen Kundenstamm genauer einzuschätzen und so den Fokus des Sortiments anzupassen. Bei der Kundensegmentierung wird zuerst festgelegt welche Merkmale der Kunden relevant sind und über die Einteilung in ein Kundensegment entscheiden. Danach werden die Kunden anhand der Merkmale in Cluster eingeteilt. Hier wurde dieser Prozess Produktbezogen durchgeführt und auf Basis der vorher ausgewählten Businessfragen und nicht primär Kundenbezogen.
Die eingeteilten Cluster geben Hinweise auf die Zielgruppe der ausgewählten Produktgruppen oder einzelnen Produkte.

## Zielsetzung 

Nachdem die Daten bereinigt wurden, wurden Zielgruppen definiert, um mit Werbung gezielter eine spezifische Zielgruppe zu erreichen. Dazu wurden die Kundendaten eines Supermarktes zum Einkaufsverhalten untersucht und vier konkrete Fragen zur Analyse aufgestellt: 

- Kaufen Kunden mit Kindern mehr Süßigkeiten?  

- Kaufen Kunden mit höherem Einkommen mehr Fleisch bzw. Fisch? 

- Kaufen Kunden mit einem höheren Bildungsgrad mehr Wein? 

- Präferieren Kunden bestimmte Werbekanäle? 

## Gruppenmitglieder:
Mya Jahic, Hannah Laier, Julia Pfützer

## Ausführung des Quellcodes	
Ausführung des Quellcodes
Zum Öffnen der Datei wird ein Programm benötigt, dass ein Jupyter Notebook ausführen kann, wie zb. Anacona oder Visual Studio Code. Bei Visual Studio Code wird noch eine Extension benötigt, dass die Datei geöffnet werden kann. Wichtig ist bei Anaconda die Jupyter Shell nicht zu schließen. 
Der zweite Schritt vor dem Ausführen der Datei ist das Runterladen der benötigten Pakete.

### Technologien
Projekt wird erstellt mit:
-    pandas-Version: 1.3.0
-    numpy-Version: 1.21.0
-    matplotlib.pyplot-Version: 3.4.2
-    mpl_toolkits.mplot3d-Version: 
-    seaborn
-    scipy.cluster.hierarchy-Version: 1.6.2
-    sklearn.cluster
	
### Konfiguration
Um dieses Projekt auszuführen, installieren Sie es lokal mit pip:

```
$ pip install pandas [https://pandas.pydata.org/docs/getting_started/install.html]

$ pip install numpy [https://numpy.org/install/]

$ python -m pip install -U pip
$ python -m pip install -U matplotlib [https://matplotlib.org/stable/users/installing/index.html]

$ pip install seaborn [https://seaborn.pydata.org/installing.html]

$ python -m pip install --user scipy [https://scipy.org/install/]

$ pip install -U scikit-learn [pip install -U scikit-learn]

```
Danach kann der Code ausgeführt werden. Jede Zelle kann einzeln ausgeführt werden und die Zellen können aufeinander aufbauen. 
Falls ein Fehler auftritt, kann es daran liegen, dass alle Zellen nochmal ausgeführt werden müssen.
