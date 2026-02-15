É um endereços de memoria que guardam [[Dados]]

//Erro not set befor read it = variável foi usada antes de ser criada

## Variável do objeto
São declaradas dentro de um objeto e pertencem a cada instância criada, sendo ideais para armazenar dados exclusivos como HP ou velocidade
Sai da memoria quando o obj deixa de existir
## Variáveis internas
São pré criadas no Game Maker

EX:

### Velocidade
[speed](https://manual.gamemaker.io/lts/en/GameMaker_Language/GML_Reference/Asset_Management/Instances/Instance_Variables/speed.htm)
### Direção da velocidade
[direction](https://manual.gamemaker.io/monthly/br/GameMaker_Language/GML_Reference/Asset_Management/Instances/Instance_Variables/direction.htm)

## Variáveis Temporárias
Para cria-la é necessário utilizar a palavra var antes : var "variavel_temporaria". Elas só existem no [[Eventos|evento]] em que elas foram criadas. Facilitam a compreensão do código
Sai da memoria quando o evento termina
## Variáveis de Controle
Elas controlam se algo deve acontecer respondendo em valor [[Dados#Bool|booleano]]

## Variáveis Globais
Variáveis globais existem para todo o jogo
Uma variável global existe enquanto o jogo rodar
### Ex
global.vidas

