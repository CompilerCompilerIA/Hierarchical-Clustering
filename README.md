# Hierarchical Clustering (Clustering Jerárquico)

## Antes de empezar
Se debe de instalar las siguientes librerías ejecutando los comandos monstrados a continuación en el CMD con permisos de amdinistrador:

```
pip install jupyterlab
```
```
pip install notebook
```
```
pip install voila
```
```
pip install pandas
```
```
pip install matplotlib
```
```
pip install sklearn
```

## Bases teóricas
En este método de agrupación jerárquica, el conjunto dado de un objeto de datos se crea en una especie de descomposición jerárquica. La formación de la descomposición jerárquica decidirá los fines de la clasificación. Hay dos tipos de enfoques para la creación de descomposición jerárquica, que son:
A) Enfoque Divisivo
También llamado enfoque de arriba hacia abajo; comienza con todos los objetos de datos en el mismo grupo. Los clústeres más pequeños se crean dividiendo el grupo mediante la iteración continua. El método de iteración constante continuará hasta que se cumpla la condición de terminación.
No se puede deshacer después de dividir o fusionar el grupo, y es por eso que este método no es tan flexible.
Informe: Uso Del Algoritmo De Agrupamiento "Clustering"
Cárdenas R. Mikaela, Paniagua M. Luciano, Valenzuela D. Manuel,
Vargas C. Santiago, Viladegut A. Rodrigo
Informe: Uso Del Algoritmo De Agrupamiento "Clustering" 2
B) Enfoque Aglomerativo
También llamado enfoque de enfoque de abajo hacia arriba.
Consiste en que todos los grupos están separados al principio.
Luego continúa fusionándose hasta que todos los grupos se
fusionan o se cumple la condición de terminación.
