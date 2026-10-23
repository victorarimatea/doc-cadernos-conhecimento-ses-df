# Vocabulário controlado

**Versão:** v0.1 — 2026-10-23 · **Situação:** rascunho, a validar

Fonte única dos verbetes de conceito da wiki e dos links automáticos entre cadernos. Na geração da ferramenta, cada termo (ou sinônimo) encontrado num caderno vira link para o verbete — no máximo um link por conceito por seção, e apenas no sentido registrado aqui.

## Como registrar um conceito

| Campo | Conteúdo |
|---|---|
| `id` | Identificador estável, minúsculo, sem acento (ex.: `habilitacao-estabelecimento`) |
| Termo | Forma preferida |
| Sinônimos | Outras formas que devem virar link para este verbete |
| Definição | Duas ou três linhas, em linguagem simples |
| Não confundir com | Conceitos parecidos com outro sentido |
| Caderno principal | Caderno que explica o conceito |
| Normas | Normas que o regem, com dispositivo |
| Origem do termo | Norma, uso técnico corrente ou síntese analítica (para não dar força normativa a termo acadêmico) |

## Conceitos

| id | Termo | Sinônimos | Definição | Não confundir com | Caderno principal | Normas | Origem do termo |
|---|---|---|---|---|---|---|---|
| `renases` | RENASES | Relação Nacional de Ações e Serviços de Saúde | Lista oficial das ações e serviços que o SUS oferece, organizada em cinco componentes, com o critério de acesso de cada item | RENAME; SIGTAP | RENASES | Decreto 7.508/2011, arts. 21 a 24; Portaria GM/MS 841/2012 | Norma |
| `rename` | RENAME | Relação Nacional de Medicamentos Essenciais | Lista oficial dos medicamentos padronizados no SUS, atualizada periodicamente | RENASES | — | Decreto 7.508/2011, arts. 25 a 29 | Norma |
| `sigtap` | SIGTAP | Tabela de Procedimentos, Medicamentos e OPM do SUS; Tabela SUS | Tabela nacional que identifica cada procedimento por código e define as regras para registrá-lo e aceitá-lo | RENASES; orçamento | SIGTAP | Portarias GM/MS 321/2007 e 2.848/2007 | Norma |
| `cnes` | CNES | Cadastro Nacional de Estabelecimentos de Saúde | Cadastro oficial dos estabelecimentos, com estrutura, profissionais, serviços e habilitações | capacidade operacional | CNES | a registrar no caderno CNES | Norma |
| `habilitacao-estabelecimento` | habilitação | habilitação do estabelecimento | Autorização do gestor para que um estabelecimento já credenciado ao SUS execute determinados procedimentos da tabela | habilitação profissional; serviço/classificação do CNES | CNES | Portaria GM/MS 841/2012, art. 7º, IV | Norma |
| `regulacao-acesso` | regulação do acesso | regulação; central de regulação | Autorização prévia, por central ou complexo regulador, para o acesso do usuário a uma ação ou serviço | regulação sanitária | RENASES | Portaria GM/MS 841/2012, art. 7º, III; Portaria SES-DF 1.388/2018 | Norma |
| `relacao-complementar` | relação complementar | relação específica e complementar | Lista adotada por estado, DF ou município para incluir ações e serviços que não constam da RENASES | carteira de serviços | RENASES | Decreto 7.508/2011, art. 24; Resolução CIT 2/2012, art. 6º | Norma |
| `carteira-servicos` | carteira de serviços | — | Relação do que uma unidade ou rede efetivamente oferta, com os itens e a forma de acesso | Carta de Serviços ao Usuário; RENASES | Carteira de serviços | a registrar | Uso técnico corrente |
| `carta-servicos-usuario` | Carta de Serviços ao Usuário | Carta de Serviços | Documento que informa ao cidadão os serviços prestados, como acessá-los e os compromissos de atendimento | carteira de serviços | Carteira de serviços | Lei 13.460/2017 | Norma |
| `padrao-integralidade` | padrão de integralidade | — | Expressão usada na literatura para o conjunto de ações e serviços que o SUS se compromete a ofertar numa região | RENASES (a norma não usa a expressão) | RENASES | — | Síntese analítica (literatura) |
