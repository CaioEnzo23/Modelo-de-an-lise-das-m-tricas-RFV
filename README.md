# Desafio: Crie um modelo de análise das métricas RFV

Este projeto foi criado com o intuito de aprimorar habilidades em Python utilizando um modelo de clusterização. 
O objetivo neste projeto é desenvolver um modelo de clusterização que é capaz de agrupar os clientes conforme o seu comportamento de compras levando em consideração o RFV.
Analisei os clusters obtidos para assim identificar o perfil de cliente, como padrões e características em comum para determinar o seu comportamento de compra. 
Utilizei gráficos e visualizações para auxiliar na análise.

Portanto separei este projeto em 5 partes :

# Análise exploratória dos dados

- Realizei uma descrição estatística dos dados com describe().
- Visualizei as distribuições e identifiquei a relevância das colunas para a análise com gráfico gerados com hist e figure.
- Verifiquei a presença de dados nulos, duplicados, outliers e demais inconsistências nos dados usando isnull, duplicated, figure e describe.
- Fiz o tratamento de dados.

![image](https://github.com/user-attachments/assets/539ac587-2733-4bde-9030-316bb1a75f8a)

![image](https://github.com/user-attachments/assets/45adc4e8-7f48-465b-85c4-ebb9233befaa)


# Pré-processamento dos dados

- Realize a normalização dos dados com fillna, astype e MinMaxScaler.
- Removi os dados nulos, duplicados, outliers e inconsistentes com fillna e isnull.

![image](https://github.com/user-attachments/assets/c3182590-6256-42a3-a563-48d38a2f37c1)


# Seleção de um algoritmo de clusterização

- Escolhi um algoritmo adequado para base de dados que no caso K0Means foi o algoritmo ultilizado.
- Encontrei a quantidade ideal de clusters através dos métodos de Elbow com scaler e inertia.
- Implemente o algoritmo escolhido que foi o K0Means.

![image](https://github.com/user-attachments/assets/eff129eb-4cc5-4bf7-86b3-ca8d6792c937)

![image](https://github.com/user-attachments/assets/1f800da5-f5b6-4dd1-a965-6080c0e69c69)

![image](https://github.com/user-attachments/assets/79c6accc-d54e-4de4-9ecb-739534f37d56)


# Analise os clusters obtidos

- Identifiquei os padrões e características em comum entre os clientes com fit e score.
- Plotei gráficos para auxiliar na análise com visualizer e index.

![image](https://github.com/user-attachments/assets/0841cb82-4040-4cba-ade3-b397005513fb)

![image](https://github.com/user-attachments/assets/37b00f5f-d10b-4b74-a7c5-ba3eaf6f0b6d)

![image](https://github.com/user-attachments/assets/26a898cf-e1fe-4629-a321-28908e6db6b7)

# Dados de Clientes

Fiz analise de dados e plotei gráfico dos clientes que compram os mesmos produtos.

![image](https://github.com/user-attachments/assets/16367325-392e-45e0-bd50-416d170d01c4)

![image](https://github.com/user-attachments/assets/2663b59d-cffb-4e9d-a866-9bb256b3f945)

Fiz analise de dados e plotei gráfico dos clientes que possuem a mesma frequência de compras.

![image](https://github.com/user-attachments/assets/c8d34c33-20e9-481a-9d2d-948910fbe678)

![image](https://github.com/user-attachments/assets/6948d9fc-0575-42cf-8150-3c326c63a426)

Fiz analise de dados e plotei gráfico dos clientes que gastam mais dinheiro em suas compras.

![image](https://github.com/user-attachments/assets/b2d024df-d9b5-46ba-86c6-4b85459a96da)

![image](https://github.com/user-attachments/assets/141922fc-d484-45bf-91d8-af1e34590b79)

# Interpretação dos resultados obtidos

- Descrevi o perfil de compras dos clientes de cada cluster pára assim atingir a maior taxa de sucesso.
- Justifiquei como essa análise pode ser útil para empresa para segmentação de seus clientes e personalização das campanhas de marketing.
- Sugiri ações possíveis com base nas ações realizadas para a Concentração dos Esforços do Marketing.
