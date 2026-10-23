# Cadernos de conhecimento

Pasta única dos cadernos de conhecimento do projeto Carteira de Serviços da SES-DF. Cada caderno é a **fonte** de um capítulo da ferramenta de consulta (grupo "Conhecimento" ou "Carteira SES-DF").

Criada em 22/10/2026 no repositório da ferramenta e trazida para este repositório público em 23/10/2026. Como escrever um caderno está no [modelo de caderno](../MODELO-CADERNO.md); os conceitos ficam no [vocabulário controlado](../vocabulario-controlado.md).

## Por que esta pasta existe

Até 22/10/2026 os cadernos eram Google Docs soltos na pasta de conhecimento do Drive, sem README nem histórico, e o texto dos capítulos era copiado para dentro da ferramenta à mão. Com isso, o capítulo de CNES chegou a existir na ferramenta sem nenhum caderno de origem, e os capítulos de SIGTAP, Carteira e Rede passaram a ter conteúdo que os cadernos não tinham.

## Regras

1. **Um lugar só.** O texto de cada caderno vive só aqui. A pasta "06-cadernos" do Drive do projeto é um espelho somente leitura, atualizado automaticamente a partir deste repositório. Não edite no Drive: a próxima atualização sobrescreve.
2. **Repositório público.** O texto não contém dado interno não publicado, número preliminar da rede, deliberação em curso nem dado pessoal. Dado da rede aparece só dentro da ferramenta (privada), no bloco "Nesta ferramenta".
3. **Uma subpasta por caderno**, com nome curto, minúsculo, sem acento (`cnes`, `sigtap`, `carteira-servicos`, `rede-hospitalar`, `renases`).
4. **Os mesmos arquivos em toda subpasta:**

   | Arquivo | Conteúdo |
   |---|---|
   | `README.md` | Ficha do caderno: finalidade, público, capítulo que alimenta, versão vigente, situação, normas usadas, decisões, pendências, conferências estruturais e origem |
   | `caderno.md` | O texto do caderno, com cabeçalho de versão |
   | `proposta-grafica.md` | Como o capítulo aparece na ferramenta: ordem das seções, quadros, destaques, infográficos e blocos com dados vivos |
   | `CHANGELOG.md` | Registro de alterações, da mais recente para a mais antiga |

   Podem existir também o `dossie-de-estudo.md` (pesquisa aprofundada) e arquivos de trabalho de uma etapa, com o nome dizendo o que são e a data. Arquivos de trabalho não são mantidos depois: valem como registro.
5. **Nome de arquivo fixo, versão no conteúdo.** O nome não muda a cada versão. A versão fica no cabeçalho do `caderno.md`, no `CHANGELOG.md` e no histórico do GitHub. Cada versão aprovada recebe uma marca (tag) `cad-<caderno>-vX.Y`, por exemplo `cad-cnes-v1.0`.
6. **Versões.** `v0.x` é rascunho em discussão; `v1.0` é a primeira aprovada pelo Victor; correção pequena sobe o segundo número (`v1.1`); mudança de estrutura sobe o primeiro.
7. **Normas não são copiadas.** O caderno cita a norma pelo nome e aponta para a transcrição no [repositório de governança documental](https://github.com/victorarimatea/doc-governanca-ses-df), onde também está o nome-base do PDF original guardado na pasta compartilhada de normas do Drive.
8. **Procedência sempre.** Toda afirmação normativa tem fonte primária e data de conferência. O que não foi verificado fica marcado como pendente, nunca reconstruído de memória.
9. **Toda alteração entra no `CHANGELOG.md`** no mesmo commit que altera o caderno, com data, versão, o que mudou e de onde veio (chat, decisão, fonte).
10. **Ligação com a ferramenta.** Cada capítulo da ferramenta deve indicar seu caderno-fonte e versão. Enquanto a geração da ferramenta não lê esta pasta diretamente (pendência registrada na fila da ferramenta), o texto do capítulo ainda é uma cópia dentro do código da ferramenta; o `README.md` de cada caderno diz se capítulo e caderno estão alinhados.
11. **Conferência a cada mudança estrutural da ferramenta** (seção 6.1 do modelo), com o resultado no `README.md` de cada caderno afetado.

## Cadernos

| Caderno | Capítulo na ferramenta | Versão vigente | Situação |
|---|---|---|---|
| [CNES](cnes/README.md) | Conhecimento · CNES | — | Sem caderno até 22/10/2026; em construção (linha de base e verificação de fontes registradas) |
| [SIGTAP](sigtap/README.md) | Conhecimento · SIGTAP | v1.0 | Migrado; capítulo tem conteúdo que o caderno não tem |
| [Carteira de serviços](carteira-servicos/README.md) | Conhecimento · Carteira e Carta de Serviços | v1.2 | Migrado; faltam Cartas de Serviços e Decreto DF 36.419/2015 |
| [Rede hospitalar do DF](rede-hospitalar/README.md) | Conhecimento · Rede hospitalar do DF | v1.0 | Migrado; diverge do capítulo sobre URD |
| [RENASES](renases/README.md) | ainda não existe | v0.2 | Rascunho; reescrita no modelo v1.0 (v0.3) em andamento |

Todos os cadernos acima são anteriores ao modelo v1.0 e serão adaptados a ele, um por vez.

Fora desta rodada, a migrar depois para o mesmo padrão: o caderno de Iniciativas e Programas, o de Ações Civis Públicas e demanda reprimida e o texto do capítulo "O projeto Carteira de Serviços da SES-DF", que hoje não tem caderno identificado.

## Como criar um caderno novo

Copie a pasta [`_modelo/`](_modelo/), renomeie para o nome curto do caderno, preencha o `README.md`, abra o `CHANGELOG.md` com a entrada `v0.1`, escreva o `caderno.md` seguindo o [modelo de caderno](../MODELO-CADERNO.md) e acrescente a linha na tabela acima e no [README do repositório](../README.md).

## Espelho no Drive

Pasta "06-cadernos" dentro de "PROJETO - CARTEIRA DE SERVIÇOS" no Drive, com uma subpasta por caderno e os mesmos arquivos. Atualizada por uma tarefa agendada que compara o último commit desta pasta com o que já está no Drive e copia só o que mudou. Cada arquivo espelhado traz no topo o aviso de que é cópia e o commit de origem. Procedimento em [`espelho-drive.md`](espelho-drive.md).
