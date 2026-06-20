---
título: "Fable 5: Quando Volta e o Que Você Precisa Fazer Antes de 8 de Julho"
data: 2026-06-20
status: roteiro
tags: [roteiro, claude, fable5, mythos5, anthropic, kyc, exportacao, governo-eua, segurança]
pesquisa: [[Referências/pesquisa-2026-06-20]]
tema-kebab: fable5-quando-volta-kye-julho
duração-estimada: 10–13 minutos
formato: análise + guia prático
---

## Gancho (0–30s)

Em 9 de junho a Anthropic lançou o Fable 5 — o modelo mais poderoso que eles já tornaram público. Três dias depois o governo americano mandou tirar do ar. Para todo mundo fora dos EUA.

Hoje é 20 de junho. Fable 5 continua fora. E em **8 de julho** — ou seja, em 18 dias — a Anthropic vai exigir que TODOS os usuários verifiquem identidade para continuar usando qualquer modelo avançado.

A cobertura brasileira explicou o que aconteceu. Hoje eu vou te contar **por que aconteceu** e o que você precisa fazer nos próximos 18 dias para não perder acesso ao Claude.

---

## Introdução (30s–2min)

### Contexto: o que é Fable 5

O Claude Fable 5 é a primeira versão pública do projeto Mythos — o modelo que a Anthropic vinha desenvolvendo em segredo. Lançado em 9 de junho, superava o Opus 4.8 em codificação autônoma (80,3% no SWE-Bench Pro vs. 69,2% do Opus 4.8). Preço dobrado: US$ 10/M tokens de entrada, US$ 50/M de saída.

Mas o Fable 5 tinha uma característica inédita: **ele se autocensurava automaticamente** em cibersegurança ofensiva, biologia e química — retornando para o Opus 4.8 quando detectava essas solicitações.

Esse detalhe técnico é o centro do que aconteceu depois.

---

## Bloco 1 — O que realmente aconteceu em 12 de junho (2min–5min)

### A sequência de eventos

**9 de junho:** Fable 5 e Mythos 5 lançados publicamente.

**10–11 de junho:** Repercussão. Dario Amodei, CEO da Anthropic, em entrevistas e declarações públicas, detalhou as capacidades do Fable 5 — especificamente na área de cibersegurança. Disse que o modelo era capaz de encontrar vulnerabilidades em sistemas de forma autônoma com precisão sem precedentes.

**12 de junho:** O governo americano (administração Trump) emitiu uma diretiva de controle de exportação classificando o Fable 5 e o Mythos 5 como tecnologia estratégica — não podem ser acessados por estrangeiros.

**O problema:** A Anthropic não tem como verificar a nacionalidade de cada usuário em tempo real. Sem esse mecanismo, eles desligaram os dois modelos globalmente.

### O paradoxo de Dario Amodei

Aqui está o ângulo que ninguém está explicando em português:

As **declarações públicas do próprio CEO sobre as capacidades do Fable 5** foram usadas pelo governo americano como justificativa para a diretiva.

Em outras palavras: a transparência da Anthropic sobre o que o modelo podia fazer foi o gatilho da restrição.

Isso cria um dilema existencial para qualquer empresa de IA de fronteira:
- Se você é transparente sobre riscos → o governo usa isso para restringir
- Se você não é transparente → você esconde riscos do público

Não existe resposta certa. E esse debate vai definir o futuro da IA aberta.

### O contexto do DoD

Em março de 2026, o Departamento de Defesa americano havia classificado a Anthropic como "risco de cadeia de suprimentos" — depois que a empresa recusou desenvolver armamentos autônomos letais.

Ou seja: a Anthropic foi punida duas vezes pelo mesmo governo — uma por dizer não ao uso militar, outra por ser transparente demais sobre o que o modelo podia fazer.

---

## Bloco 2 — O que é o KYC e o que acontece em 8 de julho (5min–8min)

### KYC: Know Your Customer

KYC é verificação de identidade — o mesmo processo que bancos fazem quando você abre uma conta. A Anthropic vai implementar isso como requisito obrigatório a partir de **8 de julho de 2026**.

### O que muda na prática

| Situação | Antes de 8/07 | Depois de 8/07 |
|---|---|---|
| Você usa Claude.ai com e-mail | Acesso normal | Precisa verificar identidade |
| Você usa API com chave | Acesso normal | Empresa precisa verificar CNPJ/RG |
| Você está no Brasil | Acesso normal (modelos disponíveis) | Acesso condicionado à verificação |

### O que vai ser pedido (estimativa baseada em práticas de KYC)

Para pessoas físicas:
- Documento de identidade (RG, CPF ou passaporte)
- Foto com o documento (selfie)
- País de residência

Para empresas (uso via API):
- CNPJ ou equivalente local
- Nome do representante legal
- Documento do responsável

**Atenção:** A Anthropic ainda não publicou o fluxo exato de KYC para usuários internacionais. O prazo e o processo foram confirmados, mas os documentos aceitos para brasileiros não estão detalhados no FAQ público até hoje (20/06).

### O que fazer agora

**Nos próximos 18 dias:**

1. **Acesse sua conta na Anthropic** (claude.ai ou console.anthropic.com)
2. Verifique se já aparece algum aviso de verificação pendente no painel
3. Se você usa API, acesse o Console e veja se há seção de verificação de identidade da organização
4. **Prepare seus documentos:** RG ou passaporte, CPF, comprovante de residência
5. **Documente seu fluxo atual:** se você tem um micro SaaS ou automação que depende do Claude, saiba exatamente quais modelos usa — para o caso de algum ser restrito pós-verificação

### O cenário mais provável

A verificação deve liberar acesso a modelos como Opus 4.8 e Claude Sonnet sem restrição para usuários verificados no Brasil. O Fable 5 e Mythos 5 — com a diretiva de exportação ainda em disputa judicial — podem continuar indisponíveis para estrangeiros mesmo após o KYC.

---

## Bloco 3 — Quando o Fable 5 volta? (8min–11min)

### O que a Anthropic disse

A Anthropic descreveu a diretiva como um "mal-entendido" e anunciou que está contestando judicialmente. Não deu prazo.

### O que a disputa judicial pode resultar

Há três cenários possíveis:

**Cenário A — Anthropic ganha rapidamente (improvável em < 30 dias):** Fable 5 volta para todos. Prazo: difícil estimar, disputas regulatórias federais raramente resolvem em semanas.

**Cenário B — Acordo com verificação de identidade:** O governo aceita que usuários verificados (KYC completo, com país confirmado) acessem o Fable 5. Nesse caso, o KYC de 8/07 se torna o caminho para o Fable 5 — depois da verificação, usuários em países "seguros" (lista a ser definida) teriam acesso.

**Cenário C — Restrição permanente para estrangeiros:** O governo não cede e o Fable 5 fica disponível apenas para cidadãos e empresas americanas. O Opus 4.8 continua sendo o teto para usuários internacionais.

### Qual o cenário mais provável?

O Cenário B é o mais plausível politicamente. O governo tem interesse em controle de acesso, não em eliminar um produto americano do mercado global. KYC resolve o controle de acesso sem destruir a receita da Anthropic.

Se isso se confirmar, fazer o KYC antes de 8/07 pode ser exatamente a porta de entrada para o Fable 5.

---

## CTA e Encerramento (11min–13min)

### Resumo

- **12/06:** Fable 5 e Mythos 5 tirados do ar por diretiva do governo americano
- **Por quê:** Declarações públicas de Dario Amodei sobre capacidades do modelo foram usadas como justificativa
- **8/07 — em 18 dias:** KYC obrigatório para todos os usuários
- **Fable 5:** Pode retornar via KYC no Cenário B, mas sem prazo confirmado

### Sua ação hoje

1. Acesse **claude.ai** agora e verifique se há seção de verificação de identidade
2. Prepare seus documentos (RG + CPF + comprovante)
3. Se você usa API, acesse o Console e verifique o status da sua organização
4. **Cadastre seu e-mail** no Anthropic para receber o aviso quando o fluxo KYC estiver disponível para brasileiros

### Pergunta para os comentários

O Dario deveria ter ficado quieto? Se ele não tivesse declarado publicamente as capacidades do Fable 5, o governo provavelmente não teria reagido tão rápido. Mas se ele não declarasse, seria ele transparente sobre os riscos do modelo?

Deixa a sua resposta nos comentários — esse debate não tem resposta certa.

---

## Notas de Produção

- **Thumbnail sugerida:** Tela do Claude com bandeira americana bloqueando, data "8/07" em destaque vermelho
- **Short (30s):** Sequência de datas — 9/06 lançamento → 12/06 banimento → 8/07 KYC → ? retorno — perguntar "você está preparado?"
- **Repurposing:** Tabela de cenários (A, B, C) vira carrossel LinkedIn/Instagram
- **Série natural:** ep.1 (este) → ep.2 (guia KYC passo a passo quando fluxo for publicado) → ep.3 (o futuro da IA aberta: o dilema da transparência)
- **Follow-up:** Quando a Anthropic publicar o fluxo exato de KYC, publicar update imediato — janela de busca vai disparar
