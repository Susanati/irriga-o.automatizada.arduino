# irriga-o.automatizada.arduino
Irrigação Automatizada com Arduino.

Arduino é uma plataforma que possibilita o desenvolvimento de projetos eletrônicos. Em outras palavras, é uma plataforma de prototipagem eletrônica.
O Arduino é uma placa open-source. Sendo assim, toda a propriedade intelectual é compartilhada entre os usuários. Os usuários então compartilham soluções em códigos para aprimoramentos da plataforma.
A placa tem como principal componente o microcontrolador, que é um tipo de processador bem menor do que o convencional.
O microcontrolador executa os programas e avalia qualidade das entradas e saídas, ou seja, dos canais pelos quais é possível a comunicação entre mundo externo e digital.

Este projeto teve a finalidade de estudar o melhoramento da irrigação na agricultura. Para desenvolvimento tecnológico de atividades que podem ser melhoradas na realização com a automatização de irrigação com Arduino na cultura do Abacaxi.

O sistema automatizado de irrigação com Arduino tem como objetivo:
●      O desenvolvimento de um protótipo automatizado desenvolvido em um ambiente mecânico automatizado a baixo custo.
●      Sistema programado para controle de irrigação do solo.
●      Leitura da umidade do solo.
●      Automatização da decisão do disparo ou interrupção mecânica do processo de irrigação pelo dispositivo relé.
●      Controle funcional da saída de água, onde a água pode ser controlada pelo acionada do disparo do relé para liberação válvula solenoide efetuar a irrigação.
●      Com o solo totalmente irrigado e úmido o sistema vai desligar automaticamente e parar de irrigar solo.
●      Informações do processo de irrigação no decorrer do funcionamento sendo demonstrado no dispositivo display de LCD.
●      Coleta de dados em tempo real através de um sistema por um dispositivo seja ele web ou mobile através de uma comunicação wifi e rede internet.

O microcontrolador utlizado no projeto foi Placas Circuito Atmega328p.
Foi feito um ano de levantamento de peças e inicializando testes desde a humidade da terra, led, sensor de temperatura do solo e tempo de irrigação. Sua programação foi realizada o ide do arduino com linguagem em C com seguinte lógica : o sensor de humidade da terra contato que a terra estaria seca ele libera o rele para libera a bomba solenoide e em seguida a irrigação inicia, com a terra em 0 a 25% a terra estava estado de seca demostrando no lcd, após a medição desse sensor constante a humidade da terra 25 a 70% a terra está húmida demostrando no lcd e logo após a medição com resultado de 71 a 100% a terra estaria totalmente irrigada.
