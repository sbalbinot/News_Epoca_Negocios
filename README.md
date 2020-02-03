# News_Epoca_Negocios
Capture startup news data from Época Negócios website.

- Acessar o site https://epocanegocios.globo.com/
- Clicar em "Search"
- Para cada startup da lista de startups, inserir o nome em "Digite sua busca"
- Clicar em "Notícias"
- Para cada notícia, acessar o link.
  - Carga inicial: todas as notícias
  - Carga diária: desconsiderar notícias antigas (maior que 30 dias)
- O arquivo de saída terá os seguintes campos:
 1. Título da notícia
 2. Resumo da notícia - ***deixar em branco***
 3. Data da notícia
 4. Texto da notícia
 5. Nome da startup
 6. Nome do veículo - texto **"Época Negócios"** para todas as linhas
 7. Data e hora da Captura
 8. URL da notícia
