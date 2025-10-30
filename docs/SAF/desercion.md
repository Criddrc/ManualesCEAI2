---
---
# NOVEDAD DESERCIÓN DE APRENDICES

El siguiente es el protocolo que se debe seguir para registrar una novedad de cancelación por deserción en el aplicativo SAF. Intervienen los siguientes roles: Instructor, Apoyo Coordinación, Coordinación Académica, Coordinación de Formación y Aprendiz

## 1️⃣ Registrar Solicitud de Cancelación por Deserción (Instructor)

El instructor ingresa al listado de aprendices y activa la opción **"Solicitar cancelación"**. SAF valida que el aprendiz tenga **3** días consecutivos de faltas. Si no es así, el instructor podrá continuar con la novedad registrando el rango de fechas de inasistencia del aprendiz. El aprendiz queda resaltado con color azul y la novedad inicia con estado **"Solicitada"**.

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/1-desercion_registro_instructor_1.png)
</figure>

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/2-desercion_registro_instructor_2.png)
</figure>

## 2️⃣ Consultar novedad (Apoyo a coordinación)

El apoyo a coordinación ingresa al módulo de novedades y consulta la novedad registrada usando los filtros disponibles: 

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/3-novedades_filtros.png)
</figure>

Cuando el sistema devuelva el resultado de la consulta, el usuario (coordinadores, apoyo a coordinación o administrador) tiene las siguientes opciones para la novedad del aprendiz: ver los detalles de la novedad, cancelar la novedad, editar la novedad o reiniciar la novedad.

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/4-novedades_opciones.png)
</figure>

**Opciones:**

- **Ver detalles de la novedad**: El usuario puede visualizar la información relacionada con la novedad haciendo clic en el ícono de la lupa "<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/5.x/svgs/solid/search.svg" class="off-glb" width="15px">".

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/5-novedades_detalle.png)
</figure>

- **Editar la novedad**: Se usa para registrar un paso dentro del proceso de la novedad que cambiará el estado de la misma. El usuario debe hacer clic en el ícono del lapiz "<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/5.x/svgs/solid/edit.svg" class="off-glb" width="15px">" y SAF habilita un formulario de edición de la novedad.

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/6-novedades_editar.png)
</figure>

- **Cancelar la novedad**: Se usa para cancelar una novedad que no debe continuar por solicitud del coordinador académico o del instructor que registró la solicitud. El apoyo a coordinación o administrador deben hacer clic en el ícono de la equis "<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/5.x/svgs/solid/times.svg" class="off-glb" width="11px">".

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/7-novedades_cancelar.png)
</figure>

## 3️⃣ Aceptar o rechazar la novedad (Apoyo a coordinación)

El apoyo a coordinación selecciona en el campo **"Aprobar Solicitud"** la opción **Aprobar** o **Rechazar** según el protocolo. Para completar la acción debe hacer clic en el botón "Registrar". Si desea puede usar el campo "Observaciones" para completar la información.

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/8-desercion_aprobar_solicitud.png)
</figure>

- Si aprueba la novedad, el estado cambia a **"En trámite"**.
- Si la novedad es rechazada, cambia a **"Cancelada"** y termina el proceso.


## 4️⃣ Aprobar la novedad desde Coordinación Académica (Coordinador Académico)

El coordinador debe ingresar por la opción **"Gestión de Novedades -> Novedades de Aprendices"**. En esta vista, el coordinador selecciona **"Firmar deserciones coordinador académico"** usando el filtro **"Momento de la Novedad"** (además puede hacer uso del resto de filtros en caso de necesitar realizar una consulta más precisa).

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/9-desercion_filtro_firmar_academico.png)
</figure>

Una vez ajustados los filtros, se debe hacer clic en el botón **"Consultar"**. Esto mostrará las novedades que cumplan con los filtros. El coordinador debe seleccionar si aprueba o rechaza la novedad usando las casillas **"Aprobar Coordinador Académico"** o **"Rechazar Coordinador Académico"**.

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/10-desercion_firmar_academico.png)
</figure>

Después de seleccionar las novedades a aprobar/rechazar se debe hacer clic en el botón **"guardar"**. La novedad cambiará a uno de los siguientes estados:
- **Aprobada coordinador académico**: Si el coordinador académico aprueba la novedad, pero aún falta la aprobación del **coordinador de formación**.
- **Novedad cancelada**: Si el coordinador rechaza la novedad.
- **Aprobada coordinación**: Si tanto el coordinador académico como el de formación han aprobado la novedad.

## 5️⃣ Aprobar la novedad desde Coordinación de Formación (Coordinador de Formación)

El coordinador debe ingresar por la opción **"Gestión de Novedades -> Novedades de Aprendices"**. En esta vista, selecciona **"Firmar deserciones coordinador formación"** usando el filtro **"Momento de la Novedad"** (además puede usar el resto de filtros para realizar consultas más precisas).

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/11-desercion_filtro_firmar_formacion.png)
</figure>

Una vez ajustados los filtros, se debe hacer clic en el botón **"Consultar"**. En los resultados mostrados, el coordinador debe seleccionar si aprueba o rechaza la novedad usando las casillas **"Aprobar Coordinador Formación"** o **"Rechazar Coordinador Formación"**.

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/12-desercion_firmar_formacion.png)
</figure>

Después de seleccionar las novedades a aprobar/rechazar se debe hacer clic en el botón **"guardar"**.La novedad pasará a uno de los siguientes estados:
- **Aprobada coordinador formación**: Si el coordinador formación aprueba la novedad, pero aún falta la aprobación del **coordinador académico**.
- **Novedad cancelada**: Si el coordinador rechaza la novedad.
- **Aprobada coordinación**: Si ambos coordinadores aprueban la novedad.

## 6️⃣ Notificación al aprendiz (Apoyo a coordinación)

Una vez la novedad se encuentra en estado **"Aprobada coordinación"**, el apoyo debe notificar al aprendiz solicitándole la entrega de evidencias que soporten la deserción. Esto se realiza mediante el envío de la carta **"Solicitud Soportes Incumplimientos"**. Para esto ingresa a consultar la ficha desde el menú de Formación - Cursos Titulada y hace clic en la opción "Descargar carta novedad" para el aprendiz respectivo. El apoyo puede descargar varias cartas de forma masiva seleccionando los aprendices.

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/13-descargar_carta_evidencias.png)
</figure>

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/14-desercion_notificacion_solicitud_evidencias.png)
</figure>

Cuando el apoyo notifica al aprendiz debe registrar en SAF esta acción para que el sistema inicie el conteo respectivo. El aprendiz cuenta con 5 días hábiles para entregar los soportes. De lo contrario, la novedad pasará automáticamente al estado **"Evidencias no presentadas"**.

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/15-estado_aprendiz_notificado.png)
</figure>

## 7️⃣ Revisar soportes de incumplimiento (Coordinador académico)

Si el aprendiz presenta los soportes, el coordinador debe ingresar por la opción **"Gestión de Novedades -> Novedades de Aprendices"**. En esta vista, selecciona **"Revisar evidencias deserción"** usando el filtro **"Momento de la Novedad"**.

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/16-desercion_filtro_revisar_evidencias.png)
</figure>

En este paso, el coordinador descarga los soportes usando el botón **"Descargar"**. Después de revisar las evidencias, debe aprobarlas o rechazarlas según corresponda, haciendo clic en el check que aplique.

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/17-desercion_revision_evidencias.png)
</figure>

Despues de aprobar o rechazar la novedad, se debe hacer clic en el boton **"guardar"**. Esto cambiará la novedad a uno de los siguientes estados:
- **Novedad cancelada**: Si los soportes son aprobados, la novedad se cancela y termina.
- **Evidencias rechazadas**: Si los soportes son rechazados, la novedad continúa.

## 8️⃣ Completar información de la novedad (Apoyo a coordinación)

En cualquiera de los casos, evidencias rechazadas o no presentadas, el apoyo a coordinación debe editar la novedad y completar los campos **"Número Solicitud de Radicado"**, **"Número Respuesta Radicado"**, **"Fecha de Respuesta"**, **"Fecha de Activación"** y **"Duración"**.

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/18-desercion_evidencias_rechazadas_o_no_presentadas.png)
</figure>

Una vez completados los campos, se debe dar clic en el botón **"Registrar"**. Esto pasará la novedad al estado **"En espera de recurso"** y enviará un correo al aprendiz notificando que debe presentar un recurso a través de PQR. Adjuntamente, se envía el formato **"Notificación por Aviso"**.

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/19-desercion_notificacion_por_aviso.png)
</figure>

Una vez notificado, el aprendiz cuenta con 10 días hábiles para presentar el recurso. De lo contrario, la novedad pasará automáticamente al estado **"Recurso no presentado"**.

## 9️⃣ Cargar recurso de reposición (Apoyo a coordinación)

[Presentar recurso](./cargarrecurso.md)

## 🔟 Pasar novedad a Pendiente SOFIA

En cualquier caso, "Recurso no presentado" o "Recurso rechazado" el apoyo debe editar la novedad y seleccionar la opción "Enviar a SOFIA". La novedad pasará a estado **"Pendiente SOFIA"**


## 1️⃣1️⃣ Finalizar novedad

SAF notifica a SOFIA a través de correo sobre la novedad. Cuando el equipo SOFIA reporte el tramitado de la novedad, se debe proceder a finalizarla en SAF. El apoyo a coordinación edita la novedad y selecciona la opción **"Tramitada"** en el campo **"Estado de la solicitud"** y completa el campo **"Fecha en la que se reportó la novedad en SOFIA"**. Hacer clic en el botón Registrar

<figure markdown="span">
	![Image title](site:assets/imagenes/desercion/novedad_desercion/20-desercion_tramitada.png)
</figure>
