# Caderno de CNES

| Campo | Valor |
|---|---|
| Finalidade | Explicar ao gestor o que o Cadastro Nacional de Estabelecimentos de Saúde registra, quem atualiza, como consultar e como ler os dados sem confundir cadastro com capacidade real |
| Público | Gestores hospitalares e equipes de apoio da SEGHOSP e da CICS |
| Capítulo que alimenta | Conhecimento · CNES (rota `#k-cnes`) |
| Versão vigente | nenhuma: o caderno está em construção |
| Situação | Etapa 3 de 5 concluída (verificação em fonte primária); próximas: rascunho v0.1 e aprovação |
| Alinhamento com a ferramenta | O capítulo existe na ferramenta desde a v0.2 (26/09/2026) sem caderno de origem. Até o caderno ser aprovado, o texto da ferramenta é a única versão |

## Arquivos

- [`linha-de-base-capitulo_2026-10-22.md`](linha-de-base-capitulo_2026-10-22.md) — texto do capítulo como publicado na v0.3.10, com cada afirmação marcada como normativa, institucional, dado do projeto ou orientação ao gestor, e a lista do que conferir na Etapa 3.
- [`verificacao-fontes_2026-10-22.md`](verificacao-fontes_2026-10-22.md) — conferência de cada afirmação em fonte primária, com link e data; achados novos; pendências que dependem de portais bloqueados.
- [`proposta-grafica.md`](proposta-grafica.md) — como o capítulo aparece hoje na ferramenta.
- [`CHANGELOG.md`](CHANGELOG.md) — registro de alterações.
- `caderno.md` — será criado na Etapa 4 (rascunho v0.1).

## Normas usadas

| Norma | Transcrição | Situação de verificação |
|---|---|---|
| Portaria GM/MS nº 1.646/2015 (institui o CNES na forma atual) | não transcrita | conferida em 22/10/2026 (cópia oficial no gov.br da ANS; DOU de 05/10/2015) |
| Portaria de Consolidação GM/MS nº 1/2017 (Título VII, Capítulo IV, arts. 358 a 390; reúne a 1.646/2015, a 2.022/2017 e a 1.321/2016) | [transcrita](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-CONSOLIDACAO-GMMS-1-2017-ORGANIZACAO-E-FUNCIONAMENTO-DO-SUS.md) em 24/10/2026 | conferida em 24/10/2026; texto até outubro de 2018, alterações posteriores pendentes |
| Portaria SAS/MS nº 118/2014, republicada em 16/06/2014 (desativação após seis meses sem atualização) | não transcrita | conferida em 22/10/2026 (cópia municipal da versão republicada); vigência atual pendente |
| Portaria SAS/MS nº 511/2000 (ficha cadastral e banco nacional; origem do cadastro) | não transcrita | conferida em 22/10/2026 (cópia da SES-AM) |
| Portaria GM/MS nº 2.022/2017 (tipo de estabelecimento derivado das atividades) | não transcrita | conferida em 22/10/2026 (cópia municipal) |

## Dados do projeto usados

| Base | Onde está | Competência |
|---|---|---|
| Extração CNES do DF (estabelecimentos, leitos, equipamentos, habilitações, serviços, profissionais) | `data/cnes/` no repositório da ferramenta (privado) | 08/2026 |
| Força de trabalho agregada por especialidade | Project, `claude/forca-trabalho-agregada-202608.md`; Drive, pasta de camadas derivadas | 08/2026 |
| Habilitação oficial × declarado | Project, `claude/habilitacao-oficial-vs-declarado-v1.0.md`; Drive, pasta de camadas derivadas | CNES 08/2026 × SIGTAP 09/2026 |

## Pendências

Fila de pendências do Project: `claude/backlog/2026-10-22_cadernos-renases-cnes.md` (item "Caderno formal de CNES") e `claude/backlog/2026-10-22_caderno-cnes.md`.

## Origem

Caderno pedido em 22/10/2026 (prompt `claude/prompt-caderno-cnes.md` no Project), depois que a auditoria dos capítulos de conhecimento mostrou que o capítulo de CNES nunca teve caderno.
