# Anualidades-Anticipadas

con este código podemos resolver las funciones para anualidades anticipadas

```{r}
source("https://raw.githubusercontent.com/IsabellaC01/Anualidades-Anticipadas/refs/heads/main/ejercicios.R")
```
Se realizan los cálculos:
```{r}
# Creamos objetos con los valores de entrada:
anualidad=1200
tasaPeriodo=0.005
nPeriodos=60
# Calculamos el valor futuro:
valorFuturo=valorFuturo(A=anualidad,r=tasaPeriodo,n=nPeriodos)
# Imprimimos el resultado:
valorFuturo

```
