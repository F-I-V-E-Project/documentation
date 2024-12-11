# F-I-V-E-Project

## Descrição

Este projeto se trata de uma biblioteca virtual que tem como objetivo permitir um melhor gerenciamento de livros por parte dos funcionários da instituição que o aderir, e visualização da disponibilidade dos livros por parte dos clientes, tornando assim, mais fácil a vida tanto dos trabalhadores docentes quanto dos clientes.
Escolhemos seguir o padrão de projeto Factory pois vimos que se adequava a proposta do projeto e os integrantes já estavam um pouco familiarizados com este padrão

## Funcionalidades implementadas

O funcionário pode tanto adicionar, excluir, visualizar e editar tanto Clientes, Funcionários e Livros do sistema

O cliente pode pagar suas multas, vizualizar uma lista dos livros, pegar livros emprestado e devolvelos

## Índice

1. [Objetivos do Projeto](#objetivo)
2. [Definições, Acrônimos e Abreviações](#definições-acrônimos-e-abreviações)
3. [Requisitos](#requisitos)
   1. [Requisitos Funcionais](#requisitos-funcionais)
   2. [Requisitos Não Funcionais](#requisitos-não-funcionais)
4. [Diagramas UML](#diagramas-uml)
   1. [Personas](#personas)
   2. [Diagrama de Casos de Uso](#diagrama-de-casos-de-uso)
   3. [Diagrama de Classe](#diagrama-de-classe)
5. [Estrutura do Projeto](#estrutura-do-projeto)
6. [Licença](#licença)
7. [Contato](#contato)

## Definições, Acrônimos e Abreviações.
▪ CRUD - Acrônimo de Create, Read, Update, Delete.

▪ GitHub - Plataforma de hospedagem de código-fonte usando o sistema de controle de versão Git.

▪ MIT - Massachusetts Institute of Technology.

▪ MySQL - Sistema de gerenciamento de banco de dados relacional de código aberto, amplamente usado para armazenar dados em aplicativos.

▪ MySQLWorkbench: Ferramenta gráfica para design, desenvolvimento e administração de bancos de dados MySQL.

▪ POO: Programação Orientada a Objetos.

▪ Padrão Factory: Padrão de design de software que cria objetos sem expor a lógica de criação ao cliente, utilizando uma interface comum.

▪ UpperCamelCase: Convenção de nomenclatura onde a primeira letra de cada palavra é maiúscula, sem espaços, por exemplo: MinhaClasseExemplo.

## Requisitos
Serão descritos abaixo os requisitos funcionais e não funcionais do projeto.

   ### Requisitos Funcionais
   RF01: O sistema deverá permitir o cadastro de ao menos duas entidades principais.
   
   RF02: O sistema deverá Implementar operações CRUD para todas as entidades relacionadas.
   
   RF03: O sistema deve possuir uma interface que permita a interação do usuário com as funcionalidades do sistema.
   
   RF04: O sistema deve ser capaz de gerar pelo menos um relatório.
   
   RF05: O sistema deve permitir a adição, edição e remoção de registros.
   
   RF06: O sistema deve permitir que os usuários emprestam e devolvam materiais da biblioteca.
   
   RF07: O sistema deve controlar a quantidade de cada item disponível na biblioteca.
   
   RF08: O sistema deve permitir que os usuários pesquisem o catálogo da biblioteca.

   ### Requisitos Não Funcionais
   RNF01: O sistema deve ser implementado utilizando o padrão Factory descrito na documentação.
   
   RNF02: O sistema deverá ser modular, assim respeitando os principios da POO.
   
   RNF03: O código deverá ser versionado no GitHub com os integrantes mantendo o historico claro e organizado de commits
   
   RNF04: O projeto deverá ser documentado deixando claro seus objetivos, requisitos, arquitetura e suas principais classes
   
   RNF05: O sistema deve ser rápido e eficiente, respondendo às solicitações dos usuários em tempo hábil, mesmo durante períodos de pico de uso.
   
   RNF06: O sistema deve ser fácil de manter e atualizar, permitindo que a equipe da biblioteca faça alterações e atualizações com facilidade.
   
   RNF07: O sistema deve ser fácil de usar e navegar, com uma interface amigável e intuitiva para todos os tipos de usuários.
   
   ENF08: O sistema deve utilizar o padrão UpperCamelCase.

## Personas
   ![WhatsApp Image 2024-11-21 at 22 15 19](https://github.com/user-attachments/assets/24768738-9b51-4508-a9d9-ba5a791a464b)


## Diagramas UML
   
   ### Diagrama de Casos de Uso
    
   ![image](https://github.com/user-attachments/assets/05009660-d623-4999-882d-87950f4253f5)


   ### Diagrama de Classe

   ![image](https://github.com/user-attachments/assets/85c6f93e-e98e-4743-ab29-e24e82323d55)


## Estrutura do Projeto 
- `src/`: Código-fonte do projeto.
- `lib/`: Conector do banco de dados com o código.

## Tecnologias Utilizadas
- Linguagem de Programação: Java.
- Framework/Biblioteca: MySQL, MySQLWorkbench

## Instruções de Instalação
1. Clone o repositório:
   ```sh
   git clone (https://github.com/F-I-V-E-Project/core-project)
## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo <LICENSE> para mais detalhes.
## Contato
![image](https://github.com/user-attachments/assets/c6e1bce0-c7ee-4796-898d-8c9f04f52e00)
Fernando Rufino Barcelos
fernandosbarcelo27@gmail.com

![image](https://github.com/user-attachments/assets/f7f91ef3-07b8-4431-9868-354794418590)
Ícaro Wanzeler
icarowanzeler16@gmail.com

![image](https://github.com/user-attachments/assets/a5e07dce-9f63-48e9-b8ba-f4ad96ed486c)
Vanderson Henrique
vandersonyi@gmail.com

![image](https://github.com/user-attachments/assets/364c3812-45b2-4665-9a0a-b67324a6bf4e)
Emilli Giuliane Pereira Lima
emilligiuliane@gmail.com
