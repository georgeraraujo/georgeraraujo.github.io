---
title: "Andamento e metrônomo"
date: 2021-11-03 16:00:00 -0300
categories:
  - bateria
tags:
  - bateria
excerpt_separator: "<!--more-->"
toc: true
toc_icon: "drum"
toc_label: "Sumário"
toc_sticky: true
---
Oi pessoal,  
hoje vamos falar de andamento e metrônomo, e vamos recomendar
um aplicativo de metrônomo para nossas práticas.
<!--more-->


## Andamento

O andamento é a velocidade de um trecho em uma peça musical.
É geralmente medido pelo número de tempos a executar em um minuto
de música, ou _batidas por minuto_ (**bpm**).
O termo _batidas_ vem do inglês _beats_, que corresponde a _tempos_.

{% capture informacao-1 %}
O(A) baterista deve permanecer atento(a) à diferença entre **tempos da fórmula
de compasso** e percussões (toques) nos tambores e nos pratos porque a velocidade
em bpm (batidas por minuto) **não necessariamente corresponde ao número de
percussões que o(a) baterista executa**:

- Um tempo em um compasso pode se subdividir em 2, 3 ou mais percussões;
- No tempo (ou subdivisão) em que ocorre uma pausa, o(a) baterista não percute
nenhum componente do _kit_.
{% endcapture %}

<div class="notice--info">
  {{ informacao-1 | markdownify }}
</div>

O andamento pode variar ao longo da música por meio de uma nova indicação
ou por palavras que indicam mudanças graduais de velocidade.


### Metrônomo

O metrônomo é um dispositivo que produz um som (por exemplo, tique-taque
ou estalo) e/ou um sinal visual em um intervalo regular definido pelo(a)
musicista, geralmente entre 40 e 208 bpm. O(A)s musicistas usam o metrônomo
para praticar e tocar. Um metrônomo é mostrado na figura a seguir:

{% capture fig_img %}
[![](/assets/images/Метроном_в_движении.gif)](https://commons.wikimedia.org/wiki/File:Метроном_в_движении.gif)
{% endcapture %}

{% capture fig_caption %}
Wikimedia Commons [(CC-BY-SA-3.0)](https://creativecommons.org/licenses/by-sa/3.0/deed.en)
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>{{ fig_caption | markdownify | remove: "<p>" | remove: "</p>" }}</figcaption>
</figure>

Além do aparelho mecânico mostrado na figura anterior, há também metrônomos
eletrônicos e aplicativos de metrônomo.

Em uma banda, a bateria – e, por extensão, o(a) baterista – é responsável
pelo andamento e pelo ritmo da música e **serve como metrônomo para os outros
instrumentos**. Para bem executar essa tarefa, o(a) baterista deve tocar
com regularidade e precisão, fundamentos que são desenvolvidos por meio
da prática.
{: .notice--info}


### Indicação de andamento e indicação metronômica

A **indicação de andamento** é grafada no início da peça musical, logo acima
da fórmula de compasso:

- em composições clássicas, consiste de uma instrução (um termo em italiano
ou em língua pátria) que indica uma _faixa aproximada_ de batidas por minuto;
- em composições modernas, a indicação pode também conter uma _indicação
metronômica_ exata que complementa ou simplesmente substitui a instrução
indicativa.

A **indicação metronômica** pode aparecer sozinha ou ao lado da instrução
indicativa e define a velocidade da música em notas por minuto, conforme
mostrado no exemplo a seguir:

![Indicação metronômica](/assets/images/exm-2.24-indicacao_metronomica.png)


### Andamentos em italiano

A relação de andamentos principais contida na tabela a seguir é baseada
na obra _Tipbook Music on Paper: Basic Theory_[^pinksterboer-2010]:

| Andamento   | Indicação metronômica | Descrição                |
|-------------|-----------------------|--------------------------|
| _Largo_     | ♩ = 40 − 60           | Bastante vagaroso        |
| _Adagio_    | ♩ = 66 − 76           | Vagaroso                 |
| _Andante_   | ♩ = 76 − 108          | Vagaroso a médio         |
| _Moderato_  | ♩ = 108 − 120         | Médio                    |
| _Allegro_   | ♩ = 120 − 168         | Depressa, rápido         |
| _Presto_    | ♩ = 168 − 200         | Bastante depressa, veloz |
|====
{: rules="groups"}

A tabela é exemplificativa. Vários textos descrevem outras relações
de andamentos, alguns deles com nomes baseados em subdivisões dos
apresentados. Além disso, a correspondência entre andamentos e
indicações metronômicas não é exata e varia conforme o(a) autor(a)
da peça e o estilo musical. A figura a seguir mostra a escala descrita
na obra _Compêndio de Teoria Elementar da Música_[^lacerda-1967]:

![Uma escala de andamentos](/assets/images/fig-2.4-andamentos_em_italiano.svg)


## _Metronomerous_

Em minhas práticas uso o [Metronomerous][metronomerous], um aplicativo
de metrônomo **gratuito** e **sem anúncios** que pode ser instalado em
celulares e _tablets_ Android e também tem uma versão que roda diretamente
em navegadores de Internet.
Tive a oportunidade de traduzir a interface e as páginas de ajuda
do aplicativo para português do Brasil.

É necessário conhecimento básico de notação musical e um pouco de tempo
para se familiarizar com ele. Tem os recursos que seguem:

- sem anúncios
- subdivisões: colcheias, semicolcheias, tercinas, quiálteras de cinco, quiálteras de sete
- acentos em qualquer nota de semicolcheia ou tercina
- definição de volumes diferentes para cada subdivisão ou acento
- definição de andamento por roda seletora, toque ou entrada numérica
- indicações de andamento em italiano
- marcação de andamento com _flash_ e vibração
- silêncio: _playback_ silenciável por um número configurável de compassos
- incremento de andamento: aumento gradual do andamento durante o _playback_
- vários sons para escolher, alguns deles editáveis
- salve suas configurações na Lista de Batidas
- programe sequências complexas de batidas (arranjos)
- compartilhe arranjos com outros usuários e dispositivos
- visualize o metrônomo em modo retrato ou paisagem
- vem com documentação de ajuda
- idiomas: inglês, alemão, russo e português brasileiro

Há metrônomos, inclusive comerciais, cujo ajuste de subdivisões se aplica
igualmente a todos os tempos de cada compasso. Por exemplo: um compasso
de quatro semínimas ajustado para quatro subdivisões terá dezesseis
semicolcheias por compasso. O Metronomerous se destaca porque permite
configurar as subdivisões **para cada tempo** de um compasso. Isso é
bastante útil porque é comum de se encontrar em exercícios de livros.

No primeiro exercício de [_Bass Drum Control_][bdc], por exemplo, devemos
tocar quatro semínimas e em seguida oito colcheias no bumbo; para fazer
isso, ajustamos o Metronomerous para que o compasso tenha oito tempos, e
em seguida ajustamos apenas os quatro últimos para se subdividir em colcheias.

![Exercício 1 de Bass Drum Control](/assets/images/Screenshot_20211103-180152_Metronomerous.jpg)


### Fechamento

Agora que sabemos o básico sobre andamento e metrônomo, é hora de
praticar! Use sempre o metrônomo em seus treinos. Comece devagar e
acelere o andamento (ou inclua subdivisões) progressivamente à medida
que evolui. A velocidade e a precisão estão ao seu alcance, e o metrônomo
está aí para ajudar.


[^pinksterboer-2010]: Pinksterboer, H. (2010). _Tipbook Music on Paper: Basic Theory_. Tipbook series. Hal Leonard Books. ISBN: 9781423465294.
[^lacerda-1967]: Lacerda, O. (1967). _Compêndio de Teoria Elementar da Música_. Ricordi Brasileira. ISBN: 9788599477281.
[metronomerous]: https://www.metronomerous.de/
[bdc]: https://colinbailey.me/bass-drum-control/
