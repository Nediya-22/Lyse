# Report on How to Make a Good Scientific Prompt Using Building Blocks
## Introduction
This report presents a systematic method for creating good scientific prompts using six key building blocks: TASK, CONTEXT, EXEMPLAR, PERSONA, FORMAT, and TONE. By combining these elements, prompts can be tailored to produce precise, reliable, and context-appropriate responses, which are particularly important in scientific communication.
Steps in Making a Good Scientific Prompt

#  TASK

Le **TASK** précise exactement ce que l’IA doit accomplir. C’est la formulation directe de la mission.

 Exemples scientifiques :

* **DFT** : Calculer la structure de bande électronique d’un nanomatériau 2D PEGylé avec *Quantum ESPRESSO*.
* **MD** : Simuler la stabilité d’un nanomatériau PEGylé dans un milieu biologique avec *GROMACS*.
* **FDTD** : Modéliser l’absorption optique d’un nanomatériau 2D sous lumière NIR-I pour la PTT.
* **Optimisation** : Utiliser la régression pour optimiser le gap électronique de nanomatériaux 2D en fonction de substitutions atomiques.



#  CONTEXT

Le **CONTEXT** définit le cadre scientifique, les hypothèses ou l’environnement du calcul.

 Exemples scientifiques :

* **DFT** : Se concentrer sur l’effet des modifications de surface (PEGylation) sur l’absorption NIR-I.
* **MD** : Étudier comment la fonctionnalisation influence les interactions avec les membranes biologiques.
* **FDTD** : Relier l’absorption et l’efficacité de conversion énergétique aux applications PDT/PTT.
* **Optimisation** : Appliquer l’analyse de données pour identifier les substitutions améliorant la stabilité structurale.



#  EXEMPLAR

L’**EXEMPLAR** fournit un modèle de style ou de structure auquel la réponse doit ressembler.

 Exemples scientifiques :

* **DFT** : Rédiger la réponse comme une section *Méthodes* d’un article en science des matériaux.
* **MD** : Suivre le style d’un tutoriel de simulation destiné aux doctorants.
* **FDTD** : Structurer comme un résumé de conférence en nanophotonique.
* **Optimisation** : Présenter comme une section *Résultats/Discussion* dans un article de data science appliqué aux matériaux.



#  PERSONA

Le **PERSONA** définit le rôle ou la voix que l’IA doit adopter.

 Exemples scientifiques :

* **DFT** : Se mettre dans la peau d’un physicien computationnel enseignant à des doctorants.
* **MD** : Adopter la voix d’un biophysicien expliquant des résultats de dynamique moléculaire.
* **FDTD** : Parler comme un chercheur en photonique s’adressant à ses pairs.
* **Optimisation** : Répondre comme un data scientist spécialisé en matériaux computationnels.



#  FORMAT

Le **FORMAT** indique comment la réponse doit être structurée (tableaux, équations, listes…).

 Exemples scientifiques :

* **DFT** : Donner 3 points avec équations LaTeX de l’équation de Schrödinger et transitions optiques.
* **MD** : Fournir un organigramme ou des étapes numérotées du protocole de simulation.
* **FDTD** : Expliquer étape par étape (1, 2, 3) avec éventuellement un schéma ASCII.
* **Optimisation** : Présenter un tableau comparant régression linéaire vs non linéaire.



# 
Le **TONE** définit le style de communication (académique, pédagogique, vulgarisé, professionnel…).

 Exemples scientifiques :

* **DFT** : Ton académique, précis et formel.
* **MD** : Ton didactique, adapté à des étudiants avancés.
* **FDTD** : Ton technique mais engageant, mettant en avant les applications.
* **Optimisation** : Ton professionnel et concis, destiné à des chercheurs interdisciplinaires.



#  Exemple de prompt complet (Intégration de tous les blocs)

*"En tant que chercheur en photonique (PERSONA), explique comment les simulations FDTD (TASK) permettent de modéliser l’absorption de lumière NIR-I dans des nanomatériaux 2D PEGylés (CONTEXT). Présente la réponse en 3 étapes numérotées (FORMAT), avec une équation en LaTeX pour illustrer l’absorption optique. Garde un ton technique mais engageant, en soulignant les applications en PTT et PDT (TONE). Structure l’explication comme un résumé de conférence scientifique (EXEMPLAR)."*



Veux-tu que je **génère un nouveau DOCX** avec cette intégration finale et les titres/sous-titres déjà en couleurs (rouge/bleu) ?
