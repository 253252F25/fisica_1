# Fisica 1

## Cinematica
La cinematica è la parte della meccanica che studia **il moto dei corpi senza considerare le cause che lo producono**.

Nel nostro sistema di riferimento che può essere un piano cartesiano, le coordinate polari o qualsiasi altro sistema La posizione è **un vettore** che individua **un corpo rispetto all’origine di un sistema di riferimento**. tramite: #localizzazione #modulo e #direzione 

Lo spostamento è il cambiamento di posizione di un corpo. Anche questo è un vettore, quindi ha modulo (quanto ti sei spostato in linea retta) direzione verso (da posizione iniziale a finale)
![[fig4.png]]


$\Delta r = r2 - r1$

> **spostamento ≠ distanza percorsa** +20m -10m = 30m (distanza percorsa) e 10m di spostamento


Per facilitare lo studio semplifichiamo il moto di un oggetto con il moto di un **punto materiale**  cioè di un punto senza le dimensioni.
Lungo una sola direzione **moto rettilineo**. 
![[fig5.png]]
 

Nella figura vediamo il tracciato di un ascensore che procede dal piano terra al primo piano sulle assi il tempo è definito con $t$ e lo spostamento con $x$ 

> Il diagramma in figura si chiama diagramma orario 

Per descrivere il movimento di un corpo si introducono le grandezze di #posizione, #spostamento, #tempo, #velocità e #accelerazione.

### Il tempo 
Il tempo è uno delle unita di misura riconosciute dal SI si misura in $s$ (secondi) 

### Spostamento 
Lo spostamento e la misura che si rileva nel esperimento generalmente per ottenere questo valore effettuiamo due misure in due tempi diversi otteniamo quindi due coppie di valori $\{t_1, x_1\}$ e $\{t_2, x_2\}$ 

Per ottenere lo spostamento e il tempo impiegato usiamo quindi queste due formule:
$$ tempo\_impiegato = t_2-t_1 $$
$$ spostamento = x_2-x_1 $$
 
![[fig6.png]]
### Velocità (Vettoriale media)
La velocità è il rapporto tra lo spostamento e il tempo che si è impiegato per completare il movimento.
$$
velocita
= 
\frac{spostamento}{tempo\_impiegato}  
= 
\frac{\Delta x}{\Delta t}
$$

Questa è detta anche **Velocità Vettoriale Media** che graficamente è rappresentata dalla pendenza della retta passate dai due punti che sono le nostre rilevazioni ovvero il coefficiente angolare $m$ della retta.
$$X(t) = m·t + x_0$$
### Velocità (Scalare Media)
La definizione di **velocità vettoriale media** utilizza lo spostamento ${\Delta x}$ Tuttavia lo spostamento tiene conto solo della posizione iniziale e finale e non del percorso effettivamente seguito dal corpo.

Se durante il moto il corpo **cambia direzione**, lo spostamento può risultare molto più piccolo della distanza realmente percorsa.
 
Per questo motivo si introduce la **velocità scalare media**, definita come il rapporto tra **spazio totale percorso** e **tempo impiegato**.

$$v_{scalare} = \frac{s}{\Delta t}$$

dove la $s$ tiene conto di tutte le posizioni e le somma 

### Velocità (istantanea)
La misura tuttavia più vicina alla quotidianità di velocità e la velocità istantanea cioè la velocità che troviamo nel quadro strumenti delle nostre auto. questa rappresenta la velocita che il corpo ha nel momento della rilevazione.
nel nostro grafico Essa coincide con il coefficiente angolare $m$ della retta tangente alla funzione della posizione tempo.

L'operazione matematica che ci permette di trovare la retta tangente ad una funzione è la derivata della funzione che descrive i movimento.
quindi usiamo
$$
v = \frac{dx}{dt}
$$


### Grafico della posizione, velocità e accelerazione
  ![[fig9a.png]]
In questo grafico vediamo che la velocita non è costante ma che aumenta (accelerazione) esegue un tratto a velocita costante per poi rallentare (decelerare).

per prima cosa scomponiamo in diversi tratti da calcolare 

#### Tratto 0 - A 
in questo tratto vediamo che non c'è spostamento quindi la velocità è nulla.
* $V_a = \frac{\Delta x}{\Delta t} = \frac{0-0}{1-0} = 0 m/s$ 
* $V_d = \frac{\Delta x}{\Delta t} = \frac{26-26}{10-9} = 0 m/s$  

#### Tratto B-C
in questo tratto la velocita è costante quindi possiamo usare la formula della velocita media
 
* $V_{bc}= \frac{\Delta x}{\Delta t}= \frac{24-4}{8-3}=4 m/s$ 

#### Tratti AB e CD
I tratti che rimangono sono i tratti AB e CD cioè quelli di accelerazione e decelerazione 
Qui non possiamo approssimare a nessuna funzione consueta quindi useremo la derivata per ottenere la velocita 
$$v= \frac{dx}{dt}$$
inserendo i risultati otteniamo questo grafico
 
![[fig9b.png]]
Proprio come la velocità è la variazione della posizione, l'accelerazione è la variazione della velocità nel tempo. Le formule fondamentali da usare sono:

- **Accelerazione Media:** $\vec{a}=\frac{\Delta\vec{v}}{\Delta t}$
    
- **Accelerazione Istantanea:** $\vec{a}=\frac{d\vec{v}}{dt}$ (che equivale anche alla derivata seconda della posizione: $\frac{d^{2}\vec{x}}{dt^{2}}$)
![[fig9c.png]]
 
- La formula $x(t) = x(t_0) + \int_{t_0}^{t} v(t') dt'$ ci dice che la posizione in un dato istante $x(t)$ è uguale alla posizione iniziale $x(t_0)$ più lo spostamento totale avvenuto in quell'intervallo di tempo.

- **Significato grafico:** L'integrale della velocità nel tempo ($\int v \cdot dt$) corrisponde all'**area sottesa alla curva** (o alla linea) nel grafico della velocità.

# L3P13 