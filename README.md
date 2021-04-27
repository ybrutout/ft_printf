# ft_printf
19S - second projet in the first ring.  
19S - deuxieme projet du premier cercle.  
  
In this project, we have to rewrite the printf function identically.  
You can find the details of the project in the PDF.  
Dans ce projet, nous devons réécrire à l'identique la fonction printf.  
Vous pouvez retrouver les détails du projet dans le PDF.  
  
## Grade

First try : 91%
Second try : 100%

## Explanation

During this project, we had to manage the following conversions: "%c, %s, %d, %i, %u, %p, %x, %X".  
At the same time, we had to manage the following flags: "-0.*".  
  
Durant ce projet, noous devions gérer les conversions suivantes : "%c, %s, %d, %i, %u, %p, %x, %X".  
Dans un même temps, nous devions gérer les flags suivants : "-0.*".  
  
Printf is a function found in the <stdio.h> library.  
man printf EN : https://linux.die.net/man/3/printf  
  
Printf est un fonction qui se retrouve dans la librairie <stdio.h>.  
man printf FR : http://manpagesfr.free.fr/man/man3/printf.3.html  
  
### Conversions

Une conversion a une syntaxe bien précise. Elle suit toujours un ordre qui est :  
%[flags][width][precision][type]  
  
**Remarque :** Seul le pourcent et le type sont obligatoire.  

#### Type 




