# Objects

Seguindo os princípios de OOCSS (CSS Orientado a Objetos), aqui é onde iremos ter nossos pequenos “objetos”, que nada mais são que pequenos pedaços da interface, em geral, padrões que se repetem por todo o site e que podem ter ou não uma camada visual por cima.

Aqui é onde fazemos os padrões de botões, listas, paineis, etc. 
Nesse momento, só é permitido também o uso de `classes`. 

Seguindo o padrão do RSCSS, teríamos algo assim:

```scss
.base-list {
    margin: 0;
    padding: 0;
    list-style: none;

    > .item {
        padding: $spacing-unit;
    }
}
```