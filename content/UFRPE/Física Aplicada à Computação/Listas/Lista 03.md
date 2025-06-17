• Capítulo 25
– 15
– 16
– 21
• Capítulo 26
– 24
– 42
– 50
• Capítulo 27
– 2
– 22
– 29
– 31

## (Cap 25) Questão 15

#### Dados:
- $C_1 = C_6 = 3{,}00 \, \mu\text{F}$
- $C_2 = 2{,}00 \, \mu\text{F}$
- $C_3 = C_5 = 2{,}00 \, \mu\text{F}$
- $C_4 = 4{,}00 \, \mu\text{F}$
- $V = 20{,}0 \, \text{V}$

#### (a) Capacitância equivalente $C_{\text{eq}}$

1. Capacitores $C_4$ e $C_5$ em série:
$$
\frac{1}{C_{45}} = \frac{1}{4{,}00} + \frac{1}{2{,}00} = \frac{3}{4} \Rightarrow C_{45} = \frac{4}{3} \, \mu\text{F}
$$

2. $C_{45}$ em paralelo com $C_3$ e $C_2$:
$$
C_{centro} = 2{,}00 + \frac{4}{3} + 2{,}00 = 6{,}00 \, \mu\text{F}
$$

3. $C_{centro}$ em série com $C_1 \parallel C_6$:
$$
C' = C_1 + C_6 = 3{,}00 + 3{,}00 = 6{,}00 \, \mu\text{F}
$$
$$
C_{\text{eq}} = \frac{6{,}00 \cdot 6{,}00}{6{,}00 + 6{,}00} = \frac{36}{12} = 3{,}00 \, \mu\text{F}
$$

#### (b) Carga total armazenada
$$
q = C_{\text{eq}} \cdot V = 3{,}00 \cdot 10^{-6} \cdot 20{,}0 = 6{,}00 \cdot 10^{-5} \, \text{C}
$$

#### (c) Diferença de potencial em $C_1$
Como $C_1$ e $C_6$ estão em paralelo, ambos recebem a mesma tensão:
$$
V_1 = \frac{6{,}00}{6{,}00 + 6{,}00} \cdot 20{,}0 = 10{,}0 \, \text{V}
$$

#### (d) Carga em $C_1$
$$
q_1 = C_1 \cdot V_1 = 3{,}00 \cdot 10^{-6} \cdot 10{,}0 = 3{,}00 \cdot 10^{-5} \, \text{C}
$$

#### (e) Diferença de potencial em $C_2$
$$
V_2 = V - V_1 = 20{,}0 - 10{,}0 = 10{,}0 \, \text{V}
$$

#### (f) Carga em $C_2$
$$
q_2 = C_2 \cdot V_2 = 2{,}00 \cdot 10^{-6} \cdot 10{,}0 = 2{,}00 \cdot 10^{-5} \, \text{C}
$$

#### (g) Diferença de potencial em $C_3$

$C_3$ e $C_{45}$ estão em série e compartilham $V_2 = 10{,}0 \, \text{V}$

Como $C_3 = 2{,}00 \, \mu\text{F}$ e $C_{45} = 4{,}00 \, \mu\text{F}$, usamos divisão de tensão:
$$
V_3 = \frac{C_{45}}{C_3 + C_{45}} \cdot V_2 = \frac{4{,}00}{6{,}00} \cdot 10{,}0 = \frac{2}{3} \cdot 10{,}0 = 6{,}67 \, \text{V}
$$

#### (h) Carga em $C_3$
$$
q_3 = C_3 \cdot V_3 = 2{,}00 \cdot 10^{-6} \cdot 6{,}67 \approx 1{,}33 \cdot 10^{-5} \, \text{C}
$$

---

## (Cap 25) Questão 16

**Passo 1: Determinação das capacitâncias a partir dos gráficos**

A relação entre carga e tensão em um capacitor é dada por:

$$
q = C \cdot V
$$

Portanto, a inclinação da reta nos gráficos $q \times V$ representa a capacitância.

Sabemos que:
- O gráfico usa como escala vertical $q_s = 16{,}0\ \mu C$,
- E como escala horizontal $V_s = 2{,}0\ V$.

Do gráfico:
- A reta 1 atinge $12\ \mu C$ quando $V = 2{,}0\ V$, logo:

$$
C_1 = \frac{q}{V} = \frac{12\ \mu C}{2{,}0\ V} = 6{,}0\ \mu F
$$

- A reta 2 atinge $8\ \mu C$ a $2{,}0\ V$:

$$
C_2 = \frac{8\ \mu C}{2{,}0\ V} = 4{,}0\ \mu F
$$

- A reta 3 atinge $4\ \mu C$ a $2{,}0\ V$:

$$
C_3 = \frac{4\ \mu C}{2{,}0\ V} = 2{,}0\ \mu F
$$

**Passo 2: Determinar a capacitância equivalente do circuito**

Pelo circuito, o capacitor $C_1$ está em série com o conjunto $C_2$ e $C_3$, que estão em paralelo. Primeiro somamos os capacitores em paralelo:

$$
C_{23} = C_2 + C_3 = 4{,}0\ \mu F + 2{,}0\ \mu F = 6{,}0\ \mu F
$$

Agora, como $C_1$ está em série com $C_{23}$, a capacitância equivalente total $C_{\text{eq}}$ do circuito é dada por:

$$
\frac{1}{C_{\text{eq}}} = \frac{1}{C_1} + \frac{1}{C_{23}} = \frac{1}{6{,}0\ \mu F} + \frac{1}{6{,}0\ \mu F} = \frac{2}{6} = \frac{1}{3}
$$

$$
C_{\text{eq}} = 3{,}0\ \mu F
$$

**Passo 3: Carga total fornecida pela bateria**

Como a bateria fornece $V = 6{,}0\ V$, a carga total armazenada pelo circuito é:

$$
q_{\text{total}} = C_{\text{eq}} \cdot V = 3{,}0\ \mu F \cdot 6{,}0\ V = 18\ \mu C
$$

Essa carga é a mesma que passa pelo capacitor $C_1$, pois ele está em série com o restante do circuito:

$$
q_1 = 18\ \mu C
$$

**Passo 4: Determinar a tensão sobre $C_1$**

$$
V_1 = \frac{q_1}{C_1} = \frac{18\ \mu C}{6{,}0\ \mu F} = 3{,}0\ V
$$

**Passo 5: Determinar a tensão sobre o ramo paralelo ($C_2$ e $C_3$)**

A diferença de potencial da bateria é de $6{,}0\ V$, e $C_1$ "gasta" $3{,}0\ V$, então resta:

$$
V_{23} = 6{,}0\ V - 3{,}0\ V = 3{,}0\ V
$$

Como $C_2$ e $C_3$ estão em paralelo, ambos estão submetidos a essa mesma tensão.

**Passo 6: Determinar a carga sobre o capacitor 2**

$$
q_2 = C_2 \cdot V_{23} = 4{,}0\ \mu F \cdot 3{,}0\ V = 12\ \mu C
$$

****Resposta Final:****

A carga no capacitor 2 é:

$$
\boxed{q_2 = 12\ \mu C}
$$

---

## (Cap 25) Questão 21

**Dados:**
- $C_1 = 1{,}0 \, \mu\text{F}$
- $C_2 = 3{,}0 \, \mu\text{F}$
- $V = 100 \, \text{V}$ (polos opostos)
- Após o fechamento das chaves $S_1$ e $S_2$, os capacitores ficam em paralelo

**(a) Nova diferença de potencial entre os pontos $a$ e $b$**

**Passo 1: Cargas iniciais**

$$
q_1 = C_1 \cdot V = 1{,}0 \cdot 10^{-6} \cdot 100 = 1{,}0 \cdot 10^{-4} \, \text{C}
$$
$$
q_2 = C_2 \cdot V = 3{,}0 \cdot 10^{-6} \cdot 100 = 3{,}0 \cdot 10^{-4} \, \text{C}
$$

**Passo 2: Cargas com polaridades opostas**

Como os capacitores foram carregados com polaridades opostas:

$$
Q_{\text{total}} = q_2 - q_1 = 3{,}0 \cdot 10^{-4} - 1{,}0 \cdot 10^{-4} = 2{,}0 \cdot 10^{-4} \, \text{C}
$$

**Passo 3: Capacitância equivalente**

$$
C_{\text{eq}} = C_1 + C_2 = 1{,}0 + 3{,}0 = 4{,}0 \, \mu\text{F} = 4{,}0 \cdot 10^{-6} \, \text{F}
$$

**Passo 4: Nova diferença de potencial**

$$
V_{ab} = \frac{Q_{\text{total}}}{C_{\text{eq}}} = \frac{2{,}0 \cdot 10^{-4}}{4{,}0 \cdot 10^{-6}} = 50 \, \text{V}
$$

**(b) Nova carga em $C_1$**

$$
q'_1 = C_1 \cdot V_{ab} = 1{,}0 \cdot 10^{-6} \cdot 50 = 5{,}0 \cdot 10^{-5} \, \text{C}
$$

**(c) Nova carga em $C_2$**

$$
q'_2 = C_2 \cdot V_{ab} = 3{,}0 \cdot 10^{-6} \cdot 50 = 1{,}5 \cdot 10^{-4} \, \text{C}
$$

**Respostas Finais:**
- **(a)** $V_{ab} = \boxed{50 \, \text{V}}$
- **(b)** $q_1' = \boxed{5{,}0 \cdot 10^{-5} \, \text{C}}$
- **(c)** $q_2' = \boxed{1{,}5 \cdot 10^{-4} \, \text{C}}$

---

## (Cap 26) Questão 24

Dados:
- Comprimento total: $L = 9{,}0 \, \text{mm}$
- Raio da seção 3: $r_3 = 2{,}00 \, \text{mm}$
- Gráfico indica intensidades de campo elétrico:
  - Seção 1: $E_1 = 2{,}5 \cdot 10^3 \, \text{V/m}$
  - Seção 2: $E_2 = 4{,}0 \cdot 10^3 \, \text{V/m}$
  - Seção 3: $E_3 = 1{,}5 \cdot 10^3 \, \text{V/m}$

**Conceito físico:**

Como o material é o mesmo, a resistividade $\rho$ é constante. Pela equação:

$$
E = \rho J \Rightarrow J \propto E
$$

Onde $J$ é a densidade de corrente.

Como a barra está em série, a corrente total $I$ é a mesma em todas as seções. Assim:

$$
I = J_1 A_1 = J_2 A_2 = J_3 A_3
$$

Logo, usando $J \propto E$ e $A = \pi r^2$, podemos escrever:

$$
E_1 \cdot \pi r_1^2 = E_3 \cdot \pi r_3^2
\Rightarrow E_1 r_1^2 = E_3 r_3^2
$$

**(a) Determinar o raio $r_1$:**

$$
E_1 r_1^2 = E_3 r_3^2
\Rightarrow 2{,}5 \cdot r_1^2 = 1{,}5 \cdot (2{,}0)^2 = 6{,}0
\Rightarrow r_1^2 = \frac{6{,}0}{2{,}5} = 2{,}4
\Rightarrow r_1 = \sqrt{2{,}4} \approx 1{,}55 \, \text{mm}
$$

**(b) Determinar o raio $r_2$:**

$$
E_2 r_2^2 = E_3 r_3^2
\Rightarrow 4{,}0 \cdot r_2^2 = 1{,}5 \cdot (2{,}0)^2 = 6{,}0
\Rightarrow r_2^2 = \frac{6{,}0}{4{,}0} = 1{,}5
\Rightarrow r_2 = \sqrt{1{,}5} \approx 1{,}22 \, \text{mm}
$$

Respostas Finais:
- **(a)** $r_1 = \boxed{1{,}55 \, \text{mm}}$
- **(b)** $r_2 = \boxed{1{,}22 \, \text{mm}}$

--- 

## (Cap 26) Questão 42

**Dados:**
- $V = 12 \, \text{V}$
- $R = 6{,}0 \, \Omega$
- Carga do elétron: $e = 1{,}60 \times 10^{-19} \, \text{C}$

**(a) Sentido do movimento do elétron**

O campo elétrico no fio aponta do terminal positivo para o terminal negativo da bateria, ou seja, no **sentido da corrente convencional**.

Como o elétron possui carga negativa, ele se move **no sentido oposto ao do campo elétrico**.

**Resposta**: O elétron se move no sentido **do terminal negativo para o terminal positivo**, ou seja, **contra o campo elétrico**.

**(b) Trabalho realizado pelo campo elétrico sobre o elétron**

O trabalho realizado pelo campo é dado por:

$$
W = q \cdot V
$$

Como estamos interessados no **valor absoluto** do trabalho:

$$
W = e \cdot V = (1{,}60 \times 10^{-19}) \cdot (12) = 1{,}92 \times 10^{-18} \, \text{J}
$$

**Resposta**: $W = \boxed{1{,}92 \times 10^{-18} \, \text{J}}$ ou $\boxed{12 \, \text{eV}}$

**(c) Energia transformada em energia térmica**

Como o elétron não ganha energia cinética média no processo (movimento em regime estacionário), todo o trabalho realizado é dissipado como **calor no fio**.

**Resposta**: $\boxed{1{,}92 \times 10^{-18} \, \text{J}}$ ou $\boxed{12 \, \text{eV}}$

---

## (Cap 26) Questão 50

**Dados:**
- Corrente: $I = 2{,}00 \, \text{A}$
- Escala vertical: $E_{t,s} = 40{,}0 \, \text{mJ}$
- Escala horizontal: $t_s = 5{,}00 \, \text{s}$

O gráfico fornece energia térmica $E_t$ dissipada por cada resistor ao longo do tempo. Como a potência dissipada é a **inclinação da curva** $P = \frac{E_t}{t}$, podemos determinar a potência em cada resistor pela razão entre a altura (em mJ) e a base (em s).

**(1) Potência dissipada em cada resistor**

- **Resistor 1 (curva 1)**: linha tracejada atinge o topo $E_t = 40{,}0 \, \text{mJ}$ em $t = 5{,}00 \, \text{s}$
  $$
  P_1 = \frac{40{,}0 \, \text{mJ}}{5{,}00 \, \text{s}} = 8{,}00 \, \text{mW}
  $$

- **Resistor 2 (curva 2)**: linha cheia atinge metade da escala ($20{,}0 \, \text{mJ}$) em 5 s
  $$
  P_2 = \frac{20{,}0 \, \text{mJ}}{5{,}00 \, \text{s}} = 4{,}00 \, \text{mW}
  $$

**(2) Potência total fornecida pela bateria**

$$
P_{\text{bateria}} = P_1 + P_2 = 8{,}00 + 4{,}00 = 12{,}00 \, \text{mW}
$$

**Resposta Final:**
$$
\boxed{P_{\text{bateria}} = 12{,}0 \, \text{mW}}
$$

---

## (Cap 27) Questão 2

**Dados fornecidos:**

- $\mathcal{E}_1 = 150\ \text{V}$ (orientada para cima)
- $\mathcal{E}_2 = 50\ \text{V}$ (orientada para baixo)
- $R_1 = 3{,}0\ \Omega$
- $R_2 = 2{,}0\ \Omega$
- $V_P = 100\ \text{V}$

**Passo 1: Determinar a corrente no circuito**

Vamos aplicar a Lei das Malhas para calcular a corrente que percorre o circuito fechado.

Assumindo o sentido da corrente no sentido horário (de $Q \rightarrow R_1 \rightarrow P \rightarrow R_2 \rightarrow Q$), temos:

$$
\mathcal{E}_1 - \mathcal{E}_2 = i(R_1 + R_2)
$$

Substituindo os valores:

$$
150\ \text{V} - 50\ \text{V} = i(3{,}0\ \Omega + 2{,}0\ \Omega)
\Rightarrow 100\ \text{V} = i(5{,}0\ \Omega)
\Rightarrow i = \frac{100\ \text{V}}{5{,}0\ \Omega} = 20\ \text{A}
$$

**Passo 2: Aplicar a Lei das Tensões para encontrar $V_Q$**

Percorremos o circuito no sentido de $Q \rightarrow R_1 \rightarrow P \rightarrow R_2 \rightarrow \mathcal{E}_1 \rightarrow Q$, e aplicamos a Lei das Malhas:

$$
V_Q + \mathcal{E}_1 - i R_2 = V_P
$$

Substituindo os valores numéricos:

$$
V_Q + 150\ \text{V} - (20\ \text{A})(2{,}0\ \Omega) = 100\ \text{V}
\Rightarrow V_Q + 150\ \text{V} - 40\ \text{V} = 100\ \text{V}
\Rightarrow V_Q + 110\ \text{V} = 100\ \text{V}
\Rightarrow V_Q = 100\ \text{V} - 110\ \text{V} = -10\ \text{V}
$$

****Resposta Final:****

$$
\boxed{V_Q = -10\ \text{V}}
$$


---

## (Cap 27) Questão 22

**Dados:**
- Todos os resistores têm $R = 5{,}0 \, \Omega$

**(a) Resistência equivalente entre os pontos $F$ e $H$**

Analisando o circuito:

- Há duas malhas simétricas com três resistores:
  - Caminho superior: dois resistores em série de $5{,}0 \, \Omega$: total de $10{,}0 \, \Omega$
  - Caminho inferior: também $10{,}0 \, \Omega$
- Entre os dois caminhos está um resistor central de $5{,}0 \, \Omega$ ligado entre os nós intermediários.

As duas malhas estão em paralelo, ligadas pelo resistor do meio. Aplicamos a fórmula de resistência equivalente para esse tipo de associação:

$$
R_{\text{eq}} = \frac{(10{,}0)(10{,}0)(5{,}0)}{(10{,}0)(10{,}0) + 2(10{,}0)(5{,}0)} 
= \frac{500}{100 + 100} = \frac{500}{200} = 2{,}50 \, \Omega
$$

**Resposta (a)**: $\boxed{2{,}50 \, \Omega}$

**(b) Resistência equivalente entre os pontos $F$ e $G$**

Agora, queremos a resistência entre $F$ e o ponto inferior $G$.

**Passo 1: Parte do circuito (superior) vira um conjunto equivalente:**

Os resistores de cima e o central (do meio) formam uma malha em série e paralelo:

- Dois em série: $5{,}0 + 5{,}0 = 10{,}0 \, \Omega$
- Este resultado está em paralelo com o resistor do meio:

$$
R = \frac{(5{,}0)(10{,}0)}{5{,}0 + 10{,}0} = \frac{50}{15} = 3{,}33 \, \Omega
$$

**Passo 2: Esse resultado está em série com o resistor inferior da perna direita ($R = 5{,}0 \, \Omega$):**

$$
R_{\text{eq}}(FG) = \frac{(5{,}0)(8{,}33)}{5{,}0 + 8{,}33}
= \frac{41{,}65}{13{,}33} \approx 3{,}13 \, \Omega
$$

**Resposta (b)**: $\boxed{3{,}13 \, \Omega}$

---

## (Cap 27) Questão 29

**Dados:**
- $R_1 = 6{,}0 \, \Omega$
- $R_2 = 18{,}0 \, \Omega$
- $\mathcal{E} = 12{,}0 \, \text{V}$
- Tempo: $t = 1{,}00 \, \text{min} = 60 \, \text{s}$

**(a) Valor absoluto da corrente $i_1$**

Os três resistores $R_2 = 18{,}0 \, \Omega$ estão em paralelo:

$$
\frac{1}{R_{\text{eq,paralelo}}} = \frac{1}{18} + \frac{1}{18} + \frac{1}{18} = \frac{3}{18} \Rightarrow R_{\text{eq}} = 6{,}0 \, \Omega
$$

Esse conjunto está em **série** com $R_1 = 6{,}0 \, \Omega$:

$$
R_{\text{total}} = R_1 + R_{\text{eq}} = 6{,}0 + 6{,}0 = 12{,}0 \, \Omega
$$

Corrente total no circuito:

$$
I = \frac{\mathcal{E}}{R_{\text{total}}} = \frac{12{,}0}{12{,}0} = 1{,}00 \, \text{A}
$$

Como os resistores $R_2$ são idênticos e estão em paralelo, a corrente se divide igualmente:

$$
i_1 = \frac{1{,}00}{3} = 0{,}333 \, \text{A}
$$

**Resposta (a)**: $\boxed{0{,}333 \, \text{A}}$

**(b) Sentido da corrente $i_1$**

A corrente flui do terminal positivo da bateria, atravessa $R_1$, e depois entra nos três $R_2$ em paralelo. Portanto:

**Resposta (b)**: A corrente $i_1$ flui **da esquerda para a direita**.

**(c) Energia dissipada em 1,00 min**

Potência dissipada:

$$
P = I^2 R = (1{,}00)^2 \cdot 12 = 12 \, \text{W}
$$

Energia total dissipada em $60 \, \text{s}$:

$$
E = P \cdot t = 12 \cdot 60 = 720 \, \text{J}
$$

**Resposta (c)**: $\boxed{720 \, \text{J}}$

---

## (Cap 27) Questão 31

**Dados:**

- $\mathcal{E}_1 = 5{,}0\ \text{V}$
- $\mathcal{E}_2 = 12{,}0\ \text{V}$
- Todas as resistências $R = 2{,}0\ \Omega$
- O potencial no ponto ligado ao solo (terra) é $0\ \text{V}$

**Objetivo:**
Determinar os potenciais:
- $V_1$: no ponto ao lado da bateria de 12 V
- $V_2$: no ponto ao lado da bateria de 5 V

**Passo 1: Simplificar o circuito**

Observando o circuito, temos três conjuntos de resistores:

1. Dois resistores de $2{,}0\ \Omega$ em paralelo no lado direito (perto de $V_1$):
   $$
   R' = \frac{1}{\frac{1}{2} + \frac{1}{2}} = 1{,}0\ \Omega
   $$

2. Dois resistores de $2{,}0\ \Omega$ em série no lado superior esquerdo:
   $$
   R'' = 2{,}0\ \Omega + 2{,}0\ \Omega = 4{,}0\ \Omega
   $$

3. Um resistor único de $2{,}0\ \Omega$ entre os pontos $V_1$ e $V_2$, na base do circuito.

Agora temos três resistores em série:

$$
R_{\text{eq}} = R + R' + R'' = 2{,}0\ \Omega + 1{,}0\ \Omega + 4{,}0\ \Omega = 7{,}0\ \Omega
$$

**Passo 2: Determinar a corrente no circuito**

As duas baterias estão em oposição (uma sobe 12 V, a outra desce 5 V). A diferença total de potencial fornecida ao circuito é:

$$
\Delta V = \mathcal{E}_2 - \mathcal{E}_1 = 12\ \text{V} - 5\ \text{V} = 7{,}0\ \text{V}
$$

$$
i = \frac{\Delta V}{R_{\text{eq}}} = \frac{7{,}0\ \text{V}}{7{,}0\ \Omega} = 1{,}0\ \text{A}
$$

**Passo 3: Determinar $V_1$**

Vamos analisar o ramo da direita, onde está $V_1$:

- A corrente de $1{,}0\ \text{A}$ passa por $R' = 1{,}0\ \Omega$, gerando uma queda de tensão:
  $$
  V_{R'} = i \cdot R' = 1{,}0\ \text{A} \cdot 1{,}0\ \Omega = 1{,}0\ \text{V}
  $$

- A bateria de 12 V eleva o potencial, e logo após vem a queda de 1 V no resistor.

Como a referência de 0 V está no topo (terra), o potencial em $V_1$ será:

$$
V_1 = 0\ \text{V} - 12\ \text{V} - 1{,}0\ \text{V} = -13\ \text{V}
$$

(Nota: A convenção pode variar conforme a escolha do caminho; em muitos casos a referência da bateria pode ser considerada a diferença entre os extremos do conjunto. Adotando o lado direito como base de referência da bateria, temos:)

Na verdade, o potencial no ponto $V_1$ é:

$$
V_1 = -12\ \text{V} + 1\ \text{V} = -11\ \text{V}
$$

**Passo 4: Determinar $V_2$**

Analisando o lado esquerdo:

- A corrente de $1{,}0\ \text{A}$ passa por $R'' = 4{,}0\ \Omega$, gerando uma queda de:
  $$
  V_{R''} = 1{,}0\ \text{A} \cdot 4{,}0\ \Omega = 4{,}0\ \text{V}
  $$

- A bateria de 5 V aumenta o potencial.

Partindo do terra (0 V), subimos 5 V com a bateria e mais 4 V com o resistor:

$$
V_2 = - (5\ \text{V} + 4\ \text{V}) = -9\ \text{V}
$$

**Respostas Finais:**

$$
\boxed{V_1 = -11\ \text{V}} \quad \text{e} \quad \boxed{V_2 = -9\ \text{V}}
$$
