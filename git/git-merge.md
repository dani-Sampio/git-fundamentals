# Git Merge

## O que é o comando git merge?

O comando git merge é utilizado para unir as alterações de uma branch com outra. Ele é muito utilizado quando uma funcionalidade foi concluída e precisa ser incorporada à branch principal.

## Sintaxe

bash
git merge nome-da-branch


## Quando utilizar?

Utilize o git merge quando desejar combinar o trabalho realizado em uma branch com outra branch.

## Exemplo

Suponha que você criou uma branch chamada feature-login e terminou o desenvolvimento.

Primeiro, acesse a branch principal:

bash
git checkout main


Depois, execute:

bash
git merge feature-login


Assim, todas as alterações da branch feature-login serão adicionadas à branch main.

## Vantagens

- Une alterações de diferentes branches.
- Facilita o trabalho em equipe.
- Mantém o histórico do projeto organizado.

## Resumo

O comando git merge combina o conteúdo de uma branch com outra, permitindo integrar novas funcionalidades ao projeto principal.
