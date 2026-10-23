# doc-cadernos-conhecimento-ses-df

**Tipo:** D — Documento
**ID:** D04
**Versão:** v1.0 — 2026-10-23
**Visibilidade:** Público
**Mantenedor:** victorarimatea
**Projeto de origem:** Carteira de Serviços Hospitalares da SES-DF — CICS (Central Integrada de Comando em Saúde)

---

## Descrição

Coleção de **cadernos de conhecimento** para gestores da rede hospitalar da Secretaria de Estado de Saúde do Distrito Federal (SES-DF). Cada caderno explica um instrumento ou conceito do SUS — o que é, como funciona, por que importa para a gestão hospitalar e como não errar na leitura — num formato padronizado e com procedência visível de cada afirmação.

Os cadernos alimentam o grupo **Conhecimento** da ferramenta de consulta da Carteira de Serviços e formam, junto com as normas transcritas, uma wiki de estudo: caderno, norma, conceito e dossiê de estudo, ligados entre si.

**Material de estudo.** Não substitui a publicação oficial das normas citadas nem orientação jurídica institucional.

---

## Estrutura

```
doc-cadernos-conhecimento-ses-df/
├── README.md                  Este arquivo
├── INDICE.md                  Mapa de todos os arquivos
├── backlog-versoes.md         Histórico de versões do repositório
├── MODELO-CADERNO.md          Modelo de caderno v1.0 — regra de escrita, apresentação, versionamento e conferência
├── vocabulario-controlado.md  Conceitos com definição curta, sinônimos e caderno principal (rascunho)
└── cadernos/
    └── renases/               Caderno RENASES (v0.2, rascunho) + dossiê de estudo
```

---

## Cadernos

| Caderno | Situação | Versão | Pasta |
|---|---|---|---|
| RENASES — Relação Nacional de Ações e Serviços de Saúde | Rascunho; reescrita no modelo v1.0 em andamento | v0.2 | [`cadernos/renases/`](./cadernos/renases/) |
| SIGTAP | Publicado na ferramenta (v0.3.10); a migrar para este repositório no modelo v1.0 | — | — |
| Carteira de serviços e Carta de Serviços | Publicado na ferramenta; a migrar | — | — |
| CNES | Publicado na ferramenta; a migrar (caderno formal em elaboração) | — | — |
| Rede hospitalar do DF | Publicado na ferramenta; a migrar | — | — |

---

## Regras principais (detalhe em `MODELO-CADERNO.md`)

- **Caderno ensina; não emite parecer.** Interpretação do projeto só no destaque "Leitura do projeto", com rótulo fixo e no máximo dois por caderno.
- **Toda afirmação tem procedência.** Norma, dado oficial, literatura, decisão judicial (com a força: vinculante, orientativa ou isolada) ou leitura do projeto.
- **Orientação de natureza jurídica** só entra referenciada na orientação jurídica institucional que a sustenta.
- **Um conteúdo, um lugar.** Normas vêm de [`doc-governanca-ses-df`](https://github.com/victorarimatea/doc-governanca-ses-df), sem cópia; dados da rede aparecem só dentro da ferramenta, nunca no texto dos cadernos.
- **Conferência obrigatória** dos cadernos a cada mudança estrutural da ferramenta.

---

## Repositórios relacionados

| Repositório | Relação |
|---|---|
| [doc-governanca-ses-df](https://github.com/victorarimatea/doc-governanca-ses-df) (D01) | Fonte das normas transcritas citadas pelos cadernos |
| [skl-transcricao-documental](https://github.com/victorarimatea/skl-transcricao-documental) (S05) | Padrão de transcrição das normas |

---

## Navegação rápida

→ **[INDICE.md](./INDICE.md)** — mapa completo de todos os arquivos
→ **[MODELO-CADERNO.md](./MODELO-CADERNO.md)** — como um caderno é feito

---

*Repositório mantido pela CICS/SES-DF — github.com/victorarimatea*
