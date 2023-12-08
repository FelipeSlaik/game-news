# game-news

## API Utilizada
- O RAWG é o maior banco de dados de videogames e serviço de descoberta de jogos.
-Saiba o que a API de banco de dados de jogos RAWG pode fazer e crie algo legal com ela!
[API RAWG](https://rawg.io/apidocs)

## Requisitos
- Node.js (de preferência a versão mais recente LTS)
- arquivo `.env` (deixei um com o nome `env-test` na raíz do projeto), renomeie para `.env` e adicione sua `API_KEY_GAMES` do site RAWG

## Note
- Caso seja alterado algo nos scripts em `src/[filename].js`, execute o comando `npm run build`
- Caso seja adicionado mais algum script, adicione-o no arquivo `webpack.config.js` dentro de `module.exports.entry.YOUR_FILE`