# Parte 2: os critérios da IA

Materiais de apoio do autor para os temas da Parte 2 do livro. Não são
trechos do livro. Todos os dados de exemplo são fictícios
(`example.com.br`, "Clínica Exemplo Saúde", "Dra. Ana Exemplo").

| Arquivo | O que é |
|---|---|
| [llms.txt](llms.txt) | Modelo de `llms.txt` para prestador de serviço. |
| [robots.txt](robots.txt) | Modelo de `robots.txt` com os robôs de IA de busca liberados e comentários sobre busca e treinamento. |
| [entidade-organization-person.jsonld](entidade-organization-person.jsonld) | Modelo de JSON-LD com o negócio (`Organization`) e o responsável (`Person`) ligados por `@id`. |
| [checklist-entidade-e-prova-social.md](checklist-entidade-e-prova-social.md) | Checklist de coerência da entidade e de prova social. |

## Notas sobre o modelo de llms.txt

O `llms.txt` é uma [proposta aberta](https://llmstxt.org/) de arquivo em
Markdown, publicado na raiz do site, que resume o site para sistemas de
IA. É uma proposta, não um padrão oficial, e o Google informou em junho de
2026, no [registro de mudanças do Google Search Central](https://developers.google.com/search/updates),
que o arquivo não é necessário para a Pesquisa Google e não afeta a
visibilidade nem a posição, embora não haja problema em mantê-lo para
outros sistemas.

Como o modelo está montado, bloco por bloco:

1. **Título (`#`).** O nome do negócio, exatamente como aparece no site e
   no perfil do Google. É o único elemento obrigatório da proposta.
2. **Resumo (`>`).** O que o negócio faz, onde, para quem e em que
   horário, em uma ou duas frases. É o trecho com mais chance de ser
   repetido, então só entra fato conferível.
3. **Parágrafo de contexto.** Endereço, responsável e canal de contato,
   com os mesmos dados do site e do JSON-LD.
4. **Seções (`##`) com listas de links.** Uma seção por grupo de páginas
   (serviços, sobre, perguntas frequentes), cada link com uma descrição
   curta do que a página responde.
5. **Seção `Optional`.** Pela convenção da proposta, reúne o que um
   sistema pode pular quando precisa de um contexto menor.

Depois de adaptar, o [llms-txt-lint](https://github.com/LucasFerrazSEO/llms-txt-lint)
(do autor) confere a estrutura do arquivo, e o
[gerador de llms.txt](https://lucasferrazseo.com/ferramentas/gerador-de-llms-txt/)
do site da agência do autor monta um arquivo pelo navegador.

## Notas sobre o modelo de robots.txt

Os comentários dentro do arquivo explicam cada bloco. A lista de robôs é
uma seleção da [ai-bots-list](https://github.com/LucasFerrazSEO/ai-bots-list)
(do autor), que traz a lista completa com a categoria de cada robô e um
verificador de `robots.txt`. As descrições dos robôs de busca e de
treinamento seguem a documentação de cada empresa:
[OpenAI](https://developers.openai.com/api/docs/bots),
[Anthropic](https://support.claude.com/en/articles/8896518-does-anthropic-crawl-data-from-the-web-and-how-can-site-owners-block-the-crawler),
[Perplexity](https://docs.perplexity.ai/guides/bots),
[Google](https://developers.google.com/crawling/docs/crawlers-fetchers/google-common-crawlers)
e [Apple](https://support.apple.com/en-us/119829) (todas conferidas em
setembro de 2026).

## Notas sobre o modelo de JSON-LD

O modelo usa `Organization` para ficar genérico. Na prática, troque pelo
tipo mais específico do seu segmento. O repositório
[schema-org-templates-br](https://github.com/LucasFerrazSEO/schema-org-templates-br)
(do autor) traz modelos completos por segmento, com a justificativa de
cada tipo.

O `.jsonld` passa no `python -m json.tool` e no
[jsonld-graph-check](https://github.com/LucasFerrazSEO/jsonld-graph-check)
(do autor) com zero erro e zero aviso. Troque todos os marcadores
`SUBSTITUA_...` pelo perfil real, ou apague a linha se o perfil não
existir.
