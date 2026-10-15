# Zelda3 – traduzione italiana

Traduzione amatoriale in italiano dei dialoghi di *The Legend of Zelda: A Link to the Past* per [Zelda3 HD](https://github.com/ghost19880/zelda3), la reimplementazione in C del gioco.

I nomi seguono la terminologia ufficiale italiana raccolta su [Zelda Wiki](https://zeldawiki.wiki) (Amuleti, Calzari di Pegaso, Palazzo Cupo, Rocca Tartaruga…), con l'eccezione voluta di *Villaggio Calbarico*.

## Uso

Non serve fare niente a mano: il [launcher](https://github.com/ghost19880/Zelda-3-Launcher) scarica `dialogue_it.txt` quando nelle impostazioni scegli **Italian** e prepara da solo il font con le lettere accentate.

A mano: copia `dialogue_it.txt` nella cartella `assets` del gioco ed esegui `python make_font_it.py` e poi `python restool.py --languages=it` nella stessa cartella; infine metti `Language = it` in `zelda3.ini`.

Serve sempre una copia della ROM americana originale: qui c'è solo il testo tradotto.

---

*Italian fan translation of the dialogue for [Zelda3 HD](https://github.com/ghost19880/zelda3). Used automatically by the launcher when Italian is selected. A Link to the Past is © Nintendo; this repository contains no ROM data.*
