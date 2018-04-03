# \<polymer-case\>



## Instalando Polymer-CLI

Primeiro, verifique se o Polymer-cli foi instalado corretamente. [Polymer CLI](https://www.npmjs.com/package/polymer-cli) 

## Executando o projeto

```
$ polymer serve
```

```
$ polymer serve --open  //para abrir o navegador
```

## Executando testes

```
$ polymer test
```

## Exemplo de utilização do component

Para povoar o elemento customizado de ```<select> ``` deve ser definida a propriedade "items" com o array de objetos a serem listados. Estes objetos devem possuir os atributos "name" para descrição e "value" para valor do item na listagem.

O componente também aceita a configuração de dois elementos de rodapé, contidos nos slots "footer" e "footer2".

```
<my-select-element items='[{"name": "Arroz", "value": 999}]' >
    <h5 slot="footer2">Footer test2</h5>
    <h6 slot="footer">Footer test</h6>
</my-select-element>
```
