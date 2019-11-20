# javascript-studies
Estudando e (re)aprendendo javascript


### Métodos de STRING

#### Split()
- Divide um objeto String em um array de strings. Separa a string inicial em substrings.
- Sintaxe: *__str.split(separador, limite)__*
    - Separador (Opcional): Diz com qual caracter a string será separada. 
    - Limite (Opcional): Especifica um limite no número de divisões a serem encontradas 
- Exemplo: 

```
    let exemploSplit = 'Bruna'
    
    exemploSplit.split('')
    
    console.log(exemploSplit) // RESPOSTA: Array de (5) elementos: [ "B", "r", "u", "n", "a" ]

```

### Métodos de ARRAY

#### Reverse()
- Os últimos serão os primeiros! Inverte os itens de um array. O primeiro elemento do array se torna o último e o último torna-se o primeiro.
- Sintaxe: *__array.reverse()__*
- Exemplo:
```
   let exemploArrayComReverse = ['um', 'dois', 'três']
    exemploArrayComReverse.reverse()
    
   console.log(exemploArrayComReverse) // RESPOSTA: ['três', 'dois', 'um']
```

#### Join()
