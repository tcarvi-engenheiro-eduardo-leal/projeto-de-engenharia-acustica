# Circuito RLC com corrente alternada (AC)
- R de **Resitor**
- L de **Indutor**
- C de **Capacitor**

## Componentes **RLC**
- Componentes passivos:
    - **Componente Resistor (R)**:
        - **Resistor com Resistência (R)**
        - Dissipa energia na forma de calor e oferece resistência à passagem da corrente.
    - **Componente Indutor (L)**:
        - **Indutor com Reatância Indutiva ($X_L$)**
            - O indutor armazena energia na forma de um campo magnético e oferece reatância indutiva.
            - **Reatância Indutiva ($X_L$)** é a oposição que um indutor apresenta à passagem de corrente alternada (AC).
            - A reatância indutiva depende:
                - **da frequência da corrente alternada** e 
                - **da indutância do indutor**.
            - **Equação da Reatância Indutiva** ($X_L$):
                - $$ X_L = \omega L = 2 \pi f L $$
                    - onde:
                        - $ X_L $ é a Reatância Indutiva (em ohms, Ω) 
                        - $ \omega $ é a frequëncia angular do movimento = $ 2 \pi f$ (em radianos/segundo)
                        - $ L $ é indutância (em henrys, H).
                        - $ f $ é a frequência do movimento ondulatório (em Herts, Hz)
            - Em Circuitos AC, um número complexo, denominado como **Impedância Complexa** ($Z$), apresenta uma combinação da resistência ($R$) e da reatância indutiva ($X_L$).
                - $$ Z = ResistênciaDoComponente + j X_L $$
                    - onde:
                        - $ Z $ é a impedância complexa (em ohms, Ω),
	                    - $ ResistênciaDoComponente $ é a resistência do componente (em ohms, Ω),
	                    - $ X_L $ é a reatância indutiva (em ohms, Ω),
	                    - $ j $ é a unidade imaginária ($j^2 = -1$).
    - **Componente Capacitor (C)**
        - **Capacitor com Reatância Capacitiva**:
            - O capacitor armazena energia na forma de um campo elétrico e oferece Reatância Capacitiva.
            - **Reatância Capacitiva** ($X_C$) é a oposição que um capacitor apresenta à passagem de corrente alternada (AC).
            - A reatância capacitiva depende:
                - **da frequência da corrente alternada** e
                - **da capacitância do capacitor**.
            - **Equação da Reatância Capacitiva** ($X_C$):
                - $$ X_C = \frac{1}{\omega C} = \frac{1}{2 \pi f C} $$
                    - onde:
                        - $ X_C $ é a Reatância Capacitiva (em ohms, Ω) 
                        - $ \omega $ é a frequëncia angular do movimento = $ 2 \pi f$ (em radianos/segundo)
                        - $ C $ é capacitância (em farads, F)
                        - $ f $ é a frequência do movimento ondulatório (em Herts, Hz)
            - Em Circuitos AC, um número complexo, denominado como **Impedância Complexa** ($Z$), apresenta uma combinação da resistência ($R$) e da reatância capacitiva ($X_C$).
                - $$ Z = ResistênciaDoComponente - j X_C $$
                    - onde:
                        - $ Z $ é a impedância complexa (em ohms, Ω),
	                    - $ ResistênciadoComponente $ é a resistência do componente (em ohms, Ω),
	                    - $ X_C $ é a reatância capacitiva (em ohms, Ω),
	                    - $ j $ é a unidade imaginária ($j^2 = -1$).
- Componente ativo:
    - **Fonte de Tensão E(t)** com geração da **tensão elétrica**.

## Aplicação de Tensão Alternada no circuito RLC
- Ao se aplicar uma tensão alternada, uma corrente elétrica (i) aparece no circuito.
- **Fórmula de tensão alternada**:
    - $ E(t) = E_m \sin( \omega t + \phi) $
    - onde:
        - E(t) é a tensão em função do tempo
        - $ E_m $ é a amplitude da tensão
        - $ \omega $ é a frequência angular = $2 \pi f $
        - $ t $ é o tempo
        - $ \phi $ é a fase inicial
- Cada componente do circuito apresenta **queda de tensão entre seus terminais devido a passagem de corrente elétrica**.
- **Queda de Tensão no Componente Resistor**:
    - Queda de tensão devido a resistência do resistor. (lei de Ohm para resistores)
        - $ V_R = R i$ 
            - onde:
                - $ V_R $ é a queda de tensão no componente resistor (em volts, V)
                - $ R $ é a resistência do componente resistor (em ohms, Ω).
                - $ i $ é a corrente elétrica que passa no componente resistor  (em amperes, A)
    - Reescrevendo tal fórmula, considerando um valor infinitesimal para a corrente elétrica:
        - $ V_R = R ( \frac {dq} {dt} ) $ 
- **Queda de Tensão no Componente Indutor**:
    - Queda de tensão devido a impedância do elemento indutor
    - A queda de tensão no componente indutor ocorre por causa da oposição da reatância indutiva contra a corrente elétrica. 
    - A queda de tensão no componente indutor é igual à tensão necessária para “empurrar” a corrente através da reatância indutiva. 
    - Queda de tensão devido a impedância do elemento indutor (lei de Ohm para componentes reativos):
        - $ V_L = X_L i $ 
            - onde:
                - $ V_L $ é a queda de tensão no componente indutor (em volts, V)
                - $ X_L $ é a reatância indutiva (em ohms, Ω)
                - $ i $ é a corrente elétrica que passa no componente indutor  (em amperes, A)
    - Reescrevendo tal fórmula considerando um valor infinitesimal de corrente:
        - $ V_L = L ( \frac {d^2q} {dtˆ2} ) $ 
- **Queda de Tensão no Componente Capacitor**:
    - Queda de tensão devido a impedância do elemento capacitor.
    - A queda de tensão no componente capacitor ocorre por causa da oposição da reatância capacitiva contra a corrente elétrica. 
    - A queda de tensão no componente capacitor é igual à tensão necessária para “empurrar” a corrente através da reatância capacitiva. 
    - Queda de tensão devido a impedância do elemento indutor (lei de Ohm para componentes reativos):
        - $ V_C = X_C i $ 
            - onde:
                - $ V_C $ é a queda de tensão no componente capacitor (em volts, V)
                - $ X_C $ é a reatância capacitiva (em ohms, Ω)
                - $ i $ é a corrente elétrica que passa no componente capacitor  (em amperes, A)
        - Reescrevendo tal fórmula considerando um valor infinitesimal de corrente:
            - $ V_C =  X_C \frac {dq} {dt} = \frac{1}{C}q$ 
- **Queda Total de Tensão no Circuito RLC**:
    - Conforme ***Lei de Kirchhoff para voltagens***, a voltagem aplicada em um circuito em série é igual à soma das quedas de voltagem geradas por seus elementos. 
        - Assim, para um sinal de tensão alternada, em um circuito RLC em série, com fase inicial = 0, temos:
            - $ E(t) = E_m \sin \omega t = R ( \frac {dq} {dt} ) + L ( \frac {d^2q} {dtˆ2} ) + \frac {1} {C} q $
    - A tensão total no circuito ($V_{total}$) é a soma fasorial das quedas de tensão nos três componentes passivos do circuito:
            - Para somar duas ou mais quantidades senoidais que variam no tempo, é mais simples transformá-las em seus equivalentes fasoriais, somá-las como vetores complexos e depois converter o resultado de volta para a forma de tempo, se necessário.
            - $$ V_{total} = V_R + V_L + V_C $$
    - Num circuito RLC em série, a queda de tensão nos três componentes (resistor R, indutor L, e capacitor C) pode ser analisada considerando a impedância total do circuito. 
        - A impedância total (Z) é a soma de vetores das impedâncias individuais:
            - $$ Z = R + j X_L - j X_C $$
                - onde:
                    - $ Z $ é a impedância total (em ohms, Ω),
                    - $ R $ é a resistência de todos os componentes do circuito (em ohms, Ω),
                    - $ X_L $ é a reatância indutiva (em ohms, Ω),
                    - $ X_C $ é a reatância capacitiva (em ohms, Ω),
                    - $ j $ é a unidade imaginária ($j^2 = -1$).

## Analogia entre fórmula de Tensão Alternada do circuito elétrico RLC com a fórmula da Força Aplicada de um sistema mecânico vibracional
- Em um sistema de vibração forçada e com amortecimento viscoso:
    - $$ F(x) = ma + cv + kx $$
        - onde:
            - `m` é a massa
            - `a` é a aceleração
            - `c` é o amortecimento
            - `v` é a velocidade
            - `k` é a constante da mola
            - `x` é o deslocamento
    - Reescrevendo os valores de aceleração e de velocidade:
        - $$ F(x) = m ( \frac {d^2x} {dtˆ2} ) + c ( \frac {dx} {dt} ) + kx $$  
    - Fórmula da variação de Força Senoidal:
        - $$ F(t) = F_0 \sin \omega t $$
    - Fórmula final:
        - $$ F_0 \sin \omega t = m ( \frac {d^2x} {dtˆ2} ) + c ( \frac {dx} {dt} ) + kx $$ 
- Analogia com a fórmula da queda total de tensão, em um circuito RLC de corrente alternada (AC), em um mesmo tempo $t$:
    - $ V \sin \omega t = L ( \frac {d^2q} {dtˆ2} ) + R ( \frac {dq} {dt} ) + \frac {1} {C} q $
    - $ F_0 \sin \omega t = m ( \frac {d^2x} {dtˆ2} ) + c ( \frac {dx} {dt} ) + kx $
- Do ponto de vista matemático, a análise dos valores do circuito elétrico é a mesma do sistema mecânico. 
- Assim, pode-se relacionar estas 2 equações, considerando, como equivalentes, as seguintes variáveis:  

| Circuitos Elétricos                     |  Sistema Mecânico                           |
|-----------------------------------------|---------------------------------------------|
| Carga Elétrica (q)                      | Deslocamento (x)                            |
| Corrente Elétrica ($i=\frac{dq}{dt}$)   | Velocidade ($v=\frac{dx}{dt}$)              |
| Voltagem $ E(t) = V \sin \omega t $     | Forca Aplicada $F(t) = F_0 \sin \omega t$   |
| Indutância (L)                          | Massa (m)                                   |
| Resistência (R)                         | Coeficiente de Armortecimanto Viscoso (c)   |
| Inverso da Capacitância (1/C)           | Rigidez da Mola (k)                         |
- Esta analogia matemática é relevante na aplicação de métodos experimentais, pois torna mais fácil a percepção do impacto de alterações nas variáveis do sistema.
    - É visualmente e mentalmente mais fácil modificar os componentes elétricos (Indutância, Resistência e  Inverso da Capacitância) e seus análogos mecânicos (Massa, Coeficiente de Armortecimanto Viscoso e Rigidez da Mola), em uma circuito análogo ao circuito elétrico.
- **Mas não é tão simples medir a corrente elétrica, em um circuito elétrico. E também não é simples medir a força em um sistema mecânico.**
    - Por isso, pode-usar o outros relacionamentos de analogia:

| Circuitos Elétricos   |  Sistema Mecânico   | Tipo de Analogia                          |
|-----------------------|---------------------|-------------------------------------------|
| Voltagem E(t)         | Velocidade (dx/dt)  | Analogia da impedância (de primeiro tipo) |
| Corrente Elétrica (i) | Forca Aplicada F(t) | Analogia da mobilidade (do segundo tipo)  |
- As grandezas acústicas e mecânicas como ***massa, amortecimento e rigidez*** são tratadas, respectivamente, pelos equivalentes de um circuito elétrico, como ***resistor, indutor** e **capacitor***.

## Importância do circuito RLC
- ( reler )
- O circuito RLC é importante porque ele pode ressoar, o que significa que pode amplificar sinais de uma determinada frequência, e também pode ser usado para filtrar sinais de determinadas frequências. 

## Ressonância em um circuito RLC
- ( reler )
- Ocorre quando a reatância indutiva e a reatância capacitiva se cancelam, resultando em uma impedância ou admitância mínima. 
- Na ressonância em circuito em Série: 
    - A impedância é mínima, e a corrente é máxima.
- Na ressonância em circuito em Paralelo:
    - A admitância é máxima, e a tensão é máxima.

## Fator de Qualidade (Q)
- ( reler )
- O fator de qualidade Q é uma medida da “nitidez” da ressonância e é dado por:

## Banda de Passagem
- ( reler )
- A banda de passagem (\Delta f) de um circuito RLC em ressonância é a faixa de frequências em que a resposta (corrente ou tensão) é significativa. É relacionada ao fator de qualidade por:

## Aplicações de Circuitos RLC
- Aplicações:
    - Filtragem de sinal elétrico: filtros passa-baixa, passa-alta, passa-banda e rejeita-banda.
    - Osciladores de sinal elétrico: Em eletrônica, para gerar sinais de uma frequência específica.
    - Sintonizadores de sinal elétrico: Em rádios e televisores, para selecionar a frequência de um sinal.

## A tensão elétrica 
- A tensão elétrica é a **diferença de potencial elétrico entre dois pontos dentro de um circuito elétrico**. 
- Ela **representa o trabalho necessário para mover uma carga elétrica de um ponto para outro**. 
- A unidade de medida da tensão elétrica é o *volt* (**V**). 
- Matematicamente, a tensão (V) é definida como:  
    - $V = \frac{W}{Q}$
        - onde:
            - ***V*** é a `tensão elétrica`,
            - ***W*** é o `trabalho realizado para mover a carga`,
            - ***Q*** é a `quantidade de carga elétrica`.