Testes com git ignore

pasta1
|    |- pasta1.1
|    |- pasta1.2
|    |    |- pasta1.2.1
|    |    |- arquivo1.2.txt
|    |    |- teste.txt
|    |    |>.gitignore
|    |      |-> arquivo1.2.txt
|    |>.gitignore 
|       |-> /pasta1.1
pasta2
|    |- pasta2.1
|    |- pasta2.2
|    |   |- arquivo2.2.txt
|    |>.gitignore
|       |-> /pasta1
|       |-> /pasta2.2/arquivo2.2.txt
pasta3
|    |- pasta3.1
|       |- arquivo3.1.txt
|       |>.gitignore
|           |-> /arquivo3.1.txt
|    |- pasta3.2
|    |   |- teste.txt
|    |>.gitignore
|       |-> arquivo3.1.txt
pasta4
|    |- pasta4.1
|       |- arquivo4.1.txt
|       |>.gitignore
|           |-> arquivo4.1.txt
|    |- pasta4.2
pasta5
|    |- pasta5.1
|    |- pasta5.2
|    |>.gitignore
|       |-> /pasta5.1
teste.txt
|>.gitignore
    |-> /pasta5.1
    |-> teste.txt