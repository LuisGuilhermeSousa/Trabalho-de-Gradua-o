# Projeto 2: 2020-2 - UDA Brasil

![udabrasil](https://user-images.githubusercontent.com/56441318/138007015-903b6f49-11ae-423f-a04f-fb109281f4bc.png)

### Parceiro Acadêmico

SPC Brasil

### Visão do Projeto 

Em um mundo onde dados os dados se tornaram algo extremamente valioso para as empresas, conseguir dados confiáveis está se tornando uma missão cada vez mais complexa. Conseguir os dados até pode ser uma tarefa fácil, dado à grande demanda que a internet proporciona, porém garantir que esses dados sejam confiáveis e que atendam padrões rigorosos é algo muito mais complexo.

Tendo em vista este problema, a empresa parceira SPC Brasil que é reconhecida nacionalmente por processar, armazenar e analisar milhões de operações de crédito todos os dias, foi responsável por passar essa missão para nossa equipe.

E assim surgiu a UDA Brasil, um sistema capaz de analisar a qualidade dos dados de uma remessa, avaliar se essa remessa possui dados íntegros e seguros, além de ser capaz de criar um ranking de todas as empresas fontes destes dados, classificando-as da mais confiável até a menos confiável.

### link do git

[Clique aqui para acessar o repositório do projeto](https://github.com/justhenrique/SPC-projeto-integrador)

### Tecnologias adotadas na solução

Durante a execução do projeto, utilizamos inúmeras tecnologias muito usadas no mercado, principalmente voltadas para a análise de dados 

HARDWARE

- **NodeMCU** - O microcontrolador NodeMCU é uma plataforma open-source para a criação de projetos *Internet of Things (Iot),* considerado o celebro físico do projeto, essa placa é responsável por enviar os sinais elétricos para os periféricos, receber e enviar dados via Wi-Fi e também receber a programação que faz tudo isso funcionar.
- Para os periféricos, simulando as luzes de uma residência, utilizamos alguns LED's convencionais e outros do tipo RGB, onde o usuário pode escolher a cor da luz do ambiente. Também utilizamos um cooler para simular o controle do sistema de climatização da casa.

### Circuito elétrico
![image](https://user-images.githubusercontent.com/56441318/133184318-2bcf21c5-4432-487e-b9dc-9ad8c569c268.png)

### Foto do protótipo
![image](https://user-images.githubusercontent.com/56441318/133184553-3908d44b-c6ee-4b59-950c-c2b0f51a6afb.png)

SOFTWARE

- **C++** - A linguagem de programação utilizada no projeto foi a C++. É uma linguagem multiplataforma que no projeto fui usada para fazer a programação da placa NodeMCU, controlando o recebimento de dados vindos do aplicativo (Blynk) e o envio de dados por meio físico para os periféricos.
- **Arduino IDE** - Ambiente de programação usado para o desenvolvimento do código. É muito usado em projetos de robótica e de Iot, sendo prático e funcional para a aplicação do projeto.
- **Blynk** - Aplicativo voltado para o desenvolvimento de aplicações Mobile voltadas para Iot. Nele, foi feito o desenvolvimento da interface usada pelo usuário para controlar todo o sistema, bem como receber e enviar dados das diversas funcionalidades do projeto.


![image](https://user-images.githubusercontent.com/56441318/133184068-aafd18a6-6ca8-4142-91ae-46e986157036.png)
Telas de navegação da aplicação

### Contribuições pessoais 

No desnvolvimente deste projeto fiquei encarregado das tarefas de montagem do circuito elétrico, ligando e testando os terminais da placa Node MCU, além de ficar responsável pela programação do algoritmo que controla toda a parte elétrica do projeto. O algoritmo era responsável por controlar como e quando os periféricos deveriam funcionar. Por último, também fui responsável por programar a interface do usuário para controlar todo o sistema. A interface consistia em um aplicativo desenvolvido na plataforma Blynk que fazia a comunicação com a placa e enviava os comandos do usuário por Wi-Fi, fazendo assim o sistema funcionar.

### Aprendizados Efetivos - Hard Skills

Com relação à parte técnica do projeto, considero que houve um crescimento muito grande com as tecnologias utilizadas, a grande maioria delas eu não havia tido a oportunidade de trabalhar antes, como a placa NodeMCU e a linguagem C++ para a programação. Em ambas, considero que hoje sei fazer com autonomia um novo projeto utilizando estas tecnologias, basta apenas dar uma pequena relembrada nos conceitos mais específicos, porém a base está bem consolidada.

### Aprendizados Efetivos - Soft Skills

O projeto foi uma ótima oportunidade para se introduzir na metodologia Scrum, com entregas de valor e separadas em Sprints. Todos do grupo nunca tinham trabalhado dessa forma, então foi um grande desafio para todos se adequar ao novo modelo. Na minha parte, acredito que o aprendizado foi muito efetivo, não só pelas Hard Skills das tecnologias novas, mas sim pelo novo modelo de trabalho Scrum, que com certeza será usado nos demais projetos da faculdade.

Todos os tópicos mostrados acima, considero-os como aprendizado efetivo e sei fazer com autonomia.
