---
titulo: Skill de Pesquisa Diária — Cerebro Persam
versao: 1.1.0
atualizado: 2026-04-14
tags:
  - skill
  - pesquisa
  - automacao
  - workflow
---

# Skill: Pesquisa Diária de Conteúdo

Esta skill define como realizar a pesquisa diária de conteúdo para o vault Cerebro Persam, identificar temas virais, e transformar achados em notas e roteiros prontos para produção.

---

## Termos de Busca por Categoria

### IA e Modelos de Linguagem
- `"Claude Anthropic novidades [ANO]"`
- `"ChatGPT atualização [MES] [ANO]"`
- `"Gemini Google novidades [ANO]"`
- `"modelos de linguagem tendências [ANO]"`
- `"agentes de IA autônomos 2026"`
- `"Claude Managed Agents beta"`
- `"LLM benchmark novo [ANO]"`
- `"IA generativa casos de uso empresa [ANO]"`
- `"Anthropic revenue ARR [ANO]"`
- `"OpenAI vs Anthropic [ANO]"`

### Marketing Digital e YouTube
- `"vídeos virais YouTube [ANO]"`
- `"algoritmo YouTube mudança [MES] [ANO]"`
- `"tendências YouTube Shorts [ANO]"`
- `"marketing de conteúdo estratégia [ANO]"`
- `"clipping estratégia conteúdo [ANO]"`
- `"criadores de conteúdo renda [ANO]"`
- `"como viralizar YouTube [ANO]"`
- `"branded content marketing invisível [ANO]"`

### Micro SaaS e Empreendedorismo Digital
- `"micro SaaS crescimento [ANO] Brasil"`
- `"micro SaaS ideias [ANO]"`
- `"SaaS com IA [ANO]"`
- `"micro SaaS agentes IA [ANO]"`
- `"negócio digital solo founder [ANO]"`
- `"no-code micro SaaS [ANO]"`
- `"SaaS vertical nicho Brasil [ANO]"`
- `"como lançar SaaS 30 dias [ANO]"`

### Ferramentas para Criadores
- `"ferramentas IA criadores de conteúdo [ANO]"`
- `"edição de vídeo IA [ANO]"`
- `"Descript alternativas [ANO]"`
- `"Runway Gen [versão] review"`
- `"Google Veo [versão] novidades"`
- `"CapCut atualização IA [ANO]"`
- `"ferramentas IA produtividade criador [ANO]"`
- `"podcast IA ferramentas gratuitas [ANO]"`

### Tendências Gerais de Tecnologia
- `"inteligência artificial tendências [MES] [ANO]"`
- `"Physical AI robótica [ANO]"`
- `"computação quântica IA [ANO]"`
- `"IA governança ética regulação [ANO]"`
- `"tecnologia empregos impacto [ANO]"`
- `"startups IA Brasil [ANO]"`

---

## Ângulos de Tendência Identificados em 2026

### Ângulos de Alto Potencial Viral
1. **"O que a empresa X não quer que você saiba"** — funciona para qualquer big tech com novo produto
2. **"X% das pessoas fazem Y — você é da outra parte?"** — polarização que gera cliques
3. **"Como fazer X em N dias (resultado real, não promessa)"** — tutoriais com credibilidade
4. **"Estou testando X por 30 dias — olha o que aconteceu"** — narrativa de jornada
5. **"A oportunidade que vai fechar em [prazo]"** — urgência baseada em janela de mercado
6. **"Por que [tendência óbvia] está errada"** — contraposição a consensus

### Formatos com Melhor Performance em Abril 2026
- Vídeos de 10–15 minutos no YouTube (análise + tutorial)
- Shorts de 30–45 segundos como "trailer" do vídeo longo
- Carrosséis no LinkedIn com dados e análise
- Threads no X/Twitter com thread-hooks fortes

### Nichos Subexplorados em Conteúdo PT-BR
- Claude API e desenvolvimento com Anthropic SDK
- Micro SaaS com agentes de IA (muito pouco conteúdo em português)
- Physical AI e robótica para leigos
- Governança e regulação de IA no Brasil
- Comparativos reais de ferramentas (não patrocinados)

---

## Estrutura de Nota de Pesquisa

```markdown
---
titulo: Pesquisa Diária — [DATA]
data: [YYYY-MM-DD]
fonte: WebSearch
tags: [pesquisa, temas relevantes]
status: referencia
---

## Destaques do Dia
## Marketing Digital e YouTube
## IA e Claude
## SaaS
## Ferramentas para Criadores
## Fontes Consultadas
```

---

## Critérios de Seleção de Tema para Roteiro

Priorizar temas que satisfaçam pelo menos 3 dos critérios abaixo:

- [ ] Dado numérico impactante e verificável
- [ ] Evento recente (últimos 7 dias)
- [ ] Pouco coberto em conteúdo PT-BR
- [ ] Conecta IA com impacto prático no Brasil
- [ ] Tem ângulo de oportunidade ou urgência
- [ ] Gera polarização ou debate (sem ser clickbait vazio)
- [ ] Tem potencial de evergreen (conteúdo útil além da data de publicação)

---

## Exemplos de Ângulos Usados com Sucesso (Abril 2026)

| Tema | Ângulo Escolhido | Potencial |
|------|-----------------|-----------|
| Claude for Word | "Anthropic está montando o sistema operacional da IA para o trabalho" | Alto |
| Micro SaaS + agentes | "67% das startups serão micro SaaS — como entrar agora" | Alto |
| Vídeos virais 2026 | "Marketing invisível domina: o que realmente viraliza" | Médio-alto |
| Ferramentas de IA | "87% dos criadores usam IA — os 13% estão perdendo dinheiro" | Médio |

---

## Workflow de Produção Diária

1. **Pesquisa** (5 buscas em paralelo, uma por categoria)
2. **Síntese** → `Referências/pesquisa-[DATA].md`
3. **Seleção** → 2 temas que satisfaçam ≥3 critérios acima
4. **Roteiro** → `Roteiros/roteiro-[DATA]-[tema-kebab].md`
5. **Commit e push** → `git add . && git commit -m 'pesquisa diária [DATA]' && git push origin main`

---

## Histórico de Atualizações

| Data | Versão | Mudança |
|------|--------|---------|
| 2026-04-14 | 1.1.0 | Criação inicial da skill com termos, ângulos e critérios baseados na pesquisa de estreia |
