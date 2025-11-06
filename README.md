"Proyecto colaborativo"

se creo feature/funcionalidad-A y feature/funcionalidad-B
para realizar el ejecicios. 

además se reutilizo el mismo proyecto para realizar la tarea solicitada:

se crea feature/funcionalidad-C y se crea feature/funcionalidad-D

### Caso 1
dentro de funcionalidad-C
archivo script.js
  function apellido(){
    return "MORENO";
}
dentro de funcionalidad-D
archivo script.js
function name(){
    return "JULIO";   
}

En la rama main 
se realizar el git merge feature/funcionalidad-C y 
se realiza el git merge feature/funcialidad-D
donde se aceptan ambos cambios.
[Evidencia! acepto ambos cambios](/assets/evidencia/CASO1-AceptanAmbosCambios.png)


### Caso 2
dentro de funcionalidad-C
se crea archivo scritpDos.js
const valorBase = 10;

console.log(valorBase + 5)

dentro de funcionalidad-D
se crea archivo scritpDos.js
const valorBase = 10;
console.log(valorBase / 2);

En la rama main 
se realizar el git merge feature/funcionalidad-C y 
se realiza el git merge feature/funcialidad-D
aparece este cuadro
[Evidencia!](/assets/evidencia/CASO1-AceptanAmbosCambios.png)
se comparan los cambios 
[Evidencia! comparan los cambios](/assets/evidencia/CASO2-ComparaCambios.png)
se deja el cambio con la suma que fue el primer merge que se realizo
[Evidencia! mantiene la funcion suma](/assets/evidencia/CASO2-Suma.png)


### Caso 3
dentro de funcionalidad-D
modifique la division por multiplicación
const valorBase = 10;
console.log(valorBase * 2);

En la rama main 
se realiza el git merge feature/funcialidad-D
selecciono hacerlo manual y agrego funciones básicas como restar, sumar, multiplicar y dividir.
[Evidencia! mantiene la funcion suma](/assets/evidencia/CAS03-ResultadoFinal.png)
