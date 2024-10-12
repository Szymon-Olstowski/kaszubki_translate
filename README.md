
# Make sure you have upgraded version of pip
Windows
```
py -m pip install --upgrade pip
```

Linux/MAC OS
```
python3 -m pip install --upgrade pip
```
# required package
```
pip install beautifulsoup4
```
# Project description
The package uses the beautifulsoup4 package which uses the page to fetch a word from the page: https://kaszebe.org/.
The package itself can translate short sentences, because too long code causes errors and you have to use the word not in capital letters because it won't translate correctly.
# Who use a pacpage?
```
from kaszubski_translate_Szymtest import a
print(a.tlumacz_p_k(""))
This a function print translate from Polish to Kashubian.
print(a.tlumacz_k_p(""))
This a function print translate from Kashubian to Polish.

```