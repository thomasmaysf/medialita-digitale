# Modulo 1 — Logica binaria e primi dispositivi

**Tema:** accoglienza, riflessione sul digitale in famiglia, logica binaria (teoria e pratica), riconoscere i «mattoni» comuni dei computer.

**Facilitazione:** un facilitatore o una facilitatrice con almeno un secondo adulto; per laboratorio hardware servono due adulti o più.

### Esempio di orario (da adattare)

| Blocco | Orario indicativo |
|--------|-------------------|
| Parte A — Cerchio | 9:00–10:20 |
| Pausa | 10:20–10:40 |
| Parte B — Teoria (binario) | 10:40–12:00 |
| Parte C — Dentro i dispositivi | 12:00–13:20 |

---

## Parte A — Cerchio

- Accoglienza, aspettative e domande dei ragazzi.
- Cosa fanno già con i dispositivi a casa.
- Presentazione della **scatola delle domande** per gli adulti (domande anonime per i facilitatori).

### Domande per il cerchio

1. Se potessi inventare un dispositivo, cosa farebbe?
2. Quando vedi un bambino di 3 anni con uno smartphone in mano, cosa provi?
3. Secondo te, come fa un telefono a "sapere" dove tocchi lo schermo?
4. Cosa vorresti chiedere a chi ha inventato internet o lo smartphone?
5. Hai mai iniziato qualcosa che poi non riuscivi più a fermare?
6. Secondo voi, siamo noi a comandare i dispositivi o sono loro a comandare noi?

Le domande 5 e 6 introducono la visione del cortometraggio Disney **Fantasia**, episodio *L’apprendista stregone*, per riflettere su una forza che non si controlla.

## Pausa

## Parte B — Logica binaria, teoria

*Esempio di orario: 10:40–12:00 (80 min).*

Si passa dall’**analogico al digitale** con l’esercizio principale sulle dita, poi la metafora dell’onda e della griglia alla lavagna, infine le schede esercizi.

**Tempi suggeriti (esempio, 80 min)**

| Blocco | Durata | Orario indicativo |
|--------|--------|-------------------|
| Step 1 — Contare in binario con una mano | 35 min | 10:40–11:15 |
| Step 2 — Le copie si allontanano | 25 min | 11:15–11:40 |
| Schede esercizi e chiusura | ~20 min | 11:40–12:00 |

### Materiali stampabili

PDF da stampare per attività sul pavimento o sul tavolo (ritagliare i gettoni se indicato nel foglio). Il tappetino binario serve allo **Step 1**; i tappetini delle porte logiche all’**extra** facoltativo di Parte B.

[:material-file-pdf-box: Scarica tappetino binario](modulo-1/files/tappetino-binario.pdf){ .md-button }
Tappetino a **bit** (0/1) con gettoni: per rappresentare numeri e sequenze in binario.

[:material-file-pdf-box: Scarica tappetini porte logiche](modulo-1/files/tappetini-porte-logiche.pdf){ .md-button }
Tre pagine di **tappetini** per porte logiche (AND, OR, NOT, …) con gettoni per ingressi e uscita.

### Step 1 — Contare in binario con una mano (0–31) (~35 min)

!!! important "Esercizio principale della Parte B"
    I ragazzi **vivono** il binario sulle proprie dita: cinque bit, numeri da 0 a 31, stessa logica dei gettoni sul [tappetino binario](modulo-1/files/tappetino-binario.pdf).

Metodo ispirato al *finger binary counting* descritto su [Art of Memory — Finger Binary Counting](https://artofmemory.com/wiki/Finger_Binary_Counting/) (palmo rivolto verso il viso, dita alzate = **1** / acceso, dita piegate = **0** / spento).

#### Valore delle dita (una mano)

| Dito | Potenza di 2 | Valore |
|------|--------------|--------|
| Pollice | 2⁰ | 1 |
| Indice | 2¹ | 2 |
| Medio | 2² | 4 |
| Anulare | 2³ | 8 |
| Mignolo | 2⁴ | 16 |

Il numero è la **somma** dei valori delle dita alzate. Tutte alzate = **31**; pugno chiuso = **0**.

Spiegate ai ragazzi: *«Ogni dito è un interruttore: su o giù. Non conta l’ordine in cui le alzate, conta **quali** sono su.»*

#### Tappetino e gettoni

Allineate mano e tappetino: ogni dito corrisponde a una colonna di bit; i gettoni 0/1 sul tappetino ripetono la stessa configurazione. Fate provare **3–4** numeri (es. 5, 10, 15) prima di andare veloci.

#### Tabella 0–31 (decimale, binario a 5 bit, dita alzate)

Bit in ordine **mignolo → pollice** (16, 8, 4, 2, 1), come sul tappetino.

| Dec | Binario | Dita alzate (ON) |
|-----|---------|------------------|
| 0 | 00000 | pugno chiuso |
| 1 | 00001 | pollice |
| 2 | 00010 | indice |
| 3 | 00011 | pollice, indice |
| 4 | 00100 | medio |
| 5 | 00101 | pollice, medio |
| 6 | 00110 | indice, medio |
| 7 | 00111 | pollice, indice, medio |
| 8 | 01000 | anulare |
| 9 | 01001 | pollice, anulare |
| 10 | 01010 | indice, anulare |
| 11 | 01011 | pollice, indice, anulare |
| 12 | 01100 | medio, anulare |
| 13 | 01101 | pollice, medio, anulare |
| 14 | 01110 | indice, medio, anulare |
| 15 | 01111 | pollice, indice, medio, anulare |
| 16 | 10000 | mignolo |
| 17 | 10001 | pollice, mignolo |
| 18 | 10010 | indice, mignolo |
| 19 | 10011 | pollice, indice, mignolo |
| 20 | 10100 | medio, mignolo |
| 21 | 10101 | pollice, medio, mignolo |
| 22 | 10110 | indice, medio, mignolo |
| 23 | 10111 | pollice, indice, medio, mignolo |
| 24 | 11000 | anulare, mignolo |
| 25 | 11001 | pollice, anulare, mignolo |
| 26 | 11010 | indice, anulare, mignolo |
| 27 | 11011 | pollice, indice, anulare, mignolo |
| 28 | 11100 | medio, anulare, mignolo |
| 29 | 11101 | pollice, medio, anulare, mignolo |
| 30 | 11110 | indice, medio, anulare, mignolo |
| 31 | 11111 | pollice, indice, medio, anulare, mignolo |

#### Sequenza progressiva in classe

1. **Solo pollice e indice (0–3), ~8 min** — Contate insieme da 0 a 3 più volte. *«Adesso aggiungete solo il medio e arriviamo fino a 7.»*
2. **Tre dita (0–7), ~7 min** — Ripetete fino a 7; poi *«Ogni dito nuovo **raddoppia** quanti numeri potete fare?»*
3. **Cinque dita (0–31), ~10 min** — Salite a 16 (solo mignolo), poi 17, … fino a 31. Celebrate il **31** tutti insieme.
4. **Giochi in coppia, ~7 min** — Uno mostra le dita, l’altro dice il numero; poi invertite. Variante: uno dice un numero, l’altro lo mostra.
5. **Giro veloce, ~3 min** — Il facilitatore o la facilitatrice chiama numeri a caso; chi risponde prima (mano giusta) vince un punto simbolico.

#### Domande per il cerchio (chiusura Step 1)

- Con **cinque** dita quanti numeri distinti possiamo fare? Perché il massimo è **31** e non 32?
- Con **due mani** (dieci dita), fino a quanto si arriva? *(1023 = 2¹⁰ − 1, come nella fonte.)*
- Se avessimo una sesta “dita”, quanti numeri in più? Cosa succede ogni volta che aggiungiamo un bit?
- Tenete a mente questi **bit** accesi o spenti: nello **Step 2** vedrete la stessa idea in una «scala» sulla lavagna.
- Otto bit fanno un **byte**: quanti byte servono per un numero più grande di 31?

Dopo i **bit** sulle dita (Step 1), passate all’**analogico** e al **digitale** sulla lavagna.

### Step 2 — Le copie si allontanano (25 min)

#### Materiali

- Gessi bianchi e colorati
- Carta lucida / vellum con griglia **grossa** e griglia **fine**
- Nastro adesivo
- Pennarelli
- Fogli quadrettati puliti

#### Parte 1 — L’onda e le sue copie (~7 min)

1. Chiedete un volontario che disegni un’**onda** sulla lavagna con il gesso bianco. Potete dirgli: *«Su e giù, come un’onda del mare, il più regolare possibile: due o tre volte da un lato all’altro della lavagna.»*
2. Tracciate due linee orizzontali come **limite in alto e in basso**, così l’onda resta dentro lo spazio che userete con le griglie.
3. Un secondo studente prova a **copiare la stessa onda**, con un gesso di colore diverso, appena sopra o sotto la prima.
4. Un terzo studente fa lo stesso, con un **terzo colore**.

Con tutte e tre le onde visibili, fatevi guidare da queste domande:

- Sono uguali? **Dove** sono più diverse?
- Tutti cercavano di copiare alla perfezione. Perché non ci sono riusciti?
- Se provassimo cento volte, qualcuno la farebbe **identica**? E come potremmo esserne sicuri?
- La prima onda è davvero perfettamente regolare? Il primo disegnatore voleva fare un picco più alto di un altro?

**Infinito e precisione**

- Dove sta **esattamente** la linea? Il gesso ha uno spessore. L’onda è al centro, sul bordo sopra o sul bordo sotto?
- Quanti punti ci sono sull’onda tra due vostre dita? Si potrebbero **contare** tutti?
- Potreste descrivere quest’onda a parole in modo così preciso che qualcuno in un’altra stanza disegni **la stessa identica**?

!!! abstract "Idea chiave (analogico)"
    Questo è il mondo **analogico**: la linea si muove senza salti, ci sono **infiniti** punti possibili, e ogni copia introduce un po’ di **errore**.

5. Cancellate la lavagna. Un nuovo studente disegna una **onda nuova** in bianco, sempre tra gli stessi limiti: sarà l’onda di riferimento per il resto dell’esercizio.

#### Parte 2 — La griglia grossa (~8 min)

1. Fissate con il nastro il vellum a **griglia grossa** sopra l’onda.
2. Un studente traccia l’onda con il pennarello seguendo una sola regola: *«Puoi muoverti solo lungo le linee della griglia — su, giù, destra o sinistra.»*

Domande mentre traccia:

- Qui l’onda passa **tra** due linee. Quale segui? Chi decide?
- Un altro compagno avrebbe scelto la stessa linea?

3. *(Consigliato)* Un secondo studente copia la **scala** su un foglio quadrettato pulito **contando i quadrati**, senza guardare l’onda. Le copie risultano **identiche**.

Osservazioni di gruppo:

- Cosa è successo all’onda? In cosa si è trasformata?
- Dove perde di più la scala: alle **cime**, o nel mezzo? Perché proprio lì?
- Ogni «gradino» della scala ha la stessa altezza? Perché no? (La griglia ha trattenuto anche il tremolio della mano.)
- La scala è «sbagliata», o solo **diversa**?
- Le copie a gesso non erano mai uguali. Perché le copie della scala sono uscite **uguali**?
- E se i quadrati fossero più alti dell’onda intera?

#### Parte 3 — La griglia fine (~6 min)

1. Sostituite il vellum grosso con quello a **griglia fine**, sempre sulla stessa onda.
2. Un nuovo studente la traccia allo stesso modo, solo lungo le linee.

Osservazioni di gruppo:

- Cosa è cambiato rispetto alla griglia grossa?
- Dove perde ancora qualcosa?
- Cosa ci è costato? (Più quadrati, più scelte, più lavoro.)

!!! tip "Risoluzione"
    **Risoluzione** significa quanto è **fine** la griglia: più i quadrati sono piccoli, più la scala assomiglia all’onda — ma il lavoro aumenta.

#### Parte 4 — Quanto deve essere fine per essere perfetta? (~4 min)

1. Mettete i due vellum **affiancati**, con l’onda bianca ancora visibile in mezzo.

Domande per arrivare all’idea finale:

- Quanto dovrebbe essere fine la griglia prima che non distinguiate più la scala dall’onda?
- Se non vedete differenze, significa che **non** ce ne sono?
- La griglia potrebbe diventare così fine da **essere** l’onda? Cosa succede se la rendiamo sempre più fine, all’infinito?
- Se ingrandissimo moltissimo la scala più fine, cosa vedreste?
- Quindi: cosa preferireste mandare a qualcuno lontano — l’onda o la scala? Perché?
- Un computer «preferisce» la scala (o i bit) all’onda continua: collegamento con lo **Step 1**?

!!! abstract "Idea chiave (il compromesso digitale)"
    La scala non sarà **mai** l’onda, ma può bastare ai nostri occhi e si può **copiare sempre uguale** — come i numeri 0–31 sulle dita allo Step 1. È il compromesso che fa il **digitale**.

### Extra (facoltativo) — Porte logiche con i tappetini

??? tip "Extra"
    Usate questo blocco **solo** se il gruppo chiude in anticipo le schede (11:40–12:00) o se alcuni ragazzi chiedono «un altro gioco» sul binario. Non è obbligatorio per arrivare alla Parte C.

Stampate i [tappetini delle porte logiche](modulo-1/files/tappetini-porte-logiche.pdf) (tre pagine: **AND**, **OR**, **NOT**) e ritagliate i gettoni 0/1 per ingressi e uscita.

1. **NOT (un ingresso):** un gettone in ingresso; l’uscita è l’opposto. *«Se qui metto 1, cosa deve uscire? E se metto 0?»*
2. **AND (due ingressi):** l’uscita è 1 **solo** se entrambi gli ingressi sono 1. Provate tutte e quattro le combinazioni sul tappetino.
3. **OR (due ingressi):** l’uscita è 1 se **almeno** un ingresso è 1.

In coppia o in squadre: un adulto legge una frase (*«Entrambi i genitori dicono sì»* → AND; *«Almeno uno vuole il gelato»* → OR) e i ragazzi impostano i gettoni. Collegate al binario: *«Ogni ingresso è un bit; la porta decide l’uscita come fa il computer, un passo alla volta.»*

---

## Parte C — Dentro i dispositivi {#parte-c-dentro-i-dispositivi}

*Esempio di orario: 12:00–13:20.*

Si attraversano quattro «taglie» di computer, dallo **desktop** al **telefono**, cercando sempre le stesse famiglie di componenti. Più il dispositivo è piccolo e integrato, meno i pezzi si vedono separati — ma la logica resta quella dei **transistor** che agiscono come interruttori (come i bit sulle dita in Parte B).

### Materiali

- Un **desktop** vecchio (tower) già **scollegato dalla rete**, con coperchio apribile
- **Due o tre laptop** (anche non funzionanti), uno eventualmente con base smontabile
- Una **Raspberry Pi** (scheda nuda o in case trasparente) con scheda microSD
- Un **smartphone** di scorta *oppure* foto / video di teardown approvati (se non si apre un telefono reale)
- Cacciaviti a croce e a taglio piccoli, vaschetta per viti, **tappetino antistatico** o superficie asciutta
- Etichette o lavagnetta per nominare i pezzi

### Sicurezza (obbligatoria)

- **Staccate la spina** prima di aprire il desktop; togliete la batteria del laptop se si apre il vano.
- **Non aprite** alimentatori ATX, batterie gonfie o smartphone con batteria danneggiata; **non toccate** condensatori o parti interne dell’alimentatore.
- **Solo gli adulti** maneggiano cacciaviti e componenti pesanti o taglienti; i ragazzi osservano a distanza di sicurezza.
- Indossate occhiali se rimuovete pannelli metallici; attenzione a **bordi affilati** nel chassis.
- Nessun dato personale sui dispositivi: usate hardware **wipato** o dedicato al laboratorio.

### Svolgimento

#### 1. Desktop aperto (~12 min)

1. Rimuovete il pannello laterale con un adulto che guida. Fate osservare il gruppo da vicino, senza toccare.
2. Individuate a voce alta, senza fretta: **scheda madre**, **CPU** (sotto il dissipatore), **RAM**, **scheda video** (se presente), **disco** HDD/SSD, **alimentatore** (solo **esterno**, senza aprirlo), **ventole**.
3. Chiedete: *«Se dovessimo disegnare questo computer come una mappa, quali sono i tre «quartieri»: dove si pensa, dove si ricorda per poco, dove si archivia?»*

#### 2. Laptop (~8 min)

1. Mostrate un portatile **chiuso e spento**, poi il vano (se accessibile): batteria, disco/SSD, ventola, scheda madre più compatta.
2. Confrontate con il desktop: *«Cosa è sparito in un unico pezzo? Cosa è diventato più piccolo?»*
3. Un secondo adulto può tenere il gruppo mentre l’altro smonta **solo** ciò che è previsto e reversibile.

#### 3. Raspberry Pi (~6 min)

1. Mostrate la scheda sul palmo: **SoC** (CPU+GPU insieme), slot **microSD** (memoria «disco»), porte USB, alimentazione **5 V**.
2. Spiegate: *«Qui quasi tutto è su un unico chip. È ancora un computer, ma pensato per costare poco e consumare poco.»*
3. Opzionale: collegatela a un monitor per mostrare che si accende — solo se avete tempo e setup pronto.

#### 4. Smartphone (~9 min)

1. **Non** è obbligatorio aprirlo: spesso bastano **foto** di teardown e un telefono spento per parlare di **schermo**, **batteria**, **fotocamera**, **antenne** nascoste.
2. Se mostrate un device aperto (solo adulti): evidenziate che **CPU/GPU/RAM** sono nel **SoC**, la memoria flash è saldata, il raffreddamento è quasi tutto **passivo**.
3. Messaggio chiave: *«Riconoscete il «computer» dentro? Stesse idee del tower, ma impacchettate come in una barretta di cioccolato.»*

### Tabella comparativa (semplificata)

| Componente / funzione | Desktop | Laptop | Raspberry Pi | Smartphone |
|----------------------|---------|--------|--------------|------------|
| Elaborazione (CPU / GPU) | CPU e scheda video spesso separate | CPU/GPU integrati, meno spazio | SoC unico sul chip | SoC unico, non sostituibile |
| Memoria di lavoro (RAM) | Moduli DIMM visibili | Saldata o su slot stretti | Chip sulla scheda | Integrata nel SoC |
| Archiviazione | HDD / SSD, cavi visibili | SSD NVMe o SATA compatto | Scheda microSD | Flash saldata |
| Alimentazione | Alimentatore esterno (non aprire) | Batteria + caricabatterie | USB / GPIO 5 V | Batteria + ricarica |
| Raffreddamento | Ventole e dissipatori grandi | Ventola / heat pipe | Spesso passivo | Quasi tutto passivo |

### Domande per il gruppo

- Quale pezzo avete **riconosciuto** subito? Quale no?
- Perché nel telefono è difficile vedere la «scheda madre» come nel desktop?
- Dove sono, secondo voi, i **miliardi di interruttori** di cui parlava il binario sulle dita?
- Tutti questi apparecchi hanno bisogno di **energia** e di **non surriscaldarsi**: cosa notate di diverso tra tower e smartphone?
- Se un computer è solo tanti ON/OFF velocissimi, perché ci serve ancora parlare di **onde** e **analogico** (Parte B)?

!!! abstract "Idea chiave"
    Desktop, laptop, Raspberry Pi e smartphone sono **computer** con gli stessi ingredienti: transistor che fanno da interruttori (i **bit** che avete contato con le dita), organizzati in **elaborazione**, **memoria**, **archiviazione**, **alimentazione** e **gestione del calore**. Più il dispositivo è integrato, meno vedete i pezzi — ma la logica è la stessa.

---

## Regole operative per questo modulo

Vedi anche [Regole generali](../regole-generali.md). In sintesi:

- Tutti gli adulti di facilitazione presenti per **tutto** il modulo; chi non parla sta in fondo e aiuta la sorveglianza.
- Fotocopie al minimo; **quaderno per ogni ragazzo**.
- Riepilogo dell’incontro precedente alla lavagna (al modulo 1: introduzione al percorso).
- **Timbro del patentino** a fine incontro.
