# Trabalho de Graduação

 

## Projeto 1: 2019-2 - SIGMA - Sistema Inteligente de Gerenciamento Manual de Ambiente

![Untitled](https://user-images.githubusercontent.com/56441318/132886130-f3f8a69e-8222-433c-8654-af9d656dccc6.png)

### Parceiro Acadêmico

Fatec São José dos Campos - Prof. Jessen Vidal

### Visão do Projeto (Equipe)

Das inúmeras evoluções tecnológicas que tivemos desde o início deste milênio, a internet sem sombra de dúvidas foi um dos adventos mais importantes da humanidade. Com ela, fomos capazes de conectar pessoas pelo globo, facilitar o acesso ao conhecimento, criar novas formas de entretenimento, além de criar uma nova forma das pessoas se comunicare. A partir desse ponto, a evolução foi crescendo a cada ano em uma escala nunca antes vista.

Nesta última década de 2010, uma das inovações mais avançadas e que promete mudar a vida das pessoas, é o desenvolvimento da chamada "Internet das coisas". Uma forma de conectar objetos que antes, nunca foram pensados em serem conectador, agora estarão todos ligados e compartilhando informações. Desde utensílios domesticos como geladeiras e máquinas de lavar, até mesmo acessórios vestíveis como relógios e anéis. Desde então, surgiu a necessidade de se conectar a casa inteira em uma única interface, a fim de fascilitar a usabilidade e o controle de todos estes dispositivos conectados.

Assim surgiu a ideia do SIGMA (Sistema Inteligente de Gerencialmento Manual de Ambiente) de criar uma plataforma onde o usuário tem todo o controle de sua residência na palma da sua mão, por meio de um aplicativo mobile. Com ele o usuário pode:

- Controlar a iluminação ambiente
- Controlar o sistema de climatização de sua residência
- Ter uma interface para monitorar tudo
- Ter um controle energético mais eficiente
- Ter mais segurança

O SIGMA veio para fascilitar e otimizar esse controle a fim de oferecer uma intereface que permite o usuário ter o controle de tudo na palma da mão.

### link do git

[https://github.com/LuisGuilhermeSousa/sigma-sistema-inteligente-de-gerenciamento-manual-de-ambiente](https://github.com/LuisGuilhermeSousa/sigma-sistema-inteligente-de-gerenciamento-manual-de-ambiente)

### Tecnologias adotadas na solução (Equipe)

Duruante a execução do projeto, utilizamos inumeras tecnologias muito usadas no mercado, tanto no hardware, quanto no software. 

HARDWARE

- **NodeMCU** - O microcontrolador NodeMCU é uma plataforma open-source para a criação de projetos *Internet of Things (Iot),* considerado o celebro físico do projeto, essa placa é responsável por enviar os sinais elétricos para os periféricos, receber e enviar dados via Wi-Fi e também receber a programação que faz tudo isso funcionar.
- Para os periféricos, simulando as luzes de uma residencia, utilizamos alguns LED's convencionais e outros do tipo RGB, onde o usuário pode escolher a cor da luz do ambiente. Também utilizamos um cooler para simular o controle do sistema de climatização da casa.

### Circuito elétrico
![image](https://user-images.githubusercontent.com/56441318/133184318-2bcf21c5-4432-487e-b9dc-9ad8c569c268.png)

### Foto do protótipo
![image](https://user-images.githubusercontent.com/56441318/133184553-3908d44b-c6ee-4b59-950c-c2b0f51a6afb.png)

SOFTWARE

- **C++** - A linguagem de programação utilizada no projeto foi a C++. É uma linguagem multiplataforma que no projeto fui usada para fazer a programação da placa NodeMCU, controlando o recebimento de dados vindos do aplicativo (Blynk) e o envio de dados por meio físico para os periféricos.
- **Arduino IDE** - Ambiente de programação usado para o desenvolvimento do código. É muito usado em projetos de robótica e de Iot, sendo prático e funcional para a aplicação do projeto.
- **Blynk** - Aplicativo voltado para o desenvolvimento de aplicações Mobile voltadas para Iot. Nele, foi feito o desenvolvimento da interface usada pelo usuário para controlar todo o sistema, bem como receber e enviar dados das diversas funcionalidades do projeto.

![image](https://user-images.githubusercontent.com/56441318/133183938-8cefeee0-cdfc-493f-84d2-024b75aae4aa.png)

Tela de login da aplicação


-
![image](https://user-images.githubusercontent.com/56441318/133184068-aafd18a6-6ca8-4142-91ae-46e986157036.png)
Telas de navegação da aplicação

### Contribuições pessoais (Individual)

No desemvolvimente deste projeto fiquei encarregado das tarefas de montagem do circuito elétrico, ligando e testando os terminais da placa Node MCU, além de ficar responsável pela porgramação do algoritmo que controla toda a parte elétrica do projeto. O algoritmo era responsável por controlar como e quando os periféricos deveriam funcionar. Por último, também fui responsável por programar a interface do usuário para controlar todo o sistema. A interface consistia em um aplicativo desenvolvido na plataforma Blynk que fazia a comunicação com a placa e enviava os comandos do usuário por Wi-Fi, fazendo assim o sistema funcionar.

### Aprendizados Efetivos HS (Individual)

O projeto foi uma ótima oportunidade para se introduzir na metodologia Scrum, com entregas de valor e separadas em Sprints. Todos do grupo nunca tinham trabalhado dessa forma, então foi um grande desafio para todos se adequar ao novo modelo. Na minha parte, acredito que o aprendizado foi muito efetivo, não só pelas Hard Skills das tecnologias novas, mas sim pelo novo modelo de trabalho Scrum, que com certeza será usado nos demais projetos da faculdade.

Todos os tópicos mostrados acima, considero-os como aprendizado efetivo e sei fazer com autonomia.
