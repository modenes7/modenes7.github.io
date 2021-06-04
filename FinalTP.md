# TP FINAL TECHNOLOGIES WEB ET MULTIMEDIA
## Gaia Modenese

Ce travail à l’objective de combiner plusieurs logiciels pour analyser un corpus bilingue et illustrer les résultats de l'analyse. Le corpus que j'ai choisi d'analyser et le livre « Le Petit Prince », écrit par Antoine de Saint-Exupéry. Plus précisément je comparerai les versions en italien et en anglais du 2004. La raison pour laquelle je choisi d'analyser ce livre est car il est un des livres les plus connus et plus traduit au monde, mais surtout il s'agit d'un livre que j'adore. J'ai donc pensé qu'il serait intéressant d'analyser les différences dans les styles des 2 traductions avec l'aide d'un concordancier : AntConc. Dans ce document vous trouvez une explication des résultat obtenus grâce à l'analyse de mon corpus bilingue avec le logiciel AntConc.

## Analyse du Corpus avec AntConc

### Fonction Word List

**But :** Comparer la longueur des ouvres en regardant le numéro de Word tokens

**Résultats**
| Italien | Anglais |
| ----------- | ----------- |
| 14276 | 17209 |

**Conclusion**
 
Contrairement à ce que je m'attendais la traduction anglaise est plus longue par rapport à celle italienne. En effet l’italien est une langue moins synthétique que l’anglaise et d’habitude ses phrases sont plus longues et utilisent plus de mots pour exprimer le même concept par rapport à la langue anglaise.


### Fonction Concordance Plot I

**But :** Observer la fréquence des noms des personnages plus importantes du livre pour comparer les occurrences dans les deux langues et essayer, sur la base de cela, de comprendre quelle langue utilise le plus de synonymes or pronoms.

**Objets de la recherche :** le Prince, le Renard, le Serpent et le Roi

**Résultats**
Personnage | Italien | Anglais |
| ----------- | ----------- | ----------- |
| Prince | 197 | 210 |
| Rendard | 34	|  36 |
| Serpent | 16	| 16 | 
| Roi | 36 |	34 | 

**Conclusion**
 
Il n’y pas une grande différence entre les occurrences des noms des personnages dans les deux versions, ce qui montre que les traductions sont probablement assez fidèles et traduites littéralement. Le seul mot qui a un peu plus de différence est « Le prince » qui apparaisse 197 fois en italien et 210 dans la version anglaise. La version italienne a doc probablement utilisé quelque synonyme ou pronom de plus pour éviter les répétitions. 

### Fonction Concordance Plot II

**But :** Comparer l’usage du discours direct dans les deux livres

**Objet de la recherche :** " (Guillomet)

**Résultats**
| Italien | Anglais |
| ----------- | ----------- |
| 1186 | 1265 |

**Conclusion**

On peut donc déduire que la version anglaise utilise légèrement plus le discours direct par rapport à la version italienne qui a probablement converti quelques discussions entre les personnages en discours indirect.

### Fonction File View

**But :** Découvrir comment le mot italien "addomesticare" (domestiquer) a été traduit en anglais. 

**Stratégie :** J'ai cherché le mot à "addomesticare" dans le corpus en italien avec la fonction « File View », qui m'a permis de localiser le mot dans le livre italien et ensuite chercher son équivalent dans le chapitre anglais correspondant. De cette manière j'ai découvert que domestiquer est traduit en anglais par le verbe « to tame ». 

**Résultats**
| Italien | Anglais |
| ----------- | ----------- |
| domestiquer | to tame |

### Fonction Concordance

**But :** Analyser le occurrences des équivalents "addomesticare et "to tame" en contexte et observer le numéro d'occurrences

**Résultats**
| Italien | Anglais |
| ----------- | ----------- |
| 18 | 18 |

**Conclusion**
Dans les 2 livres il y a les mêmes occurrences du verbe domestiquer : 18. En analysant toutes les différentes concordances j'ai aussi remarqué que les phrases sont traduites assez littéralement. . Par example, « I am not tamed », « non sono addomesticata »

### Fonction Collocates

**But :** Analyser les collocations des mots liés au thème principale du livre : l'amitié

**Objet de la recherche :** « amic. » et « friend. » (Regex)

**Résultats**
Collocations plus fréquentes et intéressantes qui sont présents dans les 2 livres sont : 
- prince
- renard 
- pronoms possessif « mon » et « son »

**Conclusion**
En effet dans le livre le renard et le prince sont devenus très amis. On peut supposer que les pronoms possessifs mettent en évidence encore plus l'exclusivité et la beauté de cette amitié.

### Fonction Clusters/N-grams

**But :** Analyser les clusters des mots liés à un autre thème importante du livre : l'enfance

**Objet de la recherche :** « bambin. » et « enfant. » (Regex)

**Résultats**

Dans les 2 versions on peut trouver des Clusters en commun compte par exemple :
- « les enfants comprennent »
- « les enfants doivent être indulgentes avec les adultes » 
- « les enfants doivent toujours expliquer aux adultes… »

**Conclusion**
C'est trois phrases montrent un aspect qui est récurrent dans l'histoire, c'est à dire le fait que et les enfants sont pleines de fantaisie et de créativité et les adultes ne le ne leurs comprennent pas, c'est pour cela que les enfants doivent être très indulgents et patients et expliquer toujours les choses aux adultes. 



