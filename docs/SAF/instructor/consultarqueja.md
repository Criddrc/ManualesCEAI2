# 📘 COMITÉ DE SEGUIMIENTO - CONSULTAR QUEJAS

La consulta de quejas de aprendices desde el módulo de Comité de Seguimiento. A través de esta gestión se pueden filtrar y revisar todas las quejas registradas por los instructores, conociendo su estado actual dentro del proceso, las observaciones registradas, las fechas de comité asignadas y las acciones disponibles según la situación de cada queja en el sistema SAF-CEAI.

> **Referencia de estados de una queja:** El sistema maneja cinco estados posibles para cada queja:
 **Pendiente** indica que la queja fue registrada por el instructor y aún no ha sido gestionada por la Coordinación. 
 **Agendada** indica que la queja tiene fecha y hora de comité asignadas. 
 **En Proceso** indica que la queja está siendo atendida activamente. 
 **Tramitada** indica que la queja fue atendida y tiene fecha de comité registrada. 
 **Rechazada** indica que la queja fue revisada y no procedió, quedando registrada una observación que sustenta la decisión.

## 1️⃣ **Acceder a Quejas**

Asegúrese de haber iniciado sesión en el sistema SAF-CEAI con sus credenciales de **Coordinador Académico**.

En el menú lateral izquierdo, localice la sección **Comité de Seguimiento** y haga clic sobre ella para desplegar el submenú. Dentro del submenú, identifique y haga clic en la opción **Quejas**. El sistema lo redirigirá a la interfaz de consulta de quejas.

![Menú Comité de Seguimiento - Quejas](site:assets/imagenes/saf/registrarQueja/menuQuejas.png){: .clickable-image}

## 2️⃣ **Configurar los filtros de búsqueda**

En la parte superior de la pantalla encontrará el panel **Consulta de Quejas** con los siguientes campos de filtro disponibles.
 - **ID Queja:** En el campo **ID Queja** puede escribir directamente el identificador numérico de la queja que desea buscar. Si no conoce el ID, deje este campo vacío para consultar todas las quejas según los demás filtros aplicados.
 - **Curso/Ficha:** En el selector **Curso/Ficha** haga clic en la flecha desplegable ![desplegable](site:assets/imagenes/saf/iconos/desplegable.png){:.inline-img} y seleccione el grupo o ficha cuyas quejas desea consultar. El valor predeterminado es **TODOS**, lo que incluirá quejas de todos los grupos disponibles en el resultado.
 - **Estado:** En el selector **Estado** haga clic en la flecha desplegable ![desplegable](site:assets/imagenes/saf/iconos/desplegable.png){:.inline-img} y seleccione el estado por el cual desea filtrar las quejas. Las opciones disponibles son **TODOS**, **Pendiente**, **Agendada**, **Rechazada**, **Tramitada** y **En Proceso**. Seleccione el estado específico que desea revisar o deje el valor **TODOS** para ver el resultado completo sin distinción de estado.

![Opciones desplegables del selector Estado](site:assets/imagenes/saf/registrarQueja/selectorEstado.png){: .clickable-image}

- **Fecha Comité:** En el campo **Fecha Comité** puede ingresar una fecha en formato dd/mm/aaaa para filtrar únicamente las quejas que tengan programada esa fecha de comité. Este campo es opcional y puede dejarse vacío si no requiere filtrar por fecha.

- **Aprendiz:** En el selector **Aprendiz** haga clic en la flecha desplegable ![desplegable](site:assets/imagenes/saf/iconos/desplegable.png){:.inline-img} y seleccione el nombre del aprendiz específico cuyas quejas desea consultar. El valor predeterminado es **TODOS**.
En el selector **Aprendiz** haga clic en la flecha desplegable ![desplegable](site:assets/imagenes/saf/iconos/desplegable.png){:.inline-img} y seleccione el nombre del aprendiz específico cuyas quejas desea consultar. El valor predeterminado es **TODOS**.

- **Instructor Quejoso:** En el selector **Instructor Quejoso** haga clic en la flecha desplegable ![desplegable](site:assets/imagenes/saf/iconos/desplegable.png){:.inline-img} y seleccione el instructor que registró la queja que desea ubicar. El valor predeterminado es **TODOS**.

![Panel Consulta de Quejas con todos sus filtros](site:assets/imagenes/saf/registrarQueja/selectorEstado2.png){: .clickable-image}

## 3️⃣ **Ejecutar la consulta**

Una vez configurados los filtros deseados, haga clic en el botón ![Consultar](site:assets/imagenes/saf/iconos/consultar.png){:.inline-img}. El sistema mostrará el **Listado de Quejas** con todos los registros que correspondan a los criterios seleccionados.

Cada fila del listado presenta el ID de la queja, la ficha, el grupo, el documento del aprendiz, el nombre del aprendiz, el estado actual de la queja, el nombre del informante o quejoso, la fecha en que se registró la queja, el campo de observación con el comentario registrado por la Coordinación, la fecha de comité asignada, la hora de citación y la columna de opciones de acción.

El campo **Observación** permite identificar el motivo por el cual una queja fue rechazada. Cuando el estado es **Rechazada**, este campo mostrará el texto explicativo registrado por el Coordinador Académico al momento de tramitar la decisión.

![Listado de Quejas con estados Tramitada y Rechazada](site:assets/imagenes/saf/registrarQueja/panelConsulta.png){: .clickable-image}

Cuando el filtro **Estado** se establece en **Pendiente**, el listado mostrará únicamente las quejas que aún no han sido gestionadas por la Coordinación, es decir, aquellas que no tienen fecha de comité asignada ni observación registrada y que están a la espera de ser atendidas.

![Listado de Quejas filtrado por estado Pendiente](site:assets/imagenes/saf/registrarQueja/listadoQuejasPendientes.png){: .clickable-image}

## 4️⃣ **Identificar las opciones disponibles por queja**

En la columna **Opciones** de cada queja del listado encontrará íconos de acción cuya disponibilidad varía según el estado actual de la queja consultada.

El ícono de ![ver](site:assets/imagenes/saf/iconos/ver.png){:.inline-img} está disponible en todos los estados y permite abrir el formulario de la queja en modo de solo lectura para revisar toda la información registrada por el instructor.

![Ícono Ver queja](site:assets/imagenes/saf/registrarQueja/iconoVer.png){: .clickable-image}

El ícono de ![descargar](site:assets/imagenes/saf/iconos/descargar.png){:.inline-img} está disponible en todos los estados y permite generar y descargar el documento oficial de la queja en formato PDF.

![Ícono Descargar queja](site:assets/imagenes/saf/registrarQueja/iconoDescargar.png){: .clickable-image}

El ícono de ![agendar](site:assets/imagenes/saf/iconos/agendar.png){:.inline-img} está disponible únicamente para quejas en estado **Pendiente** y permite asignar la fecha y hora del comité en el que se atenderá la queja.

![Ícono Agendar queja](site:assets/imagenes/saf/registrarQueja/iconoAgendar.png){: .clickable-image}
![Agendar Queja para comité](site:assets/imagenes/saf/registrarQueja/Agendarcomite.png){: .clickable-image}

El ícono de  ![rechazar](site:assets/imagenes/saf/iconos/rechazar.png){:.inline-img} está disponible únicamente para quejas en estado **Pendiente** y permite registrar una observación que sustente la razón por la cual la queja no procede.

![Ícono Rechazar queja](site:assets/imagenes/saf/registrarQueja/iconoRechazar.png){: .clickable-image}
![Ícono Rechazar queja](site:assets/imagenes/saf/registrarQueja/observacionRechazar.png){: .clickable-image}

El ícono de ![editar](site:assets/imagenes/saf/iconos/editar.png){:.inline-img} está disponible para quejas que ya tienen fecha de comité asignada y permite modificar esa fecha y la observación registrada.

![Ícono Editar queja](site:assets/imagenes/saf/registrarQueja/iconoEditar.png){: .clickable-image}

El ícono de ![eliminar](site:assets/imagenes/saf/iconos/eliminarP.png){:.inline-img} está disponible para quejas que ya tienen fecha de comité asignada y permite eliminar esa fecha, revirtiendo la queja a su estado anterior para poder reagendarla o gestionarla nuevamente.

![Ícono Eliminar fecha de comité](site:assets/imagenes/saf/registrarQueja/iconoEliminar.png){: .clickable-image}

## 5️⃣**Nota importante** 
Los íconos de acción visibles en la columna **Opciones** dependen directamente del estado actual de cada queja. Una queja en estado **Pendiente** mostrará los íconos de ver, descargar, agendar y rechazar. Una queja en estado **Tramitada**, **Agendada** o **En Proceso** con fecha de comité asignada mostrará los íconos de ver, descargar, editar y eliminar. Revise siempre el estado de la queja antes de interpretar las opciones disponibles para cada registro.