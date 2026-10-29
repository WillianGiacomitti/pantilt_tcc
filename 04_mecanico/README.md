# Numeração das peças

As peças e montagens próprias do projeto seguem o padrão:

```
PTU-GG-PP_DESCRICAO_RNN
```

| Campo | Significado |
|---|---|
| `PTU` | Prefixo do projeto (*Pan-Tilt Unit*) |
| `GG` | Subconjunto ao qual a peça pertence |
| `PP` | Número da peça dentro do subconjunto (`00` = montagem do subconjunto) |
| `DESCRICAO` | Nome curto da peça, em maiúsculas e separado por hífen |
| `RNN` | Revisão (`R00` = primeira versão, `R01` = primeira alteração, ...) |

Componentes comerciais e modelos de fornecedores usam o prefixo `STD_` e ficam em `02_componentes_comerciais/`.

## Subconjuntos (`GG`)

| GG | Subconjunto | Montagem |
|---|---|---|
| `00` | Montagem principal | `PTU_00-00_MONTAGEM-PRINCIPAL` |
| `10` | Eixo pan (base giratória, rolamento e engrenagens) | — |
| `20` | Eixo tilt (vigas, apoios e engrenagens) | — |
| `30` | Suporte do módulo multimodal | `PTU-30-00_MONTAGEM-MODULO` |
| `40` | Encoder AS5600 no motor NEMA17 | `PTU-40-00_MONTAGEM_AS5600` |
| `50` | Prensa-cabo | `PTU-50-00_MONTAGEM-PRENSA-CABO` |
| `60` | Base fixa | `PTU-60-00_MONTAGEM-BASE-FXA` |
| `70` | Peças de teste | — |

Exemplo: `PTU-10-02_ENGRENAGEM-PAN-17-DENTES_R01` é a peça 02 do eixo pan (engrenagem de 17 dentes), na revisão 01.
