# Eletroacústica

## Análise da Eletroacústica
- Parte da engenharia que linda com **conversões (transdução)** entre:
    - **Energia Mecânica**
    - **Energia Elétrica**
    - **Energia Acústica**
- A análise da eletroacústica pode seguir dois padrões:
    - **Padrão 1 das equações diferenciais da física**:
        - Energia acústica pensada como ondas quantificadas com equações diferenciais.
        - Energia elétrica pensada como formada por diferencial de potencial entre terminais de algum condutor. Condutor que passa a ter diferença de potencial devido interações dos campos elétricos e magnéticos. Tais interações também são quantificadas, nesta forma de análise, por equações diferenciais.
    - **Padrão 2 de analogia com um circuito elétrico**:
        - Inspeciona-se visualmente o processo eletroacústico e se define um circuito que representa uma analogia com um circuito elétrico.
        - Vincula-se elementos acústicos ao circuito.
        - Resolve-se o circuito e se conclui a análise eletroacústica.

## Sistemas/Equipamentos da Eletroacústica:

### Produtor de som
1. Recebe uma tensão elétrica ($V$), medida em volts (V)
2. Gera som que possui uma pressão sonora ($P$), medida em pascal (Pa).
3. O som produzido segue alcançando, pelo ar, superfícies de objetos que recebem esta pressão.
4. A recepção da pressão sonora equivale a recepção acústica do som.

### Equipamento Captador do Som (Microfones)
1. Recepciona ondas sonoras cujas **frequência** ($f$) estão entre 20 Hz e 20 KHz e que possuem **pressão sonora** ($P$).
2. As ondas sonoras alcançam a superfície de captação do microfone com certa força ($F$) de movimentação das partículas de ar, ocorrendo a **recepção da pressão sonora** ($P$).
    - A pressão sonora ($P$) é medida em pascal (Pa).
        - $ 1 Pa = 1 \frac {N} {m^2} $
3. O microfone converte o sinal sonoro (pressão sonora $P$), **no domínio do tempo**, em um sinal elétrico equivamente, com o **mesmo domínio do tempo**.
4. A **energia acústica da pressão sonora** ($P$) sofre conversão/transdução para a **energia vibracional/mecânica, dentro do microfone**.
    - **Depois se converte a energia mecânica vibracional, no microfone, em tensão elétrica, medida em volts (V)**, também neste dispositivo eletroacústico.
5. Mas o sinal elétrico gerado é baixo! Por isso, depois o microfone ainda faz uma **pré-amplificação do sinal elétrico**.
6. O sinal elétrico, depois desta transdução e depois desta pré-ampliação, e com o mesmo domínio de tempo da fonte acústica, está pronta para a **transmissão**.
    - O design do microfone pode ser feito para captar ondas menos direcionais ou para captar ondas mais direcionais. 

### Equipamento Gravador de Som
1. A cadeia do sistema de gravação começa no microfone que recepciona as pressão sonora fornecida pela fonte sonora.
2. O microfone, conforme indicado anteriormente, converte o sinal sonoro no domínio do tempo em um sinal elétrico equivamente, com o mesmo domínio de tempo.
    - O microfone:
        - possui um transdutor que faz tal conversão
        - faz uma pré-amplificação do sinal elétrico
        - Produz sinais elétricos equivalentes à pressão sonora, respeitando o domínio do tempo
3. **Mixagem em um Console**
4. **Conversão do sinal de Analógico para Digital**
5. **Processamento do sinal digital**
6. **Armazenamento de dados e/ou transmissão dos dados digitais**

### Equipamento Amplificador do Som
1. Recepção das Ondas Sonoras conforme indicado na recepção executada por microfones.
2. **Amplificação do sinal elétrico**
3. **Transmissnão do sinal amplificado**
    - Depois ocorre a recepção de som amplificado.

### Equipamento Processador do Sinal de Áudio
- Processamento dos sinais elétricos equivalentes do som.

### Equipamento de Transmissão do Som
- Processo de transmissão dos sinais elétricos equivalentes do som.

### Equipamento de Reprodução de Som
- Exemplos:
    - ***Alto-falantes***
    - ***Fones de ouvido***
1. Recebe ou recupera dados digitais de som compactados com codecs.
2. Processamento dos dados recebidos no equipamento de reprodução
    3. Decodifica os dados digitais em valores digitais que podem ser processados.
    3. Converte dados digitais decodificados para tensão elétrica analógica
4. Recebe tensão elétrica analógica, medida em volt (V).
2. Amplifica a potência do sinal
3. Converte tal tensão elétrica em energia vibracional ou mecânica, dentro do alto-falante.
5. Converte a energia vibracional em pressão sonora, medida em pascal (Pa).
    - 1 Pa = 1 N/metro_quadrado
6. Transmissão do som audível nas faixas de frequência de áudio entre 20Hz e 20KHz.
    - A pressão sonoral segue até alcançar objetos que sofrem com a pressão sonora.
    - Qualidade do som transmitido:
        - Apenas a localização nesta frequência não é suficiente para a qualidade do áudio.
        - O nível e atraso de tempo entre várias partes do espectro de áudio devem existir de uma forma que se gere qualidade.
        - Os sinais de áudio também precisam estar livres de ruído, de degradação de sinal, de distorção, em todos os níveis de pressão sonora de interesse para audição.
        - E as propriedades espaciais do ambiente também são relevantes para que não haja reverberação demasiada do som.

## Equipamentos de Medição Acústica:
- ***Microfone***
- ***Analisadores de espectro***
- ***Geradores de ruído***
- ***Medidores de nível de ruído***
- ***Osciloscópios***
- ***Medidores de Ruido e de Vibração***
    - Aplicações
    - Microfone
    - Acelerômetro
    - Giroscópio

## Elementos de um sistema acústico
- Compliância acústica
- Massa
- Resistência
- Transformador
- Gerador
