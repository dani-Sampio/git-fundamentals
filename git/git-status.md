# Git Status

## O que é o comando git status?

O comando `git status` mostra o estado atual do repositório. Ele informa quais arquivos foram modificados, quais estão prontos para serem salvos (staging) e quais ainda não estão sendo rastreados pelo Git.

## Sintaxe

```bash
git status
```

## Quando utilizar?

Utilize esse comando sempre que quiser verificar a situação do seu projeto antes de adicionar arquivos ou criar um commit.

## Exemplo

Após editar um arquivo, execute:

```bash
git status
```

Saída esperada:

```text
Changes not staged for commit:
modified: README.md
```

## Resumo

O `git status` é um dos comandos mais importantes do Git, pois permite acompanhar todas as alterações realizadas no projeto antes de salvá-las no histórico.
