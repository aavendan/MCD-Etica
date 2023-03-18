# MCD-Etica

COMPAS (Correctional Offender Management Profiling for Alternative Sanctions) es una herramienta de Northpointe, Inc., que evalúa la probabilidad de que un acusado de un delito se convierta en reincidente.

Propublica realiza un [análisis](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing) en el que se propone a descubrir la precisión subyacente de su algoritmo de reincidencia y probar si el algoritmo estaba sesgado contra ciertos grupos. 

Los [resultados](https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm) demuestran que los acusados de raza negra tenían muchas más probabilidades que los acusados caucásicos de ser juzgados incorrectamente con un mayor riesgo de reincidencia, mientras que los acusados caucásicos tenían más probabilidades que los acusados de raza negra de ser marcados incorrectamente como de bajo riesgo.

El conjunto de datos está disponible en [Github](https://github.com/propublica/compas-analysis) y en [Kaggle](https://www.kaggle.com/danofer/compass).

## Librerías usadas

* Numpy
* Pandas
* Lime
* SHAP
* Matplotlib

## Referencias

Machine Bias. (2016). Retrieved 18 February 2022, from https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing

How We Analyzed the COMPAS Recidivism Algorithm. (2016). Retrieved 18 February 2022, from https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm

GitHub - propublica/compas-analysis: Data and analysis for 'Machine Bias'. (2022). Retrieved 18 February 2022, from https://github.com/propublica/compas-analysis

The Perfect Recipe for Classification Using Logistic Regression. (2021). Retrieved 18 February 2022, from https://towardsdatascience.com/the-perfect-recipe-for-classification-using-logistic-regression-f8648e267592

Singh, D., & Python, I. (2022). Interpreting Data using Statistical Models with Python | Pluralsight. Retrieved 18 February 2022, from https://www.pluralsight.com/guides/interpreting-data-using-statistical-models-python

Building A Logistic Regression in Python, Step by Step. (2019). Retrieved 18 February 2022, from https://towardsdatascience.com/building-a-logistic-regression-in-python-step-by-step-becd4d56c9c8

Molnar, C. (2022). Interpretable Machine Learning. Retrieved 18 February 2022, from https://christophm.github.io/interpretable-ml-book/index.html

An introduction to explainable AI with Shapley values — SHAP latest documentation. (2022). Retrieved 18 February 2022, from https://shap.readthedocs.io/en/latest/example_notebooks/overviews/An%20introduction%20to%20explainable%20AI%20with%20Shapley%20values.html

How to Use LIME to Understand sklearn Models Predictions [Python]? by Sunny Solanki. (2022). Retrieved 18 February 2022, from https://coderzcolumn.com/tutorials/machine-learning/how-to-use-lime-to-understand-sklearn-models-predictions

Explainable AI: An illuminator in the field of black-box machine learning. (2021). Retrieved 18 February 2022, from https://towardsdatascience.com/explainable-ai-an-illuminator-in-the-field-of-black-box-machine-learning-62d805d54a7a

