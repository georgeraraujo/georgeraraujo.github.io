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
às características da altura dos sons. Não há consenso na literatura
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

É possível distinguir entre dois sons de altura indefinida, isto é,
cujos espectros são inarmônicos, qual é mais alto e qual é mais baixo
se a maioria de suas componentes espectrais de maior intensidade estiver
concentrada em bandas diferentes (uma mais aguda, outra mais grave)
do espectro sonoro.
{: .notice}


### Espectrograma

Em Acústica, **espectrograma** é uma representação gráfica do espectro
de um som em função do tempo.

Os espectrogramas geralmente mostram três propriedades de cada componente
espectral[^9] em um gráfico cartesiano bidimensional: a frequência,
o momento em que ocorre, e a intensidade. Um dos eixos representa a
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


## Alguns termos subjetivos da Acústica

A Acústica adotou vários termos subjetivos para descrever as sensações
auditivas que resultam do processamento dos estímulos sonoros pelo cérebro.
Alguns desses termos, que complementam e enriquecem as caracterizações físicas
dos sons com descrições visuais e sensoriais, são úteis para descrever
a sonoridade de tambores e pratos.

Vários dos termos, originados do estudo da acústica de salas de concerto
e do ramo de gravação e reprodução sonora, bem como de sítios de internet,
fazem referência às faixas de frequência (grupos) do campo auditivo
e às bandas nas quais eles se subdividem.

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

O conceito de calidez foi definido com maior detalhe por
M. Long (LONG, 2014)[^long-2014] com o auxílio do termo _reverberação_:

- **Reverberação:** a continuação do som no ambiente depois que
a fonte sonora deixa de produzi-lo;
- **Calidez** (_warmth_)**:** reverberação das baixas frequências,
entre 75 e 350 Hz.


### Termos originados do ramo de gravação e reprodução sonora

Os termos a seguir foram obtidos de sítios de internet e adaptados
para este texto.

- **Corte:** a capacidade do som (geralmente alto ou forte) de "cortar"
a música ao redor e se fazer ouvir com clareza entre os sons produzidos
por outros instrumentos;
- **Estridente:** som excessivo em médios e/ou agudos, que causa fadiga
auditiva no(a) ouvinte;
- **Quente** (_warm_)**:** som com graves e médios-graves entre moderados
e proeminentes, e agudos suaves e sem estridência;
- **Escuro** (_dark_)**:** som que combina graves e médios-graves
proeminentes em forte contraste com agudos recuados; um som quente
especialmente rico em graves e pobre em agudos. O oposto de _brilhante_.
Alguns textos também descrevem o som com característica escura
como **aveludado** ou **encorpado**;
- **Brilhante** (_bright_)**:** som que combina médios-agudos e agudos
proeminentes em forte contraste com graves recuados.
Tem bastante _corte_. O oposto de _escuro_.


### Termos específicos para pratos

Os termos a seguir, a menos de _"shimmer"_, foram obtidos de sítios
de internet e adaptados para este texto.

- **Resposta** (_response_)**:** a combinação da característica
(_seca_ ou _viva_) e da velocidade (mais/menos _rápida_) com as quais
o prato reage – "abre" – ao ser tocado;
- **Seco** (_dry_)**:** prato com som curto e bastante definido, pobre
em parciais e com pouco _wash_. Contrastar com _vivo_;
- **Vivo** (_lively_)**:** prato com som vibrante, rico em parciais
e com _wash_ de moderado a proeminente. Contrastar com _seco_.
Um prato com som especialmente vivo é dito _explosivo_;
- **Rápido** (_fast_)**:** prato (geralmente de ataque ou de corte)
que responde – "abre" – quase imediatamente e por toda sua área ao ser tocado;
- **Sujo** (_trashy_)**:** prato cujo som tem bastante energia nas
bandas de médios e médios-agudos, que ao se mesclar com as demais
frequências resulta em uma combinação áspera e complexa;
- **_Ping_:** som do estágio de ataque ao tocar o prato
(geralmente de condução) com a ponta da baqueta. Vem antes do _wash_;
  - **_Pingy_:** prato com _ping_ nítido e articulado, claramente distinto do _wash_;
- **_Wash_:** som dos estágios de sustentação e decaimento. Vibrante.
Vem depois do _ping_;
  - **_Washy_:** prato com _wash_. Produz um som vibrante e espalhado (_spread_) por uma ampla faixa de frequências;
- **_Shimmer_** ("som prateado")**:** conforme definido por
Rossing (ROSSING, 2000)[^rossing-2000], agudos entre 3 e 5 kHz
que se sobressaem na mescla de frequências do _wash_ e evocam
a sensação de brilho trêmulo;
  - **_Shimmering_:** prato com _shimmer_ proeminente.


[audio-spectrum-explained]: https://www.teachmeaudio.com/mixing/techniques/audio-spectrum/
[audio-frequency-spectrum-cheatsheet]: https://bestmusicstuff.com/products/audio-frequency-spectrum-cheatsheet
[Flute.nonvib.ff.A4.stereo.aif]: http://theremin.music.uiowa.edu/MIS-Pitches-2012/MISFlute2012.html
[60s-Rogers-Pop-Kit]: https://www.drum-drops.com/products/60s-rogers-pop-kit
[^beranek-2003]: Beranek, L. (2003). _Concert Halls and Opera Houses: Music, Acoustics, and Architecture_. Springer New York. ISBN: 9780387955247.
[^long-2014]: Long, M. (2014). _Architectural Acoustics_. Elsevier Science. ISBN: 9780123982650.
[^9]: Os sons simples que formam um som composto, cada um com sua frequência e amplitude.
[^rossing-2000]: Rossing, T.D. (2000). _Science of Percussion Instruments_. Series in popular science. World Scientific. ISBN: 9789810241582.
