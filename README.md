# Previsão de Churn de Assinantes GamersClub

Projeto de Machine Learning para identificação de futuros players que irão cancelar sua assinatura na Gamers Club.

## Motivação

Uma das fontes de receita da GC são as assinaturas de seus players. Com isso, quando há crescimento de churn (cancelamento), é um sinal de que a receita terá queda. Assim, ao identificar os possíveis players que deixarão de assinar, temos oportunidade de retê-los, podendo realizar promoções e adição de benefícios, bem como comunicação de quais funcionalidades ele pode passar a utilizar.

## Dados

Utilizaremos os dados fornecidos pela própria Gamers Club. Você pode baixar estes dados no Kaggle: [Brazilian CS:GO Platform Dataset by Gamers Club](https://www.kaggle.com/datasets/gamersclub/brazilian-csgo-plataform-dataset-by-gamers-club).

## Ferramentas

- Python 3.10
- Databricks
- MLFlow
- PostgreSQL

### 1. Introdução e definição do problema

Aqui vamos definir qual é a problemática que vamos atuar. Dando um boa introdução de como funciona a Gamers Club e seus assinaturas.
Desta forma o pessoal consegue entender melhor quais serão as oportunidades envolvidas.

### 2. Definição das Features Store

A partir dos dados, podemos identificar quais variáveis (atributos) podem fazer mais sentido para este estudo. A ideia é ao final deste encontro tenhamos as principais features preditoras do churn, em formato de Feature Store.

Feature Store criadas:
- [X] Assinatura
- [X] Gameplay
- [X] Medalha


### 3. Variável resposta e ABT

Uma das etapas mais complicadas no processo de modelagem é a definição e construção da variável resposta, i.e., a variável (evento) que desejamos prever. Neste encontro teremos não só esta definição, mas sua construção e a tabela para o treinamento do nosso algoritmo.

### 4. SEMMA

Ao organizarmos nosso mapa mental sobre o ciclo analítico, as coisas ficam mais fáceis de serem codificadas, isto é, tendo claro quais são os passos necessários a serem seguidos, podemos escrever um código mais limpo e claro. Para ajudar neste entendimento, vamos apresentar o conceito do SEMMA, desenvolvido pelo SAS Institute.

### 5. Modelo Final

Após ter treinado diversos algoritmos e testado diferentes métricas de performance, vamos decidir qual é o melhor algoritmo para explicar o evento de Churn de assinaturas na GC.

### 6. Deploy

Para gerarmos valor a partir dos dados, é necessário que outros usuários e sistemas possam consumir as informações geradas pelo modelo. Então buscamos realizar o deploy deste algoritmo em forma de Batch e/ou Real Time, seja usando agendadores ou APIs.
