
---
title: "A coalizão do BBB"
date: 2020-08-14
tags:
  - estatística
---

A última edição do BBB acabou faz tempo. Porém, durante o fervor do programa nas redes, fiquei me questionando se havia alguma estratégia dominante para algum dos participantes. 
Evidentemente, é um jogo subjetivo que se baseia no voto popular (que ultrapassa a população brasileira em 2 vezes), logo, não há nenhum tipo de racionalidade general que se aplique aos participantes específicos. O amado hoje é odiado amanhã, e isso acontece com todas as suas combinações de sentimento durante a duração do programa.

Mas como é divertido modelar situações irrealistas, podemos imaginar um cenário onde o BBB não tem voto popular. A exclusão dos participantes ocorre de maneira aleatória. Então, nessa abstração da realidade, o ambiente físico desse jogo é:

1. Existem 20 jogagores;
2. As rodadas são formadas por todos os participantes;
3. A cada rodada, sai apenas 1 jogador;
4. A última rodada é formada por 3 jogadores.
5. A probabilidade de sair é idêntica para todos os jogadores.

Nessas configurações, a probabilidade de qualquer um dos jogadores ganhar o BBB é igual. Logo, é sem graça

Um possível estratégia que fugiria dessa situação homogênea seria uma coalizão. Na coalizão, um grupo de pessoas pode fazer com que a probabilidade de sair das pessoas fora da coalizão seja maior do que a probabilidade dos membros do grupo. O equivalente no mundo real seria um conjunto de pessoas que se comportam de certa maneira que faz com que a chance de alguém do grupo sair do jogo seja menor do que alguém fora do grupo. Então, podemos remodelar o ambiente físico do jogo:

1. Existem 20 jogagores;
2. Existem M pessoas dentro da coalizão;
3. As rodadas são formadas por todos os participantes;
4. A cada rodada, sai apenas 1 jogador;
5. A última rodada é formada por 3 jogadores.
6. A probabilidade de alguém da coalizão sair é menor que a probabilidade de alguém fora da coalizão sair.
7. O prémio é dividido igualmente entre os membros da coalizão, caso haja vitória de algum membro.

A pergunta que resta é: **Quantos pessoas é preciso que a coalizão tenha para que algum dos membros ganhe com certeza o jogo?**


