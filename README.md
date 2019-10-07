# Clone-BD-code-signal

Cahier de charge partiel CODE SIGNAL

# I) INSCRIPTIION/CONNEXION

	a) INSCRIPTIION
		- Email
		- Full name 
		- password

	b) CONNEXION
		- Email 
		- password

# II) DASHBOARD DEVELOPPER

	- Panneau challenge (Arcade)
	- Historique d'activité
	- Challenge entreprise
	- Challenge entre équipe
	- Interview pour recruteur
	- Lien vers l'activité en cours de resolution 

	a) Panneau challenge(Arcade)

		- Liste des rubriques(langage de programation) avec en son sein :
			+ Nom de la rubrique 
			+ Information (Description)
			+ Nombre d'exo resolut / nbre total de la rubrique

	b) Contenue Rubrique

		Chaque rubrique est composé de :
		- Sections d'exercice (Titre de la section, le nbre d'exercice) qui contient :
			+ une liste d'exo(titre de la serie, le nombre d'exo)
			L'exercice a son tour comprend:
				% Titre de l'exo 
				% Description
				% Difficulté de l'exo
				% Nbre de point (score)
				% Categorie de l'exo
				% Etat de validité
			Il y a dans l'exo (à gauche) des options(menu) de vues:
			- Le menu Drafts contenant la liste de mes solution(chacun de mes submits pour l'exo en question)reparti par:
				% Date du submit
				% Le language(qui affiche le langage dans lequel le meme exo a pu etre resolut)
				% le score

			- Le menu solution qui liste toutes les solutions des autres codeur pour le meme exo.
				% Le nbre de liste de solution
				% Le user ayant resolu
				% le langage dans lequel il l'a resolu
				% Le nbre de vote

			- Le menu commentaire qui contient les commentaires des autres codeur sur l'exo en cour
				% User 
				% Date du post du commentaire
				% Le commentaire
				% Les reponses

------------------------------------------------- Daily challenge -----------------------------------------------
 Ici est affiché la liste des challenges. Ils peuvent etre filtré par:
- Statut(Public, Private)
- Statuses (etat de l'exercice)
- Difficulté
- Types

Chaque challenge est representé par 
- Statut
- Titre 
- user
- categorie
---------------------------
- Date
- Nbre d'inscrit
- Nbre de commentaire
- Recompense 

NB: L'interface du challenge est identique à celui l'arcade, à la difference du temps de resolution

---------------------------------------------- Company challenge ---------------------------------------------------

- Nom
- Situation géographique
- Type de l'entreprise 
- Date de creation de l'entreprise 
- Nbre d'employé
- Domaine d'intervention
- Medias
- Description entreprise
- Code challenge entreprise qui comporte :
	+ Titre
	+ Nbre de souscripteur
	+ Recompense
	+ Temps de resolution
	+ Difficulté

