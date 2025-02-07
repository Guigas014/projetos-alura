# spotify-imersao

### Criando uma API Falsa com JSON-Server

Para consumir o arquivo "artists.json" como uma API e usar a função "fetch" (javascript) foi utilizado o JSON-Server através do node.

#### Trabalhando com o JSON-Server

- Instalação:

      `npm i json-server -D`

Após criarmos o arquivo JSON (artists.json no exemplo) podemos inicializar o JSON-Server. Para isso usamos o seguinte comando na pasta onde o arquivo JSON está localizado.

- Rodando o servidor:

      `json-server --watch server.json`

- No caso do exemplo dessa aplicação:

      `json-server --watch api-artists/artists.json`
