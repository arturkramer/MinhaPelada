# Minha Pelada
### Aplicação desenvolvida em [QT](http://www.qt.io) a fim de registrar e gerenciar peladas

Esta aplicação permite que o usuário insira o nome do peladeiro, sua matrícula e o número de peladas disputadas pelo mesmo. A interface inicial da aplicação está demonstrada na figura abaixo.

![](figuras/tela_inicial.png)

Como pode-se ver, essa aba inicial denominada "Inserir", possui na parte superior, três Labels e três Line Edits, nos quais o usuário pode inserir os dados do peladeiro desejado. Abaixo desses itens ditos anteriormente possui uma Table Widget(tabela) na qual são inseridos, após o PushButton "Inserir" for clicado, os dados do peladeiro em questão. Vale ressaltar que existe também uma observação abaixo da Table Widget, que se refere ao símbolo *.  

A aplicação possui também uma aba denominada "Estatísticas" referente aos dados inseridos na tabela. Essa aba está demonstrada na figura abaixo.

![](figuras/estatisticas.png)

Essa aba, como pode-se observar, possui 5 Group Boxes e 5 Labels. Nos três primeiros são mostrados a quantidade em porcentagem de cada cargo existente na tabela. Os dois últimos são responsavéis por mostrar o peladeiro mais assíduo e o menos assíduo, respectivamente, tudo segundo dados extraídos da Table Widget da aba "Inserir".

A aplicação também é capaz de realizar ordenações, no momento em que o usuário clica determinado PushButton. Primeiramente, pode-se ordenar os dados da Table Widget por nome dos peladeiros, ao clicar o PushButton que contém a mensagem "Ordenar por Nome", como demonstrado a seguir:

![](figuras/ordenar_name.png)

Seguindo, o usuário também pode optar por ordenar por assiduidade, ou seja, por ordem decrescente do número de peladas, ao pressionar o PushButton que contém a mensagem "Ordenar por Assiduidade", como demostrado na figura abaixo:

![](figuras/ordenar_ass.png)

Por fim, o mesmo pode optar por ordenar por prioridade da pelada, ao pressionar o PushButton que contém a mensagem "Ordenar por Prioridade", levando em conta que servidores possuem maior prioridade do que dependentes, que por sua vez, possuem mais prioridade do que convidados. Essa ordenação está demonstrada a seguir:

![](figuras/ordenar_prio.png)









