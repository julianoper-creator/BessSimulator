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
| Taxa de saída ao final do contrato | **R$ 800.000** | Custo operacional de retirada + reinstalação |
| Monitoramento | **Plataforma IA própria** | Deploy Year 2 — substitui analistas SCADA manuais |

> ¹ **Por que BNDES não é a rota principal**: exige fabricação nacional, elevando CAPEX em
> 20–30% para a mesma capacidade geradora. DSCR cai para 0,80–0,90× — inviável.

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

| Item | Escala Inicial (1–30 proj.) | Escala Madura com IA (100+ proj.) | Variação |
|------|-----------------------------|----------------------------------|----------|
| Manutenção técnica de campo | R$ 6.500 | R$ 2.800 | IA preditiva reduz visitas reativas |
| Seguro patrimonial | R$ 2.200 | R$ 1.500 | Apólice coletiva |
| SCADA / Monitoramento IA | R$ 1.500 | **R$ 150** | Plataforma própria amortizada |
| Administração da SPE | R$ 1.000 | R$ 600 | Automação administrativa |
| Fundo de contingência | R$ 1.300 | **R$ 700** | Manutenção preditiva reduz surpresas |
| **Total O&M mensal** | **R$ 12.500** | **R$ 5.750** | **-19% vs modelo manual** |
| **Total O&M anual** | **R$ 150.000** | **R$ 69.000** | |
| **O&M como % receita BOT** | **11,4%** | **5,2%** | |

> **O&M escala madura sem IA seria R$ 7.100/mês.** A plataforma de monitoramento por IA
> reduz o custo em R$ 1.350/projeto/mês — representando R$ 3,68M/ano de economia
> a 227 projetos. Investimento de desenvolvimento: R$ 250k (payback < 3 meses).

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

### 4.2 Fase Operate — P&L Mensal

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  RECEITA BOT (cliente, desconto 10%)       R$ 110.062/mês
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  (-) O&M — custo do projeto (antes do split)
      Escala Inicial (sem IA)              -R$  12.500/mês
      Escala Madura (com IA)               -R$   5.750/mês
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  EBITDA PARA DISTRIBUIÇÃO
      Escala Inicial                        R$  97.562/mês
      Escala Madura com IA                  R$ 104.312/mês  = R$ 1.251.744/ano
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  INVESTIDOR 90%:
      Escala Inicial   R$  87.806/mês  [yield 17,00%/ano]
      Escala Madura    R$  93.881/mês  [yield 18,17%/ano]  ← melhora c/ IA

  EMPRESA 10% (fee líquido, sem O&M):
      Escala Inicial   R$   9.756/mês
      Escala Madura    R$  10.431/mês
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  FUNDING CDI+3% — referência (inviável):
      PMT = R$ 104.817/mês  vs  EBITDA R$ 104.312  → DSCR ~1,00×  ✗
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## 5. COMPARATIVO 10 ANOS vs 15 ANOS — TRÊS PERSPECTIVAS

```
╔══════════════════════════════════════════════════════════════════════════╗
║        COMPARATIVO BOT — 10 ANOS vs 15 ANOS (com IA de monitoramento)  ║
╚══════════════════════════════════════════════════════════════════════════╝

━━━ INVESTIDOR | Capital aportado: R$ 6.200.000 ━━━━━━━━━━━━━━━━━━━━━━━━━

                              10 ANOS           15 ANOS
  Yield mensal (maduro)       R$ 93.881         R$ 93.881   (igual)
  Yield anual                 18,17%            18,17%      (igual)
  Recupera capital em         Mês 68            Mês 68      (igual)
  Total recebido              R$ 10.996.020     R$ 16.534.080
  Múltiplo do capital         1,77×             2,67×
  IRR                         ~14,2%  ✗         ~17,0%  ✓
  vs CDI+3% (16,25%)          -2,05 p.p.  ✗    +0,75 p.p.  ✓

━━━ CLIENTE | Mensalidade: R$ 110.062/mês ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

                              10 ANOS           15 ANOS
  Total pago no contrato      R$ 13.207.440     R$ 19.811.160
  Taxa de saída               R$    800.000     R$    800.000
  Tarifa mercado equivalente  R$ 18.439.000     R$ 31.671.000
  Economia líquida            R$  4.431.560     R$ 11.059.840
  Comprometimento             10 anos           15 anos  ⚠

━━━ EMPRESA | Por projeto — Ciclo 1 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

                              10 ANOS           15 ANOS
  EPC margin (upfront)        R$   930.000      R$   930.000
  Fee 10% acumulado           R$ 1.220.520      R$ 1.837.080
  Total ciclo 1               R$ 2.150.520      R$ 2.767.080
  WALE médio na saída (Ano 7)  ~7 anos           ~12 anos
  Valuation saída estimado     ~R$ 2,05B         ~R$ 2,46B

┌──────────────────────────────────────────────────────────────────────────┐
│  VEREDITO                                                                │
│  Investidor:  IRR 17,0% > CDI+3% com contrato 15 anos + IA  ✓          │
│  Cliente:     economiza R$11M — proposta muito mais forte               │
│  Empresa:     O&M -19% por projeto, EBITDA maior, valuation maior       │
└──────────────────────────────────────────────────────────────────────────┘
```

---

## 6. RETORNO DO INVESTIDOR — DETALHE 15 ANOS COM IA

### 6.1 Yield Mensal sobre o Capital

| Cenário | Recebe/mês | % Mensal | % Anual | vs CDI+3%/mês |
|---------|-----------|---------|---------|---------------|
| Escala inicial (O&M R$12.500) | R$ 87.806 | 1,416% | 17,00% | +0,152 p.p. |
| **Escala madura com IA (O&M R$5.750)** | **R$ 93.881** | **1,514%** | **18,17%** | **+0,250 p.p.** |
| Desconto 15%, madura com IA | R$ 88.437 | 1,426% | 17,11% | +0,162 p.p. |

### 6.2 Fluxo Completo de 15 Anos

```
  Capital investido:                           R$  6.200.000

  Anos  1–5  (inicial, O&M R$12.500):
    R$ 87.806/mês × 60:                       R$  5.268.360

  Anos  6–15 (maduro com IA, O&M R$5.750):
    R$ 93.881/mês × 120:                      R$ 11.265.720
  ─────────────────────────────────────────────────────────
  Total recebido 15 anos:                      R$ 16.534.080
  Múltiplo do capital:                         2,67×
  Lucro acima do capital:                      R$ 10.334.080

  Capital totalmente recuperado via yield:     Mês 68 (~5 anos e 8 meses)
  IRR 15 anos:    ~17,0%  vs  CDI+3% 16,25%  →  +0,75 p.p.  ✓
```

### 6.3 Plataforma de IA como Diferencial Competitivo

```
  O que a IA de monitoramento entrega:
  ┌─────────────────────────────────────────────────────────┐
  │  • Anomalia detectada → OS criada → técnico acionado    │
  │    sem nenhum analista no processo                      │
  │  • Manutenção preditiva: falha antecipada em 18+ dias   │
  │  • Dashboard em tempo real para cliente e investidor    │
  │  • Relatórios mensais automatizados por SPE             │
  │  • Uptime: 98% → 99,2% com manutenção preditiva         │
  │  • Dados de 227 projetos × 15 anos = ativo intelectual  │
  │    valioso no processo de venda da empresa              │
  └─────────────────────────────────────────────────────────┘

  Investimento: R$ 250k (Ano 2: R$150k + Ano 3: R$100k)
  Economia anual (227 projetos): R$ 3,68M (O&M) + R$ 742k (analistas)
  Payback: < 3 meses
```

---

## 7. PERSPECTIVA DE RECEBÍVEIS — INVESTIDOR vs EMPRESA (15 ANOS)

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  CLIENTE PAGA: R$ 110.062/mês
  (-) O&M:      -R$ 12.500 (inicial) → -R$ 5.750 (maduro c/ IA)
  EBITDA:        R$  97.562 (inicial) →  R$ 104.312 (maduro c/ IA)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

┌──────────────────────────────────┬──────────────────────────────────────┐
│     INVESTIDOR (90%)             │       EMPRESA (10%)                  │
├──────────────────────────────────┼──────────────────────────────────────┤
│  Capital:     R$ 6.200.000       │  EPC margin:   R$    930.000         │
│                                  │                                      │
│  Anos 1–5 (inicial, ×60m):       │  Anos 1–5:                           │
│  R$ 87.806/mês = R$5.268.360    │  R$ 9.756/mês = R$  585.360         │
│                                  │                                      │
│  Anos 6–15 (maduro IA, ×120m):   │  Anos 6–15:                          │
│  R$ 93.881/mês = R$11.265.720   │  R$10.431/mês = R$ 1.251.720        │
│                                  │                                      │
│  TOTAL 15 anos: R$16.534.080    │  Fee total:    R$ 1.837.080          │
│  = 2,67× o capital               │  + EPC:        R$   930.000          │
│  Yield: 18,17%/ano  ✓            │  TOTAL CICLO 1:R$ 2.767.080          │
│  IRR:   ~17,0%/ano  ✓            │                                      │
├──────────────────────────────────┴──────────────────────────────────────┤
│  FIM DO CONTRATO (MÊS 180):                                              │
│  Taxa de saída (cliente paga):  R$ 800.000                              │
│  Custo retirada + reinstalação: -R$ 800.000  → custo líquido = R$0      │
│  Empresa retoma ativo. Investidor encerrou com 2,67× o capital.          │
├──────────────────────────────────────────────────────────────────────────┤
│  POSIÇÃO LÍQUIDA DO CLIENTE:                                             │
│  Tarifa mercado 15 anos (+5%/ano):  R$31.671.000                        │
│  BOT + taxa de saída:               R$20.611.160                        │
│  ECONOMIA LÍQUIDA:                  R$11.059.840  ✓                     │
└──────────────────────────────────────────────────────────────────────────┘
```

### Segundo Ciclo — Empresa (Ano 15)

```
  Capital adicional:          R$ 0  (taxa de saída cobre reinstalação)
  Tarifa MWh em 15 anos:      R$ 409 × 1,05¹⁵ = R$ 850/MWh
  BOT second life (10% desc): R$ 765/MWh × 299 = R$ 228.835/mês
  (-) O&M maduro com IA:      -R$   5.750/mês
  EBITDA second life:          R$ 223.085/mês = R$ 2.677.020/ano
  ROI sobre capital zero:      ∞
```

---

## 8. WALE — VIDA CONTRATUAL RESTANTE NA SAÍDA (ANO 7)

| Projeto assinado | Anos decorridos | 10 anos restantes | 15 anos restantes |
|-----------------|----------------|-------------------|-------------------|
| Ano 1 | 6 anos | 4 anos | 9 anos |
| Ano 2 | 5 anos | 5 anos | 10 anos |
| Ano 3 | 4 anos | 6 anos | 11 anos |
| Ano 4 | 3 anos | 7 anos | 12 anos |
| Ano 5 | 2 anos | 8 anos | 13 anos |
| Ano 6 | 1 ano | 9 anos | 14 anos |
| Ano 7 | 0 anos | 10 anos | 15 anos |
| **WALE médio** | | **~7 anos** | **~12 anos** |

---

## 9. NOSSA RECEITA POR PROJETO — 15 ANOS COM IA

| Fonte | Momento | Valor |
|-------|---------|-------|
| Margem EPC | Ano 0 | **R$ 930.000** |
| Fee 10% — Anos 1–5 (inicial, ×60m) | Mensal | R$ 585.360 |
| Fee 10% — Anos 6–15 (maduro IA, ×120m) | Mensal | R$ 1.251.720 |
| **Total Ciclo 1** | | **R$ 2.767.080** |
| Taxa de saída (custo líquido) | Mês 180 | R$ 0 |
| **Receita média anual ciclo 1** | | **R$ 184.472** |

---

## 10. P&L CONSOLIDADO — ANO A ANO

### 10.1 Receita por Fonte

| Fonte de Receita | Ano 1 | Ano 3 | Ano 5 | Ano 7 |
|-----------------|-------|-------|-------|-------|
| Margem EPC | R$ 4,7M | R$ 23,3M | R$ 41,9M | R$ 51,2M |
| Fee 10% — investidor | R$ 0,6M | R$ 4,8M | R$ 12,9M | R$ 27,8M |
| Reciclagem de ativos | — | R$ 14,0M | R$ 87,5M | R$ 140,0M |
| Serviços O&M / SCADA terceiros | R$ 0,3M | R$ 2,0M | R$ 8,0M | R$ 20,0M |
| BESS ancilares (CCEE) | — | R$ 1,0M | R$ 8,0M | R$ 20,0M |
| Plataforma IA (licenciamento) | — | — | R$ 1,5M | R$ 8,0M |
| **Receita Total** | **R$ 5,6M** | **R$ 45,1M** | **R$ 159,8M** | **R$ 267,0M** |

### 10.2 Custos

| Custo | Ano 1 | Ano 3 | Ano 5 | Ano 7 |
|-------|-------|-------|-------|-------|
| O&M dos ativos (com IA a partir Ano 3) | R$ 0,8M | R$ 4,8M | R$ 11,2M | R$ 15,6M |
| Overhead da empresa | R$ 2,6M | R$ 8,7M | R$ 26,4M | R$ 42,7M |
| **Total** | **R$ 3,4M** | **R$ 13,5M** | **R$ 37,6M** | **R$ 58,3M** |

### 10.3 EBITDA e Valuation

| Métrica | Ano 1 | Ano 3 | Ano 5 | Ano 7 |
|---------|-------|-------|-------|-------|
| Receita | R$ 5,6M | R$ 45,1M | R$ 159,8M | R$ 267,0M |
| Custos | -R$ 3,4M | -R$ 13,5M | -R$ 37,6M | -R$ 58,3M |
| **EBITDA** | **R$ 2,2M** | **R$ 31,6M** | **R$ 122,2M** | **R$ 208,7M** |
| Margem EBITDA | 39% | 70% | 76% | 78% |
| **Valuation 12× (WALE 12a)** | — | R$ 379M | R$ 1.466M | **R$ 2.504M** |

---

## 11. PROJEÇÃO DE PROJETOS E PORTFÓLIO

| Ano | Novos Projetos | Portfólio Ativo | AUM Total | Headcount |
|-----|---------------|-----------------|----------|-----------|
| 2025 (base) | — | 2 | R$ 12M | 8 |
| 2026 | 5 | 7 | R$ 43M | 18 |
| 2027 | 15 | 22 | R$ 136M | 35 |
| 2028 | 25 | 47 | R$ 291M | 60 |
| 2029 | 35 | 82 | R$ 508M | 95 |
| 2030 | 45 | 127 | R$ 787M | 130 |
| 2031 | 50 | 177 | R$ 1.097M | 150 |
| 2032 | 50 | 227 | R$ 1.407M | 170 |

---

## 12. PLANO OPERACIONAL — 7 ANOS

### ANO 1 (2026) — Fundação | 5 projetos | R$ 5,6M
```
□ Constituir holding + modelo SPE
□ Contrato BOT: 15 anos, desconto 10%, taxa de saída R$ 800k
□ Fechar 3–5 projetos com clientes âncora
□ Prospectar 10–15 investidores (HNWIs, family offices)
□ Implantar SCADA básico + iniciar desenvolvimento da plataforma IA
□ Contratar: 2 engenheiros, 1 KAM, 1 advogado, 1 dev, 1 financeiro
```

### ANO 2 (2027) — Pipeline | +15 projetos | R$ 15M
```
□ Lançar MVP da plataforma IA de monitoramento (R$ 150k)
□ Estruturar FIDC para 10+ investidores
□ Ampliar equipe comercial: 3 KAMs + 1 pré-vendas
□ Contratar CFO com experiência em fundos
□ Expandir para 2 novos estados
```

### ANO 3 (2028) — Aceleração | +25 projetos | R$ 45,1M
```
□ Plataforma IA v2: manutenção preditiva + dispatch automático (R$ 100k)
□ Lançar FIDC (R$ 80–150M)
□ Substituir analistas SCADA manuais pela plataforma IA
□ Iniciar licenciamento da plataforma para terceiros
□ Habilitação BESS para ancilares CCEE
```

### ANO 4 (2029) — Escala | +35 projetos | R$ 85M
```
□ Motor Transfer: 10–15 cessões/vendas/ano
□ Plataforma IA com 80+ projetos monitorados — dados proprietários únicos
□ Presença nacional (5+ estados)
□ Conselho de Administração com 2+ independentes
```

### ANO 5 (2030) — Liderança | +45 projetos | R$ 159,8M
```
□ AUM > R$ 787M — valuation próximo de R$ 1B
□ Plataforma IA: monetização via licenciamento (R$ 1,5M/ano)
□ Iniciar conversas exploratórias com compradores
□ Investment bank para valuation (pre-deal)
```

### ANO 6 (2031) — Preparação para Saída | +50 projetos | R$ 205M
```
□ Advisor sell-side
□ VDD + Information Memorandum
□ Plataforma IA como ativo de PI destacado no IM
□ Aumentar WALE > 13 anos (renovar contratos)
□ Auditoria Big 4 — 3º ano consecutivo
```

### ANO 7 (2032) — Evento de Saída | R$ 267M | Valuation R$ 1B+
```
□ M&A sell-side competitivo
□ Binding Bids + negociação SPA
□ Plataforma IA + dados de 227 projetos = ativo intelectual no deal
□ Earn-out: 10–15% contingente a 2 anos
```

---

## 13. TESE DE SAÍDA

### 13.1 Valuation

| Método | Base | Múltiplo | Valuation |
|--------|------|----------|-----------|
| EV/EBITDA (WALE ~12a, 15a contratos) | R$ 208,7M | 12× | R$ 2,50B |
| EV/AUM | R$ 1,407B | 0,72× | R$ 1,01B |
| EV/Receita Recorrente | R$ 48M | 20× | R$ 960M |
| **Consenso conservador** | | | **R$ 1,0B – R$ 1,3B** |

### 13.2 Perfil de Compradores

| Tipo | Exemplos | Múltiplo | Motivação |
|------|----------|----------|-----------|
| Utility nacional | Engie, EDP, CPFL | 12–15× | Plataforma + 227 clientes + IA |
| Utility internacional | Enel X, Iberdrola | 11–14× | Entrada BR + tecnologia |
| Fundo infraestrutura | Brookfield, Pátria | 9–12× | Cash flow 15 anos+ |
| PE energético | BTG Energia, Kinea | 10–12× | Crescimento + PI |

---

## 14. RISCOS E MITIGAÇÕES

| Risco | Prob. | Impacto | Mitigação |
|-------|-------|---------|----------|
| Cliente não aceita 15 anos | Média | Alto | Economia R$11M é argumento central |
| Yield spread fino vs CDI+3% | Alta | Crítico | Pitch yield 18,17%/ano para family offices |
| O&M subestimado | Baixa | Médio | IA preditiva reduz surpresas + contingência |
| Plataforma IA não se desenvolve | Baixa | Médio | MVP em Ano 2; fallback: SaaS terceiro |
| Overhead cresce > receita | Média | Alto | Contratação vinculada a projetos assinados |
| Comprador não aparece Ano 7 | Baixa | Crítico | 3 formatos de saída; 15+ compradores |

---

## 15. KPIs — REVISÃO TRIMESTRAL

| KPI | Ano 2 | Ano 4 | Ano 5 | Ano 7 |
|-----|-------|-------|-------|-------|
| Receita Total | R$ 15M | R$ 85M | R$ 160M | R$ 267M |
| EBITDA | R$ 7,5M | R$ 60M | R$ 122M | R$ 209M |
| Margem EBITDA | 50% | 71% | 76% | 78% |
| Projetos no portfólio | 22 | 82 | 127 | 227 |
| AUM | R$ 136M | R$ 508M | R$ 787M | R$ 1,41B |
| Yield ao investidor (maduro) | 17,0% | 17,5% | 18,0% | 18,17% |
| IRR ao investidor | ~15% | ~16% | ~16,8% | ~17,0% |
| Spread vs CDI+3% (yield) | +0,75 p.p. | +1,25 p.p. | +1,75 p.p. | +1,92 p.p. |
| O&M como % receita BOT | 11,4% | 6,5% | 5,5% | 5,2% |
| Uptime médio portfólio | 96% | 98% | 99% | 99,2% |
| WALE médio contratos | 14 anos | 13 anos | 13 anos | 12 anos |
| Projetos monitorados por IA | 0 | 82 | 127 | 227 |
| NPS clientes | 55 | 65 | 72 | 78 |

---

## 16. PRÓXIMOS 90 DIAS

### Sprint 1 (Semanas 1–4): Jurídico e Modelagem
- [ ] Holding + modelo SPE
- [ ] Contrato BOT: 15 anos, taxa saída R$ 800k, O&M do projeto antes do split
- [ ] Modelo financeiro: yield 18,17%, IRR 17%, O&M com IA explícito

### Sprint 2 (Semanas 3–8): Captação e Tecnologia
- [ ] Pitch deck: 1,514%/mês, IRR 17%, 2,67× capital em 15 anos
- [ ] Iniciar arquitetura da plataforma IA de monitoramento
- [ ] SPE piloto com 1º investidor real

### Sprint 3 (Semanas 5–12): Pipeline
- [ ] Qualificar 15–20 oportunidades
- [ ] MVP da calculadora BOT + simulador de yield
- [ ] Parceiro SCADA para fase 1 (antes da IA própria)

---

## 17. GLOSSÁRIO

| Termo | Definição |
|-------|----------|
| **BOT** | Build-Operate-Transfer: construir, operar 15 anos, retirar |
| **O&M** | Operação e manutenção — custo do projeto, antes do split |
| **IA de Monitoramento** | Plataforma própria: detecção de anomalias + manutenção preditiva + dispatch automático |
| **EBITDA do Projeto** | Receita BOT menos O&M — base para split 90/10 |
| **WALE** | Weighted Average Life: prazo médio ponderado restante dos contratos |
| **IRR** | Taxa Interna de Retorno — considera timing e valor do dinheiro |
| **Yield** | Retorno anual cash-on-cash — métrica principal para o investidor |
| **Motor Transfer** | Reciclagem de ativos: cessão de recebíveis ou venda de SPE madura |
| **Taxa de Saída** | R$ 800k ao final do contrato = custo operacional de retirada |
| **Second Life BOT** | Segundo ciclo: custo zero, EBITDA 100% empresa, tarifa inflacionada |
| **CDI+3%** | Custo de capital referência: 13,25% + 3% = 16,25% a.a. |
| **FIDC** | Fundo de Investimento em Direitos Creditórios |

---

*Versão 7.0 — Maio/2026 | Confidencial*
*Contrato: 15 anos | O&M maduro com IA: R$ 5.750/projeto/mês*
*Investidor: yield 18,17%/ano | IRR ~17,0% > CDI+3% ✓ | 2,67× capital em 15 anos*
*WALE saída: ~12 anos | Plataforma IA: ativo intelectual proprietário*
