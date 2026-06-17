# Limiti e derivate

Web app didattica di **analisi matematica** per il triennio della scuola secondaria di secondo grado.
Tutto in un unico file (`index.html`): basta aprirlo nel browser, funziona anche offline
e da mobile. Nessuna dipendenza esterna.

Pensata come continuazione naturale di
[equazioni-disequazioni-sistemi](https://ventilii-gif.github.io/equazioni-disequazioni-sistemi/),
di cui riprende lo stile e l'impostazione.

## Sezioni

Ogni sezione è organizzata in tre momenti: **Teoria** (schede richiudibili), una **Simulazione**
interattiva da esplorare cambiando funzione e parametri, e la palestra **«Prova tu»** (quiz di
teoria + quiz di calcolo a risposta chiusa, con correzione e spiegazione immediate).

### Parte 1 · I limiti

1. **Concetto di limite** — idea intuitiva, definizione con gli intorni (ε–δ), limite finito e
   infinito, limite destro e sinistro. Simulazione: ci si *avvicina* al punto da entrambi i lati con
   tabelle di valori che mostrano la convergenza (o il salto, o l'infinito).
2. **Calcolo e forme indeterminate** — algebra dei limiti, forme determinate con l'infinito, le sette
   forme indeterminate, le tecniche di risoluzione (scomposizione, confronto dei gradi,
   razionalizzazione) e i limiti notevoli. Simulazione: ogni forma indeterminata viene risolta passo
   passo, con conferma numerica e grafica.
3. **Continuità e asintoti** — funzioni continue, le tre specie di discontinuità, asintoti verticali,
   orizzontali e obliqui. Simulazione: un punto di ispezione mobile classifica la continuità leggendo
   i limiti laterali, mentre il grafico mostra gli asintoti.

### Parte 2 · Le derivate

4. **Derivata e retta tangente** — rapporto incrementale, definizione di derivata come limite,
   significato geometrico (pendenza della tangente) e fisico (velocità), derivabilità e continuità.
   Simulazione: la **secante** scivola fino a diventare **tangente** (h → 0) e il rapporto incrementale
   tende a f′(x₀).
5. **Regole di derivazione** — derivate fondamentali e regole di linearità, prodotto, quoziente e
   funzione composta (catena), derivate di ordine superiore. Simulazione: la funzione e la sua
   derivata a confronto, con il legame fra segno di f′ e crescenza.
6. **Studio di funzione** — segno della derivata prima e monotonia, massimi e minimi, concavità e
   flessi (derivata seconda), schema completo e problemi di ottimizzazione. Simulazione: massimi,
   minimi e flessi evidenziati sul grafico con la striscia dei segni di f′.

## Utilizzo

- In locale: aprire `index.html` con un qualsiasi browser moderno.
- Online: attivabile con GitHub Pages (Settings → Pages → branch di pubblicazione); l'app sarà
  raggiungibile all'indirizzo `https://ventilii-gif.github.io/derivate/`.

I grafici sono disegnati su `<canvas>`; le funzioni delle simulazioni hanno derivate e punti notevoli
calcolati in forma esatta, così i valori mostrati (limiti, pendenze, estremi, flessi) sono corretti e
non semplici approssimazioni di comodo.
