# Discola

Briscola a due, scritta in Delphi 3 nel 1997 da Diego Amicabile e portata sul
web. Qui trovi l'app per Android e le regole; per giocare subito nel browser
vai su **<https://discola.netlify.app>**.

## Scarica

- **Android:** prendi il file `.apk` dall'[ultima release](https://github.com/diegoami/discola-releases/releases/latest),
  aprilo sul telefono e consenti l'installazione da questa fonte. È la stessa
  versione del sito, ma si gioca senza connessione: le carte, i caratteri e
  tutto il resto sono dentro l'app, e niente lascia il telefono.

Ogni release riporta il checksum SHA-256 dei file in `SHA256SUMS.txt`. Windows o
Android possono avvisarti che l'app viene da uno sviluppatore sconosciuto: è
normale per un'app distribuita fuori dagli store.

## Le regole

La briscola a due con un mazzo italiano da 40 carte: quattro semi — denari,
coppe, spade, bastoni — e in ogni seme le carte da 1 (asso) a 10 (re), passando
per fante (8), cavallo (9) e re (10).

**Come si vince.** Vince la partita chi arriva per primo a **61 punti su 120**.

**Valore delle carte.** I punti stanno quasi tutti in cinque carte per seme:

| Carta | Punti |
|---|---:|
| Asso | 11 |
| Tre | 10 |
| Re | 4 |
| Cavallo | 3 |
| Fante | 2 |
| 7, 6, 5, 4, 2 | 0 |

Cinque per seme fanno 30 punti, per quattro semi fanno i 120 in gioco.

**Chi batte chi.** Quando due carte non contano i punti ma decidono chi prende,
l'ordine dentro un seme è: **Asso, Tre, Re, Cavallo, Fante, 7, 6, 5, 4, 2** —
l'asso e il tre stanno sopra le figure, che è la sorpresa di chi arriva da altri
giochi.

**La briscola.** A inizio partita l'ultima carta del mazzo viene girata scoperta
e il suo seme è la *briscola*, che vale più di ogni altro seme per tutta la mano.

**La presa.** Chi gioca per primo cala una carta qualsiasi; l'avversario risponde
con quella che vuole — non c'è obbligo di rispondere al seme. La presa la vince:

- una briscola su una non-briscola;
- fra due briscole, o fra due carte dello stesso seme, quella più alta
  nell'ordine qui sopra;
- se i semi sono diversi e nessuna è briscola, **la carta di chi ha aperto**: la
  risposta di un altro seme non prende.

Chi vince la presa incassa le due carte, pesca per primo dal mazzo e apre la
presa successiva. Quando il mazzo finisce si gioca con le carte in mano fino
all'ultima.

## Gli avversari

Quattro, gli stessi del 1997, ognuno con il suo carattere:

| Avversario | Carattere |
|---|---|
| **Valerio** | Lo standard della casa. Equilibrato. |
| **Graziano** | Il più sciolto: brucia le briscole presto. |
| **Piero** | Cambia carattere a ogni sessione. |
| **Franco** | Il più tirchio: si tiene le briscole fino in fondo. |

E cinque mazzi fra cui scegliere: Trevisane, Piacentine, Napoletane, Romagnole e
Francesi — le immagini originali del programma del 1997.

## Un dettaglio

L'icona dell'app è il fante di spade delle Trevisane. In Veneto quella carta si
chiama *la vecia*, la vecchia — anche se di vecchia non ha niente e i baffi ce li
ha eccome. Non chiedete perché: è così e basta.

## Provenienza

- Sorgente Delphi del 1997: [`diegoami/discola-PAS`](https://github.com/diegoami/discola-PAS)
- Gioca nel browser: <https://discola.netlify.app>

Questo repository contiene solo le release scaricabili. Il codice della versione
web è privato.
