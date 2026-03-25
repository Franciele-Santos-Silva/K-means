# Aplicação de Técnicas de IA: K-means no Dataset Iris

Este projeto consiste na aplicação do algoritmo K-means ao conjunto de dados Iris, obtido do UCI Machine Learning Repository. O objetivo é realizar uma análise de classificação não supervisionada, avaliando a capacidade do K-means em agrupar as amostras de flores de acordo com suas espécies. A execução do experimento foi realizada variando o percentual de dados utilizados para treino, de 10% a 80%, repetindo cada cenário 20 vezes para garantir robustez estatística.

## Descrição dos Arquivos
- **kmeans_iris.m**: Script MATLAB que realiza a leitura do dataset, embaralha os dados, executa o K-means para diferentes percentuais de treino, calcula acurácia e salva os resultados em CSV.  
- **iris.csv**: Conjunto de dados com 150 amostras de flores Iris, contendo 4 atributos numéricos e 1 coluna de espécie.  
- **resultados_kmeans.csv**: Arquivo gerado pelo script contendo estatísticas (mínimo, máximo, média e desvio padrão) das taxas de acerto para cada percentual de treino.  

## Instruções para Executar
1. Abra o MATLAB.  
2. Navegue até a pasta do repositório.  
3. Execute o script `kmeans_iris.m`.  
4. Ao final da execução, os resultados serão salvos em `resultados_kmeans.csv`.  
5. É possível visualizar as primeiras linhas do dataset e as estatísticas de cada execução diretamente no terminal do MATLAB.

## Tecnologias Utilizadas
- MATLAB R2026  
- Dataset Iris (UCI Machine Learning Repository) 
