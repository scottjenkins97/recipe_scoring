# recipe_scoring
Space to work on the recipe scoring task for the SIAM Competition

## Question: Given a page from a recipe book, how can we quantify how healthy it is?

## Motivation
It is well-known that a good diet is fundamental for preventing a variety of chronic diseases and for maintaining optimal health and cognitive functions. In this way, a consistent quantitative method to assess a person's diet is quite useful for a healthy lifestyle.
Even though there are various methods in the scientific literature to evaluate the quality of food items, there remains the need for reliable methods to assess the quality of dish recipes. The usefulness of such methods is more evident, when considering that people usually eat food items as ingredients of a recipe.
Detalytics is interested in developing general quantitative methods to assess the quality of recipes, that are consistent with the state-of-the-art assessment methods for food items.
In particular, in this project we require the participants to employ Multi-criteria Decision Analysis (MCDA) and Natural Language Processing (NLP) approaches (from Machine Learning) to extract the essential information contained in recipes (i.e., ingredients and cooking procedure), and then use this information to adequately define an overall Recipe Quality Score.
Since there are various ways to achieve this, special importance will be given to the rationale explaining the choices made to define this score, in the final report.
Due to time constraints, in this project we will focus on the Food Compass score, as the baseline score for food items. Note that this score takes into account 54 food attributes as input, and its calculation procedure is publicly available (see References below).

## Provided inputs:
• A database 8,032 food items, with their respective Food Compass score.
• A database of 45,629 recipes (ingredients and cooking procedure).

## Expected outputs:
- An NLP method to process these recipes (as text input data) and extract relevant features and information that will be used to calculate the recipe quality score. This method should be thoroughly documented (feature engineering, model choices, training procedure, etc.).
- The definition of a Recipe Quality Score, that uses an adequate MCDA procedure and the previous NLP method. This score has to take into account the Food Compass score definition and "generalizes" it in a coherent manner. The rationale explaining this MCDA procedure and its consistency with the Compass score should be thoroughly documented as well.
- A Python implementation code of the aforementioned NLP method and MCDA procedure. Note that depending on the approach chosen by the participant, both of these could be developed either simultaneously or sequentially.
- The Recipe Quality Score for all the 45,629 recipes.
- A report (max. 15 pages) presenting the previous points (NLP, MCDA development documentation), with particular emphasis on the rationale that justifies the choices made during the development of the NLP method and the construction (selection) of the MCDA procedure.

References:
Mozaffarian, D., El-Abbadi, N.H., O’Hearn, M. et al. Food Compass is a nutrient profiling system using expanded characteristics for assessing healthfulness of foods. Nat Food 2, 809–818 (2021). https://doi.org/10.1038/s43016-021-00381-y

O’Hearn, M., Erndt-Marino, J., Gerber, S. et al. Validation of Food Compass with a healthy diet, cardiometabolic health, and mortality among U.S. adults, 1999–2018. Nat Commun 13, 7066 (2022). https://doi.org/10.1038/s41467-022-34195-8

