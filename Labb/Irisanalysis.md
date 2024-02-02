# Morphological Characteristics of Iris Flowers

# Introduction:

*This report presents a correlation analysis of measurements on iris petals and sepals. The aim is to investigate if there is a significant correlation between the width and length of the petals and sepals, and if a linear regression model would be a suitable description of these relationships.*

BILD


## Background and Dataset Explanation: ##

The Iris Flower Dataset, containing measurements from 150 flowers distributed across three subspecies: Iris Setosa, Iris Versicolor, and Iris Virginica, is used as the data material. Each flower has four measurement values, including the width and length of petals and sepals.

![Tabell](result_table.png)



## Hypotheses: ##
*To guide the analysis, two hypotheses were formulated:*

- $H_{0a}$: There is no significant correlation between petal length $X$ and width $Y$.


- $H_{1a}$: There is a significant correlation between petal length $X$ and width $Y$.



## Method and Analysis Approach: ##

To answer the hypotheses, the following methodological approach was chosen. By performing the following steps, a deeper understanding of the correlations was expected:

- Examine the scatter distribution of petals and sepals to capture potential linear relationships.

- Calculate bivariate correlation Pearson's - $r$ between width and length for both petals and sepals.

- Evaluate the significance of the correlation based on $r$- and $p$-values.
In case of a significant correlation, use a linear regression model.

- In case of a significant correlation, use a linear regression model $Y = \beta_0 + \beta_1X + \varepsilon$ for in-sample predictions.



# Analysis: #  
BILD

## Petal: ##
A closer look at the scatter distribution of petals suggests a linear relationship between width and length, despite the presence of a measurement gap. Nevertheless, overall trends show a linear connection between width and length.

## Sepal: ##
In contrast to petals, the scatter distribution for sepals does not reveal a clear correlation. However, a subdivision based on subspecies provides a more differentiated picture, especially for Iris Setosa, where a certain correlation is observed.

## Correlation: ##
A comprehensive consideration of a correlation heatmap for the entire dataset confirms previous observations. For sepals, a low correlation between width and length is reflected across the dataset, but a subdivision by subspecies shows some correlation, especially for Versicolor. For petals, there is an overall correlation, but when divided by subspecies, a weaker connection between width and length emerges.

## Answer to Hypotheses: ##
The results from the conducted correlation analysis provide support for drawing conclusions regarding the formulated hypotheses.

- **Null Hypothesis $H_{0a}$:**
  Based on the analysis of the morphological characteristics of petals, we cannot reject the null hypothesis $H_{0a}$ of no significant correlation between petal length $X$ and width $Y$. The results do not provide sufficient evidence to demonstrate the absence of a correlation.

- **Alternative Hypothesis $H_{1a}$ :**
  On the other hand, the results strongly support the alternative hypothesis $H_{1a}$, postulating a significant correlation between petal length $X$ and width $X$. Statistical analyses and calculations clearly show a significant correlation between these morphological characteristics.

  
# Conclusions: #
- For petal measurements, a significant correlation between width and length is observed, suggesting that a linear regression model is suitable for predictions within the sample.

- In sepal measurements, a significant correlation between width and length cannot be established across the entire dataset. However, a differentiated analysis based on subtypes may provide additional insights and support more optimized regression models, especially for Iris setosa.

- This report not only provides insights into the correlation among iris flower measurements but also emphasizes the importance of a differentiated analysis based on subtypes for a deeper understanding of the observed relationships.



