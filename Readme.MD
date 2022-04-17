
# Projeto Integrador: Alucar

## Tópicos 
*   [Introdução](#introdução)
*   [Ferramenta Utilizadas](#ferramenta-utilizadas)
*   [Requisitos](#Requisitos)
*   [Como utilizar nossa plataforma](#)
*   [Referências](#)
*   [Agradecimentos](#)
  
*** 
 ## Introdução

Este projeto avaliativo consiste em um Web App que foi desenvolvido utilizando metodologia scrum com 4 sprints de 2 semanas, orientado e supervisionado pela equipe de tutores com foco em agilidade, aplicação de conhecimentos técnicos, clima e cultura de trabalho. 

Nossa squad consiste em uma equipe com 6 pessoas, sendo 1 Lider de Front End Jennifer Mayumi, 1 Lider de Back End Nelson Kobayashi, 1 Lider de Infraestrutura Paulo Ventura, 1 Lider de Banco de Dados Nathalia Vieira, 1 Lider de Teste Andre Ribeiro e 1 FullStack Luiz Gustavo Trindade, que presta suporte a todas as frentes. 

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

****

## Requisitos

### **Primeira Sprint**

* **Front End**

  * Template da página home responsive, que inclua header, buscador, categorias de forma funcional, lista de carros e footer, além de um bloco emergente de registro de login.


 ![Versão Mobile](https://user-images.githubusercontent.com/83051644/163721550-751d8c3d-7b45-4c2b-8ad9-5837f33262e5.png)
 ![Versção Desktop](https://user-images.githubusercontent.com/83051644/163721636-c88d9dd1-eeb0-45d2-959d-23b578422073.png)

* **Back End**

  * Expor uma API Rest que nos permita gerenciar as diferentes categorias de nossos carros, ou seja, a API deve nos permitir realizar operações CRUD. 
  * Testar com Postman o funcionamento correto.

* **Banco Dados**
  
    * Criar uma base de dados em Mysql e a tabela “categorias” para persistir os dados de nosso sistema. 

* **Testing**
  
  * Planejar Casos de Teste baseados nos requisitos do que será desenvolvido durante a Sprint;
  * Validar o funcionamento da API Rest criada durante a Sprint através do Postman e criar todos os scripts de testes pertinentes;
  * Executar os Casos de Teste que foram planejados inicialmente para a Sprint;
  * Fazer um teste exploratório sobre o que foi desenvolvido durante a Sprint.

* **Infraestrutura**
  
  * Criar repositório Gitlab e realizar o suporte dos integrantes do repositório;
  * Criar esboço da rede necessária para execução do projeto (servidores, banco de dados e armazenamento).
  

### Lições aprendidas

> Melhorar a Gestao do tempo;
> 
> Entregar maior valor para cliente;
>
> Descentralizar tarefas;
>
> Maior integração do grupo.


***

### **Segunda Sprint**

* **Front End**

  * Criar tela de detalhe do produto;
  * Conexão APIs com a página Home;
  * Conexão APIs com a página detalhe do produto.

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

* **Testing**
  
  * Teste com Robot Framework da página Home.
  * Teste com Postman das APIs.

* **Infraestrutura**
  
  * Criar infraestrutura para hospedagem no AWS.
  
  

### Lições aprendidas

> Planejamento da review, para entregar o real valor do produto para o cliente;
> 
> Adaptação dos requisitos;
>
> Refatoração e aperfeiçoando do código para melhor desepenho.
> 
> Espírito de Equipe.

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

  * Tabela de funções;

* **Testing**
  
  * Criar testes unitários para páginas de reserva e confirmação de reserva usando JEST framework.
  * Executar teste exploratório das páginas de reserva e confirmação de reserva.
  * Desenvolver scripts de teste automatizados usando Postman para a API de produtos.
  * Continuar com as atividades de criação e execução de casos de teste manuais e testes estáticos.

* **Infraestrutura**
  
  * Fazer o deploy do código no servidor web EC2 na AWS;
  * Criar tabelas no RDS na AWS;
  * Adicionar imagens no Bucket AWS para gerar URL.
  
  

### Lições aprendidas

> Suporte das equipes transversais;
> 
> Determinação da equipe;
>
> Trabalhar no planejamento para evitar sobrecarga de atividades;
> 
> Priorizar entregas essenciais;


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

* **Testing**
  
  * Criar e executar testes unitários utilizando JEST sobre as funcionalidades da página de reservas (realizadas por usuários) e sobre a página formulário de produto (a que se ingressa com perfil de administrador). 
  * Realizar e registrar o testing exploratório sobre as funcionalidades da página de reservas e sobre a página formulário de produto. 
  * Executar os casos de testes que pertencem à suite de regressão e gerar um relatório final de testes. 
  * Adicionar à coleção de Postman scripts automatizados para testar os métodos  agregados neste sprint. 
  * Criar um script relacionado a ambas páginas em testes de regressão automatizados criados com Selenium Web Driver / JEST.

* **Infraestrutura**
  
  * Criar uma URL para acesso ao site do Projeto Integrador. 
  * Criar Pipeline em Terraform para automatização 
  
  

### Lições aprendidas







