# Mushroom-Classification
Safe to eat or deadly poison? https://www.kaggle.com/datasets/uciml/mushroom-classification

Content
This dataset includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family Mushroom drawn from The Audubon Society Field Guide to North American Mushrooms (1981). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom; no rule like "leaflets three, let it be'' for Poisonous Oak and Ivy.

Notebooks description:<br/>
**1. Feature_selection.ipynb**<br/>
This notebook contains an example of dataset preprocessing, namely the search for constant features and duplicated features. Also, there are methods for categorical feature selection, specifically -**Chi-Squared** and **Mutual information.**

**2.Categorical_encoding.ipynb**<br/>
This notebook contains different encoding methods for classification problems. Methods considered:<br/>
- One hot Encoding
- Label Encoding
- Ordinal Encoding
- Count and Frequency
- Probability Ratio Encoding
- Mean Encoding
- Weight of evidence
- Leave One Out encoding
