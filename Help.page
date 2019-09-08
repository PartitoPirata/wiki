---
format: Markdown
title: Guida
...

# Navigazione

Il modo più naturale di navigare le pagine è di cliccare i link che
collegano le pagine l'una con l'altra. Il link "Prima Pagina" che si
trova nella barra di navigazione laterale ti porterà sempre alla
pagina iniziale della Wiki. Il link "Tutte le pagine" ti porterà alla
lista di tutte le pagine della Wiki, organizzate in cartelle se sono
presenti sottodirectory. In alternativa, puoi usare la funzione
"Cerca". Nota che la funzione di ricerca agisce su parole intere, per
cui se devi cercare "gremlins", inserisci questa parola, e non
"gremlin". Se conosci il nome della pagina, puoi usare la funzione
"Vai".

# Creare e modificare pagine

## Registrazione di un account

Per poter modificare le pagine, dovrai loggarti nella Wiki. Per
registrare il tuo account, clicca su "Non Autenticato" e segui il
link presente nel testo "If you do not have an account, click here
to get one."
Dovrai scegliere un nome utente e una password, che potrai quindi
usare per loggarti cliccando sul bottone "Login". Quando sarai
loggato dentro, il bottone "Login" sarà sostituito da "Logout", che
potrai utilizzare per effettuare il logout una volta terminata la
tua sessione di lavoro.

Nota che i login utilizzano i cookie di sessione, quindi se non
esegui il logout sarai ancora loggato dentro quando tornerai alla
Wiki dallo stesso browser.

## Modificare una pagina

Per modificare una pagina, clicca il bottone "Modifica" nell'angolo
in alto a sinistra.

Puoi cliccare su "Preview" in ogni momento per vedere come appaiono
le tue modifiche. Nulla è salvato fino a quando non premi "Salva".

Nota che è necessario aggiungere una descrizione alle tue modifiche.
Questo serve a rendere più semplice per gli altri vedere come la pagina
è stata cambiata.

## Metadati della pagina

Le pagine possono opzionalmente iniziare con un blocco di metadati. Per
esempio:

    ---
    format: latex+lhs
    categories: haskell matematica
    toc: no
    title: Haskell e
      Teoria delle Categorie
    ...

    \section{Introduzione}

Il blocco dei metadati consiste in una lista di coppie chiave-valore,
ognuna su una linea separata. Se necessario, il valore può continuare
sulla riga seguente, purché inizi con uno spazio. (Questo è illustrato
dal valore di `title` qui sopra.) Il blocco dei metadati deve iniziare
con una linea con `---` e terminare con una linea con `...`, seguita
facoltativamente da una o più righe vuote.

Currently the following keys are supported:

format
:   Overrides the default page type as specified in the configuration file.
    Possible values are `markdown`, `rst`, `latex`, `html`, `markdown+lhs`,
    `rst+lhs`, `latex+lhs`.  (Capitalization is ignored, so you can also
    use `LaTeX`, `HTML`, etc.)  The `+lhs` variants indicate that the page
    is to be interpreted as literate Haskell.  If this field is missing,
    the default page type will be used.

categories
:   A space or comma separated list of categories to which the page belongs.

toc
:   Overrides default setting for table-of-contents in the configuration file.
    Values can be `yes`, `no`, `true`, or `false` (capitalization is ignored).

title
:   By default the displayed page title is the page name.  This metadata element
    overrides that default.

## Creating a new page

To create a new page, just create a wiki link that links to it, and
click the link.  If the page does not exist, you will be editing it
immediately.

## Reverting to an earlier version

If you click the "history" button at the bottom of the page, you will
get a record of previous versions of the page.  You can see the differences
between two versions by dragging one onto the other; additions will be
highlighted in yellow, and deletions will be crossed out with a horizontal
line.  Clicking on the description of changes will take you to the page
as it existed after those changes.  To revert the page to the revision
you're currently looking at, just click the "revert" button at the bottom
of the page, then "Save". 

## Deleting a page

The "delete" button at the bottom of the page will delete a page.  Note
that deleted pages can be recovered, since a record of them will still be
accessible via the "activity" button on the top of the page.

# Uploading files

To upload a file--a picture, a PDF, or some other resource--click the
"upload" button in the navigation bar.  You will be prompted to select
the file to upload.  As with edits, you will be asked to provide a
description of the resource (or of the change, if you are overwriting
an existing file).

Often you may leave "Name on wiki" blank, since the existing name of the
file will be used by default.  If that isn't desired, supply a name.
Note that uploaded files *must* include a file extension (e.g. `.pdf`).

If you are providing a new version of a file that already exists on the
wiki, check the box "Overwrite existing file." Otherwise, leave it
unchecked.

To link to an uploaded file, just use its name in a regular wiki link.
For example, if you uploaded a picture `fido.jpg`, you can insert the
picture into a (markdown-formatted) page as follows: `![fido](fido.jpg)`.
If you uploaded a PDF `projection.pdf`, you can insert a link to it
using:  `[projection](projection.pdf)`.



# Markdown

This wiki's pages are written in [pandoc]'s extended form of [markdown].
If you're not familiar with markdown, you should start by looking
at the [markdown "basics" page] and the [markdown syntax description].
Consult the [pandoc User's Guide] for information about pandoc's syntax
for footnotes, tables, description lists, and other elements not present
in standard markdown.

[pandoc]: http://pandoc.org
[pandoc User's Guide]: http://pandoc.org/README.html
[markdown]: http://daringfireball.net/projects/markdown
[markdown "basics" page]: http://daringfireball.net/projects/markdown/basics
[markdown syntax description]: http://daringfireball.net/projects/markdown/syntax 

Markdown is pretty intuitive, since it is based on email conventions.
Here are some examples to get you started:

<table>
<tr>
<td>`*emphasized text*`</td>
<td>*emphasized text*</td>
</tr>
<tr>
<td>`**strong emphasis**`</td>
<td>**strong emphasis**</td>
</tr>
<tr>
<td>`` `literal text` ``</td>
<td>`literal text`</td>
</tr>
<tr>
<td>`\*escaped special characters\*`</td>
<td>\*escaped special characters\*</td>
</tr>
<tr>
<td>`[external link](http://google.com)`</td>
<td>[external link](http://google.com)</td>
</tr>
<tr>
<td>`![folder](/img/icons/folder.png)`</td>
<td>![folder](/img/icons/folder.png)</td>
</tr>
<tr>
<td>Wikilink: `[Front Page]()`</td>
<td>Wikilink: [Front Page]()</td>
</tr>
<tr>
<td>`H~2~O`</td>
<td>H~2~O</td>
</tr>
<tr>
<td>`10^100^`</td>
<td>10^100^</td>
</tr>
<tr>
<td>`~~strikeout~~`</td>
<td>~~strikeout~~</td>
</tr>
<tr>
<td>
`$x = \frac{{ - b \pm \sqrt {b^2 - 4ac} }}{{2a}}$`
</td>
<td>
$x = \frac{{ - b \pm \sqrt {b^2 - 4ac} }}{{2a}}$^[If this looks like
code, it's because jsMath is
not installed on your system.  Contact your administrator to request it.]
</td>
</tr>
<tr>
<td>
`A simple footnote.^[Or is it so simple?]`
</td>
<td>
A simple footnote.^[Or is it so simple?]
</td>
</tr>
<tr>
<td>
<pre>
> an indented paragraph,
> usually used for quotations
</pre>
</td>
<td>

> an indented paragraph,
> usually used for quotations

</td>
<tr>
<td>
<pre>
    #!/bin/sh -e
    # code, indented four spaces
    echo "Hello world"
</pre>
</td>
<td>

    #!/bin/sh -e
    # code, indented four spaces
    echo "Hello world"

</td>
</tr>
<tr>
<td>
<pre>
* a bulleted list
* second item
    - sublist
    - and more
* back to main list
    1. this item has an ordered
    2. sublist
        a) you can also use letters
        b) another item
</pre>
</td>
<td>

* a bulleted list
* second item
    - sublist
    - and more
* back to main list
    1. this item has an ordered
    2. sublist
        a) you can also use letters
        b) another item

</td>
</tr>
<tr>
<td>
<pre>
Fruit        Quantity
--------  -----------
apples         30,200
oranges         1,998
pears              42

Table:  Our fruit inventory
</pre>
</td>
<td>

Fruit        Quantity
--------  -----------
apples         30,200
oranges         1,998
pears              42

Table:  Our fruit inventory

</td>
</tr>
</table>

For headings, prefix a line with one or more `#` signs:  one for a major heading,
two for a subheading, three for a subsubheading.  Be sure to leave space before
and after the heading.

    # Markdown

    Text...
 
    ## Some examples...
   
    Text...

## Wiki links

Links to other wiki pages are formed this way:  `[Page Name]()`.
(Gitit converts markdown links with empty targets into wikilinks.)

To link to a wiki page using something else as the link text:
`[something else](Page Name)`.

Note that page names may contain spaces and some special characters.
They need not be CamelCase.  CamelCase words are *not* automatically
converted to wiki links.

Wiki pages may be organized into directories.  So, if you have
several pages on wine, you may wish to organize them like so:

    Wine/Pinot Noir
    Wine/Burgundy
    Wine/Cabernet Sauvignon

Note that a wiki link `[Burgundy]()` that occurs inside the `Wine`
directory will link to `Wine/Burgundy`, and not to `Burgundy`.
To link to a top-level page called `Burgundy`, you'd have to use
`[Burgundy](/Burgundy)`.

To link to a directory listing for a subdirectory, use a trailing
slash: `[Wine/]()` will link to a listing of the `Wine` subdirectory.
