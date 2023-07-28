# Find Bank Score

## Ideia

**Case: Score de Crédito dos Clientes de um banco**

A ideia é simular que um banco precisa conseguir definir o score de crédito dos seus clientes.

Para isso é necessário analisar todos os clientes do banco e com base nessa análise, criar um modelo que consiga aprender usando a biblioteca de Machine Learning *Scikit-Learn* e ensinar com 70% das informações do clientes a IA prever o score de novos clientes e dizer automaticamente se o score de crédito dele: **Poor , Standard, Good**

## Documentação - Documentation
O próprio arquivo jupyter já está documentado e comentado.

## Ferramentas - Tools 
As ferramentas e Bibliotecas utilizadas foram:

- **Pandas**
- **Numpy**
- **Scikit-Learn**
  - **LabelEncoder**
    > cria o codificador para transformar dados string em inteiro.
  - **train_test_split**
    > realiza a divisão da base de dados para 70% dados de treino e 30% dados de teste.
  - **RandomForestClassifier**
    > instância um algoritmo de modelo Árvore de Busca para realizar a previsão.
    ![ArvoreDeBusca](https://www.homemmaquina.com.br/wp-content/uploads/2020/07/arvorededecisao1.png)
  - **KNeighborsClassifier**
    > instância um algoritmo de modelo KNN - Nearest Neighbors para realizar a previsão.
    ![KNN](https://miro.medium.com/v2/resize:fit:640/format:webp/1*wW8O-0xVQUFhBGexx2B6hg.png)

**Obs.:** Para testar o código é necessário ter as bibliotecas acima instaladas, caso não tenha segue abaixo o comando para instalar no terminal.

```
pip install pandas numpy scikit-learn
```
