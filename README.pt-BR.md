[English](README.md) · **Português (Brasil)**

# A Empresa que a IA Recomenda: materiais de apoio do autor

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE) ![Language: pt-BR](https://img.shields.io/badge/materials-pt--BR-green.svg)

Este é o repositório companheiro do livro *A Empresa que a IA Recomenda*,
de Lucas Ferraz. Ele reúne checklists e modelos escritos pelo autor para
apoiar os temas das quatro partes do livro: modelos de `llms.txt`,
`robots.txt` e JSON-LD, checklists para o dono do negócio e um modelo de
plano de 90 dias.

**Este repositório não contém o texto do livro.** Os materiais daqui são
materiais de apoio do autor. Não são trechos do livro e não reproduzem os
capítulos.

Os materiais estão em português do Brasil, porque o livro e os leitores
são brasileiros. Este README existe em inglês e em português.

## Sumário

- [Sobre o livro](#sobre-o-livro)
- [O que o repositório contém](#o-que-o-repositório-contém)
- [Como citar](#como-citar)
- [Onde comprar](#onde-comprar)
- [Métodos](#métodos)
- [Perguntas frequentes](#perguntas-frequentes)
- [Limitações](#limitações)
- [Projetos relacionados do autor](#projetos-relacionados-do-autor)
- [Como contribuir](#como-contribuir)
- [Autor](#autor)
- [Licença](#licença)

## Sobre o livro

| Campo | Valor |
|---|---|
| Título | A Empresa que a IA Recomenda |
| Subtítulo | O guia prático para captar clientes na era da inteligência artificial |
| Autor | Lucas Ferraz |
| Edição | 1ª edição, Belo Horizonte, 2026, edição do autor |
| Formato | E-book, 114 páginas, 14 capítulos em quatro partes, português do Brasil |
| ISBN | 978-65-02-23078-7 |
| Ficha catalográfica (CIP) | 26-377725.0, Câmara Brasileira do Livro, CDD 658.0563 |
| Publicação | julho de 2026 |
| Página-casa do livro | [lucasferraz.com/livros/a-empresa-que-a-ia-recomenda/](https://lucasferraz.com/livros/a-empresa-que-a-ia-recomenda/) |
| Apresentação completa | [lucasferrazseo.com/livro-a-empresa-que-a-ia-recomenda/](https://lucasferrazseo.com/livro-a-empresa-que-a-ia-recomenda/) |

As quatro partes do livro são: **A mudança**, **Os critérios da IA**,
**A IA no atendimento** e **O começo**.

## O que o repositório contém

Uma pasta por parte do livro. Todo arquivo abre com um aviso de que é
material de apoio do autor e não trecho do livro.

```
parte-1-a-mudanca/
  checklist-como-voce-aparece-hoje.md    como o negócio aparece hoje no Google e em quatro assistentes de IA
parte-2-criterios-da-ia/
  README.md                              notas sobre cada modelo
  llms.txt                               modelo de llms.txt para prestador de serviço
  robots.txt                             modelo de robots.txt, robôs de IA de busca liberados, busca e treinamento explicados
  entidade-organization-person.jsonld    modelo de JSON-LD de entidade (Organization + Person)
  checklist-entidade-e-prova-social.md   checklist de coerência da entidade e de prova social
parte-3-ia-no-atendimento/
  checklist-ia-no-atendimento.md         IA no atendimento com uma pessoa no contato
  modelo-politica-de-resposta.md         modelo de política de resposta
parte-4-o-comeco/
  diagnostico-rapido.md                  diagnóstico rápido em checklist
  plano-90-dias.md                       modelo de plano de 90 dias (tabela)
CITATION.cff                             metadados de citação do livro
```

Todos os dados de exemplo são fictícios (`example.com.br`). O modelo de
JSON-LD passa no `python -m json.tool` e no
[jsonld-graph-check](https://github.com/LucasFerrazSEO/jsonld-graph-check)
(do autor) com zero erro e zero aviso.

## Como citar

As referências abaixo vêm da página-casa do livro. O GitHub também lê o
[CITATION.cff](CITATION.cff) e mostra o botão "Cite this repository" com o
livro como citação preferida.

**ABNT**

> FERRAZ, Lucas. A empresa que a IA recomenda, o guia prático para captar clientes na era da inteligência artificial. 1. ed. Belo Horizonte, ed. do autor, 2026. E-book. ISBN 978-65-02-23078-7.

**APA**

> Ferraz, L. (2026). A empresa que a IA recomenda, o guia prático para captar clientes na era da inteligência artificial (1ª ed.) [E-book]. Edição do autor. ISBN 978-65-02-23078-7.

## Onde comprar

O e-book está à venda em:

- [Amazon (Kindle)](https://www.amazon.com.br/dp/B0H9XCZCXX)
- [Google Play Livros](https://play.google.com/store/books/details?id=TKT3EQAAQBAJ)

Confira o preço atual em cada loja.

## Métodos

Dois métodos do autor ligados ao livro têm verbete público no glossário do
site da agência dele:

- [Método das Duas Camadas](https://lucasferrazseo.com/glossario/metodo-das-duas-camadas/):
  separa ser achado na busca de ser recomendado na resposta gerada.
- [Método Rodada de Citação](https://lucasferrazseo.com/glossario/metodo-rodada-de-citacao/):
  mede, em rodadas sucessivas, se sistemas de IA citam uma empresa nas
  respostas.

## Perguntas frequentes

**Este repositório contém o livro?**
Não. Contém só materiais de apoio escritos pelo autor. O livro está à
venda nas lojas listadas acima.

**Posso usar estes materiais com os meus clientes?**
Sim. Estão sob licença CC BY 4.0, então você pode compartilhar e adaptar,
inclusive para uso comercial, desde que dê crédito ao autor.

**Seguir estes checklists faz o meu negócio aparecer no Google ou ser
recomendado por IA?**
Nenhum material garante isso. Os checklists e modelos organizam um
trabalho que torna o negócio mais fácil de entender. O que cada buscador
ou sistema de IA mostra está fora do controle de qualquer pessoa.

## Limitações

Os materiais são modelos genéricos para prestadores de serviço brasileiros
que vendem por orçamento. Não tratam de loja virtual nem de anúncio pago.
Assistentes de IA, robôs e documentação das plataformas mudam com
frequência: os nomes e as descrições dos robôs foram conferidos em
setembro de 2026.

## Projetos relacionados do autor

- [geo-measurement-protocol](https://github.com/LucasFerrazSEO/geo-measurement-protocol):
  protocolo de medição de citação por sistemas de IA.
- [schema-org-templates-br](https://github.com/LucasFerrazSEO/schema-org-templates-br):
  modelos JSON-LD por segmento para negócios brasileiros de serviço.
- [ai-bots-list](https://github.com/LucasFerrazSEO/ai-bots-list):
  lista aberta de robôs de IA, com verificador de `robots.txt`.
- [llms-txt-lint](https://github.com/LucasFerrazSEO/llms-txt-lint):
  confere a estrutura de um arquivo `llms.txt`.
- [citation-round-logger](https://github.com/LucasFerrazSEO/citation-round-logger):
  registra rodadas de citação por IA e calcula a participação de cada
  marca.

## Como contribuir

Correções e sugestões são bem-vindas pelas [Issues do GitHub](https://github.com/LucasFerrazSEO/a-empresa-que-a-ia-recomenda/issues).

## Autor

[Lucas Ferraz](https://lucasferraz.com) é especialista em SEO, criação de sites e Generative Engine Optimization e fundador da [Lucas Ferraz SEO](https://lucasferrazseo.com).

## Licença

CC BY 4.0. Veja o arquivo [LICENSE](LICENSE). A licença cobre os
materiais deste repositório, não o texto do livro.
