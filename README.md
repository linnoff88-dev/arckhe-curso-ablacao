# âœ‚ï¸ Auditoria de AblaÃ§Ã£o â€” curso INEMA

Curso HTML self-contained (formato INEMA.CLUB dark Ã¢mbar, camada de aprendizagem v2) que ensina a auditar e enxugar a prÃ³pria configuraÃ§Ã£o do Claude Code â€” `CLAUDE.md`, skills e hooks â€” pelo mÃ©todo de **ablaÃ§Ã£o**.

**Curso online:** https://inematds.github.io/curso-ablacao/

> Toda linha da sua configuraÃ§Ã£o Ã© **culpada de complexidade atÃ© provar utilidade**.
> Mas o objetivo nÃ£o Ã© cortar o mÃ¡ximo: Ã© maximizar **qualidade + autonomia + verificabilidade Ã· complexidade**.

## Para quem

Quem **jÃ¡ usa Claude Code** e acumulou config prÃ³pria. NÃ£o Ã© curso de introduÃ§Ã£o ao Claude Code.

**PrÃ©-requisitos:** Claude Code em uso; pelo menos um `CLAUDE.md` (global ou de projeto) e/ou skills prÃ³prias; noÃ§Ã£o bÃ¡sica de git e terminal.

## Estrutura

4 trilhas Â· 8 mÃ³dulos Â· 48 tÃ³picos Â· ~6h30

| Trilha | MÃ³dulos | Pergunta que responde |
|---|---|---|
| **1. Por que apagar** (emerald) | 1.1 ConfiguraÃ§Ã£o envelhece Â· 1.2 O mÃ©todo de ablaÃ§Ã£o | Por que uma config que funcionava virou peso morto? |
| **2. Como diagnosticar** (blue) | 2.1 A taxonomia Â· 2.2 De microgerenciamento a critÃ©rio e verificaÃ§Ã£o | Como dizer o que fica, o que sai e o que precisa de teste? |
| **3. Auditar de verdade** (purple) | 3.1 Rodando a skill `audit-ablacao` Â· 3.2 Do relatÃ³rio aos cortes | Como rodar a auditoria e transformar o relatÃ³rio em cortes seguros? |
| **4. Provar e manter** (amber) | 4.1 O plano de ablaÃ§Ã£o A/B/C Â· 4.2 O ciclo contÃ­nuo | Como provar que a versÃ£o mÃ­nima nÃ£o piorou â€” e manter assim? |

Cada mÃ³dulo tem 6 tÃ³picos, exercÃ­cio prÃ¡tico na **sua prÃ³pria config** e critÃ©rio de saÃ­da verificÃ¡vel.

## Projeto final

Quatro entregÃ¡veis sobre a sua configuraÃ§Ã£o: (1) relatÃ³rio da skill com as 10 seÃ§Ãµes; (2) `CLAUDE.md` antes/depois com diff; (3) tabela A/B/C com â‰¥2 tarefas reais; (4) polÃ­tica de ablaÃ§Ã£o pessoal.

**AprovaÃ§Ã£o:** os 4 itens existem; toda remoÃ§Ã£o aplicada tem trecho citado + risco + como testar; toda instruÃ§Ã£o devolvida tem falha repetida registrada; a versÃ£o final tem pelo menos uma verificaÃ§Ã£o objetiva onde antes nÃ£o havia nenhuma.

## Skill que o curso ensina a usar

[`inematds/audit-ablacaocc`](https://github.com/inematds/audit-ablacaocc) â€” skill de diagnÃ³stico (somente leitura) que audita `CLAUDE.md`, skills e hooks, classifica cada instruÃ§Ã£o e propÃµe uma versÃ£o mÃ­nima, sem tocar em nenhum arquivo.

## Estrutura de arquivos

```
curso-ablacao/
â”œâ”€â”€ index.html                  # landing do curso
â”œâ”€â”€ assets/
â”‚   â”œâ”€â”€ learn.css               # camada de aprendizagem (temas, prose, controles)
â”‚   â”œâ”€â”€ learn.js                # window.INEMA (progresso, dÃºvida, notas, jornada)
â”‚   â””â”€â”€ curso.css               # base v1 + light mode completo
â”œâ”€â”€ curso/
â”‚   â”œâ”€â”€ trilha1/  index.html + modulo-1-1.html + modulo-1-2.html
â”‚   â”œâ”€â”€ trilha2/  index.html + modulo-2-1.html + modulo-2-2.html
â”‚   â”œâ”€â”€ trilha3/  index.html + modulo-3-1.html + modulo-3-2.html
â”‚   â””â”€â”€ trilha4/  index.html + modulo-4-1.html + modulo-4-2.html
â”œâ”€â”€ capa/capa.png               # capa 1280x720
â”œâ”€â”€ doc/                        # plano do curso, contrato de pÃ¡gina e material de base
â””â”€â”€ .github/workflows/pages.yml # deploy do GitHub Pages via Actions
```

Sem build, sem backend, sem framework: HTML + Tailwind via CDN + JS inline. Abre atÃ© em `file://`.

## CrÃ©ditos

MÃ©todo e visÃ£o: **Boris Cherny** (Anthropic), palestra na Y Combinator sobre o corte de 80% do prompt de sistema do Claude Code. Resumos e material de base em [`doc/`](doc/). Curso montado pelo INEMA no formato `formato-curso-v2`.

<!-- inema-backlink:v1 -->
## Mais no INEMA.CLUB

- [Ficha completa deste curso](https://www.inema.club/cursos/234-auditoria-de-ablacao-enxugue-seu-claude-code-sem-perder-qualidade/)
- [Guia: como aprender inteligÃªncia artificial](https://www.inema.club/aprender-inteligencia-artificial/)
- [Todos os cursos](https://www.inema.club/cursos/)
<!-- /inema-backlink:v1 -->

---

Projeto adaptado da comunidade INEMA TDS - Marca Arckhe