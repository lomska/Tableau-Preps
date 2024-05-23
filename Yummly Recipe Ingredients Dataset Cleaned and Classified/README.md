The part of the Yummly dataset that I cleaned and classified includes six cuisines: <b>Italian</b>, <b>French</b>, <b>Chinese</b>, <b>Indian</b>, <b>Mexican</b> and <b>Southern US</b> cuisine. I used it in [this visualization](https://public.tableau.com/app/profile/lomska/viz/WhatWillWeCookFrom100most-usedingredientsintheworldstopcuisines/Tree). 

The dataset creation process is described in [the notebook](https://github.com/lomska/Tableau-Preps/blob/main/Yummly%20Recipe%20Ingredients%20Dataset%20Cleaned%20and%20Classified/Dataset%20Preparation.ipynb).

To extract the names of the ingredients, I updated the [word corpus designed by Zack Scholl](https://github.com/schollz/ingredients/blob/main/corpus.go).
The [word corpus I created](https://github.com/lomska/Tableau-Preps/blob/main/Yummly%20Recipe%20Ingredients%20Dataset%20Cleaned%20and%20Classified/assets/corpus.txt) is in the assets folder.

<b>The same folder contains two dictionaries:</b>

- [corpus_conversion.json](https://github.com/lomska/Tableau-Preps/blob/main/Yummly%20Recipe%20Ingredients%20Dataset%20Cleaned%20and%20Classified/assets/corpus_convertion.json) - converts phrases extracted using the corpus into ingredients;

- [ingredient_classification.json](https://github.com/lomska/Tableau-Preps/blob/main/Yummly%20Recipe%20Ingredients%20Dataset%20Cleaned%20and%20Classified/assets/ingredient_classification.json) - classifies them into groups and subgroups.
