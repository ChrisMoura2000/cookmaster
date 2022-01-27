Este projeto foi desenvolvido durante o curso da trybe com o intuito de praticar as seguintes habilidades:

- Entender o que há por dentro de um token de autenticação;

- Gerar tokens a partir de informações como login e senha;

- Autenticar rotas do Express, usando o token JWT;

- Fazer upload de arquivos em APIs REST;

- Salvar arquivos no servidor através de uma API REST;

- Consultar arquivos do servidor através de uma api REST.

- Realizar testes de integração

Desenvolvi um app utilizando a arquitetura MSC!
Nesse projeto é possivel fazer o cadastro e login de pessoas usuarias, onde apenas esses pessoas podem acessar, modificar e deletar as receitas cadastradas.

Desenvolvi todas as camadas da aplicação (Models, Service e Controllers)

Através dessa aplicação, é possível realizar as operações básicas que se pode fazer em um determinado banco de dados (nesse projeto MongoDB): Criação, Leitura, Atualização e Exclusão (ou `CRUD`, para as pessoas mais íntimas 😜).

Para realizar qualquer tipo de alteração no banco de dados (como cadastro, edição ou exclusão de receitas) é necessário autenticar-se. Além disso, as pessoas usuárias podem ser clientes ou administradores. Pessoas clientes apenas pode disparar ações nas receitas que ele mesmo criou. Já uma pessoa administradora pode disparar qualquer ação em qualquer receita.

A autenticação é feita via `JWT`.

É possível adicionar uma imagem à uma receita, utilizando o upload de arquivos fornecido pelo `multer`.
