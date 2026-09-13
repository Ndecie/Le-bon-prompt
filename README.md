
Readme · MD
Le Bon Prompt
Un générateur de prompts pour ceux qui savent ce qu'ils veulent, mais pas comment le demander à une IA.

Le site : https://ndecie.github.io/Le-bon-prompt/

Le problème
Les gens ont des besoins précis et reçoivent des réponses vagues. Pas parce que l'IA est mauvaise, mais parce que la demande n'a jamais été cadrée. Quelqu'un qui demande « un tableau de suivi » reçoit trois tableaux différents, parce qu'il n'a jamais dit : un seul tableau, ces colonnes-là, des listes déroulantes fermées, une ligne par anomalie.

Ce site pose les questions à sa place.

Comment ça marche
On resserre en quatre temps, puis on rouvre.

L'intention — quel verbe : créer, analyser, rédiger, organiser, automatiser, expliquer, décider, corriger.
L'objet — quel type de résultat, parmi ceux qui correspondent au verbe choisi.
Le métier — RH et paie, finance, marketing, administration, terrain associatif… C'est ce qui décide des questions suivantes.
Votre situation — vous racontez, avec vos mots, même en désordre.
Vient ensuite l'interrogatoire : six questions taillées pour votre métier et pour votre type de résultat. Puis la relance — si une réponse est trop courte, le site vous la ressort et réclame un exemple concret ou un chiffre.

À la fin, un prompt structuré en cinq parties — rôle, contexte, tâche, contraintes, format de sortie — prêt à coller dans Claude, ChatGPT ou Gemini.

Dictée vocale
Chaque champ de réponse a un bouton Parler, pour ceux qui n'ont pas envie d'écrire.

La transcription est assurée par la reconnaissance vocale du navigateur — rien à installer, rien à payer. Sur Chrome, cette reconnaissance s'appuie sur les serveurs de Google ; le site lui-même n'enregistre, ne stocke et ne transmet aucun audio.

Fonctionne sur Chrome et Edge, sur ordinateur comme sur Android. Irrégulier sur iPhone. Exige une connexion https, ce que GitHub Pages fournit.

Technique
Un seul fichier : index.html. Aucune dépendance, aucun build, aucun serveur, aucune base de données, aucun traceur. Les seules ressources externes sont les polices, chargées depuis Google Fonts.

Rien n'est enregistré : vos réponses vivent dans l'onglet et disparaissent quand vous le fermez.

L'héberger ailleurs
Téléchargez index.html et déposez-le sur n'importe quel hébergement statique — GitHub Pages, Netlify, Vercel, ou un simple dossier FTP. Il n'y a rien d'autre à faire.

Auteur
Ndecie Boulandi — Orbis Dakar, Dakar, Sénégal.

Formation Maîtriser l'IA : une session intensive pour apprendre à écrire vos prompts vous-même, sans outil.

In English. Le Bon Prompt is a French-language prompt builder. It narrows a vague idea down through four questions, interrogates the user with domain-specific follow-ups, pushes back when an answer is too short, and assembles a structured prompt — role, context, task, constraints, output format — ready to paste into any AI assistant. Voice dictation included. Single HTML file, no dependencies, no tracking.

