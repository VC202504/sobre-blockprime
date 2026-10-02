# BlockPrime

Indicador próprio para TradingView e robô de execução automática. O indicador classifica cada sinal por qualidade; o robô só opera o que passa no filtro e cuida do risco sozinho.

**Site:** [blockprime.app](https://blockprime.app)  
**Situação:** Em testes, conta demo

## O que faz

- Indicador em Pine Script v6, com código original
- Leitura de estrutura de mercado (Smart Money Concepts), fluxo de ordens, zonas de liquidez, FVG e order blocks
- Dois níveis de sinal: seletivo, com percentual de confiança, e rápido, com nota de qualidade de 0 a 100
- Sinal enviado por webhook para uma fila, de onde o robô executa no MetaTrader 5
- Gestão de risco em camadas: risco fixo por operação, limite de posições abertas, trava de perda diária e trailing stop
- Relatórios de desempenho por ativo e por faixa de qualidade, usados para decidir o que o robô opera

## Tecnologia

Pine Script v6, Supabase (Edge Functions e PostgreSQL), Python, MetaTrader 5

## Sobre este repositório

Este repositório é a página de apresentação do produto. O código-fonte é proprietário e fica em repositório privado.

Desenvolvido por [Kenyo Veloso Chianca](https://github.com/VC202504), engenheiro civil, pela The Bridge Brasil Ltda.
