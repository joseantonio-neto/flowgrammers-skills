---
name: persona
description: Gera personas de usuário baseadas em dados para pesquisa de UX e design de produto. Uso: /persona generate [opções]
---

# /persona

Gera personas de usuário estruturadas com dados demográficos, objetivos, pontos de dor e padrões comportamentais.

## Uso

```
/persona generate                                            Gera persona (interativo)
/persona generate json                                       Gera persona em formato JSON
```

## Formato de Entrada

O modo interativo solicita o contexto do produto. Alternativamente, forneça o contexto diretamente:

```
/persona generate
> Produto: Ferramenta de gestão de projetos B2B
> Público-alvo: Gerentes de engenharia em empresas de médio porte
> Problema principal: Visibilidade entre times
```

## Exemplos

```
/persona generate
/persona generate json
/persona generate json > persona-gerente-eng.json
```

## Scripts
- `product-team/ux-researcher-designer/scripts/persona_generator.py` — Gerador de persona (argumento posicional `json` para saída JSON)

## Referência de Skill
> `product-team/ux-researcher-designer/SKILL.md`
