# Custo do Plano de Saúde: Análise Estatística dos Fatores Associados e Ações Preventivas

[![Medium](https://img.shields.io/badge/Artigo%20completo-Medium-black?logo=medium\&logoColor=white)](LINK_MEDIUM)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](LINK_COLAB)

## Contexto

Uma empresa do setor alimentício, com mais de 20 mil colaboradores distribuídos pelo Brasil, identificou ao longo dos anos um crescimento nos custos relacionados ao plano de saúde oferecido aos seus funcionários.

Para investigar os fatores associados a esse aumento, a área de Benefícios e Bem-Estar realizou uma pesquisa interna com uma amostra aleatória de 1.338 colaboradores.

Foram analisadas características como idade, sexo, IMC, quantidade de filhos, tabagismo e região, juntamente com o Custo do Plano de Saúde.

## Objetivo

Identificar os principais fatores associados ao Custo do Plano de Saúde e quantificar a magnitude dessas associações, de forma a direcionar possíveis ações preventivas para contribuir com a redução dos custos.

## Análise

O projeto realizou:

* Análise exploratória univariada e bivariada dos dados;
* Análise das associações entre as características dos colaboradores e o Custo do Plano de Saúde;
* Regressão linear múltipla por Mínimos Quadrados Ordinários;
* Avaliação de multicolinearidade por meio do VIF;
* Testes de Breusch-Pagan e Jarque-Bera;
* Utilização de erros-padrão robustos HC3;
* Construção de intervalos de confiança para características da população.

## Resultados

Os principais fatores associados ao Custo do Plano de Saúde foram:

* **Tabagismo:** maior associação monetária estimada, com fumantes apresentando custo médio estimado **R$ 2.381,14 superior** ao de não fumantes, mantendo as demais variáveis constantes.
* **Quantidade de filhos:** cada filho adicional esteve associado a um aumento médio estimado de **R$ 47,35** no custo.
* **IMC:** cada aumento de um ponto no IMC esteve associado a um aumento médio estimado de **R$ 32,19** no custo.
* **Idade:** cada ano adicional de idade esteve associado a um aumento médio estimado de **R$ 25,79** no custo.

O modelo final apresentou **R² de aproximadamente 0,75**.

Com base nesses resultados, foram propostas ações preventivas relacionadas principalmente à cessação do tabagismo, promoção de hábitos saudáveis e acompanhamento preventivo ao longo do ciclo de vida.

## Tecnologias

* Python
* Pandas
* NumPy
* SciPy
* Statsmodels
* Matplotlib
* Seaborn

## Estrutura do projeto

```text
NOME_DO_REPOSITORIO/
│
├── NOME_DO_NOTEBOOK.ipynb    # Notebook com a análise dos dados
├── base_plano_de_saude.xlsx  # Base de dados utilizada no projeto
├── requirements.txt           # Dependências do projeto
```

## Como reproduzir a análise

A maneira mais simples é abrir o notebook diretamente no Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](LINK_COLAB)

Caso prefira executar localmente:

```bash
git clone LINK_REPOSITORIO
cd NOME_DO_REPOSITORIO
pip install -r requirements.txt
jupyter notebook NOME_DO_NOTEBOOK.ipynb
```

## Artigo completo

A descrição detalhada da metodologia, dos resultados e das conclusões está disponível no Medium:

[Custo do Plano de Saúde: Análise Estatística dos Fatores Associados e Ações Preventivas](LINK_MEDIUM)
