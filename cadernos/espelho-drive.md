# Espelho dos cadernos no Drive — procedimento

Procedimento seguido pela tarefa agendada "Espelho dos cadernos no Drive". A tarefa só diz
"siga este arquivo"; para mudar o espelho, mude este arquivo, não a tarefa.

## Origem e destino

- **Origem (lugar único):** repositório público `victorarimatea/doc-cadernos-conhecimento-ses-df`,
  ramo `main`, pasta `cadernos/` (desde 23/10/2026; antes era a pasta `cadernos/` do
  repositório privado `victorarimatea/carteira-servicos-ses-df`).
- **Destino (espelho somente leitura):** Drive, pasta "PROJETO - CARTEIRA DE SERVIÇOS"
  (id `1lZNRTVZYa_z0trO1vLtOzPnFVr-NxWjv`) > `06-cadernos`, com uma subpasta por pasta de
  `cadernos/` e o mesmo nome. Os ids ficam no arquivo de estado (abaixo).
- **Fora do espelho:** a pasta `_modelo/` e este próprio arquivo ficam só no GitHub.

## Arquivo de estado

Na raiz de `06-cadernos` há um arquivo de texto `00-estado-do-espelho.txt` com:

```
origem: <dono/repositório de origem>
commit: <sha do último commit espelhado>
data: <AAAA-MM-DD HH:MM, horário de Brasília>
pastas:
<subpasta> <id da pasta no Drive>
arquivos:
<caminho em cadernos/> <sha do blob no GitHub> <id do arquivo no Drive>
```

## Passos

1. Ler o arquivo de estado no Drive.
2. Listar a pasta `cadernos/` no GitHub, recursivamente, com o SHA de cada arquivo
   (ferramenta do GitHub, leitura). Se o repositório responder "não encontrado", anexá-lo à
   sessão com acesso de leitura e tentar de novo.
3. Se a linha `origem:` do estado não existir ou for diferente da origem atual, tratar
   todos os arquivos como alterados (cópia completa, para que todos os cabeçalhos apontem
   para a origem atual). Caso contrário, comparar com o estado. Se nenhum SHA mudou e não há arquivo novo ou removido, terminar
   sem mensagem.
4. Para cada pasta nova em `cadernos/` (fora `_modelo/`): criar a subpasta em `06-cadernos`.
5. Para cada arquivo novo ou alterado:
   - baixar o conteúdo do GitHub para um arquivo local e calcular o SHA-256;
   - montar o conteúdo espelhado = cabeçalho abaixo + conteúdo original;
   - se havia versão anterior no Drive, mandá-la para a lixeira;
   - criar o arquivo na subpasta, com o mesmo nome, tipo `text/markdown`, sem conversão
     para Google Docs;
   - baixar o arquivo criado e conferir que o conteúdo depois do cabeçalho tem o mesmo
     SHA-256 do original. Se não tiver, mandar para a lixeira, tentar uma vez de novo e, se
     falhar outra vez, registrar no aviso final e não atualizar o estado desse arquivo.
6. Para cada arquivo removido do GitHub: mandar a cópia do Drive para a lixeira.
7. Regravar o arquivo de estado (lixeira na versão anterior, criação da nova).
8. Enviar um aviso curto ao Victor só se algo mudou ou falhou: quais cadernos foram
   atualizados e o commit de origem.

## Cabeçalho de cada arquivo espelhado

```
<!-- ESPELHO SOMENTE LEITURA. Fonte: github.com/victorarimatea/doc-cadernos-conhecimento-ses-df/blob/main/cadernos/<caminho>
     Commit <sha curto> · copiado em <AAAA-MM-DD>. Não edite aqui: a próxima atualização sobrescreve. -->

```

## Regras

- Nunca editar arquivo no GitHub a partir desta tarefa.
- Nunca apagar definitivamente no Drive: só lixeira.
- Não espelhar nada fora de `cadernos/`.
