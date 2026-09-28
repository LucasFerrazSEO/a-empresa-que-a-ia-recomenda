# Checklist de entidade e prova social

Material de apoio do autor para os temas da Parte 2 do livro (Os
critérios da IA). Não é trecho do livro.

"Entidade" é o negócio visto como uma coisa única e reconhecível: o mesmo
nome, o mesmo endereço, o mesmo telefone e a mesma descrição em todo lugar
onde ele aparece. "Prova social" é o que terceiros dizem sobre o negócio.
Quanto mais coerentes forem as duas, menos espaço sobra para uma máquina
confundir a sua empresa com outra.

## Parte A: a entidade é a mesma em todo lugar?

- [ ] O nome do negócio é escrito do mesmo jeito no site, no perfil da
      empresa no Google, nas redes sociais e nos diretórios.
- [ ] Endereço, CEP e telefone são idênticos em todos esses lugares,
      inclusive na formatação.
- [ ] O horário de funcionamento do site bate com o do perfil do Google.
- [ ] A categoria principal do perfil do Google descreve o serviço que
      mais traz clientes.
- [ ] O site tem uma página "Sobre" que diz quem é o responsável, desde
      quando o negócio existe e onde atende.
- [ ] O site descreve cada serviço em uma página própria, com o que é,
      para quem é e em que região é oferecido.
- [ ] O site tem dados estruturados (JSON-LD) com o negócio e o
      responsável ligados entre si. Modelo neste diretório:
      [entidade-organization-person.jsonld](entidade-organization-person.jsonld).
- [ ] O `sameAs` do JSON-LD lista só perfis que existem e pertencem ao
      negócio.
- [ ] O site tem um `llms.txt` com o resumo do negócio e as páginas mais
      importantes. Modelo neste diretório: [llms.txt](llms.txt).
- [ ] O `robots.txt` não bloqueia, por engano, os robôs de busca com IA.
      Modelo neste diretório: [robots.txt](robots.txt).

## Parte B: o que terceiros dizem sobre o negócio

- [ ] O perfil do Google tem avaliações recentes, e as avaliações são
      respondidas.
- [ ] As respostas às avaliações mencionam o serviço prestado de forma
      natural, sem repetir palavra-chave.
- [ ] O negócio aparece em diretórios e associações do próprio setor
      (conselho profissional, associação comercial, entidade de classe),
      com os mesmos dados da Parte A.
- [ ] Existe alguma menção em veículo local, parceiro ou evento, com link
      ou com o nome completo do negócio.
- [ ] Depoimentos no site têm nome (ou iniciais autorizadas), serviço e
      data, e foram publicados com autorização do cliente.
- [ ] Nenhum depoimento, avaliação ou número de cliente foi inventado.

## Como usar o resultado

Marque o que já está feito e liste o que falta em ordem de esforço: o que
se resolve em uma tarde (corrigir telefone, completar horário) vem antes
do que leva semanas (conseguir menção de terceiros). Este checklist
organiza o trabalho. Ele não garante posição no Google nem citação por
nenhuma IA.
