# Custo do Plano de Saúde: Análise Estatística dos Fatores Associados e Ações Preventivas

[![Medium](https://img.shields.io/badge/Artigo%20completo-Medium-black?logo=medium\&logoColor=white)](https://medium.com/@luizamarchenib/custo-do-plano-de-sa%C3%BAde-an%C3%A1lise-estat%C3%ADstica-dos-fatores-associados-e-a%C3%A7%C3%B5es-preventivas-97eab0e7c24b?postPublishedType=repub)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1TsPMjdWwlFcJZOGfKEtYp2lnOP1vg63d?usp=sharing)

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
custos_plano_de_saude/
│
├── custos_plano_de_saude.ipynb    # Notebook com a análise dos dados
├── base_plano_de_saude.xlsx       # Base de dados utilizada no projeto
├── requirements.txt                # Dependências do projeto
```

## Como reproduzir a análise

A maneira mais simples é abrir o notebook diretamente no Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1TsPMjdWwlFcJZOGfKEtYp2lnOP1vg63d?usp=sharing)

Caso prefira executar localmente:

```bash
git clone https://github.com/luizamb2306/custos_plano_de_saude
cd custos_plano_de_saude
pip install -r requirements.txt
jupyter notebook custos_plano_de_saude.ipynb
```

