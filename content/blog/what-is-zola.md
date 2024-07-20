+++
title = "O que é Zola"
date = 2021-10-03

[taxonomies]
tags = ["rust", "outros"]
+++

Lorem ipsum dolor sit amet, consectetur adipiscing elit. 

<!-- more -->

Nunc eu feugiat sapien. Aenean ligula nunc, laoreet id sem in, interdum bibendum felis. Donec vel dui neque. Praesent ac sem ut justo volutpat rutrum a imperdiet tellus. Nam lobortis massa non hendrerit hendrerit. Vivamus porttitor dignissim turpis, eget aliquam urna tincidunt non. Aliquam et fringilla turpis. Nullam eros est, eleifend in ornare sed, hendrerit eget est. Aliquam tellus felis, suscipit vitae ex vel, fringilla tempus massa. Nulla facilisi. Pellentesque lobortis consequat lectus. Maecenas ac libero elit.

# Título 1

## Título 2

### Título 3

#### Título 4

##### Título 5

###### Título 6

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Citação

> Esta é uma citação
> com várias linhas

## Tabelas

Tabelas não fazem parte da especificação principal do Markdown, mas o Zola as suporta nativamente.

   Nome | Idade
--------|------
    Bob | 27
  Alice | 23

### Markdown inline dentro de tabelas

| Inline&nbsp;&nbsp;&nbsp;     | Markdown&nbsp;&nbsp;&nbsp;  | Em&nbsp;&nbsp;&nbsp;                | Tabela      |
| ---------- | --------- | ----------------- | ---------- |
| *itálico*  | **negrito**  | ~~riscado~~&nbsp;&nbsp;&nbsp; | `código`     |

## Blocos de Código

#### Bloco de código com crases

```python
prices = {'apple': 0.40, 'banana': 0.50}
my_purchase = {
  'apple': 1,
  'banana': 6
}
grocery_bill = sum(prices[fruit] * my_purchase[fruit]
                   for fruit in my_purchase)
print('I owe the grocer $%.2f' % grocery_bill)
```

## Tipos de Listas

#### Lista Ordenada

1. Primeiro item
2. Segundo item
3. Terceiro item

#### Lista Não Ordenada

* Item da lista
* Outro item
* E mais um item

#### Lista Aninhada

* Item
    1. Primeiro Sub-item
    2. Segundo Sub-item

## Outros Elementos — abbr, sub, sup, kbd, mark

<abbr title="Graphics Interchange Format">GIF</abbr> é um formato de imagem bitmap.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Pressione <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> para encerrar a sessão.

<mark>Os skinks</mark> podem se esconder facilmente em seu habitat devido à sua coloração protetora (camuflagem).

