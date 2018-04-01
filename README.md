# F1 Big Data Challenge
Solução para o desafio proposto desenvolvido em python utilizando pandas.


## Relatórios

1. Pontuação mediana por temporada dos 20 melhores pilotos das últimas 10 temporadas

2. Todas as corridas onde apenas 3 equipes pontuaram.

3. Melhor tempo de Pitstop e equipe que executou e piloto que estava no carro por temporada

4. Melhor tempo de Pitstop por equipe por temporada

5. Piloto que mais pontuou daqueles que nunca subiram no pódio 

   o piloto não pode ter subido em um pódio em sua carreira da formula um para entrar nesse grupo

Gere os relatório em um formato **xlxs**, não esqueça adicionar os relatórios no
seu repositório.


## Dataset

Foi utilizado o dataset **formula-1-race-data** disponível no Kaggle:

* [Formula 1 Race Data](https://www.kaggle.com/cjgdev/formula-1-race-data-19502017)


## Pré-requisitos

- Instalar a lib openpyxl para gerar arquivos **xlsx**.


## Como executar

- Para executar os relatórios foi utilizado a imagem: [Docker com Jupyter/PySpark](https://hub.docker.com/r/jupyter/pyspark-notebook/)
- Executar com o seguinte comando para inicializar o container: docker run -e GRANT_SUDO=yes --user root -it -p 8888:8888 jupyter/pyspark-notebook
- Copiar o dataset e notebooks para o container
- Criar a pasta reports
- Instalar via conda a lib openpyxl no environment root do container inicializado
- Rodar notebooks
- Os relatórios serão gerados na pasta reports no formato xlsx


## Diretórios

* dataset - arquivos baixados do kaggle
* reports - relatórios gerados a partir dos notebooks
