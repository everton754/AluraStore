# Análise de Vendas da AluraStoreBr

Bem-vindo ao notebook de análise de vendas da AluraStoreBr! Este projeto foi desenvolvido no Google Colab para explorar os dados de vendas de uma empresa fictícia, a AluraStoreBr, com o objetivo de fornecer insights acionáveis para otimizar suas estratégias de negócios.

---

## Propósito da Análise Realizada

Esta análise exploratória tem como objetivo entender o desempenho das vendas da AluraStoreBr ao longo do tempo (jan/2020 a mar/2023). A análise busca:

- Identificar padrões sazonais nas vendas.
- Avaliar o desempenho de diferentes categorias de produtos.
- Analisar tendências de faturamento por loja.
- Fornecer recomendações estratégicas, como a identificação de qual loja o Senhor João deveria vender com base em métricas financeiras e de satisfação do cliente.

---

## Estrutura do Projeto e Organização dos Arquivos

O projeto é organizado de forma simples e funcional no ambiente do Google Colab:

- **Notebook:** `AluraStoreBr.ipynb`
  - Contém todo o código necessário para a análise, incluindo:
    - Importação de bibliotecas (`pandas`, `matplotlib`, `plotly`).
    - Carregamento e limpeza dos dados.
    - Análise exploratória e geração de visualizações interativas.
- **Dados:** `vendas_alurastorebr.csv`
  - Arquivo CSV com os dados de vendas da AluraStoreBr, que deve ser carregado manualmente no ambiente do Colab. Inclui informações como faturamento mensal por loja, categorias de produtos e avaliações dos clientes.

---

## Exemplos de Gráficos e Insights Obtidos

Aqui estão alguns dos principais gráficos gerados no notebook, acompanhados de insights relevantes:

### 1. Tendência de Faturamento Mensal por Loja
- **Gráfico de Linha Interativo (Plotly):**
  - Mostra o faturamento mensal de cada loja (Loja 1 a Loja 4) entre jan/2020 e mar/2023.
  - Exemplo: ![Tendências de Faturamento](https://via.placeholder.com/600x400.png?text=Tendência+de+Faturamento)
- **Insights:**
  - Picos de vendas em julho/2022 (~R$ 50.000–R$ 60.000), possivelmente devido a alta demanda por eletrônicos e móveis.
  - Quedas significativas em junho/2021 e junho/2022 (~R$ 20.000), sugerindo baixa sazonalidade.
  - Loja 4 apresenta picos menores e quedas mais frequentes, indicando desempenho inferior.

### 2. Vendas por Categoria de Produto
- **Gráfico de Barras:**
  - Compara o total de unidades vendidas por categoria (ex.: Móveis, Eletrônicos, Eletrodomésticos).
  - Exemplo: ![Vendas por Categoria](https://via.placeholder.com/600x400.png?text=Vendas+por+Categoria)
- **Insights:**
  - Loja 4 depende fortemente de Móveis (20,4%) e Eletrônicos (19,1%), mas tem desempenho fraco em Eletrodomésticos e Instrumentos Musicais.
  - Loja 1 lidera em diversificação de categorias, contribuindo para seu maior faturamento total (R$ 1,47 mi).

### 3. Distribuição de Avaliações por Loja
- **Gráfico de Pizza:**
  - Exibe a média de avaliações dos clientes por loja.
  - Exemplo: ![Distribuição de Avaliações](https://via.placeholder.com/600x400.png?text=Distribuição+de+Avaliações)
- **Insights:**
  - Loja 3 possui a melhor média de avaliações (4,0483), indicando alta satisfação do cliente.
  - Loja 4, com 3,9958, está entre as piores, sugerindo problemas na experiência do cliente.

---

## Instruções para Executar o Notebook

Siga os passos abaixo para reproduzir a análise no Google Colab:

1. **Acesse o Notebook:**
   - Abra o arquivo `AluraStoreBr.ipynb` no Google Colab através deste [link](https://colab.research.google.com/drive/1IoRY3Mm_MKhmqnlqHWIPf17S8Qw0-pCB?usp=sharing) ou faça upload do arquivo manualmente.

2. **Carregue os Dados:**
   - Faça upload do arquivo `vendas_alurastorebr.csv` no ambiente do Colab:
     - Clique no ícone de pasta à esquerda.
     - Arraste o arquivo ou use o botão "Upload".
   
3. **Instale Dependências:**
   - A primeira célula do notebook contém os comandos para instalar as bibliotecas necessárias (`pandas`, `matplotlib`, `plotly`). Execute-a com `Shift + Enter`.

4. **Execute o Notebook:**
   - Execute todas as células sequencialmente clicando em "Run All" no menu "Runtime" ou pressionando `Ctrl + F9`.
   - Certifique-se de que o arquivo CSV esteja carregado antes de rodar as células de análise.

**Pré-requisitos:**
- Conexão com a internet para o Google Colab.
- As bibliotecas são instaladas automaticamente no ambiente, sem necessidade de configuração adicional.

---

## Conclusão

Este notebook oferece uma análise detalhada e visualizações interativas que ajudam a entender o desempenho da AluraStoreBr. A recomendação final de vender a Loja 4 é baseada em seu baixo faturamento, falta de diversificação e menor satisfação do cliente. Para mais detalhes, explore o notebook!
