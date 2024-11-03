# Predict ENEM Score

In this project, I used two decision tree models to predict ENEM scores based on students' income, family education, and school type.

1. First, I cleaned the dataset and selected the columns I would use.
2. Then, I split the 2019 scores into training and test sets.
3. I built two decision tree models: one regressor and one classifier.
4. Both models were trained and tested.
5. Finally, I tested both models against the 2021 ENEM data to verify their accuracy with a different set of students.
6. The results were reasonable and are detailed below.

## Results

- The model performed very well on the 2019 test set.
    - The classifier model achieved **87% accuracy** when tested on 2019 students.
    - The regressor model had an **average error of 57 points** when tested on 2019 students.

- When tested with students from a different year (2021), with entirely different ENEM questions, the models still produced strong results:
    - The classifier model achieved **82% accuracy** on the 2021 students.
    - The regressor model had an **average error of 62 points** on the 2021 students.

Although we expected the models to perform better in the same year they were trained, the strong performance in a different year demonstrates that the models can predict scores well and are not overfitted to data from a specific year.

Besides that, we observed the relevance of each input factor in predicting the score. **Family income** emerged as the most important factor, followed by **school type** and **parents' education**.


## Reference

You can access the data here: [ENEM data](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem)
