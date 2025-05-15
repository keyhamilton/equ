---
hide:
  - navigation
  - toc
---
## 1. Equação Horária da Posição

Existem duas situações principais para a equação horária da posição, dependendo do tipo de movimento:

**a) Movimento Uniforme (MU):**

Neste tipo de movimento, a velocidade do objeto é constante e diferente de zero, e a aceleração é nula.

A equação horária da posição é:

$S = S_0 + v \cdot t$

Onde:

* **S**: É a **posição final** do objeto em um determinado instante. Sua unidade no Sistema Internacional (SI) é o metro (m).
* **S**: É a **posição inicial** do objeto, ou seja, a posição em que ele se encontrava no instante $t=0$. Sua unidade no SI também é o metro (m).
* **v**: É a **velocidade constante** do objeto. Sua unidade no SI é metros por segundo (m/s). Se v > 0, o movimento é progressivo (a favor da orientação da trajetória). Se $v < 0$, o movimento é retrógrado (contra a orientação da trajetória).
* **$t$**: É o **tempo** decorrido desde o início do movimento. Sua unidade no SI é o segundo (s).

**Gráficos do Movimento Uniforme (MU):**

* **Gráfico da Posição em Função do Tempo ($S \times t$):**
    * Como a equação $S = S_0 + v \cdot t$ é uma função do primeiro grau em relação ao tempo, o gráfico $S \times t$ é sempre uma **reta inclinada**.
    * O **coeficiente linear** da reta (onde ela corta o eixo $S$) é a **posição inicial ($S_0$)**.
    * A **inclinação da reta** (tangente do ângulo que a reta faz com o eixo $t$) representa a **velocidade ($v$)**.
        * Se a reta for crescente, a velocidade é positiva (movimento progressivo).
        * Se a reta for decrescente, a velocidade é negativa (movimento retrógrado).
        * Se a reta for horizontal, a velocidade é zero (repouso), o que tecnicamente não seria um MU, mas um caso limite.

* **Gráfico da Velocidade em Função do Tempo ($v \times t$):**
    * Como a velocidade é constante no MU, o gráfico $v \times t$ é uma **reta horizontal paralela ao eixo do tempo ($t$)**.
    * A altura dessa reta em relação ao eixo $t$ indica o valor da velocidade.
    * A área sob a reta no gráfico $v \times t$, entre dois instantes de tempo, representa o **deslocamento ($\Delta S$)** nesse intervalo.

* **Gráfico da Aceleração em Função do Tempo ($a \times t$):**
    * Como a aceleração é nula no MU, o gráfico $a \times t$ é uma **reta horizontal sobre o eixo do tempo ($t$)**, indicando $a = 0$.

##### Veja os *[gráficos(MU)](graphs.md)*

**b) Movimento Uniformemente Variado (MUV):**

Neste tipo de movimento, a velocidade do objeto varia de maneira uniforme ao longo do tempo, o que significa que a aceleração é constante e diferente de zero.

A equação horária da posição é:

$S = S_0 + v_0 \cdot t + \frac{1}{2} \cdot a \cdot t^2$

Onde:

* **$S$**: É a **posição final** do objeto em um determinado instante. Unidade no SI: metro (m).
* **$S_0$**: É a **posição inicial** do objeto (no instante $t=0$). Unidade no SI: metro (m).
* **$v_0$**: É la **velocidade inicial** do objeto (no instante $t=0$). Unidade no SI: metros por segundo (m/s).
* **$a$**: É a **aceleração constante** do objeto. Unidade no SI: metros por segundo ao quadrado (m/s²).
    * Se $a > 0$, o movimento é acelerado quando $v > 0$ e retardado quando $v < 0$ (a velocidade e a aceleração têm o mesmo sinal para acelerado, e sinais opostos para retardado).
    * Se $a < 0$, o movimento é retardado quando $v > 0$ e acelerado quando $v < 0$.
* **$t$**: É o **tempo** decorrido. Unidade no SI: segundo (s).

**Gráficos do Movimento Uniformemente Variado (MUV):**

* **Gráfico da Posição em Função do Tempo ($S \times t$):**
    * Como a equação $S = S_0 + v_0 \cdot t + \frac{1}{2} \cdot a \cdot t^2$ é uma função do segundo grau em relação ao tempo, o gráfico $S \times t$ é sempre uma **parábola**.
    * A **concavidade da parábola** é determinada pelo sinal da **aceleração ($a$)**:
        * Se $a > 0$, a concavidade é voltada para cima.
        * Se $a < 0$, a concavidade é voltada para baixo.
    * O **ponto onde a parábola corta o eixo $S$** (quando $t=0$) é a **posição inicial ($S_0$)**.
    * O **vértice da parábola** representa o ponto onde a velocidade instantânea do objeto é zero (inversão do sentido do movimento, se houver, ou o ponto de máximo ou mínimo deslocamento dependendo da situação).

* **Gráfico da Velocidade em Função do Tempo ($v \times t$):**
    * A equação da velocidade no MUV é $v = v_0 + a \cdot t$ (também conhecida como equação horária da velocidade). Esta é uma função do primeiro grau.
    * Portanto, o gráfico $v \times t$ é uma **reta inclinada**.
    * O **coeficiente linear** da reta (onde ela corta o eixo $v$) é a **velocidade inicial ($v_0$)**.
    * A **inclinação da reta** representa a **aceleração ($a$)**.
        * Se a reta for crescente, $a > 0$.
        * Se a reta for decrescente, $a < 0$.
        * Se a reta for horizontal, $a = 0$ (o que seria um MU, não MUV).
    * A **área sob a reta** no gráfico $v \times t$, entre dois instantes de tempo, representa o **deslocamento ($\Delta S$)** nesse intervalo.

* **Gráfico da Aceleração em Função do Tempo ($a \times t$):**
    * Como a aceleração é constante no MUV, o gráfico $a \times t$ é uma **reta horizontal paralela ao eixo do tempo ($t$)**.
    * A altura dessa reta em relação ao eixo $t$ indica o valor da aceleração.
##### Veja os *[gráficos(MUV)](graphs.md)*
## 2. Equação de Torricelli

A Equação de Torricelli é particularmente útil no MUV porque ela relaciona a velocidade de um corpo com o seu deslocamento, **sem depender diretamente do tempo**. Isso é muito vantajoso quando o tempo não é fornecido no problema ou não se deseja calculá-lo.

A equação é:

$v^2 = v_0^2 + 2 \cdot a \cdot \Delta S$

Onde:

* **$v$**: É a **velocidade final** do objeto. Unidade no SI: metros por segundo (m/s).
* **$v_0$**: É a **velocidade inicial** do objeto. Unidade no SI: metros por segundo (m/s).
* **$a$**: É a **aceleração constante** do objeto. Unidade no SI: metros por segundo ao quadrado (m/s²).
* **$\Delta S$**: É o **deslocamento** do objeto ($S - S_0$). Unidade no SI: metro (m).

**Componentes da Equação de Torricelli:**

* **$v^2$ (Velocidade final ao quadrado):** Relaciona-se com a energia cinética final do objeto.
* **$v_0^2$ (Velocidade inicial ao quadrado):** Relaciona-se com a energia cinética inicial do objeto.
* **$2 \cdot a \cdot \Delta S$ (Duas vezes o produto da aceleração pelo deslocamento):** Este termo está relacionado ao trabalho realizado pela força resultante que causa a aceleração, alterando a energia cinética do objeto.

**Gráficos relacionados à Equação de Torricelli:**

A Equação de Torricelli em si ($v^2 = v_0^2 + 2 \cdot a \cdot \Delta S$) não é tipicamente usada para gerar um gráfico direto de "Torricelli vs. alguma coisa" da mesma forma que as equações horárias geram gráficos de $S \times t$ ou $v \times t$.

No entanto, podemos analisar a relação entre as grandezas presentes nela:

* **Gráfico de $v^2$ em função de $\Delta S$:**
    * Se rearranjarmos a equação como $v^2 = (2a) \cdot \Delta S + v_0^2$, vemos que ela tem a forma de uma equação linear $y = m x + c$, onde:
        * $y = v^2$
        * $x = \Delta S$
        * $m = 2a$ (o coeficiente angular da reta é o dobro da aceleração)
        * $c = v_0^2$ (o coeficiente linear, onde a reta corta o eixo $v^2$, é o quadrado da velocidade inicial)
    * Portanto, se plotarmos $v^2$ no eixo vertical e $\Delta S$ no eixo horizontal, para um MUV, obteremos uma **reta**.
    * A **inclinação** desta reta nos dará $2a$.
    * O ponto onde a reta cruza o eixo $v^2$ (quando $\Delta S = 0$) nos dará $v_0^2$.

* **Gráfico de $v$ em função de $\Delta S$:**
    * Se quisermos plotar $v$ diretamente em função de $\Delta S$, teríamos $v = \sqrt{v_0^2 + 2 \cdot a \cdot \Delta S}$.
    * Este gráfico **não será uma reta**, mas sim um arco de parábola "deitado" (a raiz quadrada de uma função linear em $\Delta S$).
    * A forma exata dependerá dos valores de $v_0$ e $a$.
    * Este tipo de gráfico é menos comum em nível introdutório, mas ilustra como a velocidade varia com o deslocamento (por exemplo, em um movimento acelerado, a velocidade aumenta mais rapidamente no início do deslocamento se $v_0$ for pequena, e a taxa de aumento da velocidade com o deslocamento diminui à medida que $\Delta S$ cresce, devido à relação quadrática).


