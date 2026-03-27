# Legislación Española de Arrendamientos

Repositorio público con legislación española relevante para contratos de arrendamiento de vivienda, estructurado para su indexación con [btca](https://btca.dev).

## Estructura

```
lau/                        Ley de Arrendamientos Urbanos (LAU)
  reformas/                 Reformas principales (RDL 7/2019, Ley 12/2023)
codigo-civil/               Código Civil — artículos relevantes
decretos-reales/            Reales Decretos y normativa complementaria
comunidades-autonomas/      Regulación autonómica por comunidad
jurisprudencia/             Resúmenes de jurisprudencia clave
```

## Uso con btca

### Cloud

Añadir este repositorio como recurso en el panel de btca con el nombre `spanish-rental-law`.

### Local (CLI)

```bash
btca add -n spanish-rental-law https://github.com/Eudamoney/spanish-rental-law
btca ask -r spanish-rental-law -q "¿Cuál es la duración mínima de un contrato de vivienda habitual?"
```

## Fuentes

- [BOE — Ley 29/1994 de Arrendamientos Urbanos](https://www.boe.es/buscar/act.php?id=BOE-A-1994-26003)
- [BOE — Real Decreto-ley 7/2019](https://www.boe.es/buscar/act.php?id=BOE-A-2019-3108)
- [BOE — Ley 12/2023 por el derecho a la vivienda](https://www.boe.es/buscar/act.php?id=BOE-A-2023-12203)
- [BOE — Código Civil](https://www.boe.es/buscar/act.php?id=BOE-A-1889-4763)

## Licencia

El contenido legislativo es de dominio público. La estructura y notas interpretativas se publican bajo [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
