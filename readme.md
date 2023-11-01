How to use the Pikalang language
------------
stable:
```shell
pip install pikalang
```


Read the Pikalang file
-----
```shell
pikalang `hello-pikachu.pokeball`
```


File Extention
--------------
A pikalang program must be stored in a file with a `.pokeball` extention


Pikalang Syntax
------
pikalang  | brainfuck | description                                   
----------|-----------|-----------------------------------------------
`pi`      | +         | increment the byte at pointer                 
`ka`      | -         | decrement the byte at pointer                 
`pika`    | [         | if pointer is zero, jump to matching `chu`    
`chu`     | ]         | if pointer is nonzero, jump to matching `pika`
`pipi`    | >         | increment the data pointer                    
`pichu`   | <         | decrement the data pointer                    
`pikapi`  | ,         | input of one byte into pointer                
`pikachu` | .         | output the byte at pointer           

For more information, go to the official [repository](https://github.com/groteworld/pikalang)
