## Inhalt
> #### Was ist Markdown*?
> #### *Wer* hat es erstellt?
> #### *Warum* es verwenden?
> #### *Wie* zu verwenden?
> #### *Wer* verwendet?
> #### Probieren Sie es aus

## mk als Server
https://www.mkdocs.org/getting-started/
https://squidfunk.github.io/mkdocs-material/

## Einleitung
### 1. Was ist Markdown*?
**Markdown** ist eine leichte **Markup-Sprache**, die Dokumente im Klartext schreibt (*leicht zu lesen, leicht zu schreiben, leicht zu ändern*) und schließlich im HTML-Format veröffentlicht.
**Markdown** kann auch als Werkzeug zum Konvertieren von in MARKDOWN-Syntax geschriebenen Sprachen in HTML-Inhalte verstanden werden.

### 2. *Wer* hat es erstellt?
Es wurde von [**Aaron Swartz**](http://www.aaronsw.com/) und **John Gruber** mitgestaltet, **Aaron Swartz** befindet sich letztes Jahr (*11. Januar) , 2013 *) Suicide, ein Programmierer mit einer allgemeinen Lebenserfahrung der **Öffnung**. Wikipedias [Einleitung](http://zh.wikipedia.org/wiki/%E4%BA%9A%E4%BC%A6%C2%B7%E6%96%AF%E6%B2%83%E8%8C%A8) ist: **Software-Ingenieur, Autor, politischer Organisator, Internet-Aktivist, Wikipedia-Person**.

Er hat eine Lebenserfahrung, die ausreicht, um dich niederknien zu lassen:
+ **14 Jahre** war an der Formulierung der RSS 1.0-Spezifikationen beteiligt.
+ **Eingeschrieben in **Stanford** im Jahr 2004**, dann abgebrochen.
+ **Gründung von [Infogami](http://infogami.org/) im Jahr 2005**, dann Fusion mit [Reddit](http://www.reddit.com/), um Partner zu werden.
+ **Demand Progress wurde 2010 gegründet** und beteiligte sich aktiv am Prohibition of Internet Piracy Act (SOPA), der Vorschlag wurde schließlich zurückgezogen.
+ **Am 19. Juli 2011** wurde er festgenommen, weil er 4,8 Millionen wissenschaftliche Arbeiten vom MIT und JSTOR heruntergeladen und kostenlos ins Internet hochgeladen hatte.
+ **Selbstmord im Januar 2013**.

![Aaron Swartz](https://github.com/DWHR-Pi/Markdown/raw/master/resource/Aaron_Swartz.jpg)

Alle Genies haben ihren Weg nach Hause von einem frühen Tod.

### 3. *Warum* es benutzen?
+ Es ist leicht zu lesen (sieht angenehm aus), leicht zu schreiben (einfache Grammatik), leicht zu ändern **Klartext**. Der Schatten des **Minimalismus** ist überall.
+ Kompatibel mit HTML, kann zum Veröffentlichen in das HTML-Format konvertiert werden.
+ Plattformübergreifende Nutzung.
+ Immer mehr Websites unterstützen Markdown.
+ Organisieren Sie Ihre E-Mails bequemer und übersichtlicher. (Abschlag hier, Luftpost)
+ Word loswerden (ich meine das nicht ernst).

### 4. *Wie* zu verwenden?
Wenn Sie **Erweiterungen** nicht zählen, ist die Syntax von Markdown absolut **einfach**, sodass Sie sie nicht aus der Hand legen können.

Die Markdown-Syntax ist hauptsächlich in die folgenden Teile unterteilt:
**Titel**, **Absatz**, **Block-Zitat**, **Code-Block**, **Hervorhebung**, **Liste**, **Trennlinie**, **Link ** , **Bild**, **Backslash `\`**, **Symbol'`'**.

#### 4.1 Titel
Zwei Formen:
1) Verwenden Sie `=` und `-`, um primäre und sekundäre Überschriften zu markieren.
> Überschrift Ebene 1
> `=========`
> Nebenüberschrift
> `---------`

Wirkung:
> Überschrift Ebene 1
> =========
> Nebenüberschrift
> ---------

2) Verwenden Sie `#`, um Überschriften der Ebenen 1-6 anzuzeigen.
> \# Überschrift der ersten Ebene
> \## Nebenüberschrift
> \### Dreistufige Überschrift
> \#### Überschrift auf vier Ebenen
> \###### Fünfstufige Überschrift
> \###### Überschrift der sechsten Ebene

Wirkung:
> # Überschrift der ersten Ebene
> ## Nebenüberschrift
> ### Dreistufige Überschrift
> #### Überschrift auf vier Ebenen
> ##### Fünfstufige Überschrift
> ###### Überschrift der sechsten Ebene

#### 4.2 Absatz
Vor und nach dem Absatz sollten Leerzeilen stehen, die sogenannte Leerzeile bedeutet, dass kein Textinhalt vorhanden ist. Wenn Sie einen Zeilenumbruch in einem Absatz erzwingen möchten, verwenden Sie **zwei oder mehr** Leerzeichen und einen Zeilenumbruch (der Zeilenumbruch wird für den Zeilenumbruch im Anführungszeichen weggelassen).

#### 4.3 Blockangebot
Verwenden Sie das Symbol `>` in jeder Zeile des Absatzes oder nur in der ersten Zeile. Sie können auch mehrere verschachtelte Anführungszeichen verwenden, wie zum Beispiel:
> \> Blockreferenz
> \>> Verschachtelte Referenzen

Wirkung:
> Blockreferenz
>> Verschachtelte Referenzen

#### 4.4 Codeblock
Die Einrichtung des Codeblocks besteht darin, jeder Zeile 4 Leerzeichen oder einen Tabulator hinzuzufügen (genau wie beim Schreiben von Code). mögen    
Ein gewöhnlicher Absatz:

void main()
{
    printf("Hallo, Markdown.");
}


Codeblock:  
Als Codeblock mit Tabulatoren realisiert. 

    void main()
    {
        printf("Hallo, Markdown.");
    }

**Hinweis**: Zwischen dem normalen Absatz muss eine Leerzeile stehen.

#### 4.5 Betonung
Fügen Sie `*` oder `_` auf beiden Seiten des hervorgehobenen Inhalts hinzu, wie zum Beispiel:
> \*Kursiv\*, \_Kursiv\_
> \*\*Fett\*\*, \_\_Fett\_\_

Wirkung:
> *kursiv*, _kursiv_
> **Fett**, __Fett__

#### 4.6 Liste
Verwenden Sie `·`, `+` oder `-`, um ungeordnete Listen zu markieren, wie zum Beispiel:
> \-(+\*) Das erste Element
> \-(+\*) Das zweite Element
> \- (+\*) das dritte Element

**Hinweis**: Es gibt mindestens ein _Leerzeichen_ oder _Tab_ nach der Markierung. Wenn es sich nicht im zitierten Block befindet, muss zwischen dem vorhergehenden Absatz eine Leerzeile stehen.

Wirkung:
> + Erstes Element
> + Zweites Element
> + Drittes Element

Die Markierungsmethode einer geordneten Liste besteht darin, die obigen Symbole durch Zahlen zu ersetzen, ergänzt durch ".", wie zum Beispiel:
> 1. Der erste Artikel
> 2. Der zweite Punkt
> 3. Der dritte Punkt

Wirkung:
> 1. Der erste Artikel
> 2. Der zweite Punkt
> 3. Der dritte Punkt

#### 4.7 Trennlinie
Die häufigste Verwendung von Trennlinien sind drei oder mehr `*` Sie können auch `-` und `_` verwenden.

#### 4.8 Link
Links können in zwei Formen generiert werden: **inline** und **Referenz**.

**Inline-Stil**:
> \[Markdown-Bibliothek von DWHR-Pi\]\(https://github.com/DWHR-Pi/Markdown "Markdown"\).

Wirkung:
> [Markdown-Bibliothek von DWHR-Pi](https://github.com/DWHR-Pi/Markdown "Markdown").

**Referenz**:
> \[DWHR-Pi's Markdown-Bibliothek 1\]\[1\]
> \[DWHR-Pi's Markdown-Bibliothek 2\]\[2\]
> \[1\]:https://github.com/DWHR-Pi/Markdown "Markdown"
> \[2\]:https://github.com/DWHR-Pi/Markdown "Markdown"

Wirkung:
> [DWHR-Pi Markdown-Bibliothek 1][1] 
> [DWHR-Pi Markdown-Bibliothek 2][2] 

[1]: https://github.com/DWHR-Pi/Markdown "Markdown"
[2]: https://github.com/DWHR-Pi/Markdown "Markdown"

**Hinweis**: Das obige `[1]:https://github.com/DWHR-Pi/Markdown "Markdown"` erscheint nicht im Block.


#### 4.9 Titel des verborgenen Inhalts 

Mit diesen Code kann man das Dokument übersichtlicher gestalten und aufklappbare Flächen für Text, Bilder usw. erstellen.  

Codeblock:
```
### Titel des verborgenen Inhalts 
<details>
<summary>Inhaltesbeschreibung im Kuzen
</summary>
Der verborgene Inhalt, wird erst sichtbar, sobald man diesen aufgeklappt hat.
</details>
```
Wirkung:
### Titel des verborgenen Inhalts 
<details>
<summary>Inhaltesbeschreibung im Kuzen
</summary>
Der verborgene Inhalt, wird erst sichtbar, sobald man diesen aufgeklappt hat.
</details>


#### 5.0 Bilder
Die Form des Hinzufügens eines Bildes ähnelt der eines Links, fügen Sie einfach ein `vor dem Link hinzu ! `.
```
![Bild name](bild.jpg)
```
#### 5.10 Backslash `\`

Es entspricht **umgekehrter Bedeutung**. Machen Sie das Symbol zu einem gewöhnlichen Symbol.
```
\**Fettschrift**
```
Wirkung:
\**Fettschrift**

#### 5.11 Das Symbol'`'
Spielen Sie die Rolle der Markierung. mögen:
>\`Strg+a\`

Wirkung:
>`Strg+A`

#### 6.0 *Wer* verwendet?
Markdown-Benutzer:
+ GitHub
+ Kurzes Buch
+ Stapelüberlauf
+ Apollo
+ Moodle
+ Reddit
+ Warte

#### 7.0 Probieren Sie es aus
+ **Chrome**-Plugins wie `stackedit` und `markdown-here` sind sehr praktisch, und Sie müssen sich keine Sorgen um Plattformeinschränkungen machen.
+ Die dillinger.io-Rezension von **Online** ist auch gut
+ MarkdownPad unter **Windowns** wurde ebenfalls verwendet, aber die Erfahrung mit der kostenlosen Version ist nicht sehr gut.
+ The Mou unter **Mac** wird von Chinesen beigesteuert und hat einen guten Ruf.
+ ReText unter **Linux** ist gut.

**Natürlich ist der letzte Bereich immer Grammatik im Stift, formatiert in meinem Kopf :). **

****
**Hinweis**: Unterschiedliche Markdown-Interpreter oder -Tools haben unterschiedliche Interpretationseffekte auf die entsprechende Grammatik (erweiterte Grammatik). Einzelheiten entnehmen Sie bitte der Anleitung des Tools.
Obwohl einige Leute sich melden wollten, um einen sogenannten standardisierten Markdown zu machen, [unerwartet hat dies auch den lebenden Gründer John Gruber verärgert](http://blog.codinghorror.com/standard-markdown-is-now-common-markdown/).
****
Das Obige ist im Grunde die Syntax aller traditionellen Markdowns.

### 7.1 Tabellen:
Verwenden Sie `|`, um die vertikale Begrenzung der Tabelle anzugeben, trennen Sie die Kopfzeile und den Inhalt der Tabelle mit `-` und verwenden Sie `:` für die Ausrichtungseinstellungen. Wenn auf beiden Seiten ein `:` steht, bedeutet dies zentriert Wenn Sie `:` nicht hinzufügen, wird standardmäßig linksbündig angezeigt.

```
|Codebasis |Link |
|:------------------------------------:|------------------------------------|
|MarkDown |[https://github.com/DWHR-Pi/Markdown](https://github.com/DWHR-Pi/Markdown "Markdown")|
|MarkDownCopy |[https://github.com/DWHR-Pi/Markdown](https://github.com/DWHR-Pi/Markdown "Markdown")|
```
Wirkung:

|Codebasis |Link |
|:------------------------------------:|------------------------------------|
|MarkDown |[https://github.com/DWHR-Pi/Markdown](https://github.com/DWHR-Pi/Markdown "Markdown")|
|MarkDownCopy |[https://github.com/DWHR-Pi/Markdown](https://github.com/DWHR-Pi/Markdown "Markdown")|

### Andere:
Verwendung von Listen (nicht traditioneller Abschlag):



Weitere erweiterte Syntax finden Sie in den Anweisungen des jeweiligen Tools.