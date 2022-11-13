## Capítulo 6

 - Atividade 6.1<br />
  `ps -r`<br />
  `top -d 1 -o %CPU -o %MEM`<br />

  
 
 - Atividade 6.2<br />
  `htop (F5 para exibição em modo árvore)`<br />
![Atividade 6.2 1](6.2_1.png)<br />
 `jobs`<br />
![Atividade 6.2 2](6.2_2.png)<br />

- Atividade 6.3<br />
![Atividade 6.3](6.3.png)<br />
- Atividade 6.4<br />
`#!/bin/bash`<br />
`printf "O diretorio atual eh: $(pwd) \n"`
`printf "O Shell desse usuario eh: $(grep $(whoami) /etc/passwd | cut -d ":" -f 7)\n"`
