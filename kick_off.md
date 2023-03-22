# Notes
22nd March 2023

Fayz and Scott met to take a first look at the problem, looking through the provided data, flagging things to be aware of, and discussing possible approaches.

- Recipes have ingredient lists (but no quantities), and a text description which looks to have some standard format (prep and cook time)
- The ingredients in the recipes do not match exactly to the food items. How to produce this mapping for these recipes, and for other recipes?
  - python 'in' method?
  - Similarity scoring?
- Once we have the health scores of the foods in the recipes, how to aggregate into a recipe score?
  - Mean score (But meals contain different ratios)
  - Infer the ratios from the text? 'sprinkle','pinch','spoonful'
- NLP could look for cooking method words: 'fry','boil','grill'
- Would be cool to build an interface where users can input their own recipes / scrape from url, and return the health score, and maybe suggest 'similar' meals which are healthier?

We'll meet again in a few weeks post undergrad dissertation deadlines at the start of April.

In summary, an interesting problem, quick to understand, and lots of scope for further complexity.
