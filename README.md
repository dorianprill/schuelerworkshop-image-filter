# schuelerworkshop-image-filter
Wie funktionieren eigentlich Bildfilter auf Social Media (und anderswo)?


## Setup
Dieses Repository enthält das Jupyter Notebook, welches Sie bereits aus dem Workshop kennen. 
Um das Notebook zu starten muss lediglich Python 3.9 oder höher installiert sein.

Bei der erstmaligen Verwendung muss eine neue virtuelle Umgebung für Python erstellt werden: 

```Bash
python -m venv env
```

Wobei "env" der Name des Ordners ist, in dem die virtuelle Umgebung angelegt werden soll (frei wählbar).  

Anschließend, wie auch vor jeder Verwendung, muss die virtuelle Umgebung aktiviert werden:

Linux/Mac:

```Bash
source env/bin/activate
```

Windows:

```Bash
env\Scripts\activate
```

Nach der Ausführung sollte in der Kommandozeile der Name der aktivierten virtuellen Umgebung vor dem Prompt erscheinen, hier z.B. `(env)`.  

Bei Erstverwendung muss einmalig das Jupyter Notebook und weitere Abhängigkeiten installiert in der aktivierten virtuellen Umgebung installiert werden:

```Bash
pip install -r requirements.txt
```




## Starten des Jupyter Notebooks

Nachdem die virtuelle Umgebung aktiviert wurde (siehe unter Setup), kann das Jupyter Notebook gestartet werden:

```Bash
jupyter notebook
```
