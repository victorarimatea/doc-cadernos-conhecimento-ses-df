# Caderno de CNES

| Campo | Valor |
|---|---|
| Finalidade | Explicar ao gestor o que o Cadastro Nacional de Estabelecimentos de Saúde registra, quem atualiza, como consultar e como ler os dados sem confundir cadastro com capacidade real |
| Público | Gestores hospitalares e equipes de apoio da SEGHOSP e da CICS |
| Capítulo que alimenta | Conhecimento · CNES (rota `#k-cnes`) |
| Versão vigente | v1.0, aprovada pelo Victor em 26/10/2026 |
| Situação | Etapas 1 a 5 concluídas; caderno aprovado no modelo de caderno v1.2. Próximo passo, na ferramenta: o capítulo de CNES passa a ser gerado do caderno, com as listas por bloco e o bloco "Nesta ferramenta" da prévia |
| Alinhamento com a ferramenta | O capítulo publicado na ferramenta (v0.3.10) ainda é o texto anterior ao caderno. Com a aprovação, o caderno passa a ser a fonte; a troca entra na próxima versão da ferramenta, a partir do gerador da prévia (`build/previa_capitulo_cnes.py` e `build/cnes_listas.py`, no repositório da ferramenta) |

## Arquivos

- [`linha-de-base-capitulo_2026-10-22.md`](linha-de-base-capitulo_2026-10-22.md) — texto do capítulo como publicado na v0.3.10, com cada afirmação marcada como normativa, institucional, dado do projeto ou orientação ao gestor, e a lista do que conferir na Etapa 3.
- [`verificacao-fontes_2026-10-22.md`](verificacao-fontes_2026-10-22.md) — conferência de cada afirmação em fonte primária, com link e data; achados novos; pendências que dependem de portais bloqueados.
- [`proposta-grafica.md`](proposta-grafica.md) — como o capítulo aparece hoje na ferramenta.
- [`CHANGELOG.md`](CHANGELOG.md) — registro de alterações.
- [`caderno.md`](caderno.md) — o caderno (v1.0, aprovado em 26/10/2026, no modelo de caderno v1.2).

## Normas usadas

| Norma | Transcrição | Situação de verificação |
|---|---|---|
| Portaria GM/MS nº 1.646/2015 (institui o CNES na forma atual) | [transcrita](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-GMMS-1646-2015-INSTITUI-O-CNES.md) em 26/10/2026 (redação original); texto vigente na consolidação (arts. 358 a 373 e 384 a 390) | conferida em 22/10/2026 (cópia oficial no gov.br da ANS; DOU de 05/10/2015); revogada por consolidação (PRC 1/2017, art. 560, XLII), conferido em 24/10/2026 |
| Portaria de Consolidação GM/MS nº 1/2017 (Título VII, Capítulo IV, arts. 358 a 390; reúne a 1.646/2015, a 2.022/2017 e a 1.321/2016) | [transcrita](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-CONSOLIDACAO-GMMS-1-2017-ORGANIZACAO-E-FUNCIONAMENTO-DO-SUS.md) em 24/10/2026 | conferida em 24/10/2026; texto até outubro de 2018, alterações posteriores pendentes |
| Portaria de Consolidação SAES/MS nº 1/2022 (Título III, Capítulo III, arts. 217 a 290; reúne a 118/2014 e outras portarias SAS do cadastro) | [transcrita](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-CONSOLIDACAO-SAESMS-1-2022-ATENCAO-ESPECIALIZADA.md) em 25/10/2026 (315 páginas, página do DOU guardada pela SES-MG) | conferida em 25/10/2026; alterações posteriores a 31/03/2022 pendentes |
| Portaria SAS/MS nº 118/2014 (desativação após seis meses sem atualização), redações original (DOU de 19/02/2014) e republicada (DOU de 16/06/2014) | [republicada](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-SASMS-118-2014-DESATIVACAO-CNES-REPUBLICADA.md) e [original](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-SASMS-118-2014-DESATIVACAO-CNES-ORIGINAL.md), transcritas em 25/10/2026 | PDFs localizados pelo Victor em 25/10/2026; revogada por consolidação (PRC SAES/MS 1/2022, art. 432, LXIV), o texto segue nos arts. 227 a 230 |
| Portaria SAS/MS nº 511/2000 (ficha cadastral e banco nacional; origem do cadastro) | [transcrita](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-SASMS-511-2000-FICHA-CADASTRAL-CNES.md) em 26/10/2026 | conferida em 22/10/2026 (cópia da SES-AM); não aparece nas listas de revogação das consolidações de 2017 e 2022; vigência não conferida |
| Portaria GM/MS nº 2.022/2017 (tipo de estabelecimento derivado das atividades) | [transcrita](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-GMMS-2022-2017-TIPO-DE-ESTABELECIMENTO-CNES.md) em 26/10/2026 (redação republicada); texto vigente na consolidação (arts. 374 a 378 e Anexo XV) | conferida em 22/10/2026 (cópia municipal); revogada por consolidação (art. 560, XLIII) |
| Portaria GM/MS nº 1.321/2016 (formas de contratação dos profissionais) | texto vigente na consolidação (arts. 379 a 383); cópia em fonte primária não localizada | conferida no texto consolidado em 24/10/2026; revogada por consolidação (art. 560, XLIV) |
| Decreto nº 39.546/2018, Regimento Interno da SES-DF (quem faz cada tarefa do cadastro na SES-DF) | [transcrito](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/02-legislacao-distrital/DECRETO-DISTRITAL-39546-2018-REGIMENTO-INTERNO-SESDF.md) em 24/10/2026 (texto compilado do SINJ-DF de 13/10/2026) | conferido em 26/10/2026: arts. 173, 175, 176, 267, 270, 290 e equivalentes nas unidades de referência distrital |

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
| 2026-10-26 | Caderno aprovado pelo Victor (v1.0) |
| 2026-10-26 | Base normativa em dois blocos: vigentes por esfera e normas de origem em ordem cronológica, com o problema que cada uma enfrentou; a hierarquia fica como alternativa, não como regra (registrado no modelo v1.2, 4.5) |
| 2026-10-26 | Não incluir a Lei 8.080/1990 nem normas gerais que o texto não cita; incluir as portarias de origem do CNES |
| 2026-10-26 | Testar o detalhe recolhível (dois no caderno) e as listas por bloco geradas pela ferramenta, com link para a ficha de um hospital da SES-DF |
| 2026-10-26 | Trazer para o caderno a leitura completa do leito não SUS em hospital público, como segunda Leitura do projeto; os números ficam só no bloco gerado |
| 2026-10-24 | Tirar do caderno o dado do 1º ciclo da carteira (leitos habilitados × operacionais de um hospital), que é declaração interna não publicada; o repositório é público |

## Pendências

- Conferir alterações da Portaria de Consolidação nº 1/2017 posteriores a outubro de 2018 no capítulo do CNES.
- Conferir alterações da Portaria de Consolidação SAES/MS nº 1/2022 posteriores a março de 2022 no capítulo do CNES (arts. 217 a 290).
- Confirmar a que superintendência a GECAD pertence na estrutura atual da SES-DF (reestruturação de 2026).
- Ler a Wiki do CNES (não abriu em 22/10/2026) para conferir as regras de compatibilidade citadas a partir do caderno de SIGTAP.
- Confirmar com a GECAD ou na Wiki do CNES a regra de sistema que limita os leitos SUS de UTI e cuidados intermediários ao número habilitado (observada nos dados de 08/2026, sem norma localizada).
- Conferir se as habilitações de cuidados intermediários neonatais com códigos atuais (28.02 e 28.03) seguem o registro descentralizado do art. 222 da PRC SAES/MS 1/2022 (o Anexo XXXIX traz o código de 2006, 28.01) e qual instância faz, no DF, o papel da Comissão Intergestores Bipartite.
- Conferir o prazo de reapresentação da produção rejeitada (citado no exemplo da seção 5), no caderno de SIGTAP ou nos manuais do SIA e do SIH.
- Localizar a Portaria GM/MS nº 1.321/2016 em fonte primária.
- Conferir a vigência da Portaria SAS/MS nº 511/2000.
- Conferir se o Regimento Interno de 2018 ainda descreve as unidades do cadastro depois das reestruturações de 2026, e o formato do link da ficha do estabelecimento no portal do CNES.
- Descobrir a descrição dos serviços especializados 171 e 172 (HAB e HRT), que faltam na tabela auxiliar do DATASUS; as descrições de equipamento que faltavam foram completadas pelo portal do CNES em 26/10/2026 (tabela de complemento no repositório da ferramenta).


Fila de pendências do Project: `claude/backlog/2026-10-22_cadernos-renases-cnes.md` (item "Caderno formal de CNES") e `claude/backlog/2026-10-22_caderno-cnes.md`.

## Origem

Caderno pedido em 22/10/2026 (prompt `claude/prompt-caderno-cnes.md` no Project), depois que a auditoria dos capítulos de conhecimento mostrou que o capítulo de CNES nunca teve caderno.
