---
id: cnes
nome_curto: CNES
titulo: "CNES: o cadastro oficial dos estabelecimentos de saúde"
resumo: "O que o Cadastro Nacional de Estabelecimentos de Saúde registra, quem responde por ele, com que frequência deve ser atualizado e como ler os dados sem confundir cadastro com capacidade real."
versao: v0.1
revisao: 2026-10-24
situacao: com pendências
---

# CNES: o cadastro oficial dos estabelecimentos de saúde

Conhecimento · CNES · **v0.1 (rascunho)** · 2026-10-24 · base normativa conferida em fonte primária em 22 e 24/10/2026, com [pendências](README.md#pendências)
*Material de estudo. Não substitui a publicação oficial das normas citadas.*

## 1. O que é

O **CNES** (Cadastro Nacional de Estabelecimentos de Saúde) é o registro oficial de todos os estabelecimentos de saúde do país, públicos e privados, integrantes ou não do SUS. É ao mesmo tempo documento público e sistema de informação: registra a estrutura de cada unidade (instalações, leitos, equipamentos), os serviços que oferece, as habilitações que recebeu e os profissionais que nela trabalham ([PRC GM/MS 1/2017](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-CONSOLIDACAO-GMMS-1-2017-ORGANIZACAO-E-FUNCIONAMENTO-DO-SUS.md), arts. 358 e 359).

O cadastro é **obrigatório** para qualquer estabelecimento funcionar e deve vir antes das licenças sanitárias (art. 361). É a **fonte oficial** sobre estabelecimentos de saúde: todo sistema que use esses dados deve adotá-lo (art. 362).

O CNES **não** é instrumento de controle nem de indução de política. A própria norma diz que ele existe só para representar, do modo mais fiel possível, a realidade de cada lugar (art. 359, parágrafo único). Também não mede o que o hospital consegue fazer num dia comum: registra o que existe e foi declarado.

> [!NOTE]
> **Cadastro declarado, com efeito real.** O CNES é preenchido pelo próprio estabelecimento, mas o que está nele decide o que o hospital pode registrar e receber: os sistemas de produção do SUS conferem cada procedimento contra o cadastro (ver o [caderno de SIGTAP](../sigtap/caderno.md)).

## 2. Origem e base normativa

| Norma | Dispositivo | O que estabelece | Situação (24/10/2026) |
|---|---|---|---|
| [Portaria de Consolidação GM/MS nº 1/2017](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-CONSOLIDACAO-GMMS-1-2017-ORGANIZACAO-E-FUNCIONAMENTO-DO-SUS.md) | Título VII, Capítulo IV, arts. 358 a 390 | Institui o CNES; definições; obrigatoriedade; responsabilidades; atualização mínima mensal; fluxos de envio; desativação de cadastro irregular; tipo de estabelecimento por atividade; formas de contratação; comitê consultivo; dados públicos | Vigente. Texto transcrito com alterações até outubro de 2018; alterações posteriores a conferir |
| [Portaria GM/MS nº 1.646/2015](https://www.gov.br/ans/pt-br/centrais-de-conteudo/portaria-n-1646-de-02-de-outubro-de-2015-cnes-pdf) | arts. 1º a 25 | Norma de origem do CNES na forma atual; revogou a Portaria GM/MS nº 1.890/1997 (art. 25) | Revogada por consolidação (PRC 1/2017, art. 560, XLII); o texto segue nos arts. 358 a 373 e 384 a 390 |
| [Portaria GM/MS nº 2.022/2017](https://www.jacarei.sp.gov.br/wp-content/uploads/2021/02/Portaria-2022-de-7-de-agosto-de-2017.pdf) | arts. 1º a 5º | O tipo de estabelecimento passa a sair das atividades que ele realiza | Revogada por consolidação (art. 560, XLIII); o texto segue nos arts. 374 a 378 |
| Portaria GM/MS nº 1.321/2016 | arts. 1º a 6º | Terminologia das formas de contratação dos profissionais, no lugar da antiga tabela de vínculos | Revogada por consolidação (art. 560, XLIV); o texto segue nos arts. 379 a 383 |
| [Portaria SAS/MS nº 118/2014, republicada](https://saude.campinas.sp.gov.br/saude/lista_legislacoes/legis_2014/U_PT-MS-SAS-118-REP_180214.pdf) | arts. 1º e 2º | Estabelecimento sem atualização há mais de seis meses é marcado como desativado e fica impedido de apresentar produção e pedir habilitação | Vigência atual a conferir |
| [Portaria SAS/MS nº 511/2000](https://www.saude.am.gov.br/wp-content/uploads/2025/01/PT-CNES-PORTARIA-No-511-DE29-DE-DEZEMBRO-DE-2000.pdf) | — | Ficha cadastral dos estabelecimentos e banco de dados nacional: origem do cadastro atual | Histórica; vigência não conferida |

> [!WARNING]
> **Cite a consolidação.** As Portarias 1.646/2015, 2.022/2017 e 1.321/2016 foram revogadas "por consolidação" em 2017, sem mudança de conteúdo: o texto vigente está na Portaria de Consolidação nº 1/2017. Neste caderno, os artigos citados são os da consolidação. Em manuais e normas antigos, a atualização mensal aparece como art. 13 da 1.646/2015; na consolidação é o **art. 370**.

## 3. Como funciona

**Quem cadastra.** Cadastrar e manter os dados é responsabilidade de cada estabelecimento, por seus responsáveis técnicos ou administrativos (art. 364). Os profissionais respondem pelos próprios dados e devem avisar o estabelecimento de qualquer mudança (art. 365). Os gestores do SUS apoiam, validam e podem corrigir os cadastros das unidades sob seu comando (arts. 368 e 369).

**Dois caminhos até a base nacional.** Estabelecimentos fora do SUS, os ligados ao Ministério da Saúde ou da Educação, os da saúde indígena e os da Rede Sarah enviam os dados direto à base nacional (art. 371). Os demais estabelecimentos do SUS enviam ao gestor do território, que valida e repassa, e passa a responder junto pelas informações (art. 372).

**O que o cadastro guarda.** A divisão abaixo é a dos arquivos públicos que o DATASUS divulga todo mês, que são os que esta ferramenta usa. O sistema de cadastro tem outros módulos (equipes, telessaúde, mantenedora, contratos e metas).

| Bloco | O que registra | Uso na carteira |
|---|---|---|
| Estabelecimento | Tipo, natureza jurídica, gestão, vínculo com o SUS, endereço, turno e fluxo de clientela | Identificar a unidade e seu perfil |
| Instalações físicas | Salas de cirurgia do centro cirúrgico e do centro obstétrico, leitos de recuperação pós-anestésica, consultórios | Contexto de capacidade cirúrgica e ambulatorial |
| Leitos | Por tipo e especialidade: existentes, SUS e não SUS | Capacidade de internação |
| Equipamentos | Quantidade existente, em uso e disponível ao SUS | Apoio diagnóstico e terapêutico |
| Serviços especializados | Serviço e classificação, próprio ou terceirizado | Principal ponte com a SIGTAP |
| Habilitações | Habilitação, portaria e vigência | Condição para registrar procedimentos que a exigem |
| Profissionais | Ocupação (CBO), carga horária, forma de contratação, atendimento SUS | Força de trabalho |

**Tipo do estabelecimento.** Desde 2017, o tipo (hospital geral, hospital especializado e outros) não é mais escolhido: o sistema o deduz das atividades que o estabelecimento informa (arts. 374 a 376).

**Como consultar.**

| Caminho | O que mostra | Cuidado |
|---|---|---|
| [Portal do CNES](https://cnes.datasus.gov.br) | Ficha de cada estabelecimento e de cada profissional; informes por competência | Algumas funções ainda estão no [portal anterior](https://cnes2.datasus.gov.br) |
| [TabNet do CNES](https://tabnet.datasus.gov.br/cgi/deftohtm.exe?cnes/cnv/estabdf.def) | Contagens por competência (estabelecimentos, leitos, equipamentos, profissionais, serviços), com série mensal | Conta só estabelecimentos ativos |
| Arquivos de disseminação do DATASUS | Dados completos, mês a mês, por unidade da federação | Exigem tratamento; parte dos códigos não tem descrição nas tabelas auxiliares |

## 4. Situação atual e atualização

A atualização é **obrigatória e no mínimo mensal**, ou logo depois de qualquer mudança, sempre por meio eletrônico (art. 370). Manter o cadastro inclui **reafirmar que nada mudou** (art. 360, III): mês sem mudança também exige envio. A base nacional é fechada por **competência mensal**, e o DATASUS divulga os dados de cada competência.

Sem atualização por mais de seis meses, o estabelecimento é marcado como **desativado** e não pode apresentar produção ambulatorial e hospitalar, pedir novas habilitações nem entrar em novos programas (Portaria SAS 118/2014, arts. 1º e 2º). Volta a ficar ativo quando envia nova atualização sem rejeição.

Na SES-DF, a área técnica do cadastro é a **Gerência de Cadastramento de Estabelecimento e Usuários do SUS (GECAD)**, contato cnes.gecad@saude.df.gov.br. Depois do envio, a atualização leva cerca de 15 dias para aparecer, segundo orientação da própria SES-DF aos prestadores.

<!-- componente: linha-do-tempo -->
| Quando | Marco | Fonte |
|---|---|---|
| dez/2000 | Ficha cadastral dos estabelecimentos e banco de dados nacional | Portaria SAS/MS 511/2000 |
| fev–jun/2014 | Desativação automática após seis meses sem atualização | Portaria SAS/MS 118/2014, republicada |
| out/2015 | CNES na forma atual: obrigatoriedade, responsabilidades, atualização mensal | Portaria GM/MS 1.646/2015 |
| jul/2016 | Formas de contratação dos profissionais | Portaria GM/MS 1.321/2016 |
| ago/2017 | Tipo do estabelecimento passa a sair das atividades | Portaria GM/MS 2.022/2017 |
| set/2017 | As três portarias entram na Portaria de Consolidação nº 1/2017 | PRC GM/MS 1/2017, arts. 358 a 390 e 560 |

## 5. Por que importa para o gestor hospitalar

1. **Faturamento.** Procedimento só é aceito se o hospital tiver no cadastro o serviço, a habilitação, o leito e o profissional que a SIGTAP exige. Cadastro atrasado faz a produção ser rejeitada; seis meses sem atualização desativam o estabelecimento.
2. **Habilitação.** Os itens da [RENASES](../renases/caderno.md) com critério de habilitação dependem de habilitação vigente registrada no CNES.
3. **Capacidade instalada.** Leitos, salas, equipamentos e carga horária são insumos para estimar a capacidade instalada da unidade.
4. **Conferência da carteira.** O cadastro ajuda a achar incoerências nos dois sentidos: procedimento declarado sem serviço ou habilitação cadastrada, e serviço cadastrado sem nenhum procedimento declarado.
5. **Responsabilidade.** A direção responde pelo cadastro da unidade. A atualização depende de quem conhece a operação: direção, núcleos de faturamento e responsáveis técnicos.

> [!IMPORTANT]
> **Interpretação do projeto, não norma.** Três registros contam a mesma unidade de três jeitos: o CNES diz o que ela **tem** e está apta a registrar; a carteira diz o que ela **declara fazer**; a produção mostra o que ela **fez**. A carteira ganha força quando os três se confirmam. Base: PRC 1/2017, arts. 359 e 364; Portaria SAS 118/2014, art. 2º; caderno de SIGTAP.

## 6. Não confundir

| Instrumento | Pergunta que responde | Erro comum |
|---|---|---|
| CNES | Que estrutura, serviços, habilitações e profissionais a unidade declarou? | Tomar o cadastro como capacidade real do dia a dia |
| SIGTAP | Que procedimento é, como se registra e o que exige? | Achar que estar na tabela significa estar apto a fazer |
| Habilitação | O gestor autorizou a unidade a fazer determinado tipo de procedimento? | Achar que a portaria basta sem o registro vigente no CNES |
| Carteira de serviços | O que a unidade efetivamente oferta? | Confundir com o cadastro |
| Leito cadastrado | Quantos leitos existem e quantos estão disponíveis ao SUS? | Confundir com leito operacional (o que está em uso, com equipe) |
| TabNet | Quantos estabelecimentos ativos há, por competência? | Usar como lista completa: ele omite os desativados |

> [!CAUTION]
> **Cadastro não é realidade.** O CNES mostra o que foi declarado no último envio. Leito, sala ou equipamento cadastrado pode estar fechado, parado ou sem equipe. Para saber o que funciona, é preciso outra fonte, como o censo da unidade ou a contagem local.

## 7. Cuidados e limites

- **Foto mensal com defasagem.** Mudanças da operação demoram a aparecer: o envio é mensal, e a atualização leva cerca de 15 dias para aparecer depois do envio.
- **Equipamento existente não é equipamento em uso.** O cadastro separa quantidade existente, em uso e disponível ao SUS.
- **Ausência pode ser lacuna de registro.** Um equipamento comum em centro cirúrgico que não aparece em nenhum hospital do DF sugere falta de registro, não falta do equipamento.
- **Leito "não SUS" em hospital público** indica leito existente ainda não disponibilizado ao SUS. A razão deve ser conferida caso a caso.
- **Tipo e natureza jurídica nem sempre refletem o modelo de gestão.** Na competência 08/2026, o Hospital da Criança de Brasília, gerido por organização social, aparece com natureza de órgão público do DF; o HMIB, de perfil materno-infantil, aparece como hospital geral, porque o tipo sai das atividades declaradas.
- **Região de saúde em código.** O campo de região traz códigos informados pelo gestor, sem descrição oficial no arquivo; ligar às sete Regiões de Saúde do DF exige tabela da SES-DF.

> [!WARNING]
> **Código CNES é texto.** Tem sete dígitos, e muitos começam com zero, como 0010456 (HBDF). Planilha que converte o código em número apaga o zero e quebra qualquer cruzamento entre bases.

## 8. Exemplo integrado: cirurgia bariátrica

1. **RENASES.** A cirurgia bariátrica está na lista de 2012 com quatro critérios de acesso: encaminhamento, regulação, habilitação e protocolo ([caderno de RENASES](../renases/caderno.md)).
2. **Habilitação.** O Ministério da Saúde habilita o hospital como centro de referência; a habilitação, com a portaria e a vigência, é registrada no CNES.
3. **CNES.** Além da habilitação, o cadastro precisa mostrar o serviço, os leitos e os profissionais compatíveis, e estar em dia.
4. **SIGTAP.** Os procedimentos da cirurgia exigem a habilitação; sem ela no cadastro, a produção é rejeitada.
5. **Se o cadastro parar.** Seis meses sem atualização e o hospital é desativado: deixa de apresentar produção, inclusive a desta cirurgia (Portaria SAS 118/2014).
6. **Carteira.** O hospital declara se faz; a declaração pode ser conferida contra a habilitação no CNES e a produção registrada.

## 9. Nesta ferramenta

<!-- Bloco gerado pela ferramenta. Previsto: data e competência da extração do CNES usada; indicadores do DF (hospitais com leitos, leitos existentes, leitos SUS, salas cirúrgicas em centro cirúrgico); panorama da rede hospitalar por grupo (administração direta da SES-DF, IGESDF, Rede Sarah, federal universitário, Forças Armadas, privados e filantrópicos com leitos SUS) e o critério usado; links para as páginas Hospitais e Capacidade. -->

*Bloco gerado pela ferramenta: competência da extração do CNES usada, indicadores de capacidade do DF e panorama da rede hospitalar por grupo, com o critério de classificação e links para as páginas Hospitais e Capacidade.*

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
| Portaria de Consolidação GM/MS nº 1/2017, arts. 358 a 390 e 560 — [transcrição](https://github.com/victorarimatea/doc-governanca-ses-df/blob/main/03-portarias-ministeriais/PORTARIA-CONSOLIDACAO-GMMS-1-2017-ORGANIZACAO-E-FUNCIONAMENTO-DO-SUS.md) | Norma | 24/10/2026 |
| Portaria GM/MS nº 1.646/2015 — [cópia no gov.br da ANS](https://www.gov.br/ans/pt-br/centrais-de-conteudo/portaria-n-1646-de-02-de-outubro-de-2015-cnes-pdf) | Norma | 22/10/2026 |
| Portaria GM/MS nº 2.022/2017 — [cópia da Prefeitura de Jacareí](https://www.jacarei.sp.gov.br/wp-content/uploads/2021/02/Portaria-2022-de-7-de-agosto-de-2017.pdf) | Norma | 22/10/2026 |
| Portaria SAS/MS nº 118/2014, republicada — [cópia da Prefeitura de Campinas](https://saude.campinas.sp.gov.br/saude/lista_legislacoes/legis_2014/U_PT-MS-SAS-118-REP_180214.pdf) | Norma | 22/10/2026 |
| Portaria SAS/MS nº 511/2000 — [cópia da SES-AM](https://www.saude.am.gov.br/wp-content/uploads/2025/01/PT-CNES-PORTARIA-No-511-DE29-DE-DEZEMBRO-DE-2000.pdf) | Norma | 22/10/2026 |
| Portal do CNES — [cnes.datasus.gov.br](https://cnes.datasus.gov.br) | Dado oficial | 22/10/2026 |
| TabNet do CNES, estabelecimentos do DF — [DATASUS](https://tabnet.datasus.gov.br/cgi/deftohtm.exe?cnes/cnv/estabdf.def) | Dado oficial | 22/10/2026 |
| Arquivos de disseminação do CNES, competência 08/2026 (DF) | Dado oficial | 22/10/2026 |
| SES-DF, guia de orientação aos contratados, credenciamento de cirurgias oftalmológicas (edital nº 03/2025) — [InfoSaúde-DF](https://info.saude.df.gov.br/wp-content/uploads/2026/01/GUIA-DE-ORIENTACAO-AOS-CONTRATADOS-CIRURGIAS-OFTALMOLOGICAS-Edital-de-Credenciamento-no-032025-SESDF.pdf) | Documento institucional | 22/10/2026 |
| EBSERH, Manual do CNES, 2ª edição (2021) — [gov.br](https://www.gov.br/hubrasil/pt-br/acesso-a-informacao/boletim-de-servico/sede/2021/anexos/manual-cnes-2a-edicao-v3.pdf) | Documento institucional | 22/10/2026 |

## Histórico de versões

| Versão | Data | O que mudou |
|---|---|---|
| v0.1 | 2026-10-24 | Primeiro rascunho no modelo de caderno v1.1, a partir do capítulo publicado na ferramenta (v0.3.10), da linha de base e da verificação em fonte primária. Aguarda aprovação |
