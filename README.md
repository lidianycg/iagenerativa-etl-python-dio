# Desafio - Explorando IA Generativa em um Pipeline de ETL com Python

Nesse projeto, foram realizadas as 03 etapas do ETL (Extração, Transformação e Carregamento), utilizando como base um arquivo CSV com informações referentes a projetos profissionais (Projeto; Descricao; Status; Prazo).
Na primeira etapa, li o arquivo csv utilizando o pandas e extraí a lista de projetos de usuário a partir do arquivo CSV. Para cada projeto, faça uma requisição GET para obter os dados do usuário correspondente.
Criei também um dicionário para cada linha com informações específicas do projeto (Projeto, Descrição, Status e Prazo), e adicionei esse dicionário a uma lista chamada projetos.

Na etapa tranform, utilizei a API do OpenAI GPT-4 para gerar uma mensagem de engajamento personalizada para cada projeto.

Na etapa load, Em resumo, o código percorreu cada projeto na lista projetos, adicionando uma nova chave 'news' ao dicionário do projeto e atribuindo a ela o valor correspondente no índice idx da lista news. Em seguida, imprimi o índice e o projeto atualizado, agora com as mensagens de engajamento. 

Foi um projeto interessante de desenvolver, onde pude combinar habilidades técnicas com o potencial da inteligência artificial.
