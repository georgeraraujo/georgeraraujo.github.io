---
title: "Glossário"
permalink: /glossario/
toc: true
toc_icon: "drum"
toc_label: "Sumário"
toc_sticky: true
---

Esta página traz um glossário de termos subjetivos da Acústica
para descrever a sonoridade de tambores e pratos. Antes de elencar
os termos, é necessário apresentar alguns conceitos.

## Espectro sonoro e campo auditivo

O **espectro sonoro** é o conjunto de frequências de vibração que compõem
todos os sons, tanto os audíveis para o ser humano quanto os inaudíveis.

- **Infrassom** é qualquer som com frequência maior que 0 Hz e menor
que 20 Hz. É inaudível;
- **Campo auditivo** é a faixa de frequências que o ouvido de um ser
humano adulto consegue captar, e vai de 20 Hz a 20 kHz;
- **Ultrassom** é qualquer som com frequência maior que 20 kHz e menor
que 1 GHz;
- **Hiper-som** é qualquer som com frequência maior que 1 GHz.

O campo auditivo pode ser dividido em faixas de frequência
denominadas **grupos**. Os grupos se subdividem em bandas correspondentes
às características da altura (frequência) dos sons. Não há consenso na literatura
sobre a quantidade de grupos nem sobre as faixas de frequência, que
dependem do campo de aplicação. Uma divisão baseada no
artigo [_Audio Spectrum Explained_][audio-spectrum-explained] e na
referência [_Audio Frequency Spectrum Cheatsheet_][audio-frequency-spectrum-cheatsheet]
é ilustrada na tabela a seguir:

| Grupo | Banda | Faixa de frequência |
|:-|:-|:-:|
| Agudos | Presença      | 6 − 20 kHz     |
|        | Brilho        | 4 − 6 kHz      |
|----
|        | Médios-agudos | 2 − 4 kHz      |
| Médios | Médios        | 500 Hz − 2 kHz |
|        | Médios-graves | 250 − 500 Hz   |
|----
| Graves | Grave         | 60 − 250 Hz    |
|        | Subgrave      | 20 − 60 Hz     |
|====
{: rules="groups"}

O campo auditivo pode ser mostrado graficamente como na figura a seguir:

![Grupos e bandas de frequência do campo auditivo](/assets/images/fig-4.8-campo_auditivo.svg)

## Representações gráficas do som

É possível representar graficamente as propriedades dos sons para melhor
compreendê-los e analisá-los. Três dessas representações são
a **forma de onda**, o **espectro** e o **espectrograma**, descritos
nas seções a seguir.

### Forma de onda

**Forma de onda** é a representação gráfica em um plano cartesiano
da amplitude de uma onda em função do tempo.

A forma de onda de [um bumbo Rogers de 22"][60s-Rogers-Pop-Kit] é mostrado na figura a seguir:

![Forma de onda](/assets/images/fig-4.9-forma_de_onda.png)

### Espectro de um som

**Espectro** de um som é uma representação gráfica das amplitudes
ou intensidades (energia) dos sons simples de um som composto em função
das respectivas frequências para um dado trecho (janela de análise)
do sinal sonoro. Esses sons simples, cada um com sua frequência
e amplitude, são chamados de **componentes espectrais**.

- Um espectro é dito **harmônico** se as frequências de todos os
parciais são múltiplos da frequência fundamental por um número inteiro.
- Um espectro é dito **inarmônico** se a frequência de algum parcial
não é um múltiplo da frequência fundamental por um número inteiro.

O espectro a partir de 1 segundo
de [uma flauta que toca a nota Lá central (440 Hz)][Flute.nonvib.ff.A4.stereo.aif]
é mostrado na figura a seguir. Embora existam parciais cujas frequências
não são múltiplos da frequência fundamental por um número inteiro,
a frequência fundamental e os harmônicos são claramente identificáveis
e predominantes em intensidade e por isso o espectro é aproximadamente
harmônico:

![Espectro a partir de 1 s de uma flauta que toca a nota Lá central](/assets/images/fig-4.10-spec2dw.png)

O espectro do momento inicial da percussão de um bumbo Rogers de 22",
nitidamente inarmônico, é mostrado na figura a seguir:

![Espectro do momento inicial da percussão de um bumbo Rogers de 22"](/assets/images/fig-4.11-spec2dw.png)


### Espectrograma

Em Acústica, **espectrograma** é uma representação gráfica do espectro
de um som em função do tempo.

O espectrograma mostra três propriedades de cada componente
espectral[^9] em um gráfico cartesiano bidimensional: a frequência,
o momento em que ocorre, e a intensidade. Um eixo representa a
frequência e o outro representa o tempo; a intensidade de uma dada
frequência em um dado momento é indicada pela cor do ponto que a
representa.

Um espectrograma 2D da percussão de um bumbo Rogers de 22" é mostrado
na figura a seguir. A maior parte da energia está no grupo dos graves,
formado pelas bandas subgrave e grave:

![Espectrograma 2D de um bumbo Rogers de 22"](/assets/images/fig-4.12-spectrogram-bands.png)

## Estágios da duração de um som

A forma de onda de um som produzido por um instrumento musical
pode ser subdividida em estágios de intensidade (amplitude) crescente,
decrescente, constante e novamente decrescente, conforme ilustrado
na figura a seguir:

![Estágios da duração de um som produzido por um instrumento musical](/assets/images/fig-4.13-ADSR_csound.svg)

Os estágios são descritos a seguir:

- **Ataque (A):** o intervalo de tempo entre o silêncio e a intensidade
máxima do som;
- **Decaimento (D):** o intervalo de tempo entre a intensidade máxima
e a estabilização da intensidade do som;
- **Sustentação (S):** o intervalo de tempo em que o som tem intensidade
aproximadamente estável;
- **Repouso (R):** o intervalo de tempo da queda da intensidade do som
de aproximadamente estável para o silêncio.

A forma geométrica produzida pela variação de amplitude é chamada
de **envoltória** ou **envelope ADSR**.


### Estágios nos instrumentos de percussão

Em tambores e pratos de bateria, o estágio de ataque geralmente é
bastante curto porque ao percutir o instrumento a intensidade aumenta
repentinamente em um intervalo de tempo bastante reduzido, conforme
ilustrado na figura a seguir:

![Envelope ADSR de um bumbo Rogers de 22"](/assets/images/fig-4.14-envelope.png)

Quando um(a) baterista ou fabricante de baterias ou pratos usa o
termo _decaimento_, geralmente se refere ao estágio de **repouso**.
Este texto adota essa abordagem.
{: .notice}


## Extensão e tessitura

**Extensão** é definida na [Wikipedia][wikipedia-extensao] como segue:

> Em música, o termo **extensão** refere-se ao conjunto de todas as notas que um
> determinado instrumento musical ou uma voz é capaz de emitir, independente
> _(sic)_ da qualidade produzida. _(grifo conforme o original)_

**Tessitura** é definida na [Wikipedia][wikipedia-tessitura] como segue:

> Na música, **tessitura** refere-se ao conjunto de notas usadas por um determinado
> instrumento musical, com a qualidade necessária à sua execução. No
> caso da voz humana, refere-se ao conjunto de notas que um cantor consegue
> articular sem esforço excessivo de modo que seja produzida com a qualidade
> necessária. A tessitura tem, portanto, uma abrangência menor que a extensão.
> Enquanto que a extensão representa todas as notas **fisicamente** realizáveis, a
> tessitura refere-se às notas mais frequentemente **utilizáveis**. (grifos conforme o
> original)

Os tambores e pratos da bateria são instrumentos de percussão
de altura **indefinida** porque produzem notas cuja altura não pode ser distinguida
pelo(a) ouvinte – **ruídos**. Mas têm extensão e tessitura, conforme Hugo Pinksterboer expõe
em sua obra _The Cymbal Book_[^pinksterboer-1993] a respeito dos pratos:

> Pratos são instrumentos de altura indefinida. Se um prato vai ser considerado
> agudo, médio ou grave vai depender da faixa **dominante** de frequência,
> ou **tessitura**. **Um bom prato produz frequências em cada uma dessas três
> áreas**. Todas elas têm uma certa função no som. **As proporções entre elas
> determinam em grande medida qual é a característica do prato**. _(grifos nossos)_


## Alguns termos subjetivos da Acústica

A Acústica adotou vários termos subjetivos para descrever as sensações
auditivas que resultam do processamento dos estímulos sonoros pelo cérebro.
Alguns desses termos, que complementam e enriquecem as caracterizações físicas
dos sons com descrições visuais e sensoriais, são úteis para descrever
a sonoridade de tambores e pratos.

Vários dos termos fazem referência às faixas de frequência (grupos) do
campo auditivo e às bandas nas quais eles se subdividem.

### Termos originados do estudo da acústica de salas de concerto

Os termos _calidez_, _escuro_ e _brilhante_ foram definidos
por L. Beranek (BERANEK, 2003)[^beranek-2003] conforme descrito a seguir:

- **Calidez** (_warmth_)**:** de forma geral, a calidez da música de uma
orquestra em uma sala de concerto está diretamente relacionada
à audibilidade dos sons graves; e, em termos técnicos, é determinada
pela intensidade desses mesmos sons. Um som grave claramente audível
é dito _cálido_ ou **quente**;
- **Escuro** (_dark_)**:** um ambiente onde os sons graves são
demasiado intensos;
- **Brilhante** (_bright_)**:** um som definido, metálico e vibrante,
com agudos proeminentes de decaimento lento e rico em harmônicos.

É comum descrever a tessitura de um prato ou tambor
como **quente**, **escura** ou **brilhante**.
Alguns textos também descrevem o som de tessitura escura
como **aveludado** ou **encorpado**.

O conceito de calidez foi definido com maior detalhe por
M. Long (LONG, 2014)[^long-2014] com o auxílio do termo _reverberação_:

- **Reverberação:** a continuação do som no ambiente depois que
a fonte sonora deixa de produzi-lo;
- **Calidez** (_warmth_)**:** reverberação das baixas frequências,
entre 75 e 350 Hz.


## Alguns termos descritivos para pratos

O(A)s bateristas usam termos peculiares para descrever características dos pratos. Alguns
desses termos são apresentados a seguir.

### Articulação de baqueta, _ping_ e _wash_

Os termos a seguir são de autoria de Francisco Domene, proprietário da fabricante de pratos
Domene Cymbals, em uma [publicação][instagram-domene] no perfil da empresa no Instagram:

- **Articulação de baqueta:** é o som do estalo da baqueta no prato;
- **_Ping_:** é o som do metal, como um martelo batendo na bigorna de um ferreiro.

Os termos a seguir são de autoria de Mike Fitch, em seu
artigo [_Technique: Finding The Perfect Ride Cymbal_][finding-perfect-ride]:

- **Definição de baqueta:** é o som (condução[^10] ou _ping_) que o prato faz quando percutido
pela ponta da baqueta;
- **_Wash_:** é a mescla de sobretons criada pela vibração do prato.

Os termos a seguir são de autoria de Casey Scheuerell,
em sua obra _Berklee Jazz Drums_ (SCHEUERELL, 2018)[^scheuerell-2018]:

- **Estalo/Som de baqueta:** é o tanto de baqueta que ouvimos. Se você tocar com uma
baqueta de madeira em um tampo de mesa de madeira, vai ouvir um "clique" que
decorre do ataque da baqueta. A parcela desse clique que ouvimos ao tocar o prato é
chamada "estalo". Também é descrita com frequência como "som de baqueta";
- **_Wash_:** descreve o som do prato que não é o som do ataque inicial.

#### Comentário sobre a diferença entre som de condução e _ping_

O termo "definição de baqueta" de Fitch abrange dois sons:

1. condução;
2. _ping_.

São sons com características diferentes. Hugo Pinksterboer,
em sua obra _The Cymbal Book_[^pinksterboer-1993], dá a seguinte orientação
para escolher pratos de condução:

> Escute o tipo de som do ataque – o que você escuta no momento que a baqueta
> toca o prato. Pode variar do som que é comumente descrito como _ping_, que é
> bastante **brilhante**, até um "tique" extremamente seco ou gutural. _(grifo nosso)_

Trazemos novamente a definição de "brilhante" de L. Beranek[^beranek-2003]:

> Um som definido, metálico e **vibrante**, com **agudos proeminentes** de decaimento
> lento e rico em harmônicos. _(grifos nossos)_

A definição de _ping_ de Domene, descrita no começo desta seção, segue a mesma linha:

> É o som do metal, como um martelo batendo na bigorna de um ferreiro.

Com estas definições, podemos agora diferenciar com exatidão o som de condução e o _ping_:

- O som de condução – apenas o som do ataque, sem _wash_ – **não tem** agudos proeminentes
e **não é** vibrante;
- O _ping_ **tem** agudos proeminentes e **é** vibrante.

Por fim, o _ping_ é comumente associado ao prato de condução. Para produzi-lo, o(a) baterista
percute a cúpula do prato ou a área circunvizinha.

#### Comentário sobre a diferença entre os sons de condução do chimbal e do prato de condução

Dois pratos têm por função básica tocar a condução: o chimbal (_hi-hat_)
e o prato de condução (_ride_). Tratamos a seguir da diferença entre os sons
de condução produzidos por cada um.

- O chimbal, mantido fechado e tocado com as baquetas, produz um som compacto
e definido – o "clique" do ataque da baqueta – ao qual não se segue _wash_ porque a
pressão no pedal mantém os pratos juntos em uma posição fixa e os impede de vibrar
livremente;
- O prato de condução, por sua vez, vibra livremente após ser percutido na área de
condução, e por isso seu som de condução será seguido por _wash_.

Podemos então concluir que a diferença entre os sons de condução do chimbal (mantido
fechado e tocado com as baquetas) e do prato de condução é que o primeiro não é seguido
por _wash_, e o segundo é.

### Termos descritivos para o _wash_

Há fabricantes de pratos que descrevem o _wash_ de alguns modelos como "sujo" e
o de outros como _shimmering_:

- **Sujo** (_trashy_)**:** de acordo com o site do artesão [Craig Lauritsen][lauritsen],
"muitos sons inarmônicos (particularmente na faixa de frequência de médios a
agudos) de presença similar no _wash_, que resultam em um _wash_ complexo de
tessitura indistinguível". Essa descrição é comumente aplicada a pratos _china_;
- **_Shimmer_** ("som prateado")**:** conforme definido por
Rossing (ROSSING, 2000)[^rossing-2000], agudos entre 3 e 5 kHz
que se sobressaem na mescla de frequências do _wash_ e evocam
a sensação de brilho trêmulo;
  - **_Shimmering_:** prato com _shimmer_ proeminente.

### Características funcionais

Dos termos a seguir, "corte" foi obtido do site da fabricante [Sabian][sabian] e
os demais foram obtidos e adaptados do site da fabricante [Paiste][paiste]:

- **Corte:** a capacidade do som (geralmente alto ou forte) de "cortar"
a música ao redor e se fazer ouvir com clareza entre os sons produzidos
por outros instrumentos;
- **Seco** (_dry_)**:** prato com som compacto e definido, com pouco ou
nenhum _wash_. Contrastar com _vivo_;
- **Vivo** (_lively_)**:** prato com som vibrante e _wash_ de moderado a
proeminente. Contrastar com _seco_.
Um prato com som especialmente vivo é dito _explosivo_;
- **Rápido** (_fast_)**:** prato (geralmente de ataque ou de corte)
que responde – "abre" – quase imediatamente e por toda sua área ao ser tocado;
- **Resposta** (_response_)**:** a combinação da característica
(_seca_ ou _viva_) e da velocidade (mais/menos _rápida_) com as quais
o prato reage – "abre" – ao ser tocado.


[audio-spectrum-explained]: https://www.teachmeaudio.com/mixing/techniques/audio-spectrum/
[audio-frequency-spectrum-cheatsheet]: https://bestmusicstuff.com/products/audio-frequency-spectrum-cheatsheet
[Flute.nonvib.ff.A4.stereo.aif]: http://theremin.music.uiowa.edu/MIS-Pitches-2012/MISFlute2012.html
[60s-Rogers-Pop-Kit]: https://www.drum-drops.com/products/60s-rogers-pop-kit
[^9]: Os sons simples que formam um som composto, cada um com sua frequência e amplitude.
[wikipedia-extensao]: https://pt.wikipedia.org/wiki/Extens%C3%A3o_(m%C3%BAsica)
[wikipedia-tessitura]: https://pt.wikipedia.org/wiki/Tessitura
[^pinksterboer-1993]: Pinksterboer, H. (1993). _The Cymbal Book_. Hal Leonard. ISBN: 9781476866390.
[^beranek-2003]: Beranek, L. (2003). _Concert Halls and Opera Houses: Music, Acoustics, and Architecture_. Springer New York. ISBN: 9780387955247.
[^long-2014]: Long, M. (2014). _Architectural Acoustics_. Elsevier Science. ISBN: 9780123982650.
[instagram-domene]: https://www.instagram.com/p/CLc2_xdjX2l/
[finding-perfect-ride]: https://www.harmonycentral.com/articles/drum-and-percussion/technique-finding-the-perfect-ride-cymbal-r555/
[^10]: Pulso constante que faz a manutenção do tempo (em inglês, _timekeeping_).
[^scheuerell-2018]: Scheuerell, C. (2018). _Berklee Jazz Drums_. Berklee Press. ISBN: 9781540021663.
[lauritsen]: http://www.cymbalutopia.com/www.cymbalutopia.com/Cymbals_101_%26_Weight_Table.html
[sabian]: https://sabian.com/education/
[paiste]: https://www.paiste.com/en/about/everything-cymbals/cymbal-sound-classification-system
[^rossing-2000]: Rossing, T.D. (2000). _Science of Percussion Instruments_. Series in popular science. World Scientific. ISBN: 9789810241582.
