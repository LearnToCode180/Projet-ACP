## But du projet
Projet d'analyse en composantes principales dont le but est de classer les pays en utilisant les facteurs socio-économiques et sanitaires qui déterminent le développement global du pays réalisé en **Python 3** et le logiciel **SPSS**.

## Analyse en composantes principales
l’Analyse en composantes principales qui est l'une des méthodes de **Data Mining** les plus populaires. Elle permet d’explorer des jeux de données multidimensionnels constitués de variables quantitatives. Et elle permet de projeter les observations depuis un espace à p dimensions vers un espace à k dimensions (k < p) tel qu'un maximum d'information soit conservée sur les premières dimensions. Et elle est largement utilisée en biostatistique, marketing, sciences sociales et bien d’autres domaines.

## Data Set
[Link from Kaggle](https://www.kaggle.com/rohan0301/unsupervised-learning-on-country-data?select=Country-data.csv)

## Diagrammes réalisés

> On conclut depuis le graphique des valeurs propres ci-dessous que juste avec le premier axe on peut obtenir 43.55% de l’information disponible et si on ajoute les deux autres axes on obtient presque 82.16 de l'information disponible.

![Scree Plot with Python](/Diagrammes/screePlot_Python.png)

On voit ici le même résultat avec SPSS :


![Scree Plot with SPSS](/Diagrammes/screePlot_SPSS.png)

---

Et voici la qualité de représentation selon les trois facteurs :

![Qualité de représentation selon les trois facteurs](/Diagrammes/QualitePresentation.png)

> Par exemple ici on peut remarquer que le Cameroun, le Senegal et le Cote d'Ivoire sont très bien positionnés par rapport au premier axe, et le Brésil par rapport au deuxième.

---

Et voici la diagramme de représentation des variables :

![Diagramme de représentation des variables](/Diagrammes/VariablesDiagramme.png)

> On perçoit clairement que le premier axe est bien lié aux facteurs : **Décès d’enfants** ainsi que les **Naissances totales**, donc les pays sur lequel ils seront positionnés sont ceux qui ont un grand nombre de naissance et que la majorité de ces nouveau-nés mouraient avant 5 ans et ces pays-là également souffraient d’un **PIB** et **Revenu net par personne** très faibles ainsi d’un nombre moyen très faible d'années qu'un nouveau-né vivrait comme on vient de dire.

Et enfin, voici la représentation des individus par Python selon les deux premiers facteurs :

![Représentation des individus selon les deux premiers facteurs](/Diagrammes/PositionnementIndividus.png)

> On remarque ici que le Cote d’Ivoire, le Cameroun et Qatar sont les pays qui se démarquent le plus des autres et on les retrouve aux deux extrémités du premier axe factoriel qui porte 43.55% de l’information disponible, tant que les deux pays United States et United Arab Emirates sont bien positionnés par rapport au deuxième axe.

## Conclusion

Les résultats obtenus à l’aide du langage Python et du logiciel SPSS sont presque les mêmes, et on peut conclure de ces résultats-là que les pays qui souffrent le plus et qui ont plus besoin d’aide des ONG humanitaire internationale sont le Cote d’Ivoire, le Cameroun et le Sénégal.
