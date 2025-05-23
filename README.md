# MyCine - Sistema de Compra de Ingressos
**Mycine** é uma plataforma online de compra de ingressos de cinema. O Sistema permite aos usuários, fazerem login, visualizar filmes disponíveis, realizar a compra de ingressos e entrar em contato com a plataforma.

## Objetivo do Projeto

O projeto acadêmico foi criado com a finalidade de disponibilizar uma plataforma prática e funcional para a aquisição de ingressos de cinema. As principais características incluem:
* Login de usuário pré estabelecidos: **"admin"** Senha: **"123"**.
* Visualização e interação com banners de filmes.
* Compra de ingressos.
* Gerenciamento de sessões de usuários para manter o estado do login.

## Funcionalidades  
1. **Login de Usuário**:
    - Permite o registro e login dos usuários, com controle de sessão para manter o estado de login ativo.

2. **Página de Filmes**:
    - Exibe filmes disponíveis, permitindo aos usuários interagir com banners e obter mais detalhes sobre cada filme.

3. **Página de Contato**:
    - Para tirar dúvidas, enviar sugestões ou compartilhar suas ideias.

4. **Compra de Ingressos**:
    - Após o login, o usuário pode acessar uma página exclusiva de compra de ingressos (`Compra.php`).

5. **Uso de Sessões**:
    - Através da função `session_start()`, os dados do usuário são armazenados na sessão, permitindo a navegação sem a necessidade de fazer login novamente.
   - O usuário pode se deslogar utilizando `session_destroy()`.

## Linguagens Utilizadas:
- **PHP:** Responsável pelo gerenciamento de sessões e pela manipulação de dados no lado do servidor..  
- **HTML/CSS:** Utilizados para criar a estrutura e adicionar estilos às páginas.  
- **JavaScript:** Implementado para tornar as páginas dinâmicas e interativas.
- **MySQL:** Serve para armazenar informações, como os dados dos filmes, dos usuários e das formas de pagamento.

## Estruturas Utilizadas no Código

- **PHP:** Estruturas condicionais como `if`, `switch`, e operadores lógicos (`&&`, `||`) para controle de fluxo e validação de formulários.
- **Variáveis Superglobais:** Como `$_GET` e `$_POST`, usadas para capturar e processar os dados dos formulários.
- **JavaScript:** Para adicionar interatividade nas páginas, como animações e navegação.

## Para Rodar o Projeto:
1. Realize o clone deste repositório para o seu computador.
2. Verifique se PHP e MySQL estão devidamente configurados em seu ambiente.
3. Abra os arquivos PHP utilizando um servidor local, como o WAMP.
4. Acesse o projeto diretamente através do seu navegador de internet.



