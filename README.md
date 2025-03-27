# README - Projeto de Regressão Linear Simples

## 📌 Visão Geral

Este projeto demonstra a aplicação de um modelo de **Regressão Linear Simples** para prever o salário de um indivíduo com base em seus anos de experiência profissional. O modelo foi desenvolvido em Python utilizando bibliotecas como `pandas`, `numpy`, `matplotlib` e `scikit-learn`.

---

## 📊 Conteúdo do Projeto

1. **Análise Exploratória de Dados**:
   - Carregamento e visualização inicial dos dados.
   - Exploração da relação entre anos de experiência e salário.

2. **Pré-processamento**:
   - Separação das variáveis independentes (`YearsExperience`) e dependente (`Salary`).
   - Transformação dos dados para o formato adequado para o modelo.

3. **Modelagem**:
   - Criação e treinamento do modelo de Regressão Linear usando `scikit-learn`.
   - Geração de previsões com base nos dados de treinamento.

4. **Visualização dos Resultados**:
   - Gráfico de dispersão dos dados reais.
   - Linha de regressão para visualizar a relação entre experiência e salário.

5. **Resultados**:
   - O modelo mostra uma correlação positiva entre anos de experiência e salário, conforme esperado.

---

## 🛠️ Tecnologias Utilizadas

- **Python** (Linguagem de programação)
- **Pandas** (Manipulação de dados)
- **NumPy** (Cálculos numéricos)
- **Matplotlib** (Visualização de dados)
- **Scikit-learn** (Machine Learning)

---

## 📂 Estrutura do Projeto

O projeto está organizado em um Jupyter Notebook (`Regressão_Linear_Simples.ipynb`), que contém:

1. **Importação de Bibliotecas**:
   - Carregamento das bibliotecas necessárias.

2. **Carregamento dos Dados**:
   - Leitura do arquivo `Salary.csv` contendo os dados de anos de experiência e salário.

3. **Preparação dos Dados**:
   - Separação das variáveis (`X` para anos de experiência, `y` para salário).
   - Transformação dos dados para o formato adequado.

4. **Treinamento do Modelo**:
   - Criação do objeto `LinearRegression`.
   - Ajuste do modelo aos dados de treinamento.

5. **Visualização**:
   - Gráfico comparando dados reais e a linha de regressão.

---

## 📈 Como Executar o Projeto

1. **Pré-requisitos**:
   - Python 3.x instalado.
   - Bibliotecas listadas no arquivo de requisitos (instaláveis via `pip`).

2. **Instalação das Dependências**:
   ```bash
   pip install pandas numpy matplotlib scikit-learn]
   
3. **Execução**
   - Abra o Jupyter Notebook em seu ambiente local ou no Google Colab.
   - Execute as céluas sequencialmente.

---

## 📝 Conclusão
Este projeto ilustra como a Regressão Linear Simples pode ser aplicada para prever salários com base em anos de experiência. O modelo pode ser aprimorado com mais dados ou técnicas avançadas de Machine Learning.
