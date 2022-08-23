# LearningApps-Moodle

Il est actuellement possible d'intégrer des exercices LearningApps dans Moodle via les packages SCORM.
Cependant il n'était pas possible d'intégrer ces exercices dans des Tests (quiz) afin de par exemple mélanger ces exercices à d'autres plus classiques.
Cet outil permet de corriger ce défaut en permettant de générer des fichiers GIFT à importer dans la banque de question à partir d'exercices LearningApps.

![image](https://user-images.githubusercontent.com/53106394/186040982-9857150a-7d03-453d-8892-615fc4b1e211.png)

## Génération du fichier GIFT

Rendez-vous sur https://degrangem.github.io/learningapps-moodle/ et remplissez les champs nécéssaires pour obtenir le fichier GIFT.
Suivez ensuite les instructions ci-dessous pour l'importer.

## Import de la question dans la banque de question

Si vous n'avez pas encore déjà créé votre activité Test (Quiz en anglais) faites le.
Accédez au menu d'importation dans la banque de question via le menu de votre activité. 

<table><tr>
<td><img src="https://user-images.githubusercontent.com/53106394/155229742-27eaae9c-48e0-495a-84c5-7df740914796.png" width="100%" /></td>
<td><img src="https://user-images.githubusercontent.com/53106394/155229764-400df559-8af3-4ebf-adae-22d9fb4f3585.png" width="100%" /></td>
</tr></table>

Sélectionner le format  `Format GIFT`, déposez votre fichier dans la zone prévu à cet effet et appuyez sur le bouton d'importation.

## Ajouter la question à un test

Retournez sur votre activité, ouvrez le menu de votre activité et cliquez sur le lien "Modifier le test".

Appuyez sur le lien "Ajouter" et sélectionnez "de la banque de question".

![image](https://user-images.githubusercontent.com/53106394/155230688-fe9fabf4-00d8-4ea8-b8bb-053b50db99a4.png)

Il ne vous reste plus qu'à cocher la question précédemment importée, puis à cliquer sur le bouton "Ajouter les questions sélectionnée".

![image](https://user-images.githubusercontent.com/53106394/155233063-d9bdf5a1-39dd-4b68-bf3a-6e4546f5ab7b.png)

## Quelques remarques sur la configuration du test

Il faut obligatoirement ne pas afficher plus d'un seul exercice learningapps à la fois dans le test moodle, il est donc conseillé de régler le test sur "1 question par page".

Il est conseillé de configurer le test sur "Feedback à postériori". Dans le cas contraire la validation d'un exercice entraînera un rechargement de la page qui fera perdre le travail en cours sur un exercice de la même page.

## Remarque importante sur la triche

Les élèves ont la possibilité de tricher en actualisant la page pour recommencer.
Les élèves doués en informatique ont aussi la possibilité de tricher en se donnant tous les points à l'exercice sans l'effectuer.
Il est possible de réduire ces risques là en utilisant l'intégration de SafeExamBrowser (voir documentation Moodle).
