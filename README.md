---

## Propósito da Análise Realizada

O objetivo deste notebook é apoiar a decisão de qual das quatro lojas do Senhor João deve ser vendida, utilizando análise de dados detalhada. A análise busca:

- Avaliar o desempenho financeiro de cada loja (faturamento total e tendências ao longo do tempo).
- Identificar padrões sazonais e oscilações de vendas.
- Investigar a diversificação e performance de categorias de produtos e produtos mais vendidos.
- Comparar métricas de satisfação do cliente e eficiência logística (frete médio e sua proporção no faturamento).
- Fornecer uma recomendação baseada em evidências, considerando fatores como rentabilidade, potencial de crescimento e experiência do cliente.

---

## Estrutura do Projeto e Organização dos Arquivos

O projeto está estruturado para facilitar manutenção, reprodutibilidade e análise detalhada:

- **Notebook principal:**
`AluraStoreBr.ipynb`
Contém todo o pipeline de análise, desde a importação dos dados até a recomendação final, organizado em células e funções modulares.
- **Arquivos de dados:**
    - `loja_1.csv`, `loja_2.csv`, `loja_3.csv`, `loja_4.csv`
Cada arquivo representa as vendas de uma loja distinta, incluindo colunas como Produto, Categoria, Preço, Frete, Data da Compra, Avaliação, entre outras.
- **Dependências:**
    - `pandas`, `matplotlib`, `seaborn`, `plotly`, `logging`
Instaladas automaticamente no Google Colab ou via pip.
- **Organização interna do notebook:**
    - Funções de leitura, validação e limpeza dos dados.
    - Funções para análise exploratória (estatísticas, tratamento de outliers, duplicatas, tipos de dados).
    - Funções para visualização interativa (histogramas, boxplots, barras, linhas).
    - Funções específicas para análise de categorias, produtos, tendências temporais, frete e avaliações.
    - Pipeline principal que executa todas as etapas sequencialmente.

---

## Exemplos de Gráficos e Insights Obtidos

### 1. Faturamento Total e Tendências Temporais por Loja

- **Gráfico de barras:** Mostra o faturamento total de cada loja, permitindo identificar rapidamente a loja de menor desempenho.
- **Gráfico de linhas (interativo):** Exibe a evolução mensal do faturamento de cada loja, revelando sazonalidades, picos e quedas ao longo dos anos.
- **Insight:** Loja 4 apresenta o menor faturamento total e quedas frequentes ao longo do tempo, sugerindo menor potencial de crescimento.


### 2. Distribuição de Preço, Frete e Avaliação

- **Histogramas e boxplots (interativos):** Permitem observar a dispersão e assimetria dos preços, fretes e avaliações por loja.
- **Insight:** A maioria dos fretes está abaixo de R\$50, mas lojas com frete médio mais alto podem indicar ineficiências logísticas.


### 3. Faturamento por Categoria e Produtos Mais Vendidos

- **Gráfico de barras:** Compara o faturamento por categoria de produto em cada loja.
- **Gráfico de barras:** Top 5 produtos mais vendidos por loja.
- **Insight:** Loja 4 depende fortemente de poucas categorias, enquanto Loja 1 é mais diversificada e resiliente a oscilações.


### 4. Avaliação Média por Loja

- **Gráfico de barras:** Exibe a média de avaliações dos clientes por loja.
- **Insight:** Loja 3 possui a melhor média de avaliações, enquanto Loja 4 tem uma das piores, indicando problemas de satisfação do cliente.


### 5. Frete Médio e Proporção no Faturamento

- **Gráfico de barras:** Mostra o frete médio por loja e sua proporção em relação ao faturamento.
- **Insight:** Lojas com frete proporcionalmente alto podem ter margens reduzidas e desafios logísticos.

---

## Instruções para Executar o Notebook

Siga os passos abaixo para reproduzir a análise no Google Colab ou ambiente Jupyter:

1. **Abra o notebook:**
    - Faça upload do arquivo `AluraStoreBr.ipynb` para o Google Colab ou Jupyter Notebook.
2. **Carregue os dados:**
    - Faça upload dos arquivos `loja_1.csv`, `loja_2.csv`, `loja_3.csv`, `loja_4.csv` no mesmo ambiente.
3. **Instale as dependências (caso necessário):**

```python
!pip install pandas matplotlib seaborn plotly
```

4. **Execute as células sequencialmente:**
    - Siga a ordem das células para garantir que todas as etapas do pipeline sejam realizadas corretamente.
    - As visualizações interativas serão exibidas ao longo da execução.
5. **Personalize a análise:**
    - Modifique parâmetros das funções conforme necessário (ex: colunas analisadas, limites de outliers).
    - Explore visualizações segmentadas por loja, categoria ou período.

**Pré-requisitos:**

- Conexão com a internet para uso do Google Colab.
- Não é necessário conhecimento avançado em Python, pois o notebook é autoexplicativo e modular.

---

## Conclusão

O notebook oferece uma análise robusta, visual e interativa do desempenho das lojas do Senhor João. Com base nos dados, a recomendação é vender a Loja 4, que apresenta baixo faturamento, menor diversificação e satisfação do cliente inferior. Todos os passos, gráficos e insights podem ser reproduzidos e adaptados conforme a necessidade do negócio.
