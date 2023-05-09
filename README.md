# Subnetting

## Obbiettivo:
### Riprodurre utilizzare le regole di subnetting per creare due sottoreti della stessa dimensione a partire dall'immagine allegata

## Risoluzione:
### Prima di tutto ho riprodotto la rete come nell'immagine assegnataci dal prof
### ![struttura](/subnetting/subnetting1.png)

### In seguito abbiamo assegnato il giusto ip alle porte del router con la realtiva subnetmask che ci permette di sapere quanti dispositivi possiamo avere all'interno della rete per ogni porta
### ![Config Router](/subnetting/subnetting2.png)

### Dopo aver eseguito ciò abbiamo assegnato a ogni dispositivo per di entrambe le sottoreti un ip con un gateway che ci permette di collegarci al router
### ![config disp](/subnetting/subnetting3.png)

### Ci rimane quindi da assegnare anche la subnet a ogni dispositivo cosi che possano comunicare anche con l'altra rete, quindi dato che la nostra rete e suddivisa in 2 ognuna delle due reti potrà contenere fino a 128 dispositivi 
### ![subnet](/subnetting/subnetting4.png)

### Infine non ci resta che verificare che i dispostivi di una delle due sottoreti riescano a comunicare coi dispositivi dell'altra sottorete, quindi effetuiamo un ping e verifichiamo che arrivino i pacchetti
### ![verifica](/subnetting/subnetting5.png)
### Quindi come possiamo notare i pacchetti sono arrivati e quindi i dispositivi riescono a cumincare 

