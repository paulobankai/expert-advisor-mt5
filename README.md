# Expert Advisor MQL5 - XAUUSD (Gold)

Robô algorítmico desenvolvido em **MQL5** para execução automatizada de ordens no par **XAUUSD (Ouro)** no MetaTrader 5. Conta com gestão de risco quantitativa e dimensionamento dinâmico de lote baseado em volatilidade e drawdown máximo.

---

## 🏗️ Arquitetura do Sistema

| Módulo | Descrição | Componentes / Indicadores |
| :--- | :--- | :--- |
| **Modo Automático** | Operações baseadas em tendência e rompimentos | Média Móvel Exponencial (EMA), RSI, ATR |
| **Modo Manual / Híbrido** | Confirmação de entrada e gestão de ordens manuais | Filtros de Spread e Slippage |
| **CHOP Index** | Identificação de mercado lateralizado / consolidação | Choppiness Index (Período 14) |
| **Gestão de Risco** | Dimensionamento dinâmico de lote por risco percentual | Stop Loss Dinâmico, Take Profit Múltiplo, Trailing Stop |

---

## 📊 Resultados de Backtest (XAUUSD)

Os testes foram realizados utilizando dados históricos de alta precisão (tick a tick) no MetaTrader 5 para o ativo **XAUUSD**.

- **Lucro Líquido Total:** $12,450.00 USD
- **Fator de Lucro (Profit Factor):** 1.85
- **Drawdown Máximo:** 4.2%
- **Taxa de Acerto (Win Rate):** 68.4%

Veja o gráfico de desempenho em `backtest/chart_xauusd.png` e a planilha detalhada em `backtest/backtest_results.xlsx`.

---

## ⚙️ Instalação e Configuração

1. Abra o **MetaTrader 5**.
2. Vá em **Arquivo > Abrir Pasta de Dados**.
3. Navegue até `MQL5 > Experts`.
4. Copie o arquivo do Expert Advisor para esta pasta.
5. Compile o código no MetaEditor (`F7`).
6. Anexe ao gráfico de **XAUUSD (M15 ou H1)** habilitando o AutoTrading.

---

## 📄 Licenciamento

Projeto proprietário desenvolvido para operações quantitativas em mercados globais.
