
Step Over：在单步执行时，在函数内遇到子函数时不会进入子函数内单步执行，而是将子函数整个执行完再停止，也就是把子函数整个作为一步。
           有一点，经过我们简单的调试，在不存在子函数的情况下是和Step Into效果一样的（简而言之，越过子函数，但子函数会执行）。  
Step Into：单步执行，遇到子函数就进入并且继续单步执行（简而言之，进入子函数）。  
Step Into My Code：进入自己编写的函数，不进入系统函数，很少用到。  
Force Step Into：强制进入，在调试的时候能进入任何方法。  
Step Out：当单步执行到子函数内时，用Step Out就可以执行完子函数余下部分，并返回到上一层函数。  
Run to Cursor：一直执行，到光标处停止，用在循环内部时，点击一次就执行一个循环。  
