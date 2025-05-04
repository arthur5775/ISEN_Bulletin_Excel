Ce projet a pour but de créer un tableur excel permettant de calculer les moyennes des tous les semestres d'une scolarité à l'ISEN quel que soit le cycle. Les calculs sont basés sur la maquette v17/10/2023.  
Vous pouvez choisir votre cycle sur la première feuille de calcul ainsi que si vous êtes alternant ou non. Cela mettra à jour automatiquement les cours, les coefficients ainsi que le nombre d'heures de cours.  

Code couleur:  
  Moyenne semestres:  
  - rouge < 10  
  - vert > 10
  
  Moyenne UE:  
  - rouge < 10  
  - jaune >= 10 & < 11  
  - vert > 11

  Grade:
  - Grade A : 10% des meilleurs étudiants (GPA = 4.0)
  - Grade B : 25% suivants (GPA = 3.0)
  - Grade C : 30% suivants (GPA = 2.0)
  - Grade D : 25% suivants (GPA = 1.0)
  - Grade E : 10% suivants (GPA = 0.0)
  - Grade F : Non validé (note inférieure à 10/20) (GPA = 0.0)

  GPA: (formule estimée à vérifier avec la direction des études)
  - GPA = [∑(Points_GPA_module × ECTS_module) + (Points_GPA_moyenne × ECTS_moyenne)] / (Total_ECTS)
  - ECTS_moyenne = 30
  - Total_ECTS = 60
  
Rq: Les matières optionelles ne sont prises en compte que si vous changez la valeur du poids de la matière dans le menu déroulant sur la feuille de calcul du semestre concerné.  
  
Encore à ajouter:
- ajout calcul grade si moins de 30 élèves ou rentrer manuellement (sur première feuille de calcul rentrer nombre d'élève par an ou semestre)
- ajout calcul GPA grâce au grades (cf fichier anglais)
- ajout possibilité de mettre un forçage après le premier ou le second conseil de classe (remplace la note par 10,00)
- ajout possibilité ajout note de rattrappage (remplasse toujours la note originale même si inférieure) (saud si dû à maladie donc faire différents cas)
- optimisateur ajout point ambassadeur tout en laissant le choix à l'utilisateur (peu être mis sur un UE par an si 4 actions ou plus dans l'année, ne peut sauver d'un ratttrappage qu'au 2ème semestre et s'applioque après note de rattrappages au premier, mettre pour maximiser moyenne sur un 1 an sauf si un UE n'est pas validé)
- calcul minimum sur notes restantes pour objectif donné (valider matière à 10, 13 ou autre avec courbes en prenant valeurs incrémentées de 0,25)
- CENT absent toute la 2ème année
