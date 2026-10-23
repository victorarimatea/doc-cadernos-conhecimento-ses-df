# CAPÍTULO SIGTAP

Projeto Carteira de Serviços da SES-DF · Caderno de conhecimento · **v1.0** · texto de 26/09/2026 (Google Doc "cap-sigtap", sem número de versão; v1.0 atribuída na migração para o repositório em 22/10/2026)

A **SIGTAP** é o sistema e a tabela nacional que padronizam como o SUS descreve, registra, valida e, em muitos casos, atribui valores a procedimentos, medicamentos e OPM (órteses, próteses e materiais especiais). Ela é a ponte entre a assistência prestada ao usuário, o registro nos sistemas de informação, a auditoria/controle da produção e partes importantes do financiamento federal — mas **não equivale, por si só, ao orçamento nem garante que todo procedimento realizado gerará um repasse adicional**.\[[bvsms.saude.gov](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2007/prt2848_06_11_2007.html)\]\[[gov](https://www.gov.br/saude/pt-br/acesso-a-informacao/gestao-do-sus/programacao-regulacao-controle-e-financiamento-da-mac/financiamento-da-media-e-alta-complexidades-mac)\]

## O que é a SIGTAP

SIGTAP significa **Sistema de Gerenciamento da Tabela de Procedimentos, Medicamentos e OPM do SUS**. Na prática, o nome costuma designar duas coisas relacionadas:

- A **Tabela de Procedimentos, Medicamentos e OPM do SUS**, isto é, o catálogo nacional de itens assistenciais.
- O **sistema eletrônico de gestão e consulta** dessa tabela, disponível por competência mensal, com regras, atributos e histórico de alterações.

Ela define uma linguagem comum para o país inteiro. Assim, um procedimento registrado por um município, um hospital estadual, uma unidade filantrópica contratada ou um serviço privado complementar pode ser identificado pelo mesmo código e submetido a regras padronizadas de registro e processamento.

A SIGTAP não é simplesmente uma “lista de preços”. Para cada item, ela pode reunir atributos como:

- Código e nome do procedimento.
- Descrição.
- Grupo, subgrupo e forma de organização.
- Modalidade assistencial e nível de complexidade.
- Instrumento de registro permitido, como BPA, APAC, AIH e RAAS.
- Valor relacionado à produção e/ou financiamento, conforme o procedimento.
- Compatibilidades com CID, procedimentos principais e secundários, idade, sexo e outros requisitos.
- Serviço/classificação no CNES exigidos.
- Habilitações necessárias do estabelecimento.
- Regras de permanência, quantidade, composição e relacionamento com OPM ou medicamentos.
- Vigência inicial e final, bem como a portaria ou ato que incluiu, modificou ou excluiu o item.

Portanto, ela funciona como uma espécie de **cadastro clínico-administrativo nacional**, indispensável para traduzir uma ação de saúde em informação processável pelo SUS.\[[gov](https://www.gov.br/saude/pt-br/centrais-de-conteudo/publicacoes/guias-e-manuais/2026/manual-de-operacionalizacao-nos-sistemas-de-informacao-ressarcimento-ao-sus.pdf)\]\[[wiki.saude.gov](https://wiki.saude.gov.br/sigtap/index.php/P%C3%A1gina_principal)\]\[[portal.pi.gov](https://portal.pi.gov.br/sesapi/wp-content/uploads/sites/101/2026/07/Manual_de_Faturamento_para_Gestao_da_Rede_Hospitalar_e_Ambulatorial_do_Estado_do_Piaui_concluido.pdf)\]

## Origem e evolução

Antes da tabela unificada, a codificação da produção era separada entre:

- A tabela do **SIA/SUS**, voltada à produção ambulatorial.
- A tabela do **SIH/SUS**, voltada à produção hospitalar.

A unificação buscou integrar essas duas linguagens e reduzir divergências entre a assistência ambulatorial e hospitalar. A Tabela de Procedimentos, Medicamentos e OPM do SUS e o SIGTAP foram instituídos em 2007; a tabela unificada passou a substituir as tabelas anteriores a partir da competência de janeiro de 2008. A base normativa inclui a Portaria GM/MS nº 321/2007 e a Portaria GM/MS nº 2.848/2007; posteriormente, a Portaria de Consolidação GM/MS nº 1/2017 tornou-se a referência consolidada sobre o tema.\[[bvsms.saude.gov](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2007/prt2848_06_11_2007.html)\]\[[wiki.saude.gov](http://wiki.saude.gov.br/sigtap/)\]\[[info.saude.df.gov](https://info.saude.df.gov.br/wp-content/uploads/2023/11/Manual_Operacional_APAC_v_1_1.pdf)\]\[[w3.datasus.gov](http://w3.datasus.gov.br/sia/index.php?area=0408)\]

A mudança foi relevante porque criou um vocabulário comum para os sistemas de informação assistencial. Depois da implantação do CNES — o cadastro nacional de estabelecimentos de saúde — a SIGTAP se consolidou como outro eixo da padronização: o CNES informa **quem/onde** presta o serviço e com quais condições; a SIGTAP informa **o que** foi realizado e sob quais regras esse registro pode ser aceito.

## Como a tabela é estruturada

A estrutura é hierárquica, permitindo analisar desde grandes áreas de atenção até o procedimento específico:

|                      |                                                                                                                |
|----------------------|----------------------------------------------------------------------------------------------------------------|
| **Nível**            | **Função**                                                                                                     |
| Grupo                | Maior nível de agregação; reúne procedimentos com características ou finalidade assistencial semelhantes       |
| Subgrupo             | Agrupa procedimentos por tipo ou área de atuação                                                               |
| Forma de organização | Organiza por especialidade, sistema corporal, região anatômica, tipo de exame, cirurgia, equipamento, OPM etc. |
| Procedimento         | Unidade mais detalhada — a “célula” da tabela — usada no registro e processamento da produção                  |

O código do procedimento tem **dez dígitos**. Em regra, os dois primeiros correspondem ao grupo, o 3º e 4º ao subgrupo, o 5º e 6º à forma de organização, os três seguintes são sequenciais dentro dessa forma e o último é um dígito verificador. A estrutura possui nove grupos gerais de procedimentos.\[[gov](https://www.gov.br/saude/pt-br/centrais-de-conteudo/publicacoes/guias-e-manuais/2026/manual-de-operacionalizacao-nos-sistemas-de-informacao-ressarcimento-ao-sus.pdf)\]\[[wiki.saude.gov](https://wiki.saude.gov.br/sigtap/index.php/P%C3%A1gina_principal)\]

### O que deve ser lido além do código

Para o gestor, faturista, auditor ou responsável técnico, identificar o código é só o começo. É essencial consultar os atributos do procedimento vigente naquela competência:

1.  **Descrição e finalidade clínica**: confirma o que está sendo efetivamente codificado.
2.  **Instrumento de registro**: indica se a produção deve ser lançada, por exemplo, em BPA, APAC, AIH ou RAAS.
3.  **Compatibilidades**: mostra quais diagnósticos, procedimentos principais, procedimentos secundários ou condições podem ser associados.
4.  **CNES, serviço e habilitação**: verifica se aquele estabelecimento está cadastrado e habilitado para produzir o item.
5.  **Faixa etária, sexo e quantidade**: evita rejeições por inconsistência.
6.  **Valor e modalidade de financiamento**: ajuda a compreender a valoração da produção, mas não substitui a consulta ao contrato, à programação, ao teto financeiro e às regras de custeio vigentes.
7.  **Vigência**: assegura que o código e suas regras eram válidos no mês em que o atendimento ocorreu.

## Como a SIGTAP é revisada

A SIGTAP é dinâmica: sua versão relevante é a da **competência mensal** do atendimento/faturamento. As mudanças podem incluir procedimentos novos, exclusões, alteração de descrição, valor, regras de compatibilidade, instrumentos de registro, habilitações, limites ou formas de financiamento.

A revisão decorre principalmente de atos normativos e decisões técnicas do Ministério da Saúde, incluindo portarias, notas técnicas e documentos complementares. A tabela mantém as referências de vigência e do documento que incluiu ou encerrou cada item. O próprio SIGTAP disponibiliza histórico, relatórios e notas técnicas mensais sobre as alterações. Além disso, são disponibilizados arquivos por competência para importação nos sistemas que captam e processam a produção assistencial.\[[wiki.saude.gov](https://wiki.saude.gov.br/sigtap/index.php/Gerais)\]\[[wiki.saude.gov](https://wiki.saude.gov.br/sigtap/index.php/P%C3%A1gina_principal?veaction=edit)\]

### Lógica da atualização

Uma alteração tende a decorrer da combinação de fatores como:

- Incorporação ou mudança de tecnologias e práticas assistenciais.
- Necessidades epidemiológicas e prioridades nacionais.
- Revisões técnicas de protocolos e linhas de cuidado.
- Criação ou alteração de políticas estratégicas.
- Necessidade de ajustar regras de registro, controle, auditoria ou monitoramento.
- Mudanças no financiamento de determinadas ações e serviços.
- Correção de inconsistências ou aperfeiçoamento das regras de processamento.

O ponto operacional mais importante é: **faturar a competência correta exige utilizar a versão correta da SIGTAP**. Usar um código, valor ou regra de uma competência posterior pode levar a críticas, rejeições, glosas ou distorções na base de produção.

## Importância na carteira de serviços

A carteira de serviços define aquilo que uma unidade, rede, município ou região **pretende e tem condições de ofertar**. A SIGTAP oferece a taxonomia padronizada para transformar essa carteira em algo operacional, mensurável, contratável e auditável.

Uma boa carteira de serviços não deve nascer da SIGTAP isoladamente. Ela deve partir das necessidades de saúde da população, perfil epidemiológico, território, rede regionalizada, capacidade instalada, recursos humanos, equipamentos, contratos, regulação e orçamento. A SIGTAP entra para **codificar, parametrizar e acompanhar** a entrega da carteira.

|                                  |                                                                                                                        |
|----------------------------------|------------------------------------------------------------------------------------------------------------------------|
| **Uso da SIGTAP na carteira**    | **Consequência prática**                                                                                               |
| Descrever serviços ofertados     | Cada consulta, exame, procedimento, terapia ou internação pode ser associado a códigos padronizados                    |
| Verificar capacidade habilitada  | A unidade só deve programar e registrar itens compatíveis com CNES, serviços e habilitações existentes                 |
| Dimensionar metas físicas        | Permite projetar quantidades: consultas, exames, cirurgias, sessões, internações etc.                                  |
| Estimar necessidades financeiras | Os valores SIGTAP ajudam na análise, mas o custeio real deve considerar custos locais, contratos e limites financeiros |
| Contratualizar prestadores       | Facilita especificar objeto, metas, indicadores, produção e mecanismos de pagamento                                    |
| Monitorar produção e acesso      | Possibilita comparar o planejado, o realizado, o aprovado e o pago                                                     |
| Apoiar auditoria                 | Torna verificável se o atendimento e seu registro obedeceram às regras vigentes                                        |

### Um cuidado essencial

A “carteira SIGTAP” não é automaticamente a “carteira real” de uma unidade. Uma unidade pode encontrar um procedimento na tabela, mas não estar apta a ofertá-lo ou faturá-lo se não tiver, por exemplo:

- Profissionais e equipamentos necessários.
- Serviço e classificação adequados no CNES.
- Habilitação ministerial aplicável.
- Pactuação/regulação e referência regional.
- Contrato ou programação compatíveis.
- Recursos orçamentários e financeiros.
- Capacidade de cumprir as regras assistenciais e documentais.

Em outras palavras: a SIGTAP diz que o procedimento **existe no vocabulário e nas regras nacionais**; não prova, sozinha, que um prestador pode executá-lo, que ele foi autorizado na rede, que há orçamento suficiente ou que haverá pagamento extra.

## SIGTAP e faturamento SUS

O faturamento é o processo pelo qual a produção assistencial é registrada, consistida, enviada, processada, aprovada e usada para controle, informação e efeitos financeiros. A SIGTAP é a referência central das regras de codificação nesse ciclo.

### Fluxo simplificado

1.  **O usuário recebe o atendimento** em uma unidade própria ou contratada pelo SUS.
2.  **O atendimento é documentado** no prontuário e nos sistemas assistenciais.
3.  **O procedimento é codificado** conforme a SIGTAP válida para a competência.
4.  **A produção é registrada** no instrumento adequado:

- **BPA**: registro de produção ambulatorial, individualizada ou consolidada, conforme a ação.
- **APAC**: autorização e registro de procedimentos ambulatoriais de maior complexidade ou continuidade, conforme regras específicas.
- **AIH**: autorização de internação hospitalar e base de processamento hospitalar no SIH/SUS.
- **RAAS**: registro das ações ambulatoriais de saúde, utilizado em determinados contextos e redes de cuidado.

5.  **O registro é processado** no SIA/SUS, para produção ambulatorial, ou no SIH/SUS, para produção hospitalar.
6.  **As críticas de consistência são aplicadas**, confrontando o registro com a SIGTAP, o CNES e as regras dos sistemas.
7.  **A produção aprovada** gera informação para gestão, controle, avaliação, auditoria, pagamento a prestadores conforme contrato e apuração financeira federal aplicável.

O SIA/SUS possui aplicativos de entrada como BPA e APAC, além de processamento e ferramentas associadas; a integração da codificação com a tabela unificada foi justamente um dos objetivos da implantação do SIGTAP.\[[w3.datasus.gov](http://w3.datasus.gov.br/sia/index.php?area=0408)\]\[[w3.datasus.gov](http://w3.datasus.gov.br/sia/index.php?area=03)\]

### O que a SIGTAP valida no faturamento

Um procedimento pode ser rejeitado, criticado ou glosado se houver incompatibilidade, por exemplo, entre:

- Procedimento e CID/diagnóstico exigido.
- Procedimento e idade ou sexo do usuário.
- Procedimento principal e secundário.
- Procedimento e instrumento de registro utilizado.
- Procedimento e serviço/classificação do CNES.
- Procedimento e habilitação do estabelecimento.
- Quantidade lançada e limites permitidos.
- Competência de atendimento e vigência do código.
- Regra de permanência, quando aplicável.
- Existência de autorização, como APAC ou AIH, quando exigida.

A consequência é que a produção pode não ser aprovada, pode ter valor reduzido, pode exigir correção ou pode permanecer como produção informada sem produzir o efeito financeiro esperado. É por isso que o faturamento não é uma atividade meramente administrativa: ele depende de qualidade clínica, documental, cadastral e informacional.

## Relação com financiamento e orçamento

A ligação entre SIGTAP, faturamento e recursos do SUS é forte, mas é fundamental distinguir quatro conceitos:

|                   |                                                                                     |
|-------------------|-------------------------------------------------------------------------------------|
| **Conceito**      | **Pergunta que responde**                                                           |
| SIGTAP            | “Como esse procedimento é identificado e sob quais regras ele pode ser registrado?” |
| Produção aprovada | “O que foi realizado e aceito após processamento?”                                  |
| Financiamento     | “De onde vêm os recursos e qual regra define sua transferência ou uso?”             |
| Orçamento         | “Quanto foi autorizado e alocado para gastar, em qual ação e período?”              |

### MAC: teto financeiro regular

O componente **MAC — Média e Alta Complexidade Ambulatorial e Hospitalar** — compreende recursos federais destinados ao custeio de ações e serviços especializados ambulatoriais e hospitalares. Ele inclui incentivos de custeio e é transferido de forma regular e automática aos fundos de saúde estaduais, distrital e municipais.\[[gov](https://www.gov.br/saude/pt-br/acesso-a-informacao/gestao-do-sus/programacao-regulacao-controle-e-financiamento-da-mac/financiamento-da-media-e-alta-complexidades-mac)\]

Em grande parte das situações, o gestor recebe um **limite financeiro MAC**, frequentemente chamado de teto MAC. A produção aprovada no SIA/SUS e SIH/SUS é decisiva para demonstrar o que foi realizado, apoiar o controle e orientar a gestão, mas não significa que todo aumento de produção resultará, automaticamente, em transferência federal adicional acima do teto existente.

Esse ponto explica uma confusão frequente:

Um procedimento pode possuir valor SIGTAP e ser corretamente aprovado, mas o gestor pode já estar operando dentro de um teto financeiro fixado. Nesse caso, a produção aprovada é essencial para demonstrar a entrega, avaliar contratos e programar recursos, mas pode não gerar aumento imediato do repasse federal MAC.

### FAEC: produção vinculada a ações estratégicas

O **FAEC — Fundo de Ações Estratégicas e Compensação** — financia procedimentos e políticas considerados estratégicos, além de poder cobrir novos procedimentos incorporados à Tabela SUS. Nesse componente, a apuração da produção registrada no SIA/SUS e SIH/SUS tem relação direta com os recursos transferidos após processamento.\[[gov](https://www.gov.br/saude/pt-br/acesso-a-informacao/gestao-do-sus/programacao-regulacao-controle-e-financiamento-da-mac/financiamento-da-media-e-alta-complexidades-mac)\]

Assim, a classificação de financiamento indicada para determinado procedimento pode ser crucial para o gestor, porque ajuda a distinguir, em linhas gerais, se ele está relacionado ao limite MAC, ao FAEC ou a outras regras específicas de custeio. Ainda assim, a análise precisa considerar a legislação vigente na competência, regras da política, habilitação, produção aprovada e processamento financeiro.

Há também situações em que recursos inicialmente financiados via FAEC podem, após análises e decisões normativas, migrar para o limite financeiro MAC com base na série histórica da produção aprovada nos sistemas SIA/SUS e SIH/SUS.\[[bvsms.saude.gov](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2017/prt3011_13_11_2017.html)\]\[[bvsms.saude.gov](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2017/prt3011_19_12_2017_rep.html)\]

### Transferência fundo a fundo

Os recursos federais de saúde são transferidos aos fundos estaduais, distrital e municipais na modalidade **fundo a fundo**, isto é, do Fundo Nacional de Saúde para os fundos de saúde dos entes federados, observando as normas dos blocos de financiamento e seus atos específicos.\[[bvsms.saude.gov](https://bvsms.saude.gov.br/bvs/saudelegis/gm/2017/prc0006_03_10_2017ARQUIVO.html)\]\[[datasus.saude.gov](https://datasus.saude.gov.br/informacoes-financeiras/)\]

A produção informada e aprovada alimenta o processo de monitoramento da execução da política e, em determinados componentes, a apuração financeira. Porém, o dinheiro normalmente não vai diretamente da União para cada procedimento individual realizado por um hospital. Em vez disso, há uma combinação de:

- Transferências federais fundo a fundo.
- Limites financeiros e incentivos.
- Contratualização entre gestor e prestador.
- Recursos próprios municipais e estaduais.
- Programação físico-financeira.
- Regulação do acesso e referências regionais.
- Produção processada e aprovada.
- Controle, auditoria e prestação de contas.

## Exemplo integrado

Imagine que uma secretaria municipal queira ampliar a oferta de um exame especializado:

1.  Primeiro, avalia a necessidade da população, a fila de espera, a rede regional e a viabilidade técnica.
2.  Depois, identifica na SIGTAP o código exato, a descrição, o instrumento de registro, as exigências de CNES, habilitação, compatibilidades e a forma de financiamento.
3.  Verifica se realizará o exame em unidade própria ou por prestador contratado.
4.  Programa uma meta física, como 500 exames mensais, e estima o impacto financeiro — sem confundir o valor SIGTAP com o custo efetivo do serviço ou com um repasse garantido.
5.  Adequa o CNES, a regulação, a agenda, o contrato e o orçamento.
6.  Registra a produção no sistema apropriado e dentro da competência correta.
7.  Após o processamento, acompanha quantidades apresentadas, rejeitadas e aprovadas, além dos valores correspondentes e do impacto no teto MAC ou no FAEC, conforme a regra aplicável.

Esse exemplo mostra por que a SIGTAP está no centro do ciclo de gestão: ela organiza o código e a regra do procedimento; os sistemas SIA/SIH transformam a assistência em produção aprovada; o financiamento e o orçamento definem a capacidade de sustentar essa oferta.

## Síntese prática

A SIGTAP é indispensável para a gestão do SUS porque permite que a assistência seja **padronizada, registrada, auditada, comparada e financiada** em escala nacional. Ela deve ser usada como fonte oficial para codificação e regras de produção, sempre na competência correspondente.

A relação correta é:

\text{Necessidade de saúde}

\rightarrow

\text{Carteira e planejamento}

\rightarrow

\text{CNES/habilitação/contrato}

\rightarrow

\text{SIGTAP}

\rightarrow

\text{Registro em SIA/SIH}

\rightarrow

\text{Produção aprovada}

\rightarrow

\text{Controle, pagamento e financiamento}

E o limite conceitual mais importante é:

\text{Valor SIGTAP} \neq \text{custo real do serviço} \neq \text{orçamento disponível} \neq \text{repasse adicional garantido}

A tabela é a referência técnico-operacional do procedimento; o financiamento depende de sua modalidade e das normas vigentes; e o orçamento depende da programação e disponibilidade de recursos dos entes gestores.

<div>

</div>
