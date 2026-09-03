# Ordre de tri des listes

Les listes dans Catenda sont triées selon les valeurs Unicode. Pour savoir quelles lettres ont quelles valeurs Unicode, consultez [cet article Wikipedia](https://en.wikipedia.org/wiki/List_of_Unicode_characters). Cliquez ici pour en savoir plus sur les stratégies typiques appliquées à la dénomination des éléments afin qu'ils se retrouvent dans le bon ordre.

## 1. **Listes qui utilisent ce tri**

Liste de projets Tableau des modèles Page Signets Ordre du tableau de sujets Tableau des sujets Tableau des documents Tableau des étiquettes Tableau du groupe d'étiquettes Tableau des champs personnalisés Liste des membres Liste des équipes Sélecteur de révision Tableau des objets Tableau QTO Ordre des étiquettes

## 2. **Ordre des caractères Unicode**

Pour un aperçu rapide des caractères Unicode, voir ci-dessous :

### 2.1 **1. Espace ( )**

L'espace n'est souvent pas autorisé comme premier caractère, mais peut être utilisé dans la section des modèles et documents. Bien que l'espace garantisse que ce sera 100% toujours le premier dans la liste, ce n'est pas recommandé car un espace devant un mot peut sembler déroutant pour les utilisateurs. Un espace au début d'un nom peut également entraîner des problèmes car ce n'est pas autorisé dans Windows.

### 2.2 **2. Ponctuation ASCII et symboles**

Caractères de demi-largeur `!"#%&()*+-/` ! est le deuxième caractère Unicode et c'est le meilleur choix si vous voulez vous assurer que votre élément de liste apparaît en premier dans la liste.

### 2.3 **3. Chiffres ASCII**

Nombres `0001` Les nombres sont triés alphanumétriquement. Cela signifie que l'ordre peut sembler étrange si vous avez des nombres de longueur différente dans une liste : 1 10 11 12 2 20 21 22

Pour remédier à cela, ajoutez un 0 devant les nombres qui ne sont pas très longs. 00001 00002 00003 00004 00011 00111 00365 etc. Cela garantira que vos nombres se retrouvent dans le bon ordre.

### 2.4 **4. Ponctuation ASCII et symboles**

`<>@`

### 2.5 **5. LETTRES - MAJUSCULES - DEMI-LARGEUR**

`LETTRES MAJUSCULES`

### 2.6 **6. Ponctuation ASCII et symboles**

`[\]_`

### 2.7 **7. lettres - minuscules - demi-largeur**

`lettres minuscules`

### 2.8 **8. Ponctuation ASCII et symboles**

`{|}~¨´`

### 2.9 **Langues internationales**

9\. Latin européen - Majuscules puis minuscules (ÅÆØß)(âäåæçèéø) 10\. Latin non-européen et historique - Majuscules puis minuscules (grec, russe, arabe, thaï) 11\. Symboles et ponctuation CJK (「」) 12\. ひらがな (Hiragana) 13\. カタカナ (Katakana - largeur complète) 14\. Symboles Katakana (・) 15\. Bopomofo 16\. Jamo Hangul et Jamo de compatibilité 17\. Kanbun 18\. Lettres CJK encadrées et mois 19\. Symboles alchimiques 20\. Kanji (漢字) 21\. Symboles (／) 22\. ０００１－ｆｕｌｌ－ｗｉｄｔｈ－ｎｕｍｂｅｒｓ 23\. ＬＥＴＴＥＲＳ－ＦＵＬＬ－ＷＩＤＴＨ－ＣＡＰＩＴＡＬ 24.ｌｅｔｔｅｒｓ－ｆｕｌｌ－ｗｉｄｔｈ－ｌｏｗｅｒｃａｓｅ 25\. ｶﾀｶﾅ - (Katakana - largeur demie)
