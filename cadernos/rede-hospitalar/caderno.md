# Rede Hospitalar Pública do DF \- Base de Dados

Base de estudo e pesquisa para alimentar a ferramenta HTML de apresentação e consulta. Versão 1.0, 26/09/2026. Elaborada a partir de fontes oficiais da SES-DF, IGESDF, ICIPE/HCB, EBSERH, CLDF e CNES/DATASUS.

## 0\. Como usar esta base

- Cada hospital é um registro com os mesmos campos (seção 5). O identificador (campo id) é a sigla e serve como chave única.  
- A seção 7 traz os mesmos registros em JSON, pronto para ser copiado para a ferramenta HTML.  
- A seção 8 lista as fontes oficiais para consulta de dados atuais (leitos, filas, CNES), que podem ser linkadas ou embutidas na ferramenta.  
- Valores marcados como 'a confirmar no CNES' não foram localizados em fonte oficial nesta pesquisa.  
- Dados de leitos: PDS 2024-2027 (ano-base 2022), salvo indicação diferente. Leitos mudam com frequência; use a Sala de Situação para valores atuais.

## 1\. Dicionário de campos

- id: Sigla oficial (chave única)  
- nome: Nome oficial  
- ra: Região Administrativa onde está  
- regiao: Região de Saúde (Superintendência)  
- macro: Macrorregião de Saúde (1, 2 ou 3\)  
- tipo\_cnes: Classificação CNES: Geral ou Especializado  
- papel: Papel na rede: Hospital regional, URD, retaguarda, ensino  
- vocacao: Vocação ou especialidade de referência  
- gestao: Modelo de gestão  
- instituicao: Instituição responsável pela gestão  
- cnes: Código CNES  
- endereco: Endereço  
- porta\_aberta: Atende demanda espontânea (pronto-socorro)  
- leitos: Leitos informados e ano  
- uti: Tipos de UTI/UCI  
- servicos: Principais serviços, separados por ponto e vírgula  
- fontes: URLs das fontes do registro

## 2\. Territorialização

Fonte: [Plano Distrital de Saúde 2024-2027](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf) e [Regiões de Saúde \- SES-DF](https://saude.df.gov.br/regioes-de-saude).

| Macrorregião | Região de Saúde | Sigla | Regiões Administrativas |
| :---- | :---- | :---- | :---- |
| Macro 1 | Oeste | SRSOE | Ceilândia, Brazlândia (inclui Sol Nascente/Pôr do Sol) |
| Macro 1 | Sudoeste | SRSSO | Taguatinga, Samambaia, Águas Claras, Recanto das Emas, Vicente Pires, Água Quente |
| Macro 2 | Central | SRSCE | Plano Piloto, Cruzeiro, Lago Norte, Lago Sul, Varjão, Vila Planalto |
| Macro 2 | Centro-Sul | SRSCS | Guará, Núcleo Bandeirante, Candangolândia, Estrutural, Park Way, Riacho Fundo I e II, SIA/SCIA |
| Macro 2 | Sul | SRSSU | Gama, Santa Maria |
| Macro 3 | Norte | SRSNO | Planaltina, Sobradinho, Sobradinho II, Fercal |
| Macro 3 | Leste | SRSLE | Paranoá, Itapoã, São Sebastião, Jardim Botânico, Jardins Mangueiral |

## 3\. Classificação dos hospitais

- Hospital Geral (CNES): várias especialidades básicas, normalmente com pronto-socorro.  
- Hospital Especializado / vocacionado (CNES): foco em um público ou tipo de cuidado.  
- Hospital Regional: hospital geral, porta de entrada hospitalar da Região de Saúde (média complexidade).  
- Unidade de Referência Distrital (URD): atende todo o DF, geralmente por regulação; alta complexidade ou especialidade. URDs: HBDF, HMIB, HCB, HSVP, HAB ([PDS](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf); [SES-DF](https://www.saude.df.gov.br/infos-hospitais)).  
- Retaguarda: sem porta aberta, recebe pacientes transferidos (USol).

## 4\. Modelos de gestão

| Modelo | Natureza jurídica | Instituição | Instrumento | Pessoal e compras | Hospitais |
| :---- | :---- | :---- | :---- | :---- | :---- |
| Administração direta | Órgão público distrital | SES-DF | Orçamento público direto | Servidores concursados; Lei de Licitações | HRAN, HRT, HRC, HRBz, HRSam, HRG, HRGu, HRS, HRPl, HRL, HMIB, HAB, HSVP |
| Serviço Social Autônomo | Pessoa jurídica de direito privado sem fins lucrativos, criada por lei (Lei distrital 6.270/2019) | IGESDF | Contrato de gestão com metas | CLT; regulamento próprio de compras | HBDF, HRSM, USol \+ 13 UPAs |
| Organização Social de Saúde | Associação privada sem fins lucrativos qualificada como OS | ICIPE | Contrato de gestão 076/2019 | CLT; regulamento próprio | HCB |
| Gestão federal | Empresa pública federal vinculada ao MEC | EBSERH / UnB | Contratualização com a SES-DF | Empregados públicos (concurso, CLT) | HUB |
| Rede complementar | Privados e filantrópicos | Diversos (ex.: ICTDF) | Contratos e convênios | Próprios | Leitos e serviços comprados pelo SUS-DF |

Fontes: [PDS](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf); [CLDF \- Nota Técnica IGESDF 2025](https://www.cl.df.gov.br/documents/33062786/35585642/Nota+T%C3%A9cnica+CONLEGIS+-+3%C2%BA+RQDA+2025+IGESDF.pdf/4500ee7b-af12-4dbe-65ca-d44460eb9e7b?version=1.2&t=1777480822675); [Fiocruz Brasília](https://www.fiocruzbrasilia.fiocruz.br/fala-ae-mestre-os-diferentes-modelos-de-gestao-na-saude/); [HCB](https://www.hcb.org.br/geral/icipe-segue-responsavel-pela-gestao-do-hcb); [EBSERH](https://www.gov.br/ebserh/pt-br/hospitais-universitarios/regiao-centro-oeste/hub-unb/acesso-a-informacao/institucional/historia).

## 5\. Registros por hospital

### HBDF \- Hospital de Base do Distrito Federal

- ID: HBDF  
- Nome: Hospital de Base do Distrito Federal  
- RA: Plano Piloto (Asa Sul)  
- Região de Saúde: Central  
- Macrorregião: Macro 2  
- Tipo CNES: Geral  
- Papel na rede: URD \- alta complexidade  
- Vocação: Trauma, neurocirurgia, cardiologia, oncologia  
- Modelo de gestão: Serviço Social Autônomo  
- Instituição gestora: IGESDF  
- CNES: 0010456  
- Endereço: SMHS, Área Especial, Quadra 101, Brasília-DF, CEP 70.335-900  
- Porta aberta: Sim (trauma/ortopedia)  
- Leitos: 642 (2022); 66 UTI adulto e 30 UTI pediátrica (2025)  
- UTI/UCI: UTI adulto; UTI pediátrica  
- Serviços: Cirurgia cardíaca; cabeça e pescoço; cirurgia geral; oncológica; torácica; vascular; oftalmologia; ortopedia; otorrino; coloproctologia; urologia; neurocirurgia; urgência em trauma e ortopedia  
- Fontes: [www\.saude.df.gov.br](https://www.saude.df.gov.br/realizacao-de-cirurgias); [www\.cl.df.gov.br](https://www.cl.df.gov.br/documents/33062786/35585642/Nota+T%C3%A9cnica+CONLEGIS+-+3%C2%BA+RQDA+2025+IGESDF.pdf/4500ee7b-af12-4dbe-65ca-d44460eb9e7b?version=1.2&t=1777480822675); [info.saude.df.gov.br](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf)

### HMIB \- Hospital Materno Infantil de Brasília Dr. Antônio Lisboa

- ID: HMIB  
- Nome: Hospital Materno Infantil de Brasília Dr. Antônio Lisboa  
- RA: Plano Piloto (Asa Sul)  
- Região de Saúde: Central  
- Macrorregião: Macro 2  
- Tipo CNES: Especializado  
- Papel na rede: URD \- materno-infantil  
- Vocação: Gestação de alto risco, neonatologia e pediatria  
- Modelo de gestão: Administração direta  
- Instituição gestora: SES-DF  
- CNES: 0010537  
- Endereço: Av. L2 Sul, Quadra 608, Módulo A, Asa Sul, CEP 70.203-900  
- Porta aberta: Sim (pediatria, GO)  
- Leitos: 176 (2022)  
- UTI/UCI: UTI materna; UTI pediátrica; UTI neonatal; UCI neonatal  
- Serviços: Cirurgia pediátrica; oftalmologia; urgência em pediatria, cirurgia pediátrica, ginecologia e obstetrícia de alto risco  
- Fontes: [www\.saude.df.gov.br](https://www.saude.df.gov.br/realizacao-de-cirurgias); [info.saude.df.gov.br](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf); [info.saude.df.gov.br](https://info.saude.df.gov.br/wp-content/uploads/2025/05/2023_HMIB.pdf)

### HCB \- Hospital da Criança de Brasília José Alencar

- ID: HCB  
- Nome: Hospital da Criança de Brasília José Alencar  
- RA: Plano Piloto (Setor Noroeste)  
- Região de Saúde: Central  
- Macrorregião: Macro 2  
- Tipo CNES: Especializado  
- Papel na rede: URD \- pediatria especializada  
- Vocação: Pediatria de média e alta complexidade; onco-hematologia infantil  
- Modelo de gestão: Organização Social (contrato de gestão 076/2019)  
- Instituição gestora: ICIPE \- Instituto do Câncer Infantil e Pediatria Especializada  
- CNES: a confirmar no CNES  
- Endereço: AENW 03, Setor Noroeste, Brasília-DF  
- Porta aberta: Não (acesso regulado/referenciado)  
- Leitos: 212 leitos, dos quais 58 de UTI  
- UTI/UCI: UTI pediátrica  
- Serviços: Linhas de cuidado clínica, cirúrgica e onco-hematológica; ambulatório de especialidades pediátricas; 2 centros cirúrgicos com 8 salas  
- Fontes: [www\.hcb.org.br](https://www.hcb.org.br/institucional/planta-dos-blocos/); [www\.saude.df.gov.br](https://www.saude.df.gov.br/documents/37101/883336/Carta+de+Servi%C3%A7os+do+Hospital+da+Crian%C3%A7a.pdf); [www\.hcb.org.br](https://www.hcb.org.br/geral/icipe-segue-responsavel-pela-gestao-do-hcb)

### HAB \- Hospital de Apoio de Brasília

- ID: HAB  
- Nome: Hospital de Apoio de Brasília  
- RA: Plano Piloto (Setor Noroeste)  
- Região de Saúde: Central  
- Macrorregião: Macro 2  
- Tipo CNES: Especializado  
- Papel na rede: URD \- cuidados prolongados  
- Vocação: Cuidados paliativos oncológicos/geriátricos e reabilitação neurológica  
- Modelo de gestão: Administração direta  
- Instituição gestora: SES-DF  
- CNES: 2649527  
- Endereço: AENW 03, Lote A, Setor Noroeste, CEP 70.684-831  
- Porta aberta: Não (pacientes encaminhados)  
- Leitos: 58 (2022)  
- UTI/UCI: Não  
- Serviços: Enfermaria de cuidados paliativos oncológicos adultos e geriátricos; ambulatórios de cuidados paliativos (oncológicos, geriátricos, neurológicos); reabilitação de sequelas neurológicas graves  
- Fontes: [www\.saude.df.gov.br](https://www.saude.df.gov.br/en/cuidados-paliativos-2); [www\.saude.df.gov.br](https://www.saude.df.gov.br/en/hospital-de-apoio-de-brasilia); [info.saude.df.gov.br](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf)

### HSVP \- Hospital São Vicente de Paulo

- ID: HSVP  
- Nome: Hospital São Vicente de Paulo  
- RA: Taguatinga  
- Região de Saúde: Sudoeste  
- Macrorregião: Macro 1  
- Tipo CNES: Especializado  
- Papel na rede: URD \- saúde mental  
- Vocação: Psiquiatria  
- Modelo de gestão: Administração direta  
- Instituição gestora: SES-DF  
- CNES: 0010618  
- Endereço: QSC 01, Área Especial 01, Setor C Sul, Taguatinga, CEP 72.016-010  
- Porta aberta: Sim (demanda espontânea 24h)  
- Leitos: 83 leitos psiquiátricos  
- UTI/UCI: Não  
- Serviços: Emergência psiquiátrica 24h; internação psiquiátrica  
- Fontes: [saude.df.gov.br](https://saude.df.gov.br/documents/37101/47644/RELATORIOA_TUALIZADO_2021_HSVP___APROVADO_DGR.pdf/45bd3b81-0aad-0880-f079-810246b76675?t=1652704074613); [info.saude.df.gov.br](https://info.saude.df.gov.br/wp-content/uploads/2025/05/2023_HSVP.pdf)

### HUB \- Hospital Universitário de Brasília

- ID: HUB  
- Nome: Hospital Universitário de Brasília  
- RA: Plano Piloto (Asa Norte)  
- Região de Saúde: Central  
- Macrorregião: Macro 2  
- Tipo CNES: Geral  
- Papel na rede: Hospital de ensino federal, contratualizado com a SES-DF  
- Vocação: Média e alta complexidade; ensino e pesquisa  
- Modelo de gestão: Empresa pública federal  
- Instituição gestora: EBSERH / Universidade de Brasília  
- CNES: a confirmar no CNES  
- Endereço: SGAN 605, L2 Norte, Asa Norte, CEP 70.830-200  
- Porta aberta: Parcial (ex.: emergência GO)  
- Leitos: a confirmar no CNES  
- UTI/UCI: UTI adulto e neonatal (reguladas pela SES-DF)  
- Serviços: Especialidades clínicas e cirúrgicas; ressonância magnética; procedimentos cardiovasculares; ambulatório especializado  
- Fontes: [www\.gov.br](https://www.gov.br/ebserh/pt-br/hospitais-universitarios/regiao-centro-oeste/hub-unb/acesso-a-informacao/institucional/historia); [www\.gov.br](https://www.gov.br/hubrasil/pt-br/hospitais-universitarios/regiao-centro-oeste/hub-unb/governanca/relatorios-de-gestao/plano-operativo-anual)

### HRAN \- Hospital Regional da Asa Norte

- ID: HRAN  
- Nome: Hospital Regional da Asa Norte  
- RA: Plano Piloto (Asa Norte)  
- Região de Saúde: Central  
- Macrorregião: Macro 2  
- Tipo CNES: Geral  
- Papel na rede: Hospital regional  
- Vocação: Queimados e cirurgia plástica (referência distrital)  
- Modelo de gestão: Administração direta  
- Instituição gestora: SES-DF  
- CNES: a confirmar no CNES  
- Endereço: SMHN Quadra 101, Bloco A, Área Especial, CEP 70.710-905  
- Porta aberta: Sim  
- Leitos: 310 (2022)  
- UTI/UCI: UTI adulto  
- Serviços: Bariátrica; cirurgia geral; plástica; torácica; vascular; oftalmologia; otorrino; coloproctologia; urologia; urgência em cirurgia geral, clínica médica, odontologia, GO, queimados  
- Fontes: [www\.saude.df.gov.br](https://www.saude.df.gov.br/realizacao-de-cirurgias); [info.saude.df.gov.br](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf)

### HRGu \- Hospital Regional do Guará

- ID: HRGu  
- Nome: Hospital Regional do Guará  
- RA: Guará  
- Região de Saúde: Centro-Sul  
- Macrorregião: Macro 2  
- Tipo CNES: Geral  
- Papel na rede: Hospital regional de pequeno porte  
- Vocação: Clínica médica e pediatria  
- Modelo de gestão: Administração direta  
- Instituição gestora: SES-DF  
- CNES: a confirmar no CNES  
- Endereço: QI 06, Área Especial C, Guará I  
- Porta aberta: Sim  
- Leitos: 58 (2022)  
- UTI/UCI: Não informado  
- Serviços: Urgência em clínica médica e pediatria  
- Fontes: [www\.saude.df.gov.br](https://www.saude.df.gov.br/realizacao-de-cirurgias); [info.saude.df.gov.br](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf)

### HRG \- Hospital Regional do Gama

- ID: HRG  
- Nome: Hospital Regional do Gama  
- RA: Gama  
- Região de Saúde: Sul  
- Macrorregião: Macro 2  
- Tipo CNES: Geral  
- Papel na rede: Hospital regional  
- Vocação: Geral  
- Modelo de gestão: Administração direta  
- Instituição gestora: SES-DF  
- CNES: a confirmar no CNES  
- Endereço: Área Especial nº 1, Setor Central, Gama, CEP 72.405-901  
- Porta aberta: Sim  
- Leitos: Região Sul: 693 (2022, com HRSM)  
- UTI/UCI: UTI adulto  
- Serviços: Cirurgia geral; vascular; oftalmologia; ortopedia; otorrino; coloproctologia; urologia; urgência em clínica médica, cirúrgica, GO, ortopedia, cardiologia, odontologia  
- Fontes: [www\.saude.df.gov.br](https://www.saude.df.gov.br/realizacao-de-cirurgias); [info.saude.df.gov.br](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf)

### HRSM \- Hospital Regional de Santa Maria

- ID: HRSM  
- Nome: Hospital Regional de Santa Maria  
- RA: Santa Maria  
- Região de Saúde: Sul  
- Macrorregião: Macro 2  
- Tipo CNES: Geral  
- Papel na rede: Hospital regional (2º maior do DF)  
- Vocação: Gestação de alto risco; ortopedia de alta complexidade; bucomaxilofacial  
- Modelo de gestão: Serviço Social Autônomo  
- Instituição gestora: IGESDF  
- CNES: a confirmar no CNES  
- Endereço: Quadra AC 102, Conjuntos A-D, Santa Maria, CEP 72.502-100  
- Porta aberta: Sim  
- Leitos: 403  
- UTI/UCI: UTI adulto; UTI neonatal  
- Serviços: Cirurgia geral; vascular; ortopedia; otorrino; urologia; urgência em clínica médica, cirúrgica, GO, pediatria, ortopedia; atenção domiciliar (NRAD)  
- Fontes: [www\.saude.df.gov.br](https://www.saude.df.gov.br/realizacao-de-cirurgias); [www\.cl.df.gov.br](https://www.cl.df.gov.br/documents/33062786/35585642/Nota+T%C3%A9cnica+CONLEGIS+-+3%C2%BA+RQDA+2025+IGESDF.pdf/4500ee7b-af12-4dbe-65ca-d44460eb9e7b?version=1.2&t=1777480822675)

### HRC \- Hospital Regional de Ceilândia

- ID: HRC  
- Nome: Hospital Regional de Ceilândia  
- RA: Ceilândia  
- Região de Saúde: Oeste  
- Macrorregião: Macro 1  
- Tipo CNES: Geral  
- Papel na rede: Hospital regional  
- Vocação: Geral  
- Modelo de gestão: Administração direta  
- Instituição gestora: SES-DF  
- CNES: 0010480  
- Endereço: QNM 27, Área Especial 01, Ceilândia, CEP 72.215-170  
- Porta aberta: Sim  
- Leitos: Região Oeste: 616 (2022, com HRBz)  
- UTI/UCI: UTI adulto; UTI neonatal; UCI neonatal  
- Serviços: Cirurgia geral; ortopedia; oftalmologia; otorrino; coloproctologia; urgência em pediatria, clínica médica, cirurgia geral, ortopedia/trauma, GO  
- Fontes: [www\.saude.df.gov.br](https://www.saude.df.gov.br/realizacao-de-cirurgias); [info.saude.df.gov.br](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf)

### HRBz \- Hospital Regional de Brazlândia

- ID: HRBz  
- Nome: Hospital Regional de Brazlândia  
- RA: Brazlândia  
- Região de Saúde: Oeste  
- Macrorregião: Macro 1  
- Tipo CNES: Geral  
- Papel na rede: Hospital regional de pequeno porte  
- Vocação: Geral  
- Modelo de gestão: Administração direta  
- Instituição gestora: SES-DF  
- CNES: a confirmar no CNES  
- Endereço: Área Especial 06, Setor Tradicional, Brazlândia, CEP 73.740-793  
- Porta aberta: Sim  
- Leitos: Incluído no total da Região Oeste  
- UTI/UCI: Não informado  
- Serviços: Cirurgia geral; urgência em clínica médica adulto e pediátrica, cirurgia geral e GO  
- Fontes: [www\.saude.df.gov.br](https://www.saude.df.gov.br/realizacao-de-cirurgias)

### USol \- Unidade Cidade do Sol (antigo Hospital Cidade do Sol)

- ID: USol  
- Nome: Unidade Cidade do Sol (antigo Hospital Cidade do Sol)  
- RA: Sol Nascente/Pôr do Sol (Ceilândia)  
- Região de Saúde: Oeste  
- Macrorregião: Macro 1  
- Tipo CNES: Geral (anexo do HRSM no CNES)  
- Papel na rede: Retaguarda clínica  
- Vocação: Pacientes clínicos crônicos e cuidados paliativos  
- Modelo de gestão: Serviço Social Autônomo  
- Instituição gestora: IGESDF  
- CNES: Sem código próprio (anexo ao HRSM)  
- Endereço: Ao lado da UPA Ceilândia, Sol Nascente/Pôr do Sol  
- Porta aberta: Não (só transferências de hospitais e UPAs)  
- Leitos: a confirmar  
- UTI/UCI: Não informado  
- Serviços: Internação clínica de retaguarda (IAM, pneumonia, ITU, insuficiência cardíaca etc.)  
- Fontes: [www\.cl.df.gov.br](https://www.cl.df.gov.br/documents/33062786/35585642/Nota+T%C3%A9cnica+CONLEGIS+-+3%C2%BA+RQDA+2025+IGESDF.pdf/4500ee7b-af12-4dbe-65ca-d44460eb9e7b?version=1.2&t=1777480822675); [igesdf.org.br](https://igesdf.org.br/hospital-cidade-do-sol/)

### HRT \- Hospital Regional de Taguatinga

- ID: HRT  
- Nome: Hospital Regional de Taguatinga  
- RA: Taguatinga  
- Região de Saúde: Sudoeste  
- Macrorregião: Macro 1  
- Tipo CNES: Geral  
- Papel na rede: Hospital regional (grande porte)  
- Vocação: Geral; centro de AVC tipo I  
- Modelo de gestão: Administração direta  
- Instituição gestora: SES-DF  
- CNES: 0010499  
- Endereço: Setor C Norte, Área Especial 24, Taguatinga, CEP 72.120-970  
- Porta aberta: Sim  
- Leitos: Região Sudoeste: 566 (2022, com HRSam)  
- UTI/UCI: Sim  
- Serviços: Pronto-socorro geral; clínica médica; cirurgia; ortopedia; GO; pediatria; atendimento a AVC  
- Fontes: [cnes2.datasus.gov.br](https://cnes2.datasus.gov.br/Mod_Ambulatorial.asp?VCo_Unidade=5300100010499); [bvs.saude.gov.br](https://bvs.saude.gov.br/bvs/saudelegis/sas/2014/prt0184_13_03_2014_comp.html); [info.saude.df.gov.br](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf)

### HRSam \- Hospital Regional de Samambaia

- ID: HRSam  
- Nome: Hospital Regional de Samambaia  
- RA: Samambaia  
- Região de Saúde: Sudoeste  
- Macrorregião: Macro 1  
- Tipo CNES: Geral  
- Papel na rede: Hospital regional  
- Vocação: Clínica médica e maternidade  
- Modelo de gestão: Administração direta  
- Instituição gestora: SES-DF  
- CNES: a confirmar no CNES  
- Endereço: Samambaia-DF  
- Porta aberta: Sim  
- Leitos: 25 clínica médica \+ 50 maternidade (oficiais)  
- UTI/UCI: UTI adulto  
- Serviços: Cirurgia geral; oftalmologia; otorrino; coloproctologia; urologia; urgência em clínica médica e GO; centro obstétrico e maternidade  
- Fontes: [www\.saude.df.gov.br](https://www.saude.df.gov.br/realizacao-de-cirurgias)

### HRS \- Hospital Regional de Sobradinho

- ID: HRS  
- Nome: Hospital Regional de Sobradinho  
- RA: Sobradinho  
- Região de Saúde: Norte  
- Macrorregião: Macro 3  
- Tipo CNES: Geral  
- Papel na rede: Hospital regional  
- Vocação: Geral; cirurgia cardíaca  
- Modelo de gestão: Administração direta  
- Instituição gestora: SES-DF  
- CNES: a confirmar no CNES  
- Endereço: Quadra 12, Área Especial, Sobradinho, CEP 73.010-120  
- Porta aberta: Sim  
- Leitos: Região Norte: 335 (2022, com HRPl)  
- UTI/UCI: Sim  
- Serviços: Cirurgia cardíaca; plástica; vascular; oftalmologia; ortopedia; otorrino; coloproctologia; urologia; urgência em pediatria/neonatologia, clínica médica, cirurgia geral, ortopedia, GO  
- Fontes: [www\.saude.df.gov.br](https://www.saude.df.gov.br/realizacao-de-cirurgias); [info.saude.df.gov.br](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf)

### HRPl \- Hospital Regional de Planaltina

- ID: HRPl  
- Nome: Hospital Regional de Planaltina  
- RA: Planaltina  
- Região de Saúde: Norte  
- Macrorregião: Macro 3  
- Tipo CNES: Geral  
- Papel na rede: Hospital regional  
- Vocação: Geral  
- Modelo de gestão: Administração direta  
- Instituição gestora: SES-DF  
- CNES: a confirmar no CNES  
- Endereço: Av. WL4, Área Especial, Setor Hospitalar, Planaltina, CEP 73.310-000  
- Porta aberta: Sim  
- Leitos: Incluído no total da Região Norte  
- UTI/UCI: UCI neonatal  
- Serviços: Cirurgia geral; ortopedia; urgência em clínica médica, cirúrgica, ortopedia, pediatria e GO  
- Fontes: [www\.saude.df.gov.br](https://www.saude.df.gov.br/realizacao-de-cirurgias)

### HRL \- Hospital da Região Leste (Paranoá)

- ID: HRL  
- Nome: Hospital da Região Leste (Paranoá)  
- RA: Paranoá  
- Região de Saúde: Leste  
- Macrorregião: Macro 3  
- Tipo CNES: Geral  
- Papel na rede: Hospital regional  
- Vocação: Geral  
- Modelo de gestão: Administração direta  
- Instituição gestora: SES-DF  
- CNES: a confirmar no CNES  
- Endereço: Área Especial Hospitalar, Quadra 2, Conj. K, Lote 1, Paranoá, CEP 71.570-050  
- Porta aberta: Sim (24h)  
- Leitos: 219 (2022)  
- UTI/UCI: UTI adulto; UCI neonatal  
- Serviços: Cirurgia geral; ortopedia; oftalmologia; urologia; coloproctologia; vascular; urgência em clínica médica, trauma, pediatria, GO  
- Fontes: [www\.saude.df.gov.br](https://www.saude.df.gov.br/realizacao-de-cirurgias); [info.saude.df.gov.br](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf)

## 6\. Quadro-resumo

| ID | Macro | Região | Tipo | Papel | Gestão | Instituição |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| HBDF | Macro 2 | Central | Geral | URD \- alta complexidade | Serviço Social Autônomo | IGESDF |
| HMIB | Macro 2 | Central | Especializado | URD \- materno-infantil | Administração direta | SES-DF |
| HCB | Macro 2 | Central | Especializado | URD \- pediatria especializada | Organização Social (contrato de gestão 076/2019) | ICIPE \- Instituto do Câncer Infantil e Pediatria Especializada |
| HAB | Macro 2 | Central | Especializado | URD \- cuidados prolongados | Administração direta | SES-DF |
| HSVP | Macro 1 | Sudoeste | Especializado | URD \- saúde mental | Administração direta | SES-DF |
| HUB | Macro 2 | Central | Geral | Hospital de ensino federal, contratualizado com a SES-DF | Empresa pública federal | EBSERH / Universidade de Brasília |
| HRAN | Macro 2 | Central | Geral | Hospital regional | Administração direta | SES-DF |
| HRGu | Macro 2 | Centro-Sul | Geral | Hospital regional de pequeno porte | Administração direta | SES-DF |
| HRG | Macro 2 | Sul | Geral | Hospital regional | Administração direta | SES-DF |
| HRSM | Macro 2 | Sul | Geral | Hospital regional (2º maior do DF) | Serviço Social Autônomo | IGESDF |
| HRC | Macro 1 | Oeste | Geral | Hospital regional | Administração direta | SES-DF |
| HRBz | Macro 1 | Oeste | Geral | Hospital regional de pequeno porte | Administração direta | SES-DF |
| USol | Macro 1 | Oeste | Geral (anexo do HRSM no CNES) | Retaguarda clínica | Serviço Social Autônomo | IGESDF |
| HRT | Macro 1 | Sudoeste | Geral | Hospital regional (grande porte) | Administração direta | SES-DF |
| HRSam | Macro 1 | Sudoeste | Geral | Hospital regional | Administração direta | SES-DF |
| HRS | Macro 3 | Norte | Geral | Hospital regional | Administração direta | SES-DF |
| HRPl | Macro 3 | Norte | Geral | Hospital regional | Administração direta | SES-DF |
| HRL | Macro 3 | Leste | Geral | Hospital regional | Administração direta | SES-DF |

### Complementaridade da rede

1. Atenção Primária (UBS) e UPAs 24h (maioria geridas pelo IGESDF) são a porta de entrada.  
2. Hospitais regionais gerais atendem a média complexidade da sua Região de Saúde.  
3. Casos de alta complexidade ou especialidade são regulados para as URDs (HBDF, HMIB, HCB, HSVP, HAB) e para o HUB.  
4. Alguns regionais têm vocação distrital: queimados (HRAN), cirurgia cardíaca (HRS), gestação de alto risco e ortopedia de alta complexidade (HRSM).  
5. USol e HAB fazem retaguarda e cuidados prolongados, liberando leitos agudos.  
6. A rede complementar contratada cobre lacunas (UTI, cardiologia, transplantes).  
7. Assimetria: alta complexidade concentrada na Macro 2 (Plano Piloto); maior população na Macro 1; menor oferta de alta complexidade na Macro 3\.

Total de leitos gerais de internação da rede em 2022: 3.916 ([PDS](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf)).

## 7\. Dados estruturados (JSON)

Registros de hospitais, sem o campo fontes (ver seção 5):

\[

 {

  "id": "HBDF",

  "nome": "Hospital de Base do Distrito Federal",

  "ra": "Plano Piloto (Asa Sul)",

  "regiao": "Central",

  "macro": "Macro 2",

  "tipo\_cnes": "Geral",

  "papel": "URD \- alta complexidade",

  "vocacao": "Trauma, neurocirurgia, cardiologia, oncologia",

  "gestao": "Serviço Social Autônomo",

  "instituicao": "IGESDF",

  "cnes": "0010456",

  "endereco": "SMHS, Área Especial, Quadra 101, Brasília-DF, CEP 70.335-900",

  "porta\_aberta": "Sim (trauma/ortopedia)",

  "leitos": "642 (2022); 66 UTI adulto e 30 UTI pediátrica (2025)",

  "uti": "UTI adulto; UTI pediátrica",

  "servicos": "Cirurgia cardíaca; cabeça e pescoço; cirurgia geral; oncológica; torácica; vascular; oftalmologia; ortopedia; otorrino; coloproctologia; urologia; neurocirurgia; urgência em trauma e ortopedia"

 },

 {

  "id": "HMIB",

  "nome": "Hospital Materno Infantil de Brasília Dr. Antônio Lisboa",

  "ra": "Plano Piloto (Asa Sul)",

  "regiao": "Central",

  "macro": "Macro 2",

  "tipo\_cnes": "Especializado",

  "papel": "URD \- materno-infantil",

  "vocacao": "Gestação de alto risco, neonatologia e pediatria",

  "gestao": "Administração direta",

  "instituicao": "SES-DF",

  "cnes": "0010537",

  "endereco": "Av. L2 Sul, Quadra 608, Módulo A, Asa Sul, CEP 70.203-900",

  "porta\_aberta": "Sim (pediatria, GO)",

  "leitos": "176 (2022)",

  "uti": "UTI materna; UTI pediátrica; UTI neonatal; UCI neonatal",

  "servicos": "Cirurgia pediátrica; oftalmologia; urgência em pediatria, cirurgia pediátrica, ginecologia e obstetrícia de alto risco"

 },

 {

  "id": "HCB",

  "nome": "Hospital da Criança de Brasília José Alencar",

  "ra": "Plano Piloto (Setor Noroeste)",

  "regiao": "Central",

  "macro": "Macro 2",

  "tipo\_cnes": "Especializado",

  "papel": "URD \- pediatria especializada",

  "vocacao": "Pediatria de média e alta complexidade; onco-hematologia infantil",

  "gestao": "Organização Social (contrato de gestão 076/2019)",

  "instituicao": "ICIPE \- Instituto do Câncer Infantil e Pediatria Especializada",

  "cnes": "a confirmar no CNES",

  "endereco": "AENW 03, Setor Noroeste, Brasília-DF",

  "porta\_aberta": "Não (acesso regulado/referenciado)",

  "leitos": "212 leitos, dos quais 58 de UTI",

  "uti": "UTI pediátrica",

  "servicos": "Linhas de cuidado clínica, cirúrgica e onco-hematológica; ambulatório de especialidades pediátricas; 2 centros cirúrgicos com 8 salas"

 },

 {

  "id": "HAB",

  "nome": "Hospital de Apoio de Brasília",

  "ra": "Plano Piloto (Setor Noroeste)",

  "regiao": "Central",

  "macro": "Macro 2",

  "tipo\_cnes": "Especializado",

  "papel": "URD \- cuidados prolongados",

  "vocacao": "Cuidados paliativos oncológicos/geriátricos e reabilitação neurológica",

  "gestao": "Administração direta",

  "instituicao": "SES-DF",

  "cnes": "2649527",

  "endereco": "AENW 03, Lote A, Setor Noroeste, CEP 70.684-831",

  "porta\_aberta": "Não (pacientes encaminhados)",

  "leitos": "58 (2022)",

  "uti": "Não",

  "servicos": "Enfermaria de cuidados paliativos oncológicos adultos e geriátricos; ambulatórios de cuidados paliativos (oncológicos, geriátricos, neurológicos); reabilitação de sequelas neurológicas graves"

 },

 {

  "id": "HSVP",

  "nome": "Hospital São Vicente de Paulo",

  "ra": "Taguatinga",

  "regiao": "Sudoeste",

  "macro": "Macro 1",

  "tipo\_cnes": "Especializado",

  "papel": "URD \- saúde mental",

  "vocacao": "Psiquiatria",

  "gestao": "Administração direta",

  "instituicao": "SES-DF",

  "cnes": "0010618",

  "endereco": "QSC 01, Área Especial 01, Setor C Sul, Taguatinga, CEP 72.016-010",

  "porta\_aberta": "Sim (demanda espontânea 24h)",

  "leitos": "83 leitos psiquiátricos",

  "uti": "Não",

  "servicos": "Emergência psiquiátrica 24h; internação psiquiátrica"

 },

 {

  "id": "HUB",

  "nome": "Hospital Universitário de Brasília",

  "ra": "Plano Piloto (Asa Norte)",

  "regiao": "Central",

  "macro": "Macro 2",

  "tipo\_cnes": "Geral",

  "papel": "Hospital de ensino federal, contratualizado com a SES-DF",

  "vocacao": "Média e alta complexidade; ensino e pesquisa",

  "gestao": "Empresa pública federal",

  "instituicao": "EBSERH / Universidade de Brasília",

  "cnes": "a confirmar no CNES",

  "endereco": "SGAN 605, L2 Norte, Asa Norte, CEP 70.830-200",

  "porta\_aberta": "Parcial (ex.: emergência GO)",

  "leitos": "a confirmar no CNES",

  "uti": "UTI adulto e neonatal (reguladas pela SES-DF)",

  "servicos": "Especialidades clínicas e cirúrgicas; ressonância magnética; procedimentos cardiovasculares; ambulatório especializado"

 },

 {

  "id": "HRAN",

  "nome": "Hospital Regional da Asa Norte",

  "ra": "Plano Piloto (Asa Norte)",

  "regiao": "Central",

  "macro": "Macro 2",

  "tipo\_cnes": "Geral",

  "papel": "Hospital regional",

  "vocacao": "Queimados e cirurgia plástica (referência distrital)",

  "gestao": "Administração direta",

  "instituicao": "SES-DF",

  "cnes": "a confirmar no CNES",

  "endereco": "SMHN Quadra 101, Bloco A, Área Especial, CEP 70.710-905",

  "porta\_aberta": "Sim",

  "leitos": "310 (2022)",

  "uti": "UTI adulto",

  "servicos": "Bariátrica; cirurgia geral; plástica; torácica; vascular; oftalmologia; otorrino; coloproctologia; urologia; urgência em cirurgia geral, clínica médica, odontologia, GO, queimados"

 },

 {

  "id": "HRGu",

  "nome": "Hospital Regional do Guará",

  "ra": "Guará",

  "regiao": "Centro-Sul",

  "macro": "Macro 2",

  "tipo\_cnes": "Geral",

  "papel": "Hospital regional de pequeno porte",

  "vocacao": "Clínica médica e pediatria",

  "gestao": "Administração direta",

  "instituicao": "SES-DF",

  "cnes": "a confirmar no CNES",

  "endereco": "QI 06, Área Especial C, Guará I",

  "porta\_aberta": "Sim",

  "leitos": "58 (2022)",

  "uti": "Não informado",

  "servicos": "Urgência em clínica médica e pediatria"

 },

 {

  "id": "HRG",

  "nome": "Hospital Regional do Gama",

  "ra": "Gama",

  "regiao": "Sul",

  "macro": "Macro 2",

  "tipo\_cnes": "Geral",

  "papel": "Hospital regional",

  "vocacao": "Geral",

  "gestao": "Administração direta",

  "instituicao": "SES-DF",

  "cnes": "a confirmar no CNES",

  "endereco": "Área Especial nº 1, Setor Central, Gama, CEP 72.405-901",

  "porta\_aberta": "Sim",

  "leitos": "Região Sul: 693 (2022, com HRSM)",

  "uti": "UTI adulto",

  "servicos": "Cirurgia geral; vascular; oftalmologia; ortopedia; otorrino; coloproctologia; urologia; urgência em clínica médica, cirúrgica, GO, ortopedia, cardiologia, odontologia"

 },

 {

  "id": "HRSM",

  "nome": "Hospital Regional de Santa Maria",

  "ra": "Santa Maria",

  "regiao": "Sul",

  "macro": "Macro 2",

  "tipo\_cnes": "Geral",

  "papel": "Hospital regional (2º maior do DF)",

  "vocacao": "Gestação de alto risco; ortopedia de alta complexidade; bucomaxilofacial",

  "gestao": "Serviço Social Autônomo",

  "instituicao": "IGESDF",

  "cnes": "a confirmar no CNES",

  "endereco": "Quadra AC 102, Conjuntos A-D, Santa Maria, CEP 72.502-100",

  "porta\_aberta": "Sim",

  "leitos": "403",

  "uti": "UTI adulto; UTI neonatal",

  "servicos": "Cirurgia geral; vascular; ortopedia; otorrino; urologia; urgência em clínica médica, cirúrgica, GO, pediatria, ortopedia; atenção domiciliar (NRAD)"

 },

 {

  "id": "HRC",

  "nome": "Hospital Regional de Ceilândia",

  "ra": "Ceilândia",

  "regiao": "Oeste",

  "macro": "Macro 1",

  "tipo\_cnes": "Geral",

  "papel": "Hospital regional",

  "vocacao": "Geral",

  "gestao": "Administração direta",

  "instituicao": "SES-DF",

  "cnes": "0010480",

  "endereco": "QNM 27, Área Especial 01, Ceilândia, CEP 72.215-170",

  "porta\_aberta": "Sim",

  "leitos": "Região Oeste: 616 (2022, com HRBz)",

  "uti": "UTI adulto; UTI neonatal; UCI neonatal",

  "servicos": "Cirurgia geral; ortopedia; oftalmologia; otorrino; coloproctologia; urgência em pediatria, clínica médica, cirurgia geral, ortopedia/trauma, GO"

 },

 {

  "id": "HRBz",

  "nome": "Hospital Regional de Brazlândia",

  "ra": "Brazlândia",

  "regiao": "Oeste",

  "macro": "Macro 1",

  "tipo\_cnes": "Geral",

  "papel": "Hospital regional de pequeno porte",

  "vocacao": "Geral",

  "gestao": "Administração direta",

  "instituicao": "SES-DF",

  "cnes": "a confirmar no CNES",

  "endereco": "Área Especial 06, Setor Tradicional, Brazlândia, CEP 73.740-793",

  "porta\_aberta": "Sim",

  "leitos": "Incluído no total da Região Oeste",

  "uti": "Não informado",

  "servicos": "Cirurgia geral; urgência em clínica médica adulto e pediátrica, cirurgia geral e GO"

 },

 {

  "id": "USol",

  "nome": "Unidade Cidade do Sol (antigo Hospital Cidade do Sol)",

  "ra": "Sol Nascente/Pôr do Sol (Ceilândia)",

  "regiao": "Oeste",

  "macro": "Macro 1",

  "tipo\_cnes": "Geral (anexo do HRSM no CNES)",

  "papel": "Retaguarda clínica",

  "vocacao": "Pacientes clínicos crônicos e cuidados paliativos",

  "gestao": "Serviço Social Autônomo",

  "instituicao": "IGESDF",

  "cnes": "Sem código próprio (anexo ao HRSM)",

  "endereco": "Ao lado da UPA Ceilândia, Sol Nascente/Pôr do Sol",

  "porta\_aberta": "Não (só transferências de hospitais e UPAs)",

  "leitos": "a confirmar",

  "uti": "Não informado",

  "servicos": "Internação clínica de retaguarda (IAM, pneumonia, ITU, insuficiência cardíaca etc.)"

 },

 {

  "id": "HRT",

  "nome": "Hospital Regional de Taguatinga",

  "ra": "Taguatinga",

  "regiao": "Sudoeste",

  "macro": "Macro 1",

  "tipo\_cnes": "Geral",

  "papel": "Hospital regional (grande porte)",

  "vocacao": "Geral; centro de AVC tipo I",

  "gestao": "Administração direta",

  "instituicao": "SES-DF",

  "cnes": "0010499",

  "endereco": "Setor C Norte, Área Especial 24, Taguatinga, CEP 72.120-970",

  "porta\_aberta": "Sim",

  "leitos": "Região Sudoeste: 566 (2022, com HRSam)",

  "uti": "Sim",

  "servicos": "Pronto-socorro geral; clínica médica; cirurgia; ortopedia; GO; pediatria; atendimento a AVC"

 },

 {

  "id": "HRSam",

  "nome": "Hospital Regional de Samambaia",

  "ra": "Samambaia",

  "regiao": "Sudoeste",

  "macro": "Macro 1",

  "tipo\_cnes": "Geral",

  "papel": "Hospital regional",

  "vocacao": "Clínica médica e maternidade",

  "gestao": "Administração direta",

  "instituicao": "SES-DF",

  "cnes": "a confirmar no CNES",

  "endereco": "Samambaia-DF",

  "porta\_aberta": "Sim",

  "leitos": "25 clínica médica \+ 50 maternidade (oficiais)",

  "uti": "UTI adulto",

  "servicos": "Cirurgia geral; oftalmologia; otorrino; coloproctologia; urologia; urgência em clínica médica e GO; centro obstétrico e maternidade"

 },

 {

  "id": "HRS",

  "nome": "Hospital Regional de Sobradinho",

  "ra": "Sobradinho",

  "regiao": "Norte",

  "macro": "Macro 3",

  "tipo\_cnes": "Geral",

  "papel": "Hospital regional",

  "vocacao": "Geral; cirurgia cardíaca",

  "gestao": "Administração direta",

  "instituicao": "SES-DF",

  "cnes": "a confirmar no CNES",

  "endereco": "Quadra 12, Área Especial, Sobradinho, CEP 73.010-120",

  "porta\_aberta": "Sim",

  "leitos": "Região Norte: 335 (2022, com HRPl)",

  "uti": "Sim",

  "servicos": "Cirurgia cardíaca; plástica; vascular; oftalmologia; ortopedia; otorrino; coloproctologia; urologia; urgência em pediatria/neonatologia, clínica médica, cirurgia geral, ortopedia, GO"

 },

 {

  "id": "HRPl",

  "nome": "Hospital Regional de Planaltina",

  "ra": "Planaltina",

  "regiao": "Norte",

  "macro": "Macro 3",

  "tipo\_cnes": "Geral",

  "papel": "Hospital regional",

  "vocacao": "Geral",

  "gestao": "Administração direta",

  "instituicao": "SES-DF",

  "cnes": "a confirmar no CNES",

  "endereco": "Av. WL4, Área Especial, Setor Hospitalar, Planaltina, CEP 73.310-000",

  "porta\_aberta": "Sim",

  "leitos": "Incluído no total da Região Norte",

  "uti": "UCI neonatal",

  "servicos": "Cirurgia geral; ortopedia; urgência em clínica médica, cirúrgica, ortopedia, pediatria e GO"

 },

 {

  "id": "HRL",

  "nome": "Hospital da Região Leste (Paranoá)",

  "ra": "Paranoá",

  "regiao": "Leste",

  "macro": "Macro 3",

  "tipo\_cnes": "Geral",

  "papel": "Hospital regional",

  "vocacao": "Geral",

  "gestao": "Administração direta",

  "instituicao": "SES-DF",

  "cnes": "a confirmar no CNES",

  "endereco": "Área Especial Hospitalar, Quadra 2, Conj. K, Lote 1, Paranoá, CEP 71.570-050",

  "porta\_aberta": "Sim (24h)",

  "leitos": "219 (2022)",

  "uti": "UTI adulto; UCI neonatal",

  "servicos": "Cirurgia geral; ortopedia; oftalmologia; urologia; coloproctologia; vascular; urgência em clínica médica, trauma, pediatria, GO"

 }

\]

## 8\. Fontes oficiais para consulta de dados atuais

- [InfoSaúde DF \- Sala de Situação](https://info.saude.df.gov.br/sala-de-situacao/): Painéis de leitos de enfermaria, UTI, lista de espera de UTI e séries históricas  
- [Painel de leitos de UTI](https://info.saude.df.gov.br/sala-de-situacao/painel-infosaude-leitos-hospitalares-leitos-uti-gerais/): Ocupação de UTI em tempo quase real  
- [Painel de lista de espera de UTI](https://info.saude.df.gov.br/sala-de-situacao/painel-infosaude-leitos-hospitalares-lista-espera-leitos-uti/): Fila de regulação de UTI  
- [Painel de leitos de enfermaria](https://info.saude.df.gov.br/sala-de-situacao/painel-infosaude-leitos-hospitalares-leitos-enfermaria/): Ocupação de enfermarias  
- [SES-DF \- Regiões de Saúde](https://saude.df.gov.br/regioes-de-saude): Superintendências, contatos e RAs  
- [SES-DF \- Hospitais](https://www.saude.df.gov.br/infos-hospitais): Lista de hospitais e telefones  
- [SES-DF \- Realização de cirurgias](https://www.saude.df.gov.br/realizacao-de-cirurgias): Serviços cirúrgicos e de urgência por hospital  
- [Organograma SES-DF](https://info.saude.df.gov.br/wp-content/uploads/2026/04/Organograma_geral-abril.pdf): Estrutura administrativa atual  
- [Plano Distrital de Saúde 2024-2027](https://info.saude.df.gov.br/wp-content/uploads/2025/05/PDS_2024_2027___VERSAO_ATUALIZADA_POS_APROVACAO_DO_CG.pdf): Macrorregiões, leitos e modelos de gestão  
- [CNES/DATASUS \- Consulta de estabelecimentos](https://cnes.datasus.gov.br/pages/estabelecimentos/consulta.jsp): Leitos, serviços, habilitações e equipes oficiais por hospital  
- [IGESDF](https://igesdf.org.br/): Unidades geridas e relatórios de contrato de gestão  
- [HCB \- Transparência](https://www.hcb.org.br/transparencia/relatorios/): Relatórios mensais do contrato de gestão SES-DF/ICIPE  
- [HUB-UnB/EBSERH](https://www.gov.br/ebserh/pt-br/hospitais-universitarios/regiao-centro-oeste/hub-unb): Serviços e plano operativo