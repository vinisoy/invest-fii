# 📊 Planilha de Simulação de Investimentos em FIIs

Este projeto é uma planilha em Excel desenvolvida para **simular investimentos mensais** com foco em Fundos Imobiliários (FIIs). O objetivo é auxiliar usuários a organizarem suas finanças pessoais, visualizarem o crescimento do patrimônio ao longo do tempo e entenderem como alocar seus recursos de forma estratégica, de acordo com seu perfil de investidor.

---

## ⚙️ Funcionalidades

- 💰 **Cálculo de Patrimônio Futuro** com base em:
  - Aporte mensal
  - Taxa de rendimento estimada
  - Período de investimento (em anos)

- 📈 **Simulação de Dividendos Mensais**
- 🧠 **Sugestão de Investimento Personalizada** (com base em percentual da renda)
- 🧮 **Perfis de Investidor** (Conservador, Moderado, Agressivo) com alocação entre:
  - FIIs de Papel
  - FIIs de Tijolo
  - FIIs Híbridos
  - Fundos de Fundos (FOFs)

---

## 🗂 Estrutura do Projeto

### `APP`
Planilha principal para simulação de investimento. Permite inserir dados como:
- Salário
- Percentual destinado ao investimento
- Aporte mensal
- Anos de investimento
- Rendimento mensal estimado

Também exibe os resultados:
- Patrimônio acumulado ao fim do período
- Estimativa de dividendos mensais

### `Planilha2`
Tabela de referência com alocação percentual recomendada de FIIs para cada tipo de investidor (baseado em perfil de risco). 

---

## 🚀 Como Usar

1. Baixe o arquivo `Invest.xlsx`.
2. Abra a aba `APP`.
3. Insira suas informações nos campos:
   - Salário
   - Quanto investir por mês
   - Quantos anos pretende investir
   - Taxa de rendimento mensal estimada
4. A planilha irá calcular automaticamente:
   - O patrimônio acumulado ao fim do período
   - Os dividendos mensais aproximados

---

## ✅ Melhorias Futuras

- Adição de gráficos de evolução do patrimônio
- Integração com dados reais de FIIs via API (ex: Status Invest, Funds Explorer)
- Interface com validação automática de perfis
- Simulação com aportes crescentes e reinvestimento de dividendos

