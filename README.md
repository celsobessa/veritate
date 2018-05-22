# Veritate - Agregador e Buscador de Checagem de Fatos

Veritate é um **projeto experimental sem fins lucrativos** para fortalecer checagens de fatos no Brasil. Composto por [Indexador](#indexador), [Índice Público/API](#indice-publico-api), e [Agregador/Busca](#agregador-busca) reunindo artigos diversas agências de **checagem de fatos**.
<hr>

> **For english version, [click here](README-EN.md).**

<hr>

> Para mais informações, para solicitar a inclusão de um site de checagem ou solicitar exclusão de material, visite a *[Wiki do Projeto](https://github.com/celsobessa/veritate/wiki)* ou entre em contato através do email veritate{arroba}wowperations[ponto]com[ponto]br

## Sobre a iniciativa

Idealizado pelo desenvolvedor <a href="https://www.celsobessa.com.br">Celso Bessa</a>, com suporte em hospedagem e infra-estrutura: <a href="https://www.wowperations.com.br">WoWPerations</a>, a Iniciativa Veritate tem como missão fortalecer o jornalismo de checagem de fatos no Brasil:

- Incentivar o consumo de jornalismo de qualidade
- Estimular o compartilhamento de checagens de fatos
- Instigar o senso crítico a respeito de notícias falsas (_Fake News_)
- Fornecer ferramentas que ajude as pessoas a tomar decisões baseadas em informações verídicas
- Pesquisar, experimentar, desenvolver e divulgar tecnologias, algoritmos, padrões de design e melhores práticas para jornalismo digital.

Inicialmente, a iniciativa conta com os seguintes componentes: [Indexador](#indexador), [Índice Público/API](#indice-publico-api), e [Agregador/Busca](#agregador-busca).

### Visão Geral - Veritate

![Diagrama com Visão Geral da Iniciativa Veritate - Versão 0.1.0](images/veritate-diagrama-visao-geral-0.1.0.png)

Para saber mais detalhes sobre cada componente, visite a *[Wiki do Projeto](https://github.com/celsobessa/veritate/wiki)*

## Perguntas Frequentes (FAQ - Frequently Asked Questions)

### Quais os veículos que são indexados por esta iniciativa?

Neste momento, apenas [Agência Lupa](http://piaui.folha.uol.com.br/lupa/), [Agência Pública](https://apublica.org/checagem/) and [Aos Fatos](https://aosfatos.org).

### Como posso sugerir um veículo ou ter meu veículo adicionado?

Se você quer sugerir algum veículo para ser indexado, abra uma "issue" [no repositório oficial](https://github.com/celsobessa/veritate/issues) com as seguintes informações:

- Nome do Veículo
- URL do veículo
- URL da seção de checagens (se diferente da URL principal)
- Sua relação com o veículo (leitor, autor, editor, publisher, etc)

Você também pode enviar um email para o endereço mencionado acima com as mesmas informações. Nós vamos indexar apenas sites respeitados ou com bom jornalismo, de acordo com nosso conselho editorial. Temos o plano de criar um guia editorial, mas ainda não sabemos quando ele será publicado.

No aspecto tecnológico, nós priorizamos sites usando WordPress e que usem o markup LD+JSON para checagem de fatos. Nosso rastreador e nosso algoritmo privilegia sites rápidos, acessíveis e seguros (usando HTTPS), especialmente os acessíveis facilmente por celulares ou leitores de tela. E se você der permissão expressa podemos apresentar pequenos trechos (entre 140 e 280 caracteres) do artigo de seu site, para que o conteúdo seja rastreado mais rapidamente e tenha prioridade entre os resultados.

Como regra geral, *se for jornalismo bem feito, tiver boa nota no Google Page Speed Insights e passar no teste da WCAG2.0*, está bom para nós.

### Esta iniciativa tira tráfego dos sites de checagem?

Não! Ao contrário: o objetivo é gerar MAIS tráfego e melhorar ao alcance destes sites.

### Esta iniciativa atrapalha o SEO deste sites?

Não. Como é uma API, apenas deixa os dados acessíveis, mas não conta como conteúdo para buscadores.

### Esta iniciativa tem um objetivo comercial?

Não, é um experimento sem fins lucrativos. Caso se torne algo maior, provavelmente será como fundação, ONG ou algo assim, sem fins lucrativos, transparente e com a missão de fortalecer o "ecossistema" de checagem de fatos.

## Histórico de versões / Changelog

O arquivo [CHANGELOG.md](CHANGELOG.md) contém o histórico de versões da iniciativa de uma perspectiva global e alterações deste repositório. Cada componente (e seus possíveis sub-componentes) terão históricos (Changelogs) específicos e mais detalhados

## Como ajudar o projeto

Com código, redação de textos e ajuda e wiki, etc. Mais informações em breve.
