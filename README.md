php-mysql-agenda

✨ Funcionalidades

O sistema permite gerenciar contatos de forma intuitiva, com as seguintes funcionalidades:

Listagem Completa: Exibe todos os contatos (Nome, Telefone, Descrição) na tela principal.

Criação (Create): Link para uma página de formulário para adicionar novos contatos.

Visualização (Read): Botão para exibir os detalhes individuais de cada contato.

Edição (Update): Botão para modificar as informações de um contato existente.

Exclusão (Delete): Botão para remover um contato permanentemente do banco de dados.

<img width="1356" height="469" alt="image" src="https://github.com/user-attachments/assets/ea347a94-b827-4d5a-9e32-04eefb33a0a8" />


🚀 Tecnologias Utilizadas

Este projeto foi construído utilizando uma pilha LAMP (ou XAMPP/WAMP/MAMP):

Frontend: HTML5, CSS3 e Bootstrap (para um layout responsivo e moderno).

Backend: PHP.

Banco de Dados: MySQL (Para persistência dos dados e operações CRUD).

⚙️ Como Executar o Projeto Localmente

Siga estes passos para configurar e rodar o projeto em seu ambiente:

Pré-requisitos
Um servidor web local (Ex: XAMPP, WAMP, MAMP, ou um servidor LAMP).

PHP.

MySQL/MariaDB.

Passos
Clone o Repositório:

git clone https://github.com/jairo2998/php-mysql-agenda.git

Configuração do Servidor:

Mova a pasta do projeto clonado para o diretório de projetos do seu servidor web (ex: htdocs no XAMPP).

Configuração do Banco de Dados:

Crie um banco de dados vazio no seu MySQL (pode ser via phpMyAdmin) com o nome "agenda" e a tabela "contacts".

<img width="759" height="288" alt="image" src="https://github.com/user-attachments/assets/e83d196a-3ed1-4a21-8a51-696e2f9637b4" />

Ajuste de Credenciais:

Abra o arquivo de conexão PHP (config/connection.php) e insira as credenciais do seu banco de dados local (usuário, senha, nome do banco).

Acesso:

Acesse o projeto pelo seu navegador: http://localhost/php-mysql-agenda
