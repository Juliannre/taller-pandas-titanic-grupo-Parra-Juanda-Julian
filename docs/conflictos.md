# Documentación de Conflictos de Fusión

## 1. Archivo Afectado
* **Ruta:** `Proyecto_Programacion_II/notebooks/Proyecto_PRJ.ipynb`

## 2. Descripción del Conflicto
El conflicto se generó intencionalmente al intentar fusionar la rama `mis-avances` con la rama principal `main`. 
* **Cambio de Julián (rama `main`):** Tenía la versión inicial del cuaderno con los puntos del 1 al 4 y las rutas de archivos originales.
* **Cambio del segundo integrante (rama `mis-avances`):** Modificó el mismo archivo para agregar la solución de los puntos 5 al 7 y adaptó las rutas de lectura de los archivos `.csv` para que coincidieran con la nueva estructura de carpetas del proyecto.

Al coincidir las modificaciones en el mismo archivo del cuaderno, GitHub bloqueó la fusión automática.

## 3. Resolución del Conflicto
El líder del repositorio abrió la aplicación **GitHub Desktop**, cambió a la rama `main` e inició el proceso de fusión con `mis-avances`. Al detectarse el conflicto, se seleccionó la opción **"usar mi version"** para conservar las respuestas del taller completo (puntos 1 al 7) y mantener las rutas de carpetas corregidas. Se realizó el commit de la fusión y se subió con éxito al repositorio remoto.
