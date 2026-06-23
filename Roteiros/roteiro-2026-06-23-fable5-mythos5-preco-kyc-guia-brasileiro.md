---
título: "Fable 5 e Mythos 5 Voltam Mais Baratos — O Guia Completo de KYC Para Brasileiros (15 Dias)"
data: 2026-06-23
status: roteiro
tema: fable5-mythos5-preco-kyc-guia-brasileiro
tags: [roteiro, claude, fable5, mythos5, anthropic, kyc, verificacao, preco, token, brasil, prazo]
fonte-pesquisa: "[[Referências/pesquisa-2026-06-23]]"
duracao-estimada: 13-16 minutos
formato: tutorial-urgente
---

## Contexto do Vídeo

**Por que fazer agora:** A Anthropic confirmou o retorno do Claude Fable 5 e Mythos 5 com preço cortado pela metade em relação ao antigo Mythos Preview — $10/$50 por milhão de tokens. O prazo para verificação de identidade (KYC) é 8 de julho de 2026, em 15 dias. Brasileiros que não completarem o KYC até essa data perderão acesso progressivo aos modelos de fronteira da Anthropic. A cobertura brasileira tem falado muito sobre o bloqueio e o quando volta, mas ninguém traduziu concretamente os passos práticos para verificar identidade e o que o preço novo significa para quem usa a API.

**Ângulo diferencial:** O que a maioria não fez ainda: combinar (1) o prazo real do KYC + o que fazer passo a passo + (2) o que o novo preço de $10/$50 significa para quem constrói micro SaaS ou usa Claude como ferramenta de trabalho — com análise de custo/benefício real.

---

## Gancho (0–30s)

> "Você tem 15 dias. Em 8 de julho, a Anthropic exige verificação de identidade para manter acesso ao Claude Fable 5 e Mythos 5. Se você não fizer isso, perde acesso a esses modelos. Mas tem uma notícia boa que ninguém está falando: Fable 5 e Mythos 5 vão voltar custando menos da metade do preço antigo. Neste vídeo eu vou te mostrar exatamente o que você precisa fazer agora, quanto vai custar, e se vale a pena para quem usa Claude para trabalho ou para construir negócio no Brasil."

---

## Introdução (30s–2min)

**Contexto rápido:**

Em 12 de junho de 2026, o governo americano emitiu uma diretiva de exportação que forçou a Anthropic a suspender Claude Fable 5 globalmente — incluindo para o Brasil. O motivo oficial foi que a Anthropic não conseguia verificar a nacionalidade dos usuários em tempo real. A solução da Anthropic foi criar um sistema de KYC (Know Your Customer) — verificação de identidade — com prazo de 8 de julho.

**O que é KYC:**

KYC é verificação de identidade. Bancos fazem isso. A Anthropic vai exigir o mesmo: você comprova quem você é, e em troca mantém acesso aos modelos mais avançados. Não é nada novo para quem já abriu conta em banco digital no Brasil.

**Contrato com o espectador:**
"Nos próximos 13 minutos: (1) Passo a passo do KYC para brasileiros; (2) O que fica disponível com e sem verificação; (3) O novo preço de Fable 5 e Mythos 5 e o que isso muda para quem usa API ou constrói com Claude."

---

## Bloco 1 — O KYC da Anthropic: O Que Você Precisa Fazer (2min–5min)

### Prazo e impacto

**Data limite: 8 de julho de 2026 (15 dias a partir de hoje)**

Após essa data:
- Usuários **sem KYC completo**: acesso limitado ao Claude Opus 4.8 e modelos mais antigos; sem acesso ao Fable 5 e Mythos 5 quando voltarem
- Usuários **com KYC completo**: acesso pleno ao Fable 5, Mythos 5, e modelos de fronteira futuros

### Passo a passo para completar o KYC

**Passo 1: Acesse claude.ai com sua conta existente**

Se você já tem conta na Anthropic, entre normalmente. O sistema vai solicitar verificação de identidade antes de 8 de julho. Se não tem conta, crie agora para ter mais tempo de completar o processo.

**Passo 2: Inicie o fluxo de verificação**

Na plataforma, procure o banner ou notificação de "Identity Verification" / "Verificação de Identidade". O processo usa um serviço terceiro de verificação (similar ao que bancos digitais usam).

**Passo 3: Documentos aceitos para brasileiros**

A verificação aceita documentos oficiais com foto. Para brasileiros:
- **RG** com foto clara (frente e verso)
- **CNH** (Carteira Nacional de Habilitação)
- **Passaporte brasileiro** (se disponível)

O processo é fotografar o documento e fazer uma selfie — o mesmo fluxo do Nubank, C6 ou Itaú digital.

**Passo 4: Aguarde a confirmação**

O processo leva de alguns minutos a até 48 horas em casos de revisão manual. Você recebe email confirmando aprovação.

### O que fazer se não tiver documentos digitalizados

- Use o celular para fotografar com boa iluminação
- Fundo neutro (branco ou cinza) melhora a taxa de aprovação
- Evite reflexo na foto do documento (problema mais comum que causa rejeição)
- Se der erro no RG, tente a CNH — diferentes documentos têm taxas de sucesso diferentes dependendo do sistema de OCR

### O que acontece com quem não verificar

Opus 4.8 continua disponível para usuários verificados independentemente do Fable 5. Para usuários sem KYC, a Anthropic ainda não anunciou oficialmente o que fica disponível. Por precaução: complete o KYC agora para não ter surpresa.

---

## Bloco 2 — O Preço Novo: Fable 5 e Mythos 5 Pela Metade (5min–9min)

### O que foi anunciado

Quando Fable 5 e Mythos 5 retornarem, o preço será:
- **$10 por milhão de tokens de entrada**
- **$50 por milhão de tokens de saída**

Esse é **menos da metade** do preço do Claude Mythos Preview — que era substancialmente mais caro e acessível apenas para clientes enterprise.

### O que são Fable 5 e Mythos 5

**Fable 5** — descrito pela Anthropic como o modelo mais capaz amplamente disponível:
- Pensamento adaptativo sempre ativo (não precisa ativar manualmente)
- Janela de contexto de 1 milhão de tokens
- 128K tokens de saída (o dobro do que a maioria dos modelos oferece)
- Capacidades de codificação, análise e raciocínio de ponta

**Mythos 5** — versão ainda mais avançada:
- Mesmo nível de capacidades do Fable 5 mas otimizado para tarefas específicas
- Acesso mais restrito — parceiros certificados têm prioridade

### Comparativo de custo real para quem usa API

**Cenário 1: Criador de conteúdo usando Claude para roteiros**

Roteiro médio: ~5.000 tokens de entrada + ~3.000 tokens de saída
- Custo com Fable 5: (5.000 × $0,00001) + (3.000 × $0,00005) = $0,05 + $0,15 = **$0,20 por roteiro**
- Ao câmbio de R$ 5,50: **R$ 1,10 por roteiro completo**
- 20 roteiros por mês: R$ 22

**Cenário 2: Desenvolvedor de micro SaaS**

App que processa contratos de MEI — 10.000 tokens por análise, 100 análises/mês:
- Custo mensal com Fable 5: ~$50 de entrada + ~$25 de saída = **~$75/mês**
- A R$ 5,50: ~R$ 413/mês
- Se o app cobra R$ 49,90/mês por usuário: precisa de ~9 usuários para cobrir só o custo de IA

**Cenário 3: Empresa com uso intensivo**

1 milhão de tokens de entrada/saída por mês: $60/mês total — custo administrável para qualquer micro SaaS com receita.

### Vale mudar do Opus 4.8 para o Fable 5?

| Critério | Opus 4.8 | Fable 5 |
|----------|----------|---------|
| Disponível agora | Sim | Após KYC (8/07) |
| Janela de contexto | 1M tokens | 1M tokens |
| Pensamento adaptativo | Manual | Sempre ativo |
| Tokens de saída | 64K | 128K |
| Preço entrada | $15/M | $10/M |
| Preço saída | $75/M | $50/M |
| Melhor para | Uso atual sem KYC | Tarefas longas + raciocínio |

**Conclusão prática:** Se você já usa Opus 4.8 e vai completar o KYC, migrar para Fable 5 vai economizar 33% em entrada e 33% em saída, com modelo mais capaz. Faz sentido migrar.

---

## Bloco 3 — O Que Isso Significa Para Quem Constrói Com Claude no Brasil (9min–13min)

### Para quem usa Claude como ferramenta pessoal

Se você usa Claude Pro (assinatura mensal) e não a API, o KYC vai ser necessário para manter acesso ao Fable 5 no chat. O preço da assinatura mensal ainda não foi divulgado separadamente do preço da API — mas espere que o Pro inclua Fable 5 para quem verificou identidade.

**Ação**: Complete o KYC agora. Não há custo adicional na verificação — só o tempo de fazer o processo.

### Para quem usa a API (desenvolvedores e founders)

O novo preço de $10/$50 por milhão de tokens muda o cálculo de viabilidade para micro SaaS com IA:

**Antes do Fable 5 (com Mythos Preview):** Preço era alto demais para micro SaaS de baixo ticket. Só enterprise conseguia absorver o custo.

**Com Fable 5 a $10/$50:** Apps com assinatura de R$ 29,90-49,90/mês conseguem ter margem positiva com menos de 10 usuários ativos por instância.

Isso democratiza o acesso a IA de fronteira para solo founders e pequenas equipes no Brasil.

### O risco de não verificar

Além de perder acesso ao Fable 5, existe um risco de médio prazo: se a Anthropic continuar a tendência de exigir KYC para todos os modelos de fronteira, quem não verificou cedo vai enfrentar cada vez mais restrições. Melhor fazer agora enquanto o prazo está aberto.

### O que vem depois do KYC

A Anthropic mencionou que o KYC vai habilitar também:
- Acesso prioritário a novas features em beta
- Limites de uso mais altos para usuários verificados
- Acesso a Mythos 5 para partners com caso de uso avançado

Em outras palavras: KYC não é só "manter o que tinha" — é a porta para o próximo nível da plataforma.

---

## CTA e Encerramento (13min–16min)

**Resumo do que fazer agora:**

1. **Acesse claude.ai** e inicie o processo de verificação de identidade antes de 8 de julho
2. **Prepare RG ou CNH** com foto clara para o upload
3. **Avalie se você precisa do Fable 5**: para uso casual, Opus 4.8 segue disponível; para tarefas longas e raciocínio avançado, vale verificar
4. **Se você usa API**: calcule seu custo com os novos preços ($10/$50/M tokens) e considere migrar do Opus 4.8 para Fable 5 após KYC
5. **Se você quer construir micro SaaS**: o novo preço do Fable 5 muda o cálculo de viabilidade — revise seu modelo financeiro

**Pergunta para engajamento:**
"Você já iniciou o processo de verificação de identidade na Anthropic? Teve dificuldade com algum documento? Me conta nos comentários — vou responder dúvidas específicas sobre o processo para brasileiros."

**Aviso de serviço público:**
"Manda esse vídeo para alguém que usa Claude e ainda não sabe do prazo. 15 dias passa rápido."

**Próximo vídeo:**
"Semana que vem, vou fazer um teste ao vivo comparando Opus 4.8 vs. Fable 5 em tarefas reais de criação de conteúdo e código — para ajudar você a decidir quando migrar."

---

## Notas de Produção

- **Thumbnail:** Countdown visual "15 DIAS" + logo Claude + RG/documento com destaque; cores urgentes (vermelho/laranja)
- **Hook visual:** Tela do countdown para 8 de julho com calendário; depois corte para print do anúncio oficial da Anthropic
- **Tela de comparação:** Mostrar tabela Opus 4.8 vs. Fable 5 com preços lado a lado
- **Cuidado:** Não instruir o usuário a fotografar documentos em situações de baixa segurança; dizer que o processo é feito dentro da plataforma oficial claude.ai
- **Atualização necessária:** Verificar na semana da publicação se o processo de KYC foi oficialmente aberto — pode haver mudança de prazo ou processo
- **Disclaimer:** Deixar claro que as informações são baseadas nos anúncios disponíveis até a data de publicação; processo pode ter variações
- **Chamada de ação clara:** Repetir o prazo (8 de julho) pelo menos 3 vezes no vídeo para criar urgência genuína
