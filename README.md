# 📈 Simulador de Acumulação de Patrimônio em Excel

__Descrição__: Ferramenta desenvolvida para projetar o crescimento de capital ao longo do tempo, utilizando a lógica de juros compostos e aporte sistemáticos.

---------------------

### 🚀 Visão Geral
Esta ferramenta foi criada para auxiliar no planejamento financeiro de longo prazo. Diferente de uma planilha de gastos comum, ela foca na __projeção de futuro__, permitindo que o usuário visualize o impacto da taxa de juros e da consistência dos aportes no montante final acumulado.

### ✨ Principais Funcionalidades
* __Projeção de Juros Compostos__: Cálculo automático do crescimento de capital mês a mês.
* __Simulação de Aportes__: Campo dedicado para inserção de aportes mensais constantes, demonstrando o efeito da disciplina financeira.
* __Diferenciação de Capital__: Visualização clara entre o __Capital Investido__ (do bolso do usuário) vs. __Juros Ganhos__ (efeito do tempo).
* __Interface de Simulação__: Painel configurável para alterar Taxa de Juros, Período (meses/anos) e Valor Inicial.

### 🛠️ Detalhes Técnicos (Fórmulas e Lógica)
A planilha utiliza a estrutura de progressão financeira. A principal lógica aplicada em cada linha da tabela de projeção é:

__M = P . ( 1 + i )^n__

Onde:
* __M__: Montante final.
* __P__: Principal (aporte inicial + acumulado).
* __i__: Taxa de juros por período.
* __n__: Número de período.

__Recursos utilizados__:
* __Referências Absolutas ($)__: Para manter as taxas de juros fixas ao arrastar as fórmulas.
* __Formatação Condicional__: Para destacar metas atingidas ou valores de rendimento.
* __Gráfico Pizza__: Para mostrar a distribuição do investimento.

### 📋 Como utilizar
1. __Configuração__: Na aba principal, insira o seu __Aporte Inicial__.
2. __Parâmetros__: Defina a __Taxa de Juros Mensal__ esperada e o __Aporte Mensal__.
3. __Análise__: Verifique na tabela abaixo o crescimento do patrimônio e o momento em que os "Juros Mensais" ultrapassam o valor do seu "Aporte", o famoso ponto de liberdade financeira.

### 📐 Estrutura das Abas
* __Planilha1 / Simulação__: Contém os campos de entrada e a tabela progressiva de meses/anos.
* __Planilha3 / Auxiliar__: Contém dados de suporte ou cálculos intermediários para os gráficos.

Desenvolvido por: Giliano Gomes Novais
Projeto: Ferramentas de Gestão Financeira em Excel.
