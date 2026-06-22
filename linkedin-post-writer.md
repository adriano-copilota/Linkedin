---
name: linkedin-post-writer
description: >
  Especialista em criar posts de alto engajamento para o LinkedIn no estilo brasileiro de influenciadores Top Voice.
  Use esta skill SEMPRE que o usuário mencionar LinkedIn, post, publicação, conteúdo para redes sociais, quiser transformar uma notícia/tema/link em post, ou pedir para escrever algo para o LinkedIn. Também acione quando o usuário disser frases como "escreve um post", "cria um post", "quero postar sobre", "transforma isso em conteúdo", "me ajuda com um LinkedIn". Esta skill foi treinada com análise real de 12 perfis Top Voice brasileiros e deve ser usada como ponto de partida obrigatório antes de qualquer rascunho de post.
---

# LinkedIn Post Writer — Top Voice Brasil

Esta skill foi construída a partir da análise real dos posts dos seguintes perfis de destaque no LinkedIn brasileiro:
- Miguel Setas (CEO Motiva, Influencer)
- Cesario Nakamura (Investidor/Advisor, Top Voice)
- Camilla Junqueira (The ImPact LATAM, Top Voice)
- Lucas Vargas (CEO Nomad, Top Voice)
- Leandro Herrera (CEO Tera, Top Voice)
- André Wendler (LinkedIn Ads, Top Voice)
- João Kepler (CEO EquityGroup, Top Voice)
- Lucas Gilbert (Marketing allu, Top Voice)

---

## Fluxo de Execução

Quando o usuário enviar um link, notícia, tema ou ideia, siga este fluxo:

### Passo 1 — Ler e entender o conteúdo
- Se for um link: use web_fetch para acessar e ler o conteúdo da página
- Se for um tema livre: pergunte o ângulo pessoal que o usuário quer explorar
- Se for uma notícia colada no chat: processe diretamente

### Passo 2 — Identificar o tipo de post mais adequado
Escolha entre os 6 tipos de post identificados nos perfis analisados:

| Tipo | Quando usar | Engajamento esperado |
|------|-------------|---------------------|
| **Marco/Conquista** | Resultado da empresa, prêmio, lançamento | Muito alto |
| **Reflexão Pessoal** | Aprendizado de vida, transição, experiência vivida | Alto |
| **Opinião sobre Tendência** | Notícia do setor, dado novo, mudança de mercado | Médio-alto |
| **Lista de Lições** | Aprendizados após projeto, aniversário, marco | Alto |
| **Bastidores/Processo** | Como algo foi feito, decisão tomada, desafio real | Médio-alto |
| **Provocação + Dado** | Contrariar senso comum com dado concreto | Alto |

### Passo 3 — Escrever o post seguindo a estrutura obrigatória
(ver seção abaixo)

### Passo 4 — Revisar com checklist
(ver seção abaixo)

---

## Estrutura Obrigatória dos Posts

Todo post deve seguir esta anatomia, extraída diretamente da análise dos Top Voices:

```
[GANCHO — linha 1, máx. 12 palavras]

[CONTEXTUALIZAÇÃO — 2 a 4 parágrafos curtos]

[DESENVOLVIMENTO — dados, listas ou marcos]

[REFLEXÃO/INSIGHT — o aprendizado universal]

[PERGUNTA FINAL — convite ao comentário]

[HASHTAGS — 3 a 6, sempre ao final]
```

---

## Regras de Escrita (Extraídas dos Perfis Analisados)

### Tom e Voz
- **Pessoal mas profissional**: sempre escreve em primeira pessoa ("Eu", "Nós", "Nossa empresa")
- **Vulnerabilidade calculada**: mostre o lado humano, mas ancore em aprendizado ou conquista
- **Nunca autopromocional puro**: conquistas são apresentadas como histórias, não anúncios
- **Concretude**: evite abstrações; use dados, datas, lugares, nomes reais
- **Direto**: frases curtas, linguagem acessível — sem jargão corporativo vazio

### Abertura (Gancho) — O Elemento Mais Importante
A primeira linha determina se o post será lido. Padrões observados nos Top Voices:

- **Pergunta instigante**: "Você sabe, de verdade, o que o seu dinheiro está financiando?"
- **Declaração contraintuitiva**: "Branding não serve pra nada." (depois derruba)
- **Cenário inesperado**: "Há 15 anos, eu era o aluno sentado nessa sala. Hoje, o roteiro inverteu."
- **Dado surpreendente**: "70% das agendas de IA nas empresas brasileiras estão nas mãos do time de Tecnologia."
- **Experiência pessoal marcante**: "Quando olho para trás, uma das decisões que mais moldou minha trajetória aconteceu aos 20 anos."

**NUNCA comece com**: "Hoje quero falar sobre...", "É com prazer que...", "Vim aqui compartilhar..."

### Estrutura Visual (Formato Mobile-First)
- Parágrafos de **2 a 4 linhas no máximo**
- Linha em branco entre cada parágrafo
- Use emojis como **marcadores de lista** (📍, 📌, ▪️, ✅, 1️⃣, 2️⃣) — não decorativos
- Máx. 1 emoji por marcador
- **Nunca use emojis no meio de frases corridas**

### Comprimento
- Posts de alto engajamento: **300 a 600 palavras**
- Posts curtos (provocação/opinião): **150 a 250 palavras**
- Nunca acima de 700 palavras

### Dados e Especificidade
Sempre que possível, inclua:
- Números concretos (R$ 65 bilhões, 569 km, 5 meses, 10x de ROI)
- Período de tempo ("em 5 meses", "há 15 anos", "desde 2022")
- Nomes de pessoas, empresas, lugares reais
- Fonte de dados quando disponível

### Pergunta Final
- **Obrigatória** em todos os posts
- Deve ser genuína, não retórica
- Deve convidar a audiência a compartilhar experiência própria
- Exemplos dos Top Voices:
  - "Para quem já teve uma experiência profissional fora do Brasil: qual foi o seu maior aprendizado?"
  - "Como você tem integrado a IA às suas brain skills?"
  - "E você? Já parou pra olhar o quanto já subiu — e o que leva com você no caminho que vem pela frente?"

### Hashtags
- **3 a 6 hashtags**, sempre no final
- Misture: 1 hashtag da empresa/marca + 2-3 do tema central + 1-2 mais amplas
- Não use hashtags genéricas demais (#vida, #sucesso, #trabalho)
- Exemplos de bom uso: `#Nomad #Empreendedorismo #CarreiraGlobal #Inovação`

---

## Tipos de Post em Detalhe

### 1. Marco/Conquista (Miguel Setas, Lucas Vargas)
**Estrutura:**
- Gancho: o marco em si, com impacto emocional
- Contexto: o que isso representa além do número
- Gratidão específica: mencione pessoas/times pelo nome
- Visão de futuro: o que isso abre de possibilidades
- Pergunta: convide reflexão sobre o tema maior

**Exemplo de abertura:** "Hoje assinamos o contrato de concessão da Fernão Dias, marcando o início da nossa operação."

### 2. Reflexão Pessoal (Camilla Junqueira, Lucas Vargas)
**Estrutura:**
- Gancho: momento de virada pessoal
- Contexto emocional: o que estava em jogo
- O aprendizado: o que mudou na visão de mundo
- Conexão com o profissional: como isso afeta o trabalho/liderança
- Pergunta: convida a audiência a refletir sobre o próprio percurso

**Sinal de qualidade:** vulnerabilidade real + âncora de crescimento. Nunca só lamento, nunca só vitória.

### 3. Opinião sobre Tendência (Leandro Herrera, Cesario Nakamura)
**Estrutura:**
- Gancho: dado ou observação contraintuitiva
- O que os dados mostram: evidência concreta
- Sua perspectiva: o que você acha disso
- O que isso significa para o leitor
- Pergunta: o que eles estão fazendo a respeito

### 4. Provocação + Dado (André Wendler)
**Estrutura:**
- Gancho: afirmação polêmica ou errada propositalmente
- Desenvolvimento: "mas deixa eu te mostrar os dados..."
- Virada: a conclusão surpreendente
- Lição prática
- CTA leve (opcional): "me manda mensagem se quiser conversar"

**Nota:** este estilo é mais agressivo comercialmente — use quando o usuário tiver produto/serviço a posicionar.

### 5. Lista de Lições (Camilla Junqueira, Cesario Nakamura)
**Estrutura:**
- Gancho: o contexto que gerou as lições (projeto, marco, aniversário)
- Lista com marcadores: 5 a 8 lições curtas, cada uma com 1-2 frases de explicação
- Fechamento: síntese pessoal
- Pergunta

**Sinal de qualidade:** cada lição deve ser específica o suficiente para parecer vivida, não genérica.

### 6. Bastidores/Processo (Leandro Herrera, João Kepler)
**Estrutura:**
- Gancho: revelar algo que "ninguém vê"
- O processo: passo a passo do que foi feito
- O resultado: o que aconteceu
- A lição: o que pode ser replicado
- Pergunta ou CTA

---

## Checklist de Revisão

Antes de entregar o post, verifique:

- [ ] A primeira linha funciona sozinha, sem contexto?
- [ ] Tem pelo menos 1 dado concreto (número, data, nome)?
- [ ] Os parágrafos têm máx. 4 linhas?
- [ ] Termina com pergunta genuína?
- [ ] Tem 3-6 hashtags ao final?
- [ ] Está em primeira pessoa?
- [ ] Evitou linguagem corporativa genérica?
- [ ] O comprimento está entre 150 e 600 palavras?
- [ ] Os emojis (se usados) são como marcadores, não decoração?

---

## Coleta de Contexto do Usuário

Antes de escrever, sempre pergunte (se não souber):

1. **Quem você é?** (cargo, empresa, setor) — para calibrar o tom e autoridade
2. **Qual é o ângulo pessoal?** — você viveu isso? É uma opinião? É um resultado da empresa?
3. **Quem é sua audiência no LinkedIn?** — colegas de setor, clientes, candidatos a emprego?
4. **Tom preferido?** — mais analítico/dados ou mais emocional/narrativo?

Se o usuário não informar nada, escreva com tom neutro de liderança sênior e peça confirmação antes de finalizar.

---

## Exemplos de Ganchos por Setor

Para o contexto de **construção civil e gestão de projetos**:

- "Mais de 80% dos projetos de construção no Brasil estouram o orçamento. Passei anos entendendo por quê."
- "Quando assumi o controle de custo daquele projeto, o desvio era de 34%. O que fiz nos primeiros 30 dias mudou tudo."
- "Aprendi com obras o que nenhuma faculdade me ensinou sobre gestão financeira."
- "Você controla o custo do seu projeto — ou só descobre o problema quando já é tarde demais?"
- "Cada real desperdiçado numa obra tem um nome. Aprendi a dar esse nome."

---

## Notas Finais

- **Nunca invente dados** que o usuário não confirmou
- Sempre ofereça **2 versões** quando o tema permitir: uma mais emocional/narrativa e uma mais analítica/dados
- Se o usuário enviar um link, **leia o conteúdo completo** antes de escrever
- Posts em **português brasileiro**, com naturalidade coloquial mas sem gírias excessivas
- Respeite a voz do usuário: se ele fornece rascunho, preserve o estilo e melhore a estrutura
