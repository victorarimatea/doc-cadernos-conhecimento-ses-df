# Backlog de Versões — doc-cadernos-conhecimento-ses-df

---

## v1.4 — 2026-10-26

**Tipo de alteração:** Atualização
**Autorizado por:** victorarimatea
**Instrumento de aprovação:** aprovação do caderno pelo mantenedor em sessão de trabalho (26/10/2026)
**Processo SEI:** não se aplica
**IAC gerado:** não se aplica
**Exposição de motivos:** a correção de vigência do caderno de RENASES (v1.1, feita em
24/10/2026 no chat do caderno CNES) foi aprovada: as normas de base estão nas
consolidações de 2017 e 2021.

### Alterações realizadas
- `cadernos/renases/` — caderno v1.1 aprovado; README e CHANGELOG
- `README.md`, `INDICE.md`, `cadernos/README.md` — situação do caderno de RENASES

---

## v1.3 — 2026-10-26

**Tipo de alteração:** Atualização
**Autorizado por:** victorarimatea
**Instrumento de aprovação:** aprovação do caderno pelo mantenedor em sessão de trabalho (26/10/2026)
**Processo SEI:** não se aplica
**IAC gerado:** não se aplica
**Exposição de motivos:** o caderno de CNES, que não existia até 22/10/2026, foi aprovado na
v1.0, depois de três rascunhos e da prévia da página no formato da ferramenta.

### Alterações realizadas
- `cadernos/cnes/` — caderno v1.0; README, CHANGELOG
- `README.md`, `INDICE.md`, `cadernos/README.md` — situação do caderno de CNES

---

## v1.2 — 2026-10-26

**Tipo de alteração:** Atualização
**Autorizado por:** victorarimatea
**Instrumento de aprovação:** decisão do mantenedor em sessão de trabalho (26/10/2026)
**Processo SEI:** não se aplica
**IAC gerado:** não se aplica
**Exposição de motivos:** na revisão do caderno de CNES, o mantenedor aprovou apresentar
a base normativa em dois blocos (vigentes por esfera; normas de origem em ordem
cronológica, com o problema que cada uma enfrentou), deixou a ordem hierárquica como
alternativa e não como regra, e liberou para teste o detalhe recolhível e as listas
por bloco geradas pela ferramenta.

### Alterações realizadas
- `MODELO-CADERNO.md` v1.1 → v1.2 — seções 4.5 (base normativa em dois blocos) e 4.6 (detalhe recolhível em teste); decisões de 26/10/2026 na seção 9
- `cadernos/_modelo/caderno.md` — seção 2 com os dois quadros
- `cadernos/cnes/` — caderno v0.3 (rascunho), README, CHANGELOG e proposta gráfica
- `README.md`, `INDICE.md` — versão do modelo e do caderno de CNES

---

## v1.1 — 2026-10-23

**Tipo de alteração:** Atualização
**Autorizado por:** victorarimatea
**Instrumento de aprovação:** decisão do mantenedor em sessão de trabalho (23/10/2026)
**Processo SEI:** não se aplica
**IAC gerado:** não se aplica
**Exposição de motivos:** em 22/10/2026, outra sessão de trabalho (caderno de CNES)
já havia organizado os cadernos na pasta `cadernos/` do repositório privado da
ferramenta (`carteira-servicos-ses-df`), com cópia automática para o Drive. Com a
criação deste repositório, os cadernos passaram a ter dois lugares oficiais. O
mantenedor decidiu que este repositório público é o lugar único: os cinco cadernos
vieram para cá, o repositório da ferramenta passa a apontar para este e o Drive fica
só com um índice de links.

### Alterações realizadas
- `cadernos/` — trazidas do repositório da ferramenta as pastas `carteira-servicos/`, `cnes/`, `rede-hospitalar/`, `sigtap/` e `_modelo/`, mais `README.md`; cada caderno com `README.md`, `caderno.md`, `proposta-grafica.md` e `CHANGELOG.md`
- `cadernos/renases/` — reunidos os arquivos das duas sessões: README no formato de ficha (com decisões, pendências e conferências), `CHANGELOG.md`, `caderno.md` (v0.2, sem o parágrafo de histórico, que está no CHANGELOG), `proposta-grafica.md` e `dossie-de-estudo.md`
- `cadernos/_modelo/` — esqueleto do `caderno.md` atualizado para a ordem de seções do modelo v1.0; README do modelo com decisões e conferências estruturais
- Cópia automática diária para o Drive (criada em 22/10/2026 no repositório da ferramenta) desativada: com o repositório público, o Drive passa a ter só o índice "00-indice-cadernos" com os links; o procedimento `espelho-drive.md` não foi mantido e os arquivos copiados foram para a pasta de substituídos do Drive
- `cadernos/carteira-servicos/caderno.md` — fontes internas do projeto (FON-12) descritas de forma genérica, sem nomes de arquivos de trabalho nem número de processo (repositório público)
- `MODELO-CADERNO.md` v1.0 → v1.1 — seção 7 ajustada à organização adotada
- `README.md`, `INDICE.md` — estrutura e índice dos cinco cadernos

---

## v1.0 — 2026-10-23

**Tipo de alteração:** Criação
**Autorizado por:** victorarimatea
**Instrumento de aprovação:** aprovação do mantenedor em sessão de trabalho (22–23/10/2026)
**Processo SEI:** não se aplica
**IAC gerado:** não se aplica
**Exposição de motivos:** o projeto Carteira de Serviços da CICS/SES-DF
mantém na ferramenta de consulta um grupo de capítulos de conhecimento
(SIGTAP, CNES, Carteira de serviços, Rede hospitalar) cujo conteúdo vivia
dentro do código, sem versão própria nem histórico. Ao preparar o caderno
sobre a RENASES, foi aprovado um modelo de caderno padronizado (v1.0) que
separa norma, prática e interpretação, liga cadernos, normas e conceitos como
uma wiki e exige conferência a cada mudança estrutural da ferramenta. Este
repositório passa a ser o lugar canônico dos cadernos, do modelo e do
vocabulário controlado, em formato público, consumindo as normas transcritas
do repositório D01 sem cópia.

### Alterações realizadas
- `README.md`, `INDICE.md`, `backlog-versoes.md` — estrutura padrão do ecossistema
- `MODELO-CADERNO.md` — modelo de caderno de conhecimento v1.0, aprovado em 22/10/2026
- `vocabulario-controlado.md` — estrutura e primeiros conceitos (rascunho)
- `cadernos/renases/` — caderno RENASES v0.2 (rascunho), dossiê de estudo de 22/10/2026, README com o registro da evolução e proposta gráfica

### Pendências
- Reescrever o caderno RENASES no modelo v1.0 (v0.3)
- Migrar os quatro capítulos já publicados na ferramenta para este repositório, no modelo v1.0
- Validar o vocabulário controlado
