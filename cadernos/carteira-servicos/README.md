# Caderno da Carteira de Serviços

| Campo | Valor |
|---|---|
| Finalidade | Base de estudo e pesquisa sobre carteira de serviços: conceitos, normas nacionais e do DF, exemplos, estrutura mínima de uma carteira, instrumentos relacionados, fontes e alertas |
| Público | Gestores e equipes do projeto; também lido por ferramentas que montam a aplicação |
| Capítulo que alimenta | Conhecimento · Carteira e Carta de Serviços (rota `#k-carteira`) |
| Versão vigente | v1.2 · 26/09/2026 |
| Situação | Aprovado; revisão menor pendente |
| Alinhamento com a ferramenta | **Parcial.** O capítulo tem o Decreto DF nº 36.419/2015 (Carta de Serviços ao Cidadão) e o histórico de oito Cartas de Serviços (2015 a 2026), que o caderno não tem. O caderno é bem mais amplo que o capítulo |

## Arquivos

- [`caderno.md`](caderno.md) — texto do caderno (registros com identificador fixo: CON, NOR, EXE, CMP, REL, FON, ALE, PEN, GOV).
- [`proposta-grafica.md`](proposta-grafica.md) — como o capítulo aparece hoje na ferramenta.
- [`CHANGELOG.md`](CHANGELOG.md) — registro de alterações.

## Normas usadas

A lista completa está na seção 2 do próprio caderno (registros NOR, com situação de verificação de cada uma). Nenhuma delas está transcrita no repositório de governança documental, exceto o Decreto nº 7.508/2011 e a Portaria GM/MS nº 841/2012, transcritos para o caderno de RENASES.

## Pendências

Fila de pendências do Project:
- `claude/backlog/2026-10-22_caderno-cnes.md`: "Caderno da Carteira — Cartas de Serviços e Decreto DF 36.419/2015".
- `claude/backlog/2026-10-22_cadernos-renases-cnes.md`: "Ajuste no caderno da Carteira de Serviços (referências à RENASES)". As duas devem sair na mesma versão (v1.3).

## Conferências com a ferramenta

### v0.4.0 da ferramenta (em teste), 27/10/2026: mudança estrutural
- **O que mudou:** a v0.4.0 acrescenta o registro do 2º ciclo por serviço, com o grupo "Registro · 2º ciclo" no menu e as rotas `#reg`, `#reg-carteira`, `#reg-s-<serviço>`, `#reg-pend`, `#reg-revisao`, `#reg-central` e `#reg-cards`. O capítulo "Carteira e Carta de Serviços" (`#k-carteira`) continua com o texto da v0.3.10, ainda sem caderno-fonte ligado.
- **Humana (checklist da seção 6.1 do modelo):**
  - O caderno não descreve caminho de tela, nome de plano ou campo da ferramenta afetado pela mudança.
  - O caderno não tem bloco "Nesta ferramenta".
- **Resultado:** sem quebra.
- **Lacuna de conteúdo (para a v1.3, junto com as duas pendências acima):** o caderno não trata do 2º ciclo de revisão da carteira nem do modelo agrupamento → serviço → item. O conteúdo está nas notas da lista operacional do 2º ciclo (Project, versões 0.1 e 0.2). Entra no caderno quando o Victor aprovar o 2º ciclo após o teste com a unidade.

## Origem

Google Doc "cap-carteira-servicos_base-estudo-pesquisa" da pasta de conhecimento do projeto no Drive, exportado para Markdown em 22/10/2026. Este arquivo substitui a cópia antiga que ficava em `data/cap/cap_carteira.md` no repositório da ferramenta (mesmo conteúdo, formatação diferente; o histórico do Git acompanha a mudança de lugar). O Google Doc foi movido para a pasta de substituídos do Drive.
