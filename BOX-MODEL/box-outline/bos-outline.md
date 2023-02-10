## border ( e outline)
As bordas da caixa

- value: `<border-style>` | `<width>` | `<border-color>`
  - style: solid | dotted | dashed | double | groove | ridge | inset | outline
  - width: `<lenght>`
  - color: `<color>`

  ´´´css
  div {
    <!-- shorthand -->
    border-top: solid 2px; <!-- top, right, bottom, left -->
    <!-- style -->
    border: solid;
    <!-- width <lenght> | style -->
    border 2px dotted;
    <!-- style color -->
    border: outset #f33;
    <!-- widht | style | color -->
    border: medioum dashed green;
  

  }
  ```

  ### E outline?

  - diferente em 4 sentidos:
    - Não modifica o tamanho da caixa, pois não é partedo box model
    - Poderá ser diferente de retangular 
    - Não permite ajuste individuais 
    - Mais usado pelo user  agent para acessibilidade 