# TestesTecnicoQAAutomacao
Projeto referente ao teste técnico de QA Automação

Neste Projetos serão realizados testes de API, testando o endpoint "usuarios" da aplicação https://serverest.dev/.

Realizando as seguinte validações: 
    Validar usuário cadastrado com sucesso
    Validar verificações realizadas no cadastro de usuário
    Validar Edição de um usuário
    Validar listagem de usuários
    Validar Exclusão de um usuário

Também serão realizados testes de frontend, testando a aplicação https://www.saucedemo.com.

Realizando as seguinte validações:
    Login com usuário bloqueado, e validar a mensagem de bloqueio exibida;
    Realizar uma compra completa com mais de um produto no carrinho;
    Adicionar todos os produtos ao carrinho e validar o valor total da compra a ser pago.

Os testes foram desenvolvidos em Cypress.

A execução dos testes pode ser comandada diretamente no github ao realizar um pull request ou push.
O arquivo que contém a configuração da pipeline está em .github\workflows\github-actionsinit.yml

Para a execução manual dos testes é necessário baixar o repositório e seguir os passos abaixo:
    Instalar o nodeJS 16+.
    Abrir o caminho do repositório no prompt de comando.
    digitar "npm install" para instalar as dependencias do projeto.
    digitar "npx cypress run"