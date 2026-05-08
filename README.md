# README-Opgave

Dokumenter følgende oplysninger ved hjælp af Markdown-syntaks:

a. En overskrift med titlen "Markdown Dokumentation".

b. En liste over fordelene ved at bruge Markdown.

c. Et kodeeksempel, der viser, hvordan man via JavaScript itererer et array vha. et for-loop ved at bruge Markdown.

d. Et kodeeksempel, der viser, hvordan man opbygger en navigation med 3 links vha. HTML ved at bruge Markdown.

e. Indsæt et billede og beskriv billedet kort.

f. Lav et citat fra en kendt person, og tilføj kilden.

g. Upload dit Markdown-dokument README.md til et GitHub repository

h. Del linket til dit GitHub repository ved at sende en mail til din underviser

# Markdown Dokumentaiton

## Lists

- lightweight text format
- define headings
- change style
- show links
- show code

```JS
// Et array med navne
let navne = ["Anna", "Peter", "Sara"];

// Iteration gennem arrayet med et for-loop
for (let i = 0; i < navne.length; i++) {
    console.log(navne[i]);
};
```

```html
<nav>
  <a href="index.html">Forside</a>
  <a href="about.html">Om os</a>
  <a href="contact.html">Kontakt</a>
</nav>
```

## Images

![Snemanden.](/images/snowman.jpeg "*Her ser du en stor lysende sneman*.")

> At rejse er at leve.  
> — H. C. Andersen

## Link

Link til [Google](https://www.google.com/search?q=at+rejse+er+at+leve&oq=at+r&gs_lcrp=EgZjaHJvbWUqDAgBECMYJxiABBiKBTIGCAAQRRg5MgwIARAjGCcYgAQYigUyBwgCEAAYgAQyBwgDEAAYgAQyBwgEEAAYgAQyBggFEEUYPDIGCAYQRRg8MgYIBxBFGDzSAQgyMzI5ajBqN6gCALACAA&sourceid=chrome&ie=UTF-8/).
