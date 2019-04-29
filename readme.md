Este reporsitório - https://github.com/marcelorsr/catalogo-lumiere contém uma lista dos 1428 filmes identificados que foram produzidos pela companhia Lumière entre 1895-1905. Trata-se de uma tradução em língua portuguesa do repositório Catalogue Lumière - https://github.com/greyscalepress/catalogue-lumiere.

A lista está disponível como um arquivo CSV que contém um conjunto de metadados sobre cada título.

Os dados originais estão também disponíveis por meio do site http://catalogue-lumiere.com/, que oferece uma interface para navegação e para busca por meio de parâmetros específicos.

## Entendendo os dados

Eis a explicação da tabela:

1. "Numero-original": o número de catalogação do filme, tal como apareceu no catálogo Lumière.
2. "Numero-livre": O número de item que foi usado pelos pesquisadores (Michelle Aubert e Jean-Claude Seguin) em seu livro "A produção cinematográfica dos Irmãos Lumière" (título original: "La production cinématographique des Frères Lumière"; tradução livre) em 1996.
3. "titulo": O título do filme.
4. "id-cinegrafista": identificação numérica do operador de câmera (cinegrafista).
5. "cinegrafista": nome do cinegrafista.
6. "notas": comentários e anotações.
7. "descricao": a descrição original do item, extraída do catálogo Lumière.
8. "projecao": informação sobre exibições (quando, onde...).
9. "local": nomes de localizações legíveis por humanos (onde foi filmado).
10. "id-pais": identificação de país.
11. "id-cidade": identificação de cidade.
12. "id-local": identificação de local (montanha, costa, estação de trem, zoológico...). 33 elementos.
13. "data": data de produção legível por humanos.
14. "timestamp": marcação de data legível por máquinas (data aproximada de produção).
15. "info-1": metadados misteriosos.
16. "info-2": metadados misteriosos.
17. "info-3": metadados misteriosos.
18. "info-4": metadados misteriosos.
19. "info-5": metadados misteriosos.
20. "info-6": metadados misteriosos.
21. "info-7": metadados misteriosos.
22. "id-eventos": metadados misteriosos.
23. "id-generos": metadados misteriosos. 14 elementos.
24. "id-tema": tipos de pessoas (acrobatas, camponeses, crianças...).
25. "id-identidade": identificação numérica de pessoas que aparecem no filme.
26. "sequencia-1": metadados misteriosos.
27. "sequencia-2": metadados misteriosos.
28. "pessoas": notas sobre pessoas que aparecem no filme.
29. "tecnica": detalhes técnicos sobre o processo de filmagem (movimentos de câmera, etc.).
30. "id-objeto": motivos (trem, barco, máquinas...). 19 elementos.
31. "id-mov": tipo de ação (chegada, partida...). 9 elementos.
32. "suporte": detalhes técnicos sobre o negativo fílmico.

## Fonte dos dados

Os dados foram extraídos do CD-Rom que acompanha o livro "A produção cinematográfica dos Irmãos Lumière", publicado em 1996 pelo Centre national de la Cinématographie e pela Université Lumière-Lyon 2.

Este catálogo está esgotado, e será difícil de acessar, a não ser que você tenha acesso a uma boa biblioteca acadêmica.

O CD-Rom contém uma aplicação bibliográfica, feita no Macromedia Director. Destinava-se ao sistema MacOS 7 e ao Windows 95, e não é legível nos atuais sistemas operacionais.

Entretanto, os arquivos binários brutos do CD-Rom contêm alguns dados de texto legíveis, que fui capaz de recuperar.

Com alguma mágica do GREP, produzi esta tabela de CSV, que resguarda os metadados essenciais para os 1428 filmes identificados do catálogo Lumière.

## Qual é a situação de direitos autorais desses dados? Estão em domínio público?

A equipe de pesquisa que produziu esta lista reuniu todas as informações dos catálogos comerciais originais da companhia Lumière (publicados entre 1897 e 1907), de jornais publicados naquele intervalo de tempo, e de um inventário estabelecido pela Cinemateca Francesa em 1948.

É basicamente impossível estabelecer uma situação de direitos autorais nítida para esse tipo de metadados.

Pessoalmente, coloco todas as minhas contribuições para esse conjunto de metadados sob a licença Creative Commons Zero Public Domain Dedication (CC0), de modo a facilitar a pesquisa.

Manuel Schmalstieg<br/>
Arquivista digital<br/>
Dezembro de 2013

