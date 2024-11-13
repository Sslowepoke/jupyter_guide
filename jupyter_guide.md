# jupyter notebook smernice
## instaliranje python-a
- otvorite terminal
komande:
- `python --version` - proverava verziju pythona, ako ga nema kaze da ga nema
- `python` - instalira python 
- mozete iz microsoft store-a naci verziju koju hocete i skinuti

## pravljenje virtualnog okruzenja
- terminal u direktorijumu gde hocete da ga napravite
- `pip install --upgrade pip` - update-uje pip
- `pip install virtualenv`
- dodate virtualenv na PATH
- `virtualenv ime`
- `ime\Scripts\activate`
- aktivirano je virtuelno okruzenje za python

## instaliranje neophodnih biblioteka u virtuelno okruzenje
- `pip install -r po-requirements.txt`
- `pip install ime-biblioteke`

## pokretanje jupyter-a u browser-u
- `jupyter lab`
- BITNO: treba da se nalazimo u direktorijumu gde nam je projekat i da je aktivno virtuelno okruzenje gde su nam instalirane biblioteke

## pokretanje jupyter-a u vscode-u
- instaliramo python i jupyter ekstenziju
- otvorimo folder projekta kao workspace
- kliknemo na .ipynb fajl

# Koriscena dokumentacija i zanimljivi materijali
[dos elektronika uputstvo](http://tnt.etf.rs/~19e043dos/vezbe.php)
[variable explorer u jupyter-u](https://stackoverflow.com/questions/37718907/variable-explorer-in-jupyter-notebook)
[guide za jupyter](https://medium.com/@pedrohcordeiroj/use-virtual-environment-with-jupyter-notebook-1f238cab1073)
[psae predavanja](https://www.youtube.com/watch?v=0ybWaKqOUuA&list=PLLfxHIsIFJ5bcdNOcL3t7-9ulWXcE4uog)

