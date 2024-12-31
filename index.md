---
title: Lei de Ampère-Maxwell
---

<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/3.2.2/es5/tex-mml-chtml.js"></script>


# Lei de Ampere-Maxwell 

## História

O interesse inicial que estimulou pesquisadores a investigar uma relação entre corrente e campo magnético decorreu de uma observação feita em 1820 por Hans Christian Ørsted, onde percebeu que agulhas magnetizadas eram desviadas por correntes elétricas. Com isso, diversos físicos começaram a estudar o assunto separadamente, e nisso André-Marie Ampère propôs um experimento focado em medir as forças que dois fios elétricos exercem um sobre o outro.

Com isso, Ampère formulou a lei conhecida com seu nome, "lei de Ampère, em 1826, onde relacionou campos magnéticos associados a um circuito fechado à corrente eletrica que passava por eles. Na sua forma original, a corrente presa no loop só se refere a que decorre por partículas que se movem livremente, o que causa alguns problemas sobre a conservação de corrente elétrica e propagação da energia eletromagnética. **(revisar)**

Em 1861, James Clerk Maxwell extendeu a lei de Ampère, introduzindo a corrente de deslocamento no termo de corrente elétrica para satisfazer a equação de continuidade de carga elétrica. Usando como base a corrente de deslocamento, Maxwell estabeleceu a teoria do campo eletromagnético. Somente no final da década de 1880, Heinrich Hertz provou com experimentos a existência de ondas eletromagnéticas, previsto anteriormente por Maxwell.

## Definição

Retomando a Lei de Ampère original, temos que ela relaciona o campo magnético que circula em um loop fechado com a corrente elétrica nesse mesmo ambiente. Porém, mudanças no tempo em campos elétricos devem produzir campos magnéticos, fenômeno esse observado por Maxwell e não explicado na lei original. 

A equação de Ampère-Maxwell é dada como o seguinte, sobre uma superfície com curva $C$, escrita da forma integral:

$$
\int_{S} \bold{\nabla \times b \cdot da} = \oint \bold{B \cdot dl} = \mu_0 \left( I + I_D \right).
$$

Onde:

$$
I_D = \varepsilon_0 \frac{d}{dt} \int \bold{e} \cdot \bold{\hat{n}} \ da.
$$

Temos então, visualizando de forma completa:

$$
\oint \bold{B \cdot dl} = \mu_0 \left( I + \varepsilon_0 \frac{d}{dt} \int \bold{e} \cdot \bold{\hat{n}} \ da \right).
$$

Sendo os termos:

- $\bold{C}$: campo magnético;
- $\bold{e}$: campo elétrico;
- $\bold{I}$: corrente elétrica que atravessa $S$;
- $\bold{I_D}$: corrente de deslocamento;
- $\mu_0$: permeabilidade magnética do meio;
- $\varepsilon_0$: permissivide elétrica do vácuo;
- $\hat{\bold{n}}$: vetor normal unitário à superfície $S$;

O primeiro termo da parte direita da primeira equação relaciona a corrente $I$ e o campo magnético $\bold{B}$ em torno de uma curva $C$. É a contribuição original feita por Ampère, onde $I$ diz sobre todas as correntes não dependendo do eu local de origem.

A segunda parte é a contribuição feita por maxwell e mostra que a circulação do campo magnético também é causada pela variação do fluxo elétrico. 

## Aplicação em um Capacitor

Seja um capacitor duas placas condutoras separadas por algum material dielétrico. Considere o processo de carga deste capacitor. Quando ele está em um circuito e uma corrente o atravessa, temos alguns acontecimentos:

- Antes de chegar às placas do capacitor, é possível medir a corrente elétrica $I$ no fio condutor.
- Entre as placas do capacitor, não há condução de corrente porque o material dielétrico impede o fluxo da carga $I$.

Temos que dentro do capacitor, mesmo sem a corrente, ainda existe um campo magnético detectável ao redor das placas. Isso mostra que a equação original de Ampère não consegue descrever o campo magnético em todas as situações, pois, na equação original:

$$
\oint \bold{B} \cdot d \bold{l} = \mu_0 I
$$

Como $I = 0$, não há explicação do porquê existir campo magnético detectável.

Maxwell corrigiu esse problema adicionando o termo de corrente de deslocamento, resultando na equação apresentada anteriormente. O temo adicionado diz sobre a corrente associada à variação no campo elétrico entre as placas do capacitor.

Logo, enquanto o capacitor está carregando ou descarregando, o campo elétrico $\bold{e}$ entre as placas se altera com o passar do tempo, e essa variação gera uma corrente de deslocamento - equivalente em termos de magnitude à corrente de condução que está alimentando o capacitor. 

## Aplicações no Dia-a-Dia

Muitas das aplicações, mesmo extremamente importantes para o mundo moderno, estão sob algumas camadas de abstração e podem estar pouco distante do nosso cotidiano. Porém, diversas tecnologias que são essenciais atualmente utilizam conceitos de eletromagnetismo e tem a lei de Ampère-Maxwell como uma de suas bases, entre elas transmissão de dados por fibra optica e sistemas de carregamente sem fio.

Na transmissão de dados por fibra optica, os cabos transmitem informações por pulsos de luz, que é uma forma de onda eletromagnética. Por conta da lei de Ampère-Maxwell, sabemos que a mudança de campos elétricos podem criar campos magnéticos (o contrário também sendo verdade) e isso é utilizado para gerenciar a propagação de luz dentro do cabo.

Além disso, sistemas de carregamento sem fio utilizam conceitos abordados. Com a adição feita por Maxwell, é possível projetar dispositivos que carregam dispositivos como smartphones, por exemplo. Eles funcionam da seguinte maneira: coils geram campos magnéticos que variam de acordo com o tempo, com isso induzem correntes em coils próximos (o do dispositivo a ser carregado). Com o conhecimento adicionado, podemos transmitir energia por meios não metálicos!
