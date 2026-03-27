# Legislación Española de Arrendamientos

Repositorio público con legislación española relevante para contratos de arrendamiento de vivienda, estructurado para su indexación con [btca](https://btca.dev).

## Estructura

```
lau/                        Ley de Arrendamientos Urbanos (LAU 29/1994)
  reformas/                 Reformas principales (RDL 7/2019, Ley 12/2023)
codigo-civil/               Código Civil — arrendamientos, fianzas, obligaciones
enjuiciamiento-civil/       Ley 1/2000 (LEC) — procedimientos de desahucio
consumidores/               RDL 1/2007 — cláusulas abusivas y protección contractual
decretos-reales/            IRAV, IPC rent caps, certificado energético
comunidades-autonomas/      Depósito de fianzas por comunidad autónoma
jurisprudencia/             Sentencias clave del Tribunal Supremo
```

## Contenido

| Ley | Estado |
|-----|--------|
| Ley 29/1994, de Arrendamientos Urbanos (LAU) | Texto consolidado completo (5 títulos + disposiciones) |
| Código Civil (arrendamientos, fianzas, obligaciones) | Artículos relevantes verbatim del BOE |
| Ley 1/2000, de Enjuiciamiento Civil (LEC) | Artículos de desahucio y procedimiento arrendaticio |
| RDL 1/2007, Consumidores y Usuarios | Cláusulas abusivas y protección contractual |
| Ley 12/2023, por el Derecho a la Vivienda | Texto completo de la reforma |
| RDL 7/2019 (reforma LAU) | Texto completo |
| Resolución IRAV 2024 | Índice de referencia para actualización de rentas |
| RDL 6/2022, Art. 46 | Limitación extraordinaria IPC |
| RD 235/2013 | Certificación energética |
| Regulación autonómica | 5 comunidades: Cataluña, Madrid, Andalucía, Valencia, País Vasco |
| Jurisprudencia | 5 áreas: cláusulas abusivas, desahucios, fianzas, reparaciones, resolución anticipada |

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
- [BOE — Ley 1/2000 de Enjuiciamiento Civil](https://www.boe.es/buscar/act.php?id=BOE-A-2000-323)
- [BOE — RDL 1/2007 Consumidores y Usuarios](https://www.boe.es/buscar/act.php?id=BOE-A-2007-20555)
- [BOE — Ley 12/2023 por el derecho a la vivienda](https://www.boe.es/buscar/act.php?id=BOE-A-2023-12203)
- [BOE — Real Decreto-ley 7/2019](https://www.boe.es/buscar/act.php?id=BOE-A-2019-3108)
- [BOE — Código Civil](https://www.boe.es/buscar/act.php?id=BOE-A-1889-4763)
- [CENDOJ — Buscador de jurisprudencia](https://www.poderjudicial.es/search/)

## Licencia

El contenido legislativo es de dominio público. La estructura y notas interpretativas se publican bajo [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
