# Projeto2TechWeb

Nova Pokedex atualizada. Feita inteiramente em Node js.

Para utilizar seguir os passos abaixo:

1. Abrir a pasta no prompt de comando e executar o comando "npm i";
2. Copie a tabela abaixo e a que se encontra no arquivo database.txt para o mysql;
3. Mude o login e a password do seu mysql no arquivo main.js;
4. Inicie o main.js com o comando "node main.js" no terminal;
5. Utilize no localhost:3000.

  
  
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
  10. Registrar um conta;
  11. Logar em sua conta;
  12. Deslogar de sua conta;
  13. Botão de acesso a home a partir das páginas especificas de um pokemon ou de pesquisa;
  14. 
  

Lista de requisições:
1.getPokemonByName -> Retorna um json com as Status do pokemon;
2.getPokemonSpeciesByName -> Retorna um json com informações(habitat,geração, etc) do pokemon;
3.getEvolutionChainById -> Retorna um json com todos os pokemons que fazem parte da mesma linha evolutiva;

  

