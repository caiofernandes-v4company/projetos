# DESTRAVA: newsletter da V4 Ferraz & Piai

Newsletter quinzenal assinada por **Caio Fernandes** (marketing estratégico, comercial e receita) e **Edson Piai** (gestão, finanças, tributos e caixa).
Objetivo: ser vista pela base e pelo pipeline como **parceira de negócio** que entende de receita *e* de caixa, e que destrava crescimento.

## Arquivos

| Arquivo | O que é |
|---|---|
| `edicoes/edicao-01.html` | Edição 01 pronta para colar no editor HTML do ActiveCampaign (ou RD, Mailchimp etc.) |
| `pauta-editorial.md` | 12 edições planejadas, assuntos, temas por autor e regras das seções |

Para criar a próxima edição, duplique `edicao-01.html` como `edicao-02.html` e troque apenas os textos. A estrutura e os estilos ficam iguais.

## Antes de enviar a edição 01

Procure por `[` no arquivo e preencha:

- `[dia] de [mês] de [ano]`
- `[Cargo]` do Caio e do Edson
- `[link-agenda-check-in]` (clientes) e `[link-agenda-diagnostico]` (pipeline)
- `[link-nota-1]` a `[link-nota-5]` (avaliação da edição; no ActiveCampaign, cada link pode aplicar uma tag)
- `[link-instagram]`, `[link-linkedin]`, `[link-site]`, `[Endereço da unidade]`, `[Cidade/UF]`
- Opcional: trocar os círculos "CF" e "EP" por fotos (instrução em comentário no HTML)
- Ajuste a cor `#E30613` se o vermelho oficial do brand book da V4 for outro

## Segmentação: base × pipeline

O bloco de CTA usa **conteúdo condicional** do ActiveCampaign:

- Contatos com a tag **`cliente-base`** veem: *"Leve este tema para o próximo check-in"*, que reforça relacionamento e abre espaço para expansão e upsell.
- Todos os outros (pipeline) veem: *"Agende um Diagnóstico de Receita de 45 min"*, para gerar reunião comercial.

Crie as duas tags e uma lista "DESTRAVA" com os dois públicos. Se a sua ferramenta não suportar a sintaxe `%IF ... %ELSE% ... %/IF%`, faça dois envios e apague o bloco que não se aplica em cada um. Confira as merge tags (`%FIRSTNAME%`, `%WEBCOPY%`, `%UNSUBSCRIBELINK%`) e use **pré-visualização + envio de teste** antes de disparar.

## Tom de voz

- **Empresário falando com empresário.** Primeira pessoa, direto, sem jargão de agência. Quando o jargão for inevitável (bowtie, CAC, NRR), explique na mesma frase.
- **Sempre uma conta.** Cada coluna tem pelo menos um número ou cálculo simples. É isso que transmite visão de negócio.
- **Sempre uma ação.** O box "Faça na segunda-feira" fecha cada coluna com algo executável em menos de uma hora.
- **As colunas se respondem.** O Edson comenta o efeito financeiro do tema do Caio, e vice-versa.
- **Sem dado inventado.** Exemplo hipotético se apresenta como "um exemplo". Estudo, com a fonte. Caso de cliente, só real e autorizado.

## Rotina sugerida (quinzenal)

| Dia | Tarefa |
|---|---|
| D-7 | Definir tema na pauta; Caio e Edson enviam rascunhos (~400 palavras cada) |
| D-3 | Revisão cruzada (um revisa o texto do outro) e montagem no HTML |
| D-1 | Envio de teste para a equipe; checar no celular e no Outlook |
| D   | Disparo terça ou quarta, entre 7h e 9h |
| D+2 | Responder pessoalmente cada resposta recebida; leads do pipeline que clicaram no CTA → follow-up do comercial em até 1h |

**Métricas para acompanhar:** taxa de cliques (mais confiável que abertura), respostas, reuniões agendadas pelo CTA e, para a base, expansão e renovação dos clientes engajados.
