# Comandos para hacer el ejercicio básico de ramas.
## Paso I:
```
git init
git add .
git commit -m "Commit A"
*1ºCambio*
git add .
git commit -m "Commit B"
```
## Paso II:
```
git branch exp
git checkout exp
*2º Cambio*
git add .
git commit -m "Commit C"
```
## Paso III:
```
git checkout main
*3º Cambio*
git add .
git commit -m "Commit E"
```
## Paso IV:
```
git checkout exp
*4ºCambio*
git add .
git commit -m "Commit D"
```
## Paso V:
```
git checkout main
*Hago merge de main y exp, creo el readme y hago el último cambio en main*
git add .
git commit -m "Commit F"
```