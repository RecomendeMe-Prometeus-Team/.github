Descrição da Organização no GitHub

Esta organização tem como objetivo compartilhar conhecimento, ferramentas e projetos relacionados a desenvolvimento web e backend, com foco no uso de tecnologias como PHP, MySQL e ambientes de desenvolvimento locais, como o XAMPP. Nosso propósito é ajudar desenvolvedores a configurarem e executarem projetos com facilidade, promovendo boas práticas e documentação clara.

Equipe Prometeus - RecomendeMe

A Equipe Prometeus é formada por profissionais dedicados e comprometidos com a evolução constante do RecomendeMe. Nossa missão é manter a estabilidade da plataforma, implementar novas funcionalidades e garantir que o site permaneça relevante e inovador para seus usuários. Estamos sempre buscando melhorar a experiência do usuário e promover atualizações que fortaleçam a comunidade do RecomendeMe.

Pré-requisitos

Antes de iniciar, certifique-se de ter o XAMPP instalado no seu computador. Você pode baixar a última versão no site oficial: Apache Friends.

Passo a Passo

1. Iniciar o XAMPP

Abra o painel de controle do XAMPP.

Inicie os serviços "Apache" e "MySQL" clicando em "Start".

2. Configuração do Projeto

Copie seu projeto para a pasta htdocs dentro do diretório de instalação do XAMPP (por exemplo: C:\xampp\htdocs).

Certifique-se de que o projeto tenha um arquivo index.php na raiz ou um arquivo de entrada adequado.

3. Configuração do Banco de Dados

Acesse o phpMyAdmin através do navegador: http://localhost/phpmyadmin.

Crie um banco de dados para o seu projeto.

Importe o arquivo SQL do projeto (se houver) através da opção "Importar".

Atualize o arquivo de configuração do projeto (geralmente .env ou config.php) com as credenciais do banco:

Host: localhost

Usuário: root

Senha: (deixe vazio por padrão)

Nome do banco: (nome do banco que você criou)

4. Acessar o Projeto

Abra o navegador e digite a URL: http://localhost/nome_do_projeto.

O projeto deve estar rodando na porta 80 por padrão. Caso esteja em outra porta, use: http://localhost:porta/nome_do_projeto.

5. Solucionando Problemas Comuns

Erro de Porta Ocupada: Verifique se outro serviço está usando a porta 80 ou 443.

Erro de Conexão com o Banco de Dados: Verifique se o MySQL está iniciado e se as credenciais estão corretas.

Página em Branco: Confira os logs de erro do Apache em xampp\apache\logs\error.log.

6. Finalizando

Para encerrar o projeto, pare os serviços "Apache" e "MySQL" no painel do XAMPP.

Pronto! Agora você já sabe como rodar um projeto no XAMPP. Aproveite o desenvolvimento!
