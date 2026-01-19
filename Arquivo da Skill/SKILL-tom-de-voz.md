---
name: skill-tom-de-voz
description: Analyze and compare tone of voice between Figma content and iFood Brasil Instagram comments. Use when UX Writers, Content Designers, or Product Designers need to validate if their Figma content aligns with the tone of voice used by iFood's target audience in Instagram comments. Triggered when user provides a Figma link and requests tone of voice analysis or comparison with Instagram engagement.
---

## Público-Alvo

Este skill é projetado para UX Writers, Content Designers e Product Designers do iFood que precisam validar o alinhamento do tom de voz do conteúdo criado com a linguagem do público-alvo.

## Contexto de Uso

Cenário típico: Um UX Writer constrói conteúdo para um fluxo (ex: checkout) no aplicativo do iFood e precisa comparar o tom de voz utilizado com o tom de voz dos comentários dos últimos 10 posts do perfil do Instagram da iFood Brasil, garantindo que está "falando a mesma língua" do público-alvo.

## Como o Usuário Prepara o Link do Figma

Para compartilhar o conteúdo específico do Figma:
1. Selecionar a tela ou área desejada no Figma
2. Clicar com botão direito do mouse
3. Escolher 'Copy/Paste as' → 'Copy link to selection'
4. Colar o link no chat

## Formato do documento

Para esse relatório utilize o formato de documento MD e não DOCX

## Processo de Análise

Execute as seguintes etapas em ordem:

### 1. Receber e Acessar o Conteúdo do Figma
- Receber o link do Figma fornecido pelo usuário
- Acessar e analisar o conteúdo textual presente no link
- Identificar todos os elementos de texto, microcopy, mensagens e conteúdo relevante

### 2. Analisar os Comentários do Instagram
- Acessar o perfil do Instagram da iFood Brasil (@ifoodbrasil)
- Usar a extensão do Apify, instalada no Claude, para realizar o processo de web scraping e ter acesso aos comentários dos últimos 10 posts publicados no perfil @ifoodbrasil, no Instagram
- Analisar os comentários dos 10 últimos posts publicados
- Identificar padrões de linguagem, expressões, tom emocional e vocabulário utilizado pelos seguidores

### 3. Comparar os Tons de Voz
Avaliar a compatibilidade entre:
- Tom de voz do conteúdo do Figma
- Tom de voz dos comentários dos seguidores no Instagram

Aspectos a considerar:
- Formalidade vs. informalidade
- Uso de gírias e expressões coloquiais
- Nível de proximidade e pessoalidade
- Tom emocional (humor, seriedade, empatia, etc.)
- Vocabulário característico

### 4. Fornecer Feedback Detalhado

O feedback deve incluir:

**Compatibilidade do Tom de Voz:**
- Avaliar o nível de alinhamento entre o conteúdo do Figma e os comentários do Instagram
- Identificar pontos fortes onde o tom está bem alinhado
- Apontar divergências e desalinhamentos

**Conexão com Problemas e Reivindicações:**
- Avaliar se o conteúdo do Figma aborda ou pode abordar melhor os problemas, questões e reivindicações mencionados pelos seguidores nos comentários
- Identificar oportunidades de conexão com as preocupações reais do público

**Sugestões de Ajustes e Melhorias:**
- Propor melhorias específicas no texto do Figma para maior alinhamento
- Sugerir reformulações, substituições de palavras ou ajustes de tom
- Apresentar exemplos concretos de como o texto poderia ser ajustado
- Justificar cada sugestão com base nos padrões identificados nos comentários do Instagram

## Formato de Entrega

Estruture a análise de forma clara e acionável:
1. Resumo da compatibilidade (percentual ou qualitativo)
2. Pontos de alinhamento identificados
3. Gaps e oportunidades de melhoria
4. Sugestões de ajustes com exemplos antes/depois
5. Considerações sobre conexão com questões dos seguidores

## Observações Importantes

- Mantenha o foco na linguagem autêntica dos seguidores, não na linguagem oficial da marca
- Considere variações regionais e culturais do português brasileiro
- Seja específico nas sugestões, fornecendo exemplos práticos
- Priorize ajustes que aproximem o conteúdo da forma como o público realmente se comunica
