## Seletores

Existem algumas maneiras de selecionar um elemento do HTML. Nós já aprendemos a selecionar usando:

- **nome-elemento**, ex.: `h1`
- **#id**, ex.:  
  `<h1 id="id-elemento">Meu h1</h1>`

- **.class,** ex.:  
`<h3 class="classe-elemento">Meu h3</h3>`

## Combinadores de Seletores

Mas nós temos também maneiras de combinar esses seletores, veja abaixo:

- **elemento elemento:** Seleciona todos os elementos do segundo tipo que são descendentes (filhos, netos, etc.) de elementos do primeiro tipo.
- **elemento + elemento:** Seleciona todos os elementos do segundo tipo imediatamente precedidos por um elemento do primeiro tipo.
- **elemento ~ elemento:** Seleciona todos os elementos do segundo tipo que são precedidos por um elemento do primeiro tipo, não necessariamente imediatamente.
- **elemento > elemento:** Seleciona todos os elementos do segundo tipo que são filhos diretos de elementos do primeiro tipo.

## elemento ~ elemento

**SINTAXE:**

```CSS
p ~ span {
  text-decoration: underline;
  font-size: 18px;
}
```

**Resultado:** Irà selecionar todos os elementos do tipo `<span>` que seguir um elemento `<p>` dentro de um mesmo elemento pai.

## SINTAXE:

```CSS
ul > li {
  list-style: none;
}
```

**Resultado:** Irà selecionar todos os elementos `<li>` que estiverem diretamente dentro de um elemento `<ul>` especificado.

## Combinador de Seletores: > (child)

**Sintaxe:**

```css
elemento-pai > elemento-filho {
  /* propriedades CSS */
}