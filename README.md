# markdown
Guida Markdown

## Introduzione



### Cosa è il markdown?



- Il `markdown` è un linguaggio di marcatura leggero, che utilizza una sintassi per la formattazione in testo semplice
- Può essere convertito con facilità in html, xml, pdf e altri formati
- Il suo obiettivo principale è la leggibilità e la facilità d'uso
- Utilizza l'estensione `.md` oppure `.markdown` 



### Per cosa è usato il markdown?



- E' usato per i file leggimi (`readme.md` su `Github`, ecc.)
- E' usato nei messaggi su forum e blog
- E' usato in diversi generatori di siti statici
- Personalmente lo trovo molto utile per generare rapidamente documentazione tecnica su argomenti di informatica
- Github supporta una versione estesa di markdown, utilizzabile in vari elementi quali commenti e descrizioni di Issues e Pull Requests, che permette di inserire riferimenti agli utenti e ai commit tramite SHA-1 hash 



### Markdown Editors



- Estensioni/Plugin di diversi editor (vscode, atom, sublimetext, ...)
- Markpad
- HarooPad
- Markdown Pad 2
- Typora





## Elementi di formattazione



Tra i principali elementi di formattazione disponibili in markdown troviamo:



- le intestazioni per i titoli
- i blocchi di codice (i programmi che visualizzano il markdown  formattano automaticamente il codice di diversi linguaggi)
- liste puntate o numerate di elementi
- immagini
- elementi di enfasi: grassetto, sottolineato, ...
- citazioni di testo
- Link Internet
- Linee orizzontali
- Tabelle
- Task list





### Intestazioni



Le intestazioni vengono utilizzate per i titoli e corrispondono circa ai `tag <h1>, ... , <h6>` dell'`html`.



Esempio:

```markdown
# Titolo1
## Titolo2
### Titolo3
#### Titolo4
##### Titolo5
###### Titolo6
```



Siamo all'interno di un titolo3 (Intestazioni), quindi visualizziamo solo i titoli dal 4 al 6 per non alterare la struttura del documento.



Risultato: 

#### Titolo4
##### Titolo5
###### Titolo6





### Blocchi di codice



Per inserire un blocco di codice `inline` si può usare il carattere  backtick  (\`)  per delimitarlo.

Per inserire un codice di blocco multilinea si possono usare 3 backticks per delimitare, si può anche indicare a seguito delle 3 backticks di apertura il linguaggio da utilizzare per il syntax highlighting, tra quelli supportati.



Esempio:

~~~markdown
Esempio di `blocco di codice inline`, si utilizza un singolo backtick per delimitare!

Blocco di codice multilinea:
```
	if (isAwesome){
		return true
	}
```

Blocco di codice multilinea con linguaggio javascript:
```javascript
	if (isAwesome){
		return true
	}
```
~~~



Risultato:



Esempio di `blocco di codice inline`, si utilizza un singolo backtick per delimitare!



Blocco di codice multilinea:
```
	if (isAwesome){
		return true
	}
```

Blocco di codice multilinea con linguaggio javascript:
```javascript
	if (isAwesome){
		return true
	}
```





### Liste puntate o numerate



Per creare una lista numerata si usano i numeri seguiti da un punto, per indentare usare le `tabulazioni` oppure 2 spazi. Notare che la numerazione è automatica anche se vengono usati numeri diversi. 



Esempio:

```markdown
Lista numerata:

1. Persone
	1. Luigi
	2. Mario
2. Animali
	1. Gatto
	4. Cane
	3. Pappagallo
3. Cose
	1. Tavolo
	2. Fiore
	3. Martello
```



Risultato:



1. Persone
	1. Luigi
	2. Mario
2. Animali
	1. Gatto
	4. Cane
	3. Pappagallo
3. Cose
	1. Tavolo
	2. Fiore
	3. Martello



Per creare una lista puntata si può usare il carattere `-` oppure `*`, si può indentare con le `tabulazioni` oppure con 2 spazi. 



Esempio:

```markdown
Lista puntata:

- patate
	- dolci
	- per frittura
- carote
- melanzane

oppure

* patate
	* dolci
	* per frittura
* carote
* melanzane
```



Risultato:

- patate
	- dolci
	- per frittura
- carote
- melanzane





### Immagini



Per incorporare una immagine si può usare un punto esclamativo `!` seguito da una descrizione tra parentesi quadre `[]` e dalla url tra parentesi tonde `()`.



Esempio:

```markdown
![Immagine di un gatto](images/markdown/esempio_gatto.jpg)
```



Risultato:

![Immagine di un gatto](images/markdown/esempio_gatto.jpg)





### Elementi di enfasi



Abbiamo diversi tipi di enfasi:

- il grassetto, per cui si usa il delimitatore `**` oppure `__`
- il corsivo, per cui si usa il delimitatore `*` oppure `_`
- il cancellato, per cui si usa il delimitatore `~~`



Esempio:

```markdown
**Grassetto**
__Grassetto__

*Corsivo*
_Corsivo_

~~Cancellato~~
```



Risultato:

**Grassetto**
__Grassetto__

*Corsivo*

_Corsivo_

~~Cancellato~~





### Citazioni di testo



Esempio:

```markdown
> Citazione di testo
> Linea 2
```



Risultato:

> Citazione di testo
> Linea 2





### Links



Per creare un `link Internet` si possono usare le parentesi quadre `[]` seguite da quelle tonde `()` per specificare rispettivamente la `descrizione` e la `url` del link.

Github supporta anche l'autolink, in cui riconosce automaticamente tutte le url. 



Esempio:

```markdown
[link to Google!](http://google.com)

http://www.github.com/
```



Risultato:

[link to Google!](http://google.com)

http://www.github.com/





### Task list



Esempio:

```markdown
Task list:

- [x] Elemento completato
- [ ] Elemento non completato
```



Risultato:



Task list:

- [x] Elemento completato
- [ ] Elemento non completato


