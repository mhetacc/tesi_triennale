# Tesi Triennale
<p align="center">
    <img src="immagini/logo-unipd.png" alt="UniPd logo" width="220">
</p>

[![Build Latex documents](https://github.com/Bug-s-Bunny-Team/docs/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/Bug-s-Bunny-Team/docs/actions/workflows/build.yml)

## Introduzione
Questo repository contiene i sorgenti *Latex* per compilare la tesi di laurea e i lucidi della discussione (in *beamer*). 
I documenti compilati in formato *PDF*, e in versione stabile, si trovano nella cartella [pdf](pdf/).

## Prerequisiti
### Latex
È necessario installare una [distribuzione Latex](https://www.latex-project.org/get/) prima di poter compilare i documenti. Per esempio, su Windows, usando [MiKTeX](https://miktex.org/l).
A questo punto sarà sufficiente compilare il file 
```tex
tesi.tex
```
Tutte le configurazioni del documento sono invece contenute nel preambolo, in
```tex
tesi-config.tex
```

Per quanto riguarda la presentazione, invece, è sufficiente compilare il file
```tex
presentazione.tex
```

## Struttura
| Cartella                | Contenuto                      |
|-------------------------|--------------------------------|
| [pdf](pdf/)            | Tesi e lucidi della discussione in formato *PDF*  |
| [presentazione](presentazione/)             | Sorgenti necessari alla build *beamer* per i lucidi|
| [capitoli](capitoli/) | Sorgenti dei capitoli in *Latex*  |

