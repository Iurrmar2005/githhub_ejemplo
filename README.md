# githhub_ejemplo
lo mismo que he hecho en local, ahora desde servidor externo.

## Pasos para sincronizar con internet
0.**Pull**, No sabemos si alguien ha hecho modificaciones en los archivos de internet. Deberiamos descargarlos
0.En cuanto escribimos algo que esta sin grabar, en la pestaña de este archivo sale con un punto gordo, para avisarnos.
1. Grabar los cambios (Ctrl+S) - Aparece una marca en el icono de *source control* con el número de archivos en los que hemos guardado cambios.
1. **stage**:Marcar los archivos cambiado para que se preparen para ser *controlados* por el sistema
1. **commit**:Añadir los archivos marcados a un nuevo punto de control de versiones.
1. **Push**: Sincronizar (subir) lo que tenemos en nuestro ordenador

## Errores posibles

1. **No hacer stage**. Si no le dais al `+`, no hay nada que confirmat. El programa te sugiere añadir el mismo los cambios
2. **No poner mensaje de commit**. El programa te abre una pestaña para que lo pongas. Hay que escribirlo,guardarlo y cerrarlo.
3. **Olvidar sincronizar**. Esto no puedo saltarmelo 