# Git Commit

## O que é o comando git commit?

O comando `git commit` é utilizado para registrar as alterações preparadas na área de staging. Cada commit representa um ponto no histórico do projeto, permitindo acompanhar a evolução do código e, se necessário, voltar para versões anteriores.

## Sintaxe

```bash
git commit -m "Mensagem do commit"
```

## Quando utilizar?

Depois de adicionar os arquivos com `git add`, utilize o `git commit` para salvar as alterações no histórico do repositório.

## Exemplo

```bash
git add .
git commit -m "Adiciona documentação sobre Git"
```

## Boas práticas

- Escreva mensagens curtas e objetivas.
- Descreva claramente o que foi alterado.
- Faça commits pequenos e frequentes.

Exemplos de boas mensagens:

```text
docs: adiciona documentação do Git
feat: adiciona página inicial
fix: corrige erro no README
```

## Resumo

O `git commit` registra as alterações no histórico do projeto, criando uma nova versão que poderá ser consultada ou recuperada futuramente.
