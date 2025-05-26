# auctions
Projeto de estudos utilizando goroutines, leilão.

## Descrição
Esse projeto cria leilões, e possibilita criar lances, o leilão é finalizado automaticamente após um tempo, esse tempo é determinado em uma variavel "AUCTION_INTERVAL".

## Funcionamento
Primeiro precisamos criar um leilão, após esse leilão ter sido criado, é possível add os lances, para cada lance deve ser informado um id de usuário e também o id do leilão.

## Teste
Execute docker compose up -d para subir os container necessários.

Na pasta raiz do projeto add um arquivo chamado test.http, onde temos todas as requests necessárias para fazer esses teste, mas também é possível consultar no video abaixo o funcionamento:

https://github.com/user-attachments/assets/0f797669-72d7-4fc6-8dfe-4764ea0612d6
