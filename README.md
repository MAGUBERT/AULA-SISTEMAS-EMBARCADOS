# AULA-SISTEMAS-EMBARCADOS
 Aula RAFA

O esquema apresentado no Proteus representa uma fonte de alimentação com retificação de onda completa, filtragem e regulação de tensão. Abaixo, está a descrição dos componentes e suas respectivas funções:

TR1 – Transformador
Responsável por reduzir a tensão da rede elétrica (como 110V ou 220V AC) para um nível inferior adequado ao circuito.

BR1 – Ponte Retificadora
Converte a tensão alternada (AC) proveniente do transformador em tensão contínua (DC), utilizando diodos.

C1 – Capacitor
Tem como função reduzir a ondulação da tensão após a retificação. Ele armazena energia durante os picos e a libera nas quedas, ajudando a manter a tensão mais estável.

U1 – Regulador de Tensão
Mantém a tensão de saída constante em 5V, mesmo que haja variações na tensão de entrada.

R1 – Resistor
Limita a corrente elétrica que passa pelo LED, protegendo-o contra sobrecarga.

LED
Serve como indicador visual de que o circuito está funcionando corretamente.

![image](https://github.com/user-attachments/assets/9af01afd-8ff2-44d5-8ea7-94446915280d)

![image](https://github.com/user-attachments/assets/8214763b-59b6-4e4a-b4b5-5511116c8d0a)

Esse é um circuito simples e muito utilizado como fonte de alimentação regulada para dispositivos eletrônicos que operam com tensão contínua de 5V.

Explicação dos Componentes na Protoboard:
O circuito está montado em uma protoboard, que permite a criação de protótipos sem necessidade de solda, facilitando testes e modificações.

Transformador: Reduz a tensão da rede elétrica para um nível mais baixo, permitindo o uso seguro no circuito.

Diodos: Formam a ponte retificadora que converte a corrente alternada (AC) em corrente contínua (DC).

Capacitores: Suavizam as oscilações da tensão após a retificação, resultando em uma saída mais estável.

Resistores: Utilizados para limitar corrente ou como divisores de tensão.

LEDs: Indicadores de funcionamento do circuito.

![image](https://github.com/user-attachments/assets/030e3cd1-f480-4333-964b-53ac1b434d7d)


Processo de Funcionamento:
Transformação de Tensão: O transformador converte a alta tensão da rede elétrica em uma tensão AC reduzida, entre 9V e 12V, por exemplo.

Retificação: A ponte retificadora transforma essa tensão AC reduzida em uma tensão contínua pulsante.

Filtragem: Um capacitor eletrolítico suaviza essa tensão, tornando-a mais contínua e apropriada para componentes eletrônicos.

Regulação: Caso exista um regulador de tensão (como o 7805), ele estabiliza a saída exatamente em 5V.

Medição: Um multímetro digital, ajustado para medir tensão contínua (DC), mostra o valor da saída. Por exemplo, uma leitura de 7.5V indica que o circuito está funcionando corretamente após transformação, retificação e filtragem, mesmo sem regulador.

![image](https://github.com/user-attachments/assets/62cdb55b-4e87-4e8c-8180-41212d3932c5)

Observações Finais:

É essencial seguir medidas de segurança ao lidar com tensões da rede elétrica.

A leitura de tensão depende da configuração correta do multímetro e de sua qualidade.

Esse tipo de montagem é bastante comum em experimentos e projetos com microcontroladores ou outros circuitos eletrônicos que necessitam de uma fonte de energia DC confiável e estável.

![image](https://github.com/user-attachments/assets/38ffcf67-ca2a-454f-8ff1-1887750a7b0d)

![image](https://github.com/user-attachments/assets/db02ac55-d359-4511-b658-dd0114049802)

![image](https://github.com/user-attachments/assets/d918947e-0271-48e9-b1c7-0121a6e9cfaa)

![image](https://github.com/user-attachments/assets/4a046c45-acc4-4f77-8c8e-74bca0608386)

![image](https://github.com/user-attachments/assets/5c67de9e-ce02-4011-932f-4e35c0f98dde)

 1. Objetivo do circuito
O objetivo principal desse circuito é converter uma tensão alternada (AC) em uma tensão contínua (DC) estabilizada em 5 volts

 2. Componentes principais e suas funções

 J1 – Conector de Entrada
É o ponto onde você conecta a tensão AC vinda de um transformador.

 BR1 – Ponte Retificadora
Converte a tensão alternada (AC) em contínua pulsante (DC).

 C1 (1µF) – Capacitor Eletrolítico
Realiza a filtragem inicial da tensão retificada.

 C2 e C3 (22nF) – Capacitores de Desacoplamento
Filtram ruídos de alta frequência no circuito.

 U1 – Regulador de Tensão 7805
Regula a tensão de entrada para uma saída constante de 5V.

 R1 – Resistor de 220 ohms
Limita a corrente que passa pelo LED.

 D1 – LED Vermelho
Indicador visual de funcionamento. Quando aceso, mostra que a saída de 5V está presente.

 J2 – Conector de Saída
É por onde você conecta a carga que será alimentada com 5V.

 3. Placa de circuito impresso (layout)
Nas imagens seguintes, é possível ver:

O layout da PCB tem como medidas de 50mm x 30mm.

A visualização 3D mostra o projeto finalizado.

Trilha da parte de baixo da placa conectando todos os pontos corretamente.

Resumo
Este é um projeto de fonte de alimentação linear regulada com 5V de saída, ideal para bancadas de testes, projetos com Arduino ou qualquer outro circuito de baixa potência que precise de 5V.




