# Mon premier projet

Calcul de la moyenne de valeurs dans un vecteur

## Compilation

```
mpicxx mean.cpp -o mean
```

## Exécution

```
mpiexec -n 2 ./mean
```
S'il n'y a pas assez de processus disponibles :
```
mpiexec -n 2 --oversubscribe ./mean
```

## Sous Codespace

Il faut installer openmpi

```
sudo apt update
sudo apt install libopenmpi-dev openmpi-bin
```