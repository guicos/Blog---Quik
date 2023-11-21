<h1 align="center"> Blog-Quik</h1>

# :hammer: Funcionalidades do projeto

- `Funcionalidades`: Listagem de postagens, adição de post, autenticação, alteração de senha, historico, relatorio de alcance, likes.

# 🛠️ Abrir e rodar o projeto

- `Passo 1`: Clone o projeto aonde desejar eu irei usar como exemplo a 'Área de Trabalho'
- `Passo 2`: Pelo terminal acesse a pasta clonada que tera o nome de 'Blog---Quik'
- `Passo 3`: Rode o comando **docker compose up -d**
- `Passo 4`: Após finalizar a operação acesse via terminal a pasta **/back** altere o arquivo .env dentro da pasta **/back** para **postgres://postgres:root@localhost:5432/postgres?schema=public** essa alteração serve pois na subida do docker referenciamos o conteiner **db** para realizar a conexão com o Banco de Dados, porém para criação da migration necessitamos voltar para **localhost**.
- `Passo 4`: Rode o comando no terminal dentro da pasta **/back** **npm run migration:run** esse comando criara a tabela do banco de dados.
- `Passo 4`: Para finalizar acesse via terminal a pasta **/front-end** e rode o comando **npm run start**


<p>Acesse pelo seu navegador "locahost:3000" e explore!</p>
<p>Caso ocorra algum erro na subida do docker solicitamos que limpe a memoria docker e confira para ver se a porta não esta sendo utilizada</p>
