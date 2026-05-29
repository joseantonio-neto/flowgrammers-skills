---
name: okr
description: Gera cascatas de OKRs a partir da estratégia da empresa até os objetivos de time. Uso: /okr generate <estratégia>
---

# /okr

Gera frameworks de OKRs em cascata desde o nível estratégico da empresa até os key results de cada time.

## Uso

```
/okr generate <estratégia>                                   Gera cascata de OKRs
```

Estratégias suportadas: `growth`, `retention`, `revenue`, `innovation`, `operational`

## Formato de Entrada

Passe uma palavra-chave de estratégia diretamente. O gerador produz OKRs no nível da empresa, do departamento e do time, alinhados à estratégia escolhida.

## Exemplos

```
/okr generate growth
/okr generate retention
/okr generate revenue
/okr generate innovation
/okr generate operational
/okr generate growth --json
```

## Scripts
- `product-team/product-strategist/scripts/okr_cascade_generator.py` — Gerador de cascata de OKRs (`<estratégia> [--teams "A,B,C"] [--contribution 0.3] [--json]`)

## Referência de Skill
> `product-team/product-strategist/SKILL.md`
