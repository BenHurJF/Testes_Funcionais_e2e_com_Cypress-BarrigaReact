# Projeto-Testes-Funcionais-e2e-CYPRESS
Testes funcionais e2e da Aplicação: Barriga React -> https://barrigareact.wcaquino.me/login
- Cénarios de testes -
#
1- Inserindo Conta

2 - Alterando a conta

3 - Tentar criar conta já existente

4 - Inserir movimentação/Transação

5 - Consultar Saldo

6 - Remover Movimentação

- OBS: Criei um arquivo na pasta /Support chamado Locators onde criei um array com objetos
que tem nomes de referência para a tela/caminho do sistema e que contêm propriedades que setei
os get de alguns elementos da tela como botões, campos etc. Para ajudar no entendimento de cada passo.

Como Usar:
#
1- git clone no projeto

2- npm i

4- adicione a pasta raiz um arquivo com nome: 'cypress.env.json', e nele adicione o seguinte trecho de código: 

{
    "user_email": "E-mail da conta que será criada no BarrigaReact",
    "user_senha": "senha"
}

5- Comando para rodar: npm run tst

