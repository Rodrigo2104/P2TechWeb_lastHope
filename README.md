# Projeto2TechWeb
Evandro Romeiro e Rodrigo Jesus

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
  5. Filtrar pokemons que possuem dois tipos;
  6. Ter acesso a todos os "status" do pokemon ao clicar em sua imagem;
  7. Pesquisar um determinado pokemon pelo seu nome;
  8. Pesqusar um determinado pokemon pelo seu id (oficial da pokemon company);
  9. Ter acesso a toda linha evolutiva de um determinado pokemon;
  10. Acessar ao dados de uma evolução pokemon a partir de sua pré-evolução;
  11. Registrar um conta;
  12. Logar em sua conta;
  13. Deslogar de sua conta;
  14. Botão de acesso a home a partir das páginas especificas de um pokemon ou de pesquisa;
  15. Resetar filtro 
  

Lista de requisições:
1.getPokemonByName -> Retorna um json com as Status do pokemon;
2.getPokemonSpeciesByName -> Retorna um json com informações(habitat,geração, etc) do pokemon;
3.getEvolutionChainById -> Retorna um json com todos os pokemons que fazem parte da mesma linha evolutiva;

  

