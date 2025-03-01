## `stage03`
# Etapa 03 - Primeiros Modelos e Análises

~~~
├── README.md  <- apresentação da etapa
│
├── CSVs    <- Arquivos csv da etapa
│
├── images    <- Imagem dos modelos conceituais
│
└── notebook    <- Notebooks da etapa
      │
      └── analiseObesidade.ipynb <- Notebook das Análises/Querys
      │
      └── extracaoHeartDisease.ipynb <- Notebook da extração do dataset HeartDisease
      │
      └── extracaoObesityStats.ipynb <- Notebook da extração do dataset ObesityStats
~~~

* Jupyter: <br>
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MatheusCod/Kinda_SUS-MC536_2s2020/main)

## Modelos conceituais:
![Modelos Conceituais](images/modelosConceituais.png)

## Modelos lógicos:
Análise obesidade(LocationAbbr,  Mortalidade_homens, Mortalidade_mulheres, Obesidade_homens, Obesidade_mulheres)

Consumo de alimentos(Gênero, Idade, Carne vermelha, Frutas, Vegetais, Proteína, Bebidas açucaradas)

Disponibilidade(Açúcares, Frutas, Carne Vermelha, Vegetais)

## Slides da Proposta

> [Etapa 2 - Seleção de Fonte de Dados.pptx](./slides/Etapa%202%20-%20Seleção%20de%20Fonte%20de%20Dados.pptx)

## Motivação e Contexto

O conjunto de diversos fatores, como o consumo de alimentos altamente calóricos e processados e uma rotina apertada e sedentária tornou a obesidade um dos grandes problemas enfrentados pelos EUA.
Devido a sua relevância, escolhemos essa questão como tema do nosso projeto, onde serão utilizados diversos dados para entender melhor as causas da obesidade e sua relevância para a incidência de doenças cardíacas.

Os seguintes aspectos serão analisados e discutidos:

Distribuição da doença nos diferentes estados e como ela afeta diferentes faixas etárias e grupos étnicos;
Efeitos da obesidade na saúde cardíaca;
Diferença dietária com outros países.

## Método

Será feita uma união entre a base de dados Obesity Stats e Heart Disease Mortality , através dos índices em comum que as duas possuem, como Estado, Sexo e Raça/Etnicidade.
A base de dados Obesity servirá de suporte para definições e associações mais específicas entre obesidade e problemas de coração.
Por fim, a base de dados Food Availability será usada para ilustrar a proporção de tipos diferentes de comida disponíveis nos EUA, enquanto a Global Dietary Database poderá fornecer um comparativo global de consumo.

## Bases de Dados

título da base | link | breve descrição
----- | ----- | -----
Obesity | http://dbpedia.org/page/Obesity | Página da DBpedia com informações úteis e definições sobre Obesidade.
Obesity Stats | https://www.kaggle.com/adu47249/obesity-stats | Estatística sobre peso nos Estados Unidos do ano 2011 até 2016.
Heart Disease Mortality | https://catalog.data.gov/dataset/heart-disease-mortality-data-among-us-adults-35-by-state-territory-and-county-d31fc/resource/5974720b-7972-4272-8eb1-277dfdc538c2 | Mortalidade por doenças do coração em adultos (+35 anos) nos EUA.
Food Availability | https://www.ers.usda.gov/data-products/food-availability-per-capita-data-system/ | Disponibilidade de comida per capita nos EUA.
Global Dietary Database | https://www.globaldietarydatabase.org/ | Consumo de grupos de alimentos em diversos países, separado por faixa etária, nível de educação, entre outros.

