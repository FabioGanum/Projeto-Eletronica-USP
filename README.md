# Projeto-Eletronica-USP
## Pojeto para a disciplina Eletrônica para Computação na USP
### Instruções:
O projeto consiste na criação de uma *fonte de tensão ajustável*, entre 3V e 12V e com capacidade de 100mA.

### Componentes:
| Componentes   | Quantidade    | Valor |
| ------------- |:-------------:| -----:|
| transistor    | 1 | R$1600 |
| Diodo 1N4001      | 1      |   R$12 |
| Capacitor 560uF | 1      |   R$1 |
|Led Vermelho 5mm | 1| R$
| Resistor 1k ohm | 1| R$
| Resistor 120 ohm | 1| R$
| Resistor 2.2k |1 | R$
| Potenciômetro 5k | 1| R$
| Diodo Zener (13v) | 1| R$
| Transistor NPN | 1| R$
| Transformador |1 | R$
| Fusível |1 | R$
| Varistor | 1| R$
| Total |1 | R$ 0,0

### Descricao dos componentes: 

* Fusível: É um dos primeiros dispositivos de proteção no circuito. Sua função é interromper a passagem de corrente elétrica quando esta ultrapassa um valor seguro, evitando danos aos outros componentes em caso de picos de corrente.

- Varistor: Trabalha em conjunto com o fusível para proteger o circuito contra surtos de tensão. Quando há uma sobretensão na rede, o varistor atua rapidamente, absorvendo o excesso e evitando que ele chegue aos demais componentes.

- Transformador: Posicionado logo após a entrada da corrente alternada (tomada), é responsável por reduzir a tensão de 127V para um valor mais compatível com os requisitos do projeto — entre 3V e 12V. No caso deste circuito, foi escolhido um transformador que converte 110V para 12V.

  * Observação: O transformador não altera o tipo de corrente — a saída ainda é corrente alternada, apenas com menor tensão.

- Ponte de Diodos: Após a transformação da tensão, a ponte de diodos entra em ação para realizar a retificação da corrente alternada. Ela permite que o circuito aproveite ambos os semiciclos da AC, convertendo-a em corrente contínua pulsante.  

- Capacitor: Entra após a retificação, com o objetivo de suavizar a tensão pulsante. Ele armazena carga nos picos e libera durante as quedas, mantendo uma tensão mais estável. Para um ripple de 10%, foi calculado um valor de 458μF, sendo utilizado um capacitor comercial próximo, de 470μF.

- Diodo Zener: Atua como regulador de tensão. Ele só conduz quando a tensão atinge seu valor nominal — 12V neste projeto. Abaixo disso, permanece inativo. Quando a tensão ultrapassa 12V, ele entra em condução, estabilizando a tensão nesse valor, impedindo que a saída ultrapasse o limite desejado.

- Transistor: Utilizado como um elemento de controle de corrente, permite ajustar a quantidade de corrente que passa pelo circuito, tornando a regulação mais precisa e eficiente.

- Potenciômetro: Serve para ajustar manualmente a tensão de saída, funcionando como um resistor variável. Ele possibilita a variação da tensão final entre 3V e 12V, conforme a necessidade do usuário.

- Resistores: Distribuídos estrategicamente ao longo do circuito, têm a função de limitar a corrente e garantir que ela se mantenha dentro dos níveis seguros para os demais componentes.

### Imagem do Circuito:

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

### Cálculo capacitor:

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

### Link do Circuito no Falstad

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

### Imagem esquemático da PCB:

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

### Imagem PCB no programa Proteus:

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

### Video no Youtube:

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

### Alunos:

Fabio Ganum Filho  
Rafaela Dãmaso Breseghello
