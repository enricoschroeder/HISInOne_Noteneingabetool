Jupyter Noteneingabetool für HISinOne
================

Dieses Jupyter-Notebook ist ein interaktives Tool zur Noteneingabe in HISinOne.

Es können exportierte HISInOne Exceltabellen geladen werden, woraus eine interaktive Tabelle zum Eingeben der Punkte in einzelnen Aufgaben erzeugt wird.

Aus der Summe der Punkte können Noten berechnet werden sowie Statistken wie z.B. die Notenverteilung dargstellt werden.

Die Noten können dann wieder im HISinOne Format exportiert werden und in HISinOne hochgeladen werden.

Benutzung
---------

```
> python -m venv .venv
> source .venv/bin/activate
# oder Windows: .venv\Scripts\activate.bat
> pip install -r requirements.txt
> jupyter notebook Noteneingabe.ipynb
```
