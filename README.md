Diseño y Arquitectura de Despliegue  
Ivo Giuliano Cappetto  
**Fecha:** 05/05/2026

  ## Ejemplo 1:
Se configuró un contenedor basado en **PHP 8.2-Apache**. Se practicó la edición interna con el editor `vi` y la conexión remota mediante VS Code.

###  Captura: 
<img width="607" height="219" alt="Ejemplo 1" src="https://github.com/user-attachments/assets/6fb7b972-12ff-40bd-86fd-3b98d3e24a35" />

## Ejemplo 2:
Se implementó un flujo de trabajo mediante un script de Bash (`run.sh`) que gestiona el ciclo de vida del contenedor (build, stop, rm y run) en el puerto **8081**.

### Captura:
<img width="593" height="290" alt="Ejemplo 2" src="https://github.com/user-attachments/assets/49b4749b-43ab-49a5-aa76-b58a6a056292" />

---

## Uso:
Para ejecutar el segundo ejemplo:
1. Abrir terminal en la carpeta raíz.
2. Ejecutar: `sh "ejemplo 2/run.sh"`
3. Acceder a: `http://localhost:8081`
