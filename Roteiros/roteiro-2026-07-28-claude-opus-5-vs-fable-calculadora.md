---
título: "Claude Opus 5: o modelo mais inteligente da Anthropic agora custa metade do Fable 5"
data: 2026-07-28
status: roteiro
tags: [roteiro, claude, anthropic, opus-5, fable-5, ia, custo, benchmark]
tema: claude-opus-5-vs-fable-calculadora
---

# Roteiro — Claude Opus 5 vs Fable 5: Calculadora de Custo Real

**Duração estimada:** 10–13 min
**Formato:** Educacional + Acionável
**CTA principal:** Migrar para Opus 5 ou calcular custo real no seu workflow

---

## Gancho (0–30s)

> "A Anthropic acabou de lançar o modelo mais inteligente que já criou. E ele custa menos da metade do modelo anterior. Isso não é promoção de lançamento — é o preço permanente. Fico aqui e te mostro exatamente o que muda, o que não muda, e quanto isso representa em reais no seu bolso todo mês."

**Visual sugerido:** Print do benchmark Artificial Analysis Intelligence Index v4.1 — Opus 5 com 61 pontos vs Fable 5 com 60 pontos, lado a lado com tabela de preços.

---

## Introdução (30s–2min)

- Contexto: Anthropic lançou o Claude Opus 5 em 24 de julho de 2026
- Identificador de modelo: `claude-opus-5`
- Preço: $5/$25 por milhão de tokens (entrada/saída) — mesmo preço do Opus 4.8
- Fale sobre a janela de confusão: "Opus 5 é mais caro ou mais barato que Fable 5?"
  - Fable 5: $10/$50 por M tokens
  - Opus 5: $5/$25 por M tokens → **metade do custo**
- Pergunta geradora de retenção: "Então por que alguém pagaria o dobro pelo Fable 5?"

---

## Bloco 1 — O que o Opus 5 faz melhor (2min–5min)

### Benchmarks que importam (não os que a Anthropic escolheu mostrar)

- **Artificial Analysis Intelligence Index v4.1**: Opus 5 → 61 | Fable 5 → 60
  - Significa: desempenho geral praticamente igual, com vantagem mínima do Opus 5
- **ARC-AGI 3**: Opus 5 é 3× melhor que o segundo colocado
  - Significa: raciocínio em problemas novos — o tipo de tarefa que mais importa para agentes autônomos
- **OSWorld 2.0** (tarefas de computador): Opus 5 supera Fable 5 a ⅓ do custo por tarefa
  - Significa: automação de desktop, uso em agentes, micro SaaS
- **CursorBench 3.2** (codificação no editor): Opus 5 a 0,5% do Fable 5, pela metade do preço
  - Significa: para 99,5% das tarefas de código, Opus 5 entrega o mesmo resultado pela metade

### Quando Fable 5 ainda ganha

- Tarefas que exigem raciocínio filosófico ou ético muito fino
- Casos de uso de segurança crítica (Mythos 5 é a versão especializada aqui)
- Contextos com restrições governamentais específicas (histórico de export controls)

---

## Bloco 2 — Calculadora de custo real em reais (5min–8min)

### Fórmula base

> Custo mensal (R$) = (tokens de entrada + tokens de saída) × taxa × câmbio

**Exemplos concretos para criador brasileiro:**

| Caso de uso | Tokens/mês estimados | Fable 5 (R$) | Opus 5 (R$) | Economia |
|---|---|---|---|---|
| Roteiro semanal (4 roteiros × 3k tokens) | 50k entrada + 50k saída | ~R$ 29 | ~R$ 14 | 52% |
| Agente pesquisa diária (vault Obsidian) | 300k entrada + 100k saída | ~R$ 130 | ~R$ 65 | 50% |
| Micro SaaS com 100 usuários ativos | 5M entrada + 2M saída | ~R$ 2.380 | ~R$ 1.190 | 50% |

**Taxa de câmbio usada:** R$ 5,50 / US$1 (ajustar conforme o dia)

### Fast Mode Preview (quando vale)

- Preço: $10/$50 por M tokens (dobro do Opus 5 padrão, igual ao Fable 5)
- Velocidade: 2,5× mais rápido
- Quando usar: aplicações em tempo real, chatbots com usuário aguardando, demos ao vivo

---

## Bloco 3 — O que fazer agora (8min–11min)

### Passo a passo para migrar

1. **Identifique** quais chamadas de API usam `claude-fable-5` ou `claude-opus-4-8`
2. **Substitua** por `claude-opus-5` em ambiente de staging
3. **Rode os mesmos prompts** e compare outputs — para 95% dos casos, vai ser equivalente
4. **Monitore** custo por 3 dias — espere ver corte de 40–50% na fatura

### Para quem usa via interface (claude.ai)

- Opus 5 já é selecionável nos planos Pro, Max, Team e Enterprise
- Se você estava no Fable 5 por padrão: teste Opus 5 por 1 semana, compare qualidade percebida
- Dica: use o **dial de esforço** (baixo/médio/alto) por requisição — economiza tokens em tarefas simples

### Open Source: oferta da Anthropic

- Mantenedores de projetos open source recebem **6 meses de Claude Max 20×** gratuitamente
- Como se inscrever: acessar o portal de parceiros Anthropic (link na descrição)
- Vale para projetos no GitHub com histórico real de contribuições

---

## CTA e Encerramento (11min–13min)

**CTA principal:**
> "Vai lá na sua conta Anthropic agora, troca o modelo para `claude-opus-5` e manda no comentário o quanto você economizou no primeiro mês. Eu vou ler todos e vou trazer os resultados num vídeo de follow-up."

**Teaser do próximo vídeo:**
> "No próximo vídeo eu vou falar sobre algo que a maioria das pessoas ainda não entendeu sobre a IA em 2026: a fase de chat acabou. Agora a IA toma decisões sozinha — e isso muda tudo para quem trabalha com tecnologia no Brasil."

**Links para colocar na descrição:**
- Página de preços Anthropic (anthropic.com/pricing)
- Portal de parceiros para open source
- [[pesquisa-2026-07-28]] — nota de pesquisa com dados deste vídeo

---

## Notas de produção

- **Thumbnail sugerida:** Opus 5 vs Fable 5, tabela de preços com "METADE DO PREÇO" em destaque
- **Tags YouTube:** claude opus 5, anthropic 2026, modelos ia, ia para devs, micro saas ia, custo ia brasil
- **Melhor horário de publicação:** terça ou quarta, 18h–20h (audiência BR de tecnologia)
