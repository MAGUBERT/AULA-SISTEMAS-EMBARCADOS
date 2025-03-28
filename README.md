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
A pessoa que aparece na imagem pode estar ajustando o circuito ou verificando o funcionamento dos componentes.

É essencial seguir medidas de segurança ao lidar com tensões da rede elétrica.

A leitura de tensão depende da configuração correta do multímetro e de sua qualidade.

Esse tipo de montagem é bastante comum em experimentos e projetos com microcontroladores ou outros circuitos eletrônicos que necessitam de uma fonte de energia DC confiável e estável.

