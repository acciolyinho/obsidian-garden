• Capítulo 21
– 2
– 4
– 13
– 29
– 35
• Capítulo 22
– 7
– 24
– 30
– 32
– 37

## (Cap 21) Questão 2

### Resolução

As esferas 1 e 2 têm carga $q$ cada uma. Como a força eletrostática entre duas cargas pontuais idênticas a uma distância $r$ é dada por:

$$
F = k \dfrac{q^2}{r^2}
$$

**Esfera 3 toca a esfera 1**

A esfera 3 está inicialmente neutra $q = 0$, e a esfera 1 tem carga $q$. Ao se tocarem, a carga se distribui igualmente:

$$
q_1 = q_3 = \dfrac{q}{2}
$$

**Esfera 3 toca a esfera 2**

$$
q_{\text{total}} = \dfrac{q}{2} + q = \dfrac{3q}{2}
$$

**Distribuindo igualmente:**

$$
q_2 = q_3 = \dfrac{3q}{4}
$$

**Agora temos:**
- Esfera 1: $q_1 = \dfrac{q}{2}$
- Esfera 2: $q_2 = \dfrac{3q}{4}$

**Nova força entre as esferas**

$$
F' = k \dfrac{q_1 \cdot q_2}{r^2} = k \dfrac{\left(\dfrac{q}{2}\right)\left(\dfrac{3q}{4}\right)}{r^2} = k \dfrac{3q^2}{8r^2}
$$

Comparando com $F = k \dfrac{q^2}{r^2}$, temos:

$$
\dfrac{F'}{F} = \dfrac{\dfrac{3q^2}{8r^2}}{\dfrac{q^2}{r^2}} = \dfrac{3}{8}
$$

**Resposta:**

$$
\boxed{\dfrac{F'}{F} = \dfrac{3}{8} = 0{,}375}
$$

---

## (Cap 21) Questão 4:

### Resolução:

Sabemos da eletrodinâmica que a **carga elétrica $q$** transferida por uma corrente constante durante um intervalo de tempo é dada pela equação fundamental:

$$
q = i \cdot \Delta t
$$

onde:

- $q$ é a carga elétrica transferida (em coulombs, C),
- $i$ é a corrente elétrica constante (em ampères, A),
- $\Delta t$ é o intervalo de tempo durante o qual a corrente é mantida (em segundos, s).


### Passo 1: Conversão de unidades

O tempo fornecido está em microssegundos ($\mu\text{s}$). Devemos converter para segundos:

$$
\Delta t = 20 \, \mu\text{s} = 20 \times 10^{-6} \, \text{s} = 2{,}0 \times 10^{-5} \, \text{s}
$$

### Passo 2: Substituir os valores na equação

A corrente elétrica fornecida é:

$$
i = 2{,}5 \times 10^4 \, \text{A}
$$

Substituímos os valores na fórmula:

$$
q = (2{,}5 \times 10^4) \cdot (2{,}0 \times 10^{-5}) \, \text{C}
$$

### Passo 3: Efetuar o produto

Multiplicamos os coeficientes e aplicamos a propriedade das potências:

$$
q = 2{,}5 \cdot 2{,}0 \cdot 10^4 \cdot 10^{-5}
$$

$$
q = 5{,}0 \cdot 10^{-1} \, \text{C}
$$

$$
q = 0{,}50 \, \text{C}
$$

### Interpretação física:

Durante a curta duração de um relâmpago — apenas $20 \, \mu\text{s}$ — uma corrente extremamente intensa (25.000 A) flui, transferindo meio coulomb de carga. Esse valor é significativo, especialmente considerando que 1 C equivale ao fluxo de cerca de $6{,}24 \times 10^{18}$ elétrons.

### Resposta final:

$$
\boxed{q = 0{,}50 \, \text{C}}
$$

---

## (Cap 21) Questão 13:

### Resolução:

Vamos determinar a posição de equilíbrio para a carga $q_3$, ou seja, a posição onde a força elétrica resultante sobre ela devido a $q_1$ e $q_2$ é nula.  

#### Análise conceitual:

- A força elétrica entre cargas é dada pela Lei de Coulomb:

$$
F = k \frac{|q_1 q_2|}{r^2}
$$

- Para que a força resultante sobre $q_3$ seja nula, as forças devido a $q_1$ e $q_2$ devem ter o mesmo módulo e direções opostas.  

Como:

- $q_1 > 0$
- $q_2 < 0$
- $q_3$ é desconhecida (mas o sinal não interfere no ponto de equilíbrio),
- E as cargas estão dispostas sobre o eixo $x$,
  
temos que:

- Não há equilíbrio possível entre $q_1$ e $q_2$, pois nesse intervalo as forças se somariam (ambas atrairiam ou repeliriam $q_3$ para a mesma direção).

- Também não há equilíbrio fora do eixo $x$, pois a componente $y$ das forças não pode se anular de forma simétrica (já que as magnitudes são diferentes).

- Assim, devemos buscar uma posição ao longo do eixo $x$, mas fora do intervalo entre as cargas — mais precisamente, à esquerda de $q_1$, onde as forças podem se opor.

#### Cálculo:

Vamos supor que a carga $q_3$ esteja a uma distância $L_0$ à esquerda de $q_1$. Assim, as distâncias até $q_1$ e $q_2$ são:

- Até $q_1$: $L_0$

- Até $q_2$: $L + L_0$

Impondo o equilíbrio das forças (módulos iguais):

$$
k \cdot \frac{|q_1 q_3|}{L_0^2} = k \cdot \frac{|q_2 q_3|}{(L + L_0)^2}
$$

Cancelamos $k$ e $q_3$, pois não são nulos:

$$
\frac{|q_1|}{L_0^2} = \frac{|q_2|}{(L + L_0)^2}
$$

Substituímos os valores:

$$
\frac{1{,}0}{L_0^2} = \frac{3{,}0}{(10 + L_0)^2}
$$

Tirando a raiz dos dois lados:

$$
\frac{1}{L_0} = \frac{\sqrt{3}}{10 + L_0}
\quad \Rightarrow \quad
\frac{10 + L_0}{L_0} = \sqrt{3}
$$

Isolando $L_0$:

$$
\frac{10}{L_0} + 1 = \sqrt{3}
\quad \Rightarrow \quad
\frac{10}{L_0} = \sqrt{3} - 1
\quad \Rightarrow \quad
L_0 = \frac{10}{\sqrt{3} - 1}
$$

Racionalizando o denominador:

$$
L_0 = \frac{10 (\sqrt{3} + 1)}{(\sqrt{3} - 1)(\sqrt{3} + 1)} = \frac{10 (\sqrt{3} + 1)}{3 - 1} = 5(\sqrt{3} + 1)
$$

Aproximando numericamente:

$$
L_0 \approx 5 (1{,}732 + 1) = 5 \times 2{,}732 = 13{,}66 \, \text{cm} \approx 14 \, \text{cm}
$$

Logo, $q_3$ deve ser colocada a:

$$
x = -14 \, \text{cm}
$$

#### Parte (b) – Coordenada $y$

Como todas as cargas estão dispostas ao longo do eixo $x$ e a resultante deve ser nula, a carga $q_3$ também deve estar nesse eixo. Logo:

$$
y = 0
$$

**Resposta final:**

- (a) $x = -14 \, \text{cm}$
- (b) $y = 0$

---

## (Cap 21 ) Questão 29:

Inicialmente:
- Partícula 1 está em $x = -10{,}0 \, \text{cm}$,
- Partícula 3 está em $x = +10{,}0 \, \text{cm}$.

A força total sobre a partícula 5 é vertical (ao longo de $-y$). Queremos:

(a) Mover a partícula 1 de tal forma que a força total sobre a partícula 5 sofra uma rotação de $30^\circ$ no sentido anti-horário.

(b) Após esse deslocamento, mover a partícula 3 para que a força total volte à direção original (apenas vertical).

### Resolução:

#### Parte (a) – Deslocamento da partícula 1 para rotação de $30^\circ$

Sabemos que inicialmente, por simetria, as forças horizontais (de partículas 1 e 3) se cancelam, e as verticais se somam, resultando em uma força total de módulo $3F$ ao longo do eixo $y$.

Se a força for rotacionada de $30^\circ$ para a esquerda (anti-horário), significa que agora há uma componente horizontal $F_x$ para a esquerda e uma componente vertical $F_y$, mantendo a mesma direção geral da força resultante.

Aplicamos:

$$
\tan(30^\circ) = \frac{F_x}{F_y} = \frac{1}{\sqrt{3}}
$$

Como inicialmente $F_y = 3F$, então:

$$
F_x = \frac{1}{\sqrt{3}} \cdot 3F = \sqrt{3} F
$$

Agora, analisando a nova configuração:

- A partícula 3 continua exercendo força $F$ para a esquerda sobre a carga central.
- A partícula 1, ao ser deslocada, exerce força $F'$ para a direita sobre a carga central.

Então:

$$
F' - F = \sqrt{3} F \quad \Rightarrow \quad F' = (\sqrt{3} + 1) F
$$

Como a força eletrostática é inversamente proporcional ao quadrado da distância:

$$
F \propto \frac{1}{r^2}
\quad \Rightarrow \quad
\frac{1}{r^2} = (\sqrt{3} + 1)
\cdot \frac{1}{d^2}
$$

onde $d = 10{,}0 \, \text{cm}$ é a distância original. Resolvendo para $r$:

$$
r^2 = \frac{d^2}{\sqrt{3} + 1}
\quad \Rightarrow \quad
r = \frac{d}{\sqrt{\sqrt{3} + 1}}
$$

Aproximando:

$$
\sqrt{3} + 1 \approx 2{,}732
\quad \Rightarrow \quad
\sqrt{2{,}732} \approx 1{,}65
\quad \Rightarrow \quad
r = \frac{10 \, \text{cm}}{1{,}65} \approx 6{,}05 \, \text{cm}
$$

Logo, a partícula 1 deve ser deslocada para:

$$
x = -6{,}05 \, \text{cm}
$$

#### Parte (b) – Deslocamento da partícula 3 para restaurar a direção original

Para que a força total volte a ter apenas componente vertical (ou seja, $F_x = 0$), precisamos restaurar a simetria horizontal.

Assim, a partícula 3 deve ser deslocada de forma simétrica em relação à posição da partícula 1. Ou seja:

$$
x_3 = +6{,}05 \, \text{cm}
$$

**Respostas finais:**
- (a) A partícula 1 deve ser movida para $x = -6{,}05 \, \text{cm}$
- (b) A partícula 3 deve ser movida para $x = +6{,}05 \, \text{cm}$

---

## (Cap 21) Questão 35

### Resolução:

#### Parte (a) – Todos os 8 íons $\text{Cs}^+$ presentes

Sabemos que a força elétrica entre duas cargas puntiformes é dada por:

$$
F = k \frac{q_1 q_2}{r^2}
$$

onde:
- $k = 8{,}99 \times 10^9 \, \text{N} \cdot \text{m}^2/\text{C}^2$ é a constante eletrostática,
- $q = 1{,}60 \times 10^{-19} \, \text{C}$ é a carga elementar,
- $r$ é a distância entre os íons.
  
**Distância entre o centro do cubo e um vértice:**

A distância entre o centro do cubo (onde está o íon $\text{Cl}^-$) e um vértice (onde está um $\text{Cs}^+$) é a metade da diagonal do cubo:

$$
d = \frac{\sqrt{3}}{2} a = \frac{\sqrt{3}}{2} \cdot 0{,}40 \times 10^{-9} \, \text{m} \approx 0{,}346 \times 10^{-9} \, \text{m}
$$

**Interações simétricas:**

Como o sistema é perfeitamente simétrico, cada par de íons $\text{Cs}^+$ opostos exerce forças de mesma magnitude e direções opostas sobre o $\text{Cl}^-$, o que leva a uma **anulação vetorial total** da força resultante:

$$
\vec{F}_{\text{total}} = 0
$$

#### Parte (b) – Um íon $\text{Cs}^+$ ausente (defeito)

Se um dos vértices está sem o íon $\text{Cs}^+$, essa simetria é quebrada. A força total sobre o $\text{Cl}^-$ será apenas a força exercida por esse íon "ausente" — como se fosse um campo de uma carga fictícia $-e$ naquela posição (princípio da superposição).

**Cálculo da força:**
$$
F = k \frac{e^2}{d^2}
$$

Substituindo:

- $e = 1{,}60 \times 10^{-19} \, \text{C}$
- $d = 0{,}346 \times 10^{-9} \, \text{m}$

$$
F = \frac{(8{,}99 \times 10^9) \cdot (1{,}60 \times 10^{-19})^2}{(0{,}346 \times 10^{-9})^2}
$$

$$
F = \frac{(8{,}99 \times 10^9) \cdot (2{,}56 \times 10^{-38})}{1{,}197 \times 10^{-19}} \approx 1{,}91 \times 10^{-9} \, \text{N}
$$

### Respostas:

- (a) Quando todos os 8 íons $\text{Cs}^+$ estão presentes, a força eletrostática resultante sobre o íon $\text{Cl}^-$ é:

$$
\boxed{0 \, \text{N}} \quad \text{(devido à simetria)}
$$
- (b) Quando um dos íons $\text{Cs}^+$ está ausente, a força eletrostática resultante sobre o íon $\text{Cl}^-$ é:

$$
\boxed{1{,}91 \times 10^{-9} \, \text{N}}
$$

--- 

## (Cap 22) Questão 7:

### Resolução:

O campo elétrico no centro do quadrado devido a uma carga $q$ é:

$$
\vec{E} = \frac{1}{4\pi \varepsilon_0} \cdot \frac{q}{r^2} \cdot \hat{r}
$$

#### Geometria:

- O centro do quadrado está equidistante de todos os vértices.
- A distância de cada vértice ao centro é:
  
$$
r = \frac{a}{\sqrt{2}} = \frac{0{,}050 \, \text{m}}{\sqrt{2}} \approx 0{,}03536 \, \text{m}
$$

Vamos decompor os vetores campo elétrico de cada carga em suas componentes $x$ e $y$, e somar.

#### Componente $E_x$:

Por simetria e orientação:

$$
E_x = \frac{1}{4\pi \varepsilon_0} \cdot \frac{\sqrt{2}}{a^2} \cdot (q_1 + q_3 - q_2 - q_4)
$$

Substituindo os valores:

$$
E_x = \frac{1}{4\pi \varepsilon_0} \cdot \frac{\sqrt{2}}{a^2} \cdot (10 + 20 - 20 - 10) \, \text{nC} = 0
$$

#### Componente $E_y$:

$$
E_y = \frac{1}{4\pi \varepsilon_0} \cdot \frac{\sqrt{2}}{a^2} \cdot (-q_1 - q_3 + q_2 + q_4)
$$

Substituindo:

$$
E_y = \frac{1}{4\pi \varepsilon_0} \cdot \frac{\sqrt{2}}{(0{,}050)^2} \cdot (-10 - 20 + (-20) + (-10)) \times 10^{-9}
$$

$$
E_y = \frac{8{,}99 \times 10^9}{0{,}0025} \cdot \sqrt{2} \cdot (-60 \times 10^{-9})
$$

$$
E_y \approx 1{,}02 \times 10^5 \, \text{N/C}
$$

### Campo resultante:

Como $E_x = 0$ e $E_y \neq 0$, o campo total está apontando na direção $+\hat{j}$, ou seja, eixo $y$ positivo:

$$
\vec{E}_{\text{total}} = (0 \, \hat{i} + 1{,}02 \times 10^5 \, \hat{j}) \, \text{N/C}
$$

**Resposta final:**

$$
\boxed{\vec{E} = 1{,}02 \times 10^5 \, \hat{j} \, \text{N/C}}
$$

Campo elétrico no centro do quadrado é vertical, apontando para cima.

---

## (Cap 22) Questão 24:

### Resolução:

#### (a) Campo elétrico no centro do anel $(z = 0)$

Por simetria, cada elemento de carga $dq$ no anel está emparelhado com um elemento oposto. As componentes do campo elétrico desses pares se cancelam no centro do anel. Assim, o campo elétrico total no centro é:

$$
\boxed{E = 0}
$$

#### (b) Campo elétrico no ponto $z \to \infty$

A uma distância muito grande $z \gg R$, o anel se comporta como uma carga pontual concentrada na origem. A expressão para o campo ao longo do eixo $z$ é:

$$
E(z) = \frac{1}{4\pi\varepsilon_0} \cdot \frac{Qz}{(z^2 + R^2)^{3/2}}
$$

No limite $z \to \infty$:

$$
E(z) \approx \frac{1}{4\pi\varepsilon_0} \cdot \frac{Q}{z^2}
$$

Ou seja, o campo decresce como $\sim 1/z^2$, típico de uma carga pontual.

#### (c) Valor de $z$ onde $E(z)$ é máximo

Queremos o valor de $z$ onde $E(z)$ atinge seu valor máximo. Diferenciando a expressão do campo:

$$
E(z) = \frac{1}{4\pi\varepsilon_0} \cdot \frac{Qz}{(z^2 + R^2)^{3/2}}
$$

Derivando:

$$
\frac{dE}{dz} = \frac{Q}{4\pi\varepsilon_0} \cdot \frac{R^2 - 2z^2}{(z^2 + R^2)^{5/2}} = 0
$$

Resolvendo:

$$
R^2 - 2z^2 = 0 \quad \Rightarrow \quad z = \frac{R}{\sqrt{2}} \approx 0{,}707 R
$$

#### (d) Valor máximo do campo

Usamos a posição $z = \frac{R}{\sqrt{2}}$ na equação do campo:

$$
E_{\text{máx}} = \frac{1}{4\pi\varepsilon_0} \cdot \frac{Qz}{(z^2 + R^2)^{3/2}}
$$

Substituindo:
- $Q = 4{,}00 \times 10^{-6} \, \text{C}$
- $R = 0{,}020 \, \text{m}$
- $z = \frac{R}{\sqrt{2}} \approx 0{,}01414 \, \text{m}$
- $\varepsilon_0 = 8{,}85 \times 10^{-12} \, \text{C}^2/\text{N} \cdot \text{m}^2$

$$
E_{\text{máx}} \approx 3{,}46 \times 10^7 \, \text{N/C}
$$

### Respostas finais:

- (a) $\boxed{E = 0}$
- (b) $\boxed{E \propto \frac{1}{z^2}}$, como uma carga pontual
- (c) $\boxed{z = \frac{R}{\sqrt{2}} \approx 0{,}707 R}$
- (d) $\boxed{E_{\text{máx}} = 3{,}46 \times 10^7 \, \text{N/C}}$

---

## (Cap 22) Questão 30:


### Resolução:

#### Passo 1: Campo elétrico axial de um anel

O campo elétrico produzido por um anel carregado no ponto $z$ sobre seu eixo é dado por:

$$
E(z) = \frac{1}{4\pi\varepsilon_0} \cdot \frac{qz}{(z^2 + R^2)^{3/2}}
$$

Para dois anéis no mesmo plano (no plano $z = 0$), com o ponto $P$ localizado a uma altura $z = D$ acima do centro, o campo total é a soma vetorial dos dois campos gerados pelos anéis.


#### Passo 2: Superposição dos campos no ponto $P$

Seja:
- Anel menor: raio $R$, carga $+Q$
- Anel maior: raio $3R$, carga $q$
- Ponto $P$: $z = D = 2R$

O campo total no ponto $P$ é:

$$
E_{\text{total}} = \frac{1}{4\pi\varepsilon_0} \left[ \frac{Qz}{(z^2 + R^2)^{3/2}} + \frac{qz}{(z^2 + (3R)^2)^{3/2}} \right]
$$

Desejamos que $E_{\text{total}} = 0$. Como $z \neq 0$, podemos cancelar o fator comum $z / 4\pi\varepsilon_0$:

$$
\frac{Q}{(z^2 + R^2)^{3/2}} + \frac{q}{(z^2 + (3R)^2)^{3/2}} = 0
$$

Substituímos $z = 2R$:

- $z^2 + R^2 = (2R)^2 + R^2 = 5R^2$
- $z^2 + (3R)^2 = (2R)^2 + 9R^2 = 13R^2$

$$
\frac{Q}{(5R^2)^{3/2}} + \frac{q}{(13R^2)^{3/2}} = 0
$$

$$
\frac{Q}{5^{3/2} R^3} + \frac{q}{13^{3/2} R^3} = 0
$$

Multiplicando por $R^3$ e isolando $q$:

$$
\frac{Q}{5^{3/2}} + \frac{q}{13^{3/2}} = 0
\quad \Rightarrow \quad
q = -Q \cdot \left( \frac{13}{5} \right)^{3/2}
$$

Calculando:

$$
\left( \frac{13}{5} \right)^{3/2} \approx 4{,}19
\quad \Rightarrow \quad
\boxed{q = -4{,}19Q}
$$


### Resposta final:

Para que o campo elétrico no ponto $P$ seja nulo:

$$
\boxed{q = -4{,}19Q}
$$

---

## (Cap 22) Questão 32:


### Resolução:

#### Simetria e modelo

A carga está uniformemente distribuída, então podemos definir a densidade linear de carga como:

$$
\lambda = \frac{q}{L}
$$

O campo elétrico no ponto $P$, acima da mediatriz da barra, terá apenas **componente vertical** (em $y$), devido à simetria. As componentes horizontais $x$ se cancelam, pois para cada elemento $dq$ a uma distância $x$, existe outro simétrico a $-x$ com campo oposto em $x$.


#### (a) Módulo do campo elétrico

Utilizamos a expressão do campo no ponto $P$, a uma altura $R$ acima da barra, com integração ao longo da metade da barra e multiplicação por 2:

$$
E = \frac{2\lambda R}{4\pi\varepsilon_0} \int_0^{L/2} \frac{dx}{(x^2 + R^2)^{3/2}}
$$

Essa integral tem resultado conhecido:

$$
\int_0^{L/2} \frac{dx}{(x^2 + R^2)^{3/2}} = \frac{L/2}{R^2 \sqrt{(L/2)^2 + R^2}}
$$

Substituímos:

$$
E = \frac{\lambda}{2\pi\varepsilon_0} \cdot \frac{L/2}{R \sqrt{(L/2)^2 + R^2}} = \frac{q}{2\pi\varepsilon_0 LR} \cdot \frac{L/2}{\sqrt{(L/2)^2 + R^2}} = \frac{q}{2\pi\varepsilon_0 R \sqrt{(L/2)^2 + R^2}}
$$

Substituindo os valores numéricos:

- $q = 7{,}81 \times 10^{-12} \, \text{C}$
- $L = 0{,}145 \, \text{m}$
- $R = 0{,}060 \, \text{m}$
- $\varepsilon_0 = 8{,}85 \times 10^{-12} \, \text{C}^2/\text{N} \cdot \text{m}^2$

$$
E = \frac{7{,}81 \times 10^{-12}}{2\pi \cdot 8{,}85 \times 10^{-12} \cdot 0{,}060 \cdot \sqrt{(0{,}0725)^2 + 0{,}060^2}} \approx \boxed{12{,}4 \, \text{N/C}}
$$


#### (b) Direção do campo elétrico

Como a barra tem simetria em relação ao eixo $x$, o campo elétrico resultante no ponto $P$ aponta **exatamente para cima**, ou seja, ao longo do eixo $y$ positivo.

Portanto, a orientação do campo em relação ao semieixo $x$ positivo é:

$$
\boxed{+90^\circ}
$$


### Respostas finais:

- (a) $\boxed{E = 12{,}4 \, \text{N/C}}$
- (b) $\boxed{\theta = +90^\circ}$, isto é, no sentido do eixo $y$ positivo

---

## (Cap 22) Questão 37:


### Resolução:

#### Campo de um disco sólido:

A expressão do campo elétrico ao longo do eixo de um disco uniformemente carregado de raio $R$, no ponto $z$ acima de seu centro, é:

$$
E_{\text{disco}} = \frac{\sigma}{2\varepsilon_0} \left( 1 - \frac{z}{\sqrt{z^2 + R^2}} \right)
$$

Substituindo $z = 2R$:

$$
E_{\text{disco}} = \frac{\sigma}{2\varepsilon_0} \left( 1 - \frac{2R}{\sqrt{(2R)^2 + R^2}} \right)
= \frac{\sigma}{2\varepsilon_0} \left( 1 - \frac{2}{\sqrt{5}} \right)
$$

#### Campo de um anel (disco com furo central de raio $R/2$):

A ideia é considerar o anel como a **diferença** entre:

- um disco de raio $R$, com densidade $\sigma$,
- e um disco de raio $R/2$, com densidade $-\sigma$ (simulando o furo como carga oposta).

Logo, o campo total é:

$$
E_{\text{anel}} = \frac{\sigma}{2\varepsilon_0} \left( 1 - \frac{2}{\sqrt{5}} \right)
- \frac{\sigma}{2\varepsilon_0} \left( 1 - \frac{2}{\sqrt{17/4}} \right)
$$

Note que:

- $z = 2R$,
- o raio do disco interno é $R/2$,
- então $\sqrt{z^2 + (R/2)^2} = \sqrt{4R^2 + R^2/4} = \sqrt{17R^2/4} = R\sqrt{17}/2$

Assim:

$$
E_{\text{anel}} = \frac{\sigma}{2\varepsilon_0} \left[ \left( 1 - \frac{2}{\sqrt{5}} \right) - \left( 1 - \frac{4}{\sqrt{17}} \right) \right]
= \frac{\sigma}{2\varepsilon_0} \left( \frac{4}{\sqrt{17}} - \frac{2}{\sqrt{5}} \right)
$$

#### Redução percentual:

A redução percentual do campo é:

$$
\text{Redução} = \frac{E_{\text{disco}} - E_{\text{anel}}}{E_{\text{disco}}}
= \frac{\left( 1 - \frac{2}{\sqrt{5}} \right) - \left( \frac{4}{\sqrt{17}} - \frac{2}{\sqrt{5}} \right)}{1 - \frac{2}{\sqrt{5}}}
= \frac{1 - \frac{4}{\sqrt{17}}}{1 - \frac{2}{\sqrt{5}}}
$$

Calculando:

- $\frac{4}{\sqrt{17}} \approx \frac{4}{4{,}123} \approx 0{,}970$
- $\frac{2}{\sqrt{5}} \approx \frac{2}{2{,}236} \approx 0{,}894$

$$
\text{Numerador} \approx 1 - 0{,}970 = 0{,}030
\quad ; \quad
\text{Denominador} \approx 1 - 0{,}894 = 0{,}106
$$

$$
\text{Redução} \approx \frac{0{,}030}{0{,}106} \approx 0{,}283 \Rightarrow \boxed{28{,}3\%}
$$

### Resposta final:

A substituição do disco por um anel reduz o campo elétrico no ponto $P$ em aproximadamente:

$$
\boxed{28\%}
$$
