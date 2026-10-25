# Caderno de CNES

| Campo | Valor |
|---|---|
| Finalidade | Explicar ao gestor o que o Cadastro Nacional de Estabelecimentos de Saúde registra, quem atualiza, como consultar e como ler os dados sem confundir cadastro com capacidade real |
| Público | Gestores hospitalares e equipes de apoio da SEGHOSP e da CICS |
| Capítulo que alimenta | Conhecimento · CNES (rota `#k-cnes`) |
| Versão vigente | nenhuma aprovada; rascunho v0.2 de 25/10/2026 aguarda aprovação |
| Situação | Etapa 4 de 5 concluída (rascunho v0.2 no modelo de caderno v1.1; prévia da página na ferramenta publicada em 24/10/2026); próxima: aprovação pelo Victor e v1.0 |
| Alinhamento com a ferramenta | O capítulo existe na ferramenta desde a v0.2 (26/09/2026) sem caderno de origem. Até o caderno ser aprovado, o texto da ferramenta é a única versão |

## Arquivos

- [`linha-de-base-capitulo_2026-10-22.md`](linha-de-base-capitulo_2026-10-22.md) — texto do capítulo como publicado na v0.3.10, com cada afirmação marcada como normativa, institucional, dado do projeto ou orientação ao gestor, e a lista do que conferir na Etapa 3.
- [`verificacao-fontes_2026-10-22.md`](verificacao-fontes_2026-10-22.md) — conferência de cada afirmação em fonte primária, com link e data; achados novos; pendências que dependem de portais bloqueados.
- [`proposta-grafica.md`](proposta-grafica.md) — como o capítulo aparece hoje na ferramenta.
- [`CHANGELOG.md`](CHANGELOG.md) — registro de alterações.
- [`caderno.md`](caderno.md) — o caderno (v0.2, rascunho de 25/10/2026, no modelo de caderno v1.1).

## Normas usadas

| Norma | Transcrição | Situação de verificação |
|---|---|---|
| Portaria GM/MS nº 1.646/2015 (institui o CNES na forma atual) | texto vigente na consolidação (arts. 358 a 373 e 384 a 390) | conferida em 22/10/2026 (cópia oficial no gov.br da ANS; DOU de 05/10/2015); revogada por consolidação (PRC 1/2017, art. 560, XLII), conferido em 24/10/2026 |
| Portaria de Consolidação GM/MS nº 1/2017 (Título VII, Capítulo IV, arts. 358 a 390; reúne a 1.646/2015, a 2.022/2017 e a 1.321/2016) | [transcrita](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-CONSOLIDACAO-GMMS-1-2017-ORGANIZACAO-E-FUNCIONAMENTO-DO-SUS.md) em 24/10/2026 | conferida em 24/10/2026; texto até outubro de 2018, alterações posteriores pendentes |
| Portaria de Consolidação SAES/MS nº 1/2022 (Título III, Capítulo III, arts. 217 a 290; reúne a 118/2014 e outras portarias SAS do cadastro) | não transcrita | lida em 25/10/2026 na cópia da página do DOU guardada pela SES-MG (315 páginas); alterações posteriores a 31/03/2022 pendentes |
| Portaria SAS/MS nº 118/2014 (desativação após seis meses sem atualização), redações original (DOU de 19/02/2014) e republicada (DOU de 16/06/2014) | [republicada](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-SASMS-118-2014-DESATIVACAO-CNES-REPUBLICADA.md) e [original](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-SASMS-118-2014-DESATIVACAO-CNES-ORIGINAL.md), transcritas em 25/10/2026 | PDFs localizados pelo Victor em 25/10/2026; revogada por consolidação (PRC SAES/MS 1/2022, art. 432, LXIV), o texto segue nos arts. 227 a 230 |
| Portaria SAS/MS nº 511/2000 (ficha cadastral e banco nacional; origem do cadastro) | não transcrita | conferida em 22/10/2026 (cópia da SES-AM) |
| Portaria GM/MS nº 2.022/2017 (tipo de estabelecimento derivado das atividades) | texto vigente na consolidação (arts. 374 a 378) | conferida em 22/10/2026 (cópia municipal); revogada por consolidação (art. 560, XLIII) |
| Portaria GM/MS nº 1.321/2016 (formas de contratação dos profissionais) | texto vigente na consolidação (arts. 379 a 383) | conferida no texto consolidado em 24/10/2026; revogada por consolidação (art. 560, XLIV) |

## Dados do projeto usados

| Base | Onde está | Competência |
|---|---|---|
| Extração CNES do DF (estabelecimentos, leitos, equipamentos, habilitações, serviços, profissionais) | `data/cnes/` no repositório da ferramenta (privado) | 08/2026 |
| Força de trabalho agregada por especialidade | Project, `claude/forca-trabalho-agregada-202608.md`; Drive, pasta de camadas derivadas | 08/2026 |
| Habilitação oficial × declarado | Project, `claude/habilitacao-oficial-vs-declarado-v1.0.md`; Drive, pasta de camadas derivadas | CNES 08/2026 × SIGTAP 09/2026 |

## Decisões registradas

| Data | Decisão |
|---|---|
| 2026-10-22 | Criar o caderno de CNES, que não existia (o capítulo estava só na ferramenta) |
| 2026-10-24 | Escrever o caderno no modelo de caderno padronizado (v1.1), e não na estrutura de 12 seções do prompt original |
| 2026-10-24 | Citar os artigos pela Portaria de Consolidação nº 1/2017, com a norma de origem indicada |
| 2026-10-25 | Citar a regra de desativação pela Portaria de Consolidação SAES/MS nº 1/2022 (arts. 227 e 228), com a Portaria SAS 118/2014 como origem |
| 2026-10-24 | Tirar do caderno o dado do 1º ciclo da carteira (leitos habilitados × operacionais de um hospital), que é declaração interna não publicada; o repositório é público |

## Pendências

- Conferir alterações da Portaria de Consolidação nº 1/2017 posteriores a outubro de 2018 no capítulo do CNES.
- Transcrever a Portaria de Consolidação SAES/MS nº 1/2022, ao menos o capítulo do CNES (arts. 217 a 290), e conferir alterações posteriores a março de 2022.
- Confirmar a que superintendência a GECAD pertence na estrutura atual da SES-DF (reestruturação de 2026).
- Ler a Wiki do CNES (não abriu em 22/10/2026) para conferir as regras de compatibilidade citadas a partir do caderno de SIGTAP.
- Aprovação do Victor para a v1.0.


Fila de pendências do Project: `claude/backlog/2026-10-22_cadernos-renases-cnes.md` (item "Caderno formal de CNES") e `claude/backlog/2026-10-22_caderno-cnes.md`.

## Origem

Caderno pedido em 22/10/2026 (prompt `claude/prompt-caderno-cnes.md` no Project), depois que a auditoria dos capítulos de conhecimento mostrou que o capítulo de CNES nunca teve caderno.
