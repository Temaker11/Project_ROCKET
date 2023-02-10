## display: block vs display inline

- Como as caixas se comportam em relação ás outras caixas 
- Coomportamento externo  das caixas 
|-----------------------------------|----------------------------------|
|**block**                          |**inline**                        |
|-----------------------------------|----------------------------------|
| Ocupa toda a linha, colocando o   | Elementos ao lado do outro       |
| próximo elemento abaixo desse     |                                  |
|-----------------------------------|----------------------------------|
| widht e height são respeitados    | widht e height não funcionam     |
|-----------------------------------|----------------------------------|
| padding, margin, border irão      | Somente valores horizontais de   |
| funcionar normalmente.            | marigin- padding e border        |
|-----------------------------------|----------------------------------|

exemplos 
block: `<p> <div> <section>`, todos os headings `<h1> <h2>...`
inline: `<a> <strong> <span> <em>`
