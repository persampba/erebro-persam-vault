---
título: "KYC Anthropic: Faltam 2 Dias — O Que Todo Brasileiro Precisa Fazer Antes de 8 de Julho"
data: 2026-07-06
status: roteiro
tags: [roteiro, anthropic, kyc, verificacao, fable-5, brasil, urgencia]
projeto-relacionado: ""
pesquisa-base: [[Referências/pesquisa-2026-07-06]]
tema: IA e Claude
angulo: urgência + guia prático para brasileiros antes do prazo
janela: 2 dias (deadline 8/07/2026)
duracao-estimada: 10-12 minutos
formato: YouTube longo + Short de gancho
---

## Gancho (0–30s)

**[Câmera frontal, expressão direta]**

"Em 48 horas, a Anthropic vai pedir o seu RG para continuar usando o Claude.

E não, não é para todo mundo ao mesmo tempo. Mas pode ser para você.

Nesse vídeo eu vou te contar exatamente quem precisa verificar, quais documentos são aceitos, o que acontece com seus dados — e o que provavelmente vai acontecer com o Fable 5 depois de amanhã.

Fica até o final porque tem um detalhe sobre as contas corporativas que a maioria vai ignorar e se arrepender."

---

## Introdução (30s–2min)

**[Contexto rápido]**

Tudo começou em junho, quando o governo americano suspendeu o Claude Fable 5 e o Mythos 5 para usuários fora dos EUA. O motivo foi curioso: as próprias declarações públicas de Dario Amodei sobre as capacidades de cibersegurança do modelo foram usadas como justificativa pelo Departamento de Comércio americano.

A Anthropic, sem como verificar a nacionalidade dos usuários em tempo real, simplesmente tirou o modelo do ar globalmente.

A solução encontrada foi o KYC — verificação de identidade — que entra em vigor em **8 de julho de 2026**, ou seja, em **48 horas a partir de hoje**.

Mas calma. Antes de entrar em pânico, tem um detalhe importante que toda cobertura está passando por cima: **a verificação NÃO é obrigatória para todo mundo ao mesmo tempo**. Ela é acionada em situações específicas. E tem uma lista de contas completamente isentas.

Vamos destrinchar tudo isso agora.

---

## Bloco 1 — Quem Precisa Verificar e Quem Está Isento (2min–5min)

**[Título de seção na tela: "Quem é afetado?"]**

### Contas que PODEM ser solicitadas a verificar

A política afeta os planos:
- **Free** — conta gratuita do claude.ai
- **Pro** — US$ 20/mês
- **Max** — US$ 100/mês e US$ 200/mês

A verificação é acionada quando a Anthropic detecta um dos seguintes cenários:
1. Suspeita de fraude ou abuso na conta
2. Indícios de uso por menores de idade
3. Tentativa de acesso a funções restritas a determinadas jurisdições
4. **Conta criada ou acessada de países não suportados**

Esse último ponto é o que mais impacta brasileiros: se você usa VPN ou o sistema detectou comportamento inconsistente com sua localização, pode ser solicitado.

### Contas ISENTAS — sem RG, sem selfie

✅ **Claude Team** (US$ 25/assento/mês)
✅ **Claude Enterprise**
✅ **Acesso via API** (qualquer plano com chave de API)

Se você é desenvolvedor e usa a API diretamente, ou se seu acesso é via conta corporativa, **você não vai passar pelo processo de KYC na plataforma de usuário final**.

**[Momento de impacto]**

Isso tem uma implicação prática direta: se você faz micro SaaS ou automatiza fluxos via API, sua operação não é afetada pelo KYC do dia 8.

---

## Bloco 2 — Documentos Aceitos e Como o Processo Funciona (5min–8min)

**[Título de seção: "Como verificar — passo a passo"]**

### Documentos aceitos para brasileiros

A Anthropic aceita documentos emitidos pelo governo. Para o Brasil:
- **RG** (novo modelo — o digital não é aceito, precisa ser o físico)
- **CNH** (Carteira Nacional de Habilitação)
- **Passaporte**

**Atenção**: versões digitais dos documentos (RG digital, app Gov.br) **não são aceitas**. Precisa ser o documento físico original fotografado.

### O processo de verificação

A Anthropic terceirizou o processo para a **Persona** — uma empresa americana de KYC bastante usada no ecossistema de fintechs dos EUA.

O fluxo é:
1. Você acessa claude.ai e, se solicitado, é redirecionado para o fluxo de verificação
2. Fotografa seu documento (frente e verso)
3. Tira uma selfie ou grava um vídeo curto ao vivo (para verificar biometria facial)
4. A Persona valida e envia confirmação para a Anthropic

**Onde ficam seus dados?**

Seus documentos e selfie são coletados e mantidos pela **Persona**, não nos servidores da Anthropic. A Anthropic só consulta o registro na plataforma da Persona quando precisa (por exemplo, para analisar um recurso). Não há cópia nem armazenamento direto nas infraestruturas da Anthropic.

É justo ter ressalvas sobre isso — estamos entregando biometria facial para uma empresa americana terceirizada. Mas esse é o modelo adotado.

---

## Bloco 3 — O Que Acontece Com o Fable 5 e o Que Esperar Depois (8min–10min30s)

**[Título de seção: "E o Fable 5?"]**

Aqui está a parte que mais gera confusão.

O **Claude Fable 5** voltou em 1º de julho após 23 dias bloqueado — com um novo classificador de segurança que bloqueia técnicas de risco em mais de 99% dos casos. Esse classificador foi a condição exigida pelo Departamento de Comércio americano para reativar o modelo.

O KYC do dia 8 é **diferente** do desbloqueio do Fable 5. São dois processos paralelos:

| Processo | Prazo | Para quem |
|---------|-------|----------|
| KYC (verificação identidade) | 8 de julho | Free, Pro, Max sem verificação |
| Acesso ao Fable 5 pós-retorno | Em andamento | Todos os planos (restauração gradual) |

O **Opus 4.8** continua disponível para usuários brasileiros verificados, independentemente do status do Fable 5.

### Os 3 cenários para o Fable 5 daqui para frente

**Cenário A — Resolução via KYC (mais plausível):** O KYC cria um layer de verificação de nacionalidade que satisfaz as exigências do governo americano. Usuários brasileiros verificados ganham acesso progressivamente ao Fable 5.

**Cenário B — Restrição permanente para não-americanos:** Improvável, dado que o Brasil é o 3º maior mercado da Anthropic. A empresa tem incentivo econômico forte para resolver.

**Cenário C — Expansão para Mythos 5:** O Mythos 5 já foi liberado para 100+ instituições americanas via carta do Secretário de Comércio Howard Lutnick. A expansão gradual para usuários internacionais verificados é o próximo passo esperado.

---

## CTA e Encerramento (10min30s–12min)

**[Direto, sem floreios]**

Resumo do que você precisa saber:

**Se você usa Free, Pro ou Max:**
- Tenha em mãos RG físico, CNH ou passaporte
- Acesse claude.ai normalmente — se for solicitado, siga o fluxo da Persona
- A verificação não é automática para todos: você pode não ser solicitado imediatamente

**Se você usa API ou conta Team/Enterprise:**
- Você está isento. Continue normalmente.

**Se você usa o Fable 5:**
- Ele está disponível, mas a restauração via cloud providers (AWS, GCP, Microsoft Foundry) ainda está em andamento
- Opus 4.8 funciona plenamente para todo uso normal

Uma pergunta pra você nos comentários: **você acha que a Anthropic deveria ter ficado quieta sobre as capacidades do Fable 5 para evitar o bloqueio?** Essa é a questão filosófica mais importante da semana.

Se esse vídeo te ajudou, me segue porque nos próximos dias vou cobrir o que acontece depois do dia 8 e quando o Fable 5 vai estar totalmente disponível para todos os brasileiros.

Até o próximo.

---

## Notas de Produção

- **Thumbnail sugerida**: documento de identidade pixelado + logo Anthropic + texto "8 de julho — você está pronto?"
- **Short de gancho (30s)**: abrir com "Em 48 horas, a Anthropic vai pedir seu RG" — cortar no Bloco 1 com CTA para o vídeo longo
- **Tags YouTube sugeridas**: KYC Anthropic, Claude verificação identidade, Fable 5 Brasil, Anthropic julho 2026, Claude acesso brasileiro
- **Série natural**: Ep. 1 (este) → Ep. 2 (o que mudou depois de 8/07) → Ep. 3 (quando o Fable 5 volta para todos os brasileiros)
