# Análise Textual Discursiva com Python

Esta é uma implementação da técnica de Análise Textual Discursiva (ATD), proposta por Galiazzi e Moraes. São utilizadas técnicas de Processamento de Linguagem Natural (PLN) e Análise de Co-ocorrência (ACoO). Além disso, são utilizadas outras técnicas, como a identificação de entidades nomeadas e a geração de nuvem de palavras, para auxiliar na análise do texto. Por fim, após a análise, os resultados obtidos são submetidos à analise crítica, utilizando o LLM do Deepseek R1. 

É importante destacar que o LLM pode ser alterado conforme for necessário.

O LLM é rodado localmente, garantindo uma maior segurança e controle sobre os dados.

## Funcionalidades

- Análise de frequência de palavras
- Identificação de entidades nomeadas
- Geração de nuvem de palavras (wordcloud)
- Análise de coocorrência de palavras
- Visualização de redes de palavras
- Agrupamento (clustering) de termos relacionados
- Analise crítica automatizada utilizando LLM local

## Requisitos

- Python 3.x
- spaCy (com modelo pt_core_news_md)
- NLTK
- Pandas
- Matplotlib
- Seaborn
- NetworkX
- WordCloud
- scikit-learn
- OpenAI

OBS: É necessário ter o LLM rodando localmente.

## Instalação

1. Clone este repositório:
```bash
git clone [URL_DO_REPOSITORIO]
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Baixe o modelo em português do spaCy:
```bash
python -m spacy download pt_core_news_md
```

## Como Usar

O projeto está estruturado em um notebook Jupyter (`main.ipynb`) que contém todas as análises e visualizações. Para executar:

1. Inicie o Jupyter Notebook:
```bash
jupyter notebook
```

2. Abra o arquivo `main.ipynb`
3. Execute as células sequencialmente para realizar as análises

## Estrutura do Projeto

- `main.ipynb`: Notebook principal com todas as análises
- `requirements.txt`: Lista de dependências do projeto

## Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

