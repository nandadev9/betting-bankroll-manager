# Betting Bankroll Manager

Intelligent bankroll management system for sports betting with automatic suggestions based on risk levels.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)

## 🎯 Características

- ✅ **100% Offline** - Funciona direto no navegador, sem necessidade de servidor
- 🎲 **3 Níveis de Risco** - Baixo, Médio e Alto com estratégias personalizadas
- 📊 **Sugestões Automáticas** - Cálculo automático de valor e faixa de odds
- 📅 **Organização por Dia** - Cada dia é uma aba separada
- 💾 **Salvamento Automático** - Dados salvos no navegador (localStorage)
- 📈 **Estatísticas em Tempo Real** - Taxa de acerto, lucro/prejuízo, etc.
- 📥 **Exportação de Dados** - Exporte seus dados em JSON
- 📱 **Responsivo** - Funciona em desktop e mobile

## 📖 Guia de Uso

### 1️⃣ Configuração Inicial

1. **Defina sua banca inicial** - Digite o valor em reais
2. **Escolha seu nível de risco**:
   - 🛡️ **Baixo**: 2-3% por aposta | Odds 1.50-2.00
   - ⚖️ **Médio**: 3-5% por aposta | Odds 1.70-2.50
   - 🚀 **Alto**: 5-8% por aposta | Odds 2.00-3.50
3. Clique em **"Atualizar Configuração"**

### 2️⃣ Adicionar Apostas

1. A sugestão de valor aparecerá automaticamente
2. Preencha:
   - **Descrição** (ex: "Flamengo vs Palmeiras")
   - **Odd** (dentro da faixa recomendada)
   - **Valor** (use a sugestão ou personalize)
3. Clique em **"Adicionar Aposta"**

### 3️⃣ Registrar Resultados

- ✅ **Ganhou**: Clique no botão verde
- ❌ **Perdeu**: Clique no botão vermelho
- A banca será atualizada automaticamente!

### 4️⃣ Atualizar Banca

- Ao final do dia, ajuste o valor da banca se necessário
- O sistema manterá o histórico completo

## 🎲 Estratégias por Nível de Risco

| Nível | Stake | Odds | Descrição |
|-------|-------|------|-----------|
| 🛡️ Baixo | 2-3% | 1.50-2.00 | Para iniciantes. Crescimento lento e seguro |
| ⚖️ Médio | 3-5% | 1.70-2.50 | Equilibrado. Bom risco vs recompensa |
| 🚀 Alto | 5-8% | 2.00-3.50 | Agressivo. Maior risco, maior retorno |

## 📊 Estatísticas Disponíveis

- 💰 **Banca Atual** - Valor atual da sua banca
- 📊 **Lucro/Prejuízo** - Diferença em relação à banca inicial
- 📈 **Taxa de Acerto** - Percentual de apostas vencidas
- 📅 **Total de Apostas** - Quantidade total registrada
- ✅ **Vitórias** - Número de apostas ganhas
- ❌ **Derrotas** - Número de apostas perdidas

## 💡 Dicas de Uso

### ✅ Faça

- Siga as sugestões do sistema
- Respeite a faixa de odds recomendada
- Atualize a banca diariamente
- Mantenha disciplina na gestão
- Exporte seus dados regularmente

### ❌ Não Faça

- Não ignore os limites do sistema
- Não tente recuperar perdas aumentando stakes
- Não aposte mais que o sugerido
- Não ignore odds fora da faixa
- Nunca aposte dinheiro que não pode perder

## 🔧 Funcionalidades Técnicas

### Dados Salvos Automaticamente

O sistema usa `localStorage` do navegador para salvar:
- Configuração da banca
- Histórico de apostas por dia
- Resultados de cada entrada

### Exportação de Dados

Clique em "📥 Exportar Dados" para baixar um arquivo JSON com todo seu histórico.

### Limpar Dados

Botão "🗑️ Limpar Tudo" remove todos os dados (use com cuidado!).


## 🛠️ Tecnologias

- HTML5
- CSS3 (com gradientes e animações)
- JavaScript Vanilla (sem frameworks)
- LocalStorage API

## ⚠️ Avisos Importantes

## 📄 Licença

MIT License - Sinta-se livre para usar, modificar e distribuir.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:
- Reportar bugs
- Sugerir novas funcionalidades
- Melhorar o código
- Compartilhar feedbacks

