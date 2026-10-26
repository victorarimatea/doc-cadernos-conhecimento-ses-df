---
id: cnes
nome_curto: CNES
titulo: "CNES: o cadastro oficial dos estabelecimentos de saúde"
resumo: "O que o Cadastro Nacional de Estabelecimentos de Saúde registra, quem responde por ele na SES-DF, o que precisa ser atualizado a cada mês e como ler os dados sem confundir cadastro com capacidade real."
versao: v1.0
revisao: 2026-10-26
situacao: com pendências
---

# CNES: o cadastro oficial dos estabelecimentos de saúde

Conhecimento · CNES · **v1.0** (aprovada em 26/10/2026) · base normativa conferida em fonte primária em 22, 24, 25 e 26/10/2026, com [pendências](README.md#pendências)
*Material de estudo. Não substitui a publicação oficial das normas citadas.*

## 1. O que é

O **CNES** (Cadastro Nacional de Estabelecimentos de Saúde) é o registro oficial de todos os estabelecimentos de saúde do país, públicos e privados, integrantes ou não do SUS. É ao mesmo tempo documento público e sistema de informação: registra a estrutura de cada unidade (instalações, leitos, equipamentos), os serviços que oferece, as habilitações que recebeu e os profissionais que nela trabalham ([PRC GM/MS 1/2017](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-CONSOLIDACAO-GMMS-1-2017-ORGANIZACAO-E-FUNCIONAMENTO-DO-SUS.md), arts. 358 e 359).

O cadastro é **obrigatório** para qualquer estabelecimento funcionar e deve vir antes das licenças sanitárias (art. 361). É a **fonte oficial** sobre estabelecimentos de saúde: todo sistema que use esses dados deve adotá-lo, e todas as políticas nacionais de saúde partem dele (art. 362).

O CNES **não** é instrumento de controle nem de indução de política. A própria norma diz que ele existe só para representar, do modo mais fiel possível, a realidade de cada lugar (art. 359, parágrafo único). Também não mede o que o hospital consegue fazer num dia comum: registra o que existe e foi declarado.

> [!NOTE]
> **Cadastro declarado, com efeito real.** O CNES é preenchido pelo próprio estabelecimento, mas o que está nele decide o que o hospital pode registrar e receber: os sistemas de produção do SUS conferem cada procedimento contra o cadastro (ver o [caderno de SIGTAP](../sigtap/caderno.md)).

## 2. Origem e base normativa

O CNES é regido hoje por duas portarias de consolidação do Ministério da Saúde. No DF, o Regimento Interno da SES-DF diz quais unidades fazem cada tarefa do cadastro. As portarias que criaram as regras foram revogadas por consolidação, mas continuam úteis para entender o problema que cada regra quis resolver; por isso ficam numa tabela à parte, em ordem cronológica.

**Normas vigentes, por esfera**

| Esfera | Norma | Dispositivo | O que estabelece | Situação (26/10/2026) |
|---|---|---|---|---|
| Federal | [Portaria de Consolidação GM/MS nº 1/2017](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-CONSOLIDACAO-GMMS-1-2017-ORGANIZACAO-E-FUNCIONAMENTO-DO-SUS.md) | Título VII, Capítulo IV, arts. 358 a 390 | Institui o CNES; definições; obrigatoriedade; responsabilidades; atualização mínima mensal; fluxos de envio; desativação de cadastro irregular; tipo de estabelecimento por atividade; formas de contratação; comitê consultivo; dados públicos | Vigente. Texto transcrito com alterações até outubro de 2018; alterações posteriores a conferir |
| Federal | [Portaria de Consolidação SAES/MS nº 1/2022](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-CONSOLIDACAO-SAESMS-1-2022-ATENCAO-ESPECIALIZADA.md) | Título III, Capítulo III, arts. 217 a 290 | Registro de habilitações; certidão negativa e desativação por falta de atualização; CNPJ e natureza jurídica; contratos de gestão e incentivos; geração do arquivo para os sistemas de produção | Vigente. Texto transcrito como publicado em março de 2022; alterações posteriores a conferir |
| Distrital | [Decreto nº 39.546/2018, Regimento Interno da SES-DF](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/02-legislacao-distrital/DECRETO-DISTRITAL-39546-2018-REGIMENTO-INTERNO-SESDF.md) | arts. 173, 175 e 176; 267, 270 e 290; equivalentes nas unidades de referência distrital | Divide as tarefas do cadastro entre a área central (supervisão, cadastramento, habilitação) e as regiões e unidades (coleta e inserção de leitos, equipamentos, infraestrutura e profissionais) | Vigente. Texto compilado do SINJ-DF impresso em 13/10/2026; reestruturações posteriores a conferir |

> [!WARNING]
> **Cite a consolidação.** As Portarias 1.646/2015, 2.022/2017 e 1.321/2016 foram revogadas "por consolidação" em 2017, e a Portaria SAS 118/2014, em 2022, sem mudança de conteúdo: o texto vigente está na Portaria de Consolidação GM/MS nº 1/2017 e na Portaria de Consolidação SAES/MS nº 1/2022. Neste caderno, os artigos citados são os das consolidações. Em manuais e normas antigos, a atualização mensal aparece como art. 13 da 1.646/2015; na consolidação é o **art. 370**.

**Normas de origem**

| Ano | Norma | Problema que enfrentou (segundo a própria norma) | O que criou | Onde está hoje |
|---|---|---|---|---|
| 2000 | [Portaria SAS/MS nº 511/2000](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-SASMS-511-2000-FICHA-CADASTRAL-CNES.md) | O recadastramento de 1997 e 1998 tinha fragilidades e inconsistências apontadas pela Secretaria de Controle Interno, pelo TCU e por áreas do Ministério; faltava ligar a capacidade existente à produção apresentada, pagar corretamente a rede e identificar os prestadores da saúde suplementar para o ressarcimento ao SUS | Ficha cadastral dos estabelecimentos, manual de preenchimento e banco de dados nacional. Já previa bloqueio do pagamento para quem não mantivesse o cadastro (art. 10) | Não consolidada nem listada como revogada nas consolidações de 2017 e 2022; vigência não conferida |
| 2014 | [Portaria SAS/MS nº 118/2014, republicada](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-SASMS-118-2014-DESATIVACAO-CNES-REPUBLICADA.md) | O envio mensal já era obrigação dos gestores desde 2007; faltava garantir informação qualificada e uma visão correta e atualizada dos estabelecimentos das redes de atenção | Desativação automática de quem passa seis meses sem atualização, com os impedimentos que isso traz | PRC SAES/MS 1/2022, arts. 227 a 230 |
| 2015 | [Portaria GM/MS nº 1.646/2015](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-GMMS-1646-2015-INSTITUI-O-CNES.md) | Atualizar o modelo de 1997 à luz da Lei de Acesso à Informação, do Decreto 7.508/2011 e dos padrões de interoperabilidade de 2011, citados nos considerandos | O CNES na forma atual: documento público, fonte oficial, responsabilidades de cada esfera, atualização mensal, fluxos de envio, dados abertos. Revogou a Portaria GM/MS 1.890/1997 | PRC GM/MS 1/2017, arts. 358 a 373 e 384 a 390 |
| 2016 | Portaria GM/MS nº 1.321/2016 | Cópia em fonte primária não localizada; o texto consolidado diz só que a nova terminologia substitui a antiga tabela de vínculos profissionais | Terminologia de formas de contratação em três níveis: com o estabelecimento, com o empregador e detalhamento | PRC GM/MS 1/2017, arts. 379 a 383 |
| 2017 | [Portaria GM/MS nº 2.022/2017](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-GMMS-2022-2017-TIPO-DE-ESTABELECIMENTO-CNES.md) | A base, com mais de 17 anos, precisava de aprimoramento; o tipo era escolhido numa tabela por quem cadastrava. A revisão veio de grupo de trabalho do Ministério e foi pactuada na Comissão Intergestores Tripartite em julho de 2017 | Conceito de estabelecimento em quatro elementos; tipo deduzido das atividades declaradas | PRC GM/MS 1/2017, arts. 374 a 378 e Anexo XV |

<!-- componente: linha-do-tempo -->
| Quando | Marco | Fonte |
|---|---|---|
| dez/2000 | Ficha cadastral dos estabelecimentos e banco de dados nacional | Portaria SAS/MS 511/2000 |
| fev–jun/2014 | Desativação automática após seis meses sem atualização | Portaria SAS/MS 118/2014, republicada |
| out/2015 | CNES na forma atual: obrigatoriedade, responsabilidades, atualização mensal | Portaria GM/MS 1.646/2015 |
| jul/2016 | Formas de contratação dos profissionais | Portaria GM/MS 1.321/2016 |
| ago/2017 | Tipo do estabelecimento passa a sair das atividades | Portaria GM/MS 2.022/2017 |
| set/2017 | As três portarias entram na Portaria de Consolidação nº 1/2017 | PRC GM/MS 1/2017, arts. 358 a 390 e 560 |
| dez/2018 | O Regimento Interno da SES-DF distribui as tarefas do cadastro | Decreto nº 39.546/2018 |
| mar/2022 | A regra de desativação entra na Portaria de Consolidação SAES/MS nº 1/2022 | PRC SAES/MS 1/2022, arts. 227 a 230 e 432 |

## 3. Como funciona

**Quem faz o quê.** A norma federal define três responsáveis: o estabelecimento, que cadastra e mantém os dados (art. 364); o profissional, corresponsável pelos próprios dados (art. 365); e os gestores do SUS, que apoiam, validam e podem corrigir (arts. 366 a 369). Na SES-DF, o Regimento Interno distribui essas tarefas assim:

| Quem | O que faz no CNES | Base |
|---|---|---|
| Direção do estabelecimento (responsável técnico ou administrativo) | Responde pelo cadastro e pela atualização da unidade, junto com o gestor | PRC GM/MS 1/2017, art. 364; PRC SAES/MS 1/2022, art. 229 |
| Profissional de saúde | Responde pela veracidade dos próprios dados e avisa quem cadastra de qualquer mudança | PRC GM/MS 1/2017, art. 365 |
| Núcleo de Captação e Análise de Informações do SUS (NCAIS) da região de saúde | Coleta, analisa e insere os dados de leitos, equipamentos e infraestrutura das unidades hospitalares; confere inconsistências; compatibiliza o cadastro com os sistemas de produção; envia à Diretoria de Controle de Serviços de Saúde | Regimento, art. 290, IV a VI |
| Núcleo de Gestão de Pessoas da região, sob a Gerência de Pessoas | Insere e mantém atualizados os dados dos profissionais; a Gerência monitora e avalia | Regimento, arts. 270, XXII, e 267, XV |
| Unidades de referência distrital e Complexo Regulador | Têm núcleos próprios com as mesmas tarefas | Regimento, arts. 364 e 378 (HMIB), 409 e 414 (Hospital de Apoio), 441 e 445 (Hospital São Vicente de Paulo), 470 e 476 (Complexo Regulador) |
| Gerência de Cadastramento de Estabelecimentos e de Usuários do SUS (GECAD) | Gerencia o cadastramento no DF; propõe normas e padrões; monitora os dados e as inconsistências; fornece a base cadastral aos demais sistemas | Regimento, art. 176 |
| Gerência de Controle de Credenciamento e Habilitação (GCCH) | Identifica serviços com potencial de habilitação, conduz os processos com o Ministério da Saúde e monitora as habilitações | Regimento, art. 175 |
| Diretoria de Controle de Serviços de Saúde (DICS) | Supervisiona cadastramento, habilitação e processamento da produção | Regimento, art. 173 |
| SES-DF como gestora do SUS no DF | Valida e envia os dados à base nacional e passa a responder junto por eles; pode fiscalizar, auditar, validar, alterar e desativar cadastro irregular | PRC GM/MS 1/2017, arts. 368, 372 e 373 |
| Ministério da Saúde | Define terminologias e mantém os sistemas; registra no CNES as habilitações publicadas no Diário Oficial da União; corrige inconformidades apontadas por órgãos de controle ou pelo Judiciário quando ninguém mais corrigiu | PRC GM/MS 1/2017, art. 367, IV a VI; PRC SAES/MS 1/2022, arts. 220 e 221 |

> [!WARNING]
> **Confira a unidade antes de acionar.** A tabela segue o Regimento de 2018 no texto compilado de 13/10/2026. Os hospitais geridos pelo IGESDF e por organização social seguem regimento e contrato próprios, e reestruturações recentes podem ter mudado nomes e subordinação na SES-DF.

**O profissional não preenche o sistema.** Ser corresponsável (art. 365) quer dizer que o profissional responde pela verdade dos próprios dados; quem os lança é o estabelecimento, na SES-DF o Núcleo de Gestão de Pessoas. A tarefa do profissional é avisar; a da unidade é garantir que o aviso chegue ao núcleo antes do fechamento da competência. O ponto frágil são as mudanças que não passam pela área de pessoas: troca de setor dentro do hospital, cessão informal, residente que muda de rodízio, profissional que deixa de atender num serviço. Quando o cadastro não acompanha, a produção desse profissional pode ser rejeitada, porque os sistemas de produção conferem se quem executou está vinculado ao estabelecimento com a ocupação exigida pelo procedimento, e a força de trabalho da unidade aparece distorcida.

**Dois caminhos até a base nacional.** Estabelecimentos fora do SUS, os ligados ao Ministério da Saúde ou da Educação, os da saúde indígena e os da Rede Sarah enviam os dados direto à base nacional (art. 371). Os demais estabelecimentos do SUS enviam ao gestor do território, que valida e repassa, e passa a responder junto pelas informações (art. 372). No DF, a SES-DF é o gestor de todo o território: os hospitais da administração direta, os do IGESDF, os geridos por organização social e os privados contratados chegam à base nacional por ela. O Hospital Universitário de Brasília, gerido pela EBSERH, empresa vinculada ao Ministério da Educação, e a Rede Sarah enviam direto.

**O que o cadastro guarda.** A divisão abaixo é a dos arquivos públicos que o DATASUS divulga todo mês, que são os que esta ferramenta usa. O sistema de cadastro tem outros módulos (equipes, telessaúde, mantenedora, contratos e metas).

| Bloco | O que registra | Uso na carteira |
|---|---|---|
| Estabelecimento | Tipo, natureza jurídica, gestão, vínculo com o SUS, endereço, turno e fluxo de clientela | Identificar a unidade e seu perfil |
| Instalações físicas | Salas de cirurgia do centro cirúrgico e do centro obstétrico, leitos de recuperação pós-anestésica, consultórios | Contexto de capacidade cirúrgica e ambulatorial |
| Leitos | Por tipo e especialidade: existentes, SUS e não SUS | Capacidade de internação |
| Equipamentos | Quantidade existente, em uso e disponível ao SUS | Apoio diagnóstico e terapêutico |
| Serviços especializados | Serviço e classificação, próprio ou terceirizado | Principal ponte com a SIGTAP |
| Habilitações | Habilitação, portaria, vigência e, para leitos, quantidade habilitada | Condição para registrar procedimentos que a exigem |
| Profissionais | Ocupação (CBO), carga horária, forma de contratação, atendimento SUS | Força de trabalho |

<!-- componente: listas-por-bloco -->
*Listas geradas pela ferramenta: para cada bloco, os itens que aparecem nos hospitais do DF, em ordem alfabética, com quantos hospitais da rede SES-DF e quantos outros hospitais do DF têm cada item; um clique abre todos esses hospitais, com o detalhe do bloco e o link para a ficha.*

**Tipo do estabelecimento.** Desde 2017, o tipo (hospital geral, hospital especializado e outros) não é mais escolhido: o sistema o deduz das atividades que o estabelecimento informa (arts. 374 a 376).

<details>
<summary>O que conta como estabelecimento de saúde, e como o tipo é deduzido</summary>

A definição de estabelecimento tem quatro elementos, explicados no anexo da Portaria 2.022/2017 (hoje Anexo XV da PRC GM/MS 1/2017):

1. **Espaço físico delimitado e permanente.** Unidade móvel, como carreta ou embarcação, pode ser estabelecimento; barraca, tenda ou mutirão em local aberto, não.
2. **Onde as ações são realizadas.** O espaço precisa estar funcionando: unidade desativada ou em obra não é estabelecimento de saúde enquanto estiver assim.
3. **Ações e serviços de saúde humana.** Inclui vigilância, regulação e gestão, não só assistência. Exclui saúde animal, estética e salão de beleza, mesmo que fiscalizados pela vigilância sanitária.
4. **Responsabilidade técnica.** Sempre há uma pessoa física legalmente responsável.

O tipo sai de uma lista de atividades. Quem cadastra marca a atividade principal, a que predomina ou diferencia o atendimento, e as secundárias; o sistema classifica sozinho. Algumas atividades impedem certos tipos, as chamadas atividades não permitidas. Para o gestor, a consequência é que o tipo diz o que foi declarado como atividade, não o perfil assistencial: um hospital de perfil materno-infantil pode aparecer como hospital geral.

</details>

**Como consultar.**

| Caminho | O que mostra | Cuidado |
|---|---|---|
| [Portal do CNES](https://cnes.datasus.gov.br) | Ficha de cada estabelecimento e de cada profissional; informes por competência | Algumas funções ainda estão no [portal anterior](https://cnes2.datasus.gov.br) |
| [TabNet do CNES](https://tabnet.datasus.gov.br/cgi/deftohtm.exe?cnes/cnv/estabdf.def) | Contagens por competência (estabelecimentos, leitos, equipamentos, profissionais, serviços), com série mensal | Conta só estabelecimentos ativos |
| Arquivos de disseminação do DATASUS | Dados completos, mês a mês, por unidade da federação | Exigem tratamento; parte dos códigos não tem descrição nas tabelas auxiliares |

## 4. Situação atual e atualização

A atualização é **obrigatória e no mínimo mensal**, ou logo depois de qualquer mudança, sempre por meio eletrônico (art. 370). A base nacional é fechada por **competência mensal**, e o DATASUS divulga os dados de cada competência. Na prática, o que move o cadastro é a rotina da unidade:

| Acontecimento | Quem registra na SES-DF | Se não for registrado |
|---|---|---|
| Admissão, remoção, mudança de carga horária, afastamento ou desligamento de profissional | Núcleo de Gestão de Pessoas | Produção do profissional rejeitada ou atribuída à unidade errada; força de trabalho distorcida |
| Abertura, fechamento ou mudança de especialidade de leitos | NCAIS, com a direção | Capacidade cadastrada diferente da real; em UTI e cuidados intermediários, o leito SUS fica limitado ao habilitado (seção 7) |
| Chegada, parada prolongada ou baixa de equipamento | NCAIS | Equipamento parado continua contado como existente e em uso |
| Início ou fim de serviço especializado, ou troca de quem o sustenta | NCAIS, com a direção e o Núcleo de Gestão de Pessoas | Procedimentos que exigem o serviço e a classificação são rejeitados |
| Habilitação nova, renovada ou cancelada | Ministério da Saúde, nas publicadas no DOU; a SES-DF, nas descentralizadas; a GCCH acompanha | Sem habilitação vigente na competência, procedimentos que a exigem são rejeitados |
| Mês sem mudança | Gestor envia com certidão negativa | Seis meses sem envio válido desativam o estabelecimento |

**Mês sem mudança também exige envio.** Manter o cadastro inclui reafirmar que nada mudou (art. 360, III). A cada envio, o sistema gera a lista dos estabelecimentos sem alteração; o gestor confere e atesta essa ausência, a chamada certidão negativa, e envia junto com os que mudaram (PRC SAES/MS 1/2022, art. 226).

**Seis meses parado desativa.** Sem atualização por mais de seis meses, o estabelecimento é marcado como **desativado** e não pode apresentar produção ambulatorial e hospitalar nem produção de equipes, pedir novas habilitações ou entrar em novos programas. Conta como sem atualização o cadastro que não foi enviado à base nacional nesse período ou que foi enviado com rejeição. Volta a ficar ativo quando envia nova atualização sem rejeição ([PRC SAES/MS 1/2022](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-CONSOLIDACAO-SAESMS-1-2022-ATENCAO-ESPECIALIZADA.md), arts. 227 e 228, que vêm da Portaria SAS 118/2014).

**Habilitação: quem registra.** Habilitar é o gestor autorizar um estabelecimento já credenciado a fazer procedimentos que dependem de norma específica (art. 217). A regra geral é federal: a área técnica do Ministério publica a portaria no Diário Oficial da União até o dia 5 para valer no mês, e o Ministério registra a habilitação no CNES (arts. 220 e 221). Algumas habilitações são registradas pelo próprio gestor estadual ou distrital, depois de deliberação na instância bipartite: cuidados prolongados, internação domiciliar, laqueadura e vasectomia, cuidados intermediários neonatais e videocirurgia (art. 222 e Anexo XXXIX). Os códigos desse anexo são de 2006; as habilitações neonatais em uso hoje no DF têm códigos mais novos e portaria federal, por isso convém conferir antes de supor que o registro é local.

Na SES-DF, a área técnica do cadastro é a **GECAD**, contato cnes.gecad@saude.df.gov.br. Depois do envio, a atualização leva cerca de 15 dias para aparecer, segundo orientação da própria SES-DF aos prestadores.

## 5. Por que importa para o gestor hospitalar

1. **Faturamento.** Procedimento só é aceito se o hospital tiver no cadastro o serviço, a habilitação, o leito e o profissional que a SIGTAP exige, vigentes na competência. Cadastro atrasado faz a produção ser rejeitada; seis meses sem atualização desativam o estabelecimento.
2. **Habilitação.** Os itens da [RENASES](../renases/caderno.md) com critério de habilitação dependem de habilitação vigente registrada no CNES.
3. **Capacidade instalada.** Leitos, salas, equipamentos e carga horária são insumos para estimar a capacidade instalada da unidade.
4. **Conferência da carteira.** O cadastro ajuda a achar incoerências nos dois sentidos: procedimento declarado sem serviço ou habilitação cadastrada, e serviço cadastrado sem nenhum procedimento declarado.
5. **Responsabilidade.** A direção responde pelo cadastro da unidade. A atualização depende de quem conhece a operação: direção, núcleos de faturamento e responsáveis técnicos.

**Como a rejeição acontece.** *Exemplo construído para ilustrar a regra.* Em março, um cirurgião é lotado num hospital regional e começa a operar; a lotação só chega ao Núcleo de Gestão de Pessoas em maio. As internações de março e abril em que ele aparece como executante são rejeitadas, porque o sistema não o encontra vinculado ao hospital naquelas competências. O problema só aparece quando o faturamento recebe o relatório de rejeição, semanas depois. Corrigido o cadastro, a produção ainda precisa ser reapresentada dentro do prazo do sistema de produção. O mesmo vale para a habilitação que vence sem renovação: a partir da competência seguinte ao fim da vigência, os procedimentos que a exigem deixam de ser aceitos.

**Registro errado tem efeito fora da unidade.** Como o CNES é a fonte oficial de todos os sistemas e políticas de saúde (art. 362), um erro não fica no hospital: passa para a produção, o financiamento, o planejamento e os dados públicos. O gestor que validou e enviou responde junto com o estabelecimento (art. 372) e pode fiscalizar, auditar e alterar o cadastro (art. 368, IV). Quando órgãos de controle ou o Judiciário apontam inconformidade que ninguém corrigiu, o Ministério corrige (art. 367, V): auditorias usam o cadastro como evidência.

> [!IMPORTANT]
> **Interpretação do projeto, não norma.** Três registros contam a mesma unidade de três jeitos: o CNES diz o que ela **tem** e está apta a registrar; a carteira diz o que ela **declara fazer**; a produção mostra o que ela **fez**. A carteira ganha força quando os três se confirmam. Base: PRC 1/2017, arts. 359 e 364; PRC SAES/MS 1/2022, art. 228; caderno de SIGTAP.

## 6. Não confundir

| Instrumento | Pergunta que responde | Erro comum |
|---|---|---|
| CNES | Que estrutura, serviços, habilitações e profissionais a unidade declarou? | Tomar o cadastro como capacidade real do dia a dia |
| SIGTAP | Que procedimento é, como se registra e o que exige? | Achar que estar na tabela significa estar apto a fazer |
| Habilitação | O gestor autorizou a unidade a fazer determinado tipo de procedimento? | Achar que a portaria basta sem o registro vigente no CNES |
| Carteira de serviços | O que a unidade efetivamente oferta? | Confundir com o cadastro |
| Leito cadastrado | Quantos leitos existem e quantos estão disponíveis ao SUS? | Confundir com leito operacional (o que está em uso, com equipe) |
| Leito não SUS | Quantos leitos existentes não entram na conta do SUS? | Achar que, em hospital público, é leito privado ou fechado |
| TabNet | Quantos estabelecimentos ativos há, por competência? | Usar como lista completa: ele omite os desativados |

> [!CAUTION]
> **O cadastro não representa necessariamente a realidade.** O CNES mostra o que foi declarado no último envio. Leito, sala ou equipamento cadastrado pode estar fechado, parado ou sem equipe. Para saber o que funciona, é preciso outra fonte, como o censo da unidade ou a contagem local.

## 7. Cuidados e limites

- **Foto mensal com defasagem.** Mudanças da operação demoram a aparecer: o envio é mensal, e a atualização leva cerca de 15 dias para aparecer depois do envio.
- **Equipamento existente não é equipamento em uso.** O cadastro separa quantidade existente, em uso e disponível ao SUS.
- **Ausência pode ser lacuna de registro.** Um equipamento comum em centro cirúrgico que não aparece em nenhum hospital do DF sugere falta de registro, não falta do equipamento.
- **Tipo e natureza jurídica nem sempre refletem o modelo de gestão.** O tipo sai das atividades declaradas, e a natureza jurídica vem do CNPJ registrado. Por isso um hospital materno-infantil pode aparecer como hospital geral, e um hospital gerido por organização social pode aparecer como órgão público do DF.
- **Região de saúde em código.** O campo de região traz códigos informados pelo gestor, sem descrição oficial no arquivo; ligar às sete Regiões de Saúde do DF exige tabela da SES-DF.

<details>
<summary>Por que hospital gerido por organização social aparece como órgão público</summary>

A natureza jurídica do estabelecimento vem só do CNPJ registrado na Receita Federal (PRC SAES/MS 1/2022, art. 236). A entidade privada que administra estabelecimento de pessoa jurídica de direito público não pode usar o próprio CNPJ no cadastro: ela aparece só como gerente ou administrador terceiro (art. 235, III e § 1º). O hospital continua com o CNPJ do ente público e, portanto, com a natureza jurídica dele. É o caso do Hospital da Criança de Brasília, gerido por organização social: na competência 08/2026, aparece com natureza de órgão público do DF. Para saber o modelo de gestão, é preciso olhar o cadastro do administrador terceiro ou o contrato de gestão, não a natureza jurídica.

</details>

**Leito "não SUS" em hospital público.** Hospital público atende pelo SUS; então por que tem leito não SUS? Nos dados do CNES, a coluna SUS dos leitos complementares (UTI e cuidados intermediários) acompanha a habilitação: o hospital pode ter mais leitos instalados do que o número habilitado pelo Ministério da Saúde, e o que passa do habilitado aparece como não SUS. Os pacientes desses leitos são do SUS; o que falta é o reconhecimento federal do leito. Isso não é, em si, erro de cadastro: registrar como SUS um leito sem habilitação seria declarar o que não existe. Há três consequências para o gestor:

- **Financiamento.** O custeio do leito excedente fica com o DF, sem a contrapartida federal que vem com a habilitação.
- **Indicadores.** Quem conta só leito SUS subestima a capacidade pública de terapia intensiva e cuidados intermediários.
- **Oportunidade.** Leito excedente que funciona com equipe e estrutura completas é candidato a pedido de habilitação ou de ampliação, tarefa que o Regimento dá à GCCH (art. 175, II). Já o excedente que não funciona é capacidade inflada e deve sair do cadastro.

> [!IMPORTANT]
> **Interpretação do projeto, não norma.** Nos dados de 08/2026, em todos os estabelecimentos do DF com leitos de UTI ou de cuidados intermediários, públicos ou privados, o número de leitos SUS de cada tipo é exatamente o número habilitado; leito de isolamento, que não tem habilitação, conta como SUS. Nos hospitais da administração direta da SES-DF e no Hospital da Criança, todo leito não SUS é leito de UTI ou de cuidados intermediários acima da habilitação. Nos hospitais das Forças Armadas, ao contrário, há leitos não SUS clínicos e cirúrgicos, de clientela própria. A regra de sistema que produz esse padrão não foi localizada em norma; a leitura vem dos dados e deve ser confirmada com a GECAD ou na Wiki do CNES. Base: arquivos de disseminação do CNES, competência 08/2026, leitos e habilitações (ver Nesta ferramenta).

> [!WARNING]
> **Código CNES é texto.** Tem sete dígitos, e muitos começam com zero, como 0010456 (HBDF). Planilha que converte o código em número apaga o zero e quebra qualquer cruzamento entre bases.

## 8. Exemplo integrado: cirurgia bariátrica

1. **RENASES.** A cirurgia bariátrica está na lista de 2012 com quatro critérios de acesso: encaminhamento, regulação, habilitação e protocolo ([caderno de RENASES](../renases/caderno.md)).
2. **Habilitação.** O Ministério da Saúde habilita o hospital como centro de referência; a habilitação, com a portaria e a vigência, é registrada no CNES.
3. **CNES.** Além da habilitação, o cadastro precisa mostrar o serviço, os leitos e os profissionais compatíveis, e estar em dia.
4. **SIGTAP.** Os procedimentos da cirurgia exigem a habilitação; sem ela no cadastro, a produção é rejeitada.
5. **Se o cadastro parar.** Seis meses sem atualização e o hospital é desativado: deixa de apresentar produção, inclusive a desta cirurgia (PRC SAES/MS 1/2022, art. 228).
6. **Carteira.** O hospital declara se faz; a declaração pode ser conferida contra a habilitação no CNES e a produção registrada.

## 9. Nesta ferramenta

<!-- Bloco gerado pela ferramenta. Previsto: data e competência da extração do CNES usada; indicadores do DF (hospitais com leitos, leitos existentes, leitos SUS, salas cirúrgicas em centro cirúrgico); panorama da rede hospitalar por grupo (administração direta da SES-DF, IGESDF, Rede Sarah, federal universitário, Forças Armadas, privados e filantrópicos com leitos SUS) e o critério usado; leitos não SUS dos hospitais públicos, comparados com os leitos habilitados; links para as páginas Hospitais e Capacidade e para a ficha de cada hospital. -->

*Bloco gerado pela ferramenta: competência da extração do CNES usada, indicadores de capacidade do DF, panorama da rede hospitalar por grupo, com o critério de classificação, e leitos não SUS dos hospitais públicos comparados com os habilitados, com links para as páginas Hospitais e Capacidade.*

> [!TIP]
> **Recortes diferentes.** Os números da ferramenta vêm do cadastro. Quando divergirem da estrutura declarada pelos hospitais ou de contagens locais, as duas informações valem como recortes com fonte e data próprias, não como erro de uma delas.

## 10. Para aprofundar

- [Wiki do CNES (DATASUS)](https://wiki.saude.gov.br/cnes/index.php/Portal_CNES) — regras de negócio, orientações técnicas e normas.
- [Manual de atualização do CNES da EBSERH, 2ª edição (2021)](https://www.gov.br/hubrasil/pt-br/acesso-a-informacao/boletim-de-servico/sede/2021/anexos/manual-cnes-2a-edicao-v3.pdf) — orientação operacional de uma rede hospitalar federal; cita a numeração antiga dos artigos.
- Cadernos relacionados: [SIGTAP](../sigtap/caderno.md), [RENASES](../renases/caderno.md), [Rede hospitalar do DF](../rede-hospitalar/caderno.md), [Carteira de serviços](../carteira-servicos/caderno.md).

## Conceitos neste caderno

[CNES](../../vocabulario-controlado.md) · [SIGTAP](../../vocabulario-controlado.md) · [habilitação](../../vocabulario-controlado.md) · [RENASES](../../vocabulario-controlado.md) · [carteira de serviços](../../vocabulario-controlado.md)

## Fontes

| Fonte | Tipo | Consultada em |
|---|---|---|
| Portaria de Consolidação GM/MS nº 1/2017, arts. 358 a 390 e 560 — [transcrição](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-CONSOLIDACAO-GMMS-1-2017-ORGANIZACAO-E-FUNCIONAMENTO-DO-SUS.md) | Norma | 26/10/2026 |
| Portaria de Consolidação SAES/MS nº 1/2022, Título III, Capítulo III, Anexo XXXIX e art. 432 — [transcrição](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-CONSOLIDACAO-SAESMS-1-2022-ATENCAO-ESPECIALIZADA.md) da página do DOU de 31/03/2022 (cópia guardada pela SES-MG) | Norma | 26/10/2026 |
| Decreto nº 39.546/2018, Regimento Interno da SES-DF — [transcrição](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/02-legislacao-distrital/DECRETO-DISTRITAL-39546-2018-REGIMENTO-INTERNO-SESDF.md) do texto compilado do SINJ-DF | Norma | 26/10/2026 |
| Portaria GM/MS nº 1.646/2015 — [transcrição](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-GMMS-1646-2015-INSTITUI-O-CNES.md) da [cópia no gov.br da ANS](https://www.gov.br/ans/pt-br/centrais-de-conteudo/portaria-n-1646-de-02-de-outubro-de-2015-cnes-pdf) | Norma | 26/10/2026 |
| Portaria GM/MS nº 2.022/2017 — [transcrição](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-GMMS-2022-2017-TIPO-DE-ESTABELECIMENTO-CNES.md) da [cópia da Prefeitura de Jacareí](https://www.jacarei.sp.gov.br/wp-content/uploads/2021/02/Portaria-2022-de-7-de-agosto-de-2017.pdf) | Norma | 26/10/2026 |
| Portaria SAS/MS nº 118/2014, redação republicada (DOU de 16/06/2014) — [transcrição](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-SASMS-118-2014-DESATIVACAO-CNES-REPUBLICADA.md) | Norma | 25/10/2026 |
| Portaria SAS/MS nº 511/2000 — [transcrição](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-SASMS-511-2000-FICHA-CADASTRAL-CNES.md) da [cópia da SES-AM](https://www.saude.am.gov.br/wp-content/uploads/2025/01/PT-CNES-PORTARIA-No-511-DE29-DE-DEZEMBRO-DE-2000.pdf) | Norma | 26/10/2026 |
| Portal do CNES — [cnes.datasus.gov.br](https://cnes.datasus.gov.br) | Dado oficial | 22/10/2026 |
| TabNet do CNES, estabelecimentos do DF — [DATASUS](https://tabnet.datasus.gov.br/cgi/deftohtm.exe?cnes/cnv/estabdf.def) | Dado oficial | 22/10/2026 |
| Arquivos de disseminação do CNES, competência 08/2026 (DF): estabelecimentos, leitos e habilitações | Dado oficial | 26/10/2026 |
| SES-DF, guia de orientação aos contratados, credenciamento de cirurgias oftalmológicas (edital nº 03/2025) — [InfoSaúde-DF](https://info.saude.df.gov.br/wp-content/uploads/2026/01/GUIA-DE-ORIENTACAO-AOS-CONTRATADOS-CIRURGIAS-OFTALMOLOGICAS-Edital-de-Credenciamento-no-032025-SESDF.pdf) | Documento institucional | 22/10/2026 |
| EBSERH, Manual do CNES, 2ª edição (2021) — [gov.br](https://www.gov.br/hubrasil/pt-br/acesso-a-informacao/boletim-de-servico/sede/2021/anexos/manual-cnes-2a-edicao-v3.pdf) | Documento institucional | 22/10/2026 |

## Histórico de versões

| Versão | Data | O que mudou |
|---|---|---|
| v1.0 | 2026-10-26 | Aprovada pelo Victor, com o texto da v0.3 e o ajuste de redação do destaque da seção 6 ("O cadastro não representa necessariamente a realidade") |
| v0.3 | 2026-10-26 | Base normativa em dois blocos: normas vigentes por esfera, com o Regimento Interno da SES-DF, e normas de origem em ordem cronológica, com o problema que cada uma enfrentou e onde o texto está hoje; quem faz o quê no cadastro na SES-DF; papel do profissional; caminhos de envio no DF; acontecimentos que exigem atualização; certidão negativa; quem registra cada habilitação; exemplo de rejeição; efeito do registro errado; leito não SUS em hospital público, com segunda Leitura do projeto; natureza jurídica de hospital gerido por organização social; dois detalhes recolhíveis em teste; linha do tempo movida para a seção 2. Aguarda aprovação |
| v0.2 | 2026-10-25 | Vigência da Portaria SAS 118/2014 conferida: revogada por consolidação na Portaria de Consolidação SAES/MS nº 1/2022, que entra na base normativa (arts. 217 a 290 sobre o CNES); regra de desativação citada pelos arts. 227 e 228; linha do tempo até 2022. Aguarda aprovação |
| v0.1 | 2026-10-24 | Primeiro rascunho no modelo de caderno v1.1, a partir do capítulo publicado na ferramenta (v0.3.10), da linha de base e da verificação em fonte primária. Aguarda aprovação |
