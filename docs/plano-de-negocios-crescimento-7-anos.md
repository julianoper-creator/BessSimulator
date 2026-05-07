# Plano de Negócios — Crescimento e Venda da Empresa
## Modelo BOT (Build-Operate-Transfer) — Ativos de Energia
### Horizonte: 7 Anos | Meta: R$ 3M → R$ 267M ARR | Valuation de Saída: **R$ 1 BILHÃO**

---

## 1. PREMISSAS DO MODELO

| Premissa | Valor | Observação |
|---------|-------|----------|
| Ticket médio por projeto | **R$ 6.200.000** | Equipamentos importados (mercado livre) |
| Geração mensal do ativo | **299 MWh/mês** | ~2,2 MWp solar equivalente |
| Tarifa base do cliente | **R$ 409,00/MWh** | Tarifa atual paga à distribuidora |
| Desconto ofertado ao cliente | **10%** | Argumento comercial do BOT |
| Margem EPC da empresa | **15%** | Sobre o ticket do projeto |
| Custo de capital de referência | **CDI + 3% = 16,25% a.a.** | Banco privado — BNDES excluído¹ |
| Participação da empresa no projeto | **10% do EBITDA** | Após dedução de O&M |
| **Prazo dos contratos BOT** | **15 anos** | Mínimo para IRR investidor > CDI+3% |
| **Estrutura de captação** | **3 tranches** | Senior 75% / Mezanino 15% / Equity 10% |
| **Curva de maturidade O&M** | **3 anos** | Meses 1–36 inicial → Mês 37 IA plena |
| Taxa de saída ao final do contrato | **R$ 800.000** | Custo operacional de retirada + reinstalação |
| Monitoramento | **Plataforma IA própria** | Deploy Ano 2 — rollout completo Ano 3 |
| **Indexação da tarifa BOT** | **IPCA anual** | Tarifa reajustada todo aniversário do contrato |
| **Degradação BESS** | **2%/ano capacidade** | Padrão Li-ion; IPCA (+5%) mais que compensa |
| **Risco cambial** | **Hedge cambial no EPC** | USD/BRL travado no momento da importação |

> ¹ **Por que BNDES não é a rota principal**: exige fabricação nacional, elevando CAPEX em
> 20–30% para a mesma capacidade geradora. DSCR cai para 0,80–0,90× — inviável.
>
> **Modelo conservador**: toda projeção financeira usa tarifa nominal **flat** (sem IPCA).
> Com IPCA de 5%/ano e degradação de 2%/ano, o retorno dos investidores aumenta +24,9%
> sobre o modelo flat — isso é upside não capturado nas projeções base.

---

## 2. PRECIFICAÇÃO DO BOT E PROPOSTA DE VALOR

```
Valor mensal integral (sem desconto):
  299 MWh × R$ 409,00 = R$ 122.291/mês = R$ 1.467.492/ano
```

| Desconto | Tarifa BOT | Mensalidade BOT | Economia Mensal do Cliente |
|---------|-----------|----------------|---------------------------|
| 10% | R$ 368,10/MWh | R$ 110.062 | R$ 12.229 |
| 12,5% | R$ 357,88/MWh | R$ 107.007 | R$ 15.284 |
| 15% | R$ 347,65/MWh | R$ 103.997 | R$ 18.294 |

---

## 3. ESTRUTURA DE CUSTOS — EXPLÍCITA POR NÍVEL

### 3.1 Nível do Projeto — O&M (por projeto, por mês)

Deduzido da receita BOT **antes** do split. Custo do projeto — não da empresa nem do investidor.

| Item | Escala Inicial (1–36 meses) | Escala Madura com IA (mês 37+) | Variação |
|------|-----------------------------|--------------------------------|----------|
| Manutenção técnica de campo | R$ 6.500 | R$ 2.800 | IA preditiva reduz visitas reativas |
| Seguro patrimonial | R$ 2.200 | R$ 1.500 | Apólice coletiva |
| SCADA / Monitoramento IA | R$ 1.500 | **R$ 150** | Plataforma própria amortizada |
| Administração da SPE | R$ 1.000 | R$ 600 | Automação administrativa |
| Fundo de contingência | R$ 1.300 | **R$ 700** | Manutenção preditiva reduz surpresas |
| **Total O&M mensal** | **R$ 12.500** | **R$ 5.750** | **-54% a partir do mês 37** |

> **Degradação BESS e mitigação**: baterias Li-ion perdem ~2% de capacidade/ano.
> No contrato BOT, a tarifa é indexada ao IPCA (+5%/ano), gerando crescimento líquido
> de +2,9%/ano na receita real. Cláusula de garantia de capacidade: empresa garante
> mínimo de 90% da capacidade nominal; augmentação de baterias prevista no Ano 10
> se degradação acumulada superar 15%. Custo coberto pelo fundo de contingência (R$700/mês).

### 3.2 Nível da Empresa — Overhead (anual)

| Centro de Custo | Ano 1 | Ano 2 | Ano 3 | Ano 5 | Ano 7 |
|----------------|-------|-------|-------|-------|-------|
| Equipe — Engenharia e EPC | R$ 300k | R$ 600k | R$ 1,0M | R$ 3,5M | R$ 6,0M |
| Equipe — Gestão de Projetos | R$ 200k | R$ 400k | R$ 700k | R$ 2,0M | R$ 3,5M |
| Equipe — O&M Field | R$ 150k | R$ 400k | R$ 700k | R$ 2,5M | R$ 4,0M |
| Equipe — Comercial | R$ 180k | R$ 400k | R$ 700k | R$ 2,0M | R$ 3,5M |
| Equipe — Financeiro e Jurídico | R$ 120k | R$ 250k | R$ 500k | R$ 1,5M | R$ 2,5M |
| Equipe — TI e Plataforma IA | R$ 80k | R$ 280k | R$ 500k | R$ 1,4M | R$ 2,2M |
| Equipe — Liderança / Diretoria | R$ 400k | R$ 600k | R$ 900k | R$ 2,0M | R$ 3,5M |
| *Subtotal Salários + Encargos* | *R$ 2,15M* | *R$ 4,25M* | *R$ 7,25M* | *R$ 21,75M* | *R$ 37,5M* |
| Escritórios e infraestrutura | R$ 80k | R$ 150k | R$ 300k | R$ 1,0M | R$ 2,4M |
| TI — ERP, CRM, Plataforma IA | R$ 100k | R$ 350k | R$ 500k | R$ 1,2M | R$ 2,0M |
| Jurídico externo | R$ 120k | R$ 200k | R$ 300k | R$ 700k | R$ 1,0M |
| Marketing e comercial | R$ 80k | R$ 150k | R$ 250k | R$ 600k | R$ 1,0M |
| Viagens e despesas | R$ 50k | R$ 100k | R$ 200k | R$ 500k | R$ 800k |
| P&D e inovação | — | — | R$ 100k | R$ 500k | R$ 1,5M |
| Seguros e outros | R$ 50k | R$ 80k | R$ 150k | R$ 300k | R$ 500k |
| **Total Overhead Anual** | **R$ 2,6M** | **R$ 5,1M** | **R$ 8,7M** | **R$ 26,4M** | **R$ 42,7M** |
| **Headcount** | **8** | **18** | **35** | **95** | **170** |

---

## 4. P&L POR PROJETO — TODOS OS CUSTOS VISÍVEIS

### 4.1 Margem EPC

| Item | Valor |
|------|-------|
| Contrato EPC | R$ 6.200.000 |
| Custo direto de construção | -R$ 5.270.000 |
| **Margem EPC** | **R$ 930.000** (15%) |

> **Risco cambial EPC**: equipamentos importados em USD (~60% do custo direto).
> Mitigação: hedge cambial (NDF ou swap) travado na assinatura do contrato EPC.
> Exposição líquida limitada ao prazo de construção (3–4 meses).

### 4.2 Fase Operate — P&L Mensal

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  RECEITA BOT (cliente, desconto 10%)         R$ 110.062/mês
  [indexada ao IPCA anualmente — modelo flat é conservador]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  (-) O&M — custo do projeto (antes do split)
      Fase inicial — meses 1–36  (sem IA plena)  -R$  12.500/mês
      Fase madura  — mês 37–180  (IA plena)       -R$   5.750/mês
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  EBITDA PARA DISTRIBUIÇÃO
      Fase inicial                                R$  97.562/mês
      Fase madura com IA                          R$ 104.312/mês
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  EMPRESA 10%:
      Fase inicial   R$   9.756/mês
      Fase madura    R$  10.431/mês

  INVESTIDORES 90% — WATERFALL (3 tranches):
      🔵 Senior   (75%):  R$  65.875/mês  [17,0%/ano — fixo]
      🟡 Mezanino (15%):  R$  13.950/mês  [18,0%/ano — fixo]
      🔴 Equity   (10%):  R$   7.981/mês  [meses 1–36]
                          R$  14.056/mês  [mês 37+, maduro c/ IA]
      Total investidores (fase inicial):          R$  87.806/mês
      Total investidores (fase madura c/ IA):     R$  93.881/mês
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## 5. COMPARATIVO 10 ANOS vs 15 ANOS — TRÊS PERSPECTIVAS

```
╔══════════════════════════════════════════════════════════════════════════╗
║        COMPARATIVO BOT — 10 ANOS vs 15 ANOS (com IA de monitoramento)  ║
╚══════════════════════════════════════════════════════════════════════════╝

━━━ INVESTIDORES | Capital total: R$ 6.200.000 | 3 tranches | Maturidade 3 anos ━━━

                              10 ANOS           15 ANOS
  Total mensal (maduro)       R$ 93.881         R$ 93.881   (igual)
  Blended yield               18,17%            18,17%      (igual)
  🔵 Senior yield             17,0% (fixo)      17,0% (fixo)
  🟡 Mezanino yield           18,0% (fixo)      18,0% (fixo)
  🔴 Equity IRR               —                 ~22,6%  ✓
  Recupera capital em         Mês 69            Mês 69
  Total recebido (blended)    R$ 11.141.136     R$ 16.679.760
  Múltiplo blended            1,80×             2,69×
  IRR blended                 ~14,5%  ✗         ~17,0%  ✓
  vs CDI+3% (16,25%)          -1,75 p.p.  ✗    +0,75 p.p.  ✓

━━━ CLIENTE | Mensalidade: R$ 110.062/mês ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

                              10 ANOS           15 ANOS
  Total pago no contrato      R$ 13.207.440     R$ 19.811.160
  Taxa de saída               R$    800.000     R$    800.000
  Tarifa mercado equivalente  R$ 18.439.000     R$ 31.671.000
  Economia líquida            R$  4.431.560     R$ 11.059.840

━━━ EMPRESA | Por projeto — Ciclo 1 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

                              10 ANOS           15 ANOS
  EPC margin (upfront)        R$   930.000      R$   930.000
  Fee 10% acumulado           R$ 1.236.720      R$ 1.853.280
  Total ciclo 1               R$ 2.166.720      R$ 2.783.280
  WALE médio na saída (Ano 7)  ~7 anos           ~12 anos
  Valuation saída estimado     ~R$ 2,05B         ~R$ 2,46B

┌──────────────────────────────────────────────────────────────────────────┐
│  VEREDITO                                                                │
│  Investidor:  IRR blended 17,0% > CDI+3% com contrato 15 anos  ✓       │
│  Cliente:     economiza R$11M + tarifa indexada ao IPCA                 │
│  Empresa:     O&M -54% a partir mês 37 + Motor Transfer a partir Ano 3  │
└──────────────────────────────────────────────────────────────────────────┘
```

---

## 6. ESTRUTURA DE CAPTAÇÃO — 3 TRANCHES

### 6.1 Visão Geral por Tranche

| Tranche | Capital | % | Mensal (maduro) | Yield | Tipo |
|---------|---------|---|-----------------|-------|------|
| 🔵 **Senior** | R$ 4.650.000 | 75% | R$ 65.875 | **17,0%/ano** | Fixo |
| 🟡 **Mezanino** | R$ 930.000 | 15% | R$ 13.950 | **18,0%/ano** | Fixo |
| 🔴 **Equity** | R$ 620.000 | 10% | R$ 7.981 → R$ 14.056 | **15,4% → 27,2%** | Residual |
| **Total** | **R$ 6.200.000** | **100%** | **R$ 93.881** | **18,17% blended** | |

### 6.2 Waterfall — Ordem de Pagamento

```
  EBITDA maduro c/ IA (mês 37+):  R$ 104.312/mês
  ─────────────────────────────────────────────────────────────────────
  → 🏢 EMPRESA (10%):    R$  10.431/mês  (sai primeiro, fixo)
  → Investidores (90%):  R$  93.881/mês  (distribuídos em waterfall)
  ─────────────────────────────────────────────────────────────────────

  ┌──────────────────────────────────────────────────────────────────┐
  │  🔵 SENIOR — R$ 65.875/mês (17% fixo) — DSCR 1,33×            │
  └────────────────────────┬─────────────────────────────────────────┘
                           │ sobra R$ 28.006
                           ▼
  ┌──────────────────────────────────────────────────────────────────┐
  │  🟡 MEZANINO — R$ 13.950/mês (18% fixo) — DSCR 1,10×          │
  └────────────────────────┬─────────────────────────────────────────┘
                           │ sobra R$ 14.056 (maduro) / R$ 7.981 (inicial)
                           ▼
  ┌──────────────────────────────────────────────────────────────────┐
  │  🔴 EQUITY — RESIDUAL (captura toda eficiência da IA)           │
  │  Meses 1–36:  R$  7.981/mês  (15,4%/ano)                       │
  │  Mês 37–180:  R$ 14.056/mês  (27,2%/ano)                       │
  └──────────────────────────────────────────────────────────────────┘
```

### 6.3 Retorno por Tranche — 15 Anos

#### 🔵 Senior | 🟡 Mezanino | 🔴 Equity

| Métrica | 🔵 Senior | 🟡 Mezanino | 🔴 Equity |
|---------|----------|------------|----------|
| Capital | R$ 4.650.000 | R$ 930.000 | R$ 620.000 |
| Meses 1–36 | R$ 65.875/mês | R$ 13.950/mês | R$ 7.981/mês |
| Meses 37–180 | R$ 65.875/mês | R$ 13.950/mês | R$ 14.056/mês |
| Total 15 anos | R$ 11.857.500 | R$ 2.511.000 | R$ 2.311.380 |
| Múltiplo | 2,55× | 2,70× | 3,73× |
| Yield (fixo/médio) | 17,0%/ano | 18,0%/ano | 24,9%/ano |
| IRR 15 anos | ~16,8% ✓ | ~17,8% ✓ | **22,6% ✓** |

### 6.4 Rentabilidade Mensal — Resumo

| Tranche | Capital | Mensal (R$) | % ao mês | % ao ano |
|---------|---------|------------|---------|---------|
| 🔵 Senior | R$ 4.650.000 | R$ 65.875 | 1,417% | 17,0% |
| 🟡 Mezanino | R$ 930.000 | R$ 13.950 | 1,500% | 18,0% |
| 🔴 Equity (meses 1–36) | R$ 620.000 | R$ 7.981 | 1,287% | 15,4% |
| 🔴 Equity (mês 37–180) | R$ 620.000 | R$ 14.056 | 2,267% | 27,2% |
| 🔴 **Equity (média contrato)** | R$ 620.000 | **R$ 12.841** | **1,490%** | **24,9%** |

### 6.5 Upside com Indexação IPCA

```
  Modelo base (conservador): tarifa flat nominal → investidor recebe R$ 16.679.760
  Com IPCA 5%/ano + degradação 2%/ano (líquido +2,9%/ano):
  Total ao investidor: R$ 20.837.803 → +24,9% sobre o modelo flat

  Todo o upside do IPCA é distribuído proporcionalmente pelas 3 tranches,
  já que o waterfall é % do EBITDA (não valores fixos absolutos).
  → Equity é a maior beneficiária (recebe o residual em crescimento)
```

### 6.6 Buffers de Proteção (DSCR)

```
  EBITDA mínimo fase inicial: R$ 97.562/mês
  Total investidores fase inicial: R$ 87.806/mês

  DSCR Senior apenas:        87.806 ÷ 65.875 = 1,33×
  DSCR Senior + Mezanino:    87.806 ÷ 79.825 = 1,10×
  DSCR todos os 3:           87.806 ÷ 87.806 = 1,00×

  Equity quebra se EBITDA cai abaixo de:   R$ 88.695  (queda de 15%)
  Mezanino quebra se EBITDA cai abaixo de: R$ 81.083  (queda de 22%)
  Senior quebra se EBITDA cai abaixo de:   R$ 73.194  (queda de 30%)
```

---

## 7. PERSPECTIVA DE RECEBÍVEIS — WATERFALL COMPLETO (15 ANOS)

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  CLIENTE PAGA: R$ 110.062/mês (+ IPCA anual — modelo usa flat conservador)
  (-) O&M:  -R$ 12.500 (meses 1–36)  →  -R$ 5.750 (mês 37–180, c/ IA)
  EBITDA:    R$  97.562 (meses 1–36)  →   R$ 104.312 (mês 37–180, c/ IA)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

┌──────────────────────────────────────┬────────────────────────────────────┐
│  INVESTIDORES (90%) — WATERFALL      │  EMPRESA (10%)                     │
├──────────────────────────────────────┼────────────────────────────────────┤
│  🔵 SENIOR: R$ 11.857.500 | 2,55×   │  EPC:  R$    930.000               │
│  🟡 MEZANINO: R$ 2.511.000 | 2,70×  │  Fees: R$  1.853.280               │
│  🔴 EQUITY: R$ 2.311.380 | 3,73×    │  TOTAL:R$  2.783.280               │
│  TOTAL: R$ 16.679.760 | 2,69×       │                                    │
│  IRR blended: ~17,0%  ✓             │                                    │
├──────────────────────────────────────┴────────────────────────────────────┤
│  FIM DO CONTRATO (MÊS 180): taxa de saída R$ 800k (custo líquido = R$0)  │
│  ECONOMIA LÍQUIDA DO CLIENTE: R$ 11.059.840  ✓                           │
└───────────────────────────────────────────────────────────────────────────┘
```

### Segundo Ciclo — Empresa (Ano 15)

```
  Tarifa MWh em 15 anos (IPCA 5%):  R$ 409 × 1,05¹⁵ = R$ 850/MWh
  EBITDA second life:                R$ 223.085/mês = R$ 2.677.020/ano
  ROI sobre capital zero:            ∞
```

---

## 8. WALE — VIDA CONTRATUAL RESTANTE NA SAÍDA (ANO 7)

| Projeto assinado | Anos decorridos | 15 anos restantes |
|-----------------|----------------|-------------------|
| Ano 1 | 6 anos | 9 anos |
| Ano 2 | 5 anos | 10 anos |
| Ano 3 | 4 anos | 11 anos |
| Ano 4 | 3 anos | 12 anos |
| Ano 5 | 2 anos | 13 anos |
| Ano 6 | 1 ano | 14 anos |
| Ano 7 | 0 anos | 15 anos |
| **WALE médio** | | **~12 anos** |

---

## 9. NOSSA RECEITA POR PROJETO — 15 ANOS COM IA

| Fonte | Momento | Valor |
|-------|---------|-------|
| Margem EPC | Ano 0 | **R$ 930.000** |
| Fee 10% — Meses 1–36 (fase inicial) | Mensal | R$ 351.216 |
| Fee 10% — Meses 37–180 (fase madura c/ IA) | Mensal | R$ 1.502.064 |
| **Total Ciclo 1** | | **R$ 2.783.280** |
| Taxa de saída (custo líquido) | Mês 180 | R$ 0 |

---

## 10. P&L CONSOLIDADO — ANO A ANO

### 10.1 Receita por Fonte

| Fonte de Receita | Ano 1 | Ano 3 | Ano 5 | Ano 7 |
|-----------------|-------|-------|-------|-------|
| Margem EPC | R$ 4,7M | R$ 23,3M | R$ 41,9M | R$ 51,2M |
| Fee 10% — portfólio | R$ 0,6M | R$ 4,8M | R$ 12,9M | R$ 27,8M |
| Motor Transfer (líquido)² | — | R$ 13,4M | R$ 80,7M | R$ 134,5M |
| Serviços O&M / SCADA terceiros | R$ 0,3M | R$ 2,0M | R$ 8,0M | R$ 20,0M |
| BESS ancilares (CCEE) | — | R$ 1,0M | R$ 8,0M | R$ 20,0M |
| Plataforma IA (licenciamento) | — | — | R$ 1,5M | R$ 8,0M |
| **Receita Total** | **R$ 5,6M** | **R$ 44,5M** | **R$ 153,0M** | **R$ 261,5M** |

> ² **Motor Transfer**: receita **líquida** após buyout de investidores e custos de transação.
> Detalhamento completo na Seção 18.

### 10.2 Custos

| Custo | Ano 1 | Ano 3 | Ano 5 | Ano 7 |
|-------|-------|-------|-------|-------|
| O&M dos ativos (IA plena a partir Ano 3) | R$ 0,8M | R$ 4,8M | R$ 11,2M | R$ 15,6M |
| Overhead da empresa | R$ 2,6M | R$ 8,7M | R$ 26,4M | R$ 42,7M |
| **Total** | **R$ 3,4M** | **R$ 13,5M** | **R$ 37,6M** | **R$ 58,3M** |

### 10.3 EBITDA e Valuation

| Métrica | Ano 1 | Ano 3 | Ano 5 | Ano 7 |
|---------|-------|-------|-------|-------|
| Receita | R$ 5,6M | R$ 44,5M | R$ 153,0M | R$ 261,5M |
| Custos | -R$ 3,4M | -R$ 13,5M | -R$ 37,6M | -R$ 58,3M |
| **EBITDA** | **R$ 2,2M** | **R$ 31,0M** | **R$ 115,4M** | **R$ 203,2M** |
| Margem EBITDA | 39% | 70% | 75% | 78% |
| **Valuation (ver Seção 13)** | — | R$ 330M | R$ 1.200M | **R$ 1,2–2,0B** |

---

## 11. PROJEÇÃO DE PROJETOS E PORTFÓLIO

| Ano | Novos Projetos | Portfólio Ativo | AUM Total | Motor Transfer | Headcount |
|-----|---------------|-----------------|----------|---------------|-----------|
| 2025 (base) | — | 2 | R$ 12M | — | 8 |
| 2026 | 5 | 7 | R$ 43M | — | 18 |
| 2027 | 15 | 22 | R$ 136M | — | 35 |
| 2028 | 25 | 47 | R$ 291M | 2 deals | 60 |
| 2029 | 35 | 82 | R$ 508M | 8 deals | 95 |
| 2030 | 45 | 127 | R$ 787M | 12 deals | 130 |
| 2031 | 50 | 177 | R$ 1.097M | 16 deals | 150 |
| 2032 | 50 | 227 | R$ 1.407M | 20 deals | 170 |

---

## 12. PLANO OPERACIONAL — 7 ANOS

### ANO 1 (2026) — Fundação | 5 projetos
```
□ Constituir holding + modelo SPE
□ Contrato BOT: 15 anos, IPCA, garantia capacidade, taxa de saída R$ 800k
□ Fechar 3–5 projetos com clientes âncora
□ Prospectar investidores por tranche (Senior/Mezanino/Equity)
□ Hedge cambial para EPC (NDF/swap USD/BRL)
□ Implantar SCADA básico + iniciar desenvolvimento da plataforma IA
```

### ANO 2 (2027) — Pipeline | +15 projetos
```
□ Lançar MVP da plataforma IA (R$ 150k)
□ Estruturar FIDC I (~R$ 43M, 7 projetos) — ver Seção 19
□ Contratar CFO com experiência em fundos estruturados
□ Expandir para 2 novos estados
```

### ANO 3 (2028) — Aceleração | +25 projetos
```
□ Plataforma IA v2: preditiva + dispatch automático (R$ 100k)
□ ROLLOUT COMPLETO DA IA — todos os projetos migrados (mês 36)
□ Lançar FIDC II (~R$ 93M) — cota Equity passa a R$ 14.056/mês a partir daqui
□ Primeiros 2 deals de Motor Transfer (~R$ 13,4M líquido)
```

### ANO 4–5 (2029–2030) — Escala | R$ 85–153M
```
□ Motor Transfer: 8–12 deals/ano
□ FIDC III e IV — captação trimestral
□ Plataforma IA com 80–127 projetos monitorados
□ Presença nacional (5+ estados)
□ Conselho com 2+ independentes
```

### ANO 6–7 (2031–2032) — Saída | R$ 205–261M
```
□ Motor Transfer: 16–20 deals/ano
□ Advisor sell-side + VDD + Information Memorandum
□ Plataforma IA + PI destacados no IM
□ WALE > 12 anos (renovar contratos estratégicos)
□ Auditoria Big 4 — 3º+ ano consecutivo
□ M&A sell-side competitivo — Binding Bids + SPA
```

---

## 13. TESE DE SAÍDA

### 13.1 Valuation — Separado por Tipo de Receita

O comprador vai aplicar múltiplos diferentes por natureza da receita:

| Fonte de EBITDA Ano 7 | EBITDA | Múltiplo | EV parcial | Justificativa |
|-----------------------|--------|---------|-----------|---------------|
| Fee recorrente 10% (portfólio) | R$ 27,8M | 15× | R$ 417M | Contratos 15 anos, WALE 12a |
| Serviços O&M + SCADA terceiros | R$ 20,0M | 12× | R$ 240M | Recorrente, previsível |
| BESS ancilares (CCEE) | R$ 20,0M | 10× | R$ 200M | Regulatório, crescente |
| Plataforma IA (licenciamento) | R$ 8,0M | 20× | R$ 160M | SaaS, escalável |
| Motor Transfer (transacional) | R$ 134,5M | 6× | R$ 807M | Recorrente como negócio |
| **Total EV** | | | **~R$ 1,82B** | |
| Margem de negociação (-20%) | | | **~R$ 1,46B** | |
| **Consenso conservador** | | | **R$ 1,2B – R$ 1,8B** | |

> O EBITDA de Motor Transfer, embora transacional por projeto, é **recorrente como linha de negócio**
> (20 deals/ano de forma sistemática), o que justifica o múltiplo de 6×.
> Compradores estratégicos (utilities) pagarão prêmio por acesso à plataforma IA e base de clientes.

### 13.2 Perfil de Compradores

| Tipo | Exemplos | Múltiplo estimado | Motivação |
|------|----------|------------------|-----------|
| Utility nacional | Engie, EDP, CPFL | 12–15× EBITDA recorrente | 227 clientes C&I + plataforma IA |
| Utility internacional | Enel X, Iberdrola | 11–14× | Entrada no mercado brasileiro |
| Fundo infraestrutura | Brookfield, Pátria | 9–12× | Cash flow de longo prazo + IA |
| PE energético | BTG Energia, Kinea | 10–12× | Crescimento acelerado + PI |

---

## 14. RISCOS E MITIGAÇÕES

| Risco | Prob. | Impacto | Mitigação |
|-------|-------|---------|----------|
| Cliente não aceita 15 anos | Média | Alto | Economia R$11M + indexação IPCA protege o cliente |
| Yield spread fino vs CDI+3% | Alta | Crítico | Senior 17%, Mezanino 18% — ambos > CDI+3% |
| Degradação BESS > projetada | Baixa | Médio | IPCA (+5%) > degradação (2%); garantia capacidade + augmentação Ano 10 |
| Risco cambial no EPC | Média | Alto | Hedge NDF/swap USD/BRL travado na assinatura |
| O&M subestimado | Baixa | Médio | IA preditiva + fundo contingência (R$700/mês) + DSCR 1,33× |
| Plataforma IA atrasa rollout | Média | Médio | Equity recebe 15,4% até mês 36 — IRR cai mas ainda > CDI+3% |
| Motor Transfer: comprador não aparece | Baixa | Alto | Pipeline de 15+ utilities/fundos; deals estruturados via banker |
| Overhead cresce > receita | Média | Alto | Contratação vinculada a projetos assinados |
| Regulatório (ANEEL, CCEE) | Baixa | Médio | Certificação BESS Ano 3; receita ancilares não é base do modelo |
| Concorrente replica modelo | Média | Médio | Moat: IA proprietária + 3+ anos de dados + WALE 12a — ver Seção 20 |
| Tarifa de energia cai | Baixa | Alto | IPCA indexado; cliente ainda economiza mesmo com tarifa -20% |

---

## 15. KPIs — REVISÃO TRIMESTRAL

| KPI | Ano 2 | Ano 4 | Ano 5 | Ano 7 |
|-----|-------|-------|-------|-------|
| Receita Total | R$ 15M | R$ 82M | R$ 153M | R$ 261M |
| EBITDA | R$ 7,5M | R$ 58M | R$ 115M | R$ 203M |
| Margem EBITDA | 50% | 71% | 75% | 78% |
| Projetos no portfólio | 22 | 82 | 127 | 227 |
| AUM | R$ 136M | R$ 508M | R$ 787M | R$ 1,41B |
| Deals Motor Transfer | 0 | 8 | 12 | 20 |
| Yield Senior (fixo) | 17,0% | 17,0% | 17,0% | 17,0% |
| Yield Mezanino (fixo) | 18,0% | 18,0% | 18,0% | 18,0% |
| Yield Equity residual (maduro) | 27,2% | 27,2% | 27,2% | 27,2% |
| IRR blended investidor | ~15% | ~16% | ~16,8% | ~17,0% |
| O&M como % receita BOT | 11,4% | 5,2% | 5,2% | 5,2% |
| WALE médio contratos | 14 anos | 13 anos | 13 anos | 12 anos |
| Projetos monitorados por IA | 0 | 82 | 127 | 227 |
| CAC por projeto | R$ 30k | R$ 26k | R$ 24k | R$ 22k |
| LTV/CAC | 93× | 107× | 114× | 124× |
| NPS clientes | 55 | 65 | 72 | 78 |

---

## 16. PRÓXIMOS 90 DIAS

### Sprint 1 (Semanas 1–4): Jurídico e Modelagem
- [ ] Holding + modelo SPE + cláusula IPCA no contrato BOT
- [ ] Garantia de capacidade (90% nominal) + augmentação Ano 10
- [ ] Hedge cambial: parceria com mesa de câmbio para NDF nos EPCs
- [ ] Modelo financeiro: 3 tranches com waterfall + Motor Transfer

### Sprint 2 (Semanas 3–8): Captação e Tecnologia
- [ ] Pitch deck por perfil (Senior/Mezanino/Equity)
- [ ] Iniciar gestora de FIDC ou parceria (BTG/Kinea) para FIDC I
- [ ] Arquitetura plataforma IA — roadmap para rollout completo no mês 36

### Sprint 3 (Semanas 5–12): Pipeline Comercial
- [ ] Mapear 600 empresas C&I alvo (critério: conta > R$ 150k/mês energia)
- [ ] Configurar CRM + processo de qualificação (ciclo 90 dias)
- [ ] Fechar primeiros 3–5 projetos (valida CAC e ciclo de venda)

---

## 17. GLOSSÁRIO

| Termo | Definição |
|-------|----------|
| **BOT** | Build-Operate-Transfer: construir, operar 15 anos, retirar |
| **O&M** | Operação e manutenção — custo do projeto, antes do split |
| **IA de Monitoramento** | Plataforma própria: anomalias + preditiva + dispatch automático |
| **EBITDA do Projeto** | Receita BOT menos O&M — base para split 90/10 |
| **Curva de Maturidade** | Transição O&M inicial→maduro c/ IA: 3 anos (mês 36) |
| **Motor Transfer** | Venda de SPE matura a comprador estratégico — receita líquida ~R$6,7M/deal |
| **WALE** | Weighted Average Life: prazo médio ponderado restante dos contratos |
| **IRR** | Taxa Interna de Retorno — considera timing e valor do dinheiro |
| **Yield** | Retorno anual cash-on-cash |
| **Waterfall** | Ordem de pagamento: Empresa 10% → Senior → Mezanino → Equity |
| **Senior** | Tranche 75% do capital, 17%/ano fixo, 1º a receber, DSCR 1,33× |
| **Mezanino** | Tranche 15% do capital, 18%/ano fixo, 2º a receber |
| **Equity** | Tranche residual 10%, captura eficiência IA, IRR 22,6% em 15 anos |
| **DSCR** | Debt Service Coverage Ratio: EBITDA ÷ pagamento investidores |
| **FIDC** | Fundo de Investimento em Direitos Creditórios — veículo de captação |
| **CDI+3%** | Custo de capital referência: 13,25% + 3% = 16,25% a.a. |
| **NDF** | Non-Deliverable Forward: contrato de hedge cambial |
| **IPCA** | Índice de inflação — indexador da tarifa BOT |
| **Degradação BESS** | Perda de ~2%/ano na capacidade da bateria (padrão Li-ion) |
| **Augmentação** | Adição de módulos de bateria para restaurar capacidade nominal |

---

## 18. MOTOR TRANSFER — MECÂNICA DA RECICLAGEM DE ATIVOS

### O que é

Motor Transfer é a venda de uma SPE operacional matura (3+ anos de track record) a um comprador estratégico — utility, fundo de infraestrutura ou PE — que valoriza o ativo pelo seu fluxo de caixa contratado de longo prazo. A empresa **não vende o negócio**: vende projetos individuais, retém o know-how, a plataforma IA e a capacidade de construir novos projetos.

### Por que funciona a partir do Ano 3

Um comprador estratégico aceita pagar 10× EBITDA anual por um projeto que tem:
- **Track record**: 3 anos de operação comprovada, uptime 99%+
- **Contrato longo**: 12 anos remanescentes (WALE elevado)
- **O&M baixo e previsível**: R$ 5.750/mês com IA — sem surpresas
- **Receita indexada**: IPCA protege o valor real
- **Tecnologia embarcada**: plataforma IA monitora o ativo automaticamente

O comprador opera com custo de capital de 10–12%/ano. A 10× EBITDA, o IRR implícito do comprador é de ~11-13%, dentro do seu custo de capital — o deal faz sentido para ele.

### Cálculo por Transação

```
  EBITDA anual do projeto (maduro c/ IA):     R$  1.251.744
  Preço de venda (10× EBITDA anual):          R$ 12.517.440

  Buyout antecipado dos investidores:
    🔵 Senior   (PV de R$65.875/mês × 144m, IRR 16,8%): -R$ 4.069.840
    🟡 Mezanino (PV de R$13.950/mês × 144m, IRR 17,8%): -R$   827.601
    🔴 Equity   (PV de R$14.056/mês × 144m, IRR 22,6%): -R$   695.511
    Total buyout:                                        -R$ 5.592.952
  Custos de transação (legal + structuring):             -R$   200.000
  ─────────────────────────────────────────────────────────────────────
  LÍQUIDO PARA A EMPRESA por deal:             R$  6.724.488 ≈ R$ 6,7M
```

> **Nota**: o investidor é reembolsado antecipadamente pelo NPV exato dos seus fluxos futuros
> descontados ao seu próprio IRR-alvo — portanto **não perde retorno**. O comprador estratégico
> paga mais do que o NPV do investidor porque tem custo de capital menor.

### Projeção de Deals e Receita

| Ano | Deals/ano | Líquido/deal | Receita Motor Transfer |
|-----|----------|-------------|----------------------|
| 3 | 2 | R$ 6,7M | **R$ 13,4M** |
| 4 | 8 | R$ 6,7M | R$ 53,8M |
| 5 | 12 | R$ 6,7M | **R$ 80,7M** |
| 6 | 16 | R$ 6,7M | R$ 107,6M |
| 7 | 20 | R$ 6,7M | **R$ 134,5M** |

> 20 deals no Ano 7 representa **9% do portfólio de 227 projetos** — volume completamente factível.
> A empresa sempre reconstrói o pipeline com novos projetos (50/ano), mantendo o AUM crescente.

### Impacto na Empresa

A empresa abre mão de ~R$10.431/mês de fee recorrente por projeto vendido, mas recebe R$6,7M à vista. O NPV do fee perdido (10 anos remanescentes, desconto 25%) é ~R$450k. Troca favorável em ~15× o valor presente do fee.

---

## 19. MECÂNICA DE CAPTAÇÃO — ESTRUTURA FIDC

### Por que FIDC e não captação individual

Captar R$6,2M de um único investidor por projeto é viável nos primeiros anos, mas a partir do Ano 3 (+25 projetos/ano = R$155M/ano de capital novo) é necessário um veículo estruturado que:
- Permita múltiplos investidores num único instrumento
- Ofereça liquidez secundária (cotas negociáveis)
- Tenha governance e rating (reduz custo de capital do Senior)
- Escale sem exigir negociação individual por projeto

### Estrutura do FIDC BOT

```
  ┌─────────────────────────────────────────────────────────────────┐
  │  FIDC BESS INFRASTRUCTURE FUND                                  │
  │  Lastro: recebíveis de X contratos BOT (15 anos, 110k/mês cada) │
  ├──────────────────┬──────────────────┬───────────────────────────┤
  │  COTA SÊNIOR     │  COTA MEZANINO   │  COTA SUBORDINADA         │
  │  75% do capital  │  15% do capital  │  10% do capital           │
  │  Yield 17%/ano   │  Yield 18%/ano   │  Residual (27,2% maduro)  │
  │  Rating A–AA     │  Rating BBB–A    │  Sem rating               │
  │  Institucional   │  Family Office   │  Empresa (1ª perda)       │
  └──────────────────┴──────────────────┴───────────────────────────┘
```

> **Empresa retém a cota subordinada** como "first-loss piece" — sinal de skin in the game
> que reduz o custo de captação das cotas sênior e mezanino.

### Cronograma de Emissões

| FIDC | Ano | Projetos | Tamanho | Cota Sênior | Cota Mez. | Empresa (Sub.) |
|------|-----|----------|---------|------------|-----------|---------------|
| I | 2 | 7 | R$ 43M | R$ 32M | R$ 6,5M | R$ 4,5M |
| II | 3 | 15 | R$ 93M | R$ 70M | R$ 14M | R$ 9,3M |
| III | 3–4 | 20 | R$ 124M | R$ 93M | R$ 18,6M | R$ 12,4M |
| IV+ | 4–7 | Trimestral | R$ 100–200M | 75% | 15% | 10% |

> A cota subordinada da empresa (10%) pode ser reduzida para 5% após o FIDC I demonstrar
> track record positivo — liberando capital da empresa para novos projetos.

### Custos de Estruturação

| Item | FIDC I (Ano 2) | FIDCs Seguintes |
|------|---------------|-----------------|
| Legal + estruturação | R$ 400k | R$ 250k |
| Gestora (terceira) | R$ 300k | R$ 200k |
| Registro CVM/ANBIMA | R$ 80k | R$ 50k |
| Custódia + admin (anual) | 0,8% AUM | 0,5% AUM |
| Rating agency | R$ 150k | R$ 100k |
| **Total implantação** | **R$ 930k** | **~R$ 600k** |

> **Gestora**: Ano 1–2 usar gestora parceira (BTG Pactual, Kinea, Vinci). Ano 3+
> solicitar autorização CVM como gestora própria — reduz custo e aumenta controle.

### Investidores-Alvo por Cota

| Cota | Investidores | Ticket mínimo | Pipeline de captação |
|------|-------------|--------------|----------------------|
| Sênior | Bancos, fundos de pensão, seguradoras | R$ 5M+ | Relacionamento via CFO + i-bank |
| Mezanino | Family offices, HNWIs, fundos multimercado | R$ 500k | Eventos de energia, plataformas de investimento |
| Subordinada | Empresa (retida) | — | Capital próprio + Motor Transfer reciclado |

---

## 20. ANÁLISE COMPETITIVA

### Panorama do Mercado BESS BOT no Brasil (2026)

| Competidor | Modelo | Força | Fraqueza |
|-----------|--------|-------|----------|
| **Utilities (Engie, EDP, CPFL)** | Projetos próprios / concessões | Capital e relacionamento | Focam em >10MW; lento para C&I |
| **Integradores solares (BYD, WEG)** | Venda de equipamento | Capacidade produtiva | Não oferecem financiamento BOT |
| **Solar BOT (Âmbar, Elipse)** | BOT solar, sem storage | Know-how comercial | Sem BESS, sem arbitragem de energia |
| **Enel X (internacional)** | BESS corporativo global | Tecnologia e capital | Foco em projetos >5MW, CAPEX alto |
| **Startups locais emergentes** | BESS C&I nascentes | Agilidade | Sem capital estruturado nem IA |
| **Nossa empresa** | BOT BESS C&I + FIDC + IA | **Modelo completo** | Tamanho e histórico |

### Por Que Somos Difíceis de Replicar

```
  1. PLATAFORMA IA PROPRIETÁRIA
     → 3+ anos de dados de 50–200 projetos simultâneos
     → Modelos preditivos treinados especificamente em BESS C&I brasileiro
     → Concorrente que copiar hoje chegará em 2029 sem dados históricos

  2. ESTRUTURA FIDC OPERACIONAL
     → Gestora licenciada + relacionamento institucional estabelecido
     → Track record de 2+ anos de adimplência = custo de capital cai
     → Barreiras regulatórias (CVM) para copiar

  3. WALE DE 12 ANOS NO PORTFÓLIO
     → Um comprador estratégico prefere adquirir a empresa do que replicar
     → 227 contratos assinados = 227 clientes fidelizados por 9–15 anos

  4. EQUIPE ESPECIALIZADA
     → Combinação rara: EPC + financiamento + IA + operações de campo
     → Time de 170 pessoas com expertise específica em BESS BOT

  5. FIRST-MOVER EM C&I BESS BOT NO BRASIL
     → Primeiros projetos em 2026 = prime sites e referências enquanto
       concorrentes ainda estão estruturando o modelo
```

### Por Que Utilities Não Copiam Rapidamente

- **Governança lenta**: ciclo de decisão de 12–18 meses para novos produtos
- **Foco diferente**: operam projetos >10MW; o mercado C&I (<2MW) não é prioritário
- **Estrutura de custo**: custo fixo alto — não conseguem fazer economics de R$6,2M viables
- **Resultado**: as utilities são mais prováveis como **compradores** no exit do que competidores

---

## 21. FUNIL COMERCIAL

### Mercado Endereçável

```
  Empresas C&I no Brasil com conta de energia > R$ 150k/mês:  ~50.000
  Endereçável (logística + industrial + varejo + data center):  ~15.000
  Pipeline qualificado Year 5:                                    ~600 leads/ano
```

### Funil de Vendas — Ano 5 (meta: 45 projetos)

```
  600  leads gerados/ano
   ↓  qualificação (20%) — critérios: conta energia, localização, perfil de consumo
  120  oportunidades qualificadas
   ↓  proposta técnico-comercial (50%)
   60  propostas enviadas
   ↓  fechamento (75%)
   45  contratos assinados  ✓  (meta Ano 5)
```

### Fontes de Leads

| Canal | % dos leads | Custo | Maturidade |
|-------|-------------|-------|-----------|
| Referências (clientes existentes) | 30% | ~R$0 | Ano 3+ |
| Corretoras/consultoras de energia | 25% | Comissão 1% EPC | Imediato |
| Marketing digital (LinkedIn, Google) | 20% | R$ 200–300k/ano | Ano 1+ |
| Parcerias (contabilidades, associações) | 25% | Revenue share | Ano 2+ |

### Métricas de Eficiência Comercial

| Métrica | Ano 1 | Ano 3 | Ano 5 | Ano 7 |
|---------|-------|-------|-------|-------|
| KAMs ativos | 1 | 5 | 8 | 12 |
| Projetos por KAM/ano | 5 | 8 | 6 (+ gestão portfólio) | 5 |
| Ciclo médio de venda | 120 dias | 90 dias | 75 dias | 60 dias |
| CAC por projeto | R$ 30k | R$ 27k | R$ 24k | R$ 22k |
| LTV empresa (ciclo 1) | R$ 2.783.280 | R$ 2.783.280 | R$ 2.783.280 | R$ 2.783.280 |
| **LTV / CAC** | **93×** | **103×** | **114×** | **124×** |

> **LTV/CAC de 100×+** é excepcional e reflete a natureza de longo prazo do contrato BOT.
> Mesmo com CAC 5× maior, o modelo ainda seria amplamente viável.

### Ciclo de Venda — 75 dias (Ano 5)

```
  Semana 1–2:  Qualificação (consumo, localização, perfil de carga)
  Semana 3–4:  Auditoria energética gratuita + simulação de economia
  Semana 5–8:  Proposta técnico-comercial + apresentação ao CFO/CEO
  Semana 9–11: Negociação contratual (BOT + SPE + cláusulas IPCA/capacidade)
  Semana 12:   Assinatura + início do EPC
```

---

*Versão 10.0 — Maio/2026 | Confidencial*
*Resoluções v10.0: Motor Transfer (mecânica + math), FIDC (estrutura + timeline),*
*Análise Competitiva, Funil Comercial (LTV/CAC 114×), Degradação BESS + IPCA (+24,9% upside)*
*Contrato: 15 anos | IPCA indexado | Maturidade IA: 3 anos | Equity IRR: 22,6%*
