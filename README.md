Revisão Markdown
================

> Autor: Matheus  
> Data: Nov 2021

--------------------

Sumário
-------

1. [Título](https://github.com/mwmachado/gama#t%C3%ADtulo)
1. [Formatação](https://github.com/mwmachado/gama#formata%C3%A7%C3%A3o)
1. [Quebra de Linha](https://github.com/mwmachado/gama#quebra-de-linha)
1. [Quebra de Linha](#quebra-de-linha)
1. [Citação](https://github.com/mwmachado/gama#cita%C3%A7%C3%A3o)
1. [Código](https://github.com/mwmachado/gama#c%C3%B3digo)
1. [Links](https://github.com/mwmachado/gama#links)
1. [Links Relativos](https://github.com/mwmachado/gama#links-relativos)
1. [Imagem](https://github.com/mwmachado/gama#imagem)
1. [Listas](https://github.com/mwmachado/gama#listas)
   1. [Ordenadas](https://github.com/mwmachado/gama#ordenadas-123)
   1. [Não-Ordenadas](https://github.com/mwmachado/gama#n%C3%A3o-ordenadas----)
   1. [Aninhadas](https://github.com/mwmachado/gama#aninhadas)
   1. [Tarefas](https://github.com/mwmachado/gama#tarefas)
1. [Emoji](https://github.com/mwmachado/gama#emoji)
1. [Tabelas](https://github.com/mwmachado/gama#tabelas)
1. [Código HTML](https://github.com/mwmachado/gama#c%C3%B3digo-html)
1. [Referência](https://github.com/mwmachado/gama#refer%C3%AAncia)


-------

Título
------

# Título 1
## Subtítulo 2
### Subtítulo 3
#### Subtítulo 4
##### Subtítulo 5
###### Subtítulo 6

--------------------

Formatação
----------

_itálico_ *itálico*   
**negrito** __negrito__  
_**itálico e negrito**_  
~riscado~ ~~riscado~~  

------------------------

Quebra de linha
---------------

eu vou utilizar um 
espaço

eu vou utilizar dois  
espaços

Vou utiliza um

enter

--------------------

Citação
-------

> Evidentemente, a necessidade de renovação processual é uma das consequências
> das condições inegavelmente apropriadas.  
> [(Lero Lero)](https://lerolero.com/)

-------

Código
------

Código na linha `SELECT * FROM tabela;`
Bloco de código

```sql
SELECT *
FROM tabela;
```

------

Links
-----

`[texto do link](link)`  
`[google](https://www.google.com)`  
[google](https://www.google.com)

www.lerolero.com  
`[lero lero](www.lerolero.com)`  
[lero lero](www.lerolero.com)

------

Imagem
------

`![título](link da imagem)`  
`![ovelha](https://upload.wikimedia.org/wikipedia/commons/a/ac/Creative-Tail-Animal-sheep.svg)`  
![ovelha](https://upload.wikimedia.org/wikipedia/commons/a/ac/Creative-Tail-Animal-sheep.svg)

------

Links Relativos
---------------

É possível utilizar arquivos que estajam dentro do repositório, passando o caminho relativo

`![ovelha](ovelha.svg)`  
![ovelha](ovelha.svg)

---------------

Listas
------

### Ordenadas (1,2,3,...)

1. Item 1
1. Item 2
1. Item 3

### Não-Ordenadas (*, -, +)

* Item 1
+ Item 2
- Item 3

### Aninhadas

1. Item 1
1. Item 2
   1. Subitem 1
   1. Subitem 2

- Item 1
- Item 2
  - Subitem 1
  - Subitem 2

1. Item 1
1. Item 2
   - Subitem 1
   - Subitem 2

### Tarefas

- [x] Tarefa 1
- [ ] Tarefa 2
  - [ ] Subtarefa 1
  - [ ] Subtarefa 2

------

Emoji
-----

:+1:
[lista de emoji](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

-----

Tabelas
-------

|coluna 1|coluna 2|coluna 3|
|:-------|:------:|-------:|
|linha 1|valor|R$100,00|
|2|1|R$10,00|
|linha|valor 3|R$1,00|
|teste|

-------

Código HTML
-----------

<table>
    <thead>
        <tr>
            <th>Layer 1</th>
            <th>Layer 2</th>
            <th>Layer 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=4>L1 Name</td>
            <td rowspan=2>L2 Name A</td>
            <td>L3 Name A</td>
        </tr>
        <tr>
            <td>L3 Name B</td>
        </tr>
        <tr>
            <td rowspan=2>L2 Name B</td>
            <td>L3 Name C</td>
        </tr>
        <tr>
            <td>L3 Name D</td>
        </tr>
    </tbody>
</table>

-----------

Referência
----------

https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

----------
