**Variância / Desvio padrão:**
$$
\sigma^2 = \frac{\sum (f_i \cdot (x_i - \bar{x})^2)}{\sum f_i}, \quad
\sigma = \sqrt{\sigma^2}
$$

#### ANOVA

$$
F = \frac{S_E^2}{S_D^2}
$$

$$
S_E^2 = N \left[ \frac{\sum \bar{x_i}^2 - \left( \frac{\left(\sum \bar{x_i} \right)^2}{k} \right)}{k - 1} \right]
$$

$$
S_D^2 = \frac{(N_1 - 1) S_1^2 + (N_2 - 1) S_2^2 + \dots + (N_k - 1) S_k^2}
{(N_1 - 1) + (N_2 - 1) + (N_3 - 1) + \dots + (N_k - 1)}
$$

#### CHI - QUADRADO

$$
e_{ij} = \frac{N_{i \bullet} \times N_{\bullet j}}{N}
$$

$$
\chi^2 = \sum\limits_{i=1}^{I} \sum\limits_{j=1}^{J} \frac{(N_{ij} - e_{ij})^2}{e_{ij}}
$$
