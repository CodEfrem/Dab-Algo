# Algorithme DAB

Conception d'un algorithme de DAB*, sous forme de pseudo-code.

 * Distributeur Automatique de Billets*

---

```text
Le client insère sa carte dans le distributeur
le precessus de vérification de la carte est lancé
SI la carte n'est pas conforme
        ALORS le distributeur rejette la carte
    SINON SI la carte est bloquée
        ALORS le distributeur avale la carte
        Le programme s'arrête
    SINON 
        la carte est valide
        Lancer la demande du code de la carte
Le distributeur affiche un message "demandant le code de la carte"
Le client tape un code 
    SI le code est incorrect
        ALORS les distributeur affiche un message "code incorrect" 
        ET le compteur d'essai est incrémenté de 1
        SI le compteur de tentative est égal à 3
            ALORS le distributeur avale la carte
            Le programme s'arrête
        Lancer la demande du code de la carte 
    SINON
        Le code est correct
        Lancer la demande du montant à retirer
le distributeur affiche un message "demandant de choisir un momant à retirer"
Le client choisi un montant
Le processus de vérification de solde du client est lancé
    SI le montant > Le solde || (ou) le montant > plafond
        Le retrait est refusé
        Le distributeur affiche un message
        Le distributeur relance la demande du montant à retirer
    SINON
        Le retrait est autorisé
        Le processus de vérification de solde du DAB est lancé
            SI le montant > le solde
            Le retrait est refusé
            Le distributeur affiche un message
        Le distributeur relance la demande du montant à retirer
    SINON
            Le retrait est autorisé
            le distributeur remet le montant choisi
Le client récupère la carte bancaire du distributeur 
Le client récupère l'argent du distributeur
Fin du programme
``` 