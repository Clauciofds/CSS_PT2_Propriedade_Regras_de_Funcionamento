## Pseudo-Elementos

Existem elementos do HTML que possuem várias partes para serem estilizadas, por isso foram criados os pseudo-elementos, que nos ajudam a estilizar um elemento por partes. Por exemplo:

```css
input::placeholder {
  color: blue;
}

h1::before {
  content: "";
  background-color: purple;
}

h1::after {
  content: "";
  background-color: orange;
}
```