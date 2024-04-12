<!--
  <<< Notas del autor: Paso 3 >>>
  Solo una nota histórica: la versión anterior de este paso obligaba al alumno
  a escribir una descripción de la solicitud de extracción,
  verificaba que `main` fuera la rama receptora,
  y que el archivo tuviera el nombre correcto.
-->

## Paso 3: Abrir una solicitud de extracción

_¡Buen trabajo haciendo ese commit! :sparkles:_

Ahora que has realizado un cambio en el proyecto y has creado un commit, ¡es hora de compartir tu cambio propuesto a través de una solicitud de extracción!

**¿Qué es una solicitud de extracción?**: La colaboración ocurre en una _[solicitud de extracción](https://docs.github.com/en/get-started/quickstart/github-glossary#pull-request)_. La solicitud de extracción muestra los cambios en tu rama a otras personas y les permite aceptar, rechazar o sugerir cambios adicionales a tu rama. En una comparación lado a lado, esta solicitud de extracción mantendrá los cambios que acabas de hacer en tu rama y propondrá aplicarlos a la rama principal del proyecto `main`. Para obtener más información sobre las solicitudes de extracción, consulta "[Acerca de las solicitudes de extracción](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)".

### :keyboard: Actividad: Crea una solicitud de extracción

Puede que hayas notado después de tu commit que apareció un mensaje indicando tu último envío a tu rama y proporcionando un botón que dice **Comparar y hacer una solicitud de extracción**.

![captura de pantalla del mensaje y el botón](/images/compare-and-pull-request.png)

Para crear automáticamente una solicitud de extracción, haz clic en **Comparar y hacer una solicitud de extracción**, y luego pasa al paso 6 a continuación. Si no haces clic en el botón, las instrucciones a continuación te guiarán a través de la configuración manual de la solicitud de extracción.

1. Haz clic en la pestaña **Solicitudes de extracción** en el menú de encabezado de tu repositorio.
2. Haz clic en **Nueva solicitud de extracción**.
3. En el menú desplegable **base:**, asegúrate de que esté seleccionada la opción **main**.
4. Selecciona el menú desplegable **compare:**, y haz clic en `mi-primera-branch`.

   <img alt="captura de pantalla que muestra ambas selecciones de rama" src="/images/pull-request-branches.png" />

5. Haz clic en **Crear solicitud de extracción**.
6. Ingresa un título para tu solicitud de extracción. Por defecto, el título será automáticamente el nombre de tu rama. Para este ejercicio, editemos el campo para que diga `Agregar mi primer archivo`.
7. El siguiente campo te ayuda a proporcionar una descripción de los cambios que has realizado. Aquí, puedes agregar una descripción de lo que has logrado hasta ahora. Como recordatorio, has: creado una nueva rama, creado un archivo y hecho un commit.

   <img alt="captura de pantalla que muestra la solicitud de extracción" src="/images/Pull-request-description.png" />

8. Haz clic en **Crear solicitud de extracción**. Serás redirigido automáticamente a tu nueva solicitud de extracción.
9. Espera unos 20 segundos y luego actualiza esta página (la que estás siguiendo las instrucciones). [GitHub Actions](https://docs.github.com/en/actions) se actualizará automáticamente al siguiente paso.

> [!NOTA]
> ¡Es posible que veas evidencia de GitHub Actions ejecutándose en la pestaña con la solicitud de extracción abierta! La imagen a continuación muestra una línea que podrías ver en tu solicitud de extracción después de que la acción termine de ejecutarse.
> 
> <img alt="captura de pantalla de un ejemplo de una línea de acciones" src="/images/Actions-to-step-4.png"/>
