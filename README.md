# Boston House Price

Projeto de análise exploratória e aprendizado de máquina utilizando o conjunto de dados Boston House Price.

## Objetivo

Analisar os fatores relacionados ao valor médio das casas em Boston e desenvolver modelos capazes de prever a variável `MEDV`.

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Etapas do projeto

1. Carregamento e exploração dos dados
2. Verificação de valores ausentes
3. Análise estatística descritiva
4. Identificação de outliers
5. Visualização dos dados
6. Análise de correlação
7. Treinamento de modelos de regressão
8. Avaliação dos modelos
9. Otimização de hiperparâmetros
10. Agrupamento dos dados com K-Means

## Modelos utilizados

- Regressão Linear
- Random Forest Regressor
- Gradient Boosting Regressor
- K-Means

## Principais variáveis

- `RM`: número médio de quartos por residência
- `LSTAT`: porcentagem da população de menor status
- `PTRATIO`: proporção de alunos por professor
- `CRIM`: taxa de criminalidade
- `NOX`: concentração de óxidos nítricos
- `MEDV`: valor médio das casas, em milhares de dólares

## Imagens

## Principais visualizações

### Distribuição dos dados padronizados

![Distribuição dos dados padronizados](Imagens/Distribui%C3%A7%C3%A3o%20dos%20Dados%20Pdronizados.png)

### Matriz de correlação

![Matriz de correlação](Imagens/Matriz%20de%20Correla%C3%A7%C3%A3o.png)

### Valores reais e previstos

![Valores reais e previstos](Imagens/Valores%20reais%20e%20previstos.png)

### Importância das variáveis

![Importância das variáveis](Imagens/Importancia%20das%20vari%C3%A1veis.png)

## Perfil dos Clusters

A análise com K-Means dividiu os imóveis em quatro grupos com características semelhantes:

|   cluster |   CRIM |   RM |   LSTAT |   PTRATIO |   MEDV |
|----------:|-------:|-----:|--------:|----------:|-------:|
|         0 |   0.28 | 6.34 |   10.68 |     18.33 |  24.04 |
|         1 |  12.76 | 6.02 |   18.6  |     20.2  |  16.4  |
|         2 |   0.07 | 6.75 |    6.1  |     16.88 |  29.35 |
|         3 |   1.21 | 5.99 |   16.37 |     17.41 |  20.53 |

> Os valores devem ser preenchidos com o resultado exibido por  
> `df_clusterizado.groupby("cluster").mean(numeric_only=True)`.

## Como executar

Clone o repositório:

```bash
git clone URL_DO_REPOSITORIO
cd BostonHousePrice
```

## 👨‍💻 Autor

**Ronald Brasil**
