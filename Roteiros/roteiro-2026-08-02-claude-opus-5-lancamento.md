---
título: Claude Opus 5 — O que 1 Milhão de Tokens Significa na Prática
data: 2026-08-02
projeto: claude-opus-5-analise
status: rascunho
tags: [roteiro, ia, claude, anthropic, opus-5, analise]
duracao-estimada: 12-15 min
---

# Roteiro — Claude Opus 5: O que 1 Milhão de Tokens Significa na Prática

## Foco principal
> O espectador vai entender o que mudou com o Opus 5 — não em termos técnicos, mas em impacto real no trabalho. Vai sair com exemplos concretos de quando usar Opus 5 vs Sonnet 5 e uma visão clara de para onde a Anthropic está indo.

---

## Gancho (0–30s)

"Em 24 de julho a Anthropic lançou o Claude Opus 5. E a maioria das pessoas não percebeu o que realmente mudou. Não é só um número maior de tokens. É a primeira vez que um modelo de IA consegue processar um livro inteiro, uma codebase completa, ou cinco anos de e-mails corporativos — em uma única conversa. Hoje eu vou te mostrar o que isso significa na prática."

*[mostrar tela com interface do Claude carregando um arquivo grande]*

---

## Introdução (30s–2min)

Contextualização rápida:
- O que é o Claude Opus 5 — lançado em 24 de julho de 2026
- Sucede o Opus 4.8
- Três números que importam: 1M de tokens de contexto, 128K de tokens de saída, raciocínio adaptativo por padrão com 5 níveis de esforço

Comparação concreta para o espectador entender:
- 1 milhão de tokens = aproximadamente 750.000 palavras = o Harry Potter completo (7 livros) cabe em uma única conversa
- 128K de saída = Claude consegue ESCREVER um livro, não só ler um

Pergunta retórica: "Mas pra que isso serve no mundo real?"

---

## Desenvolvimento

### Bloco 1 — O que é raciocínio adaptativo e por que isso muda tudo

- Antes: Claude pensava sempre no mesmo nível de profundidade
- Agora: 5 níveis de esforço de raciocínio — de resposta rápida até raciocínio ultradetalhado
- Na prática: você faz uma pergunta simples, ele não gasta tokens à toa; para uma análise complexa, ele vai fundo
- Exemplo ao vivo: pedir análise de um contrato de 50 páginas vs perguntar qual é a capital da França — comportamento diferente, custo diferente

*[demonstração na tela — colar um documento longo e pedir análise estruturada]*

Ângulo diferenciado: "O Opus 5 não é mais caro por capricho. É mais caro porque ele pensa mais. E você controla quando ele pensa."

---

### Bloco 2 — Casos de uso reais (o que eu testei)

**Caso 1: Auditoria de codebase inteira**
- Colei uma codebase de 80 mil linhas de código
- Pedi: identifique todos os pontos de falha de segurança, inconsistências de nomenclatura e dead code
- Resultado: relatório estruturado em 3 minutos, com linha específica de cada problema

**Caso 2: Análise de documentos corporativos**
- 5 anos de atas de reunião de uma empresa (simulado)
- Pergunta: "Quais foram os temas que mais apareceram em momentos de crise?"
- Resultado: linha do tempo temática com citações diretas das atas

**Caso 3: Geração de conteúdo longo**
- Pedi um roteiro de curso completo com 10 módulos, exercícios e avaliações
- 128K de saída: o conteúdo saiu completo, sem precisar de múltiplas chamadas

*[mostrar prints ou tela em tempo real dos testes]*

---

### Bloco 3 — Opus 5 vs Sonnet 5: quando usar cada um

Comparação direta (tabela mental):

| Situação | Use |
|---|---|
| Emails, resumos, posts | Sonnet 5 |
| Análise de documentos > 50 páginas | Opus 5 |
| Código de funções simples | Sonnet 5 |
| Auditoria de codebase completa | Opus 5 |
| Geração de conteúdo curto | Sonnet 5 |
| Relatório > 10.000 palavras | Opus 5 |
| Pesquisa rápida | Sonnet 5 |
| Análise estratégica profunda | Opus 5 |

Regra prática: "Se você não tem certeza, comece com Sonnet 5. Suba para Opus 5 quando sentir que a resposta ficou superficial ou incompleta."

Custo: Opus 5 custa mais por token, mas como ele precisa de menos chamadas para tarefas complexas, o custo total pode ser equivalente ou menor.

*[exemplo numérico: 10 chamadas ao Sonnet 5 vs 1 chamada ao Opus 5 para a mesma tarefa]*

---

## CTA e Encerramento

**Resumo dos 3 pontos:**
1. Opus 5 tem 1M de tokens de contexto — você pode processar qualquer documento, codebase ou arquivo que você tem
2. Raciocínio adaptativo significa que ele pensa na profundidade certa para cada tarefa
3. A regra é simples: Sonnet 5 para velocidade e custo, Opus 5 quando a profundidade importa

**CTA:**
"Se você quiser testar o Opus 5, o link está na descrição. E se você quiser ver mais análises práticas de IA sem enrolação — sem afiliados, sem patrocinador disfarçado — inscreve no canal e ativa o sino. Na semana que vem vou mostrar como o AI Act europeu que entrou em vigor hoje afeta criadores e desenvolvedores brasileiros. Nos vemos lá."

*[tela final com subscribe + link]*

---

## Revisão

- [ ] Leu em voz alta
- [ ] Checou duração estimada
- [ ] Revisou CTA
- [ ] Confirmou dados (janela 1M, saída 128K, lançamento 24 jul 2026)
- [ ] Preparou demonstrações ao vivo para o Bloco 2
