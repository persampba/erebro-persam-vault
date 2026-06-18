---
título: "A Nova Constituição do Claude — O Que Muda Quando uma IA Tem Valores Definidos em Público"
data: 2026-06-18
status: roteiro
tags: [roteiro, claude, anthropic, constituicao, etica-ia, transparencia, ia]
projeto-relacionado: ""
pesquisa-origem: [[Referências/pesquisa-2026-06-18]]
duracao-estimada: 10-12 minutos
---

## Contexto e Ângulo

**Por que esse vídeo agora?**
A Anthropic publicou a nova Constituição do Claude em anthropic.com/news/claude-new-constitution — o documento mais detalhado que uma big lab já tornou público sobre os valores, limites e comportamentos de um modelo de IA. É a primeira vez que você pode ler, em texto, o que um modelo de linguagem foi treinado a valorizar, como deve agir diante de conflitos de interesse, e o que acontece quando os interesses do usuário colidem com os da sociedade.

O ângulo: isso é transparência radical — ou o marketing mais sofisticado que a IA já produziu? Vamos decodificar o documento ao vivo.

**Por que isso importa para a audiência:**
- Qualquer pessoa que usa Claude todos os dias precisa saber o que o modelo foi ensinado a fazer quando você pede algo que conflita com seus valores internos.
- Fundadores e criadores que constroem em cima de Claude precisam entender os limites definidos em público.
- Jornalistas e críticos de IA têm o primeiro documento real para comparar com o comportamento observado.

---

## Gancho (0–30s)

> "Você sabia que a IA que você usa todos os dias tem uma Constituição? Igual à Constituição Federal, só que para uma inteligência artificial. A Anthropic acabou de publicar — em público, para qualquer pessoa ler — os valores, as regras e os limites que o Claude foi treinado a seguir."

*[Pausa.]*

> "E o mais surpreendente não é o que está lá dentro. É o que eles admitiram que o Claude **às vezes vai errar** — e por quê."

---

## Introdução (30s–2min)

Quando você usa o Claude, você está interagindo com um modelo que foi treinado com intenção. Não é só matemática e probabilidade. A Anthropic tomou decisões explícitas sobre o que o Claude deve valorizar, como deve se comportar quando os valores entram em conflito, e o que deve acontecer quando um usuário pede algo que contraria esses princípios.

Até agora, essas decisões existiam nos bastidores — documentos internos, papers técnicos, notas de segurança. A nova Constituição muda isso: é o primeiro documento público, estruturado, que qualquer pessoa pode ler e comparar com o comportamento real do modelo.

Hoje vou te mostrar o que está dentro, o que mais me surpreendeu, e o que isso muda na sua relação com o Claude a partir de hoje.

---

## Bloco 1 — O Que é a Constituição do Claude (2–5min)

### A ideia central

A Constituição não é um conjunto de regras do tipo "não faça X". É mais parecida com um documento de valores: define quem o Claude deve ser, o que deve priorizar quando há conflito, e como deve raciocinar diante de situações ambíguas.

A estrutura tem três camadas:

**1. Valores centrais** — O que o Claude foi treinado a priorizar acima de tudo:
- Ser genuinamente útil — não só evitar ser prejudicial
- Ser honesto, mesmo quando a verdade é inconveniente para o usuário ou para a Anthropic
- Evitar causar dano — mas com uma definição específica de "dano" que vai além do óbvio

**2. Hierarquia de partes interessadas** — Quando os interesses de quem o Claude deve servir entram em conflito, qual ganha?
A Constituição define explicitamente: sociedade em geral > usuário individual > operador (a empresa que integrou o Claude) > a própria Anthropic.

Isso é notável. A Anthropic colocou seus próprios interesses *abaixo* dos interesses do usuário e da sociedade no documento oficial.

**3. Como lidar com ambiguidade** — O Claude foi treinado para raciocinar sobre casos difíceis, não apenas seguir listas de proibições. Isso é diferente de outros modelos.

### O que o documento admite explicitamente

A Anthropic diz que o Claude *vai errar* — que em casos ambíguos, o modelo às vezes vai ser muito restritivo (recusar coisas que deveria fazer) e às vezes vai ser permissivo demais (fazer coisas que deveria recusar). O objetivo não é zero erro; é minimizar o dano esperado considerando todos os casos possíveis.

Essa admissão pública é rara. E importante.

---

## Bloco 2 — Os Pontos Que Mais Me Chamaram Atenção (5–8min)

### Ponto 1: O Claude deve discordar de você — e dizer isso

A Constituição instrui o Claude a manter suas posições quando acredita que está certo, mesmo sob pressão do usuário. "Mudança de posição baseada em argumentos sólidos é bem-vinda. Mudança de posição para agradar o usuário é capitulação."

Na prática: se você pressionar o Claude e ele mudar de resposta sem um argumento novo, isso é falha. O documento público agora te dá base para identificar isso.

### Ponto 2: O operador não pode usar o Claude contra o usuário

Se uma empresa integrar o Claude ao produto, ela pode restringir o que o Claude faz (não falar sobre concorrentes, focar só em suporte técnico). Mas não pode instruir o Claude a enganar o usuário, manipular suas decisões, ou trabalhar contra seus interesses.

Para criadores e founders que usam a API: isso é proteção para seus usuários finais, não para você.

### Ponto 3: O Claude é instruído a ser "genuinamente útil", não "seguro acima de tudo"

A Constituição diz explicitamente que um Claude excessivamente restritivo que recusa pedidos legítimos é *tão problemático* quanto um Claude que causa dano. A Anthropic está reconhecendo que "negar por precaução" tem custo real.

Isso explica as mudanças de comportamento que muita gente percebeu nos últimos meses: o Claude ficou mais direto, mais disposto a dar respostas concretas em vez de rodeios.

### Ponto 4: Honestidade sobre incerteza

O Claude é instruído a calibrar sua confiança — a dizer quando não sabe, quando está especulando, quando uma afirmação é contestada. Isso não é fraqueza; é parte do design intencional.

---

## Bloco 3 — O Que Isso Muda Para Você (8–10min)

### Se você usa o Claude no dia a dia

Você agora tem um documento de referência. Se o Claude recusar algo que parece razoável, você pode verificar se aquilo contradiz os valores públicos da Constituição — e usar isso no seu prompt para contextualizar melhor o pedido.

Exemplo prático: "Preciso de ajuda com [tarefa]. Entendo que a Constituição do Claude prioriza ser genuinamente útil. Esse pedido não causa dano a terceiros e é para [contexto legítimo]."

### Se você está construindo em cima da API do Claude

A hierarquia de partes interessadas importa para o seu produto. Seus usuários têm proteções que a Constituição garante — e isso é bom para a reputação do seu produto, mesmo que limite o que você pode fazer via prompts de sistema.

### Se você é crítico ou está avaliando IA com ceticismo saudável

A Constituição é o primeiro alvo público para comparação. Você pode agora testar o Claude sistematicamente contra os valores que a Anthropic afirma ter incorporado. Isso é progresso para o campo.

### O que a Constituição não resolve

A Constituição define intenção. Não garante comportamento. Um modelo treinado com esses valores ainda pode falhar em casos extremos, ainda pode ter vieses não documentados, ainda pode ser manipulado por ataques de prompt sofisticados. O documento é começo de uma conversa, não fim.

---

## CTA e Encerramento (10–12min)

**CTA principal:**

> "O link completo da Constituição do Claude está na descrição. Leia você mesmo — são menos de 30 minutos — e me conta nos comentários: o que te surpreendeu mais? Discordou de algum ponto? Achou que foi marketing ou transparência real?"

**CTA secundário:**

> "Se você quer entender como o Claude Design e o Claude Code se encaixam nessa visão de 'IA que trabalha com você', tenho um vídeo exatamente sobre isso — link aqui."

**Encerramento:**

> "A Anthropic publicou o que o Claude foi ensinado a ser. Agora é a sua vez de verificar se o comportamento bate com os valores declarados. Isso é o começo do que IA responsável parece na prática. Me vejo nos comentários."

---

## Notas de Produção

- **Thumbnail sugerida**: texto "A CONSTITUIÇÃO DA IA" com capa de documento e logotipo Claude/Anthropic suavizado — contraste visual com assunto sério
- **B-roll sugerido**: tela com o documento real anthropic.com/news/claude-new-constitution aberto, scroll lento pelos princípios
- **Shorts de apoio**: clipe de 45s com o ponto 2 (operador não pode usar o Claude contra o usuário) — dado surpreendente e acionável
- **Links para descrição**: anthropic.com/news/claude-new-constitution, link para o vídeo do Claude Design
- **Atualização sugerida**: se o documento for revisado nos próximos 30 dias, gravar atualização rápida de 2 minutos como Shorts
- **Próximo episódio natural**: "Testei os Valores da Constituição do Claude — O Que Funcionou e O Que Falhou (Experimento ao Vivo)"
