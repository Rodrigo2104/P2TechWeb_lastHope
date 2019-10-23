# Projeto2TechWeb

Nova Pokedex atualizada. Em fase de testes e ainda com bugs.

Para utilizar seguir os passos abaixo:

1. Abrir a pasta no prompt de comando e executar o comando "npm i";
2. Copie a tabela abaixo e a que se encontra no arquivo database.txt para o mysql;
3. Inicie o main.js com o comando "node main.js" no terminal;
4. Utilize no localhost:3000.


Tabela usuário:

CREATE TABLE users(
  id INT NOT NULL AUTO_INCREMENT,
  login VARCHAR(20) NOT NULL,
  password VARCHAR(20) NOT NULL,
  name VARCHAR(32) NOT NULL,
  PRIMARY KEY (id)
  );
  
  

