# 📊 Fluxo de Caixa Empresarial em Excel

Planilha de **fluxo de caixa e resultado mensal** com dois regimes (caixa e competência), plano de contas em dois níveis, controle de contas a pagar e a receber e um **dashboard financeiro anual**.

> **Aviso:** projeto desenvolvido para estudo, a partir do projeto final do curso *Excel Completo do Básico ao Avançado* (Udemy). Todos os dados são **fictícios**.

![Dashboard financeiro 2018](imagens/dashboard-2018.png)

![Dashboard financeiro 2019](imagens/dashboard-2019.png)

---

## 🎯 Objetivo

Organizar entradas e saídas de caixa de uma empresa de comércio de mercadorias e responder perguntas como:

- Quanto entrou e saiu de caixa em cada mês?
- Qual a diferença entre o **caixa realizado** e o resultado por **competência**?
- Quanto há **a pagar** e **a receber** em aberto?
- Como estão as vendas: à vista ou a prazo?
- Quais contas pesam mais nas despesas e na evolução das vendas?

## 📁 Estrutura da planilha

| Aba | O que contém |
|---|---|
| **Início** | Menu de navegação com botões para todas as abas |
| **PCEntradas N1/N2** e **PCSaídas N1/N2** | Plano de contas de entradas e de saídas (níveis 1 e 2) |
| **RegistroEntradas** e **RegistroSaídas** | Lançamentos com data do caixa realizado, da competência e do caixa previsto, conta, histórico (NF) e valor |
| **FluxoCaixaConsolidado** | Fluxo de caixa (realizado) e de competência por mês, com saldo inicial/final e resultado mensal (lucro, prejuízo e acumulado) |
| **DetalhaReceita** e **DetalhaDespesa** | Receitas e despesas detalhadas por conta e por mês |
| **ContasPagar** e **ContasReceber** | Valores em aberto por conta e por mês previsto |
| **DashBoardFinanceiroAnual** | Painel anual com indicadores e gráficos, com filtro de ano |

Os dados cobrem de **ago/2017 a jun/2019**, com cerca de **460 lançamentos** (231 entradas e 229 saídas).

## 🛠️ Recursos do Excel utilizados

- **Tabelas estruturadas** (`TbRegistroEntradas`, `TbRegistroSaídas`) com referências estruturadas nas fórmulas
- Fórmulas **`SUMIFS`**, **`COUNTIFS`**, **`IF`** e **`AND`**
- **Validação de dados** com listas suspensas ligadas ao plano de contas
- **Tabelas dinâmicas** e **segmentações de dados**
- **Gráficos** (linha, colunas, rosca) e **minigráficos**
- Painel (dashboard) com indicadores e seletor de ano
- Navegação por botões entre as abas

## 📸 Telas

### Início
![Tela inicial](imagens/inicio.png)

### Registro das entradas de caixa
![Registro de entradas](imagens/registro-entradas.png)

### Fluxo de caixa e resultado mensal (2018)
![Fluxo consolidado](imagens/fluxo-consolidado.png)

## 🔎 O que os dados mostram

**2018**
- Entradas de **R$ 320.574** contra saídas de **R$ 302.150**, com resultado acumulado de **R$ 18.424**
- Saldo de caixa de **R$ 55.108** ao fim do ano
- **68% das vendas foram a prazo** e 32% à vista
- Em aberto: R$ 31.482 a receber e R$ 46.816 a pagar

**2019 (jan–jun)**
- Entradas de **R$ 130.659** e saídas de **R$ 169.790** por competência: resultado de **−R$ 39.131**
- No caixa, as saídas (R$ 163.337) superaram as entradas (R$ 129.286), e o saldo caiu de **R$ 55.108 para R$ 21.057**

Ou seja: a empresa fechou 2018 no azul, mas o primeiro semestre de 2019 consumiu caixa.

## ▶️ Como usar

1. Baixe o arquivo `projeto-fluxo-de-caixa.xlsx` e abra no **Microsoft Excel** (as segmentações e os minigráficos exigem Excel desktop).
2. Use os botões da aba **Início** para navegar.
3. No **dashboard**, escolha o ano no seletor e use os filtros de conta.
4. Para registrar novos lançamentos, inclua linhas nas tabelas de **RegistroEntradas** ou **RegistroSaídas**, escolhendo as contas nas listas suspensas.

## ⚠️ Limitações

- Dados fictícios, de ago/2017 a jun/2019: os meses de jul a dez/2019 aparecem zerados.
- Projeto feito em Excel; as tabelas dinâmicas precisam ser atualizadas (**Dados > Atualizar tudo**) após novos lançamentos.

## 👤 Autor

**David Lucas dos Santos**
Estudante de Análise e Desenvolvimento de Sistemas (USCS) · Técnico em Automação Industrial

[LinkedIn](https://www.linkedin.com/in/SEU-PERFIL) · [GitHub](https://github.com/SEU-USUARIO)
