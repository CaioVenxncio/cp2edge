# cp2edge

## Projeto de Monitoramento Ambiental para Vinheria

### Equipe

#### Grupo: Engenheiros do Vinho

- *Caio Venancio* (RM: 556030)
- *David Cordeiro* (RM: 557538)
- *Tiago Morais* (RM: 555619)

### Protótipo

Link do protótipo feito no Wokwi:

https://wokwi.com/projects/397154685388460033

### Apresentação

Vídeo Showcase do projeto:

https://www.loom.com/share/08bde02dc8e8480bb432de9826cb21d8?sid=64c9a53c-f228-4de8-95ac-5bfa47a2ed30

### Descrição

Este projeto consiste em um sistema de monitoramento ambiental desenvolvido para a Vinheria Agnello, utilizando tecnologias como Arduino, sensor DHT11, display LCD e LEDs. O sistema foi projetado para medir e exibir informações de temperatura, umidade e luminosidade do ambiente, proporcionando um controle mais eficiente das condições ambientais na Vinheria.

### Funcionalidades Principais

- Medição da temperatura e umidade do ambiente utilizando o sensor DHT11;
- Exibição das informações de temperatura, umidade e luminosidade no display LCD;
- Indicação visual com LEDs e alerta sonoro com buzzer para alertar sobre condições críticas de temperatura, umidade e luminosidade;
- Ajuste automático da luminosidade dos LEDs de acordo com a iluminação ambiente.

### Implementação

O sensor DHT11 foi conectado ao Arduino Uno para realizar as medições de temperatura e umidade. O display LCD foi integrado ao Arduino para exibir as informações coletadas pelo sensor. Os LEDs foram utilizados para alertar visualmente em caso de condições críticas no ambiente.

A programação em linguagem C no Arduino foi essencial para controlar todos os componentes e garantir o funcionamento correto do sistema. O código foi documentado por meio de comentários no próprio algoritmo. Foram realizados testes para calibrar as escalas das unidades e, com isso, aumentar a precisão dos intervalos numéricos no código.

### Como Utilizar

Para utilizar o sistema, basta ligar o Arduino Uno e acompanhar as informações exibidas no display LCD e nos LEDs. Caso haja alguma condição crítica de temperatura, umidade ou luminosidade, os LEDs irão alertar visualmente e o buzzer alertará de forma sonora.

### Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para fazer um fork do projeto e enviar suas melhorias através de pull requests.

Esperamos que este projeto seja útil para a Vinheria e estamos disponíveis para futuras colaborações.

### Exibição do código

Abaixo, vídeo exibindo o código e o sistema:

https://github.com/CaioVenxncio/cp2edge/assets/161903325/b8a0bea9-dc8b-4f41-b454-6134b9d34b3d

### Sistema Monitorador de temperatura, luminosidade e umidade, com fornecimento de dados em uma tela LCD

### Materiais Utilizados:

- Arduino UNO
- Breadboard
- RTC DS1307
- Tela LCD 16X2
- LED's (verde, amarelo, vermelho)
- Sensor DHT22 (sensor de umidade)
- Sensor LDR (sensor de luminosidade)
- Buzzer
- Resistores
- Cabos Jumper

### Funções do Sistema:

- LED verde precisa estar ligado quando tudo estiver OK (luminoside, umidade e temperatura).
- A tela precisa mostrar a mensagem "Ambiente a meia luz", quando o LED amarelo ligar.
- Enquanto a temperatura estiver fora da faixa ideal, o LED amarelo precisa acender e o buzzer soar continuamente. 
- Enquanto a temperatura estiver fora do ideal, a tela deve aparecer "temperatura alta" ou "temperatura baixa" e mostrar o valor da temperatura.
- O buzzer também precisa soar, quando o LED vermelho ligar (soar continuamente).
- A tela precisa mostrar a mensagem "Ambiente muito claro", quando o LED vermelho ligar.
- Enquanto o ambiente estiver com temperatura entre 10°C e 15°C, a tela precisa mostrar "temperatura OK" e o valor da temperatura.
- Enquanto o ambiente estiver com a umidade entre 50% e 70%, a tela precisa mostrar "umidade OK" e o valor umidade.
- Os valores apresentados na tela precisam ser a média de pelo menos 5 valores medidos, mostrando a média a cada 5s.
- Enquanto a umidade estiver fora do ideal o LED vermelho deve acender e soar o buzzer (continuamente).
- Enquanto a umidade estiver fora da faixa ideal, a tela precisa mostrar "umidade baixa" ou "umidade alta" e mostrar os valores. 
<br>
Obrigado por utilizar nosso sistema de monitoramento ambiental!


