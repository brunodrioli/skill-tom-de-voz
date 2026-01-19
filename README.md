# Skill Tom de Voz (exemplo: iFood 🗣️)

Skill para validação de tom de voz entre conteúdos do Figma e a linguagem autêntica do público-alvo da iFood no Instagram.

---

## 📋 O Problema

UX Writers e Content Designers frequentemente criam conteúdos para aplicativos e interfaces sem ter uma forma objetiva de validar se estão realmente "falando a mesma língua" do público-alvo. Existe um gap entre:

- **O que escrevemos**: Textos criados com base em guidelines e boas práticas de UX Writing
- **Como o público fala**: A linguagem real, autêntica e espontânea usada pelos usuários nas redes sociais

Esse desalinhamento pode resultar em:
- Conteúdos que soam artificiais ou corporativos demais
- Perda de conexão emocional com os usuários
- Menor engajamento e conversão
- Oportunidades perdidas de abordar problemas reais do público

---

## ✨ A Solução

Esta skill automatiza a análise comparativa entre o tom de voz do seu conteúdo no Figma e a linguagem real dos seguidores da iFood Brasil no Instagram. 

**Como funciona:**
1. Você cola o link de uma tela ou seleção do Figma
2. A skill acessa e analisa o conteúdo textual
3. Busca e analisa os comentários dos 10 últimos posts do @ifoodbrasil
4. Compara os tons de voz identificando padrões linguísticos
5. Fornece feedback detalhado com sugestões de melhoria

---

## 🎯 O Propósito

Criar uma ponte entre o design de conteúdo e a voz autêntica do usuário, permitindo que profissionais de UX e design:

- **Validem objetivamente** se o tom de voz está alinhado com o público
- **Identifiquem gaps** entre a linguagem planejada e a linguagem real
- **Recebam sugestões práticas** de como ajustar textos para maior proximidade
- **Conectem conteúdo com problemas reais** mencionados pelos usuários
- **Tomem decisões baseadas em dados** sobre linguagem e tom de voz

---

## 🎁 O que você ganha com isso

### Para UX Writers e Content Designers:
- ✅ Validação rápida de tom de voz (minutos vs. horas de pesquisa manual)
- ✅ Feedback objetivo baseado em dados reais de usuários
- ✅ Sugestões concretas de melhorias com exemplos antes/depois
- ✅ Maior confiança nas decisões de conteúdo
- ✅ Redução de retrabalho por desalinhamento de tom

### Para Product Designers:
- ✅ Compreensão mais profunda da linguagem do público
- ✅ Alinhamento entre design visual e verbal
- ✅ Insights sobre preocupações reais dos usuários

### Para o Produto:
- ✅ Conteúdos mais próximos e empáticos
- ✅ Maior engajamento e conversão
- ✅ Redução de fricção na experiência do usuário
- ✅ Construção de relacionamento mais autêntico com o público

---

## 💡 Casos de uso

### 1. Fluxo de checkout
**Cenário:** Você criou o microcopy para o fluxo de checkout do app iFood.

**Uso da skill:** 
- Copie o link da tela do Figma
- Peça análise do tom de voz
- Receba feedback sobre se a linguagem está próxima de como os usuários realmente falam
- Ajuste termos técnicos ou formais para expressões mais naturais

### 2. Mensagens de erro
**Cenário:** Desenvolvendo mensagens de erro e feedback do sistema.

**Uso da skill:**
- Analise se o tom empático está alinhado com a forma como usuários expressam frustração
- Identifique oportunidades de usar humor ou leveza (se identificado nos comentários)
- Valide se o vocabulário é compreensível

### 3. Onboarding de novos usuários
**Cenário:** Criando o fluxo de boas-vindas para novos usuários.

**Uso da skill:**
- Verifique se o nível de formalidade está adequado
- Identifique gírias ou expressões que podem criar proximidade
- Ajuste o tom para ser acolhedor da forma que o público aprecia

### 4. Comunicações promocionais
**Cenário:** Desenvolvendo banners e CTAs para campanhas.

**Uso da skill:**
- Analise se a urgência e entusiasmo estão calibrados
- Identifique padrões de linguagem que geram engajamento
- Ajuste o tom persuasivo sem soar invasivo

### 5. FAQ e Central de Ajuda
**Cenário:** Escrevendo respostas para dúvidas frequentes.

**Uso da skill:**
- Compare com dúvidas reais dos comentários
- Ajuste o nível de explicação (técnico vs. coloquial)
- Identifique problemas não abordados que deveriam estar no FAQ

---

## 📥 Instalação

### Pré-requisitos
- Conta ativa no Claude.ai
- Acesso ao Figma (visualização ou edição)
- Acesso ao perfil do Instagram @ifoodbrasil (público)

### Passo a Passo

1. **Baixe o arquivo da skill**
   ```bash
   # Clone o repositório
   git clone https://github.com/seu-usuario/skill-tom-de-voz.git
   
   # Ou baixe diretamente o arquivo .skill
   ```

2. **Acesse o Claude.ai**
   - Faça login em [claude.ai](https://claude.ai)
   - Navegue até Configurações (Settings)

3. **Adicione a Skill**
   - Vá para a seção "Skills" ou "Ferramentas"
   - Clique em "Upload Skill" ou "Adicionar Skill"
   - Selecione o arquivo `skill-tom-de-voz.skill`
   - Aguarde confirmação de instalação

4. **Ative a Skill**
   - Certifique-se de que a skill está ativa/habilitada
   - A skill aparecerá na lista de skills disponíveis

5. **Teste a instalação**
   - Abra uma nova conversa
   - Cole um link do Figma e peça análise de tom de voz
   - A skill deve ser acionada automaticamente

---

## 🎨 Integração com o Figma

### Como obter o link correto do Figma

A skill funciona melhor quando você compartilha links específicos de seleções, não do arquivo inteiro.

**Método recomendado:**

1. **Abra seu arquivo no Figma**
   - Navegue até o projeto com o conteúdo a ser analisado

2. **Selecione o conteúdo específico**
   - Clique na tela, frame ou componente desejado
   - Para múltiplos elementos, use Shift + clique
   - Para análise de fluxo completo, selecione todas as telas relevantes

3. **Copie o link da seleção**
   - Clique com botão direito na seleção
   - Escolha **"Copy/Paste as"** 
   - Selecione **"Copy link to selection"**
   - O link será copiado para sua área de transferência

4. **Cole no Claude**
   - Abra uma conversa no Claude
   - Cole o link
   - Adicione sua solicitação (ex: "Analise o tom de voz deste conteúdo")

**Exemplo de link do Figma:**
```
https://www.figma.com/file/ABC123/Projeto?node-id=123:456&t=xyz789
```

### Dicas para melhor análise

- ✅ **Selecione apenas conteúdo textual relevante** (evite incluir toda a página se só quer analisar um componente)
- ✅ **Agrupe telas relacionadas** ao mesmo fluxo para análise de consistência
- ✅ **Inclua contexto** na sua mensagem (ex: "Este é o fluxo de checkout", "Estes são erros de validação")
- ❌ **Evite links de arquivos completos** - dificulta a identificação do conteúdo específico
- ❌ **Não inclua protótipos apenas visuais** sem texto para análise

---

## 🎓 O que você aprenderá

Usando esta skill regularmente, você desenvolverá:

### Habilidades analíticas
- **Identificação de padrões linguísticos** em diferentes contextos sociais
- **Percepção de nuances** entre tom formal e informal
- **Sensibilidade cultural** para variações regionais do português brasileiro
- **Análise de sentimento** em feedback de usuários

### Competências de UX Writing
- **Calibração de tom de voz** para diferentes momentos da jornada
- **Uso estratégico de vocabulário** próximo ao público
- **Equilíbrio entre clareza e autenticidade**
- **Empatia baseada em dados** reais de usuários

### Visão estratégica
- **Conexão entre conteúdo e problemas reais** dos usuários
- **Priorização de ajustes** com maior impacto
- **Validação objetiva** de decisões de design
- **Alinhamento entre marca e audiência**

### Processo de trabalho
- **Iteração mais rápida** em conteúdos
- **Documentação de decisões** baseadas em análise
- **Colaboração mais efetiva** com dados concretos
- **Redução de viés pessoal** em escolhas de linguagem

---

## 🙏 Créditos

Esta skill foi desenvolvida para facilitar o trabalho de profissionais de UX Writing e Content Design, especialmente aqueles que trabalham com produtos digitais onde a autenticidade da linguagem é fundamental para o sucesso.

**Desenvolvido por:** Bruno Drioli Rodrigues

**Inspiração:** A necessidade constante de validar se estamos realmente falando a língua do nosso público, não apenas seguindo manuais de estilo.

---

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).

Você é livre para:
- ✅ Usar comercialmente
- ✅ Modificar e adaptar para seu contexto
- ✅ Distribuir
- ✅ Usar em projetos privados

**Condições:**
- Mantenha o aviso de copyright e licença
- A licença e copyright devem ser incluídos em todas as cópias

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Se você tem ideias para melhorar esta skill:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaNovaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/MinhaNovaFeature`)
5. Abra um Pull Request

### Ideias para contribuições
- Suporte para outras marcas/perfis do Instagram
- Análise de múltiplas fontes (Twitter, TikTok, etc.)
- Exportação de relatórios em diferentes formatos
- Métricas quantitativas de alinhamento
- Integração com outras ferramentas de design

---

## 📞 Suporte

Encontrou algum problema ou tem dúvidas?

- 🐛 [Abra uma issue](https://github.com/seu-usuario/skill-tom-de-voz/issues)
- 💬 [Inicie uma discussão](https://github.com/seu-usuario/skill-tom-de-voz/discussions)
- 📧 Entre em contato: bruno.drioli@gmail.com

---

## 🗺️ Roadmap

Funcionalidades planejadas para futuras versões:

- [ ] Análise comparativa com múltiplos perfis sociais
- [ ] Histórico de análises e evolução do tom de voz
- [ ] Exportação de relatórios em PDF
- [ ] Sugestões de glossário personalizado
- [ ] Integração com Notion para documentação
- [ ] Dashboard com métricas de alinhamento ao longo do tempo
- [ ] Suporte multilíngue

---

## ⭐ Mostre seu apoio

Se esta skill foi útil para você, considere:
- ⭐ Dar uma estrela no repositório
- 🐦 Compartilhar nas redes sociais
- 📝 Escrever sobre sua experiência
- 🤝 Contribuir com melhorias

---
