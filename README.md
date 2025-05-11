# 📚 Bookstore — E-commerce em PHP

Este é um projeto completo de uma loja virtual desenvolvido com PHP, utilizando conceitos modernos de desenvolvimento web como:

- Sistema de carrinho de compras
- Autenticação de usuários
- Painel administrativo
- Integração com Stripe para pagamentos (API)
- Consumo e manipulação de banco de dados via PDO
- Organização de pastas por módulos (`src`, `config`, `includes`, etc.)

## 🚀 Como rodar o projeto localmente

1. Instale o [XAMPP](https://www.apachefriends.org/index.html)
2. Copie a pasta do projeto para `C:\xampp\htdocs\bookstore`
3. Inicie **Apache** e **MySQL** pelo painel do XAMPP
4. Acesse `http://localhost/phpmyadmin`
5. Crie o banco de dados `bookstore`
6. Importe o arquivo `.sql` que está em `SQL_FILE`
7. Acesse no navegador:  
   👉 `http://localhost/bookstore`


## 📂 Estrutura de pastas

bookstore/
├── admin-panel/ # Interface administrativa (produtos, pedidos, etc.)
├── auth/ # Autenticação e login de usuários
├── categories/ # Gestão e exibição de categorias de produtos
├── config/ # Configurações do sistema (ex: conexão com banco)
├── contact.php # Página de contato
├── download.php # Sistema de downloads (ex: e-books)
├── includes/ # Includes reutilizáveis (ex: header, footer)
├── index.php # Página inicial da loja
├── shopping/ # Carrinho de compras e finalização de pedido
├── src/ # Funções reutilizáveis e bibliotecas auxiliares
├── success.php # Página de sucesso pós-compra
├── users/ # Gestão de dados dos usuários
├── SQL_FILE/ # Scripts de criação e popular banco de dados
├── vendor/ # Dependências instaladas via Composer (ex: Stripe)
├── composer.json # Dependências do projeto PHP
├── composer.lock # Arquivo de travamento do Composer
├── .git/ # Dados internos do repositório Git
└── .gitignore # Arquivos/pastas ignorados pelo Git


## 📌 Funcionalidades implementadas

- Cadastro e login de usuários
- Listagem e filtro de produtos
- Gerenciamento de estoque
- Finalização de compras com pagamento (Stripe)
- Painel administrativo para gerenciar produtos, categorias e pedidos


## 🧠 Base do projeto

Este projeto foi desenvolvido como parte do curso abaixo, com adaptações e personalizações feitas por mim:

🎓 **Curso:**  
[PHP for Beginners 2023: Build a Complete eCommerce Store](https://www.udemy.com/course/php-for-beginners-2023-build-complete-ecommerce-store)  
📚 Plataforma: Udemy  
👨‍🎓 Aluno: Rycharsson

## 🔐 Segurança

Este repositório utiliza o sistema de **proteção contra vazamento de chaves do GitHub**.  
**⚠️ Nenhuma chave secreta (como Stripe API Key) deve ser incluída diretamente no código-fonte.**

### ✅ Recomendado:
- Utilize variáveis de ambiente com `.env`
- Adicione `.env` no `.gitignore`
- Nunca commit nenhuma chave de API ou segredo


## 🧑‍💻 Autor

Projeto desenvolvido por **Rycharsson** como parte do processo de aprendizado e prática em desenvolvimento web com PHP e MySQL.

