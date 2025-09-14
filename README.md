# Rapport sur la façon de créer un bon prompt scientifique en utilisant des blocs de construction

Les prompts efficaces sont essentiels pour guider l’IA générative afin qu’elle produise des résultats précis et pertinents.

## Question : Vous êtes-vous déjà demandé pourquoi certaines réponses de l’IA sont très exactes alors que d’autres ne le sont pas ?

La différence réside souvent dans la façon dont le prompt est formulé. 

Un prompt est une instruction ou une question donnée à une IA pour l’orienter dans la génération d’une réponse. Pour créer des prompts de haute qualité, il est utile de les structurer autour de six blocs de construction clés : TÂCHE, CONTEXTE, MODÈLE, RÔLE, FORMAT et TON. En combinant ces éléments, les prompts peuvent être adaptés pour produire des réponses précises, fiables et appropriées au contexte, ce qui est particulièrement important dans la communication scientifique.

Étapes pour créer un bon prompt scientifique

##   TÂCHE

Le ** TÂCHE** précise exactement ce que l’IA doit accomplir. C’est la formulation directe de la mission.

 Exemples scientifiques :

 
* Explique les expériences d’Alain Aspect sur les interféromètres et le caractère non-local de la physique quantique, 
⁡
* **DFT** : Calcule la structure de bande électronique d’un nanomatériau 2D PEGylé avec *Quantum ESPRESSO*.


##  CONTEXTE

Le **CONTEXTE** définit le cadre scientifique, les hypothèses ou l’environnement du calcul.

 Exemples scientifiques :

* **DFT** : Se concentrer sur l’effet des modifications de surface (PEGylation) sur l’absorption NIR-I.
* *Considérant les expériences réalisées dans les années 80 avec des interféromètres*, explique comment les résultats d’Alain Aspect ont démontré le caractère non-local de la physique quantique

##   MODÈLE

L’**MODÈLE** fournit un modèle de style ou de structure auquel la réponse doit ressembler.

 Exemples scientifiques :

* **DFT** : Rédiger la réponse comme une section *Méthodes* d’un article en science des matériaux.
* **MD** : Suivre le style d’un tutoriel de simulation destiné aux doctorants.
* **FDTD** : Structurer comme un résumé de conférence en nanophotonique.
* **Optimisation** : Présenter comme une section *Résultats/Discussion* dans un article de data science appliqué aux matériaux.



##    RÔLE

Le ** RÔLE** définit le rôle ou la voix que l’IA doit adopter.

 Exemples scientifiques :

* **DFT** : Se mettre dans la peau d’un physicien computationnel enseignant à des doctorants.
* **MD** : Adopter la voix d’un biophysicien expliquant des résultats de dynamique moléculaire.
* **FDTD** : Parler comme un chercheur en photonique s’adressant à ses pairs.
* **Optimisation** : Répondre comme un data scientist spécialisé en matériaux computationnels.



##  FORMAT

Le **FORMAT** indique comment la réponse doit être structurée (tableaux, équations, listes…).

 Exemples scientifiques :

* **DFT** : Donner 3 points avec équations LaTeX de l’équation de Schrödinger et transitions optiques.
* **MD** : Fournir un organigramme ou des étapes numérotées du protocole de simulation.
* **FDTD** : Expliquer étape par étape (1, 2, 3) avec éventuellement un schéma ASCII.
* **Optimisation** : Présenter un tableau comparant régression linéaire vs non linéaire.



## TON
Le **TON** définit le style de communication (académique, pédagogique, vulgarisé, professionnel…).

 Exemples scientifiques :

* **DFT** : Ton académique, précis et formel.
* **MD** : Ton didactique, adapté à des étudiants avancés.
* **FDTD** : Ton technique mais engageant, mettant en avant les applications.
* **Optimisation** : Ton professionnel et concis, destiné à des chercheurs interdisciplinaires.



#  Exemple de prompt complet (Intégration de tous les blocs)

*"En tant que chercheur en photonique (PERSONA), explique comment les simulations FDTD (TASK) permettent de modéliser l’absorption de lumière NIR-I dans des nanomatériaux 2D PEGylés (CONTEXT). Présente la réponse en 3 étapes numérotées (FORMAT), avec une équation en LaTeX pour illustrer l’absorption optique. Garde un ton technique mais engageant, en soulignant les applications en PTT et PDT (TONE). Structure l’explication comme un résumé de conférence scientifique (EXEMPLAR)."*



Veux-tu que je **génère un nouveau DOCX** avec cette intégration finale et les titres/sous-titres déjà en couleurs (rouge/bleu) ?
