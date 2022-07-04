# mlop
Machine Learning et Optimisation

Repo personnel de documentation et notes maisons en lien avec l'optimisation et l'apprentissage machine.  Prises lors de cours, rencontres ou directement du web.



## Regression univariée

### MSE 

Calcul de l'erreur (fonction de coûts)
$$J(w,b) = \frac{1}{2m} \sum\limits_{i = 0}^{m-1} (f_{w,b}(x^{(i)}) - y^{(i)})^2$$ 

### Calcul du gradient de descente:


$$  w = w -  \alpha \frac{\partial J(w,b)}{\partial w}  \; \newline 
 b = b -  \alpha \frac{\partial J(w,b)}{\partial b}
$$

où

$$
\begin{align}
\frac{\partial J(w,b)}{\partial w}  &= \frac{1}{m} \sum\limits_{i = 0}^{m-1} (f_{w,b}(x^{(i)}) - y^{(i)})x^{(i)}\\
  \frac{\partial J(w,b)}{\partial b}  &= \frac{1}{m} \sum\limits_{i = 0}^{m-1} (f_{w,b}(x^{(i)}) - y^{(i)})\\
\end{align}
$$

et où

$\alpha$ = taux d'apprentissage

$m$ = taille de l'ensemble d'entrainement

## Régression linéaire multiple

