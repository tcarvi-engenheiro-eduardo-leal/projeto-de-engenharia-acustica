# Eletroacústica
- Parte da engenharia que linda com conversões (transdução) entre:
    - Energia Mecânica,
    - Energia Elétrica e
    - Energia Acústica
- A análise da eletroacústica pode seguir dois padrões:
    - Padrão 1:
        - Análise da energia acústica pensada como ondas quantificadas com equações diferenciais.
        - Análise da energia elétrica pensada como formada por diferencial de potencial entre terminais de algum condutor que passam a ter diferença de potencial devido interações dos campos elétricos e magnéticos. Tais interações também são quantificadas, nesta forma de análise, por equações diferenciais.
    - Padrão 2:
        - Inspeciona-se visualmente o processo eletroacústico e se define um circuito que representa uma analogia com um circuito elétrico.
        - Vincula-se elementos acústicos ao circuito.
        - Resolve-se o circuito e se conclui a análise eletroacústica.

## Sistemas/Equipamentos de Acústica:

### Produtor de som
- Recebe uma tensão elétrica, medida em volt (V), e 
    - gera som que possui uma pressão sonora, medida em Pa.
    - O som produzido segue alcançando, pelo ar, objetos que recebem esta pressão.

### Equipamento Captador do Som (Microfones)
- Recepciona ***ondas sonoras que possuem frequência entre 20 Hz e 20 KHz***.
- Quando as ondas alcançam a superfície de captação do microfone, ocorre a ***geração de pressão sonora***.
    - A pressão sonora é medida em pascal (Pa).
        - $ 1 Pa = 1 \frac {N} {m^2} $
- O microfone converte o sinal sonoro ***no domínio do tempo*** em um sinal elétrico equivamente com o ***mesmo domínio de tempo***.
- No processo de conversão/transdução de energia no microfone, converte-se **a pressão sonora em energia vibracional ou mecânica, dentro do microfone.**
    - **Depois se converte a energia mecânica vibracional em tensão elétrica, medida em volt (V)**, também neste dispositivo eletroacústico.
- Mas o sinal elétrico gerado é baixo! Depois o microfone ainda faz uma **pré-amplificação do sinal elétrico**.
- O sinal elétrico, depois desta transdução e com o mesmo domínio de tempo da fonte acústica, está pronta para transmissão.
- O design do microfone pode ser feito para captar ondas menos direcionais ou para captar ondas mais direcionais. 

### Equipamento Gravador de Som
- A cadeia do sistema de gravação começa no microfone que recepciona as pressão sonora fornecida pela fonte sonora.
- O microfone converte o sinal sonoro no domínio do tempo em um sinal elétrico equivamente com o mesmo domínio de tempo.
- O microfone possui um transdutor que faz tal conversão que também faz uma pré-amplificação do sinal elétrico:
- Tendo ocorrido a produção sinais elétricos equivalentes, ocorre, respeitando o domínio do tempo:
    - Mixagem em um console
    - Conversão do sinal de Analógico para Digital
    - Processamento do sinal digital
    - Armazenamento de dados e/ou transmissão

### Equipamento Amplificador do Som
- Amplificação de som
- Microfones apresentam, em seu interior, amplificadores do sinal elétrico do som, por exemplo.

### Equipapmento Processador de Sinal de Áudio
- Processamento de sínal de áudio

### Equipamento de Transmissão do Som

### Equipamento de Reprodução de Som
- Exemplos:
    - ***Alto-falantes***
    - ***Fones de ouvido***
- Funcionamento:
        - Recepcão ou recuperação de dados 
        - Decodifica a recepção em valores digitais
        - Converte dados digitais para forma analógica
        - Processamento do sinal
        - Recebe tensão elétrica analógica, medida em volt (V).
        - Amplificador de potência
        - Converte tal tensão elétrica em energia vibracional ou mecânica, dentro do alto-falante.
        - Converte a energia vibracional em pressão sonora, medida em pascal (Pa).
            - 1 Pa = 1 N/metro_quadrado
        - Tal pressão sonoral segue até alcançar objetos que sofrem com a pressão sonora.
            - Transmissão do som audível ocorre nas faixas de frequência de áudio entre 20Hz e 20KHz.
            - Apenas a localização nesta frequência não é suficiente para a qualidade do áudio.
            - O nível e atraso de tempo entre várias partes do espectro de áudio devem existir de uma forma que gere qualidade.
            - Os sinais de áudio também precisam estar livres de ruído, de degradação de sinal, de distorção, em todos os níveis de pressão sonora de interesse para audição.
            - E as propriedades espaciais do ambiente também são relevantes para que não haja reverberação demasiada do som.

## Equipamentos de Medição Acústica:
- ***Microfone***
- ***Analisadores de esprectro***
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
