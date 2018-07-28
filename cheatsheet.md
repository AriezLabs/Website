# Markdown Cheatsheet

Ctrl+F empfiehlt sich.

##Inline styles

Aussehen|Syntax
---|---
_Kursiv_|\_/Kursiv\_ (oder \*Kursiv\*)
__Fett__|\_\_Fett\_\_ (oder \*\*Fett\*\*)
`inline code`| \`inline code\`
~~Strikethru~~|\~~Strikethru\~~

##Weiteres

###Überschriften

Mit Rauten (\#) am Zeilenanfang; je mehr, desto kleiner, 1-5 Stück.

Eine Zeile lässt sich auch mit 5 `=`-Zeichen oder Bindestrichen in der Zeile darunter zu einer Überschrift machen (äquivalent zu `#` bzw. `##`).

###Links

erst eckige, dann runde Klammern. Ansonsten erst eckige Klammern, dann Referenznummer (z.B. `[1]`), unten dann `[1]: https://www.google.de` oder Linktext in eckige Klammern und dann unten `[Linktext]: URL`

###Bilder

wie Links, nur Ausrufezeichen vor der ersten Klammer:

```
![alt text](path)
```

###Zitate

mit > (und Space dahinter). Markdown in Quotes funktioniert.

> Quote

###HTML

HTML ist ohne Weiteres in Markdown einbettbar, aber Markdown in eingebettetem HTML bleibt ohne Funktion.

###Code snippets. 

3 Backticks (\`) gefolgt von Sprache (optional fuer Syntax Highlighting), gefolgt von Code, gefolgt von 3 weiteren Backticks. Es empfiehlt sich, den Code mittels Newlines von den Backticks zu seperieren (nötig, wenn eine Sprache angegeben wird).

``` javascript
var x = 250
var y = []
x - y //WTF?
```
###Horizontal rules.

3 Bindestriche: \-\-\-

---

###Tables.

Angabe der einzelnen Zeilen, Spalten getrennt mit \|, Kopfzeile getrennt durch eine zusaetzliche Zeile darunter, die zwischen jedem Trennsymbol \| mindestens 3 Bindestriche hat. 
In dieser Zeile kann Left/Right/Center Align der entsprechenden Spalte mit : links/rechts/beiderseits der Bindestriche angegeben werden.
