# 📊 **Projeto Telecom X: Análise de Evasão de Clientes (Churn)**

## 🎯 **Propósito da Análise**

Este projeto tem como objetivo principal **identificar e compreender os fatores que levam os clientes da Telecom X a cancelar seus serviços (churn)**. Através de uma análise exploratória de dados (AED) detalhada, buscamos extrair insights valiosos que possam subsidiar a equipe de Data Science no desenvolvimento de modelos preditivos e na formulação de estratégias eficazes para reduzir a evasão de clientes.

A alta taxa de churn representa um desafio significativo para a receita e o crescimento da empresa, e esta análise é o primeiro passo para mitigar esse problema.

## 📁 **Estrutura do Projeto**

O projeto está organizado da seguinte forma:
```bash
.
├── TelecomX_Data.json         # Dados brutos dos clientes
├── TelecomX_BR.ipynb          # Notebook Jupyter com a análise completa
└── README.md                  # Este arquivo de documentação
```
- `TelecomX_Data.json`: Contém o conjunto de dados original com informações detalhadas sobre os clientes, seus serviços e status de churn.
- `TelecomX_BR.ipynb`: É o coração do projeto, onde todas as etapas de extração, transformação, limpeza, análise exploratória e visualização de dados foram realizadas.
- `README.md`: Este documento, que fornece uma visão geral do projeto.

## 📈 **Exemplos de Gráficos e Insights Obtidos**

Durante a análise exploratória, diversos gráficos foram gerados para visualizar padrões e relações entre as variáveis e o churn. Alguns dos principais insights incluem:

- **Distribuição Geral do Churn:** O gráfico de barras inicial mostrou a proporção de clientes que permaneceram versus os que saíram, destacando a magnitude do problema de evasão.
- **Evasão por Tipo de Contrato:** Gráficos de barras revelaram que clientes com contratos mensais (`Month-to-month`) apresentam uma taxa de churn significativamente mais alta em comparação com contratos de longo prazo (anuais ou bienais).
- **Evasão por Método de Pagamento:** A análise mostrou que o método de pagamento `Electronic check` está associado à maior taxa de churn, enquanto pagamentos automáticos (transferência bancária, cartão de crédito) têm menor evasão.
- **Distribuição de Meses de Contrato (`tenure`):** Histogramas sobrepostos indicaram que a maioria dos clientes que cancelam o serviço o faz nos primeiros meses de contrato (baixo `tenure`).
- **Distribuição de Gasto Total (`Charges.Total`):** Histograma revelou que clientes com menor gasto total são mais propensos a evadir, sugerindo que clientes com contas de menor valor são mais suscetíveis ao churn.
- **Gênero:** Não foi observada uma diferença significativa na taxa de evasão entre clientes masculinos e femininos.

Esses insights são cruciais para direcionar futuras estratégias de retenção e aprimorar a experiência do cliente.

## ⚙️ **Instruções para Executar o Notebook**

Para replicar e explorar a análise, siga os passos abaixo:

1. **Pré-requisitos:**
   - Python 3.x instalado.
   - Um ambiente de desenvolvimento como Jupyter Notebook ou JupyterLab.
  
2. **Instalação de Bibliotecas:**
   
    Abra seu terminal ou prompt de comando e instale as bibliotecas necessárias (se ainda não as tiver):

    ```bash
    pip install pandas matplotlib seaborn
    ```
3. **Download dos Arquivos:**
   
     Certifique-se de ter os arquivos `TelecomX_Data.json` e `TelecomX_BR.ipynb` no mesmo diretório.
   
5. **Executar o Notebook:**

   - Abra o Jupyter Notebook/Lab a partir do diretório onde os arquivos estão salvos:
   
     ```bach
     jupyter notebook
     ```
     
    - No navegador, clique em `TelecomX_BR.ipynb` para abri-lo.
    - Execute as células do notebook sequencialmente para carregar os dados, realizar o tratamento, a análise e gerar os gráficos.
   
Ao seguir estas instruções, você poderá explorar toda a análise e os insights gerados para o projeto de churn da Telecom X.
