# Modelo de Caderno de Conhecimento — v1.0

Projeto Carteira de Serviços da SES-DF · Ferramenta HTML, grupo Conhecimento · **v1.0 — 2026-10-22** · aprovado por Victor em 22/10/2026

Este documento fixa como todo caderno de conhecimento da ferramenta é escrito, apresentado, versionado e ligado aos demais. Parte do padrão que já funciona nos cinco capítulos atuais (SIGTAP, Carteira de serviços, CNES, Rede hospitalar e Carteira SES-DF), corrige o que falta e prepara a evolução para uma wiki.

---

## 1. Diagnóstico do padrão atual

Lido diretamente da versão publicada da ferramenta (0.3.10).

### 1.1 O que já existe e funciona

| Elemento | Como aparece hoje |
|---|---|
| Cabeçalho | Rótulo "Conhecimento · nome", título, resumo de uma frase, faixa "Base de conhecimento · revisado em" |
| Corpo | De 5 a 11 seções curtas (cerca de 600 a 2.300 caracteres cada), com índice lateral fixo |
| Destaques | Três tipos, sempre abertos por uma frase-título em negrito: **informativo** (ideia-chave), **atenção** (cuidado de leitura ou limitação) e **alerta** ("não confundir", "limite de uso") |
| Tabelas | Comparações e listas curtas ("Cinco coisas que não se confundem", "pergunta que responde") |
| Dados da ferramenta | Blocos inseridos no fim de uma seção, com números e links internos (ex.: "Como esta ferramenta usa o CNES") |
| Exemplo integrado | Um caso real percorrendo todos os planos (ex.: colecistectomia videolaparoscópica) |
| Rodapé | Lista de fontes com link e atalhos para os outros capítulos |

Seções que se repetem naturalmente entre capítulos: *o que é · origem e base legal · como se lê · atualização · por que importa para a carteira · limites e erros comuns · como a ferramenta usa · exemplo integrado*. O modelo abaixo transforma essa repetição espontânea em regra.

### 1.2 O que falta

1. **Norma, prática e interpretação não se distinguem na tela.** Uma frase da norma e uma leitura do projeto têm o mesmo peso visual.
2. **Uma data de revisão para todos os capítulos.** Não há versão nem histórico por caderno.
3. **Fontes no fim, desligadas das afirmações.** Não dá para saber qual fonte sustenta qual frase.
4. **Nenhuma ligação com as normas transcritas**, nem entre conceitos de capítulos diferentes.
5. **Nenhum lugar para aprofundamento.** Ou o conteúdo entra no capítulo, ou se perde.
6. **Força jurídica não sinalizada.** Precedente vinculante, enunciado orientativo e decisão isolada apareceriam iguais.
7. **O conteúdo vive dentro do código da ferramenta**, e não num arquivo de texto versionado que alimenta a ferramenta.

---

## 2. Princípios do modelo

1. **Caderno ensina; não emite parecer.** Explica o que é, como funciona, por que importa e como não errar. Teses, debates em aberto e recomendações de desenho institucional ficam fora.
2. **O que corrige um entendimento errado é obrigatório.** Se a omissão deixaria o gestor com uma leitura falsa (ex.: "a lista está parada desde 2012"; "não estar na lista não é defesa em ação sobre procedimento"), entra no corpo, mesmo que venha de pesquisa.
3. **Toda afirmação tem procedência visível.** Norma, dado, literatura ou leitura do projeto, cada uma com marca própria.
4. **Um conteúdo, um lugar.** Norma é consumida da transcrição; dado, da base; conceito, do verbete. O caderno aponta, não copia.
5. **Estável e curto.** Seções curtas, estrutura fixa, linguagem direta; o que muda rápido (números de conjuntura, processos em curso) não entra no corpo.

---

## 3. Critério de admissão do conteúdo

Cada achado passa por três perguntas, nesta ordem:

| Pergunta | Se sim | Se não |
|---|---|---|
| É fato documentado, com fonte verificável? | segue | vai para o dossiê de estudo, marcado como interpretação, ou sai |
| Tem consequência prática para o gestor hospitalar? | segue | vai para o dossiê |
| É entendimento consolidado (norma, precedente vinculante, consenso técnico)? | **corpo do caderno** | **destaque "Leitura do projeto"** (se for nossa interpretação com base explícita) ou dossiê (se for debate) |

E quatro destinos para o que não é do caderno:

| Destino | O que recebe |
|---|---|
| **Dossiê de estudo** | Pesquisa completa: história, debate acadêmico, comparações internacionais, dados de conjuntura com data, lacunas |
| **Documentação do projeto** | Recomendações de desenho para a própria Carteira (governança, arquitetura, decisões) |
| **Outro caderno** | Tema próprio que merece caderno (ex.: judicialização e regulação, com validação jurídica) |
| **Fora** | Autopromoção, opinião sem base, número sem fonte confiável |

---

## 4. Anatomia do caderno

### 4.1 Cabeçalho (obrigatório)

- Rótulo "Conhecimento · {nome curto}"
- Título: "{Nome}: {o que é, em poucas palavras}"
- Resumo: uma frase que diz o que o caderno responde
- **Faixa de procedência** (substitui a atual): versão do caderno · data da última revisão · situação de verificação (*conferido em fonte primária* / *com pendências*, com link para elas) · aviso fixo "Material de estudo. Não substitui a publicação oficial das normas citadas."

### 4.2 Seções, em ordem fixa

| # | Seção | Obrigatória? | O que contém | Tamanho de referência |
|---|---|---|---|---|
| 1 | **O que é** | sim | Definição em linguagem simples; para que serve; o que não é | até 1.200 caracteres |
| 2 | **Origem e base normativa** | sim | Normas que criam e regem, com link para cada norma transcrita e o dispositivo exato; situação de vigência | tabela curta |
| 3 | **Como funciona** (ou "Como se lê") | sim | Estrutura, partes, códigos, fluxo | até 1.800 caracteres + tabela |
| 4 | **Situação atual e atualização** | sim | Quem atualiza, com que periodicidade, quando foi a última mudança, o que está pendente | até 1.000 caracteres |
| 5 | **Por que importa para o gestor hospitalar** | sim | Consequências práticas na rotina da unidade e na Carteira | até 1.500 caracteres |
| 6 | **Não confundir** | sim | Tabela "instrumento × pergunta que responde × erro comum" | tabela |
| 7 | **Cuidados e limites** | sim | Leituras erradas frequentes e limites dos dados | até 1.200 caracteres |
| 8 | **Exemplo integrado** | sim | Um caso real da rede percorrendo todos os instrumentos | até 1.500 caracteres |
| 9 | **Nesta ferramenta** | quando houver dado | Bloco gerado pela própria ferramenta: números, links para as páginas de dados | gerado |
| 10 | **Para aprofundar** | opcional | Link para o dossiê de estudo, cadernos relacionados e fontes externas de autoridade (ex.: Wiki SIGTAP) | lista |
| — | **Conceitos neste caderno** | gerado | Lista dos conceitos do vocabulário controlado citados, cada um com link para o verbete | gerado |
| — | **Fontes** | sim | Lista final, com o tipo de cada fonte (norma, dado oficial, literatura, decisão judicial, documento interno) | lista |
| — | **Histórico de versões** | sim | Versão, data e o que mudou | rodapé recolhido |

Regras: no máximo 11 seções; nenhuma seção acima de cerca de 2.000 caracteres sem tabela ou destaque; um caderno pode desdobrar a seção 3 em duas, mas não mudar a ordem.

### 4.3 Destaques (seis tipos, regras fixas)

Todos mantêm a convenção atual: frase-título em negrito + uma ou duas frases.

| Tipo | Cor | Pode conter | Não pode conter | Limite |
|---|---|---|---|---|
| **Ideia-chave** | azul (info atual) | Síntese de fato documentado | Opinião | livre |
| **Atenção** | âmbar (warn atual) | Cuidado de leitura, limitação, vigência | Recomendação de política | livre |
| **Não confundir** | rosa (alert atual) | Distinção conceitual que evita erro | — | livre |
| **Na ferramenta** | neutro com ícone da ferramenta (novo) | Como a ferramenta usa ou exibe o dado | Conceito geral | 1 por seção |
| **Leitura do projeto** | borda tracejada + rótulo fixo "Interpretação do projeto, não norma" (novo) | Interpretação nossa, com a base explícita | Tese sem base; autopromoção | **até 2 por caderno** |
| **Linha do tempo** | componente (novo) | Datas e marcos com fonte | Projeções | 1 por caderno |

Conteúdo jurídico leva, além do destaque, o rótulo de força: **vinculante** (súmula vinculante, tese de repercussão geral ou repetitivo), **orientativo** (enunciado, nota técnica) ou **decisão isolada**.

### 4.3.1 Regra para conteúdo de natureza jurídica

| Tipo | Exemplo | Regra |
|---|---|---|
| **Informação jurídica** — o que diz uma norma ou um precedente | "As teses do STF de 2024 valem só para medicamentos" | Entra, com citação exata (tribunal, número, data) e rótulo de força |
| **Orientação jurídica** — o que o gestor deve fazer num caso | "Diante de ação judicial, demonstre a fila regulada e o prazo" | **Só entra se referenciar a orientação jurídica institucional que a sustenta** (parecer da assessoria jurídica da SES-DF, da PGDF ou norma expressa). Sem essa referência localizada, **não entra** enquanto a validação não existir; fica registrada como pendência no README do caderno |

### 4.4 Procedência dentro do texto

- Citação de norma vira link para a norma reconstruída na ferramenta, no dispositivo: "Decreto 7.508/2011, art. 22, parágrafo único".
- Dado da ferramenta vira link para a página do dado.
- Literatura e decisões: citação curta (autor e ano, ou tribunal e número), com a referência completa em Fontes.
- Nenhum número sem data e fonte.

---

## 5. Os quatro tipos de página da wiki

| Tipo | O que é | Quem é a fonte | Liga para |
|---|---|---|---|
| **Caderno** | Material didático padronizado sobre um tema | Arquivo do caderno (seção 7) | normas, conceitos, dossiê, dados |
| **Norma** | Texto integral reconstruído, com âncora por artigo, vigência e link para o PDF original e a fonte oficial | Transcrição no repositório de governança documental | cadernos que a citam (lista gerada) |
| **Conceito** | Verbete curto: definição em 2 ou 3 linhas, sinônimos, termos que não se confundem, caderno principal, normas | Vocabulário controlado (um único arquivo) | cadernos e normas onde aparece (gerado) |
| **Dossiê de estudo** | Pesquisa aprofundada, com fatos, debate, comparações e lacunas | Relatório de pesquisa | caderno de origem |

Os links entre conceitos são criados automaticamente na geração da ferramenta a partir do vocabulário controlado: no máximo um link por conceito por seção, e apenas o sentido registrado (ex.: "habilitação" do estabelecimento não liga para habilitação profissional).

---

## 6. Governança e versionamento

- **Versão por caderno** (0.x rascunho; 1.0 aprovado; 1.1 ajuste; 2.0 reestruturação), com data e responsável.
- **Aprovação:** Victor aprova cada versão maior. Orientação de natureza jurídica segue a regra 4.3.1.
- **Gatilhos de revisão do conteúdo:** nova norma ou alteração da norma-base; mudança relevante na SIGTAP ou no CNES; lacuna do dossiê conferida; erro reportado por usuário (canal de sugestões da ferramenta).
- **Registro:** cada versão anotada no histórico do próprio caderno e no README da pasta do caderno.

### 6.1 Conferência dos cadernos a cada mudança estrutural da ferramenta

**Quando:** toda versão da ferramenta que altere a **estrutura** — páginas, rotas e endereços internos, menu e navegação, nomes de campos ou de planos exibidos, componentes e tipos de destaque, tipos de página da wiki. **Fica dispensada** a versão que só atualiza bases de dados e informações.

**Como (em duas camadas):**
1. **Automática, a cada geração da ferramenta** (vale também para atualização de bases): verificação de que todo link interno citado num caderno existe; todo conceito do vocabulário resolve para um verbete; toda âncora de norma (artigo, parágrafo, inciso) existe na transcrição vigente; toda norma citada tem versão registrada. Falha bloqueia a publicação ou gera relatório de pendências.
2. **Humana, só nas mudanças estruturais:** checklist curto — o caminho de leitura descrito no caderno ainda corresponde à tela? os nomes dos planos e campos citados mudaram? algum bloco "Nesta ferramenta" ficou sem dado? o exemplo integrado continua navegável? Resultado registrado no README de cada caderno afetado.

**Regra que evita conferência desnecessária:** caderno **não escreve números da ferramenta no texto**. Número que depende de base vem do bloco "Nesta ferramenta", gerado; número estático de fonte fixa (ex.: contagem da lista RENASES de 2012) entra com fonte e data.

---

## 7. Onde os arquivos ficam (atende à regra da pasta de Cadernos)

```
doc-cadernos-conhecimento-ses-df/          (repositório público no GitHub)
├── README.md                              ← apresentação e índice dos cadernos com situação
├── INDICE.md                              ← mapa de todos os arquivos
├── backlog-versoes.md                     ← histórico do repositório
├── MODELO-CADERNO.md                      ← este modelo
├── vocabulario-controlado.md              ← conceitos (fonte única dos verbetes e dos links automáticos)
└── cadernos/
    └── renases/
        ├── README.md                      ← proposta, situação, decisões e registro de todas as evoluções
        ├── caderno.md                     ← o conteúdo, em Markdown com cabeçalho estruturado
        ├── proposta-grafica.md            ← componentes usados e particularidades visuais
        └── dossie-de-estudo.md            ← pesquisa aprofundada
```

- **O GitHub é o lugar canônico** (repositório público `doc-cadernos-conhecimento-ses-df`, decisão de 22/10/2026), seguindo a nomenclatura do ecossistema: documentos com prefixo `doc-`; o vocabulário controlado pode evoluir para uma matriz própria (`mat-`) quando servir a mais de um projeto. As normas continuam vindo do repositório de governança documental, sem cópia.
- **No Drive do projeto**, a pasta de Cadernos espelha a mesma estrutura de pastas e traz, em cada uma, um índice que aponta para os arquivos no GitHub — sem segunda cópia do texto, para não divergir.
- **Consequência de ser público:** o texto do caderno não contém dado interno não publicado, número preliminar da rede, deliberação em curso nem dado pessoal. Tudo o que é dado da rede aparece só no bloco "Nesta ferramenta", gerado dentro da ferramenta (que segue privada), e nunca no arquivo do caderno.
- **Formato:** Markdown com cabeçalho de dados (id, nome curto, título, resumo, versão, revisão, situação) e destaques escritos na sintaxe de alertas do GitHub, que aparece formatada no próprio GitHub e é convertida pela ferramenta:

| Destaque | Sintaxe no arquivo |
|---|---|
| Ideia-chave | `> [!NOTE]` |
| Atenção | `> [!WARNING]` |
| Não confundir | `> [!CAUTION]` |
| Na ferramenta | `> [!TIP]` |
| Leitura do projeto | `> [!IMPORTANT]` |

- **Geração:** a ferramenta lê esses arquivos ao gerar cada versão (em vez de o conteúdo morar dentro do código), o que elimina a segunda cópia.

---

## 8. Aplicação ao caderno RENASES (esboço da v0.3)

| # | Seção | Conteúdo principal | Destaques |
|---|---|---|---|
| 1 | O que é | Lista oficial do que o SUS oferece e por qual porta; moldura, não lista de procedimentos | Ideia-chave: "Moldura, não conteúdo — o conteúdo está na SIGTAP e no CNES" |
| 2 | Origem e base normativa | Decreto 7.508 (arts. 21–24 e 43), Resolução CIT 2/2012, Portaria 841/2012 — com links para as normas | Atenção: pendência sobre a Portaria de Consolidação nº 1/2017 |
| 3 | Como funciona | Cinco componentes; seis critérios de acesso, com o que cada um pede do hospital e a contagem na atenção hospitalar | Ideia-chave: na atenção hospitalar, 34 de 38 itens passam pela regulação |
| 4 | Situação atual e atualização | Nasceu como fotografia do que existia; revisão bienal prevista e nunca publicada; perdeu o contrato que a operaria; políticas atuais não a citam | Linha do tempo 2011–2023 |
| 5 | Por que importa para o gestor | A carteira hospitalar como relação complementar operacional; forma de acesso como campo da carteira; coerência com habilitação | Leitura do projeto: "A carteira desce da moldura nacional até o procedimento e a porta de cada hospital" |
| 6 | Não confundir | RENASES × RENAME × SIGTAP × CNES × Carteira × Carta de Serviços | — |
| 7 | Cuidados e limites | Constar na lista não obriga cada hospital; nas ações sobre procedimentos, a lista sustenta o pedido do usuário e não a defesa; sem de-para oficial com a SIGTAP; a lista não define financiamento | Atenção (vinculante): teses do STF de 2024 valem só para medicamentos; para procedimentos, vale a responsabilidade solidária |
| 8 | Exemplo integrado | Cirurgia bariátrica: RENASES (critérios 2, 3, 4 e 5) → CNES → SIGTAP → regulação → Carteira | — |
| 9 | Nesta ferramenta | Lista navegável das 201 ações e serviços com filtro por critério (quando implementada) | Na ferramenta |
| 10 | Para aprofundar | Dossiê de estudo RENASES; Wiki SIGTAP; cadernos SIGTAP, CNES e Carteira | — |

**Vai para o dossiê:** críticas de sentido oposto (restritiva × vaga); racionamento implícito; comparação com Chile, Colômbia e Espanha; o que os órgãos de controle cobram e os números de espera no DF; a ambivalência "escudo ou gatilho" de 2012.
**Vai para a documentação do projeto:** lição de governança (dono, rito, gatilho, contrato); três granularidades da carteira; precedente de Pernambuco.
**Possível caderno próprio, com validação jurídica:** judicialização e regulação (o que o juiz pergunta, enunciados, prazos de referência).
**Fora:** "pioneirismo" e expressões de autopromoção.

---

## 9. Decisões aprovadas (22/10/2026)

1. Destaque **"Leitura do projeto"** aceito, com limite de dois por caderno e rótulo fixo.
2. Destaques novos **"Na ferramenta"** e **"Linha do tempo"** aprovados.
3. Repositórios **públicos** por enquanto.
4. Conteúdo de natureza jurídica: orientação só entra referenciada na orientação jurídica institucional que a sustenta; sem ela, não entra (regra 4.3.1).
5. Ordem e obrigatoriedade das seções aprovadas, com a **conferência dos cadernos a cada mudança estrutural da ferramenta** (seção 6.1).

**Próximos passos:** (a) gravar o modelo no README da pasta de Cadernos (Drive e GitHub); (b) reescrever o caderno RENASES na v0.3; (c) adaptar os quatro capítulos existentes ao modelo, um por vez; (d) implementar na ferramenta a leitura dos cadernos a partir dos arquivos e a verificação automática de referências — os dois últimos registrados na fila de pendências da ferramenta.

## Histórico

| Versão | Data | Alteração |
|---|---|---|
| v1.0 | 2026-10-22 | Aprovação com as cinco decisões; inclusão da regra jurídica (4.3.1), da conferência a cada mudança estrutural (6.1) e da consequência de repositório público |
| v0.1 | 2026-10-22 | Proposta a partir do padrão dos cinco capítulos da versão 0.3.10 da ferramenta |
