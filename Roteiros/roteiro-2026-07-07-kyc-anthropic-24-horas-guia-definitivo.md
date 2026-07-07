---
título: "KYC da Anthropic: Faltam 24 Horas — O Guia Definitivo Para Brasileiros Não Perderem o Acesso"
data: 2026-07-07
status: roteiro
tags: [roteiro, anthropic, kyc, claude, fable-5, verificacao-identidade, urgencia]
pesquisa-base: [[Referências/pesquisa-2026-07-07]]
tema-principal: KYC Anthropic prazo 8 de julho
duracao-estimada: 12–15 minutos
---

## Gancho (0–30s)

Amanhã, 8 de julho de 2026, a Anthropic começa a pedir RG e foto do seu rosto para você continuar usando o Claude.

Não é phishing. Não é golpe. É uma decisão real da empresa que, ironicamente, construiu sua reputação se opondo à vigilância.

Se você usa os planos gratuito, Pro ou Max, este vídeo é para você. Porque em 24 horas as regras mudam — e a maioria dos brasileiros nem sabe o que fazer.

---

## Introdução (30s–2min)

Vou explicar em menos de 15 minutos:

- O que é esse KYC e por que a Anthropic está fazendo isso agora
- Se você vai ser afetado (a resposta é mais sutil do que parece)
- Como fazer a verificação, quais documentos são aceitos no Brasil, e o que evitar
- O que muda depois de amanhã para quem verificar — e para quem não verificar
- E a pergunta que ninguém está respondendo: isso tem algo a ver com o Fable 5?

Vamos lá.

---

## Bloco 1: O Que É o KYC e Por Que a Anthropic Está Fazendo Isso (2min–5min)

**KYC** significa "Know Your Customer" — verificação de identidade. É o mesmo processo que bancos, corretoras e cassinos online usam para confirmar quem você é.

A Anthropic anunciou que a partir de 8 de julho pode solicitar verificação de identidade para usuários de planos de consumidor — ou seja: Free, Pro e Max.

Mas por quê agora?

Duas razões entrelaçadas:

**Razão 1: Controle de exportação**
Em 12 de junho de 2026, o governo americano emitiu uma diretiva suspendendo o acesso ao Fable 5 e ao Mythos 5 para usuários internacionais. A Anthropic não tinha como verificar a nacionalidade dos usuários em tempo real — então simplesmente desligou os modelos para todos os não-americanos.

O KYC resolve esse problema. Com verificação de identidade, a Anthropic consegue saber quem é cidadão americano, quem é estrangeiro com clearance, e quem cai nos grupos de restrição.

**Razão 2: Menores e fraude**
A plataforma tem crescido rapidamente. Com crescimento vem abuso — contas falsas, menores de idade acessando funcionalidades restritas, VPNs mascarando localização. O KYC é a resposta padrão da indústria para isso.

O que é irônico — e vale pontuar com honestidade — é que a Anthropic é a mesma empresa que, na sua constituição publicada em junho de 2026, coloca "privacidade do usuário" como valor central. Coletar biometria facial é o oposto disso.

A empresa argumenta que os dados ficam com a **Persona** — a empresa terceirizada de KYC — e não nos servidores da Anthropic. Mas você ainda está entregando a geometria do seu rosto a um sistema integrado à Anthropic.

---

## Bloco 2: Quem é Afetado — e Como Fazer a Verificação (5min–9min)

**Quem é afetado:**
- Planos **Free, Pro e Max** → podem ser solicitados a verificar
- Planos **Team e Enterprise** → isentos
- Acesso via **API** (Console da Anthropic) → isento

**Importante:** a verificação não é automática para todos os usuários Free/Pro/Max. Ela é acionada em situações específicas:
1. Suspeita de fraude ou comportamento atípico
2. Indícios de uso por menor de idade
3. Acesso via VPN ou de países não suportados
4. Tentativa de acesso a funções restritas por região

Ou seja: se você usa o Claude normalmente com seu IP brasileiro, sem VPN, e sem acionar nada suspeito, pode ser que você nunca veja essa tela.

Mas se você usa VPN — pare. A partir de amanhã, VPN pode ser o gatilho que ativa a verificação e, em casos extremos, o bloqueio temporário da conta.

**Como fazer a verificação:**

O processo é feito pelo site **claude.ai**, na seção de configurações de conta. Quando acionado:

1. Você vê uma tela pedindo para verificar sua identidade
2. Clica em "Verificar" e é redirecionado para o sistema da **Persona**
3. Escolhe o tipo de documento: **RG, CNH ou passaporte** (somente físicos originais)
4. Tira foto da frente e do verso do documento
5. Realiza uma selfie ao vivo com câmera ligada — há detecção de vivacidade (você vai mover o rosto)
6. O sistema processa e confirma em minutos

**O que NÃO funciona para brasileiros:**
- RG digital (o novo RG pelo app Gov.br)
- Selfie estática salva na galeria
- Foto de foto do documento
- Documentos vencidos

**Dica prática:** faça em boa iluminação, sem óculos de sol ou máscara. O algoritmo da Persona analisa geometria facial e luz insuficiente causa falha na leitura.

---

## Bloco 3: O Que Muda Depois de Amanhã — e a Conexão com o Fable 5 (9min–13min)

**Cenário A: Você verificou**
- Acesso contínuo ao Claude nos planos Free, Pro e Max
- Elegível para desbloquear modelos de fronteira quando disponíveis para sua jurisdição
- Melhor chance de acesso ao Fable 5 e Mythos 5 quando retornarem globalmente

**Cenário B: Você não verificou e foi acionado**
- Possível restrição progressiva de funcionalidades
- Em casos específicos, bloqueio temporário de conta
- Para a maioria dos usuários que nunca foram acionados: nada muda automaticamente

**E o Fable 5?**

Esta é a pergunta que mais aparece nos comentários. Deixa eu ser direto:

O KYC e o retorno do Fable 5 são **processos separados**, mas relacionados. O Fable 5 voltou em 1º de julho com um classificador de segurança novo que bloqueia técnicas de alto risco em 99%+ dos casos. Mas o acesso internacional ainda depende de autorização do Departamento de Comércio dos EUA.

O KYC é um dos mecanismos que a Anthropic propôs para reabrir o acesso global ao Fable 5 de forma controlada: se você é verificado e identificado como não sendo um agente de risco, a probabilidade de acesso aumenta.

Não há garantia. Mas usuários verificados estão em posição melhor que não verificados quando o acesso global for liberado.

**Para quem acessa via API:**
Se você tem uma organização no Console da Anthropic (acesso programático), você **não precisa** fazer nada. O KYC não afeta contas corporativas ou acesso via API. O Sonnet 5, Opus 4.8 e Fable 5 (onde disponível via API) continuam acessíveis normalmente.

---

## CTA e Encerramento (13min–15min)

Recapitulando o que você precisa fazer agora:

1. **Verifique se está usando VPN** — desative antes de amanhã
2. **Separe um documento físico** — RG físico, CNH ou passaporte
3. **Acesse claude.ai** e veja se há algum banner de verificação pendente
4. **Se a verificação for solicitada**, faça agora, não espere o prazo final
5. **Se você usa o plano Team ou Enterprise** — não precisa fazer nada

A grande questão filosófica aqui é: você confia na Persona com sua biometria para continuar usando a ferramenta de IA que mais usa no seu trabalho?

Isso é uma decisão individual. Mas agora você tem todas as informações para tomá-la.

Se esse vídeo te ajudou, deixa um like — e comenta aqui embaixo: você vai verificar ou está esperando para ver o que acontece? Quero saber o que a galera está decidindo.

Nos vejo no próximo vídeo. Até lá.

---

## Notas de Produção

- **Miniatura sugerida**: relógio mostrando 23:59 + logo Claude + "8 JULHO"
- **Gancho de thumbnail**: "AMANHÃ MUDA TUDO NO CLAUDE"
- **Tags YouTube**: KYC Anthropic, Claude verificação identidade, Fable 5 acesso, Claude bloqueado, Anthropic julho 2026
- **Shorts de apoio**: 30s mostrando o processo passo a passo de verificação na tela
- **Publicar até**: 7 de julho de 2026 (hoje) — publicação noturna maximiza alcance antes do prazo
