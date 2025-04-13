# MyCine - Sistema de Compra de Ingressos
**Mycine** é uma plataforma online de compra de ingressos de cinema. O Sistema permite aos usuários, fazerem login, visualizar filmes disponíveis, realizar a compra de ingressos e entrar em contato com a plataforma.

**Objetivo do Projeto**
O projeto acadêmico foi criado com a finalidade de disponibilizar uma plataforma prática e funcional para a aquisição de ingressos de cinema. As principais características incluem:
* Login de usuário pré estabelecidos: "admin" Senha: "123".
* Visualização e interação com banners de filmes.
* Compra de ingressos.
* Gerenciamento de sessões de usuários para manter o estado do login.

  **Funcionalidades**
-
1. Login de Usuário:

Permite o registro e login dos usuários, com controle de sessão para manter o estado de login ativo.
Página de Filmes:

Exibe filmes disponíveis, permitindo aos usuários interagir com banners e obter mais detalhes sobre cada filme.
Compra de Ingressos:

Após o login, o usuário pode acessar uma página exclusiva de compra de ingressos (Compra.php).
Uso de Sessões:

Através da função session_start(), os dados do usuário são armazenados na sessão, permitindo a navegação sem a necessidade de fazer login novamente.
O usuário pode se deslogar utilizando session_destroy().
Tecnologias Utilizadas
PHP: Para o controle de sessões e manipulação de dados no servidor.
HTML/CSS: Para a estruturação e estilização das páginas.
JavaScript: Para animações e interatividade na página de compra, como as setas de navegação na página de compras.
MySQL (provavelmente): Para o armazenamento de dados dos filmes e usuários.
Estruturas Utilizadas no Código
PHP: Estruturas condicionais como if, switch, e operadores lógicos (&&, ||) para controle de fluxo e validação de formulários.
Variáveis Superglobais: Como $_GET e $_POST, usadas para capturar e processar os dados dos formulários.
JavaScript: Para adicionar interatividade nas páginas, como animações e navegação.
Como Rodar o Projeto
Faça o clone deste repositório.
Certifique-se de que o seu ambiente tem PHP e MySQL configurados.
Abra os arquivos PHP no seu servidor local (ex: WAMP).
Acesse o projeto no navegador.
Layout

