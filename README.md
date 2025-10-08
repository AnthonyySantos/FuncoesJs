# FuncoesJs
Tutorial de como definir e criar funções em Javascript utilizando os formatos:
- ***Declaration***
- ***Expression***
- ***Arrow***

## Definição de funções
> Funções são blocos de código reutilizáveis para realizar uma tarefa específica,
> podendo ser chamada várias e várias vezes.

## Function Declaration
> Forma comum de declarar uma função.
- Podendo ser chamada antes da sua definição.
```
function NomeDaFunção(arg1, arg2) {
corpo da função
};
```

## Function Expression
> Função que é atribuida a uma variável. Podendo ser anônima ou nomeada.
- Não sofre hoisting
```
const NomeDaFunção = function(arg1, arg2) {
corpo da função
};
```

## Function Arrow
> Forma mais resumida de escrever funções, introduzida no ES6.
- Utiliza-se a sintaxe de "seta" (=>)
```
const NomeDaFunção = (arg1, arg2) => {
corpo da função
};
```
