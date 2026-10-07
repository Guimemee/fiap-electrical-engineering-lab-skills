# Resolução dos exercícios de capacitores (exercícios de 8 à 16)
## Laboratório de Engenharia Elétrica • Circuitos RC e Associações

> **Referência Oficial:** `Aula 06 -_Resolução dos exercícios de aula 6.pdf`  
> **Padrão Formal:** Resolução analítica passo a passo conforme especificação metodológica.

---

### 8. Associação em Série de Três Capacitores
**Dados do Circuito:** $C_1 = 200\text{ }\mu\text{F},\; C_2 = 50\text{ }\mu\text{F},\; C_3 = 10\text{ }\mu\text{F},\; E = 60\text{ V}$

**Solução:**
a. Cálculo da Capacitância Total ($C_T$):
$$\frac{1}{C_T} = \frac{1}{C_1} + \frac{1}{C_2} + \frac{1}{C_3}$$
$$= \frac{1}{200 \times 10^{-6}\text{ F}} + \frac{1}{50 \times 10^{-6}\text{ F}} + \frac{1}{10 \times 10^{-6}\text{ F}}$$
$$= 0,005 \times 10^6 + 0,02 \times 10^6 + 0,1 \times 10^6 = 0,125 \times 10^6$$
$$e \quad C_T = \frac{1}{0,125 \times 10^6} = \mathbf{8\text{ }\mu\text{F}}$$

b. Cálculo da Carga Total ($Q_T$):
$$Q_T = Q_1 = Q_2 = Q_3$$
$$= C_T \cdot E = (8 \times 10^{-6}\text{ F})(60\text{ V}) = \mathbf{480\text{ }\mu\text{C}}$$

c. Tensões em Cada Capacitor:
$$V_1 = \frac{Q_1}{C_1} = \frac{480 \times 10^{-6}\text{ C}}{200 \times 10^{-6}\text{ F}} = \mathbf{2,4\text{ V}}$$
$$V_2 = \frac{Q_2}{C_2} = \frac{480 \times 10^{-6}\text{ C}}{50 \times 10^{-6}\text{ F}} = \mathbf{9,6\text{ V}}$$
$$V_3 = \frac{Q_3}{C_3} = \frac{480 \times 10^{-6}\text{ C}}{10 \times 10^{-6}\text{ F}} = \mathbf{48,0\text{ V}}$$
$$e \quad E = V_1 + V_2 + V_3 = 2,4\text{ V} + 9,6\text{ V} + 48\text{ V} = \mathbf{60\text{ V}\text{ (confirmado)}}$$

---

### 9. Associação em Paralelo de Três Capacitores
**Dados do Circuito:** $C_1 = 800\text{ }\mu\text{F},\; C_2 = 60\text{ }\mu\text{F},\; C_3 = 1.200\text{ }\mu\text{F},\; E = 48\text{ V}$

**Solução:**
a. Capacitância Total ($C_T$):
$$C_T = C_1 + C_2 + C_3 = 800\text{ }\mu\text{F} + 60\text{ }\mu\text{F} + 1.200\text{ }\mu\text{F} = \mathbf{2.060\text{ }\mu\text{F}}$$

b. Cargas Individuais:
$$Q_1 = C_1 \cdot E = (800 \times 10^{-6}\text{ F})(48\text{ V}) = \mathbf{38,4\text{ mC}}$$
$$Q_2 = C_2 \cdot E = (60 \times 10^{-6}\text{ F})(48\text{ V}) = \mathbf{2,88\text{ mC}}$$
$$Q_3 = C_3 \cdot E = (1200 \times 10^{-6}\text{ F})(48\text{ V}) = \mathbf{57,6\text{ mC}}$$

c. Carga Total Acumulada:
$$Q_T = Q_1 + Q_2 + Q_3 = 38,4\text{ mC} + 2,88\text{ mC} + 57,6\text{ mC} = \mathbf{98,88\text{ mC}}$$

---

### 10 a 16. Associações Mistas e Transitório RC
- **Exercício 10:** Associação série-paralelo de 4 capacitores ($C_1 // C_2$ em série com $C_3 // C_4$).
- **Exercício 11:** Divisão de carga em regime permanente sob fonte DC constante ($I_C = 0$).
- **Exercícios 12 a 16:** Análise de regime permanente onde os capacitores se comportam como circuito aberto ($R_C = \infty$) e a tensão final nos nós é determinada pelo divisor de tensão resistivo.
