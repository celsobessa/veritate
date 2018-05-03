# Veritate - Agregador e Buscador de Checagem de Fatos

Veritate é um projeto um **projeto experimental sem fins lucrativos** de agregador/buscador reunindo artigos diversas agências de **checagem de fatos**.
<hr>

> **For english version, [click here](README-EN.md).**

<hr>

Prova de conceito tem lançamento previsto para 7 de Maio de 2018.

> Para mais informações, para solicitar a inclusão de um site de checagem ou solicitar exclusão de material que viole direitos autorais, entre em contato através do email veritate{arroba}wowperations[ponto]com[ponto]br

## Sobre a iniciativa

Idealizado pelo desenvolvedor <a href="https://www.celsobessa.com.br">Celso Bessa</a>, com suporte em hospedagem e infra-estrutura: <a href="https://www.wowperations.com.br">WoWPerations</a>, a iniciativa  Veritate tem como objetivos:

- Investigar, estudar e experimentar tecnologias, algoritmo, padrões de design e experiência de uso em buscas e jornalismo intermediado por algoritmo
- Fomentar o consumo de jornalismo de qualidade e o compartilhamento de checagem de fatos e instigar o senso crítico contra notícias falsas (_Fake News_)
- Instigar o compartilhamento de checagens de fatos e o pensamento crítico contra notícias falsas
- Instigar o pensamento crítico e decisões bem informadas sobre políticas e votos.

Inicialmente, a iniciativa terá os seguintes componentes: Indexador, Índice Públic/API, e Agregador.

### Indexador

Uma ferramenta para indexação, avaliação e organização de artigos publicados em veículos de checagem de fatos.

No momento, estamos utilizando um serviço de terceiro (Saas) para rastreio (crawl) e raspagem de dados (scrapping) e um sistema próprio para avaliação e organização. É possível que num futuro próximoutilizemos infra-estrutura própria para rastreio/raspagem. Eventualmente, tornaremos o sistema de avaliação público.

### Índice Público (API)

Um índice público com informações sobre as checagem de fatos indexadas para consumo por sistemas, que poderão consultá-lo através de uma API REST, com informações apresentadas em JSON.

É a partir de sua API que alimentaremos o agregador, e serviços e sistemas de terceiros podem ser criados. Por exemplo, um plugin de WordPress que apresente checagem de fatos para alguma palavra chave sendo usada por um editor de um blog.

### Agregador

Uma ferramenta de busca de checagem de fatos, dirigida à pessoas. A ideia é que, por exemplo, uma pessoa procurando a expressão  "Lava Jato" veria uma série de links para checagens de fatos sobre a Operação Lava Jato no sites indexados, e ao clicar em cada link, lerá o conteúdo direto no site original.

## Perguntas Frequentes (FAQ - Frequently Asked Questions)

### Quais os veículos que são indexados por esta iniciativa?

Neste momento, apenas [Agência Lupa](http://piaui.folha.uol.com.br/lupa/), [Agência Pública](https://apublica.org/checagem/) and [Aos Fatos](https://aosfatos.org).

### Como posso sugerir um veículo ou ter meu veículo adicionado?

Envie um email para o endereço mencionado acima. Nós vamos indexar apenas sites respeitados ou com bom jornalismo, de acordo com nosso conselho editorial. Temos o plano de criar um guia editorial, mas não sabemos quando publicaremos.

No aspecto tecnológico, nós priorizamos sites usando WordPress e que usem o markup LD+JSON para checagem de fatos. Nosso rastreador e nosso algoritmo privilegia sites rápidos, acessíveis e seguros (usando HTTPS), especialmente os acessíveis facilmente por telefone ou leitores de tela. E se você der permissão expressão para apresentarmos pequenos trechos (entre 140 e 280 caracteres) do artigo de seu site, o conteúdo será rastreado mais rapidamente e terá prioridade ao apresentarmos os resultados

Como regra geral, *se for jornalismo bem feito, tiver boa nota no Google Page Speed Insights e passar no teste da WCAG2.0*, está bom para nós.

### Esta iniciativa tira tráfego dos sites de checagem?

Não! Ao contrário, os objetivos são gerar MAIS tráfego e melhorar ao alcance destes sites.

### Esta iniciativa atrapalha o SEO deste sites?

Não. Como é uma API, apenas deixa os dados acessíveis, mas não conta como conteúdo para buscadores

### Esta iniciativa tem um objetivo comercial?

Não, é um experimento sem fins lucrativos. Caso se torne algo maior, provavelmente como fundação, ONG ou algo assim, sem fim lucrativo, transparente e com a missão de fortalecer o "ecossistema" de checagem de fatos.

## Histórico de versões / Changelog

O arquivo [CHANGELOG.md](CHANGELOG.md) contém o histórico de versões da iniciativa de uma perspectiva global e alterações deste repositório. Cada componente (e seus possíveis sub-componentes) terão históricos (Changelogs) específicos e mais detalhados

## Como ajudar o projeto

Com código, redação de textos e ajuda e wiki, etc. Mais informações em breve.