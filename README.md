# 📊 Projeto Quantitativo: Seleção e Rebalanceamento de Carteiras com Reinvestimento de Proventos

Este projeto tem como objetivo a construção de uma estratégia quantitativa baseada em dados do mercado financeiro brasileiro, utilizando métodos analíticos e estatísticos aplicados a ativos do índice Ibovespa.

---

## 🔧 Etapas do Projeto

1. **Web scraping** para identificação de ativos com boa liquidez listados no índice **Ibovespa**.  
2. Coleta histórica das **cotações diárias** dos ativos selecionados.  
3. Análise comparativa entre **risco e retorno**, com a construção de um **indicador quantitativo de desempenho**.  
4. **Seleção dos melhores ativos** com base no indicador desenvolvido.  
5. Aplicação da metodologia de **análise com janela deslizante (Walk-Forward Analysis - WFA)** para testar a performance da estratégia em períodos subsequentes.  
6. Desenvolvimento de uma função para **coleta de proventos** (dividendos e juros sobre capital próprio) com **reinvestimento proporcional** ao longo do tempo.  
7. **Rebalanceamento da carteira** com base em regras pré-definidas e análise de **séries temporais** para avaliação de comportamento ao longo do tempo.  
8. Avaliação das **estatísticas de performance** da carteira: Sharpe Ratio, Drawdown, Volatilidade, Retorno Acumulado, etc.  
9. **Geração de relatório analítico** e comparativo com benchmarks em formato PDF.

---

## 🧠 Tecnologias e Ferramentas

- **Python** (Pandas, NumPy, Scikit-learn, yfinance, matplotlib, seaborn)
- **Web Scraping:** requests, BeautifulSoup
- **Análise Quantitativa:** Pyfolio, Backtesting.py
- **Relatórios:** Matplotlib, ReportLab, PDF generation
- **Visualização:** Plotly, Seaborn

---

## 📎 Objetivo Final

Criar uma estratégia replicável de seleção e alocação de ativos baseada em fundamentos quantitativos, com reinvestimento de proventos e rebalanceamento sistemático, resultando em um **relatório final comparativo com benchmarks como o Ibovespa**.
