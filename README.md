http://127.0.0.1:5500/index.html



Tela de Login em PHP

Este projeto apresenta uma tela de login simples desenvolvida com HTML e integrada ao PHP para validação de usuários. A interface é minimalista, com foco em usabilidade e design limpo.

Descrição

A aplicação consiste em um formulário de login que solicita usuário e senha, enviando os dados via método POST para um arquivo PHP (valida.php), responsável pela autenticação.

Funcionalidades
Interface de login simples e intuitiva
Envio de dados via método POST
Campos obrigatórios com validação HTML (required)
Design centralizado e responsivo básico
Estilização com CSS embutido
Estrutura do Projeto

/login
│── index.html (ou index.php) Tela de login
│── valida.php Processamento do login

Funcionamento
O usuário acessa a página de login
Insere o nome de usuário e senha
Os dados são enviados para valida.php
O PHP processa e valida as credenciais
Tecnologias Utilizadas
HTML5
CSS3
PHP
Estilo da Interface
Layout centralizado usando Flexbox
Formulário com sombra e bordas arredondadas
Botão com efeito hover
Cores simples (branco e vermelho)
Configuração
Coloque os arquivos em um servidor local (XAMPP, WAMP, etc.)
Certifique-se de que o arquivo valida.php está configurado corretamente
Acesse pelo navegador:

http://localhost/login

Melhorias Futuras
Implementar autenticação com banco de dados
Criptografia de senha
Mensagens de erro para login inválido
Sistema de cadastro de usuários
Proteção contra ataques (SQL Injection, CSRF)
Observação

Este projeto é apenas um exemplo básico e não deve ser utilizado em produção sem melhorias de segurança.
