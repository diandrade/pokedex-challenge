# Jetpack Compose Pokedex

<img src="https://github.com/diandrade/Pokedex-Challenge/blob/cb67ea904f42e682957728ea821722d6d30ce1b1/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05.jpeg" alt="JetNews" width="240"></img>
<img src="https://github.com/diandrade/Pokedex-Challenge/blob/784d3a24e31c9cf02ec833fdd67f7cb1f77ecc97/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05%20(2).jpeg" alt="JetNews" width="240"></img>
<img src="https://github.com/diandrade/Pokedex-Challenge/blob/885ad43aa317ab55679afd46ac0d501964b99fee/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05%20(1).jpeg" alt="JetNews" width="240"></img>
<img src="https://github.com/diandrade/Pokedex-Challenge/blob/cb67ea904f42e682957728ea821722d6d30ce1b1/img/WhatsApp%20Image%202022-08-22%20at%2007.45.06.jpeg" alt="JetNews" width="240"></img>


Olá a todo mundo!, esse aqui é o projeto de uma Pokedex que realizei para um desafio seguindo os passos do youtuber [Philipp Lackner](https://www.youtube.com/c/PhilippLackner).

O desafio se trata de criar duas listas, uma com os pokemons utilizados através da API dos pokemons, encontrada [NESSE LINK](https://pokeapi.co), com o objetivo de mostrar os pokemons disponíveis, onde é necessário clicarmos para acessar as informações do pokemon em específico.

E outra lista, com a opção de visualizar os pokemons salvos.

As informações do pokemon obrigatórias, são as seguintes:

● ID
<br/>
● Nome
<br/>
● Tipo (grass, fire, water)
<br/>
● Foto

Em adicional seguindo os passos de Phillip, adicionamos também o **peso**, a **altura** e os **stats** do pokemon.

## Especificações Técnicas

**Tecnologias/Design Patterns do Desafio**

● MVVM (Obrigatório)
<br/>
● Room (Obrigatório)
<br/>
● Ktor ou Retrofit (Obrigatório)
<br/>
● Coroutine (Obrigatório)
<br/>
● Jetpack Compose (Opcional)
<br/>
● Injeção de Dependência (Opcional) 

## Dificuldades

Embora com muita pesquisa, diversas mudanças na técnologia de aplicativos da data dos vídeos de Phillip ocorreram, então muitas vezes foi necessário realizar pesquisas sobre as mudanças em si, como por exemplo as que ocorreram no framework Coil, sem contar também as mudanças de versão da versão base do projeto, e das versões atuais do Gradle, Kotlin e Hilt.
<br/>
**Também é valido contar sobre a dificuldade de criar a segunda lista, mesmo tentando encontrei dificuldades em utilizar o Room junto do Jetpack Compose, e decidi focar em finalizar a primeira lista, para poder trazer a função de favorito como uma feature pra as próximas etapas.**

## Apresentação Do Projeto

Caso queiram visualizar o projeto na prática, aqui temos 2 videos disponibilizados pela opção não listada do Youtube:
<br/>
<br/>
● [Apresentação Do App No Celular](https://youtu.be/wcucE0zaZ-k)
<br/>
<br/>
Como o celular não captou o som tão bem, vou detalhar o vídeo aqui. Bom, no vídeo temos a visualização do projeto a partir de sua inicialização, na qual após inicialização, temos contato com a primeira lista, demonstrando todos os pokemons da api, com foto de perfil e **estilização** pré-definidas através do projeto base disponibilizado [aqui](https://github.com/philipplackner/JetpackComposePokedex).
<br/>
Após clicar no Pokemon escolhido, temos acesso ao **id do Pokemon, ao nome, o tipo, a uma foto de perfil, peso, altura e status** do pokemon.
<br/>
Finalizando a primeira lista, temos uma opção para favoritar e desfavoritar o pokemon, na parte superior da tela.
<br/>
<br/>
● [Resumo Codificação]()
<br/>
<br/>
Nesse vídeo, temos um pouco da explicação, porém utilizando o Android Studio para demonstrar os principais desafios que ocorreram durante o projeto, e também uma visão geral da etapa de codificação.
<br/>
Também conto um pouco sobre os aprendizados adquiridos enquanto desenvolvi o projeto.








