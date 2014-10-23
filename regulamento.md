---
layout: page
title: Regulamento
permalink: /regulamento/
---

Este regulamento está ainda sujeito a alterações

## Composição das equipas

* As equipas participantes na MIUP são constituídas por, no máximo, 3 elementos. Estes elementos devem respeitar as normas de elegibilidade do ICPC (ver [Regional Rules, opção Team Composition][regrules], e [Eligibility Decision Tree][edt]).
* Cada equipa deverá ter um treinador, de preferência não participante, que será o representante da equipa antes e durante a competição.

## Inscrição de equipas

* Cada escola/faculdade pode apresentar no máximo 2 equipas. Se houver mais do que 2 equipas de uma escola/faculdade, a organização irá aceitar as primeiras duas equipas a serem inscritas de forma regular.
* Poderá ser permitida a participação eventual de 3 ou 4 equipas da mesma escola/faculdade, no caso de haver condições logísticas para tal. A escolha destas equipas ficará a cargo da organização da MIUP 2014.
* As inscrições das equipas têm que ser feitas obrigatoriamente no prazo definido pela organização.
* A participação de uma equipa está sujeita ao pagamento de uma inscrição de 50 euros na data do evento.

## Ambiente de trabalho

* Cada equipa terá direito a apenas um computador, equipado de maneira semelhante a todas as outras equipas.
* Cada equipa terá acesso aos compiladores de C, C++ e Java. Os programas deverão residir num ficheiro isolado e deverão obedecer às normas standard (ANSI-C). Será permitido o uso de STL no C++ e das packages de classes habituais do Java.
* As versões dos compiladores que estão disponíveis são o `Java 1.7.0._67` e o `GCC/G++ 4.8.2`
* As soluções serão compiladas/executadas com as seguintes flags:
  * `g++ -g -O2 -std=gnu++0x -static $*`
  * `javac -encoding UTF-8 -sourcepath . -d . $*` e `java -client -Xss8m -Xmx2048m $*`
* Todos os computadores estarão equipados com o sistema Linux e com os IDEs/editores habituais: `GEdit`, `KDevelop 4.6`, `Eclipse 3.8`, `Geany`, `Kate`, `Emacs 24.3.1`, `Nano 2.2.6` e `Vim 7.4`.
* O sistema de avaliação automática de submissões usado será o Mooshak.
* As equipas poderão levar material impresso (ver secção Material), estando impedidas de levar material em suporte informático ou calculadoras de bolso.

## Material

* Cada equipa pode ter no seu espaço da sala da competição um máximo de 25 páginas A4 impressas (não é aceite material manuscrito) com um tamanho de letra igual ou superior a 8. Cada elemento da equipa pode usar uma cópia exacta deste material. Qualquer outro material de auxilio não será permitido, com excepção da documentação online disponível no ambiente da competição.
* O material impresso tem que ser entregue ao júri da MIUP 2014 durante o processo de registo da equipa no dia da competição. Esse material será devolvido às equipas quando estas entrarem nas respectivas salas para a competição.
* A organização irá providenciar folhas A4 brancas. As equipas podem trazer réguas, compassos, lápis e canetas.

## Classificação

* As equipas são classificadas de acordo com o número de problemas resolvidos. Em caso de empate, serão classificadas pelo somatório dos tempos dos problemas resolvidos. O tempo de um problema é igual ao tempo passado desde o início da prova até à sua submissão correcta mais uma penalização de 20 minutos por cada submissão errada para esse problema.

## Desqualificação

* Se uma equipa não cumprir com todos os pontos que constam do regulamento poderá ser desqualificada antes, durante ou depois da prova.

## Apelos

* Apenas a violação do regulamento ou desqualificações por má conduta podem ser sujeitas a apelo. As decisões do júri de aceitar ou rejeitar submissões são finais e não podem ser objecto de reclamação ou apelo. Os apelos apenas podem ser apresentados pelo treinadores das equipas.

[regrules]: http://icpc.baylor.edu/regionals/rules#HTeamComposition
[edt]: http://icpc.baylor.edu/download/regionals/rules/EligibilityDecisionTree-13.pdf
