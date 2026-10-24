# Verificação em fonte primária — caderno de CNES (Etapa 3)

Registro de trabalho feito em 22/10/2026 (noite, horário de Brasília). Confere as afirmações
marcadas na [linha de base do capítulo](linha-de-base-capitulo_2026-10-22.md) e levanta o que o
caderno precisa ter e o capítulo não tem (histórico, como consultar).

## Como foi feita

- Leitura automática na nuvem (busca e leitura de páginas) e, para os portais que bloqueiam
  leitura automática, o navegador embutido do app no computador do Victor.
- **Bloqueados nos dois caminhos:** Biblioteca Virtual em Saúde do Ministério (bvsms.saude.gov.br,
  inclusive a página inicial: "The requested URL was rejected", erro 503) e InfoSaúde-DF
  (info.saude.df.gov.br, páginas HTML). Nada desses dois portais foi lido; o que depende deles
  está marcado como pendente.
- **Lidos:** portal do CNES (cnes.datasus.gov.br) e TabNet (tabnet.datasus.gov.br) pelo
  navegador; cópias oficiais em sites do governo (gov.br da ANS e da EBSERH, secretarias
  estaduais e municipais) pela leitura automática.
- Grau de cada conferência:
  - **Texto oficial** — texto integral da norma, em cópia hospedada por órgão público, com a
    citação de publicação no DOU.
  - **Fonte oficial secundária** — documento oficial de outro órgão que descreve a norma, sem
    o texto integral.
  - **Pendente** — não lido.
- Nenhuma afirmação foi reconstruída de memória.

## 1. Base legal

| # | Afirmação (linha de base) | Resultado | Fonte e data de conferência |
|---|---|---|---|
| N1 | CNES instituído na forma atual pela Portaria GM/MS nº 1.646/2015 | **Confirmada (texto oficial).** Art. 1º: "Fica instituído o Cadastro Nacional de Estabelecimentos de Saúde (CNES)". Publicada no DOU de 05/10/2015, nº 190, Seção 1, p. 669. Art. 2º: o CNES é documento público e sistema de informação oficial de cadastramento. Art. 5º: é a fonte oficial de informações sobre estabelecimentos de saúde no país | Cópia no gov.br da ANS: https://www.gov.br/ans/pt-br/centrais-de-conteudo/portaria-n-1646-de-02-de-outubro-de-2015-cnes-pdf (22/10/2026). Também listada no portal do CNES, seção Legislação, em 07/10/2015 (arquivo só por FTP) |
| N2 | A Portaria 1.646/2015 está reunida na Portaria de Consolidação nº 1/2017 | **Confirmada (texto oficial), em 24/10/2026.** O CNES é o Capítulo IV do Título VII da consolidação (arts. 358 a 390). A 1.646/2015 está nos arts. 358 a 373 (arts. 1º a 16) e 384 a 390 (comitê consultivo e disposições finais); a 2.022/2017 (tipo de estabelecimento por atividade), nos arts. 374 a 378; a 1.321/2016 (formas de contratação de profissionais), nos arts. 379 a 383. Definições no art. 360; responsabilidades e competências nos arts. 364 a 369. **Correção ao manual da EBSERH:** a atualização ao menos mensal (art. 13 da 1.646/2015) é o **art. 370** da consolidação; os arts. 371 e 372 tratam dos dois fluxos de envio (arts. 14 e 15) | PDF do texto consolidado guardado na pasta compartilhada de normas e transcrito em [`doc-governanca-ses-df`](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-CONSOLIDACAO-GMMS-1-2017-ORGANIZACAO-E-FUNCIONAMENTO-DO-SUS.md) (págs. 105 a 112 do PDF). Texto atualizado até a Portaria GM/MS 3.440, de 24/10/2018; alterações posteriores pendentes de conferência. Antes: manual EBSERH, https://www.gov.br/hubrasil/pt-br/acesso-a-informacao/boletim-de-servico/sede/2021/anexos/manual-cnes-2a-edicao-v3.pdf (22/10/2026) |
| N3 | Cadastro obrigatório para todo estabelecimento funcionar (art. 4º) | **Confirmada (texto oficial).** Art. 4º: o cadastramento e a manutenção dos dados no CNES são obrigatórios para que todo e qualquer estabelecimento de saúde possa funcionar em território nacional, devendo preceder aos licenciamentos | Portaria 1.646/2015, cópia ANS (22/10/2026) |
| N4 | Responsabilidade do estabelecimento, por seus responsáveis técnicos ou administrativos (art. 7º) | **Confirmada (texto oficial).** Art. 7º. Na consolidação, art. 364, segundo o manual da EBSERH. O mesmo manual diz que os profissionais respondem pelos próprios dados (art. 365) | Idem; manual EBSERH |
| N5 | O gestor do SUS pode desativar cadastros irregulares | **Confirmada (texto oficial); artigo localizado: art. 16.** Os gestores do SUS podem desativar cadastros realizados pelos estabelecimentos, com hierarquia municipal, estadual e federal | Portaria 1.646/2015, cópia ANS (22/10/2026) |
| N6 | Desativação automática após seis meses sem atualização (Portaria SAS/MS nº 118/2014) | **Confirmada (texto oficial), com ressalva de versão.** A versão republicada (DOU nº 113, 16/06/2014, Seção 1, p. 91) diz no art. 1º que o sistema marca como "desativados", em nível local e nacional, os estabelecimentos há mais de 6 meses sem atualização. O prazo de implantação foi de 6 competências. Sem atualização é: não exportado e transmitido há mais de 6 meses, ou transmitido com rejeição há mais de 6 meses (§ 1º). A volta a "ativo" se dá com nova exportação sem rejeição (§ 2º). O art. 2º lista o que fica impedido: apresentar produção ambulatorial e hospitalar e de vigilância sanitária, registrar produção de equipes, pedir novas habilitações, entrar em novos programas, receber recursos de equipes. A publicação original (DOU nº 35, 19/02/2014) falava em marcar como "inconsistidos", com prazo de 3 competências. Vale a republicada | Republicada: https://saude.campinas.sp.gov.br/saude/lista_legislacoes/legis_2014/U_PT-MS-SAS-118-REP_180214.pdf. Original: https://cvs.saude.sp.gov.br/zip/U_PT-MS-SAS-118_180214.pdf (22/10/2026). Vigência atual e eventual consolidação: **pendente** |

### Achados que o capítulo não tem

| Achado | Fonte |
|---|---|
| **Atualização mínima mensal.** Art. 13 da Portaria 1.646/2015 (art. 370 da consolidação, conferido no texto em 24/10/2026): processo eletrônico, com atualização ao menos mensal ou logo após qualquer mudança. O capítulo fala em "competência mensal", mas não diz que a atualização mensal é obrigação normativa | Portaria 1.646/2015, cópia ANS; PRC 1/2017, art. 370 |
| **Dois fluxos de envio.** Art. 14: estabelecimentos fora do SUS, entre outros casos, inserem os dados direto na base nacional. Art. 15: estabelecimentos do SUS enviam à esfera de gestão do SUS do território, que valida e encaminha | Portaria 1.646/2015, cópia ANS (resumo dos arts. 14 e 15; texto integral a transcrever) |
| **Prazo de adequação.** Art. 23: estabelecimentos e gestores tiveram até a competência de dezembro de 2016 para se adequar | Idem |
| **Norma revogada.** Art. 25: revoga a Portaria GM/MS nº 1.890/1997. O conteúdo da 1.890/1997 não foi conferido | Idem |
| **Origem do cadastro (2000).** Portaria SAS/MS nº 511/2000 aprovou a Ficha Cadastral dos Estabelecimentos de Saúde (FCES), o manual de preenchimento e a criação do Banco de Dados Nacional de Estabelecimentos de Saúde. Fez cessar os efeitos da Portaria SAS/MS nº 376, de 03/10/2000 (art. 12). O manual da EBSERH cita as Portarias SAS 403/2000 e 511/2000 como origem histórica | Portaria SAS 511/2000, cópia SES-AM: https://www.saude.am.gov.br/wp-content/uploads/2025/01/PT-CNES-PORTARIA-No-511-DE29-DE-DEZEMBRO-DE-2000.pdf (22/10/2026). Conteúdo das Portarias SAS 376/2000 e 403/2000: **pendente** |
| **Tipo de estabelecimento passou a ser derivado das atividades.** Portaria GM/MS nº 2.022/2017 (republicada no DOU nº 155, 14/08/2017, Seção 1, p. 94). O tipo deixa de ser escolhido e passa a sair da atividade principal e das secundárias, por uma nova Classificação de Tipos de Estabelecimentos e uma Terminologia de Atividades de Saúde. Ajuda a explicar por que o HMIB aparece como "hospital geral" | Cópia na Prefeitura de Jacareí: https://www.jacarei.sp.gov.br/wp-content/uploads/2021/02/Portaria-2022-de-7-de-agosto-de-2017.pdf (22/10/2026). Se foi consolidada: **pendente** |
| **Envio mensal mesmo sem mudança.** O manual da EBSERH recomenda o envio mensal mesmo sem alterações, como "certidão negativa". Diz ainda que leitos habilitados não podem exceder os leitos SUS | Manual EBSERH (orientação operacional, não norma) |

## 2. Funcionamento: quem atualiza, quando, o que contém

| # | Afirmação (linha de base) | Resultado | Fonte e data |
|---|---|---|---|
| I1 | SIA e SIH só aprovam produção de estabelecimento, serviço e profissional cadastrados e compatíveis com a SIGTAP | **Confirmada em parte.** O art. 2º da Portaria SAS 118/2014 mostra que estabelecimento desativado no CNES não apresenta produção. As críticas de compatibilidade com serviço, habilitação e CBO são regra da SIGTAP e do SIA/SIH, a conferir no caderno de SIGTAP e nos manuais do SIA/SIH | Portaria SAS 118/2014 republicada (22/10/2026); demais: **pendente** |
| I2 | Os sete blocos do cadastro (quadro da seção 2) | **Confirmada, com outra divisão.** O manual da EBSERH descreve os módulos do sistema: identificação; informações gerais (instalações, serviços de apoio e especializados, equipamentos); ambulatorial; hospitalar (leitos); profissionais; equipes; telessaúde; mantenedora; habilitação; regras contratuais; incentivos; contrato de gestão e metas. Os blocos do capítulo correspondem aos arquivos de disseminação que o projeto usa (estabelecimentos, leitos, equipamentos, habilitações, serviços especializados, profissionais). O caderno deve dizer que essa é a divisão dos arquivos, não a dos módulos do sistema | Manual EBSERH; dicionário da extração do projeto (`data/cnes/README.md`) |
| I3 | Base fechada por competência mensal e divulgada pelo DATASUS | **Confirmada.** O portal do CNES publica informes por competência: abertura do módulo transmissor da competência 10/2026 (16/10/2026) e prorrogação do transmissor da competência 09/2026 (05/10/2026). O TabNet do CNES para o DF tem séries mensais de ago/2005 a set/2026 e só mostra estabelecimentos com status ATIVO. A extração do projeto usa os arquivos mensais de disseminação do DATASUS | Portal do CNES, página inicial (22/10/2026, navegador); TabNet, CNES, Estabelecimentos por tipo, DF (22/10/2026, navegador) |
| I4 | Na SES-DF, o cadastramento é conduzido pela Gerência de Cadastramento de Estabelecimentos e Usuários do SUS, na SUPLANS | **Confirmada em parte.** Guia da SES-DF aos contratados do credenciamento de cirurgias oftalmológicas (edital nº 03/2025): a Gerência de Cadastramento de Estabelecimento e Usuários do SUS (GECAD) é a área técnica responsável. Contato: cnes.gecad@saude.df.gov.br. Todos os estabelecimentos devem atualizar o cadastro mensalmente; depois do envio, a atualização leva cerca de 15 dias. O guia não diz a que superintendência a GECAD pertence. **Vínculo com a SUPLANS: pendente** (reconfirmar no organograma vigente, depois da reestruturação de 2026) | https://info.saude.df.gov.br/wp-content/uploads/2026/01/GUIA-DE-ORIENTACAO-AOS-CONTRATADOS-CIRURGIAS-OFTALMOLOGICAS-Edital-de-Credenciamento-no-032025-SESDF.pdf (22/10/2026; guia sem data impressa) |
| I5 | Equipamentos separados em existente, em uso e disponível ao SUS | **Confirmada** nos arquivos de equipamentos usados pelo projeto (`qt_existente`, `qt_em_uso`, `disponivel_sus`) | `data/cnes/README.md` |

## 3. Como consultar

| Caminho | O que oferece | Situação |
|---|---|---|
| Portal do CNES: https://cnes.datasus.gov.br | Consulta de estabelecimento e de profissional, informes por competência, legislação (arquivos por FTP) | Lido em 22/10/2026. A página informa que funções ainda não migradas estão no portal anterior, https://cnes2.datasus.gov.br |
| TabNet do CNES: https://tabnet.datasus.gov.br/cgi/deftohtm.exe?cnes/cnv/estabdf.def | Tabulação por competência (estabelecimentos por tipo, DF; há tabulações de leitos, equipamentos, profissionais e serviços) | Lido em 22/10/2026; só registros ATIVOS. A lista de tabulações do CNES no TabNet não foi conferida item a item |
| Arquivos de disseminação do DATASUS | Microdados mensais por UF: estabelecimentos (ST), leitos (LT), equipamentos (EQ), habilitações (HB), serviços especializados (SR), profissionais (PF), mais tabelas auxiliares | Usados pelo projeto (extração 08/2026). A página oficial de transferência de arquivos não foi lida; o FTP é bloqueado nos dois ambientes de trabalho |
| Documentação: Wiki do CNES (https://wiki.saude.gov.br/cnes) | Normas, orientações técnicas e regras de negócio | Não abriu no navegador em 22/10/2026 |

## 4. Dados do projeto citados no capítulo

Conferidos contra a extração CNES 08/2026 (`data/cnes/`) em 22/10/2026:

| # | Afirmação | Resultado |
|---|---|---|
| D2 | 44 hospitais: 22 públicos e 22 privados ou filantrópicos com leitos SUS; divisão por grupo | **Confere**: 14 SES-DF, 2 IGESDF, 1 Rede Sarah, 1 federal universitário, 4 Forças Armadas; 22 privados ou filantrópicos com leitos SUS |
| D4 | Nenhum equipamento de código 0124 no DF | **Confere** (0 registros) |
| D5 | HCB com natureza de órgão público do DF; HMIB como hospital geral | **Confere** (natureza 1023 nos dois; HMIB tipo 05, hospital geral; HCB tipo 07, especializado) |
| D1 | Competência 08/2026 publicada pelo DATASUS em 15/09/2026 | Registrado no dicionário da extração; não reconferido no DATASUS |
| D3 | HSVP: 83 leitos habilitados e 48 operacionais no 1º ciclo | Vem da declaração do 1º ciclo, não do CNES; não reconferido aqui |
| D6, D7 | Região de saúde codificada sem descrição; descrições faltantes (2% leitos, 6% equipamentos, 2% classificações, 1% CBO) | Confere com o dicionário da extração |

## 5. Pendências para o Victor (abrir no seu navegador e baixar o PDF ou salvar a página)

Os dois portais abaixo recusam leitura automática e também o navegador do app. Abertos no seu
navegador, os arquivos podem seguir o padrão da pasta compartilhada de normas (PDF original e
transcrição). Para isso, basta deixá-los numa pasta conectada.

1. ~~Portaria de Consolidação GM/MS nº 1/2017, texto compilado~~ — **resolvida em 24/10/2026**: o
   PDF baixado pelo Victor foi transcrito (ver N2). Fica pendente só conferir alterações posteriores
   a outubro de 2018 no texto compilado da BVS:
   https://bvsms.saude.gov.br/bvs/saudelegis/gm/2017/prc0001_03_10_2017.html
2. Portaria GM/MS nº 1.646/2015 na BVS (para comparar com a cópia da ANS e ver se há texto
   compilado): https://bvsms.saude.gov.br/bvs/saudelegis/gm/2015/prt1646_02_10_2015.html
3. Portaria SAS/MS nº 118/2014, republicada, na BVS:
   https://bvsms.saude.gov.br/bvs/sas/Links%20finalizados%20SAS%202014/prt0118_12_06_2014_rep.html
4. InfoSaúde-DF, base legal do CNES e orientações de cadastro (para confirmar onde a GECAD fica
   na estrutura atual):
   https://info.saude.df.gov.br/sala-de-situacao/painel-infosaude-base-legal-do-cnes/ e
   https://info.saude.df.gov.br/sala-de-situacao/painel-infosaude-orientacoes-gerais-para-cadastro-no-cnes/
5. Portaria GM/MS nº 1.646/2015 e Portaria GM/MS nº 2.022/2017 no FTP do DATASUS (versões
   oficiais em ZIP, listadas no portal do CNES):
   ftp://ftp.datasus.gov.br/cnes/portarias/PT_1646_02102015.zip e
   ftp://ftp.datasus.gov.br/cnes/portarias/PT_GM_2017-2022_DE_07082017.ZIP

## 6. Consequências para o rascunho do caderno

- Manter a base legal do capítulo, agora com dispositivos e publicação: 1.646/2015 (arts. 1º, 2º,
  4º, 5º, 7º, 13 a 16, 23, 25) e a consolidação (Título VII, Capítulo IV, arts. 358 a 390; atualização mensal no art. 370),
  conferida no texto em 24/10/2026.
- Corrigir a ênfase: a atualização **mensal** é obrigação normativa (art. 13), não só um ritmo do
  sistema.
- Acrescentar o histórico: FCES e banco nacional em 2000 (Portaria SAS 511/2000), CNES na forma
  atual em 2015, tipo de estabelecimento por atividade em 2017 (Portaria 2.022/2017).
- Explicar a consequência da desativação: sem atualização por seis meses, o hospital não
  apresenta produção nem pede habilitação (Portaria SAS 118/2014, art. 2º). É o elo direto entre
  cadastro e faturamento.
- Seção "Como consultar" com os três caminhos (portal, TabNet, arquivos), dizendo o que cada um
  mostra e que o TabNet só conta estabelecimentos ativos.
- Na SES-DF, citar a GECAD com o contato oficial e deixar a vinculação à superintendência como
  pendente até a confirmação.
