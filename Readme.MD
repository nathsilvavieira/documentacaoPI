
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
  
*** 
 ## Introdução

Este projeto avaliativo consiste em um Web App que foi desenvolvido utilizando metodologia scrum com 4 sprints de 2 semanas, orientado e supervisionado pela equipe de tutores com foco em agilidade, aplicação de conhecimentos técnicos, clima e cultura de trabalho. 

Nossa squad consiste em uma equipe com 6 pessoas, sendo 1 Lider de Front End Jennifer Mayumi, 1 Lider de Back End Nelson Kobayashi, 1 Lider de Infraestrutura Paulo Ventura, 1 Lider de Banco de Dados Nathalia Vieira, 1 Lider de Teste Andre Ribeiro e 1 FullStack Luiz Gustavo Trindade, que presta suporte a todas as frentes. 

Durante o processo de desenvolvimento do projeto precisamos solucionar inumeros problemas e romper algumas barreiras tanto técnicas como de softskills para criação de um Web App consistente. 

Alucar e um Web App de aluguel de carros online que conecta quem precisa alugar um carro com as melhores opções e preços do país, uma plataforma 100% segura que traz consigo a segurança e conforto necessário para utilização dos serviços oferecidos.

*** 

## Ferramenta Utilizadas

**Front End**
* *HTML + CSS + Javascript*
  * *SASS*
* *React*
  * *Node + NPM*
  
**Back End**
* *Java* 
  * *Spring* 
  * *Hibernete*
  * *Javadoc*
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
* *GitLab*
* *[Figma](https://www.figma.com/file/baMcKf0sEZ4UrZp3z9DIxB/Prot%C3%B3tipo---AluCar?node-id=448%3A9856)*

****

## Requisitos

### **Primeira Sprint**

* **Front End**

  * Template da página home responsive, que inclua header, buscador, categorias de forma funcional, lista de carros e footer, além de um bloco emergente de registro de login.


 ![Versção Desktop](https://user-images.githubusercontent.com/83051644/163721636-c88d9dd1-eeb0-45d2-959d-23b578422073.png)

* **Back End**

  * Expor uma API Rest que nos permita gerenciar as diferentes categorias de nossos carros, ou seja, a API deve nos permitir realizar operações CRUD. 
    -  [Link Javadoc](#)
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

:white_check_mark: Melhorar a Gestao do tempo;
 
:white_check_mark: Entregar maior valor para cliente;

:white_check_mark: Descentralizar tarefas;

:white_check_mark: Maior integração do grupo.


***

### **Segunda Sprint**

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

:white_check_mark: Planejamento da review, para entregar o real valor do produto para o cliente;

:white_check_mark: Adaptação dos requisitos;

:white_check_mark: Refatoração e aperfeiçoando do código para melhor desepenho.

:white_check_mark: Espírito de Equipe.

***

### **Terceira Sprint**

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
  
  * Criar testes unitários para páginas de reserva e confirmação de reserva usando JEST framework.
  * Executar teste exploratório das páginas de reserva e confirmação de reserva.
  * Desenvolver scripts de teste automatizados usando Postman para a API de produtos.
  * Continuar com as atividades de criação e execução de casos de teste manuais e testes estáticos.

* **Infraestrutura**
  
  * Fazer o deploy do código no servidor web EC2 na AWS;
  * Criar tabelas no RDS na AWS;
  * Adicionar imagens no Bucket AWS para gerar URL.
  
  

### Review - Lições aprendidas

:white_check_mark: Suporte das equipes transversais;

:white_check_mark: Determinação da equipe;

:white_check_mark: Trabalhar no planejamento para evitar sobrecarga de atividades;

:white_check_mark: Priorizar entregas essenciais;


### **Quarta Sprint**

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
    - 

* **Infraestrutura**
  
  * Criar uma URL para acesso ao site do Projeto Integrador. 
  
  
  

### Review - Lições aprendidas

:white_check_mark: 

:white_check_mark: 

:white_check_mark: 

:white_check_mark: 


## *Como utilizar nossa plataforma*

* Realizar clone do repositório;
* Abrir projeto na IDE VScode para executar o Front End;
* 
## *Referências*
*  [MDN](#)
*  [StackOverflow](#)
*  [YouTube](#)


## *Agradecimentos*

O Grupo agradece aos instrutores e colegas do curso Certified Tech Developer da *Digital House* em especial aos professores e instrutores Vitória Gonçalves que desempenhou o papel de Scrum Master, Matheus Mafra que atuou como nosso PO e também aos professores Sergio Silva, Renan Souza, Whesley Rimar,Tiago Gomes além dos assistentes Gabriel Rodrigues, Priscilla Souza, Janete Ferreira, Moises Vasconcellos e Nidio Dolfini que nos deram toda base e conhecimento técnico necessário para desenvolvermos todo o projeto integrador. 

Agradecemos também aos patrocinadores *Mercado Livre* e *Globant* por disponibilizar essas bolsas de estudo, que nos possibilitou a capacitação necessária para ingressar no mercado de trabalho. 

