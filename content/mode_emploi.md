# Mode d'emploi pour l'exécution des notebooks Jupyter

Afin de pouvoir exécuter les notebooks mis à disposition pour les cours et les travaux pratiques, deux possibilités sont possibles :

## Utiliser son environnement personnel

Pour ce mode, il suffit de télécharger les notebooks Jupyter depuis ce site et les exécuter sur sa machine. Pour installer l'environnement logiciel nécessaire à l'exécution des notebooks du cours, suivre la procédure suivante :
  
```{admonition} Procédure pour installer son environnement personnel

- Installer la dernière version de `miniforge` (disponible sur le site [conda-forge](https://conda-forge.org/download/)).

- Créer un nouvel environnement pour le cours en tapant dans un terminal :

`mamba create -n apm5msx2 python=3`

- Activer l'environnement apm5msx2 :

`mamba activate apm5msx2` 

-  Installer les packages python nécessaires pour le cours :

`mamba install jupyterlab numpy scipy plotly mpmath sympy matplotlib`

-  Lancer le serveur Jupyter :

`jupyter notebook` ou `jupyter lab`
```

## Utiliser le JupyterHub de l'école Polytechnique

Pour ce mode, il suffit de télécharger les notebooks Jupyter depuis ce site et les copier vers le serveur `JupyterHub` de l'école (cf. procédure suivante).

``````{admonition} Utilisation du JupyterHub de l'école

- Dans un navigateur, se rendre sur le [JupyterHub de l'école](https://lysithea.polytechnique.fr) et cliquez sur GitLab IN2P3 puis CC-IN2P3 Single Sign-On puis eduGAIN et enfin choisissez votre établissement.

- Utiliser vos identifiants pour vous connecter sur la plateforme.

- Sur la page Server Options, cliquer dans le rectangle  `Python scientific environment` qui permet de lancer un `JupyterLab` avec un noyau Python et les modules nécessaires au cours.

- Cliquer sur l'icone `Upload files` du menu de la barre latérale gauche pour téléverser un notebook depuis votre machine vers le `JupyterLab` puis l'exécuter.

```{admonition} Remarque
Pour récupérer un notebook depuis la plateforme vers votre machine, cliquer avec le bouton droit sur le nom du notebook dans la barre latérale gauche puis en choisir `download`.
```

```{admonition} Attention
:class: warning
Penser à déplacer vos notebooks dans le répertoire `persistent` afin qu'ils soient conserver pour une prochaine session.
```
``````
