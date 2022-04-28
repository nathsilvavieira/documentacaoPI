
# Projeto Integrador: Alucar

## Tópicos 
*   [Introdução](#introdução)
*   [Ferramenta Utilizadas](#ferramenta-utilizadas)
*   [Requisitos](#requisitos)
      - [Primeira Sprint](#primeira-sprint)
      - [Segunda Sprint](#segunda-sprint)
      - [Terceira Sprint](#terceira-sprint)
      - [Quarta Sprint](#quarta-sprint)
*   [Como utilizar nossa plataforma](#como-utilizar-nossa-plataforma)
*   [Referências](#referências)
*   [Agradecimentos](#agradecimentos)
*   [Conclusão](#conclusão)
  
*** 
 ## Introdução

Este projeto avaliativo consiste em um Web App que foi desenvolvido utilizando metodologia scrum com 4 sprints de 2 semanas, orientado e supervisionado pela equipe de tutores com foco em agilidade, aplicação de conhecimentos técnicos, clima e cultura de trabalho. 

Nossa squad consiste em uma equipe com 6 pessoas, sendo 1 Lider de Front End Jennifer Mayumi, 1 Lider de Back End Nelson Kobayashi, 1 Lider de Infraestrutura Paulo Ventura, 1 Lider de Banco de Dados Nathalia Vieira, 1 Lider de Teste Andre Ribeiro e 1 FullStack Luiz Gustavo Trindade, que presta suporte a todas as frentes. 

[Inclir imagem das forças e fortalezas do grupo]

Durante o processo de desenvolvimento do projeto precisamos solucionar inumeros problemas e romper algumas barreiras tanto técnicas como de softskills para criação de um Web App consistente. 

Alucar e um Web App de aluguel de carros online que conecta quem precisa alugar um carro com as melhores opções e preços do país, uma plataforma 100% segura que traz consigo a segurança e conforto necessário para utilização dos serviços oferecidos.

O objetivo do nosso projeto é desenvolver um  site funcional,  de simples manuseio pelos usuários que permita que nossos clientes e administradores naveguem de forma fácil e rápida, tendo acesso a todo histórico e registro de atividades. 

*** 

## Ferramenta Utilizadas

**Front End**
* *HTML + CSS + Javascript*
  * *SASS*
  * *FontAwesome*
* *React*
  * *Node + NPM*
  * *MUI*
  * *Popper*
  
**Back End**
* *Java* 
  * *Spring* 
  * *Hibernete*
  * *Javadoc*
  * *Swagger UI*
* *API*
  * *REST*
  * *JSON*

**Banco de Dados**
* *MYSQL*
* *Workbench*

**Testes**
* *Postman*
* *JUnit*
* *RobotFramework*

**Infraestrutura**
* *AWS*

**Gestão**
* *Git*
* *GitHub*
   - [FrontEnd](https://github.com/noubarijou/PICTDFEFinal)
   - [BackEnd I](https://github.com/noubarijou/PICTDBEFinal)
   - [BackEnd II](https://github.com/NelsonKobayashi/PICTDBE-FINAL)
   - [BackEnd III](https://github.com/NelsonKobayashi/ProjetoIntegradorBackendFinal)
* *GitLab*
* *[Figma](https://www.figma.com/file/baMcKf0sEZ4UrZp3z9DIxB/Prot%C3%B3tipo---AluCar?node-id=448%3A9856)*
* *[Metro](https://metroretro.io/)*

****

## Requisitos

### **Primeira Sprint**

Foi criado o design do Figma para o projeto, discutido identidade visual da empresa, desenvolvido um desenho da infraestrutura necessária, distribuído as atividades de cada responsável, planejados casos de testes iniciais, criado tabelas necessárias e feito uma página home responsiva. 

* **Front End**

  * Template da página home responsive, que inclua header, buscador, categorias de forma funcional, lista de carros e footer, além de um bloco emergente de registro de login.


 ![Versção Desktop](https://user-images.githubusercontent.com/83051644/163721636-c88d9dd1-eeb0-45d2-959d-23b578422073.png)

* **Back End**

  * Expor uma API Rest que nos permita gerenciar as diferentes categorias de nossos carros, ou seja, a API deve nos permitir realizar operações CRUD. 
  
  * Testar com Postman o funcionamento correto.

* **Banco Dados**
  
    * Criar uma base de dados em Mysql e a tabela “categorias” para persistir os dados de nosso sistema.
    
    ![Tabela Categorias](https://user-images.githubusercontent.com/83051644/163734538-920da244-756f-44ee-9f45-a6f943173520.png)


* **Testing**
  
  * Planejar Casos de Teste baseados nos requisitos do que será desenvolvido durante a Sprint;
  * Validar o funcionamento da API Rest criada durante a Sprint através do Postman e criar todos os scripts de testes pertinentes;
  * Executar os Casos de Teste que foram planejados inicialmente para a Sprint;
  * Fazer um teste exploratório sobre o que foi desenvolvido durante a Sprint.
    - [Link Casos de teste e teste exploratório](https://docs.google.com/spreadsheets/d/1jsBMA1GEZW0pySNQ8QNekEMqFCganpSo/edit#gid=1177918246)

* **Infraestrutura**
  
  * Criar repositório Gitlab e realizar o suporte dos integrantes do repositório;
    - [Gitlab Grupo 4](https://gitlab.com/projeto-integrador-brasil/turma1/projeto-integrador-v1.0_equipe4)
  * Criar esboço da rede necessária para execução do projeto (servidores, banco de dados e armazenamento).
  ![Desenho da Infraestrutura](https://user-images.githubusercontent.com/83051644/163735020-01ed08e6-413f-48ee-9492-8746969ac114.png)

  

### Review - Lições aprendidas

Discutimos os principais pontos impactantes da sprint nessa [review](https://metroretro.io/board/LBBWAPVY7Z4O) e obstaculos enfrentados, levantadas as seguintes lições aprendidas:

:white_check_mark: Melhorar a Gestao do tempo;
 
:white_check_mark: Entregar maior valor para cliente;

:white_check_mark: Descentralizar tarefas;

:white_check_mark: Maior integração do grupo.


***

### **Segunda Sprint**

Atualizamos o design no Figma e refatorado código, criado a infraestrutura no AWS, realizado os testes automatizados com as funcionalidades, desenvolvido os detalhes de produto no Front End e conectado as APIs do Back end, criada e populada as tabelas no Banco de Dados. 

* **Front End**

  * Criar tela de detalhe do produto;
  * Conexão APIs com a página Home;
  * Conexão APIs com a página detalhe do produto.
  
    ![Detalhes](https://user-images.githubusercontent.com/83051644/163899209-84dbc3ca-bc37-4c69-8b8b-2eb80d4cc53e.png)


* **Back End**

  * API de produtos: 
    - Criar produtos. 
    - Listar produtos por categoria. 
    - Listar produtos por cidade. 
    - Buscar produtos por id. 
    - Listar todos os produtos.
  
  * API de cidades:
    - Listar cidades.
    - Criar cidades

* **Banco Dados**
  
  * Criar tabela de produtos.
  * Criar tabela de cidades.
  * Criar tabela de características. 
  * Criar tabela de imagens.
  
  ![Tabelas e seus relacionamentos](https://user-images.githubusercontent.com/83051644/163896992-eab07e36-8b82-4881-b882-c90225d0a7c1.png)


* **Testing**
  
  * Teste com Robot Framework da página Home.
  * Teste com Postman das APIs.
      - [Robot Framework](https://drive.google.com/drive/folders/15-IEg0B6pF8142pZDrTCqOllywn5DTb9?usp=sharing)
      - [Casos de Teste](https://docs.google.com/spreadsheets/d/1jsBMA1GEZW0pySNQ8QNekEMqFCganpSo/edit?usp=sharing&ouid=103135306469444684787&rtpof=true&sd=true)

* **Infraestrutura**
  
  * Criar infraestrutura para hospedagem no AWS.
  
  

### Review - Lições aprendidas

Após implementado os pontos levantados na sprint anterior e demonstramos pontos fortes do grupo na [review](https://metroretro.io/board/LBT46JAZDG0H) abaixo:

:white_check_mark: Planejamento da review, para entregar o real valor do produto para o cliente;

:white_check_mark: Adaptação dos requisitos;

:white_check_mark: Refatoração e aperfeiçoando do código para melhor desepenho.

:white_check_mark: Espírito de Equipe.

***

### **Terceira Sprint**

Atualizado e refatorado todo código, criado as telas de reservas, desenvolvidas novas APIs e testadas, criadas e populadas novas tabelas no banco, além de feito deploy do código e adicionado imagens na AWS. 

* **Front End**

  * Tela de reserva.
  * Tela de confirmação de reserva.

* **Back End**

  * API de produtos:
    -  Consulta de produtos por cidade e por data.

  * API de reserva:

    -  Criar uma reserva;

    -  Verificar as reservas por produto.

  * API de usuários:

    - Registro;

    - Login com JWT.

* **Banco Dados**
  
  *  Tabela de reservas;

  *  Tabela de usuários; 

  *  Tabela de funções;

* **Testing**
  
  * Criar testes unitários para páginas de reserva e confirmação de reserva.
  * Executar teste exploratório das páginas de reserva e confirmação de reserva.
  * Desenvolver scripts de teste automatizados usando Postman para a API de produtos.
  * Continuar com as atividades de criação e execução de casos de teste manuais e testes estáticos.

* **Infraestrutura**
  
  * Fazer o deploy do código no servidor web EC2 na AWS;
  * Criar tabelas no RDS na AWS;
  * Adicionar imagens no Bucket AWS para gerar URL.
  
  

### Review - Lições aprendidas

Novos obstáculos foram identiifcados, a resiliência da equipe foi trabalhada, apesar de atrasos em algumas entregas devido a problemas identificados no código (funcionamento JWT) conseguimos realizar a entrega nesta penultima [review](https://metroretro.io/board/LB97BYK2B3LZ). 

:white_check_mark: Suporte das equipes transversais;

:white_check_mark: Determinação da equipe;

:white_check_mark: Trabalhar no planejamento para evitar sobrecarga de atividades;

:white_check_mark: Priorizar entregas essenciais;


### **Quarta Sprint**

Iniciamos essa sprint com a resolução das pendências da quarta sprint e finalização das funcionalidades de administrador e reservas na API e no Front End. Implementação dos testes automatizados e relatórios, finalização do banco de dados e criação da URL. 

* **Front End**

  * Página de administrador de produto. 
  * Página de reservas feitas pelo usuário.

* **Back End**

  * API de reservas:
    -  Filtrar por usuario.

  * API de produto:

    -  Modificar, buscar por id e listar todos.

  * API de usuários:

    - Registro;

    - Login com JWT.

* **Banco Dados**
  
  *  Entrega do DER do estado final da base de dados.
  
  ![DER](https://user-images.githubusercontent.com/83051644/163899652-dec5276f-1e53-4d8a-a4fa-f371252e3bda.png)


* **Testing**
  
  * Criar e executar testes unitários utilizando JEST sobre as funcionalidades da página de reservas (realizadas por usuários) e sobre a página formulário de produto (a que se ingressa com perfil de administrador). 
  * Realizar e registrar o testing exploratório sobre as funcionalidades da página de reservas e sobre a página formulário de produto. 
  * Executar os casos de testes que pertencem à suite de regressão e gerar um relatório final de testes. 
  * Adicionar à coleção de Postman scripts automatizados para testar os métodos  agregados neste sprint. 
  * Criar um script relacionado a ambas páginas em testes de regressão automatizados criados com Selenium Web Driver / JEST.
    - [Casos de Teste](https://docs.google.com/spreadsheets/d/1jsBMA1GEZW0pySNQ8QNekEMqFCganpSo/edit?usp=sharing&ouid=103135306469444684787&rtpof=true&sd=true)
    - [Teste Exploratório](https://docs.google.com/spreadsheets/d/1jsBMA1GEZW0pySNQ8QNekEMqFCganpSo/edit#gid=1694370201)

* **Infraestrutura**
  
  * Criar uma URL para acesso ao site do Projeto Integrador. 
   

### Review - Lições aprendidas

Finalizamos o projeto com muitas lições aprendidas, pudemos simular o ambiente de trabalho, lidamos com desafios de hard skills e softskills além de rotacionarmos nas funções. 

:white_check_mark: Desenvolvemos autogerenciamento de ativades. 

:white_check_mark: Habilidades de comunição.

:white_check_mark: Aprendemos a lidar com conflitos. 

:white_check_mark: Rotacionamento de atividades. 


## *Como utilizar nossa plataforma*

### **Front End**

* Realizar clone do repositório;
* Abrir projeto na IDE VScode para executar o Front End;
* Abrir terminal no VScode e executar comando git checkout Frontend;
* Excutar comando npm install;
* Executar comendo npm start. 

### **Back End**
* Realizar clone do repositório;
* Abrir projeto na IDE Intellij para executar o Back End;
* Abrir terminal no VScode e executar comando git checkout Backend;
* Excutar com comando Run ou Shift+F10.
 


## *Referências*
*  [MDN - React](https://developer.mozilla.org/pt-BR/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/React_getting_started)
*  *StackOverflow*
    - [StackOverflow-React](https://stackoverflow.com/questions/59144633/i-am-getting-an-error-of-html-webpack-plugin-in-reactjs)
    - [CORS issue on Swagger UI](https://stackoverflow.com/questions/32480934/cors-issue-on-swagger-ui)
*  [Como usar o Fontawesome](https://www.digitalocean.com/community/tutorials/how-to-use-font-awesome-5-with-react-pt)
*  *Youtube*
    - [Datepicker](https://www.youtube.com/watch?v=iYZryimRK9w)
    - [Traversy Media](https://www.youtube.com/channel/UC29ju8bIPH5as8OGnQzwJyA)
    - [Autenticação JWT com React Router](https://www.youtube.com/watch?v=AClyxTbfI08)
    - [Tutorial: Como criar um token JWT com Java, Spring Boot, Spring Security e JPA](https://www.youtube.com/playlist?list=PLTN1gMq8EHuIpxyecEp04TvLr3TQbzMRL)
    - [Protegendo sua aplicação Java com Spring Security](https://www.youtube.com/watch?v=FOX0r52_hwE)
    - [Autenticação JWT com Spring Security](https://www.youtube.com/watch?v=idnwOWqUsEQ)
    - [API REST com Spring Boot - parte 5: Swagger](https://www.youtube.com/watch?v=HX4lheDqoiA)
    - [Como fazer testes automatizados em JS](https://www.youtube.com/watch?v=8hxhZkBzWhk)
*  [React](https://pt-br.reactjs.org/tutorial/tutorial.html)
*  [React Hooks JWT Authentication ](https://www.bezkoder.com/react-hooks-jwt-auth/)
*  [Spring Boot Token based Authentication with Spring Security & JWT](https://www.bezkoder.com/spring-boot-jwt-authentication/)
*  [MUI - React UI](https://mui.com/pt/material-ui/getting-started/learn/)
*  [IQcode](https://iqcode.com/code/javascript/yup-validate-password-confirmation)
*  *NPM*
    - [Datepicker](https://www.npmjs.com/package/react-datepicker)
    - [ReactDatepicker](https://reactdatepicker.com/#example-date-range)
    - [Popper](https://popper.js.org/docs/v2/tutorial/)
*  [CRUD Operations using MySQL Database](https://www.geeksforgeeks.org/spring-boot-crud-operations-using-mysql-database/)
*  [CTD SummerWeek Spring Security](https://github.com/gabriel-srodrigues/security-summer-week)
*  [SpringSecurity](https://glysns.gitbook.io/springframework/spring-security/untitled)
*  [Swagger Cors](https://swagger.io/docs/open-source-tools/swagger-ui/usage/cors/)
*  [Como Gerar Javadoc](https://www.impacta.com.br/blog/como-gerar-javadoc-no-eclipse/)
*  [Spring Boot + Spring Security + JWT + MySQL + React Full Stack Polling App - Part 1](https://www.callicoder.com/spring-boot-spring-security-jwt-mysql-react-app-part-1/)
*  [Spring Boot + Spring Security + JWT + MySQL + React Full Stack Polling app - Part 2](https://www.callicoder.com/spring-boot-spring-security-jwt-mysql-react-app-part-2/)
*  [Summerweek Docker](https://nidio.notion.site/nidio/Summerweek-Docker-833ae2c08a994a81a7f0892673ee7dce)
*  [21 Days of AWS using Terraform — Day 8- Introduction to AWS RDS MySQL using Terraform](https://devopslearning.medium.com/21-days-of-aws-using-terraform-day-8-introduction-to-aws-rds-mysql-using-terraform-d92ce1c52438)
*  [Deploy de Aplicação Java na AWS](https://www.linkedin.com/pulse/deploy-de-aplica%25C3%25A7%25C3%25A3o-java-na-aws-tiago-perroni/?trackingId=G%2FyjmH%2FxSniHGyvFUYbrLw%3D%3D)
*  [W3SHOOL-SQL](https://www.w3schools.com/sql/sql_alter.asp)
*  [Capitais do Brasil](https://www.todamateria.com.br/capitais-do-brasil/)
*  [Documentação Robotframework](https://github.com/robotframework/robotframework/blob/master/doc/releasenotes/rf-5.0.rst)
*  [Testes automatizados Selenium](https://www.devmedia.com.br/testes-automatizados-com-o-framework-selenium/32955)
*  [Testes React](https://create-react-app.dev/docs/running-tests/)
*  [Playground](https://br-playground.digitalhouse.com/login)


## *Agradecimentos*

O Grupo agradece aos instrutores e colegas do curso Certified Tech Developer da *Digital House* em especial aos professores e instrutores Vitória Gonçalves que desempenhou o papel de Scrum Master, Matheus Mafra que atuou como nosso PO e também aos professores Sergio Silva, Renan Souza, Whesley Rimar,Tiago Gomes além dos assistentes Gabriel Rodrigues, Priscilla Souza, Janete Ferreira, Moises Vasconcellos e Nidio Dolfini que nos deram toda base e conhecimento técnico necessário para desenvolvermos todo o projeto integrador. 

Agradecemos também aos patrocinadores *Mercado Livre* e *Globant* por disponibilizar essas bolsas de estudo, que nos possibilitou a capacitação necessária para ingressar no mercado de trabalho. 

## *Conclusão*

Nosso projeto tem cunho educativo que visa simular o ambiente de trabalho, foi implementado nesse bimestre conceitos aprendidos durante esses 9 meses de curso consultando além dos materiais disponibilizados e colaboração dos tutores e colegas de turma. 

