# Desafio - Ifood

Este projeto foi desenvolvido como parte do módulo de Estatística Descritiva do curso EBA - Estatística do Básico ao Avançado, ministrado pela Professora Renata Biaggi. 
O desafio envolve a análise exploratória de dados de clientes do Ifood, com o objetivo de investigar padrões de consumo e perfis de clientes. 

Para mais informações sobre o curso, acesse o site: [EBA - Estatística do Básico ao Avançado](https://renatabiaggi.com/eba/).

## Dados

O conjunto de dados contém informações sobre:
- Perfis de clientes (renda, filhos, estado civil, etc.)
- Preferências de produto (gastos com diferentes categorias)

## Objetivo
O objetivo deste projeto é realizar uma análise exploratória dos dados para entender o comportamento de consumo dos clientes e identificar correlações entre variáveis como renda, número de filhos e gastos.

## Análises Realizadas
- **Distribuição de Renda**: Analisada através de histogramas e boxplots para observar a dispersão e simetria dos dados.
![histograma_renda](https://github.com/user-attachments/assets/dee45a6c-7479-4466-969e-fe74f5a16b66)
- **Perfis de Educação**: Comparação dos níveis de educação dos clientes, identificando uma predominância de clientes com graduação.
- **Estado Civil e Número de Filhos**: Investigação sobre a relação entre estado civil e número de filhos por meio de boxplots e estatísticas descritivas.
  ![estado-civil](https://github.com/user-attachments/assets/5f0f5bbf-de96-4871-b6bd-d41219b92150)
- **Gastos vs Filhos**: Comparação de gastos em diferentes faixas de clientes com base no número de filhos.
![boxplot_filhos_vs_gastos](https://github.com/user-attachments/assets/71d9a5c3-142c-4a77-adbe-b512da9b87c8)
- **Correlação entre Gastos e Renda**: Avaliada através de gráficos de dispersão e cálculo da correlação de Pearson.
  ![gastsosrenda](https://github.com/user-attachments/assets/9f586b1e-05f5-48d7-93f3-0f43d1573dd3)
- **Comparação de Consumo entre Faixas de Renda**: Análise detalhada do consumo de diferentes categorias de produtos, como vinhos e carne, por faixa de renda (baixa, média e alta).
  ![gastos-faixa](https://github.com/user-attachments/assets/8efe16d7-91ed-4716-991b-e34b47b815f3)


## Conclusões
- Clientes com maior renda tendem a gastar mais, conforme mostrado pela correlação forte entre renda e despesas.
- Os clientes de alta renda têm um consumo elevado de vinhos, enquanto os de baixa renda gastam mais em carne.
- Há uma distribuição relativamente equilibrada de gastos entre clientes com e sem filhos, embora aqueles sem filhos gastem ligeiramente mais.
- A maioria dos clientes está concentrada nas faixas de renda média e alta, e a educação de nível superior predomina na base de dados.

## Ferramentas Utilizadas
- **Pandas**: Manipulação e análise de dados
- **Matplotlib** e **Seaborn**: Visualização de dados
- **Numpy**: Operações numéricas
- **Jupyter Notebook**: Ambiente de desenvolvimento interativo
