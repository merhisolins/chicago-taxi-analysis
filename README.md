# Análise de Dados - Festival News

## Descrição:
Este projeto tem como objetivo a análise de dados relacionados a eventos de festivais. O foco é extrair informações relevantes a partir de um conjunto de dados estruturado em formato HTML, transformando-os em insights valiosos.

As principais informações extraídas incluem:

- Localização e datas dos festivais.
- Avaliações de público e participação ao longo dos anos.
- Impacto econômico e cultural dos eventos.
- Tendências e padrões de popularidade.

A metodologia aplicada envolve a extração e tratamento de dados, análise estatística e visualização gráfica para melhor compreensão das informações.

## Conjunto de Dados:
O conjunto de dados utilizado no projeto está armazenado no arquivo **festival_news.html** e contém as seguintes colunas principais:

- **Festival Name** (Nome do festival)
- **Location** (Localização)
- **Date** (Data do evento)
- **Attendance** (Público presente)
- **Revenue** (Receita gerada pelo evento)

Os dados foram estruturados e convertidos para um formato tabular utilizando a biblioteca `pandas`.

## Arquitetura e Tecnologias Utilizadas
Este projeto segue um modelo de **análise de dados estruturada**, garantindo eficiência no processamento e exploração dos dados. A abordagem se divide em:

🔹 **Extração e Tratamento de Dados**: Leitura de arquivos HTML e conversão para DataFrames com `pandas`.
🔹 **Análise Exploratória**: Limpeza, padronização e tratamento de valores ausentes.
🔹 **Visualização de Dados**: Representação gráfica com `Matplotlib` e `Seaborn`.

As principais tecnologias e bibliotecas utilizadas incluem:

- **Python 3.8+** – Linguagem base para manipulação de dados.
- **Pandas** – Extração e processamento de tabelas estruturadas.
- **NumPy** – Suporte para manipulação numérica e vetorial.
- **Matplotlib / Seaborn** – Criação de visualizações gráficas.
- **LXML** – Leitura de arquivos HTML e conversão de tabelas.
- **Jupyter Notebook** – Desenvolvimento interativo e documentação de insights.

## Execução do Projeto

### 🔧 Pré-requisitos
Certifique-se de que possui o **Python 3.8+** instalado em sua máquina. Para instalar todas as dependências necessárias, execute o seguinte comando no terminal:

```bash
pip install -r requirements.txt
