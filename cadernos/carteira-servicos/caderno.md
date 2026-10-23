# CAP \- CARTEIRA DE SERVIÇOS \- BASE DE ESTUDO E PESQUISA

Projeto Carteira de Serviços da SES-DF · Base de conhecimento v1.2 · 26/09/2026

Histórico de versões: v1.0 (26/09/2026), versão inicial. v1.1 (26/09/2026), pendências PEN-01 a PEN-04 verificadas em fonte primária; NOR-22, NOR-23 e NOR-24 atualizadas; incluídos NOR-30, NOR-31, EXE-11 a EXE-13, REL-14, FON-13, ALE-09 a ALE-12 e a seção 2.4. v1.2 (26/09/2026), incorporado o eixo Governança, participação social e monitoramento da Carteira, com GOV-01 a GOV-12, fluxo FLX-01 a FLX-08, matriz MAT-GOV, indicadores IND-GOV-01 a IND-GOV-07 e pendências PEN-GOV-01 a PEN-GOV-04. As propostas operacionais dependem de validação institucional.

## 0\. Como usar esta base

Este documento é uma base de estudo e pesquisa estruturada. Ele foi preparado para ser lido por pessoas e também por outra ferramenta que vai montar a aplicação HTML de consulta da Carteira de Serviços.

Convenções:

- Cada registro tem um identificador fixo (ID) que pode virar chave de dados no HTML: CON (conceitos), NOR (normas), EXE (exemplos), CMP (campos da carteira), REL (instrumentos relacionados), FON (fontes de consulta da SES-DF), ALE (alertas), PEN (pendências).  
- As colunas das tabelas são os campos sugeridos para cada tipo de registro.  
- Status da informação: "Verificado" significa conferido em fonte primária (norma ou documento oficial) nesta pesquisa. "Fonte secundária" significa informação obtida em artigo, notícia ou citação de terceiros. "A verificar" significa informação ainda pendente de conferência.  
- A base foi feita a partir de uma pesquisa com três modelos de IA (Claude Fable 5, GPT 6 Sol e Gemini 3.1 Pro) e de uma pesquisa complementar específica sobre a SES-DF. As contradições entre os modelos foram resolvidas a favor da fonte primária (ver seção 7).  
- Esta base complementa o documento "PROJETO\_CARTEIRA\_SERVICOS\_DOCUMENTO\_MESTRE\_v1.0" e o capítulo "CAP \- SIGTAP", que ficam na mesma pasta.

## 1\. Conceitos (CON)

| ID | Termo | Definição de trabalho | Fonte | Status |
| :---- | :---- | :---- | :---- | :---- |
| CON-01 | Carteira de Serviços | Instrumento técnico e normativo, voltado à gestão e ao planejamento da rede de saúde, que define as ações, procedimentos, exames e composição mínima de equipe a serem ofertados nos estabelecimentos da SES/DF. Seus objetivos são organizar a assistência, facilitar a regulação do acesso e promover a equidade da oferta. | [Portaria SES-DF nº 632/2025, art. 2º, IV](https://www.sinj.df.gov.br/sinj/Norma/b7211d3fbde043308032717260456eb6/ses_prt_632_2025.html) | Verificado |
| CON-02 | Carta de Serviços | Instrumento de gestão pública e controle social que informa os cidadãos sobre os serviços prestados em uma unidade: como são ofertados e acessados, os padrões de qualidade esperados e os compromissos assumidos no atendimento. Não é a mesma coisa que a Carteira. | [Portaria SES-DF nº 632/2025, art. 2º, III](https://www.sinj.df.gov.br/sinj/Norma/b7211d3fbde043308032717260456eb6/ses_prt_632_2025.html); [Lei nº 13.460/2017, art. 7º](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2017/lei/l13460.htm) | Verificado |
| CON-03 | Carteira de Serviços da APS (definição nacional) | Lista de ações e serviços clínicos e de vigilância em saúde ofertados na APS, voltada à população, aos demais níveis do sistema, aos gestores e aos profissionais. A lista não é excludente: um item ausente não significa que ele não deva ser feito. | [CaSAPS \- Ministério da Saúde](https://www.gov.br/saude/pt-br/composicao/saps/publicacoes/cartazes-e-cartilhas/casaps_versao_profissionais_saude_gestores_completa.pdf) | Verificado |
| CON-04 | RENASES | Relação Nacional de Ações e Serviços de Saúde, com todas as ações e serviços que o SUS oferece ao usuário, organizada em cinco componentes. Estados e municípios podem ter relações complementares. | [Decreto nº 7.508/2011, arts. 21-24](https://www.planalto.gov.br/ccivil_03/_ato2011-2014/2011/decreto/d7508.htm); [Portaria GM/MS nº 841/2012](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2012/prt0841_02_05_2012.html) | Verificado |
| CON-05 | Documento Descritivo | Anexo do contrato do hospital que define todas as ações e serviços a serem prestados, com metas e indicadores. Na prática, é a carteira hospitalar contratualizada. | [Portaria GM/MS nº 3.410/2013](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2014/prt3410_30_12_2013.html) | Verificado |
| CON-06 | Padrão essencial e padrão ampliado | Na PNAB, o padrão essencial reúne as ações e procedimentos que todas as equipes devem garantir. O padrão ampliado reúne as ações estratégicas recomendadas conforme a realidade local. | [PNAB \- Portaria nº 2.436/2017](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2017/prt2436_22_09_2017.html) | Verificado |
| CON-07 | Quatro planos da oferta | Separação analítica que convém manter na carteira: (1) direito ou norma aplicável; (2) capacidade cadastrada ou declarada; (3) compromisso pactuado ou contratado; (4) produção efetivamente realizada. Um item previsto em norma ou cadastrado no CNES não prova que o serviço está sendo ofertado. | Síntese do conselho de modelos (proposta do GPT 6 Sol) | Conceito analítico |
| CON-08 | Oferta de Cuidados Integrados (OCI) | Arranjo que reúne procedimentos, exames, consultas e outras tecnologias em saúde para o atendimento de agravos específicos. | [Portaria SES-DF nº 632/2025, art. 2º, XVIII](https://www.sinj.df.gov.br/sinj/Norma/b7211d3fbde043308032717260456eb6/ses_prt_632_2025.html) | Verificado |
| CON-09 | Regulação do acesso de segunda geração | Regulação que vai além da oferta de vagas: considera análise clínica, trajetória assistencial, protocolos, matriciamento e a capacidade instalada da rede. | [Portaria SES-DF nº 632/2025, art. 2º, XXII](https://www.sinj.df.gov.br/sinj/Norma/b7211d3fbde043308032717260456eb6/ses_prt_632_2025.html) | Verificado |
| CON-10 | Gerações de carteira | Tipologia analítica: (1) informativa, uma lista de ações; (2) gradativa, com itens classificados por obrigatoriedade ou maturidade; (3) contratual e mensurável, com indicador por item, meta e vínculo com contrato. | Síntese do conselho (proposta do Claude Fable 5\) | Conceito analítico |

## 2\. Base normativa (NOR)

### 2.1 Nacional

| ID | Norma | Data | Tema | Dispositivos relevantes para a carteira | Status | URL |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| NOR-01 | Constituição Federal, arts. 196-200 | 1988 | Direito à saúde e SUS | Base de universalidade e integralidade | Vigente | [Planalto](https://www.planalto.gov.br/ccivil_03/constituicao/constituicao.htm) |
| NOR-02 | Lei nº 8.080 | 19/09/1990 | Lei Orgânica da Saúde | Art. 7º (integralidade; divulgação dos serviços; epidemiologia no planejamento) | Vigente | [Planalto](https://www.planalto.gov.br/ccivil_03/leis/l8080.htm) |
| NOR-03 | Decreto nº 7.508 | 28/06/2011 | Organização do SUS, Regiões de Saúde, RENASES, RENAME | Art. 7º (rol de ações por região), arts. 21-24 (RENASES e relações complementares), arts. 25-29 (RENAME) | Vigente | [Planalto](https://www.planalto.gov.br/ccivil_03/_ato2011-2014/2011/decreto/d7508.htm) |
| NOR-04 | Resolução CIT nº 2 | 17/01/2012 | Diretrizes da RENASES | Finalidade de tornar públicas as ações e serviços do SUS | Vigente | [BVS](https://bvsms.saude.gov.br/bvs/saudelegis/cit/2012/res0002_17_01_2012.html) |
| NOR-05 | Portaria GM/MS nº 841 | 02/05/2012 | RENASES, 1ª versão | 5 componentes; códigos de acesso (procura direta, encaminhamento, regulação, habilitação, PCDT, vigilância); relações complementares. Não foi encontrada consolidação posterior. | Vigente, sem atualização conhecida | [BVS](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2012/prt0841_02_05_2012.html) |
| NOR-06 | Lei Complementar nº 141 | 13/01/2012 | Financiamento e planejamento | Plano de saúde, programação anual e relatório de gestão | Vigente | [Planalto](https://www.planalto.gov.br/ccivil_03/leis/lcp/lcp141.htm) |
| NOR-07 | Portaria GM/MS nº 2.436 (PNAB), hoje no Anexo XXII da Portaria de Consolidação nº 2/2017 | 21/09/2017 | Atenção Básica | Padrões essencial e ampliado; oferta pública e pactuada; afixar na UBS a "relação de serviços disponíveis" | Vigente | [BVS](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2017/prt2436_22_09_2017.html) |
| NOR-08 | Portaria GM/MS nº 3.390 (PNHOSP) | 30/12/2013 | Política Nacional de Atenção Hospitalar | Perfil assistencial do hospital definido pela rede; acesso regulado | Vigente (consolidada) | [BVS](https://bvs.saude.gov.br/bvs/saudelegis/gm/2013/prt3390_30_12_2013.html) |
| NOR-09 | Portaria GM/MS nº 3.410 | 30/12/2013 | Contratualização hospitalar | Documento Descritivo com todas as ações e serviços, metas e indicadores; oferta contratada disponível à regulação | Vigente (consolidada) | [BVS](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2014/prt3410_30_12_2013.html) |
| NOR-10 | Portaria GM/MS nº 1.646 | 02/10/2015 | CNES | Cadastro de estabelecimentos, profissionais, serviços e habilitações | Vigente (consolidada) | [BVS](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2015/prt1646_02_10_2015.html) |
| NOR-11 | Lei nº 13.460 | 26/06/2017 | Direitos do usuário de serviços públicos | Art. 7º: Carta de Serviços ao Usuário (serviços, requisitos, etapas, prazos e canais) | Vigente | [Planalto](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2017/lei/l13460.htm) |
| NOR-12 | Portaria GM/MS nº 1.604 (PNAES) | 18/10/2023 | Política Nacional de Atenção Especializada | Diretrizes da atenção especializada | Vigente | [DOU](https://www.in.gov.br/web/dou/-/portaria-gm/ms-n-1.604-de-18-de-outubro-de-2023-517547992) |
| NOR-13 | Portaria GM/MS nº 3.493 | 10/04/2024 | Novo cofinanciamento da APS (substitui a lógica inicial do Previne Brasil) | Componentes fixo, vínculo, qualidade e outros; os indicadores medem só uma parte da carteira | Vigente | [BVS](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2024/prt3493_11_04_2024.html) |
| NOR-14 | CaSAPS \- Ministério da Saúde | Dez/2019 (versão 2020\) | Carteira nacional da APS | Documento técnico sem portaria própria; cerca de 210 a 212 itens; não excludente; adaptável pelo gestor | Referência técnica | [MS](https://www.gov.br/saude/pt-br/composicao/saps/publicacoes/cartazes-e-cartilhas/casaps_versao_profissionais_saude_gestores_completa.pdf) |

### 2.2 Distrito Federal (SES-DF)

| ID | Norma ou documento | Data | Tema | Dispositivos relevantes para a carteira | Status | URL |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| NOR-20 | Portaria SES-DF nº 77 | 14/02/2017 | Política de APS do DF | Art. 16 (ações baseadas na Carteira de Serviços da APS); art. 17 (indicador "percentual da carteira de serviços da APS aprovada pela SES oferecido pela equipe", consolidado mensalmente pelas GSAP); art. 22 (carteira da UBS visível ao usuário); art. 26, IV (afixar a carteira na entrada da unidade) | Vigente, alterada pela Portaria 114/2022 | [SES-DF](https://www.saude.df.gov.br/documents/37101/45840/Portaria-SES_DF-n%C2%BA-77-2017-Esstabelece-a-Pol%C3%ADtica-de-Aten%C3%A7%C3%A3o-Prim%C3%A1ria-%C3%A0-Sa%C3%BAde-do-Distrito-Federal.pdf/5092cc7f-3559-c0de-4bb8-14c88426eee0?t=1648125104991) |
| NOR-21 | Portaria SES-DF nº 139 | 20/03/2017 | Referência Técnica Assistencial na assistência hospitalar | Referências técnicas distritais por área | A verificar (texto integral) | [Wiki SES-DF](https://wiki.saude.df.gov.br/index.php/Refer%C3%AAncia_T%C3%A9cnica_Distrital) |
| NOR-22 | Portaria SES-DF nº 773 | 19/07/2018 | Atenção Ambulatorial Secundária (AASE) | Art. 2º, II (conceito de Carteiras de Serviços); arts. 5º, 6º, 18 e 19 (carteiras da AASE e exclusões) | Revogada pelo art. 81 da Portaria SES-DF 632/2025 (DODF de 15/01/2026). Usar apenas como histórico | [SINJ-DF](https://www.sinj.df.gov.br/sinj/Norma/82c3196081194fa3b7cd6862311bcaca/Portaria_773_19_07_2018.html) |
| NOR-23 | Portaria SES-DF nº 1.357 | 06/12/2018 (DODF nº 237, 14/12/2018) | Atenção Hospitalar (AH) | Art. 2º (definição de AH); art. 3º (NAQH, NIR, equipes horizontais); art. 4º (rol de serviços que podem compor a AH); art. 6º (princípios); art. 10 (regulação pelo CRDF, panoramas 1 a 3); arts. 12-13 (ambulatório de egressos e ambulatório terciário); art. 16, parágrafo único (oferta à regulação por instrumentos formais); art. 22 (planos distritais como documentos norteadores); arts. 23 e 26 (criação e descontinuidade de serviços). Não usa o termo "carteira". Detalhe na seção 2.4 | Vigente (sem anotação de revogação no SINJ-DF). Verificado | [SINJ-DF](https://www.sinj.df.gov.br/sinj/Norma/536a9f4da0a9459f96bd8c3bc06dfc50/Portaria_1357_06_12_2018.html) |
| NOR-24 | Portaria SES-DF nº 632 (Política Distrital de Atenção Ambulatorial Especializada, PDAAE) | 16/12/2025 | Atenção Ambulatorial Especializada | Art. 2º, III e IV (definições de Carta e de Carteira); art. 6º, I (toda oferta da AAE prevista em carteira própria); art. 17 (carteira por normativa específica); art. 18 (revisão anual, pactuada com as Regiões e as URD); art. 19 (execução por profissionais habilitados); art. 41 (equipamentos alinhados à carteira); art. 2º, II (Ambulatório Hospitalar); art. 13 (ambulatórios hospitalares integram a AAE); art. 14 (exclui internação, permanência acima de 12 horas e urgência); arts. 77-80 (reorganização e transição dos ambulatórios existentes); art. 81 (revoga as Portarias 773/2018 e 132/2020) | Vigente; publicada no DODF em 15/01/2026 | [SINJ-DF](https://www.sinj.df.gov.br/sinj/Norma/b7211d3fbde043308032717260456eb6/ses_prt_632_2025.html) |
| NOR-25 | CaSAPS-DF, 3ª edição (versão profissional) | 2025 | Carteira da APS do DF | 1ª versão em 2016; revisão pela Comissão Permanente de Revisão da CaSAPS (CPRCS, criada em 2022, coordenada pela COAPS); 82 páginas; organizada por ciclos de vida, populações vulneráveis, PIS, eMulti, saúde bucal e procedimentos | Vigente; passou por consulta pública | [SES-DF](https://www.saude.df.gov.br/documents/37101/620159/CaSAPS_DF___versao_FINAL_10_03_25__com_ficha_catalografica_.docx+\(1\).pdf/95aab6d1-6413-00fa-3445-0cd7b12dfc22?t=1742320979393) |
| NOR-26 | Plano Distrital de Saúde (PDS) 2024-2027 | 2024 (atualizado em 2025\) | Planejamento | Objetivo: "Estruturar e reorganizar a Atenção Especializada Ambulatorial e Hospitalar, com foco na qualificação da carteira de serviços"; cita o Plano Distrital de Serviços Cirúrgicos 2023/2026 | Vigente | [InfoSaúde](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf) |
| NOR-27 | Programação Anual de Saúde (PAS) 2026 | Aprovada em 18/03/2026 | Planejamento anual | Ações 139 e 142: construir a Carteira de Serviços da AAE (validação pela COASIS, consulta pública no DODF, revisão e publicação). Indicador 52: meta de 2.587.483 consultas especializadas; indicador 53: meta de 33.546.620 exames | Vigente | [InfoSaúde](https://info.saude.df.gov.br/wp-content/uploads/2026/04/PAS_2026_Aprovada_pelo_Colegiado_de_Gestao_SESDF_18.03.2026_Revisado.pdf) |
| NOR-28 | Decreto DF nº 38.488 | 13/09/2017 | Complexo Regulador do DF | Autoridade para a regulação de todos os serviços do SUS no DF | Vigente (citado na Portaria 632/2025) | [SINJ-DF](https://www.sinj.df.gov.br/sinj/Norma/b7211d3fbde043308032717260456eb6/ses_prt_632_2025.html) |
| NOR-29 | Contrato de Gestão IGESDF nº 001/2018; Lei DF nº 5.899/2017 e Decreto DF nº 39.674/2019 | 2018 | Unidades geridas pelo IGESDF | Metas e indicadores contratuais das unidades do IGESDF | Vigente | [SES-DF](https://www.saude.df.gov.br/contrato-de-gestao-igesdf) |
| NOR-30 | Portaria SES-DF nº 432 | 27/10/2023 | Contratualização de hospitais | Incorpora como norma própria da SES-DF as diretrizes de contratualização da PNHOSP (Anexo 2 do Anexo XXIV da PRC nº 2/2017). O Documento Descritivo deve conter todas as ações e serviços do hospital e metas físicas, com validade máxima de 24 meses | Vigente. Verificado | [SINJ-DF](https://www.sinj.df.gov.br/sinj/Norma/2033976f5af94d1783ed5bac13f4a8c2/Portaria_432_27_10_2023.html) |
| NOR-31 | Portaria SES-DF nº 132 | 28/02/2020 | Centro Especializado em Saúde da Mulher (CESMU) | Instituía o CESMU e critérios de encaminhamento | Revogada pelo art. 81 da Portaria 632/2025 | [SINJ-DF](https://www.sinj.df.gov.br/sinj/Norma/0c8a59cfc0bc4220a1e311f9c1529f95/Portaria_132_28_02_2020.html) |

### 2.3 Referências internacionais

| ID | País | Norma | Ponto-chave | Status | URL |
| :---- | :---- | :---- | :---- | :---- | :---- |
| NOR-40 | Espanha | Ley 16/2003, com a redação do RDL 16/2012 | Carteira comum dividida em básica, suplementar e acessória. Essa divisão é de 2012, não do RD 1030/2006. | Vigente | [Ministerio de Sanidad](https://www.sanidad.gob.es/en/profesionales/prestacionesSanitarias/CarteraDeServicios/home.htm) |
| NOR-41 | Espanha | Real Decreto 1030/2006 | Carteira comum do SNS em anexos por área; critérios de inclusão; atualização; carteiras complementares das comunidades autônomas. Art. 2.4: se o serviço não existe no local, é obrigatório encaminhar. | Vigente | [BOE](https://www.boe.es/buscar/act.php?id=BOE-A-2006-16212) |
| NOR-42 | Espanha (Madri) | Cartera de Servicios Estandarizados de AP | 40 serviços; indicador de cobertura e critérios de boa atenção por serviço; avaliação automática pelo prontuário eletrônico; indicadores fazem parte do Contrato Programa | Vigente | [Comunidad de Madrid](https://www.comunidad.madrid/salud/cartera-servicios-comunes-sistema-nacional-salud) |
| NOR-43 | Portugal | Decreto-Lei 103/2023 e Despacho 14237/2024 (que revogou o Despacho 12456-B/2023); histórico: Portaria 1368/2007 | Carteira básica, obrigatória para todas as USF, e carteira adicional contratualizada, com indicador e compensação financeira | Vigente | [Diário da República](https://diariodarepublica.pt/dr/detalhe/despacho/14237-2024-898377839) |
| NOR-44 | Reino Unido | Contrato GMS do NHS | Serviços essenciais, adicionais e ampliados ("enhanced") na atenção primária | Vigente | [NHS England](https://www.england.nhs.uk/wp-content/uploads/2020/12/20-21-GMS-Contract-October-2020.pdf) |

### 2.4 Detalhe da Portaria SES-DF nº 1.357/2018 e lacuna da carteira hospitalar

Rol de serviços que podem compor a Atenção Hospitalar (art. 4º): Serviço Hospitalar de Emergência; leitos gerais; Núcleo de Atenção Domiciliar; cuidados paliativos; cuidados prolongados; terapia intensiva; cuidados intermediários; odontologia hospitalar; ambulatórios de especialidades cirúrgicas; ambulatório em saúde mental; patologia clínica; terapia antineoplásica e imunobiológicos; medicina nuclear; anatomia patológica e citopatologia; diagnóstico por imagem; unidade especializada de referência em saúde mental; qualidade e segurança do paciente; controle de infecção hospitalar; central de material e esterilização; nutrição hospitalar; ambulatórios hospitalares de caráter terciário; farmácia hospitalar; farmácia clínica; saúde funcional; serviço hospitalar especializado em saúde mental; assistência social; vigilância epidemiológica; hematologia e hemoterapia ([SINJ-DF](https://www.sinj.df.gov.br/sinj/Norma/536a9f4da0a9459f96bd8c3bc06dfc50/Portaria_1357_06_12_2018.html)). Esse rol pode servir de lista de valores para o tipo de serviço hospitalar no HTML, mas não indica qual hospital oferta cada serviço.

Situação da carteira hospitalar (verificação de 26/09/2026): não foi localizada uma Carteira de Serviços hospitalar da SES-DF instituída por portaria, publicada no DODF ou registrada no SINJ-DF. O PDS 2024-2027, as PAS 2025 e 2026, a Portaria 188/2026 e a página de consultas públicas não trazem esse instrumento. O conteúdo de uma carteira hospitalar existe hoje de forma dispersa:

| Instrumento | O que cobre | Força normativa | Registro na base |
| :---- | :---- | :---- | :---- |
| Portaria 1.357/2018, art. 4º | Tipos de serviço da AH | Norma vigente | NOR-23 |
| Carteira de Serviços Ortopedia SES-DF (Anexo I) | Subespecialidades ambulatoriais e cirurgias eletivas com código SIGTAP por hospital | Documento técnico, sem ato de aprovação localizado | EXE-11 |
| Plano Distrital de Serviços Cirúrgicos 2023/2026 | Especialidades cirúrgicas e capacidade por hospital | Plano de gestão, texto integral não localizado | REL-09 |
| Documentos Descritivos (HUB, HCB, IGESDF) | Serviços, metas e recursos por hospital contratualizado | Portaria 432/2023 | NOR-30, EXE-12 |
| Acordos de Gestão Local 2024-2027 | Metas e indicadores dos 10 hospitais da administração direta | Contratualização interna | REL-14 |
| CaSAAE-DF | Oferta ambulatorial especializada, incluindo ambulatórios hospitalares | Portaria 632/2025, em fase final | EXE-03 |

Zona de sobreposição: a Portaria 1.357/2018 inclui na AH os ambulatórios de especialidades cirúrgicas e os ambulatórios terciários (arts. 4º e 13). A Portaria 632/2025 inclui os Ambulatórios Hospitalares na AAE (arts. 2º, II, e 13). Leitura sugerida para o HTML: a oferta ambulatorial dentro dos hospitais segue a CaSAAE-DF; internação, urgência e procedimentos que dependem da estrutura hospitalar seguem a Portaria 1.357/2018, ainda sem carteira própria.

## 3\. Exemplos de carteiras (EXE)

| ID | Ente | Nível de atenção | Documento / ano | Estrutura e classificação | Lição para a SES-DF | URL |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| EXE-01 | Ministério da Saúde | APS | CaSAPS, 2019/2020 | Grupos: vigilância, promoção, adulto/idoso, criança/adolescente, procedimentos, saúde bucal. Cada item traz insumos, orientações e "saiba mais". Não traz indicador por item nem códigos SIGTAP. | Serve de base de conteúdo, mas não é monitorável sem correspondência com códigos | [MS](https://www.gov.br/saude/pt-br/composicao/saps/publicacoes/cartazes-e-cartilhas/casaps_versao_profissionais_saude_gestores_completa.pdf) |
| EXE-02 | SES-DF | APS | CaSAPS-DF, 3ª ed., 2025 | Ciclos de vida, rastreamento, vigilância, assistência farmacêutica, condições crônicas, 8 populações vulneráveis, PIS, eMulti, saúde bucal, procedimentos diagnósticos e terapêuticos. Tem comissão permanente de revisão. | É o modelo interno de governança (comissão, consulta pública, edições) | [SES-DF](https://www.saude.df.gov.br/documents/37101/620159/CaSAPS_DF___versao_FINAL_10_03_25__com_ficha_catalografica_.docx+\(1\).pdf/95aab6d1-6413-00fa-3445-0cd7b12dfc22?t=1742320979393) |
| EXE-03 | SES-DF | AAE | CaSAAE-DF, Carteira de Serviços da AAE (em fase final) | Prevista na Portaria 632/2025 (art. 17\) e nas ações 139/142 da PAS 2026\. Consulta pública de 8/12/2025 a 7/1/2026; em janeiro de 2026 estava em análise técnica. Publicação final não localizada até 26/09/2026. Inclui os ambulatórios hospitalares (art. 13 da Portaria 632/2025) | Deve ser conciliada com a carteira hospitalar do projeto na parte ambulatorial dos hospitais | [SES-DF, consulta pública](https://www.saude.df.gov.br/web/guest/w/sa%C3%BAde-lan%C3%A7a-consulta-p%C3%BAblica-para-servi%C3%A7os-da-aten%C3%A7%C3%A3o-ambulatorial-especializada-do-df); [SES-DF, jan/2026](https://www.saude.df.gov.br/w/gdf-institui-pol%C3%ADtica-de-aten%C3%A7%C3%A3o-ambulatorial-especializada-para-qualificar-atendimento-no-sus) |
| EXE-04 | SES-DF | Transversal, para o cidadão | "Carteira de Serviços" no InfoSaúde | Lista de 24 serviços para o cidadão (ambulatório, cirurgias, exames, transplantes, TRS etc.). Na prática, funciona como Carta de Serviços. | Mostra a confusão entre carta e carteira; o HTML deve separar as duas | [InfoSaúde](https://info.saude.df.gov.br/transparencia-e-prestacao-de-contas/carteira-de-servicos/) |
| EXE-05 | Rio de Janeiro | APS | Edições de 2011, 2016 e 2021 | Classificação em 2016: I (todas as unidades), II (modelos A e B), O (opcional). Em 2021: ações essenciais, estratégicas e ampliadas e estágios I a III. Tem códigos SIGTAP, CNES atualizado mensalmente e "carteirômetro"; é anexo do contrato com as OSS. | É o caso mais maduro de carteira mensurável e contratual no Brasil | [SMS-Rio 2021](https://subpav.org/download/impressos/Livro_CarteiraDeServicosAPS_2021_20211229.pdf) |
| EXE-06 | Belo Horizonte | APS e rede | Carteira Orientadora, 2018 | Organizada por macroprocessos (territorialização, eventos agudos, condições crônicas, domicílio etc.) | Inclui ações territoriais e coletivas como itens | [PBH](https://prefeitura.pbh.gov.br/sites/default/files/estrutura-de-governo/saude/2021/carteira-orientadora_servicos-sus-bh-07-11-2018-1.pdf) |
| EXE-07 | Porto Alegre | APS | Carteira APS, 2019 | Varia conforme o tipo de unidade (I a III); tem versão separada para o usuário | Carteira diferente por perfil de unidade, análoga ao perfil hospitalar | [SMS-POA](https://prefeitura.poa.br/sites/default/files/usu_doc/cartadeservicos/Carteira%20de%20Servi%C3%A7os%20APS%20POA.pdf) |
| EXE-08 | Florianópolis | APS e rede | Carteira (portaria de 2014\) e Carta de Serviços (2022) | Os dois instrumentos coexistem, cada um com sua função | Separar carteira e carta | [Carta de Serviços](https://www.pmf.sc.gov.br/arquivos/arquivos/pdf/24_11_2022_11.39.38.0573f6461813ca3259234f35db6ab187.pdf) |
| EXE-09 | Hospitais SUS e EBSERH | Hospitalar | Documento Descritivo / Manual de Contratualização EBSERH | Ações, serviços e metas por hospital, com indicadores | É o modelo de "carteira hospitalar contratualizada" | [Manual EBSERH](https://www.gov.br/hubrasil/pt-br/acesso-a-informacao/boletim-de-servico/sede/2024/anexos-2024/manual_contratualizacao_ebserh_26_11_24_vf); [Modelo MS](https://wiki.saude.gov.br/contratacao/index.php/Modelo_do_Documento_Descritivo_ou_Plano_Operativo) |
| EXE-10 | Madri | APS | Cartera de Servicios Estandarizados | Indicador de cobertura e critérios de boa atenção por serviço; avaliação automática | Referência para os indicadores por item | [Comunidad de Madrid](https://www.comunidad.madrid/salud/cartera-servicios-comunes-sistema-nacional-salud) |
| EXE-11 | SES-DF | Hospitalar e ambulatorial (ortopedia) | Carteira de Serviços Ortopedia SES-DF (Anexo I), arquivo de novembro de 2023 | Por hospital (HBDF, HRC, HRG, HRL, HRPL, HRS, HRSM, HRT): subespecialidades de consulta ambulatorial e cirurgias eletivas com código SIGTAP, nome do procedimento, complexidade e porte (cerca de 265 linhas) | É o protótipo interno mais próximo do modelo procedimento × unidade do projeto; não foi localizado o ato que o aprova | [SES-DF](https://www.saude.df.gov.br/documents/37101/0/Carteira_de_Servicos_Ortopedia_SES__1_.pdf/59232908-e888-39cb-634d-16669bdea46c?t=1699959876095); listado em [Notas Técnicas](https://www.saude.df.gov.br/notas-tecnicas) |
| EXE-12 | SES-DF e EBSERH | Hospitalar contratualizado | Convênio SES-DF e HUB-UnB, com Documento Descritivo (vigência de 01/12/2024 a 01/12/2029) | Caracterização do hospital, abrangência, estrutura, 49 especialidades, lista de serviços, indicadores, metas e recursos | Exemplo local de carteira hospitalar contratual (NOR-30) | [SES-DF](https://www.saude.df.gov.br/documents/37101/0/Convenio_027540_2024_SESDF_EBSERH_HUB_UNB.pdf/198f9845-2fdf-6b7e-5b95-7146d1904248?t=1733492986406) |
| EXE-13 | SES-DF (DIASF/SULOG) | Transversal (três níveis) | Carteira de Serviços do Cuidado Farmacêutico, 1ª ed., 2025 | Para cada serviço: definição, pré-requisitos e atividades principais | Carteira temática que atravessa os níveis de atenção | [SES-DF](https://saude.df.gov.br/documents/37101/0/Carteira_de_servicos.pdf/07e9b17f-922d-500d-261e-81a5832aeb08?t=1757610677748) |

## 4\. Estrutura mínima de uma carteira (CMP)

### 4.1 Blocos do documento-base

| ID | Bloco | Conteúdo mínimo | Referência |
| :---- | :---- | :---- | :---- |
| CMP-B01 | Apresentação e finalidade | Público (gestor, profissional, regulação, cidadão); caráter não excludente; nível de atenção | CaSAPS; Portaria 632/2025, art. 17 |
| CMP-B02 | Base normativa | Ato que institui a carteira; normas nacionais e distritais | NOR-03, NOR-07, NOR-24 |
| CMP-B03 | Perfil e tipologia das unidades | Tipo de unidade, perfil assistencial, porte e habilitações | PNHOSP; Portaria 77/2017, art. 7º |
| CMP-B04 | Rol de ações e serviços | Organizado por especialidade, linha de cuidado ou grupo SIGTAP | CaSAPS-DF; catálogo SUPLANS |
| CMP-B05 | Classificação de obrigatoriedade | Essencial / estratégico / ampliado, ou obrigatório / opcional por tipologia | PNAB; Rio; Portugal |
| CMP-B06 | Interfaces de rede | Acesso, regulação, referência e contrarreferência, protocolos | RENASES; Portaria 632/2025 |
| CMP-B07 | Compromissos com o usuário | Prazos, horários, canais (ligação com a Carta de Serviços) | Lei 13.460/2017 |
| CMP-B08 | Governança | Responsável, comissão, revisão anual, consulta pública, controle de versões | Portaria 632/2025, art. 18; CPRCS da CaSAPS-DF |
| CMP-B09 | Monitoramento | Indicadores de implantação da carteira e de produção | Portaria 77/2017, art. 17; Rio ("carteirômetro") |

### 4.2 Dicionário de campos por item (unidade × serviço/procedimento)

Estes são os campos sugeridos para a aplicação HTML. A unidade analítica recomendada é o par procedimento × unidade executante, coerente com a Base Analítica v0.1 do projeto.

| ID | Campo | Descrição | Tipo | Obrigatório | Fonte de preenchimento |
| :---- | :---- | :---- | :---- | :---- | :---- |
| CMP-01 | id\_item | Identificador único do registro | texto | Sim | Gerado |
| CMP-02 | cod\_sigtap | Código SIGTAP (10 dígitos) | texto | Sim, quando houver código | SIGTAP |
| CMP-03 | nome\_procedimento | Nome oficial do procedimento | texto | Sim | SIGTAP |
| CMP-04 | nome\_cidadao | Nome em linguagem simples | texto | Não | Área técnica |
| CMP-05 | grupo\_subgrupo\_forma | Hierarquia SIGTAP | texto | Sim | SIGTAP |
| CMP-06 | especialidade | Especialidade ou área (vocabulário controlado) | lista | Sim | Base consolidada |
| CMP-07 | linha\_cuidado | Linha de cuidado ou rede temática | lista | Não | Grupos condutores das RAS |
| CMP-08 | nivel\_atencao | APS / AAE / hospitalar / urgência | lista | Sim | Normas NOR-20, NOR-23, NOR-24 |
| CMP-09 | complexidade | AB / média / alta (atributo SIGTAP) | lista | Sim | SIGTAP |
| CMP-10 | financiamento | FAEC, MAC, PAB (atributo SIGTAP) | lista | Não | SIGTAP |
| CMP-11 | instrumento\_registro | BPA-C, BPA-I, APAC, AIH, RAAS | lista | Não | SIGTAP |
| CMP-12 | cnes\_unidade | Código CNES da unidade executante | texto | Sim | CNES |
| CMP-13 | nome\_unidade | Nome da unidade | texto | Sim | CNES |
| CMP-14 | regiao\_saude | Região de Saúde ou URD | lista | Sim | SES-DF |
| CMP-15 | gestao | Administração direta / IGESDF / conveniado / contratado | lista | Sim | CNES / contratos |
| CMP-16 | setor\_servico | Setor ou serviço declarado (PLAN1) | texto | Não | Levantamento SEGHOSP |
| CMP-17 | classificacao\_oferta | Essencial / estratégico / ampliado, ou exclusivo da rede | lista | Não | Definição da carteira |
| CMP-18 | status\_oferta | Declarado / confirmado / validado / suspenso / não ofertado | lista | Sim | Ciclos de validação |
| CMP-19 | habilitacao\_cnes | Habilitação ou serviço especializado exigido, se houver | texto | Condicional | CNES / SIGTAP |
| CMP-20 | cbo\_executante | CBO ou categoria profissional habilitada | texto | Não | SIGTAP / CNES |
| CMP-21 | estrutura\_requerida | Sala, leito, equipamento, anestesia, OPME | texto | Não | PLAN1 / área técnica |
| CMP-22 | forma\_acesso | Procura direta / encaminhamento / regulação / habilitação / PCDT | lista | Sim | Códigos da RENASES / CRDF |
| CMP-23 | sistema\_regulacao | SISREG III / SISLEITOS / TrakCare / sem regulação | lista | Não | CRDF |
| CMP-24 | protocolo\_referencia | Protocolo, PCDT ou nota técnica | link | Não | SES-DF / MS |
| CMP-25 | capacidade\_declarada | Volume ou capacidade mensal declarada | número | Não | Unidade |
| CMP-26 | producao\_observada | Produção aprovada no período (SIA/SIH) | número | Não | SIA / SIH / InfoSaúde |
| CMP-27 | competencia\_producao | Mês e ano da produção | data | Condicional | SIA / SIH |
| CMP-28 | demanda\_fila | Fila ou demanda regulada | número | Não | SISREG / CRDF |
| CMP-29 | indicador\_meta | Indicador e meta associados | texto | Não | PDS / PAS / contrato |
| CMP-30 | contrato\_vinculado | Contrato de gestão ou Documento Descritivo | texto | Condicional | Contratos |
| CMP-31 | metodo\_vinculo | Regra de conciliação (exata, por nome, manual) | lista | Sim | Base Analítica v0.1 |
| CMP-32 | confianca | Alta / média / baixa | lista | Sim | Base Analítica v0.1 |
| CMP-33 | fonte\_origem | Arquivo, aba e linha de origem | texto | Sim | Rastreabilidade |
| CMP-34 | data\_atualizacao | Data da última verificação | data | Sim | Gerado |
| CMP-35 | observacoes | Ressalvas e notas | texto | Não | Área técnica |

Regras de exibição sugeridas para o HTML:

- Sempre separar visualmente os quatro planos (CON-07): declarado, cadastrado no CNES, contratado ou pactuado e produzido.  
- Não tratar a ausência como inexistência: um procedimento não declarado deve aparecer como "sem informação", e não como "não ofertado", até a validação.  
- Exibir a data e a fonte de cada informação.  
- Não exibir dados identificáveis de pacientes.

## 5\. Instrumentos relacionados (REL)

| ID | Instrumento | Pergunta que responde | Relação com a carteira | Onde consultar |
| :---- | :---- | :---- | :---- | :---- |
| REL-01 | RENASES | O que o SUS oferece e como se acessa? | A carteira local é uma relação complementar e operacional da RENASES | [Portaria 841/2012](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2012/prt0841_02_05_2012.html) |
| REL-02 | RENAME / REME-DF | Quais medicamentos estão padronizados? | Os itens clínicos dependem de medicamentos e insumos disponíveis | [RENAME](https://www.gov.br/saude/pt-br/composicao/sectics/daf/rename) |
| REL-03 | SIGTAP | Qual é o código, os atributos, o financiamento e o instrumento de registro? | Linguagem comum dos itens. É uma tabela, não recebe a produção. Ver o capítulo "CAP \- SIGTAP". | [SIGTAP](http://sigtap.datasus.gov.br) |
| REL-04 | CNES | Que estrutura, profissionais, serviços e habilitações a unidade tem? | Registra capacidade, não compromisso de oferta; deve ser confrontado com a carteira | [CNES](https://cnes.datasus.gov.br) |
| REL-05 | SIA / SIH / SISAB | O que foi efetivamente produzido? | Mostra a oferta realizada; permite comparar com a carteira declarada | [InfoSaúde \- Sala de Situação](https://info.saude.df.gov.br/sala-de-situacao/) |
| REL-06 | Regulação (CRDF: SISREG III, SISLEITOS, TrakCare) | Quem faz o quê na rede e qual é a fila? | A carteira informa à regulação o que cada unidade oferece e delimita o que deve ser resolvido em cada nível | [PDS 2024-2027](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf) |
| REL-07 | Protocolos, PCDT e linhas de cuidado | Como e quando fazer? | A carteira diz o que é ofertado; os protocolos dizem como fazer | [Portaria 632/2025, art. 2º, XVI](https://www.sinj.df.gov.br/sinj/Norma/b7211d3fbde043308032717260456eb6/ses_prt_632_2025.html) |
| REL-08 | PDS, PAS e RAG (acompanhados no SESPlan) | Quais são as prioridades, metas e orçamento? | O PDS 2024-2027 e a PAS 2026 têm objetivo e ações específicos sobre a carteira | [PAS 2026](https://info.saude.df.gov.br/wp-content/uploads/2026/04/PAS_2026_Aprovada_pelo_Colegiado_de_Gestao_SESDF_18.03.2026_Revisado.pdf) |
| REL-09 | Plano Distrital de Serviços Cirúrgicos 2023/2026 | Qual é o perfil e a capacidade cirúrgica por hospital? | Especialidades cirúrgicas e salas eletivas e de urgência, SRPA e centro obstétrico por hospital (PDS, pp. 118-119). Base diretamente comparável à carteira cirúrgico-ambulatorial | [PDS](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf); elaboração citada no [Despacho de 18/07/2023](https://www.sinj.df.gov.br/sinj/Norma/c9086dd110e841f7a281d1aab0851692/ses_des_18_07_2023.html) |
| REL-10 | Contrato de Gestão IGESDF / Documento Descritivo | O que foi contratado, com quais metas? | Carteira contratualizada das unidades geridas pelo IGESDF | [SES-DF](https://www.saude.df.gov.br/contrato-de-gestao-igesdf); [Indicadores IGESDF](https://indicadores.igesdf.org.br/) |
| REL-11 | Carta de Serviços ao Cidadão | Como o cidadão acessa, com que prazos e por quais canais? | É uma visão derivada da carteira, voltada ao cidadão | [InfoSaúde \- Carta de Serviços](https://info.saude.df.gov.br/transparencia-e-prestacao-de-contas/carta-de-servicos/) |
| REL-12 | Cofinanciamento federal da APS | Quais ações induzem repasse? | Os indicadores cobrem só uma parte da carteira | [Portaria 3.493/2024](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2024/prt3493_11_04_2024.html) |
| REL-13 | Referência Técnica Distrital (RTD) | Quem responde tecnicamente por cada área? | São os validadores técnicos naturais dos itens da carteira | [Wiki SES-DF](https://wiki.saude.df.gov.br/index.php/Refer%C3%AAncia_T%C3%A9cnica_Distrital) |
| REL-14 | Acordos de Gestão Local (AGL) 2024-2027 | Quais metas cada hospital da administração direta assumiu? | 10 hospitais (HRSAM, HRT, HRC, HRBZ, HRGU, HRAN, HRPL, HRS, HRL, HRG); matriz de indicadores, sem lista de serviços | [AGL HRG](https://www.saude.df.gov.br/documents/37101/0/Acordo+de+Gest%C3%A3o+Local+-+HRG.pdf/1002ee03-ea39-0675-612c-1ff161fe9e2a?t=1703760997133); [Relatório AGL 2024](https://info.saude.df.gov.br/wp-content/uploads/2025/05/Relatorio_3o_quad___Resultado_Final_HOSPITALAR____consolidado__.docx___Documentos_Google.pdf) |

## 6\. Fontes de consulta de informações atuais da SES-DF (FON)

| ID | Fonte | Conteúdo | Uso no HTML | Forma de acesso | URL |
| :---- | :---- | :---- | :---- | :---- | :---- |
| FON-01 | Portal InfoSaúde (DGIE/SUPLANS) | Painéis, produção, leitos, planejamento, transparência | Fonte principal de dados atualizados | Web e painéis | [InfoSaúde](https://info.saude.df.gov.br/) |
| FON-02 | Sala de Situação | Produção SIA/SIH, procedimentos cirúrgicos, OPME, leitos | Produção observada (CMP-26) | Painéis | [Sala de Situação](https://info.saude.df.gov.br/sala-de-situacao/) |
| FON-03 | Orientações de faturamento (GEPI) | Regras de registro BPA, APAC, AIH, RAAS | Instrumento de registro (CMP-11) | Web | [GEPI](https://info.saude.df.gov.br/sala-de-situacao/painel-infosaude-orientacoes-gerais-de-faturamento-gepi/) |
| FON-04 | Carteira de Serviços para o cidadão (InfoSaúde) | 24 serviços, com informações de acesso | Camada de informação ao cidadão | Web | [InfoSaúde](https://info.saude.df.gov.br/transparencia-e-prestacao-de-contas/carteira-de-servicos/) |
| FON-05 | CNES / DATASUS | Estabelecimentos, leitos, serviços, habilitações e equipes do DF | CMP-12, CMP-13, CMP-19 | Web e download | [CNES](https://cnes.datasus.gov.br) |
| FON-06 | SIGTAP | Tabela por competência mensal | CMP-02 a CMP-11 | Web e download | [SIGTAP](http://sigtap.datasus.gov.br) |
| FON-07 | Portarias SES-DF / SINJ-DF | Normas distritais atualizadas | Base normativa | Web | [Portarias SES](https://www.saude.df.gov.br/portarias-ses); [SINJ-DF](https://www.sinj.df.gov.br/) |
| FON-08 | Consultas públicas da SES-DF | Minutas de carteiras (CaSAPS-DF, AAE) | Acompanhar novas edições | Web | [Consultas públicas](https://saude.df.gov.br/consultas-publicas) |
| FON-09 | Plano Distrital de Saúde e PAS | Objetivos, metas e indicadores | CMP-29 | PDF | [PDS](https://info.saude.df.gov.br/transparencia-e-prestacao-de-contas/plano-distrital-de-saude-pds/) |
| FON-10 | Portal de Indicadores do IGESDF | Indicadores das unidades do IGESDF | Desempenho do Hospital de Base, HRSM e UPAs | Web | [IGESDF](https://indicadores.igesdf.org.br/) |
| FON-11 | Wiki SES-DF | Sistemas, fluxos e referências técnicas | Documentação de apoio | Web | [Wiki SES-DF](https://wiki.saude.df.gov.br/index.php/InfoSa%C3%BAde) |
| FON-12 | Fontes internas do projeto | Bases de trabalho do projeto (acesso restrito à equipe) | Carteira declarada (CMP-16 a CMP-18, CMP-31 a CMP-33) | Documentação interna do projeto | — |
| FON-13 | Página de Notas Técnicas da SES-DF | Notas técnicas de acesso e regulação e a Carteira de Ortopedia | Critérios de encaminhamento e referência por especialidade (CMP de acesso) | Web | [SES-DF](https://www.saude.df.gov.br/notas-tecnicas) |

## 7\. Alertas de qualidade (ALE)

| ID | Alerta | Correção ou orientação |
| :---- | :---- | :---- |
| ALE-01 | Confundir Carteira com Carta de Serviços | Usar as definições da Portaria 632/2025 (CON-01 e CON-02). A página "Carteira de Serviços" do InfoSaúde funciona, na prática, como carta ao cidadão. |
| ALE-02 | Considerar o SIGTAP um sistema que recebe a produção (erro encontrado em um dos modelos) | O SIGTAP é a tabela. A produção é registrada no SIA, no SIH e no SISAB. |
| ALE-03 | Atribuir ao RD 1030/2006 a divisão básica/suplementar/acessória | Essa divisão vem da Ley 16/2003 alterada pelo RDL 16/2012. |
| ALE-04 | Citar o Despacho 12456-B/2023 (Portugal) como vigente | Foi revogado pelo Despacho 14237/2024. |
| ALE-05 | Tratar o Previne Brasil como modelo atual | O modelo vigente é o da Portaria GM/MS 3.493/2024. |
| ALE-06 | Afirmar que a regulação "devolve" automaticamente os encaminhamentos de itens da carteira | É uma prática possível de gestão, não uma regra nacional. |
| ALE-07 | Tratar o número de itens da CaSAPS como exato | As fontes divergem (210 no artigo científico, 212 na notícia do MS). |
| ALE-08 | Ler a presença no CNES ou na norma como oferta efetiva | Separar os quatro planos (CON-07). |
| ALE-09 | Citar a Portaria 773/2018 como vigente (o PDS 2024-2027, p. 104, ainda faz isso) | Foi revogada pela Portaria 632/2025, art. 81\. Usar a 632/2025 e o termo AAE em vez de AASE. |
| ALE-10 | Ler a PAS 2026 como se a consulta pública da CaSAAE ainda fosse acontecer | A PAS foi aprovada em 18/03/2026, mas a consulta já tinha ocorrido de 8/12/2025 a 7/1/2026. |
| ALE-11 | Copiar remissões internas da Portaria 1.357/2018 sem conferir | O art. 23, I, remete ao art. 21 quando a lista está no art. 22; o art. 25 remete a um "artigo XXX"; o art. 4º tem incisos faltando na numeração. |
| ALE-12 | Afirmar que a SES-DF tem carteira hospitalar formal | Não foi localizada. Tratar a carteira do projeto como proposta de instrumento novo, apoiada nos documentos da seção 2.4. |

## 8\. Pendências de verificação (PEN)

| ID | Pendência | Situação em 26/09/2026 | Próxima ação |
| :---- | :---- | :---- | :---- |
| PEN-01 | Texto integral da Portaria SES-DF 1.357/2018 (atenção hospitalar) | Resolvida. Texto localizado no SINJ-DF; vigente (NOR-23 e seção 2.4) | Nenhuma |
| PEN-02 | Verificar se a Portaria SES-DF 773/2018 foi revogada pela 632/2025 | Resolvida. Revogada pelo art. 81 da Portaria 632/2025 (NOR-22) | Nenhuma |
| PEN-03 | Situação da consulta pública da Carteira da AAE (PAS 2026, ações 139 e 142\) | Parcialmente resolvida. Consulta de 8/12/2025 a 7/1/2026; publicação final não localizada (EXE-03) | Acompanhar o DODF; contato GESAMB: [gesamb@saude.df.gov.br](mailto:gesamb@saude.df.gov.br), (61) 3449-4113 |
| PEN-04 | Existência de uma carteira hospitalar formal da SES-DF | Resolvida com ressalva. Não foi localizada carteira hospitalar formal; há instrumentos parciais (seção 2.4) | Confirmar com a SEGHOSP / SAIS; localizar no SEI o ato ou processo da Carteira de Ortopedia (EXE-11) |
| PEN-05 | Portaria que institui a CaSAPS-DF e a CPRCS | Aberta | Confirmar no SINJ-DF |
| PEN-06 | Conteúdo do Plano Distrital de Serviços Cirúrgicos 2023/2026 | Parcial. Só os quadros reproduzidos no PDS, pp. 118-119 (REL-09) | Solicitar o texto integral à CATES/DUAEC ou à SUPLANS |

## 9\. Referências principais

- Ministério da Saúde. CaSAPS, versão profissionais e gestores: [https\://www\.gov.br/saude/pt-br/composicao/saps/publicacoes/cartazes-e-cartilhas/casaps\_versao\_profissionais\_saude\_gestores\_completa.pdf](https://www.gov.br/saude/pt-br/composicao/saps/publicacoes/cartazes-e-cartilhas/casaps_versao_profissionais_saude_gestores_completa.pdf)  
- Ciência & Saúde Coletiva (2020), construção da CaSAPS: [https\://www\.scielo.br/j/csc/a/htnJGKWddBNkc6rjgyZLGKG/?lang=pt](https://www.scielo.br/j/csc/a/htnJGKWddBNkc6rjgyZLGKG/?lang=pt)  
- Salazar, Campos e Luiza (2017), carteira do Rio: [https\://www\.scielosp.org/article/csc/2017.v22n3/783-796/pt/](https://www.scielosp.org/article/csc/2017.v22n3/783-796/pt/)  
- EPSJV/Fiocruz, debate sobre a CaSAPS: [https\://www\.epsjv.fiocruz.br/noticias/reportagem/proposta-de-carteira-de-servicos-da-atencao-primaria-divide-opinioes](https://www.epsjv.fiocruz.br/noticias/reportagem/proposta-de-carteira-de-servicos-da-atencao-primaria-divide-opinioes)  
- Decreto nº 7.508/2011: [https\://www\.planalto.gov.br/ccivil\_03/\_ato2011-2014/2011/decreto/d7508.htm](https://www.planalto.gov.br/ccivil_03/_ato2011-2014/2011/decreto/d7508.htm)  
- Portaria GM/MS nº 841/2012 (RENASES): [https\://bvsms.saude.gov.br/bvs/saudelegis/gm/2012/prt0841\_02\_05\_2012.html](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2012/prt0841_02_05_2012.html)  
- PNAB, Portaria nº 2.436/2017: [https\://bvsms.saude.gov.br/bvs/saudelegis/gm/2017/prt2436\_22\_09\_2017.html](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2017/prt2436_22_09_2017.html)  
- Portaria GM/MS nº 3.410/2013: [https\://bvsms.saude.gov.br/bvs/saudelegis/gm/2014/prt3410\_30\_12\_2013.html](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2014/prt3410_30_12_2013.html)  
- Portaria GM/MS nº 3.493/2024: [https\://bvsms.saude.gov.br/bvs/saudelegis/gm/2024/prt3493\_11\_04\_2024.html](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2024/prt3493_11_04_2024.html)  
- Lei nº 13.460/2017: [https\://www\.planalto.gov.br/ccivil\_03/\_ato2015-2018/2017/lei/l13460.htm](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2017/lei/l13460.htm)  
- Portaria SES-DF nº 77/2017: [https\://www\.saude.df.gov.br/documents/37101/45840/Portaria-SES\_DF-n%C2%BA-77-2017-Esstabelece-a-Pol%C3%ADtica-de-Aten%C3%A7%C3%A3o-Prim%C3%A1ria-%C3%A0-Sa%C3%BAde-do-Distrito-Federal.pdf/5092cc7f-3559-c0de-4bb8-14c88426eee0?t=1648125104991](https://www.saude.df.gov.br/documents/37101/45840/Portaria-SES_DF-n%C2%BA-77-2017-Esstabelece-a-Pol%C3%ADtica-de-Aten%C3%A7%C3%A3o-Prim%C3%A1ria-%C3%A0-Sa%C3%BAde-do-Distrito-Federal.pdf/5092cc7f-3559-c0de-4bb8-14c88426eee0?t=1648125104991)  
- Portaria SES-DF nº 632/2025 (PDAAE): [https\://www\.sinj.df.gov.br/sinj/Norma/b7211d3fbde043308032717260456eb6/ses\_prt\_632\_2025.html](https://www.sinj.df.gov.br/sinj/Norma/b7211d3fbde043308032717260456eb6/ses_prt_632_2025.html)  
- CaSAPS-DF, 3ª edição (2025): [https\://www\.saude.df.gov.br/documents/37101/620159/CaSAPS\_DF\_\_\_versao\_FINAL\_10\_03\_25\_\_com\_ficha\_catalografica\_.docx+(1).pdf/95aab6d1-6413-00fa-3445-0cd7b12dfc22?t=1742320979393](https://www.saude.df.gov.br/documents/37101/620159/CaSAPS_DF___versao_FINAL_10_03_25__com_ficha_catalografica_.docx+\(1\).pdf/95aab6d1-6413-00fa-3445-0cd7b12dfc22?t=1742320979393)  
- PDS 2024-2027: [https\://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS\_2024\_2027\_\_\_VERSAO\_ATUALIZADA\_POS\_APROVACAO\_DO\_CG.pdf](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf)  
- PAS 2026: [https\://info.saude.df.gov.br/wp-content/uploads/2026/04/PAS\_2026\_Aprovada\_pelo\_Colegiado\_de\_Gestao\_SESDF\_18.03.2026\_Revisado.pdf](https://info.saude.df.gov.br/wp-content/uploads/2026/04/PAS_2026_Aprovada_pelo_Colegiado_de_Gestao_SESDF_18.03.2026_Revisado.pdf)  
- A Reforma da Saúde de Brasília (Ciência & Saúde Coletiva): [https\://www\.scielo.br/j/csc/a/Tt8gBMPmfjQSPfStTWNcnsQ/](https://www.scielo.br/j/csc/a/Tt8gBMPmfjQSPfStTWNcnsQ/)  
- Portaria SES-DF nº 1.357/2018 (atenção hospitalar): [https\://www\.sinj.df.gov.br/sinj/Norma/536a9f4da0a9459f96bd8c3bc06dfc50/Portaria\_1357\_06\_12\_2018.html](https://www.sinj.df.gov.br/sinj/Norma/536a9f4da0a9459f96bd8c3bc06dfc50/Portaria_1357_06_12_2018.html)  
- Portaria SES-DF nº 773/2018 (revogada): [https\://www\.sinj.df.gov.br/sinj/Norma/82c3196081194fa3b7cd6862311bcaca/Portaria\_773\_19\_07\_2018.html](https://www.sinj.df.gov.br/sinj/Norma/82c3196081194fa3b7cd6862311bcaca/Portaria_773_19_07_2018.html)  
- Portaria SES-DF nº 632/2025, versão com art. 81: [https\://www\.sinj.df.gov.br/sinj/Norma/b7211d3fbde043308032717260456eb6/Portaria\_632\_16\_12\_2025.html](https://www.sinj.df.gov.br/sinj/Norma/b7211d3fbde043308032717260456eb6/Portaria_632_16_12_2025.html)  
- Portaria SES-DF nº 432/2023 (contratualização de hospitais): [https\://www\.sinj.df.gov.br/sinj/Norma/2033976f5af94d1783ed5bac13f4a8c2/Portaria\_432\_27\_10\_2023.html](https://www.sinj.df.gov.br/sinj/Norma/2033976f5af94d1783ed5bac13f4a8c2/Portaria_432_27_10_2023.html)  
- Carteira de Serviços Ortopedia SES-DF: [https\://www\.saude.df.gov.br/documents/37101/0/Carteira\_de\_Servicos\_Ortopedia\_SES\_\_1\_.pdf/59232908-e888-39cb-634d-16669bdea46c?t=1699959876095](https://www.saude.df.gov.br/documents/37101/0/Carteira_de_Servicos_Ortopedia_SES__1_.pdf/59232908-e888-39cb-634d-16669bdea46c?t=1699959876095)  
- Convênio SES-DF e HUB-UnB (Documento Descritivo): [https\://www\.saude.df.gov.br/documents/37101/0/Convenio\_027540\_2024\_SESDF\_EBSERH\_HUB\_UNB.pdf/198f9845-2fdf-6b7e-5b95-7146d1904248?t=1733492986406](https://www.saude.df.gov.br/documents/37101/0/Convenio_027540_2024_SESDF_EBSERH_HUB_UNB.pdf/198f9845-2fdf-6b7e-5b95-7146d1904248?t=1733492986406)  
- Consulta pública da CaSAAE-DF: [https\://www\.saude.df.gov.br/web/guest/w/sa%C3%BAde-lan%C3%A7a-consulta-p%C3%BAblica-para-servi%C3%A7os-da-aten%C3%A7%C3%A3o-ambulatorial-especializada-do-df](https://www.saude.df.gov.br/web/guest/w/sa%C3%BAde-lan%C3%A7a-consulta-p%C3%BAblica-para-servi%C3%A7os-da-aten%C3%A7%C3%A3o-ambulatorial-especializada-do-df)  
- Acordo de Gestão Local HRG 2024: [https\://www\.saude.df.gov.br/documents/37101/0/Acordo+de+Gest%C3%A3o+Local+-+HRG.pdf/1002ee03-ea39-0675-612c-1ff161fe9e2a?t=1703760997133](https://www.saude.df.gov.br/documents/37101/0/Acordo+de+Gest%C3%A3o+Local+-+HRG.pdf/1002ee03-ea39-0675-612c-1ff161fe9e2a?t=1703760997133)  
- Carteira de Serviços do Cuidado Farmacêutico: [https\://saude.df.gov.br/documents/37101/0/Carteira\_de\_servicos.pdf/07e9b17f-922d-500d-261e-81a5832aeb08?t=1757610677748](https://saude.df.gov.br/documents/37101/0/Carteira_de_servicos.pdf/07e9b17f-922d-500d-261e-81a5832aeb08?t=1757610677748)  
- Real Decreto 1030/2006: [https\://www\.boe.es/buscar/act.php?id=BOE-A-2006-16212](https://www.boe.es/buscar/act.php?id=BOE-A-2006-16212)  
- Despacho 14237/2024 (Portugal): [https\://diariodarepublica.pt/dr/detalhe/despacho/14237-2024-898377839](https://diariodarepublica.pt/dr/detalhe/despacho/14237-2024-898377839)  
- Comunidad de Madrid, Cartera de Servicios: [https\://www\.comunidad.madrid/salud/cartera-servicios-comunes-sistema-nacional-salud](https://www.comunidad.madrid/salud/cartera-servicios-comunes-sistema-nacional-salud)

- ## Governança, participação social e monitoramento da Carteira

- Eixo GOV • Incorporado à base em 26/09/2026 • Versão 1.2  
- Natureza deste eixo: base normativa acompanhada de proposta operacional para o Projeto Carteira de Serviços da SES-DF. A matriz, as etapas, os campos e os prazos gerenciais sugeridos abaixo não constituem resolução do CSDF, norma da SES-DF ou fluxo já implantado. Devem ser validados pelas instâncias competentes antes de sua adoção institucional.

- ### Finalidade e fundamento

- GOV-01 \| Finalidade. Integrar o controle social desde o diagnóstico das necessidades até a avaliação da oferta efetivamente entregue, relacionando a Carteira ao Plano Distrital de Saúde (PDS), à Programação Anual de Saúde (PAS), ao Relatório Detalhado do Quadrimestre Anterior (RDQA) e ao Relatório Anual de Gestão (RAG). A Carteira deve apoiar, e não substituir, esses instrumentos.  
- GOV-02 \| Competência geral. O Conselho de Saúde é permanente e deliberativo e atua na formulação de estratégias e no controle da execução da política de saúde, inclusive em seus aspectos econômicos e financeiros (Lei nº 8.142/1990, art. 1º, § 2º). Fonte: [https\://www\.planalto.gov.br/ccivil\_03/leis/l8142.htm](https://www.planalto.gov.br/ccivil_03/leis/l8142.htm)  
- GOV-03 \| Conexão específica no DF. A Lei nº 4.604/2011 atribui ao CSDF aprovar diretrizes da política de saúde; estabelecer diretrizes e critérios relativos à localização e ao tipo de unidades; apoiar estudos; requisitar documentos; e promover diligências. Ao apreciar os planos, deve examinar a suficiência das ações e metas diante da situação epidemiológica e da oferta assistencial (art. 16, II, VI, XIII, XVIII, XIX e § 1º, III). Fonte: [https\://www\.sinj.df.gov.br/sinj/Norma/68849/Lei\_4604\_2011.html](https://www.sinj.df.gov.br/sinj/Norma/68849/Lei_4604_2011.html)  
- GOV-04 \| Participação territorial. Os Conselhos Regionais de Saúde (CRS) participam da formulação e do controle da política em seu âmbito, estabelecem diretrizes para o planejamento regional e acompanham os serviços. A distribuição concreta de matérias entre CRS e CSDF deve respeitar suas competências e regimentos, sem presumir hierarquia recursal automática ou poder de um CRS para decidir isoladamente a oferta de outras regiões (Resolução CSDF nº 390/2012, Primeira e Quinta Diretrizes). Fonte: [https\://www\.sinj.df.gov.br/sinj/Norma/71745/csdf\_res\_390\_2012.html](https://www.sinj.df.gov.br/sinj/Norma/71745/csdf_res_390_2012.html)  
- GOV-05 \| Planejamento e prestação de contas. A LC nº 141/2012 prevê deliberação dos conselhos sobre diretrizes de prioridades, aprovação da programação anual, informação sobre oferta e produção no relatório quadrimestral e avaliação quadrimestral com indicação de medidas corretivas (arts. 30, § 4º, 36 e 41). A Resolução CNS nº 453/2012 detalha competências sobre planos, relatórios e fiscalização. Fontes: [https\://www\.planalto.gov.br/ccivil\_03/leis/lcp/lcp141.htm](https://www.planalto.gov.br/ccivil_03/leis/lcp/lcp141.htm) ; [https\://www\.gov.br/conselho-nacional-de-saude/pt-br/atos-normativos/resolucoes/2012/resolucao-no-453.pdf](https://www.gov.br/conselho-nacional-de-saude/pt-br/atos-normativos/resolucoes/2012/resolucao-no-453.pdf)

- ### Limites de atuação e classificação das mudanças

- GOV-06 \| Separação de responsabilidades. A gestão e as equipes técnicas elaboram e validam os dados, estimam capacidade, custos e riscos, organizam a execução e respondem pelos serviços. Os conselhos contribuem com necessidades e prioridades, apreciam e deliberam sobre matérias de sua competência e fiscalizam a execução. A participação social não substitui validação clínica, sanitária, orçamentária ou administrativa, nem a aprovação de um conselho transfere a ele a responsabilidade executiva da SES-DF. Referência para a distinção: [https\://www\.planalto.gov.br/ccivil\_03/leis/l8142.htm](https://www.planalto.gov.br/ccivil_03/leis/l8142.htm)  
- GOV-07 \| Sem aprovação universal presumida. As normas gerais examinadas não instituem rito único de aprovação de todo documento denominado Carteira de Serviços. Antes de definir a tramitação de uma alteração, registrar a norma setorial aplicável, a competência decisória, a eventual exigência de apreciação ou deliberação e a necessidade de homologação/publicação. No DF, as decisões do CSDF consubstanciadas em resoluções são homologadas pelo Secretário de Saúde, conforme art. 1º da Lei nº 4.604/2011. Fonte: [https\://www\.sinj.df.gov.br/sinj/Norma/68849/Lei\_4604\_2011.html](https://www.sinj.df.gov.br/sinj/Norma/68849/Lei_4604_2011.html)  
- Classificação operacional proposta:  
- Tipo A \| Atualização descritiva sem mudança da oferta: correção de nome, contato, endereço informativo ou erro de cadastro. Fluxo técnico de validação, registro de versão e publicidade. Alteração de horário que reduza acesso ou capacidade não deve ser classificada automaticamente como simples atualização cadastral.  
- Tipo B \| Mudança assistencial relevante: inclusão, suspensão, redução, transferência ou redefinição de serviço, capacidade ou referência territorial. Exigir estudo de impacto e encaminhamento à instância de controle social competente, identificando no processo se o ato é de ciência, apreciação, recomendação ou deliberação.  
- Tipo C \| Mudança de planejamento, metas ou prioridades: articular à revisão dos instrumentos pertinentes e observar as competências deliberativas aplicáveis. Para a PAS, a aprovação pelo Conselho deve ocorrer antes do encaminhamento da LDO do exercício correspondente, nos termos do art. 36, § 2º, da LC nº 141/2012. Fonte: [https\://www\.planalto.gov.br/ccivil\_03/leis/lcp/lcp141.htm](https://www.planalto.gov.br/ccivil_03/leis/lcp/lcp141.htm)  
- Intercorrência urgente \| A proposta de fluxo não deve impedir providências imediatas de proteção à vida e à segurança assistencial. Recomenda-se documentar a justificativa, as medidas de continuidade, a comunicação aos afetados e o encaminhamento ao controle social no prazo aplicável, sem tratar a urgência como dispensa permanente de prestação de contas.

- ### Fluxo de participação proposto

- Sequência: abertura e classificação → diagnóstico técnico e escuta territorial → análise regional → consolidação distrital → apreciação/deliberação competente → resposta e formalização → implementação e divulgação → monitoramento e revisão.  
- FLX-01 \| Abertura. A coordenação do projeto registra a demanda, versão afetada, unidade/serviço, territórios, motivo e classificação A/B/C. A área competente confirma o rito aplicável. Produto: ficha de alteração com responsável e fundamento.  
- FLX-02 \| Diagnóstico e escuta. Unidades, áreas técnicas e planejamento consolidam necessidades, oferta, capacidade operacional, produção, filas e barreiras de acesso. CRS e representações de usuários contribuem com evidências territoriais. Produto: diagnóstico com fontes, datas, limitações e registro das contribuições.  
- FLX-03 \| Análise regional. A gestão regional apresenta a proposta e as alternativas ao(s) CRS afetado(s), respeitando pauta e regimento. Registrar ata, manifestação, pedidos de complementação e divergências; uma reunião de apresentação não deve ser registrada como aprovação. Produto: manifestação regional identificável.  
- FLX-04 \| Consolidação distrital. A coordenação reúne os diagnósticos, compara impactos entre territórios, incorpora ou justifica o não acolhimento das contribuições e articula o tema com PDS/PAS e financiamento. Mudanças de alcance distrital ou inter-regional devem ser encaminhadas ao CSDF conforme sua competência. Produto: dossiê consolidado e quadro de respostas.  
- FLX-05 \| Apreciação e deliberação. O CSDF recebe o dossiê e o examina segundo seu regimento, com subsídio de comissão competente quando cabível. A decisão colegiada permanece com o plenário quando exigida. Produto: parecer, recomendação ou resolução, conforme a natureza do ato, com condições, responsáveis e encaminhamentos claramente registrados.  
- FLX-06 \| Resposta e formalização. A gestão registra acatamento ou justificativa, adequa o plano de execução e providencia os atos de sua competência. A Lei nº 4.604/2011, art. 16, § 2º, prevê manifestação do Secretário em 30 dias sobre as considerações do Conselho; a aplicação ao processo deve ser verificada no enquadramento da matéria. Registrar separadamente decisão, homologação e publicação, sem presumir que uma substitui a outra. Fonte: [https\://www\.sinj.df.gov.br/sinj/Norma/68849/Lei\_4604\_2011.html](https://www.sinj.df.gov.br/sinj/Norma/68849/Lei_4604_2011.html)  
- FLX-07 \| Implementação e divulgação. A gestão executa as medidas, atualiza a versão oficial da Carteira e informa usuários, unidades, regulação e conselhos envolvidos. Produto: versão publicada, data de vigência, orientação de acesso e plano de continuidade quando houver suspensão ou transferência.  
- FLX-08 \| Monitoramento e revisão. Unidades e gestão regional alimentam indicadores; CRS acompanham efeitos territoriais; o CSDF avalia repercussões e encaminha medidas corretivas no âmbito de suas atribuições. Recomenda-se integrar o painel da Carteira ao ciclo quadrimestral e à avaliação anual, sem substituir os relatórios legais. Base da periodicidade quadrimestral: LC nº 141/2012, arts. 36 e 41\. Fonte: [https\://www\.planalto.gov.br/ccivil\_03/leis/lcp/lcp141.htm](https://www.planalto.gov.br/ccivil_03/leis/lcp/lcp141.htm)

- ### Dossiê mínimo e rastreabilidade

- GOV-08 \| Dossiê recomendado. Conter: versão atual e proposta; unidades, serviços e população afetada; justificativa epidemiológica; necessidades não atendidas; capacidade cadastrada e capacidade operacional; produção e acesso; impactos territoriais; riscos e alternativas; recursos e custos; vínculo com metas do PDS/PAS; manifestação dos CRS; respostas técnicas; cronograma; responsáveis; indicadores; e ato decisório exigido.  
- GOV-09 \| Registro de manifestações. Para cada contribuição, registrar origem, data, síntese, documento comprobatório, análise técnica, decisão sobre acolhimento, justificativa, responsável e prazo. Recomenda-se devolver aos CRS e ao CSDF o resultado da análise, inclusive quando houver discordância, para não limitar a participação a uma coleta sem resposta.  
- GOV-10 \| Integração com os quatro planos da oferta (CON-07). Confrontar direito/norma aplicável, capacidade cadastrada ou declarada, compromisso pactuado/contratado e produção realizada. Complementar com disponibilidade operacional e acesso efetivo; CNES, publicação da Carteira ou produção passada, isoladamente, não devem ser usados como prova suficiente de disponibilidade atual.

- ### Campos sugeridos para a ferramenta de consulta

- GOV-11 \| Entidade proposta: evento de governança. Relacionar cada evento à versão da Carteira e a um ou mais pares unidade × serviço/procedimento, sem obrigar que toda manifestação corresponda a apenas um procedimento.  
- Identificação: id\_evento; id\_versao\_carteira; unidades\_servicos\_afetados; territorios\_afetados; tipo\_alteracao; motivo; numero\_processo.  
- Tramitação: instancia (CRS/CSDF/gestão); nome\_colegiado; comissao; data\_encaminhamento; data\_reuniao; natureza\_manifestacao; numero\_ato; url\_documento; fundamento\_competencia.  
- Decisão e execução: recomendacoes\_condicionantes; resposta\_gestao; justificativa; responsavel; prazo; data\_homologacao; data\_publicacao; data\_vigencia; indicador\_vinculado; evidencia\_conclusao.  
- Estados sugeridos: em estudo; em escuta territorial; em análise regional; em consolidação; encaminhado ao CSDF; em apreciação; deliberado; aguardando formalização; em implementação; em monitoramento; concluído; devolvido para complementação. Separar situação da tramitação, natureza da manifestação e situação operacional do serviço.  
- Regras de qualidade propostas: usar “não se aplica” com justificativa e não campos vazios para etapas dispensadas; “aprovado” exige ato que comprove aprovação; “apresentado” ou “ciência” não equivale a “deliberado”; manter fontes, datas e histórico de versões; disponibilizar informações públicas agregadas, sem dados identificáveis de pacientes.

- ### Indicadores e rotina de acompanhamento

- GOV-12 \| Painel proposto. Exibir por unidade, serviço e território, com referência temporal e fonte. Metas e limiares de alerta devem ser definidos e validados institucionalmente; não são estabelecidos neste estudo.  
- IND-GOV-01 \| Disponibilidade operacional: número de pares unidade × serviço previstos e ativos / número de pares previstos para o período × 100\. Separar ativos, parciais, suspensos e sem informação; explicitar a cobertura dos dados.  
- IND-GOV-02 \| Execução da oferta: produção realizada / meta pactuada para o mesmo serviço e período × 100\. Não somar procedimentos heterogêneos como se fossem equivalentes; distinguir produção de vagas ofertadas.  
- IND-GOV-03 \| Acesso: fila registrada e tempo de espera, com mediana e percentil 90 quando viáveis. Definir se o tempo mede usuários ainda em fila ou atendimentos realizados. A fila registrada não representa, sozinha, toda a necessidade não atendida.  
- IND-GOV-04 \| Continuidade: dias de suspensão, causa, pessoas potencialmente afetadas, alternativa de atendimento e previsão de restabelecimento. IND-GOV-05 \| Equidade: comparação de oferta, acesso e resultados entre territórios, considerando população e necessidades.  
- IND-GOV-06 \| Resposta às manifestações: proporção respondida no prazo aplicável e pendências por responsável. IND-GOV-07 \| Medidas corretivas: proporção concluída no prazo, com evidência de execução, e atrasos críticos.  
- Rotina sugerida: atualização operacional mensal ou conforme a disponibilidade da fonte; apresentação consolidada no ciclo quadrimestral; revisão anual articulada à PAS e ao RAG; comunicação extraordinária diante de interrupções relevantes. Somente a periodicidade legal dos instrumentos deve ser tratada como obrigação normativa; a atualização mensal é recomendação de projeto. Base legal do ciclo quadrimestral: [https\://www\.planalto.gov.br/ccivil\_03/leis/lcp/lcp141.htm](https://www.planalto.gov.br/ccivil_03/leis/lcp/lcp141.htm)

- ### Validações institucionais pendentes

- PEN-GOV-01 \| Confirmar o ato específico de instituição/revisão de cada Carteira, seu rito de participação e a necessidade de aprovação, homologação e publicação. Responsável proposto: coordenação do projeto com as áreas normativa/jurídica competentes.  
- PEN-GOV-02 \| Confirmar regimentos vigentes, comissão competente do CSDF, regras dos CRS envolvidos e fluxo formal de encaminhamento. Responsável proposto: coordenação com as secretarias dos conselhos. Não se presume que o fluxo proposto já tenha sido acordado.  
- PEN-GOV-03 \| Pactuar responsáveis institucionais, calendário, indicadores e fontes. Definir os prazos gerenciais que não estejam previstos em norma. Responsável proposto: gestão da SES-DF, áreas técnicas e instâncias de controle social, respeitadas suas competências.  
- PEN-GOV-04 \| Harmonizar o calendário de prestação de contas. A LC nº 141/2012, art. 36, § 1º, prevê envio do relatório de gestão ao conselho até 30 de março do ano seguinte, enquanto o texto da Lei distrital nº 4.604/2011, art. 16, § 3º, menciona 30 de abril. Não adotar o prazo distrital isoladamente: usar o marco federal no planejamento e submeter a harmonização à área competente. Fontes: [https\://www\.planalto.gov.br/ccivil\_03/leis/lcp/lcp141.htm](https://www.planalto.gov.br/ccivil_03/leis/lcp/lcp141.htm) ; [https\://www\.sinj.df.gov.br/sinj/Norma/68849/Lei\_4604\_2011.html](https://www.sinj.df.gov.br/sinj/Norma/68849/Lei_4604_2011.html)

- ### Matriz de responsabilidades proposta

- MAT-GOV \| Leitura: a coluna de gestão identifica quem prepara e executa; as colunas dos conselhos identificam participação e deliberação dentro de suas competências. A matriz não cria atribuições, não torna consultiva uma competência deliberativa e não transfere ao conselho a responsabilidade executiva. “Coordenação” significa a instância que a SES-DF designar formalmente para o projeto.  
- 

| Atividade / produto | Gestão e equipes SES-DF | Conselhos Regionais | CSDF |
| :---- | :---- | :---- | :---- |
| Diagnóstico de necessidades e oferta | Unidades e áreas técnicas produzem dados; planejamento consolida. | Contribuem com necessidades e evidências territoriais. | Requisita informações e subsidia prioridades distritais. |
| Critérios e prioridades | Coordenação apresenta alternativas, impactos e viabilidade. | Discutem prioridades regionais, conforme competência. | Delibera sobre diretrizes e matérias de sua competência. |
| Proposta de alteração e dossiê | Coordenação elabora; áreas técnicas validam capacidade, acesso e custos. | Analisam impactos locais e registram manifestação. | Aprecia impactos distritais/inter-regionais e matérias encaminhadas. |
| Enquadramento e rito decisório | Gestão, com apoio normativo/jurídico, identifica atos e competências. | Observam o regimento e a competência territorial. | Observa o regimento e define tratamento no âmbito colegiado. |
| Parecer / recomendação / resolução | Presta esclarecimentos e responde às considerações. | Emitem manifestação ou deliberação no próprio âmbito. | Comissões subsidiam; plenário delibera quando cabível. |
| Formalização e publicação | Autoridade competente formaliza; Secretário homologa resoluções do CSDF conforme a lei. | Acompanham atos e devolutivas referentes ao território. | Registra e acompanha suas decisões e encaminhamentos. |
| Implementação da Carteira | Gestores regionais, unidades e áreas responsáveis executam e atualizam dados. | Acompanham acesso e continuidade local; apontam problemas. | Controla e fiscaliza a execução da política. |
| Monitoramento e prestação de contas | Planejamento e gestores consolidam indicadores, RDQA/RAG e justificativas. | Verificam efeitos territoriais e encaminham evidências. | Avalia relatórios e indica medidas corretivas nas competências legais. |
| Correção e revisão | Gestão define e executa plano corretivo com prazo, orçamento e responsáveis. | Acompanham a correção e comunicam persistência dos problemas. | Acompanha respostas; aprecia revisões que integrem sua competência. |

- 