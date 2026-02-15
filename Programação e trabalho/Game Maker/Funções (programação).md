Checa se a condição é verdadeira e retorna em dado [[Dados#Bool|Booleanos]]

## If
significa "Se"
Checa se a informação é correta para que seja executado um comando
se sim ele retorna True, se não ele retorna False
## Else
significa  "Se não"
Se a informação do If for falsa ele executara o comando
(sempre vem depois do If)
## Else if
Uma condição para que caso a primeira condição seja falsa

## Função recursiva
chama ela mesma
# Função do usuário
pode ser chamada posteriormente em qualquer momento em seu código. Uma função definida pelo usuário é aquela que você define para fazer uma tarefa que não é coberta pelas ações visuais incorporadas GML ou pelas funções de corredor GML, e pode ser global, por exemplo ou local no escopo (veja [aqui](https://manual.gamemaker.io/monthly/br/GameMaker_Language/GML_Overview/Variables_And_Variable_Scope.htm) para mais informações sobre escopo); elas também podem ser usadas como **construtoras** para criar [estruturas](https://manual.gamemaker.io/monthly/br/GameMaker_Language/GML_Overview/Structs.htm). Para saber mais sobre o uso desta ação para criar funções globais, consulte a seção sobre [Criação de funções de ação](https://manual.gamemaker.io/monthly/br/Drag_And_Drop/Drag_And_Drop_Overview/Action_Block_Functions.htm).
A diferença entre função e método é que o método  só é usável no objeto que foi criado
## Ex
Function ImparOuPar (-n)
{

}
## Method
são funções de objetos
### Ex
ImparOuPar = function(-n)
{

}
### @Method
serve para fazer o método aparecer no preenchimento automático
#### EX
@method bom dia {string}_ mensage1
Bom dia = Function(mensage1)
show_mensage (mensagem1)
## @Function
bom dia (mensagem1)
param primeira_mensagem
paran segunda_mensagem
# Funções Condicionais aninhadas
é quando se coloca um if dentro de um if por exemplo
