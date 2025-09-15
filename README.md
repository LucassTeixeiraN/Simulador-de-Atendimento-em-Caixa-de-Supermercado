# **📊 Resultados e Análise**

A simulação foi executada para cenários com 1 a 5 caixas. Os parâmetros base foram:

+ **Número de Clientes:** 100
+ **Tempo Médio por Cliente:** 5,0 minutos
+ **Desvio-Padrão do Atendimento:** 0,5 minutos

### **Tabela de Resultados**
|Número de Caixas| Médio Total (minutos)|Desvio-Padrão (minutos)|
|---|---|---|
|1|500.20|5.01|
|2|	250.10|	3.55|
|3|	166.73|	2.87|
|4|	125.05|	2.50|
|5|	100.04|	2.24|

### **Conclusões Principais**
**1. Impacto Exponencial:** Aumentar o número de caixas tem um impacto direto e significativo na redução do tempo total de atendimento. Dobrar o número de caixas de 1 para 2 reduz o tempo total pela metade.

**2. Lei dos Rendimentos Decrescentes:** O ganho de eficiência é maior no início. Adicionar o segundo caixa economizou ~250 minutos, enquanto adicionar o quinto caixa economizou apenas ~25 minutos. Isso sugere que existe um ponto de equilíbrio ideal entre o custo de um novo caixa e o benefício no tempo de atendimento.

**3. Maior Previsibilidade:** Com mais caixas, o desvio-padrão diminui. Isso indica que a operação se torna mais estável e previsível, com menos variações drásticas no tempo necessário para atender todos os clientes.
