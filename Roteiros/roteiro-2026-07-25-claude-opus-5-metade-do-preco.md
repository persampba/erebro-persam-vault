---
título: Claude Opus 5 — Fable 5 pela metade do preço
data: 2026-07-25
status: roteiro
tags: [roteiro, claude, anthropic, opus-5, preco, agentes, ia]
tema: Claude Opus 5 lançamento com preço 50% menor que Fable 5
gancho: Você finalmente pode pagar pelo modelo mais inteligente da Anthropic
---

# Claude Opus 5: você finalmente pode pagar pelo modelo mais inteligente da Anthropic

---

## Gancho (0–30s)

A Anthropic acabou de lançar um modelo com a inteligência do Fable 5 — o modelo mais poderoso do mundo — por **metade do preço**.

Não é um modelo menor. Não é um modelo intermediário. É o Opus 5, e ele chega com 1 milhão de tokens de contexto, pensamento ativado por padrão, e uma novidade técnica que vai mudar como empresas usam IA.

Mas tem um detalhe que a maioria vai ignorar — e esse detalhe pode custar caro. Fica até o final.

---

## Introdução (30s–2min)

Antes de falar dos números, deixa eu contextualizar o que aconteceu ontem, 24 de julho de 2026.

A Anthropic lançou silenciosamente o `claude-opus-5`. Sem keynote. Sem evento. Uma postagem no blog e o modelo disponível na API.

O anúncio foi simples: **US$ 5 por milhão de tokens de entrada. US$ 25 por milhão de saída.** Isso é 50% mais barato do que o Fable 5 — que até ontem era o único modelo com essa capacidade de raciocínio.

Para quem não acompanha: o Fable 5 custa US$ 10/M entrada e US$ 50/M saída. É o modelo que a Anthropic usa em tarefas que exigem raciocínio profundo, múltiplos passos, e muito contexto.

Agora o Opus 5 chega na mesma categoria de inteligência por metade do preço.

O mercado reagiu. Vamos entender por quê isso importa.

---

## Bloco 1 — O que é o Claude Opus 5 e o que ele entrega

**Contexto de 1 milhão de tokens.** Por padrão. Isso significa que você pode jogar dentro do modelo um projeto inteiro, um repositório de código, centenas de páginas de documentos legais, e pedir para ele trabalhar em cima de tudo isso ao mesmo tempo.

**Pensamento ativado por padrão.** O modelo não só responde — ele raciocina antes de responder. Você vê o processo. Para agentes autônomos, isso é crítico.

**Cache mais eficiente.** O Opus 5 permite armazenar em cache prompts a partir de 512 tokens — antes eram 1.024 tokens no Opus 4.8. Isso parece detalhe técnico, mas na prática significa que prompts mais curtos agora ficam em cache, reduzindo o custo em chamadas repetidas.

**Modificação de ferramentas sem invalidar cache.** Em agentes com múltiplas ferramentas, você agora pode alterar as ferramentas disponíveis sem recomeçar o cache do zero. Isso reduz custo e latência em sistemas complexos.

**Sistema de fallback melhorado.** Menos interrupções causadas por filtros de segurança. Para quem opera agentes em produção, isso é redução direta de erro e retrabalho.

---

## Bloco 2 — Quem se beneficia e como usar

**Caso de uso 1: Agentes de longa duração**
Se você roda agentes que precisam manter contexto por horas — análise de contratos, pesquisa de mercado, automação de processos — o Opus 5 é o modelo certo. O contexto de 1M tokens e o preço 50% menor tornam isso viável em escala.

**Caso de uso 2: Processamento de documentos longos**
Escritórios de advocacia, consultorias, auditores — qualquer profissional que trabalha com documentos extensos pode agora alimentar o modelo com o material completo sem o custo proibitivo do Fable 5.

**Caso de uso 3: Projetos de código complexos**
Repositórios completos dentro do contexto do modelo. O Opus 5 analisa dependências, entende arquitetura, propõe refatorações com visão do todo — não só do trecho colado.

**Comparação rápida:**
| Modelo | Entrada | Saída | Contexto |
|--------|---------|-------|----------|
| Fable 5 | US$ 10/M | US$ 50/M | 1M tokens |
| **Opus 5** | **US$ 5/M** | **US$ 25/M** | **1M tokens** |
| Sonnet 5 | US$ 3/M | US$ 15/M | 200k tokens |

---

## Bloco 3 — O detalhe que ninguém está falando

Nos primeiros benchmarks externos, o Opus 5 **tende a respostas muito longas** — mesmo quando a resposta poderia ser curta.

Isso importa porque no modelo de cobrança por token, **respostas longas = conta mais alta**. Se você está rodando o modelo em produção sem controlar o comprimento da saída, pode pagar mais do que esperava mesmo com o preço mais baixo.

A solução é simples: adicione instruções explícitas de tamanho de resposta nos seus prompts de sistema. "Seja conciso. Máximo X parágrafos." Isso corta o custo real de forma significativa.

O outro ponto: revisão de código. Nos testes iniciais, o Opus 5 deixou passar alguns erros ao revisar código — especialmente em linguagens menos comuns. Para uso crítico em produção, valide os outputs com testes automatizados antes de aceitar as sugestões.

Isso não tira o valor do modelo. Mas é o tipo de informação que a maioria vai descobrir depois de uma fatura inesperada.

---

## CTA e Encerramento (final)

Se você ainda estava esperando o preço certo para usar o modelo mais poderoso da Anthropic — esse pode ser o momento.

O Claude Opus 5 está disponível agora na API e no Claude.ai. Se você tem plano Pro, Max ou Team, já tem acesso.

Minha recomendação: comece com os seus projetos mais longos e mais complexos. Aqueles que o Sonnet 5 trata bem mas perde o fio. Teste. Meça o custo real com a instrução de tamanho de resposta que mencionei.

E se você quiser saber como estou usando o Opus 5 no meu workflow de criação de conteúdo, eu faço um vídeo sobre isso — manda nos comentários.

Se esse vídeo foi útil, inscreve no canal. Eu cubro Anthropic, Claude e IA prática para quem cria e constrói — sem hype, com dados.

Até o próximo.

---

## Notas de produção

- Mostrar na tela a tabela de preços comparando Fable 5 e Opus 5
- Exibir a interface do Claude com o modelo selecionado
- Capturar exemplo real de contexto longo sendo processado
- Destacar visualmente o alerta sobre respostas longas (B-roll de fatura)
- Fontes: [[Referências/pesquisa-2026-07-25]]
