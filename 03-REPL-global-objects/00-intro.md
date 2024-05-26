- REPL (Read, Eval, Print, Loop)
    
    → very useful in experimenting with node.js  and debug JS code.
    
    → wright `node` enter in REPL
    
    ⇒ what we can do in REPL
    
    - run JS code
    - multiline code
    - `_` will represent the last result
    - with `double Tab Btn` we can get all variable’s and keywords
    
    ```jsx
    .editor   : Enter editor mode -> we can code like edditer
    
    .break    Sometimes you get stuck, this gets you out
    .clear    Alias for .break
    .help     Print this help message
    .load     Load JS from a file into the REPL session
    .save     Save all evaluated commands in this REPL session to a file
    
    .exit     Exit the REPL
    ```


.break and .clear example
```
> while(true){
... .break
>
```

.save fileName.js            `below code will be save in file`
```
> let a = 10;
> let b = 20;
> let result = (a<b ? "a is smaller", "b is smaller")
> console.log(result)
```

.load fileName.js
-> this load js file in REPL

