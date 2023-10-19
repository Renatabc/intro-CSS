# Introdução ao CSS
Conceitos iniciais na folha de estilização de sites, em formato CSS. Importante que já tenha uma base em HTML para conseguir entender melhor essa seção.

### O que é CSS?
*Cascading Style Sheets*, ou Folha de Estilo em Cascata, é um mecanismo para adicionar estilos a um documento web (HTML). Determina como deve ser o layout de uma página e como os elementos do nosso site devem ser.

> O que **não** é?<br>
>1. Linguagem de programação;
>2. Linguagem de marcação.

> O que **pode ser criado?**<br>
>1. Layouts e estilização de páginas web - [Exemplo](https://www.netflix.com/br/);
>2. Animações - [Exemplo](https://renatabc.github.io/Day11CSS/);
>3. Formas geométricas e desenhos - [Exemplo](https://github.com/Renatabc/Day01CSS);
>4. Filtros;
>5. Contadores.

### Formas de declaração do CSS
- **Propriedade**: Característica de um elemento do HTML.
- **Valor**: o que a propriedade terá.

Exemplo: propriedade: valor;
```
background: red;
color: white;
```

### Como declarar
- **CSS Inline**: adicionamos o código CSS utilizando o atributo style dentro das tags HTML, elemento por elemento. *Ela acaba não sendo muito usada, pois só conseguimos alterar elementos isoladamente, fazendo com que muito tempo seja perdido.*
- **CSS Interno**: é adicionado dentro da tag head da página HTML. Dentro dela, adiciona-se a tag *style* e as regras CSS.
- **CSS Externo**: é criado um arquivo de extensão .css com todas as regras CSS que queremos aplicar. Ele é referenciado no HTML através da tag *link*. É o melhor recurso e mais utilizado.

### Depurando CSS
É um processo onde se identifica problemas no código-fonte da aplicação e ajuda a entender seu comportamento.
Todos os navegadores possuem uma ferramenta para desenvolvedores com essa finalidade, chamada **Dev Tools**.

>**Atalhos no Google Chrome:**<br>
>CTRL + SHIFT + i<br>
>CTRL + SHIFT + c<br>
>F12

## Seletores
Ele define quais elementos iremos aplicar o CSS.

### Seletor de tags
Busca elementos por uma tag HTML específica.

### Seletor de id
Busca elementos através do atributo id.

### Seletor de classes
Busca elementos através do atributo class.

### Seletores universais
Seleciona todos os elementos HTML.

### Seletores de atributo
Seleciona elementos que possuem um atributo específico em nosso documento HTML. Conseguimos também buscar atributo com um valor específico.