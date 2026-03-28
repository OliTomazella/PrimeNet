## Comparação de Conteúdo: Netflix vs. Amazon Prime Video
Este projeto realiza uma análise exploratória e estatística comparando os catálogos das duas maiores plataformas de streaming. O objetivo foi entender as estratégias de conteúdo, distribuições de gêneros e validar hipóteses sobre as bibliotecas de títulos.

## Estrutura do Projeto
01_Data: Contém os datasets originais e as versões tratadas após a limpeza.

02_notebook: Notebooks numerados que documentam todo o processo de análise.

outputs: Gráficos e visualizações geradas durante o estudo.

## Etapas do Desenvolvimento
O projeto foi dividido em quatro fases principais para garantir a reprodutibilidade:

1.  Limpeza e Tratamento (ETL)
Amazon Prime: Tratamento de valores nulos, padronização de datas e limpeza de strings na base original.

Netflix: Aplicação do mesmo rigor de limpeza para garantir que as bases fossem comparáveis.

Arquivo: 02_notebook/amazon_analise.ipynb e netflix_analise.ipynb

2. Análise Individual
Exploração de métricas como: ano de lançamento, classificação indicativa e volume de filmes vs. séries em cada plataforma isoladamente.

3. Comparação Direta
Cruzamento das bases limpas para identificar diferenças na estratégia de catálogo entre Prime Video e Netflix.

Arquivo: 02_notebook/comparação_PrimeNet.ipynb

4. Teste de Hipóteses
Aplicação de testes estatísticos para validar se as diferenças observadas (como média de lançamentos ou proporção de gêneros) são significativamente diferentes.

Arquivo: 02_notebook/teste_hipoteses_streaming.ipynb

## Principais Tecnologias
Python (Pandas, Matplotlib, Seaborn)

Estatística Computacional

Jupyter Notebook

## Como visualizar
Clone o repositório.

Os datasets tratados estão na pasta 01_Data.

Os resultados visuais mais importantes podem ser encontrados na pasta outputs