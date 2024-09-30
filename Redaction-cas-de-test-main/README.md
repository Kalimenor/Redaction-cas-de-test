# Rédaction de cas de test / test fonctionnel
Afin de nous familiariser avec la rédaction de cas de test et les bonnes pratiques concernant l'exécution de tests, nous avons mis en place des tests fonctionnels sur trois modules du site de notre organisme de formation.<br/> Le but est de tester les différents modules afin de déceler les éventuels défauts.<br/>

### Le tableau de synthèse est consultable [ICI](https://docs.google.com/spreadsheets/d/1Jrd9wfgYacOR8oP4kxeDFXGI0FDILyfVdYa4s2JK7Ac/edit?gid=0#gid=0).



#### URL de la page: https://inscription.it-akademy.fr/ <br/>
#### **Module à tester (test fonctionnel):**
<img src="img/crea.png" width="250" height="400" />   <img src="img/cone.png" width="250" height="400" />   <img src="img/mdp.png" width="250" height="400" />
#### **Test non-fonctionnel:** 
  - Test de compatibilité navigateur (chrome, safari, edge, opéra...)
  - Test des messages d'erreur
  - Test de l'état de déconnexion 

#### Déroulé:
  - Définition dela stratégie de test
    - Regle de nommage
    - Stratégie de test fonctionnel
    - Stratégie de test non-fonctionnel
  - Rédaction des cas de test
  - Execution des tests
  - Automatisaton des tests --> [Script Python](script/test_connexion.py)

## Voici un appercu des étapes clés 
#### Règles de nommage
<img src="img/nom.png" width="700" height="350" />

#### Rédaction des cas de test 
![redaction cas de test](https://github.com/user-attachments/assets/dd2e1ed3-bfe9-48df-b92c-014a3905da41)

#### Mise en place d'un tableau de synthèse 
![Capture d'écran 2024-09-30 120344](https://github.com/user-attachments/assets/286ec0ab-daa3-4c73-bc26-d39ba7ab614a)

#### Automatisation des tests --> [Script Python](script/test_connexion.py)
<img src="img/auto.gif" width="900" height="450" />
