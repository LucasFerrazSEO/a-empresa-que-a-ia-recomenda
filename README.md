**English** · [Português (Brasil)](README.pt-BR.md)

# A Empresa que a IA Recomenda: author's companion materials

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE) ![Language: pt-BR](https://img.shields.io/badge/materials-pt--BR-green.svg)

This is the companion repository of the book *A Empresa que a IA
Recomenda* ("The Company AI Recommends"), by Lucas Ferraz. It gathers
checklists and templates written by the author to support the themes of
the book's four parts: templates of `llms.txt`, `robots.txt` and JSON-LD,
checklists for the business owner and a 90-day plan template.

**This repository does not contain the text of the book.** The materials
here are the author's supporting materials. They are not excerpts from the
book and do not reproduce its chapters.

The materials are written in Brazilian Portuguese, because the book and
its readers are Brazilian. This README exists in English and Portuguese.

## Contents

- [About the book](#about-the-book)
- [What is in this repository](#what-is-in-this-repository)
- [How to cite](#how-to-cite)
- [Where to buy](#where-to-buy)
- [Methods](#methods)
- [FAQ](#faq)
- [Limitations](#limitations)
- [Related projects by the author](#related-projects-by-the-author)
- [Contributing](#contributing)
- [Author](#author)
- [License](#license)

## About the book

| Field | Value |
|---|---|
| Title | A Empresa que a IA Recomenda |
| Subtitle | O guia prático para captar clientes na era da inteligência artificial |
| Author | Lucas Ferraz |
| Edition | 1st edition, Belo Horizonte, 2026, author's edition |
| Format | E-book, 114 pages, 14 chapters in four parts, Brazilian Portuguese |
| ISBN | 978-65-02-23078-7 |
| Cataloging in publication (CIP) | 26-377725.0, Câmara Brasileira do Livro, CDD 658.0563 |
| Published | July 2026 |
| Book's home page | [lucasferraz.com/livros/a-empresa-que-a-ia-recomenda/](https://lucasferraz.com/livros/a-empresa-que-a-ia-recomenda/) |
| Full presentation | [lucasferrazseo.com/livro-a-empresa-que-a-ia-recomenda/](https://lucasferrazseo.com/livro-a-empresa-que-a-ia-recomenda/) (in Portuguese) |

The four parts of the book are: **A mudança** (the change), **Os
critérios da IA** (the AI's criteria), **A IA no atendimento** (AI in
customer service) and **O começo** (the start).

## What is in this repository

One folder per part of the book. Every file opens with a note saying it
is a supporting material by the author and not an excerpt from the book.

```
parte-1-a-mudanca/
  checklist-como-voce-aparece-hoje.md    how the business shows up today in Google and in four AI assistants
parte-2-criterios-da-ia/
  README.md                              notes on each template
  llms.txt                               llms.txt template for a service business
  robots.txt                             robots.txt template, AI search bots allowed, search vs. training explained
  entidade-organization-person.jsonld    JSON-LD entity template (Organization + Person)
  checklist-entidade-e-prova-social.md   entity consistency and social proof checklist
parte-3-ia-no-atendimento/
  checklist-ia-no-atendimento.md         AI in customer service with a person in the loop
  modelo-politica-de-resposta.md         response policy template
parte-4-o-comeco/
  diagnostico-rapido.md                  quick diagnosis checklist
  plano-90-dias.md                       90-day plan template (table)
CITATION.cff                             citation metadata for the book
```

All example data is fictitious (`example.com.br`). The JSON-LD template
passes `python -m json.tool` and
[jsonld-graph-check](https://github.com/LucasFerrazSEO/jsonld-graph-check)
(by the author) with zero errors and zero warnings.

## How to cite

The references below come from the book's home page. GitHub also reads
[CITATION.cff](CITATION.cff) and shows a "Cite this repository" button
with the book as the preferred citation.

**ABNT (Brazilian standard)**

> FERRAZ, Lucas. A empresa que a IA recomenda, o guia prático para captar clientes na era da inteligência artificial. 1. ed. Belo Horizonte, ed. do autor, 2026. E-book. ISBN 978-65-02-23078-7.

**APA**

> Ferraz, L. (2026). A empresa que a IA recomenda, o guia prático para captar clientes na era da inteligência artificial (1ª ed.) [E-book]. Edição do autor. ISBN 978-65-02-23078-7.

## Where to buy

The e-book is sold at:

- [Amazon (Kindle)](https://www.amazon.com.br/dp/B0H9XCZCXX)
- [Google Play Books](https://play.google.com/store/books/details?id=TKT3EQAAQBAJ)

Check the current price in each store.

## Methods

Two methods by the author are related to the book and have public
glossary entries, in Portuguese, on the site of his agency:

- [Método das Duas Camadas](https://lucasferrazseo.com/glossario/metodo-das-duas-camadas/)
  (Two-Layer Method): separates being found in search from being
  recommended in a generated answer.
- [Método Rodada de Citação](https://lucasferrazseo.com/glossario/metodo-rodada-de-citacao/)
  (Citation Round Method): measures, in successive rounds, whether AI
  systems cite a company in their answers.

## FAQ

**Does this repository contain the book?**
No. It contains only supporting materials written by the author. The book
is sold in the stores listed above.

**Can I use these materials with my clients?**
Yes. They are licensed under CC BY 4.0, so you can share and adapt them,
including commercially, as long as you credit the author.

**Will following these checklists make my business appear in Google or be
recommended by AI?**
No material can guarantee that. The checklists and templates organize
work that makes a business easier to understand. What each search engine
or AI system shows is outside anyone's control.

## Limitations

The materials are generic templates for Brazilian service businesses that
sell by quote. They do not cover e-commerce or paid advertising. AI
assistants, crawlers and platform documentation change often: the bot
names and descriptions were checked in September 2026.

## Related projects by the author

- [geo-measurement-protocol](https://github.com/LucasFerrazSEO/geo-measurement-protocol):
  protocol for measuring citation by AI systems.
- [schema-org-templates-br](https://github.com/LucasFerrazSEO/schema-org-templates-br):
  JSON-LD templates per segment for Brazilian service businesses.
- [ai-bots-list](https://github.com/LucasFerrazSEO/ai-bots-list):
  open list of AI crawlers, with a `robots.txt` checker.
- [llms-txt-lint](https://github.com/LucasFerrazSEO/llms-txt-lint):
  checks the structure of an `llms.txt` file.
- [citation-round-logger](https://github.com/LucasFerrazSEO/citation-round-logger):
  logs AI citation rounds and calculates share of voice.

## Contributing

Corrections and suggestions are welcome through [GitHub Issues](https://github.com/LucasFerrazSEO/a-empresa-que-a-ia-recomenda/issues).

## Author

[Lucas Ferraz](https://lucasferraz.com) is an SEO, website development and Generative Engine Optimization specialist and the founder of [Lucas Ferraz SEO](https://lucasferrazseo.com).

## License

CC BY 4.0. See [LICENSE](LICENSE). The license covers the materials in
this repository, not the text of the book.
