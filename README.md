# Wikilabs

In wikilabs possibile inserire laboratori in aree già esistenti o in nuove aree.

Per inserire un laboratorio è necessario produrre un file di testo con le seguenti caratteristiche:

* il nome del file deve contenere la data e il titolo e deve avere estensione md (markdown) aaaa-mm-gg-titolo.md
* nell'intestazione del file ci possono essere questi attributi inseriti fra le tre linee (---)

```
---
layout: laboratory
title: inserire titolo
author: inserire autore 
categories: inserire tipo laboratorio ad es. ['Laboratori del fare']
target: ad es. Tutti, famiglie, bambini (10 persone per volta)
abstract: inserire abstract
duration: inserire durata del laboratorio ad es. 30 min.
cards_attach: inserire nomi dei file che con le schede
results_attach: inserire nome dei file che con i risultati ad es. ["filerisultati.pdf","filerisultati2.pdf",...]
events: inserire eventi in cui è stato tenuto il laboratorio ["evento 1","evento 2", ]
image: file immagine
---
```
* può essere inserita una descrizione del laboratorio dopo la chiusura delle linee.

* per inserire un nuovo tipo di laboratorio è sufficiente inserire una nuova categoria in **categories**. Prima di inserire una nuova categoria verificare le categorie esistenti

* i file attach devono essere caricati in public/attaches

* le immagini devono essere caricate in public/images

* i laboratori devono essere caricati in _posts

* è possibile prevedere nuovi attributi. Ad esempio potremo aggiungere dati e informazioni di consuntivo, video ecc...

* Il sistema si autoconfigura rispetto a eventi e tipi di laboratori non appena caricato il file.

* Il testo dei laboratori può essere scritto usando il formato [markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

* Per le immagini è meglio usare rapporto 16/9 

## Author

**Alessandra Donnini**
- <https://github.com/etcware>

## License

This theme and application is available as open source under the terms of the [MIT
License](https://github.com/Dopolavoro-Matematico/dopolavoro-matematico.github.io/blob/main/LICENSE.md).


