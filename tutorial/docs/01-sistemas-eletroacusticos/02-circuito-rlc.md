# Circuito RLC

## Componentes
- Componentes passivos:
    - Indutor de Indutância (L)
        - Armazena energia na forma de um campo magnético e oferece reatância indutiva.
    - Resistor de Resitência (R)
        - Dissipa energia na forma de calor e oferece resistência à passagem da corrente.
    - Capacitor de Capacitância (C)
        - Armazena energia na forma de um campo elétrico e oferece reatância capacitiva.
- Componente ativo:
    - Fonte de Tensão E(t)

## Aplicação de Tensão Alternada no circuito RLC
- Ao se aplicar uma tensão alternada, uma corrente elétrica (i) aparece no circuito.
- Fórmula de tensão alternada:
    - $ E(t) = E_m \sin( \omega t + \phi) $
    - onde:
        - E(t) é a tensão em função do tempo
        - $ E_m $ é a amplitude da tensão
        - $ \omega $ é a frequência angular = $2 \pi f $
        - $ \phi $ é a fase inicial
- Cada componente do circuito apresenta **queda de tensão devido a passagem de corrente elétrica**.
- Queda de Tensão no Componente Indutor:
    - $ V_L = L ( \frac {di} {dt} ) $ 
    - Queda de tensão devido a impedância do elemento indutor.
    - Reescrevendo tal fórmula considerando um valor infinitesimal de corrente:
    - $ V_L = L ( \frac {d^2q} {dtˆ2} ) $ 
- Queda de Tensão no Componente Resistor:
    - $ V_R = i R $ 
    - Queda de tensão devido a resistência do resistor.
    - Reescrevendo tal fórmula considerando um valor infinitesimal de corrente:
    - $ V_R = R ( \frac {dq} {dt} ) $ 
- Queda de Tensão no Componente Capacitor:
    - $ V_C = \frac 1 C \int idt $ 
    - Queda de tensão devido a impedância do elementos capacitor.
    - Reescrevendo tal fórmula considerando um valor infinitesimal de corrente:
    - $ V_C = \frac {q} {C} $ 
- Conforme ***Lei de Kirchhoff para voltagens***, a voltagem aplicada em um circuito em série é igual à soma das quedas de voltagem geradas por seus elementos. 
- Assim, para um sinal de tensão alternada, em um circuito RLC em série, com fase inicial = 0, temos:
    - $ E(t) = E_m \sin \omega t = L ( \frac {d^2q} {dtˆ2} ) + R ( \frac {dq} {dt} ) + \frac {1} {C} q $

## Vinculação com fórmula de sistema mecânico vibracional
- Sistema de vibração forçada com amortecimento viscoso.
- Fórmula da variação de Força Senoidal:
    - $ F(t) = F_0 \sin \omega t $
    - Incluindo na fórmula:
        - massa m
        - amortecimento c
        - constante da mola k
        - deslocamento x
        - velocidade v
        - a aceleração a
        - temos:
            -  $ ma + cv + kx = F_0 \sin \omega t $
    - Reescrevendo valores de aceleração e velocidade:
        - $ F_0 \sin \omega t = m ( \frac {d^2x} {dtˆ2} ) + c ( \frac {dx} {dt} ) + kx $  
- Percebemos que as equações mostradas para $ E(t) = E_m \sin \omega t $ e para $ F_0 \sin \omega t $ possuem a mesma forma.
    - $ E_m \sin \omega t = L ( \frac {d^2q} {dtˆ2} ) + R ( \frac {dq} {dt} ) + \frac {1} {C} q $
    - $ F_0 \sin \omega t = m ( \frac {d^2x} {dtˆ2} ) + c ( \frac {dx} {dt} ) + kx $  
- Do ponto de vista matemático, a análise do circuito elétrico é a mesma do sistema mecânico. 
- Assim, pode-se relacionar estas 2 equações, considerando como equivalentes, as seguintes variáveis:  

| Circuitos Elétricos           |  Sistema Mecânico                         |
|-------------------------------|-------------------------------------------|
| Carga Elétrica (q)            | Deslocamento (x)                          |
| Corrente Elétrica (i)         | Velocidade (dx/dt)                        |
| Voltagem E(t)                 | Forca Aplicada F(t)                       |
| Indutância (L)                | Massa (m)                                 |
| Resistência (R)               | Coeficiente de Armortecimanto Viscoso (c) |
| Inverso da Capacitância (1/C) | Rigidez da Mola (k)                       |
- O principal valor da analogia com circuitos elétricos está na aplicação em métodos experimentais.  
    - É visualmente e mentalmente mais fácil modificar os componentes elétricos (indutores, resistores e capacitores) e seus análogos mecânicos (massa, coeficiente de armotecimento viscoso o inverso da rigidez da mola), em uma circuito análogo ao circuito elétrico.
- Não é tão simples medir a corrente elétrica, em um circuito elétrico. E também não é simples medir a força em um sistema mecânico.
- Por isso, pode-usar o seguinte relacionamentos de analogia:

| Circuitos Elétricos   |  Sistema Mecânico   | Tipo de Analogia                          |
|-----------------------|---------------------|-------------------------------------------|
| Voltagem E(t)         | Velocidade (dx/dt)  | Analogia da impedância (de primeiro tipo) |
| Corrente Elétrica (i) | Forca Aplicada F(t) | Analogia da mobilidade (do segundo tipo)  |

## Importância do circuito RLC
- O circuito RLC é importante porque ele pode ressoar, o que significa que pode amplificar sinais de uma determinada frequência, e também pode ser usado para filtrar sinais de determinadas frequências. 

## Ressonância em um circuito RLC
- Ocorre quando a reatância indutiva e a reatância capacitiva se cancelam, resultando em uma impedância ou admitância mínima. 
- Na ressonância em circuito em Série: 
    - A impedância é mínima, e a corrente é máxima.
- Na ressonância em circuito em Paralelo:
    - A admitância é máxima, e a tensão é máxima.

## Fator de Qualidade (Q)
- O fator de qualidade Q é uma medida da “nitidez” da ressonância e é dado por:

## Banda de Passagem
- A banda de passagem (\Delta f) de um circuito RLC em ressonância é a faixa de frequências em que a resposta (corrente ou tensão) é significativa. É relacionada ao fator de qualidade por:

## Aplicações de Circuitos RLC
- Aplicações:
    - Filtros: Circuitos RLC são usados em filtros passa-baixa, passa-alta, passa-banda e rejeita-banda.
    - Osciladores: Em eletrônica, para gerar sinais de uma frequência específica.
    - Sintonizadores: Em rádios e televisores, para selecionar a frequência de um sinal.

-Um circuito RLC, seja em série ou em paralelo, é uma configuração de resistor, indutor e capacitor que pode ressoar a uma frequência específica.
- Ele tem aplicações em filtragem, oscilação e sintonização de sinais elétricos.
- As propriedades de ressonância, fator de qualidade e banda de passagem são fundamentais para sua análise e aplicação prática.

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