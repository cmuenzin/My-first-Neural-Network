# **Python Neuronales Netz**

Konstruktion eines neuronalen Netzes mit 2 Layern das lernen soll die Zahlen im MNIST Data Set korrekt zu kategorisieren

# Zielsetzung

Das Netz soll mit einem Teil der Daten trainiert werden um möglichst eindeutig zu kategorisieren

# Über die Daten

Das MNIST Set besteht aus tausenden 28 x 28 Pixel Sets (also insgesamt 784 Pixel pro Set) Auf den Pixel Grids ist in Grayscale eine Zahl von 0-9 abgebildet. Ist ein Pixel schwarz hat es den Wert 0, ist es weiß hat es den Wert 255. In der Matrix der Daten steht jede Spalte hinter der ersten für eines der 784 Pixel. In der ersten Spalte steht die Zahl die abgebildet ist - die Lösung. Folglich ist jede Zeile ein Datenset für ein 28x28 Grid
