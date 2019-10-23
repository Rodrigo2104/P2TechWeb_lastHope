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
  
  
  
  Lista de funcionalidades:
  1. Conferir uma tabela completa com todos os pokemons;
  2. Conferir na mesma tabelas suas sprites oficiais;
  3. Conferir a "tipagem" de cada pokemon da tabela por meio de cores;
  4. Filtrar entre todos os pokemons aqueles de um determinado tipo;
  5. Ter acesso a todos os "status" do pokemon ao clicar em sua imagem;
  6. Pesquisar um determinado pokemon pelo seu nome;
  7. Pesqusar um determinado pokemon pelo seu id (oficial da pokemon company);
  8. Ter acesso a toda linha evolutiva de um determinado pokemon;
  9. Acessar ao dados de uma evolução pokemon a partir de sua pré-evolução;
  10. 
  

