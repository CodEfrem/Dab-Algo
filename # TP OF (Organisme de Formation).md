# TP OF (Organisme de Formation)

Prépavenir a besoin d'un système de gestion pour les demandes d'inscription aux formations du catalogue.

### Le catalogue 

- Développeur Web et Web Mobile 
- Concepteur Développeur d'Applications 
- Webdesigner
- Référencement SEO  
  
  Le programme sera utilisé par 2 personnes ( un admin et un assistant),  l'objectif étant de faciliter la gestion du processus d'inscription des futurs élèves.

  ---

  Prise de notes : 
  Est ce que les futurs apprenant peuvent postuler à plusieurs? 
        oui ils peuvent postuler à plusieurs mais devront choisir une seule formation

---

Le postulant va sur le site de la formation et clique sur la rebruique "candidature"

Il y a le choix de toutes les formation, il peut cliquer sur une d'elles.
    SI la session de candidature est fermé
         ALORS il ne pourra pas Cliquer dessus
         Il ne peut pas postuler
SINON 
    La session est encore disponible 
    Il peut postuler 
La page affiche ensuite le formulaire 
Le postulant peut remplir le formulaire directement sur la page et envoyer son CV sur un Upload-section

Il obtient un numéro de suivi et un mot de passe pour suivre les étapes de sa candidature 
Lors de sa connexion il verra indiqué :
    Envoyé
    OU en cours de traitement 
    OU traitement terminé 
    OU Réponse


Du coté du centre ils recevront les candidatures 
Classé par formation : 
  OU Développeur Web et Web Mobile 
  OU Concepteur Développeur d'Applications 
  OU Webdesigner
  OU Référencement SEO

Vous donnerez l'indication sur l'étape de la candidature du postulant: 
    OU en cours de traitement 
    OU traitement terminé 
    OU Réponse 
        Une liste déroulente pour les réponse 
    SI réponse refusé 
        ALORS dossier archivé 
    SINON SI en Attente 
        ALORS Dossier garder dans la rubrique attente et envoyé en archivé si la personne n'est pas recontactée
    SINON SI Accepté 
        ALORS dossier envoyer dans personne a contacter 

    SI Le postulant à effectué la formation
        ALORS archivé dans un dossier ancien stagiaire. 
    



    
