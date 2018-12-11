# Problèmes solutionnés en optique

## Hypothèse

Partant de l'hypothèse que la rétroaction (*feedback*) aux étudiants est plus importante que les tests, les devoirs, ou même les cours en classe, je rassemble ici l'ensemble des questions que j'ai composées, modifiées ou solutionnées au fil des années dans le cadre de mon enseignement en optique et biophotonique à l'Université Laval. Ces questions ont été utilisées comme devoir, comme questions d'examen et comme question en classe.

## Plan à long terme

Le plan à long terme est d'obtenir une base de données importantes de problèmes en optique qui sera: 

1. utilisés par n'importe qui
2. corrigés par n'importe qui
3. améliorés par n'importe qui

Si vous voyez une erreur, vous devriez la corriger et:

1. M'envoyer la correction dans le bon fichier corrigé, ou 
2. Faire une requête Pull request sur GitHub après avoir fait une copie (fork) du répertoire.

## Comment utiliser ces questions

1. Vous pouvez aller directement sur le [Web](https://github.com/dccote/Questions) ou télécharger/clôner le [répertoire](https://github.com/dccote/Questions) GitHub. Si vous allez sur le Web, vous ne verrez pas les équations.
2. Si vous télécharger ou clôner Télécharger Typora pour bien voir les extensions markdown propres à [Typora](http://typora.io), en particulier $\LaTeX$.
3. Optionnel, mais préférable: vous devriez copier le stylesheet questions.css du répertoire `site` dans le Theme Folder de Typora (voir les préferences du logiciel).  En sélectionnant, vous aurez un style approprié pour les questions.
4. Pour voir les questions dans leur ensemble, ouvrez le document [Questions.md](Questions.md)
5. Bientôt deux documents séparés `Questions.md` et `Réponses.md` vous permettront de lire les questions sans être trop tenté par la réponse qui suit.
6. Pour voir les questions individuellement, allez dans chaque répertoire comme par exemple [001-Ondes](001-Ondes).
   1. Dans le logiciel Typora, le menu **View →File Tree** vous permettra de voir tous les répertoires et les fichiers dans une barre à gauche.  Très pratique.

## Ce que vous trouverez ici

Vous trouverez dans l'ensemble de ces répertoires des questions d'optique souvent solutionnées en format Markdown qui est un format texte lisible en soi, mais qui est encore mieux avec les extensions [Typora](http://typora.io) (logiciel gratuit toute plateforme, permet les équations LaTex lorsque visionné dans Typora). En particulier:

1. Plusieurs répertoires contenant des questions, sous forme `Qxxx-yyy.md`. Chaque fichier a les éléments suivants:

   1. Un titre (header de niveau 2): `## titre` 
   2. La durée estimée en minutes ou heures (`m` ou `h`):` Durée: Nm`
   3. La question (header de niveau 3): `### Question`
   4. La réponse (header de niveau 3): `### Réponse`
2. Des scripts pour générer des documents qui incluent l'ensemble des questions dans `site`.
3. Des modifications au stylesheet de Typora pour avoir une style qui me plaît à l'affichage dans `site`
4. Un répertoire `assets` où les images sont rassemblées.
5. Un document `Questions.md` regroupant toutes les questions avec réponses.