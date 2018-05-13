# Improving Winemaking using Data

We explored red wine data using R to find statistical correlations between different variables and wine quality. The goal was to find some variables that could be tuned to obtain the highest quality wine possible.

## Structure of the dataset

- X: whole number, unique for each observation (Removed).

- fixed.acidity: non-volatile acids found in wines, the most common are tartaric, malic, citric and succinic (as tartaric acid in g/L).

 - volatile.acidity: largely acetic acid, linked to the vinegary taste (as acetic acid in g/L).

 - citric.acid: found in small quantities, typically 1/20 of the tartaric acid concentrations (in g/L).

  - residual.sugar: the sugar that remains in wine after fermentation completes (in g/L).

  - chlorides: the amount of salt (as sodium chloride in g/L). There are legal limits for chloride content in wines, but it varies widely from country to country (i.e. 0.606 g/L of sodium chloride for Australia while the same limit is set at 0.06 g/L in Switzerland).

 - free.sulfur.dioxide: SO2 [molecular] + HSO3 [bisulfites] + SO3 [sulfites]. It is the buffer against microbes and oxidation (in mg/L)

 - total.sulfur.dioxide: free sulfur dioxide + bound sulfur dioxide [sulfites attached to either sugars, acetaldehyde or phenolic compounds] (in mg/L)

  - density: mass divided by volume, the density of wines are close to that of water (in g/cm3)

 - pH: -log10 of the activity of the hydrogen ion, it ranges from 0 to 14. (Zero is the most acidic, 7 is neutral, and 14 is the most basic); pH values for wines are typically between 3 and 4.

 - sulphates: The concentration of sulfates. Sulfur dioxide, upon oxidation, is converted into sulfate (as potassium sulfate in g/L)

 - alcohol: the amount of alcohol in % vol. For wines, it varies in a wide range, between 5.5% (Moscato d’Asti ) up to 21% (fortified wines).

- quality: a whole number to qualify the wine. It ranges from zero (bad) to ten (excellent), it is a subjective measure. For this dataset, it was the median of blind testing of at least three different experts for each sample.




## Files
- RedWine.Rmd 
- Redwine.htlm
- References.txt
- WineQualityReds.csv (dataset)
