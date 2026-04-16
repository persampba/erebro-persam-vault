---
título: "Eu Construí um Micro SaaS com Agentes de IA em 1 Semana"
data: 2026-04-16
projeto: micro-saas-agentes-ia
status: rascunho
tags: [roteiro, micro-saas, agentes, ia, empreendedorismo, build-in-public, brasil]
duracao-estimada: 15-18 minutos
pesquisa: [[Referências/pesquisa-2026-04-16]]
---

# Roteiro — Eu Construí um Micro SaaS com Agentes de IA em 1 Semana

## Foco principal
> O espectador vai entender como agentes de IA mudaram a equação do Micro SaaS, ver o processo real de construção em 1 semana e sair inspirado (e com um plano concreto) para começar o próprio produto.

---

## Gancho (0–30s)

*[Câmera direta, tom de confissão]*

Semana passada eu fiz um experimento. Peguei uma ideia, uma conta na AWS, o Claude como parceiro de desenvolvimento — e tentei construir um produto SaaS funcional em sete dias.

Não um protótipo bonito sem backend. Um produto real: landing page, autenticação, pagamento recorrente, e a funcionalidade principal rodando com agente de IA.

*[Pausa]*

Deu certo. E isso me assustou um pouco.

Hoje eu vou mostrar tudo: o que eu construí, quanto custou, quanto tempo levou de verdade — e por que eu acho que agentes de IA mudaram completamente a matemática do Micro SaaS.

---

## Introdução (30s–2min)

Antes de entrar no projeto, preciso dar contexto sobre o que está acontecendo no mercado.

Micro SaaS não é novidade. A ideia de construir produtos pequenos, focados, com equipe mínima existe há anos. O problema sempre foi a **barreira de execução**: mesmo com uma ideia boa, construir o produto consumia semanas de desenvolvimento, e operar consumia tempo constante.

Em 2026, essa equação mudou por três razões:

**Primeira:** Infraestrutura ficou absurdamente barata. Serverless, bancos gerenciados, autenticação pronta — o custo operacional de um SaaS enxuto é próximo de zero nos primeiros meses.

**Segunda:** IA generativa acelerou desenvolvimento. O que levava 3 semanas de código agora leva 3 dias com um bom prompting.

**Terceira — e essa é a mais importante:** Agentes de IA viraram o produto em si.

Antes, IA era um feature. "Temos IA no nosso produto!" Hoje, o agente *é* o produto. Você não constrói o algoritmo — você configura o comportamento do agente, define as ferramentas que ele usa, e entrega valor que antes exigia uma equipe inteira.

É nessa terceira onda que a minha semana aconteceu.

---

## Desenvolvimento

### Bloco 1 — A ideia: o que eu construí e por quê

*[Tela: landing page do produto]*

O produto que eu construí se chama **BriefBot** — um agente que monitora menções de uma marca ou produto no GitHub, Reddit e Hacker News, e toda manhã manda um resumo estruturado por email com:

- Reclamações recorrentes (prioridade alta)
- Elogios e casos de uso interessantes
- Oportunidades de resposta
- Tendências de percepção ao longo da semana

Público-alvo: fundadores de produtos técnicos e times de produto que precisam de inteligência de mercado sem contratar uma pessoa só pra isso.

**Por que esse produto?**

Três critérios que uso para validar ideia de Micro SaaS:

1. **Dor clara e frequente** — fundadores odeiam não saber o que estão falando sobre eles na internet. Isso é real, eu já senti.
2. **Disposição para pagar** — se resolve problema de negócio, pagam. R$150-300/mês por isso é razoável.
3. **Construível sozinho em menos de 2 semanas** — se não consigo fazer isso, a ideia está grande demais.

BriefBot passou nos três. Fui em frente.

---

### Bloco 2 — Os 7 dias: o processo real

*[Linha do tempo visual — pode ser um card simples na tela]*

**Dia 1 — Validação rápida**
Antes de escrever uma linha de código, passei o dia fazendo pesquisa de demanda. Postei em 3 grupos de founders brasileiros descrevendo o problema sem mencionar o produto. 14 pessoas responderam dizendo que sentiam essa dor. 3 pediram pra ser avisadas quando lançar.

Isso foi suficiente pra continuar.

**Dias 2-3 — Estrutura do agente**
O coração do produto é um agente que:
- Usa ferramentas de busca (GitHub API, Reddit API, Hacker News API)
- Lê e classifica os resultados
- Gera o briefing em formato estruturado
- Dispara por email no horário configurado

Usei Claude API com tool use para construir o agente. O prompt do sistema define o comportamento, as ferramentas são as APIs de busca, e o output é JSON estruturado que vira o email.

Duas horas de trabalho para o agente funcionar no básico. Mais um dia para refinar a qualidade do output e testar com dados reais.

**Dias 4-5 — Produto ao redor do agente**
Landing page (Next.js + Tailwind), autenticação (Clerk), banco de dados (Supabase), pagamento (Stripe). Cada um desses com documentação ótima, templates prontos.

Tempo real: ~12 horas de código. O resto foi configuração e ajustes.

**Dia 6 — Testes com usuários reais**
Convidei 5 das pessoas que demonstraram interesse. Dei acesso grátis por 30 dias. Coletei feedback em chamada de 30 minutos cada.

Feedback principal: "o email tá bom mas quero receber em Slack também." Feature fácil, adicionei no dia 7.

**Dia 7 — Lançamento soft**
Postei no Twitter/X, no grupo de indie hackers brasileiro, e mandei email para quem pediu para ser avisado. 

Resultado do primeiro dia: 47 cadastros, 8 upgrades para plano pago.

---

### Bloco 3 — O que os números dizem (e o que eles não dizem)

*[Volta para câmera, tom mais honesto]*

Antes que você pense "uau, isso é fácil", deixa eu ser direto sobre o que os números escondem.

**O que custou de verdade:**
- Claude API: ~$30/semana para os testes e o agente rodando
- Infraestrutura: ~$20/mês (Vercel + Supabase + Clerk no tier inicial)
- Meu tempo: 7 dias, mas estimando umas 60-70 horas reais de trabalho

Não é passivo. É trabalho concentrado.

**O que ajudou mais do que eu esperava:**
- Agentes com tool use do Claude são surpreendentemente confiáveis para tarefas estruturadas
- A comunidade indie hacker brasileira é ativa e quer dar feedback — aproveite isso
- Stacks modernas (Vercel, Supabase, Clerk, Stripe) têm documentação muito boa em 2026

**O que foi mais difícil do que eu esperava:**
- Qualidade do output do agente varia muito dependendo do prompt — ajustar isso levou mais tempo que o código
- Integração com APIs de terceiros (Reddit especialmente) tem limitações de rate que afetam o produto
- Onboarding de usuários é negligenciado por devs e é onde a maioria abandona

*[Pausa]*

O ponto principal: isso não era possível da mesma forma dois anos atrás. Agentes de IA como produto — não como feature — mudaram o que uma pessoa consegue construir sozinha.

Só 5% das PMEs brasileiras usam SaaS hoje. O mercado é enorme. E a barreira de entrada nunca foi tão baixa.

---

## CTA e encerramento

*[Tom de conversa, não de pitch]*

Se você está pensando em construir um Micro SaaS mas trava na etapa de escolha de ideia ou de tecnologia, me conta nos comentários qual é o maior bloqueio. Vou fazer um vídeo respondendo os mais comuns.

Duas coisas concretas se você quer começar:

**Um:** Antes de escrever código, passe um dia testando se a dor é real. Post em grupos, conversa com pessoas do nicho. Se ninguém se importar com o problema, o produto não vai vender.

**Dois:** Pense em que tarefas repetitivas e chatas do seu nicho um agente de IA poderia fazer bem. Esse é o produto. A tecnologia existe, o mercado existe — falta o problema certo.

Se curtiu esse formato de build in public, me fala nos comentários — pretendo transformar isso em uma série e acompanhar o BriefBot ao vivo ao longo dos próximos meses.

Inscrição, like e compartilha com quem está nessa de empreendedorismo tech. Até a próxima.

---

## Revisão
- [ ] Leu em voz alta
- [ ] Checou duração estimada
- [ ] Revisou CTA
- [ ] Preparou tela do produto para gravação
- [ ] Tem acesso às métricas reais para mostrar
- [ ] Confirmou detalhes técnicos (custos, APIs, stack)
