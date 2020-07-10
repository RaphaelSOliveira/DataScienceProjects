# Detecção de Cliques Fraudulentos

## Kaggle e Fonte de Dados

Os dados trabalhados nesse projeto são públicos. Eles foram retirados do site [Kaggle](https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection/data).
Este site é amplamente utilizado por cientistas de dados que querem colocar o seu conhecimento à prova.
Foi utilizado o dataset train_sample, que possui menos registros, pois não estou utilizando nenhuma técnica de Big Data.

## Resumo:

### O problema de negócio:

A maior plataforma independente de serviço de big data da China, cobre mais de
70% dos dispositivos móveis ativos em todo o país. Eles processam 3 bilhões de
cliques por dia, dos quais 90% são potencialmente fraudulentos. Sua abordagem
atual para evitar a fraude de cliques para desenvolvedores de aplicativos é
medir a jornada do clique de um usuário em e sinalizar endereços
IP que produzem muitos cliques, mas nunca acabam instalando aplicativos.

### Objetivo do Trabalho:

Criar um modelo de classificação que avaliará se um usuário fará o download de um aplicativo depois de clicar em um anúncio de aplicativo para celular.

### Linguagem Utilizada:

Este trabalho foi realizado com a linguagem R. Para detalhes de código acessar o link do github.

## Conclusão:

O modelo alcançou uma ótima acurácia permitindo a conclusão do projeto. As estapas de seleção de variáveis e de balanceamento do dataset foram de estrema importância para que o modelo preditivo tivesse uma boa taxa de acertos. Além disso, o algorítmo RandomForest se sobressaiu em relação ao SVM.
