# Desafio Técnico para Seleção Globo.com
# Desenvolvedor Frontend - Angular


## Considerações Gerais
A escolha da linguagem é deixada para você, utilize **a que você se sente mais confortável**. Sugerimos que você se mantenha na linguagem que você se colocou mais familiarizado nas entrevistas mas fica a seu critério a escolha. 

Forneça as instruções de instalação e execução do seu sistema, observaremos **principalmente seu *design* de código**. Aspectos como coesão, baixo acoplamento, testabilidade e legibilidade são os principais pontos.

Escolha ao menos dois dos desafios abaixo para resolver de acordo com o seu perfil. Quanto mais dados tivermos para analisar, melhor para o candidato.
Caso já tenha participado do processo seletivo, por favor escolha um desafio diferente do que foi feito anteriormente.

## 1 - IMDB Movie Rating App

Uma das grandes dificuldades das empresas de *Streaming* na atualidade é a curadoria e recomendação de filmes. Uma reclamação constante é que os usuários perdem muito tempo escolhendo filmes. Enquanto antigamente bastava a gente perguntar ao dono da locadora onde alugavamos filmes em VHS, atualmente, diante da diversidade, por mais que o algoritimo seja super alinhado, ele nunca avaliará um filme como um humano, com críticas não somente como *gostei*/*não gostei*, e sim com aspectos mais avançados como fotografia, roteiro, atuações, etc.

Para isso, projete um APP que leia que, a partir da consulta de um usuário, seja possivel avaliar um determinado filme com notas de 1 a 5, nos seguintes aspectos:
- Roteiro
- Fotografia
- Efeitos especiais
- Elenco

Para buscar os filmes, use a API https://english.api.rakuten.net/hmerritt/api/imdb-internet-movie-database-unofficial/details

OBS.: você não precisa enviar os dados ao servidor. Apenas simule o que você faria para montar a página que recebe as informações.

## 2 - Paredão BBB (Somente a parte visual!)

### Considerações Gerais

### O desafio

Você deve implementar o sistema de votação do Paredão do BBB. No Paredão, dois
ou mais participantes se enfrentam em uma votação popular para permanecer na
casa. Ao final da votação, o participante que recebeu mais votos é eliminado do
programa.

Esse sistema pode ser dividido em três partes:

* API para registro e consulta dos votos.
* Client que permite aos usuários participarem da votação, escolhendo um
  participante para ser eliminado.
* Client que permite à produção do programa consultar algumas informações sobre
  o estado da votação.

As regras de negócio para o desenvolvimento da solução são:

* Cada usuário pode votar quantas vezes quiser com uma taxa máxima de 10 votos
  por minuto.
* A votação é chamada na TV em horário nobre, com isso, é esperado um enorme
  volume de votos concentrados em um curto espaço de tempo. A sua solução deve
  suportar pelo menos 1000 votos por segundo.
* A produção do programa gostaria de poder consultar: o total geral de votos, o
  total por participante e o total de votos por hora de cada Paredão.
* Devido ao grande volume de acessos, podemos enfrentar períodos de lentidão ou
  instabilidade nos serviços. Todo o sistema deve estar preparado para isso.
* Como a produção acessará constantemente o estado da votação durante o programa
  ao vivo, as consultas não podem ser lentas. No entanto, é aceitável que a
  resposta apresente dados defasados em momentos de instabilidade.

#### Observações

* Este desafio é normalmente implementado pelo time de backend mas, como gostamos de desafios,
  porque não criarmos como seria a nova cara do paredão do BBB??
* Não se preocupe com o registro de candidatos e Paredões. Você pode popular a
  view da forma que achar mais conveniente.
* Gostamos sempre de ser surpreendidos... :wink:

OBS.: você não precisa enviar os dados ao servidor. Apenas simule o que você faria para montar a página que recebe as informações.

Após terminar, commite o seu código e faça um pull request para a branch master. forneça no arquivo README.MD como deve ser buildado e testado este seu applicativo.

Outra dica: nós iremos avaliar a estrutura do seu código e como você se mantem focado no que foi pedido. Cuide da estrutura, entregue com qualidade! Queremos saber mais como você cuida do seu código!

Em caso de duvida, entre em contato com a gente!


