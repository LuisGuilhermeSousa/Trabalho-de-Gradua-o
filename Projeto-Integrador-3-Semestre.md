# Projeto 3: 2020-2 - VisGeo
![93688444-5704dc80-fa9c-11ea-8bed-fdac35ce7337](https://user-images.githubusercontent.com/56441318/138171757-052e48af-3a19-4e94-80d7-4174e54ae5a3.png)

### Parceiro Acadêmico
Visiona

### Visão do Projeto 
Neste projeto, tivemos a missão de fazer um projeto para a Visiona, uma joint-venture entre a Telebras e Embraer e com estímulo do Governo brasileiro, ela é uma empresa especializada em tecnologia espacial, realizando diversos serviços relacionados ao monitoramento e estudo via satélite.
A missão passada ao nosso grupo era desenvolver um sistema do tipo ETL(Extract Transform Load) web que fosse capaz de extrair arquivos georreferenciados de shapefiles, transformalos e carregá-los em um banco de dados geográfico, assim como o processo inverso de extrair diretamente do banco de dados.
Com isso, surgiu a VisGeo, um sistema de fácil manuseio pelo usuário, pensado em agilizar ao máximo esse processo de extração, transformação e carga de dados geográficos. Tudo isso em uma plataforma web segura e que presa pela segurança dos usuários.

### Funcionamento da Aplicação
A VisGEO surgiu com a finalidade de solucionar o problema proposto pelo nosso cliente, onde que, ele tinha a necessidade de ter um sistema ETL simples, intuitivo e de baixo custo. Com esse desafio em mãos, desenvolvemos uma aplicação web, na qual realiza uma extração de dados georreferenciados de shapefiles, transformando e carregando essas informações para um banco de dados geográfico.

A seguir temos a demonstração explicita de todas as funcionalidades da aplicação:

#### - Segurança:

Para a utilização de nossa ferramenta é necessário que todos os usuários sejam cadastrados e autenticados no sistema. 

![sem autenticação](https://user-images.githubusercontent.com/56441371/98485237-b3aa8b00-21f3-11eb-8004-bbd61514c6ef.gif)

Além disso, para se registrar e logar na aplicação utilizamos um token criptográfado, pois para nós a segurança de nossos usuários é prioridade.

![ezgif com-gif-maker](https://user-images.githubusercontent.com/56441371/98485048-70035180-21f2-11eb-909e-3cec1c97d671.gif)

#### - Usabilidade pensando na simplicidade:

Autenticação no banco de dados de maneira simples.

![upload](https://user-images.githubusercontent.com/55189046/93727271-ca881600-fb90-11ea-9664-bf09c9b0bae2.gif)

O usuário possui autonomia, pois com o sistema DE → PARA para a realização do upload dos shapefiles, ele decide o que será salvo.

![configuring](https://user-images.githubusercontent.com/55189046/93727270-c9ef7f80-fb90-11ea-83e5-c96e0ae2a0bc.gif)

E caso não seja necessário realizar a configuração do DE → PARA, pode-se enviar diretamente todas as informações para o banco de dados com apenas um clique

![salvando direto](https://user-images.githubusercontent.com/56441371/98487551-5964f680-2202-11eb-9386-2806fc1c0167.gif)

Conseguimos também facilmente, baixar todos os shapefiles salvos no banco de dados.

![sprint2](https://user-images.githubusercontent.com/56457600/100559745-7e450a80-3292-11eb-816b-b1cfe497f6ea.gif)


### link do git

[Clique aqui para acessar o repositório do projeto](https://github.com/justhenrique/VisGeo-ETL)

### Tecnologias adotadas na solução
![93688825-3c803280-fa9f-11ea-9408-bd07d27aad71](https://user-images.githubusercontent.com/56441318/138166339-caf4fded-d7d7-4bfb-a330-84ea3d9f594d.png)

- De acordo com os requisitos não funcionais levantados e alinhamento com nosso cliente, optamos por utilizar Java no CRUD de usuários.
- A API que trata do processo ETL foi desenvolvida em Python, com auxílio do Framework Flask, e das bibliotecas PyShp e postgresql.
- O front-end foi desenvolvido com React usando as bibliotecas Ant Design, Axios, Bootstrap, React-Bootstrap, React Icons e StyledComponents.
- Os arquivos shapefiles são carregados em Banco de Dados Postgres, utilizando a extensão para arquivos geográficos, PostGis.

### Contribuições pessoais 
Neste projeto fiquei responsável pelo front-end da aplicação, mais especificamente no desenvolvimento das telas de Login e cadastro, Visualização da carga de arquivos e do design  da aplicação utilizando a ferramenta Figma para fazer os primeiros protótipos de como seria a aparência e a usabilidade da aplicação.


### Aprendizados Efetivos - Soft Skills
Já com as soft skills, a grande novidade foi ter contato com uma empresa tão renomada em uma área totalmente desconhecida por nosso time, então tivemos um contato bem próximo, sempre enviando dúvidas e recebendo feedbacks sobre o andamento do projeto. Com relação a metodologia Scrum, apenas aperfeiçoamos o que já estava bem conhecido entre nosso time com entregas de valor priorizando sempre o mais útil para o nosso cliente.

### Aprendizados Efetivos - Hard Skills
Foi um excelente projeto para ter contato com arquivos e dados geográficos, nos quais nenhum dos integrantes do grupo havia trabalhado antes, então foi uma oportunidade muito boa para conhecer a extensão PostGis do banco de dados Postgree, específica para arquivos geográficos. Também foi o primeiro projeto que foi usado React no front-end, permitindo assim criar interfaces muito mais intuitivas e dinâmicas para o usuário, além de uma boa variedade de ferramentas como Python, Java e Docker usadas no back-end.

### Aprendizados Efetivos
- Linguagem Java - Sei fazer com ajuda
- Linguagem Python - Sei fazer com autonomia
- Flask - Sei fazer com ajuda
- Docker - Sei fazer com ajuda
- React - Sei fazer com ajuda
- Styled Components - Sei fazer com ajuda
