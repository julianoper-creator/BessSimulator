# Estrutura Operacional — Viabilização por Fase
## Modelo BOT de Energia | Headcount, Remuneração e Investimentos

---

> **Referência salarial**: valores CLT. Custo real empresa ≈ **1,65× o salário bruto**
> (FGTS + férias + 13º + INSS patronal + benefícios).
> Exemplo: salário R$10.000 → custo empresa ~R$16.500/mês.

> **Modelo de execução**: híbrido. EPC e O&M de campo são majoritariamente
> **terceirizados**. A empresa gerencia, supervisiona e opera a plataforma de IA.
> O crescimento de headcount não é linear ao portfólio — é o modelo asset-light.

---

## INTERNO vs TERCEIRIZADO — VISÃO GERAL

```
┌─────────────────────────────────┬────────────────────────────────────┐
│  INTERNO (nossa equipe)         │  TERCEIRIZADO                      │
├─────────────────────────────────┼────────────────────────────────────┤
│  EPC:                           │  EPC:                              │
│  • Gestão do projeto (PM)       │  • Equipe civil e estrutural       │
│  • Engenharia e projetos        │  • Eletricistas certificados       │
│  • Procurement / compras        │  • Logística e içamento            │
│  • Fiscalização de obra         │  • Comissionamento especializado   │
├─────────────────────────────────┼────────────────────────────────────┤
│  O&M:                           │  O&M:                              │
│  • Plataforma IA (monitoramento)│  • Visitas preventivas de campo    │
│  • Supervisão regional          │  • Limpeza e inspeção              │
│  • Dispatch e escalação         │  • Manutenção corretiva            │
│  • Gestão de contratos O&M      │  • Troca de inversores/baterias    │
│  • 20 técnicos próprios         │  • Rotas em regiões remotas        │
│    (resposta rápida/âncora)     │                                    │
└─────────────────────────────────┴────────────────────────────────────┘
```

---

## PLATAFORMA IA DE MONITORAMENTO — DETALHAMENTO

```
  FLUXO SEM IA (manual):                FLUXO COM IA (automático):
  Sensor → SCADA → Analista →          Sensor → IA → Alerta →
  Decisão → Técnico acionado            OS criada → Técnico acionado
  R$500/proj/mês | 6 analistas          R$150/proj/mês | 1 analista

  O QUE A PLATAFORMA FAZ:
  1. Ingestão contínua de telemetria (tensão, corrente, SOC, temperatura)
  2. Detecção de anomalias via ML (séries temporais + benchmarking)
  3. Manutenção preditiva: "falha em 18 dias" → agenda visita preventiva
  4. Dispatch automático: anomalia → OS → técnico terceirizado notificado
  5. Dashboard tempo real: cliente + investidor + gestão interna
  6. Relatórios mensais automatizados por SPE
  7. Uptime: 98% → 99,2%

  ROADMAP DE DESENVOLVIMENTO:
  Ano 2: MVP — telemetria + alertas + dashboard    R$ 150.000
  Ano 3: V2  — preditiva + dispatch automático     R$ 100.000
  Ano 4+: manutenção e evolução                    R$  50.000/ano
  Total investimento: R$ 300.000

  IMPACTO FINANCEIRO (227 projetos, Ano 7):
  Economia O&M/projeto/mês:  R$ 7.100 → R$ 5.750 = -R$ 1.350
  Economia total/ano:        R$ 1.350 × 227 × 12  = R$ 3.676.200
  Economia analistas:        5 pessoas × R$ 148.5k = R$   742.500
  Total economia anual:                             R$ 4.418.700
  Payback do investimento:   R$ 300k ÷ R$ 4,4M/ano = < 1 mês

  VALOR ESTRATÉGICO ADICIONAL:
  • Dados de 227 projetos × 15 anos = ativo de PI único no setor
  • Licenciamento para terceiros: R$ 1,5M (Ano 5) → R$ 8M (Ano 7)
  • Argumento de venda no exit: barreira de entrada tecnológica
```

---

## FASE 1 — ANO 1 (2026)
### 5 projetos | R$ 5,6M receita | 8 pessoas

```
                    CEO / Sócio-Fundador
                          │
        ┌─────────────────┼──────────────────────┐
     Comercial        Engenharia/EPC        Financeiro/Jurídico/TI
    (1 KAM Sênior)    (2 Engenheiros)       (Adv. + Financ. + Dev)
                           │
                     O&M (1 Técnico)
```

| Cargo | Qtd | Salário Bruto | Custo Empresa/mês | Custo Anual | Quando |
|-------|-----|--------------|-------------------|------------|--------|
| CEO / Sócio-Fundador | 1 | R$ 15.000 | R$ 24.750 | R$ 297.000 | Dia 1 |
| Engenheiro Sênior EPC | 1 | R$ 13.000 | R$ 21.450 | R$ 257.400 | Dia 1 |
| Engenheiro Pleno EPC | 1 | R$ 9.000 | R$ 14.850 | R$ 178.200 | Mês 1 |
| KAM / Comercial Sênior | 1 | R$ 9.000 + comissão | R$ 14.850 | R$ 178.200 | Dia 1 |
| Advogado de Energia | 1 | R$ 12.000 | R$ 19.800 | R$ 237.600 | Mês 1 |
| Analista Financeiro | 1 | R$ 6.000 | R$ 9.900 | R$ 118.800 | Mês 2 |
| Dev / TI (plataforma IA) | 1 | R$ 10.000 | R$ 16.500 | R$ 198.000 | Mês 1 |
| Técnico O&M | 1 | R$ 5.000 | R$ 8.250 | R$ 99.000 | Mês 3 |
| **TOTAL** | **8** | **R$ 79.000** | **R$ 130.350** | **R$ 1.564.200** | |

**Comissão comercial:** 0,5% do ticket EPC fechado

### Investimentos Não-Pessoal — Ano 1

| Item | Valor | Tipo |
|------|-------|------|
| Constituição jurídica (holding + modelo SPE) | R$ 35.000 | Único |
| Contrato BOT padrão (assessoria especializada) | R$ 40.000 | Único |
| ERP financeiro (Omie) | R$ 4.000/mês | Recorrente |
| CRM (HubSpot) | R$ 800/mês | Recorrente |
| SCADA básico (pré-IA) — setup + licença | R$ 60.000 | Único |
| Início desenvolvimento plataforma IA (Ano 1) | R$ 50.000 | Único |
| Computadores + periféricos (8 pessoas) | R$ 72.000 | Único |
| Escritório — aluguel + setup | R$ 6.000/mês | Recorrente |
| Veículo O&M (1 picape) | R$ 90.000 | Único |
| Ferramentas e equipamentos O&M | R$ 25.000 | Único |
| Certificações técnicas (NR10, NR35, ANEEL) | R$ 15.000 | Único |
| Marketing — website + materiais + pitch deck | R$ 35.000 | Único |
| Seguros empresariais | R$ 18.000 | Anual |
| Linha de capital de giro (banco) | R$ 3.000.000 | Crédito |
| **Total investimento (único)** | **R$ 422.000** | |
| **Total custo recorrente/ano** | **R$ 166.800** | |

---

## FASE 2 — ANO 2 (2027)
### +15 projetos | R$ 15M receita | 18 pessoas

### Novas Contratações — Ano 2

| Cargo | Qtd | Salário Bruto | Custo Empresa/mês | Custo Anual |
|-------|-----|--------------|-------------------|------------|
| CFO | 1 | R$ 22.000 | R$ 36.300 | R$ 435.600 |
| Diretor Comercial | 1 | R$ 18.000 | R$ 29.700 | R$ 356.400 |
| KAM / Comercial Pleno | 2 | R$ 7.500 + comissão | R$ 24.750 | R$ 297.000 |
| Analista Pré-Venda | 1 | R$ 5.500 | R$ 9.075 | R$ 108.900 |
| Coordenador EPC | 1 | R$ 11.000 | R$ 18.150 | R$ 217.800 |
| Engenheiro Pleno (2º) | 1 | R$ 9.000 | R$ 14.850 | R$ 178.200 |
| Supervisor O&M | 1 | R$ 8.500 | R$ 14.025 | R$ 168.300 |
| Técnico O&M (2º e 3º) | 2 | R$ 5.000 | R$ 16.500 | R$ 198.000 |
| Dev Sênior (plataforma IA) | 1 | R$ 14.000 | R$ 23.100 | R$ 277.200 |
| **Total novas** | **11** | | **R$ 186.450** | **R$ 2.237.400** |

**Total equipe Ano 2 (18 pessoas):** ~R$ 315.000/mês → R$ 3.780.000/ano

### Investimentos Não-Pessoal — Ano 2

| Item | Valor | Tipo |
|------|-------|------|
| **MVP Plataforma IA (conclusão)** | **R$ 150.000** | Único |
| Expansão SCADA (novos projetos) | R$ 40.000 | Único |
| Upgrade ERP (módulo projetos) | R$ 40.000 | Único |
| Veículos O&M (+2 picapes) | R$ 180.000 | Único |
| Escritório regional (1 estado) | R$ 30.000 + R$ 4.000/mês | Misto |
| Computadores + periféricos (11 novos) | R$ 99.000 | Único |
| Estruturação FIDC (legal + advisor) | R$ 200.000 | Único |
| Portal do cliente v1 | R$ 80.000 | Único |
| **Total investimento Ano 2** | **~R$ 819.000** | |

---

## FASE 3 — ANO 3 (2028)
### +25 projetos | R$ 45,1M receita | 35 pessoas

### Novas Contratações — Ano 3

| Cargo | Qtd | Salário Bruto | Custo Empresa/mês | Custo Anual |
|-------|-----|--------------|-------------------|------------|
| Diretor de Operações (COO) | 1 | R$ 20.000 | R$ 33.000 | R$ 396.000 |
| Gerente de Projetos EPC | 2 | R$ 12.000 | R$ 39.600 | R$ 475.200 |
| Engenheiro Pleno EPC | 1 | R$ 9.000 | R$ 14.850 | R$ 178.200 |
| KAM / Comercial (2 novos) | 2 | R$ 7.500 | R$ 24.750 | R$ 297.000 |
| Analista de Marketing | 1 | R$ 6.000 | R$ 9.900 | R$ 118.800 |
| Supervisor O&M Regional | 2 | R$ 9.000 | R$ 29.700 | R$ 356.400 |
| Técnico O&M (4 novos) | 4 | R$ 5.000 | R$ 33.000 | R$ 396.000 |
| **Analista SCADA / IA (1 — único)** | **1** | **R$ 9.000** | **R$ 14.850** | **R$ 178.200** |
| Analista Jurídico | 1 | R$ 5.500 | R$ 9.075 | R$ 108.900 |
| Analista Financeiro (3º) | 1 | R$ 7.000 | R$ 11.550 | R$ 138.600 |
| **Total novas** | **16** | | **R$ 220.275** | **R$ 2.643.300** |

> ⚠️ **Nota SCADA**: com a plataforma IA operacional no Ano 3, **não são contratados
> mais analistas de monitoramento**. 1 analista supervisiona todos os projetos.
> No modelo manual seriam necessários 6 analistas nesta fase.

**Total equipe Ano 3 (35 pessoas):** ~R$ 535.000/mês → R$ 6.420.000/ano

### Investimentos Não-Pessoal — Ano 3

| Item | Valor | Tipo |
|------|-------|------|
| **Plataforma IA v2 — preditiva + dispatch** | **R$ 100.000** | Único |
| Lançamento FIDC (emissão R$80–150M) | R$ 300.000 | Único |
| AMS — Asset Management System | R$ 120.000 | Único |
| Escritórios regionais (+1 estado) | R$ 35.000 + R$ 4.500/mês | Misto |
| Veículos O&M (+3) | R$ 270.000 | Único |
| Auditoria Big 4 (1º ano) | R$ 180.000 | Anual |
| Certificação BESS — CCEE | R$ 30.000 | Único |
| Computadores + periféricos (16 novos) | R$ 144.000 | Único |
| **Total investimento Ano 3** | **~R$ 1.179.000** | |

---

## FASE 4 — ANO 4–5 (2029–2030)
### +35–45 proj/ano | R$ 85–160M | 60–95 pessoas

### Cargos Críticos — Novas Contratações Ano 4–5

| Cargo | Qtd | Salário Bruto | Custo/mês | Observação |
|-------|-----|--------------|-----------|------------|
| CTO | 1 | R$ 25.000 | R$ 41.250 | Ano 4 |
| CMO | 1 | R$ 20.000 | R$ 33.000 | Ano 4 |
| Head de Relações com Investidores | 1 | R$ 18.000 | R$ 29.700 | Ano 4 |
| Gerente Regional O&M | 2 | R$ 12.000 | R$ 39.600 | Ano 4 |
| Dev Pleno — Plataforma IA (2) | 2 | R$ 12.000 | R$ 39.600 | Ano 4 |
| Analista de Dados / BI | 2 | R$ 9.000 | R$ 29.700 | Ano 4 |
| Especialista ESG | 1 | R$ 10.000 | R$ 16.500 | Ano 5 |
| KAM Sênior (3 novos) | 3 | R$ 10.000 + comissão | R$ 49.500 | Ano 4–5 |
| Engenheiro Sênior EPC (2) | 2 | R$ 14.000 | R$ 46.200 | Ano 4 |
| Técnicos O&M (10 novos) | 10 | R$ 5.000 | R$ 82.500 | Ano 4–5 |
| Coordenador de Contratos SPE | 2 | R$ 8.000 | R$ 26.400 | Ano 4 |
| Gerente de RH | 1 | R$ 10.000 | R$ 16.500 | Ano 4 |

> ⚠️ **SCADA/IA**: plataforma escalou automaticamente de 22 para 127 projetos
> sem novas contratações de analistas. Apenas 1 analista sênior supervisiona tudo.

**Total equipe Ano 5 (95 pessoas):** ~R$ 1.650.000/mês → R$ 19.800.000/ano

### Investimentos Não-Pessoal — Ano 4–5

| Item | Valor | Tipo |
|------|-------|------|
| SAP Enterprise (ERP completo) | R$ 350.000 + R$ 120.000/ano | Misto |
| Plataforma IA — evolução e escala | R$ 50.000/ano | Recorrente |
| AMS completo (100+ ativos) | R$ 300.000 | Único |
| Escritórios regionais (+2 estados) | R$ 70.000 + R$ 9.000/mês | Misto |
| Veículos O&M (+8) | R$ 720.000 | Único |
| Sistema ESG reporting | R$ 80.000 | Único |
| Auditoria Big 4 (anual) | R$ 300.000 | Anual |
| Conselho de Administração (2 independentes) | R$ 250.000 | Anual |
| Equity plan (setup jurídico) | R$ 60.000 | Único |
| FIDC 2ª emissão (R$150–300M) | R$ 400.000 | Único |
| Investment bank — pré-valuation (Ano 5) | R$ 150.000 | Único |
| **Total Ano 4–5** | **~R$ 2.880.000** | |

---

## FASE 5 — ANO 6–7 (2031–2032)
### +50 proj/ano | R$ 205–267M | 150–170 pessoas

```
               Conselho de Administração (5 membros)
                              │
                             CEO
                              │
     ┌──────────┬─────────────┬───────────┬──────────┬────────────┐
    CFO        COO          CMO         CTO        CLO        Chief RI
     │          │             │            │          │
  Fin.(12)  EPC(20)    Comercial(15) TI+IA(10)  Jur.(6)
  M&A(3)    O&M(38)    Mkt(5)                   Compliance(2)
             SCADA-IA(1)
             Sup.Reg.(6)
```

### Cargos Críticos — Ano 6–7

| Cargo | Qtd | Salário Bruto | Custo/mês | Observação |
|-------|-----|--------------|-----------|------------|
| Chief Legal Officer | 1 | R$ 28.000 | R$ 46.200 | Ano 6 |
| Head de M&A / Corporate Finance | 1 | R$ 25.000 | R$ 41.250 | Ano 6 |
| Analista M&A | 2 | R$ 12.000 | R$ 39.600 | Ano 6 |
| Compliance Officer | 1 | R$ 14.000 | R$ 23.100 | Ano 6 |
| Gerente de Expansão Regional | 2 | R$ 14.000 | R$ 46.200 | Ano 6 |
| Técnicos O&M (18 novos) | 18 | R$ 5.500 | R$ 163.350 | Ano 6–7 |
| Engenheiros EPC (4 novos) | 4 | R$ 14.000 | R$ 92.400 | Ano 6 |
| Dev Plataforma IA (3 novos) | 3 | R$ 12.000 | R$ 59.400 | Ano 6 |
| Analista de Contratos SPE (3) | 3 | R$ 7.000 | R$ 34.650 | Ano 6 |

> **Analista SCADA no Ano 7: ainda apenas 1 pessoa** monitorando 227 projetos.
> A plataforma IA escalou de 7 para 227 projetos sem nova contratação de analistas.
> Economia acumulada vs modelo manual: ~R$ 5M/ano em salários.

**Total equipe Ano 7 (170 pessoas):** ~R$ 2.900.000/mês → R$ 34.800.000/ano

### Investimentos Não-Pessoal — Ano 6–7 (Preparação para Saída)

| Item | Valor | Tipo |
|------|-------|------|
| Auditoria Big 4 (anual, pré-exit) | R$ 400.000 | Anual |
| Vendor Due Diligence (VDD) | R$ 700.000 | Único |
| **Investment bank sell-side** | **~1,0–1,5% do deal (~R$10–15M)** | No closing |
| Advogados M&A (SPA, CADE) | R$ 600.000 | Único |
| Data Room (Ansarada / Intralinks) | R$ 80.000 | Anual |
| Due diligence técnica / ambiental | R$ 300.000 | Único |
| Renovação contratos (extensão WALE) | R$ 150.000 | Único |
| Consultor ESG / Rating | R$ 120.000 | Único |
| Plataforma IA — evolução + documentação PI | R$ 80.000 | Único |
| Veículos O&M (+6) | R$ 540.000 | Único |
| **Total (ex-IB)** | **~R$ 2.970.000** | |

---

## RESUMO CONSOLIDADO

| Fase | Ano | Pessoas | Custo Pessoal/ano | Analistas SCADA | Overhead Total/ano |
|------|-----|---------|-------------------|-----------------|-------------------|
| Fundação | 1 | 8 | R$ 1,56M | 0 (SCADA básico) | R$ 2,6M |
| Crescimento | 2 | 18 | R$ 3,78M | 0 (IA em dev.) | R$ 5,1M |
| Aceleração | 3 | 35 | R$ 6,42M | **1 (IA ativa)** | R$ 8,7M |
| Escala | 5 | 95 | R$ 19,80M | **1** | R$ 26,4M |
| Saída | 7 | 170 | R$ 34,80M | **1** | R$ 42,7M |

**Economia acumulada da plataforma IA (vs 6 analistas no modelo manual):**
```
  Modelo manual (6 analistas × R$148.5k/ano):  R$ 891.000/ano
  Modelo IA (1 analista × R$148.5k/ano):       R$ 148.500/ano
  Economia anual:                               R$ 742.500/ano
  Economia 5 anos (Ano 3 → Ano 7):             R$ 3.712.500
  + Economia O&M por projeto (R$1.350 × 227 × 12): R$ 3.676.200/ano
  Total economia Ano 7:                         R$ 4.418.700/ano
```

---

## TECNOLOGIA E FERRAMENTAS — STACK COMPLETO

| Categoria | Ferramenta | Fase | Custo/ano |
|-----------|-----------|------|----------|
| **ERP** | Omie (Y1) → SAP B1 (Y3) → SAP S/4 (Y5) | Ano 1 | R$48k→R$200k→R$500k |
| **CRM** | HubSpot (Y1–2) → Salesforce (Y3+) | Ano 1 | R$10k→R$80k |
| **Monitoramento IA** | **Plataforma própria** | **Ano 2** | **R$50k/ano (manutenção)** |
| **AMS** | Desenvolvido internamente | Ano 3 | R$120k impl. |
| **BI / Analytics** | Power BI → Tableau (Y5) | Ano 4 | R$36k |
| **GED** | Google Workspace | Ano 1 | R$12k |
| **Gestão de Projetos** | Monday.com | Ano 1 | R$8k |
| **Assinatura eletrônica** | ClickSign / DocuSign | Ano 1 | R$6k |
| **Data Room M&A** | Ansarada | Ano 6 | R$80k |
| **ESG Reporting** | Plataforma própria integrada à IA | Ano 5 | incluso |
| **Portal do Cliente** | Desenvolvimento próprio + IA | Ano 2 | R$80k impl. |

---

## GOVERNANÇA CORPORATIVA POR FASE

| Mecanismo | Ano 1 | Ano 3 | Ano 5 | Ano 7 |
|-----------|-------|-------|-------|-------|
| Estrutura jurídica | Holding + SPEs | + FIDC SPE | + Debentures | + Comitê M&A |
| Auditoria | Contador externo | Big 4 (1º) | Big 4 (3º) | Big 4 (5º) |
| Conselho | Sócios | + Advisor | + 2 independentes | 5 membros |
| Compliance | Manual interno | Política formal | Compliance Officer | CLO dedicado |
| Equity Plan | — | Esboço | Implementado | Cliff+Vesting ativo |
| Plataforma IA | Em desenvolvimento | MVP ativo | Escalada | PI documentado |

---

## POLÍTICA DE COMISSÕES

| Evento | Comissão | Quem | Quando |
|--------|----------|------|--------|
| Fechamento EPC | 0,5% do ticket | KAM | Na assinatura |
| BOT ativo 12 meses | R$ 5.000 fixo | KAM original | Mês 13 |
| Indicação de investidor | 0,3% do capital | Qualquer funcionário | No aporte |
| Renovação de contrato | 0,2% do valor remanescente | Gestão de conta | Na assinatura |

---

## POLÍTICA DE BENEFÍCIOS (CLT)

| Benefício | Todos | Sênior+ | Diretores+ |
|-----------|-------|---------|------------|
| VR / VA | R$ 1.200/mês | R$ 1.200/mês | R$ 1.200/mês |
| Plano de Saúde | Enfermaria | Apartamento | Apartamento VIP |
| Plano Odontológico | Básico | Completo | Completo |
| Seguro de Vida | R$ 200k | R$ 500k | R$ 1M |
| Gympass | Basic | Plus | Black |
| Celular corporativo | Técnicos e KAMs | Gerentes+ | Todos |
| Carro corporativo | — | — | Diretores Ano 3+ |
| Equity (stock options) | Ano 3+ | Ano 2+ | Ano 1 |

---

*Versão 2.0 — Maio/2026 | Complemento ao Plano de Negócios v7.0*
*Modelo híbrido: gestão interna + execução terceirizada*
*Plataforma IA: 1 analista monitora 227 projetos — economia R$ 4,4M/ano no Ano 7*
*Referências salariais: mercado brasileiro, setor energia/infraestrutura, 2026*
