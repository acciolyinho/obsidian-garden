#### Noções

**Ponto médio / Média:**
$$
x_i = \frac{\text{limite inferior} + \text{limite superior}}{2}, \quad \bar{x} = \frac{\sum (x_i \cdot f_i)}{\sum f_i}
$$

**Moda:**
$$
M = L + \left( \frac{d_1}{d_1 + d_2} \right) \cdot h
$$

- $L$ = limite inferior da classe modal
- $d_1​$ = diferença entre a frequência da classe modal e a frequência da classe anterior
- $d_2$ = diferença entre a frequência da classe modal e a frequência da classe seguinte
- $h$ = amplitude do intervalo de classe (sup - inf)

**Variância / Desvio padrão:**
$$
\sigma^2 = \frac{\sum (f_i \cdot (x_i - \bar{x})^2)}{\sum f_i}, \quad
\sigma = \sqrt{\sigma^2}
$$

#### Estimação
**Grandes Amostras / Pequenas Amostras:**
$$
E = \bar{x} \pm Z_{critico} \cdot \frac{\sigma \text{ ou } s}{\sqrt{n}}, \quad 
E = \bar{x} \pm t_{n-1, {critico}} \cdot \frac{s}{\sqrt{n}}
$$

**Proporção**
$$E = \hat{p} \pm Z_{critico} \cdot \sqrt{\frac{\hat{p}(1 - \hat{p})}{n}}$$

E = Intervalo de confiança
P = Proporção alvo da amostra
Z = Crítico Tab
N = Número de amostras
X = Média
S ou Sigma = Desvio padrão

#### Ajustamento
**Coeficiente de Correlação:**
$$
r = \frac{n \cdot \sum (X \cdot Y) - \sum X \cdot \sum Y} {\sqrt{ n \cdot \sum X^2 - (\sum X)^2} \cdot \sqrt{n \cdot \sum Y^2 - (\sum Y)^2}}
$$

**Regressão**
$$
a = \frac{n \cdot \sum (X \cdot Y) - \sum X \cdot \sum Y} {n \cdot \sum X^2 - (\sum X)^2}
$$

$$
b = \bar{y} - a \cdot \bar{x}
$$

$$
Y = a \cdot X + b
$$
