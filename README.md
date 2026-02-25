# 📊 **Telecom X: Análise de Evasão de Clientes - Parte 2**
## 📌 Sobre o Projeto
Esse projeto é a parte 2 do projeto TelecomX e visa colocar em prática os conhecimentos adquiridos em análise de dados e machine learning para fazer uma previsão da evasão de clientes da empresa fictícia TelecomX

A partir da análise, buscamos insights para compreender os fatores que influenciam de forma positiva ou negativa na evasão dos clientes, explorando os modelos de aprendizado de máquinas que se adequem melhor à previsão categórica.

A base de dados contém informações de clientes, como tempo de contrato, tipo de contrato, formas de pagamento, planos, contratos adicionais entre outras categorias que servirão como variáveis para a análise.

## 🎯 Objetivo
Explorar modelos de Machine Learning e desenvolver modelos capazes de prever quais clientes têm maior chance de cancelar seus serviços na empresa fictícia TelecomX com os dados previamente tratados.

## 🧰 Tecnologias e Bibliotecas Utilizadas

* ![Python](https://img.shields.io/badge/Python-Programming-blue) **Linguagem de Programação:** Utilizada para todo o desenvolvimento do projeto.
* ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange) **Ambiente de Desenvolvimento:** Usado para escrever, executar e documentar o código de forma interativa.
* ![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green) **Manipulação de Dados:** Utilizada para leitura e tratamento do dataframe.
* ![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-lightblue) **Suporte Matemático:** Usada para operações matemáticas e numéricas.
* ![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Visualization-red) **Visualização de Dados:** Criação de gráficos personalizados.
* ![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-purple) **Análise Estatística:** Utilizada para gerar o Heatmap de correlação e gráficos estatísticos.
* ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-yellow) **Machine Learning:** Usada para construção e avaliação de modelos preditivos.

## 📂 Estrutura do Projeto

**README.md**: Arquivo com descrição do projeto.

**TelecomX-parte2.ipynb**: Notebook contendo todas as células de execução do projeto e relatório final.

**dados_tratados.csv**: Base de dados tratada na parte 1 do projeto. 

## 🔄 Pipeline do Projeto

O projeto foi estruturado em etapas sequenciais, formando um fluxo de trabalho claro:
 
1. Preparação dos Dados:
    * Extração do Arquivo Tratado: Extrair o arquivo CSV previamente tratado
    * Remoção de Colunas Irrelevantes: Eliminar colunas que não trazem valor para a análise
    * Encoding: Transformar variáveis categóricas em numéricas para torná-las compatíveis com algoritmos de machine learning, com o método One-Hot Encoding.
    * Verificação da Proporção de Evasão: Calcular a proporção de clientes que evadiram em relação aos que permaneceram ativos
2. Correlação e Seleção de Variáveis:
    * Visualizar a matriz de correlação para identificar relações entre variáveis numéricas
    * Análises Direcionadas: Investigar como variáveis específicas se relacionam com a evasão, gerando gráficos como boxplot ou de dispersão (scatter plots)
3. Modelagem Preditiva:
    * Separação de Dados: Dividir dados em treino e teste para avaliar o desempenho do modelo
    * Criação de Modelos: Criar modelos diferentes para prever a evasão dos clientes
    * Avaliação dos Modelos: Avalie cada modelo utilizando métricas de acurácia precisão, recall, f1-score e matriz de confusão. Em seguida fazer uma análise crítica e comparar os modelos, verificar também modelos com Overfitting ou Underfitting
4. Análise de Importância das Variáveis:
    * Análise das variáveis mais relevantes para a previsão de evasão
    * Conclusão: Fazer relatório detalhado destacando os fatores que mais influenciam a evasão, com base nas variáveis selecionadas e no desempenho de cada modelo.

## 🚀 Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/marcosamcorreia/Desafio-TelecomX-parte2

2. Abra o arquivo 'TelecomX-parte2.ipynb', pelo Google Collab ou como preferir
3. Altere o caminho do arquivo caso necessário 'dados = pd.read_csv('/CAMINHO/dados_tratados.csv')'
4. Execute todas as células
5. Leia o relatório final no final do projeto

