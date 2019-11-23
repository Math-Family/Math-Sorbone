
$$\Large \text{ Montrer que la double inégalité suivante est satisfaite:}$$

$\large \text{pour tout   } x \geq 0$  $\frac{x}{x+1}\leq ln(1+x) \leq x $


##  Premiere étape : l'éxistance de $\huge c$:

$\large \exists c \in [0, x[   \text{tel que } f'(c)=\frac{f(x)-f(0)}{x-0}= \frac{f(x)}{x}$   $\large \text{  Retenons cela        (1)}$

##  Deuxième étape : l'déterminer $\huge c$ en fonction de $\huge f'(c)$:

$\large f(x)= ln(1+x) \rightarrow f'(x)=\frac{1}{1+x}$ 
### ET
$\large f'(c)=\frac{1}{1+c}$
$\large \text{ On a donc:} \color{red}{\Huge c= \frac{1}{f'(c)}-1} $    $\large \text{  Retenons cela        (2)}$

## Résumons:   
### On a les donéees suivantes  :

$\large \color{green } {c \in [0, x[ } \text{   ce qui veut dire qu 'on a: }$

 $ \huge \color{red}{c\geq 0}$
 
$ \huge \color{red}{c < x}$



 $\large \text{Pour } \Huge c\geq 0 $ 
 
 $\large \text{ Revenons à  (2)  }$  $\large c\geq 0  \rightarrow  \frac{1}{f'(c)}-1 \geq 0 \rightarrow f'(c)\leq 1$

## Or on a déjà   $\large f'(c) = \frac{f(x)}{x}$

$\large \text{ Donc on a :} \frac{f(x)}{x}\leq 1 \rightarrow \huge f(x)\leq x  \large \text{  Retenons cela        (3)}$



 $\large \text {Pour }\Huge c\leq x $ 
 
  $\large \text{ Revenons à  (2)  }$   $\large c\leq x  \rightarrow  \frac{1}{f'(c)}-1 \leq x
  \rightarrow f'(c)\geq \frac{1}{1+x}$ 
  
  $\large \text{Or on a  f'(c)}=\frac{f(x)}{x}   \text{Donc on aura } \frac{f(x)}{x}  \geq \frac{1}{1+x} \rightarrow f(x) \geq \frac{x}{1+x}$

## Finaelment on peut conclure ce qui suit :

$\huge f(x)\leq x   \color{red}   {\text{  Et}}   f(x) \geq \frac{x}{1+x} $


$$\Huge  \frac{x}{1+x} \leq ln(x+1) \leq x  $$


```R

```
