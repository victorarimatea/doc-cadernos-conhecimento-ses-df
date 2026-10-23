# Linha de base do capítulo CNES (ferramenta v0.3.10)

Registro de trabalho da Etapa 2 do caderno de CNES, feito em 22/10/2026. Não é mantido
depois: vale como fotografia do que o capítulo dizia antes de ter caderno.

- **Origem do texto:** capítulo "CNES: o cadastro dos estabelecimentos de saúde", rota
  `#k-cnes` da ferramenta publicada (v0.3.10), extraído de
  `build/carteira_v0.3.10.packed.json` (campo `conh.capitulos`, id `cnes`). Conteúdo
  datado pela ferramenta em 26/09/2026.
- **Texto preservado como está.** Só a marcação abaixo foi acrescentada, entre colchetes, no
  início de cada afirmação. Os parágrafos e as linhas de quadro foram mantidos inteiros.
- **Bloco gerado pela ferramenta** (fora do texto): na seção 6 a ferramenta acrescenta quatro
  indicadores calculados do CNES 08/2026 (hospitais com leitos, leitos existentes, leitos SUS
  e salas cirúrgicas em centro cirúrgico). Não entra nesta linha de base.

## Legenda

| Marca | Significa | O que a Etapa 3 faz com ela |
|---|---|---|
| **[N]** | Afirmação normativa: o que uma norma determina | Conferir em fonte primária, com link e data |
| **[I]** | Afirmação institucional ou de funcionamento: quem faz, como o sistema opera, sem citar norma | Conferir em fonte oficial (DATASUS, SES-DF) ou marcar pendente |
| **[D]** | Dado do projeto: números e achados das extrações do CNES 08/2026 e do 1º ciclo | Conferir contra a base do projeto (não contra norma) |
| **[O]** | Orientação ao gestor: leitura, cuidado ou recomendação do projeto | Revisar redação; não precisa de fonte normativa |

---

## 1. O que é o CNES

**[N]** O Cadastro Nacional de Estabelecimentos de Saúde (CNES) é o registro oficial de todos os estabelecimentos de saúde do país, públicos e privados. Foi instituído na forma atual pela Portaria GM/MS nº 1.646/2015, hoje reunida na Portaria de Consolidação nº 1/2017. O cadastro é obrigatório para que qualquer estabelecimento funcione no território nacional (art. 4º).

**[I]** Cada estabelecimento tem um código CNES de sete dígitos. É esse código que os sistemas do SUS usam para aceitar ou rejeitar a produção: o SIA e o SIH só aprovam procedimentos de estabelecimentos, serviços e profissionais cadastrados e compatíveis com as exigências da SIGTAP.

## 2. O que o CNES registra

**[I]** Quadro, mantido inteiro (o conteúdo da coluna "Uso na carteira" é **[O]**):

| Bloco | O que registra | Uso na carteira |
|---|---|---|
| Estabelecimento | Tipo de unidade, natureza jurídica, gestão, vínculo com o SUS, endereço, turno e fluxo de clientela | Identificar a unidade e seu perfil |
| Instalações físicas | Salas de cirurgia do centro cirúrgico e do centro obstétrico, leitos de recuperação pós-anestésica, consultórios | Contexto de capacidade cirúrgica e ambulatorial |
| Leitos | Por tipo e especialidade: existentes, SUS e não SUS | Capacidade de internação |
| Equipamentos | Quantidade existente, em uso e disponível ao SUS | Apoio diagnóstico e terapêutico |
| Serviços especializados | Serviço e classificação, próprio ou terceirizado, ambulatorial ou hospitalar | Principal ponte com a SIGTAP |
| Habilitações | Habilitação, portaria e vigência | Condição para registrar procedimentos que exigem habilitação |
| Profissionais e vínculos | CBO, carga horária, tipo de vínculo, atendimento SUS | Força de trabalho (na ferramenta, só agregados) |

## 3. Competência mensal e responsabilidade

**[N]** O cadastro é **autodeclaratório**. Pela Portaria nº 1.646/2015, cadastrar e manter os dados é responsabilidade de cada estabelecimento, por seus responsáveis técnicos ou administrativos (art. 7º), e o gestor do SUS pode desativar cadastros irregulares. Estabelecimentos sem atualização há mais de seis meses são desativados automaticamente (Portaria SAS/MS nº 118/2014).

**[I]** A base nacional é fechada por **competência mensal** e divulgada pelo DATASUS. Na SES-DF, o cadastramento de estabelecimentos é conduzido pela Gerência de Cadastramento de Estabelecimentos e Usuários do SUS, na SUPLANS. **[O]** Nas unidades, a atualização depende de quem conhece a operação: direção, núcleos de faturamento e responsáveis técnicos.

> Destaque informativo — **[O]** **Quando atualizar.** Sempre que um leito, sala, equipamento, serviço ou profissional mudar. Um cadastro atrasado faz a produção ser rejeitada e distorce qualquer análise de capacidade.

## 4. Por que importa para a carteira e para a capacidade

**[O]** **Aptidão.** A SIGTAP associa cada procedimento a CBO, serviço/classificação, habilitação e tipo de leito. O CNES mostra se o hospital tem esses itens. A combinação indica o que a unidade está apta a registrar. A carteira indica o que ela diz fazer; a produção, o que fez.

**[O]** **Capacidade instalada.** Leitos, salas cirúrgicas, equipamentos e carga horária profissional são insumos para estimar capacidade instalada. Não medem capacidade produtiva: faltam agenda, ocupação, equipes de fato escaladas, anestesia e insumos.

**[O]** **Conferência cruzada.** Na validação da carteira, o CNES ajuda a encontrar incoerências nos dois sentidos: procedimento declarado sem serviço ou habilitação cadastrada, e serviço cadastrado sem nenhum procedimento declarado.

## 5. Limites conhecidos: cadastro não é realidade

- **[O]** **Foto mensal com defasagem.** Mudanças operacionais demoram a aparecer no cadastro.
- **[O][D]** **Leito cadastrado não é leito operacional.** No 1º ciclo da carteira, o HSVP registrou 83 leitos habilitados e 48 operacionais. Contagens físicas feitas pelas unidades costumam divergir do CNES.
- **[I]** **Equipamento existente não é equipamento em uso.** O CNES separa quantidade existente, em uso e disponível ao SUS; um equipamento cadastrado pode estar parado.
- **[D]** **Ausências que surpreendem.** O arco cirúrgico (código 0124) não aparece em nenhum estabelecimento do DF na competência 08/2026, embora seja comum em centros cirúrgicos. A ausência no cadastro pode ser lacuna de registro.
- **[O]** **Leitos "não SUS" em hospital público.** Em geral são leitos existentes, sobretudo de UTI e de cuidado intermediário neonatal, ainda não habilitados ao SUS.
- **[D]** **Tipo e natureza jurídica nem sempre refletem o modelo.** O HCB, gerido por organização social, aparece com natureza de órgão público do DF; o HMIB, hospital de perfil materno-infantil, aparece como hospital geral.
- **[D]** **Região de saúde codificada.** O campo de região vem com códigos informados pelo gestor, sem descrição oficial no arquivo; o mapeamento para as 7 Regiões exige tabela da SES-DF.
- **[D]** **Descrições faltantes.** Pequena parte dos códigos de leito, equipamento, serviço e CBO não tem descrição nas tabelas auxiliares oficiais.

> Destaque de atenção — **[O]** **Código CNES é texto.** São sete dígitos, e muitos começam com zero, como 0010456 (HBDF) ou 0010480 (HRC). Planilhas que convertem o código em número apagam o zero e quebram qualquer cruzamento.

## 6. Como esta ferramenta usa o CNES

**[D]** A ferramenta usa a extração **CNES_DF_202608**, competência 08/2026, publicada pelo DATASUS em 15/09/2026. O panorama da rede hospitalar reúne **44 hospitais**: 22 públicos e 22 privados ou filantrópicos com leitos SUS.

**[D]** Quadro, mantido inteiro:

| Grupo no panorama | Hospitais | Observação |
|---|---|---|
| SES-DF, administração direta | 14 | Os 13 hospitais da carteira e o HCB, que o CNES registra com natureza pública do DF |
| IGESDF (serviço social autônomo) | 2 | HBDF e HRSM |
| Rede Sarah (serviço social autônomo) | 1 | Sarah Brasília, com leitos SUS |
| Federal universitário | 1 | HUB |
| Forças Armadas | 4 | HFA, HFAB, HMAB e HNAB, sem leitos SUS |
| Privados e filantrópicos com leitos SUS | 22 | Hospitais gerais, especializados (como o ICTDF) e hospitais-dia, a maioria de oftalmologia |

**[D]** Critério usado: é hospital o estabelecimento dos tipos hospital geral, hospital especializado, unidade mista ou hospital-dia; é público o de natureza jurídica da administração pública ou de serviço social autônomo.

> Destaque informativo — **[O]** **Recortes diferentes.** Os números do CNES são de cadastro. Quando divergirem da estrutura declarada na PLAN1 ou de contagens locais, as duas informações valem como recortes com fonte e data próprias, não como erro de uma delas.

## Fontes listadas no capítulo

- CNES – consulta de estabelecimentos: https://cnes.datasus.gov.br/pages/estabelecimentos/consulta.jsp
- Portaria GM/MS nº 1.646/2015: https://bvsms.saude.gov.br/bvs/saudelegis/gm/2015/prt1646_02_10_2015.html
- InfoSaúde – base legal do CNES: https://info.saude.df.gov.br/sala-de-situacao/painel-infosaude-base-legal-do-cnes/
- Wiki CNES (DATASUS): https://wiki.saude.gov.br/cnes/index.php/Portal_CNES

---

## Resumo para a Etapa 3

**Afirmações normativas a conferir em fonte primária**

| # | Afirmação | Norma citada | Observação |
|---|---|---|---|
| N1 | O CNES foi instituído na forma atual pela Portaria GM/MS nº 1.646/2015 | Portaria GM/MS 1.646/2015 | Conferir também a norma de criação original do CNES, que o capítulo não cita |
| N2 | A Portaria 1.646/2015 está reunida na Portaria de Consolidação nº 1/2017 | PRC GM/MS 1/2017 | Conferir artigo e anexo de destino |
| N3 | O cadastro é obrigatório para todo estabelecimento funcionar (art. 4º) | Portaria 1.646/2015, art. 4º | Conferir número do artigo no texto vigente (consolidado) |
| N4 | Cadastrar e manter é responsabilidade do estabelecimento, por seus responsáveis técnicos ou administrativos (art. 7º) | Portaria 1.646/2015, art. 7º | Idem |
| N5 | O gestor do SUS pode desativar cadastros irregulares | Portaria 1.646/2015 (sem artigo) | Localizar o artigo |
| N6 | Desativação automática após seis meses sem atualização | Portaria SAS/MS nº 118/2014 | Conferir se segue vigente e se foi consolidada |

**Afirmações institucionais a conferir em fonte oficial**

| # | Afirmação | Onde conferir |
|---|---|---|
| I1 | SIA e SIH só aprovam produção de estabelecimento, serviço e profissional cadastrados e compatíveis com a SIGTAP | Manuais do SIA/SIH, Wiki CNES/SIGTAP |
| I2 | Conteúdo dos sete blocos do cadastro (quadro da seção 2) | Wiki CNES, manual do CNES, dicionário dos arquivos de disseminação |
| I3 | Base fechada por competência mensal e divulgada pelo DATASUS | DATASUS (arquivos de disseminação, TabNet) |
| I4 | Na SES-DF, o cadastramento é conduzido pela Gerência de Cadastramento de Estabelecimentos e Usuários do SUS, na SUPLANS | Organograma e InfoSaúde da SES-DF; atenção à reestruturação de 2026 |
| I5 | Equipamentos separados em existente, em uso e disponível ao SUS | Dicionário dos arquivos de equipamentos do CNES |

**Dados do projeto a conferir contra a base** (`data/cnes/` e notas de força de trabalho e habilitação no Project): D1 data de publicação da competência 08/2026 (15/09/2026); D2 44 hospitais e a divisão por grupo; D3 HSVP com 83 leitos habilitados e 48 operacionais no 1º ciclo; D4 ausência do código de equipamento 0124 no DF; D5 natureza jurídica do HCB e tipo do HMIB; D6 campo de região codificado; D7 códigos sem descrição.

**Lacunas em relação à estrutura pedida para o caderno**: o capítulo não trata do histórico do CNES (norma de criação, versões do sistema), de como consultar (portal, TabNet, arquivos de disseminação, com o caminho exato), nem da relação com a RENASES (critério de acesso por habilitação). Não tem exemplo integrado nem síntese prática.
