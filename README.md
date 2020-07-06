# desafio-fundamentos-reactjs
<h3>Desafio do Bootcamp GoStack 11 da Rocketseat.</h3>

Essa será uma aplicação que irá se conectar ao seu backend do [Desafio 06](https://github.com/MagnoBelloni/desafio-database-upload-nodejs), e exibir as transações criadas e permitir a importação de um arquivo CSV conforme modelo abaixo, para gerar novos registros no banco de dados.
> [Modelo de CSV](https://github.com/Rocketseat/bootcamp-gostack-desafios/blob/master/desafio-database-upload/assets/file.csv)

<h2>Para rodar a aplicação</h2>
<ol>
  <li>Execute "yarn" no terminal para instalar todas as dependencias.</li>
  <li>Certifique-se de ter um banco de dados criado igual especificado no arquivo <b>ormconfig.json</b>.</li>
  <li>Execute "yarn typeorm migration:run", para realizar a criação do banco de dados</li>
  <li>Execute "yarn dev:server", para rodar a aplicação, ela ficara no endereço "http://localhost:3333/"</li>
</ol>

<h2>Para rodar os testes</h2>
<ol>
  <li>Execute "yarn" no terminal para instalar todas as dependencias.</li>
  <li>Execute "yarn test" para rodar os testes.</li>
</ol>

<h2>Resumo da aplicação:</h2>
<ul>
  <li>Listagem de transações, de deposito e saque.</li>
  <li>Importação de um arquvio CSV, para gravar transações.</li>
</ul>
