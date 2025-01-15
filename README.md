# Desigualdade Salarial entre Gêneros no Brasil 🇧🇷 

https://desigualdade.onrender.com/

Através da base de dados dos quatro trimestres de 2023 da [PNADContínua](https://www.ibge.gov.br/estatisticas/sociais/trabalho/9171-pesquisa-nacional-por-amostra-de-domicilios-continua-mensal.html) disponibilizada pelo IBGE, foi possível calcular regressões lineares, utilizando o método OLS *(ordinary least squares)*. Foi rodado uma regressão para cada gênero: uma utilizando a base de dados filtrada para **mulheres** e outra para **homens**.

A fórmula da regressão linear para o logaritmo do salário por hora (`log_salario_hora`) é dada por:

$$
\log(\text{salario-obra}) = \beta_0 + \sum_{i=1}^{n} \beta_i \cdot x_i
$$

Onde $\beta_0$ é o intercepto, $\beta_i$ são os coeficientes para as variáveis independentes $x_i$, que incluem idade, raça, região e nível educacional.


# Gender Wage Inequality in Brazil 🇺🇸

https://desigualdade.onrender.com/en

Using the 2023 quarterly dataset from the [Continuous PNAD](https://www.ibge.gov.br/estatisticas/sociais/trabalho/9171-pesquisa-nacional-por-amostra-de-domicilios-continua-mensal.html) provided by IBGE, linear regressions were calculated using the **OLS (Ordinary Least Squares)** method. Two separate regressions were performed: one with the dataset filtered for **women** and another with the dataset filtered for **men**. 

The formula for the linear regression of the logarithm of hourly wage (`log_hourly_wage`) is given by:

$$
\log(\text{hourly-wage}) = \beta_0 + \sum_{i=1}^{n} \beta_i \cdot x_i
$$

Where $\beta_0$ s the intercept, $\beta_i$ are the coefficients for the independent variables $x_i$, which include age, race, region, and educational level.
