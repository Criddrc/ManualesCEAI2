# 📘 REGISTRAR CURSOS COMPLEMENTARIOS

La gestión de **Cursos Complementarios** permite al rol de **Coordinador Académico** consultar, registrar y administrar los cursos de formación complementaria del centro. A través de este módulo se pueden crear nuevos cursos, asignar instructores responsables, definir empresas, programas especiales y vincularlos opcionalmente a una ficha titulada, garantizando el control y seguimiento de toda la oferta complementaria del centro.

## 1️⃣ **Acceder al módulo de Cursos Complementarios**

- Asegúrese de haber iniciado sesión en el sistema SAF-CEAI con sus credenciales de **Coordinador Académico**.
- Una vez dentro del sistema, la página principal mostrará el panel de bienvenida con el nombre del usuario y el rol activo en el sistema.
- En el menú lateral izquierdo, localice la sección **Formacion** y haga clic sobre ella para desplegar el submenú. Dentro del submenú, identifique y haga clic en la opción **Cursos Complementaria**. El sistema lo redirigirá a la interfaz de consulta y gestión de cursos complementarios.

![Menú Formación - Cursos Complementaria](site:assets/imagenes/saf/cursosComplementarios/menuCursosComplementarios.png){: .clickable-image}

## 2️⃣ **Consultar Cursos Complementarios existentes**

Al ingresar, el sistema presenta el formulario **Consultar Cursos Complementarios** en la parte superior. Este formulario permite buscar cursos registrados previamente utilizando diferentes criterios de búsqueda antes de crear uno nuevo.

![Formulario Consultar Cursos Complementarios](site:assets/imagenes/saf/cursosComplementarios/formularioConsulta.png){: .clickable-image}

- **Id-Curso:** Permite ingresar el identificador numérico del curso si se conoce previamente. 
- **Ficha:** Permite buscar por el número de ficha asociado al curso. 
- **Fecha de inicio y Fecha Fin:** Permiten delimitar la búsqueda por rango de fechas en formato aaaa-mm-dd. 
- **Programa de Formación:** Cuenta con un ícono de búsqueda ![buscar](site:assets/imagenes/saf/iconos/lupa.png){:.inline-img} que abre la ventana emergente de consulta de programas. 
- **Instructor:** Muestra por defecto la opción TODOS y permite filtrar por instructor responsable. 
- **Empresa:** Permite filtrar los cursos por la empresa contratante. 
- **Ficha SOFIA:** Permite filtrar por la ficha registrada en el sistema SOFÍA Plus.

Una vez definidos los filtros, haga clic en el botón ![consultar](site:assets/imagenes/saf/iconos/consultar.png){:.inline-img}. para ver los resultados. Si desea crear un nuevo curso complementario, haga clic en el botón ![nuevo](site:assets/imagenes/saf/iconos/nuevo.png){:.inline-img}. También puede descargar un reporte de los cursos consultados haciendo clic en el botón ![Descargar Reporte Cursos](site:assets/imagenes/saf/iconos/DescargarReporteCursos.png){:.inline-img}.

## 3️⃣ **Buscar el Programa de Formación Complementaria**

Al hacer clic en el ícono de búsqueda ![buscar](site:assets/imagenes/saf/iconos/lupa.png){:.inline-img} del campo **Programa de Formación**, ya sea en el formulario de consulta o en el formulario de registro, el sistema abrirá una ventana emergente titulada **Programa de Formacion** con el formulario **Consultar Programa de Formación**.

![Ventana Consultar Programa de Formación - vacía](site:assets/imagenes/saf/cursosComplementarios/modalProgramaVacio.png){: .clickable-image}

La ventana presenta tres campos de búsqueda: **Código**, donde puede ingresar el código numérico del programa; **Nombre**, donde puede escribir el nombre o parte del nombre del programa complementario; y **Acrónimo**, donde puede ingresar la sigla del programa. Ingrese el criterio de búsqueda y haga clic en el botón **Consultar** dentro de la ventana.

El sistema mostrará el **Listado Programas de Formación** con los resultados encontrados. Cada registro presenta el identificador interno, el código, el nombre completo, el acrónimo, la versión, el nivel de formación y el área de formación. En la columna **Opciones** aparece el ícono de verificación ![check](site:assets/imagenes/saf/iconos/check.png){:.inline-img} para seleccionar el programa deseado.

![Ventana Consultar Programa de Formación - con resultados](site:assets/imagenes/saf/cursosComplementarios/modalProgramaResultados.png){: .clickable-image}

Haga clic en el ícono de verificación ![check](site:assets/imagenes/saf/iconos/check.png){:.inline-img} del programa que desea registrar. La ventana se cerrará automáticamente y el programa quedará cargado en el campo del formulario principal. Si desea cancelar la búsqueda sin seleccionar ningún programa, haga clic en el botón **Cerrar** ubicado en la esquina inferior derecha de la ventana.

## 4️⃣ **Registrar un nuevo Curso Complementario**

Para crear un nuevo curso, haga clic en el botón ![nuevo](site:assets/imagenes/saf/iconos/nuevo.png){:.inline-img} del formulario de consulta. El sistema abrirá el formulario **Registro - Cursos complementarios**.

![Formulario Registro Cursos Complementarios](site:assets/imagenes/saf/cursosComplementarios/formularioRegistro.png){: .clickable-image}

> **Campos obligatorios:** El formulario indica con un asterisco (*) los campos que son de diligenciamiento obligatorio. No será posible guardar el registro si alguno de estos campos está vacío.

Diligencie el formulario con la siguiente información:

- **Ficha:** Ingrese el número de ficha si el curso complementario está asociado a una ficha. Este campo no es obligatorio.
- **Codigo Inscripcion:** Ingrese el código de inscripción del curso si aplica. Este campo no es obligatorio.
- **Fecha Inicio \*:** Ingrese la fecha de inicio del curso en formato aaaa-mm-dd. Este campo es obligatorio.
- **Fecha Fin \*:** Ingrese la fecha de finalización del curso en formato aaaa-mm-dd. Este campo es obligatorio.
- **Cupo \*:** Ingrese el número máximo de participantes que tendrá el curso. El sistema muestra por defecto el valor 30. Este campo es obligatorio.
- **Programa de Formación \*:** Haga clic en el ícono de búsqueda ![buscar](site:assets/imagenes/saf/iconos/lupa.png){:.inline-img} para abrir la ventana emergente y seleccionar el programa de formación complementaria correspondiente. Este campo es obligatorio.
- **Instructor Responsable \*:** Haga clic en la flecha desplegable ![desplegable](site:assets/imagenes/saf/iconos/desplegable.png){:.inline-img} y seleccione el instructor responsable de dictar el curso. Este campo es obligatorio.
- **Empresa \*:** Haga clic en la flecha desplegable ![desplegable](site:assets/imagenes/saf/iconos/desplegable.png){:.inline-img} y seleccione la empresa contratante o beneficiaria del curso complementario. Este campo es obligatorio.
- **Ciudad \*:** Haga clic en la flecha desplegable ![desplegable](site:assets/imagenes/saf/iconos/desplegable.png){:.inline-img} y seleccione la ciudad donde se realizará el curso. El sistema muestra por defecto la ciudad del centro de formación. Este campo es obligatorio.
- **Programa Especial \*:** Haga clic en la flecha desplegable ![desplegable](site:assets/imagenes/saf/iconos/desplegable.png){:.inline-img} y seleccione si el curso pertenece a algún programa especial. El sistema muestra por defecto la opción **NINGUNO**. Este campo es obligatorio.
- **Coordinador:** Haga clic en la flecha desplegable ![desplegable](site:assets/imagenes/saf/iconos/desplegable.png){:.inline-img} y seleccione el coordinador responsable del seguimiento del curso. Este campo no es obligatorio.
- **Está asociado a una ficha titulada:** Si el curso complementario está vinculado a una ficha de formación titulada, marque esta casilla. Al activarla, el sistema habilitará los campos necesarios para asociar la ficha correspondiente.

## 5️⃣ **Guardar el registro**

Una vez diligenciados todos los campos obligatorios, haga clic en el botón ![Guardar](site:assets/imagenes/saf/iconos/guardar.png){:.inline-img} ubicado en la parte inferior izquierda del formulario. El sistema validará la información ingresada y guardará el nuevo curso complementario. 

![Botones Guardar](site:assets/imagenes/saf/cursosComplementarios/botonGuardar.png){: .clickable-image}

## 6️⃣ **Nota importante:** 
Una vez guardado el curso complementario, el Coordinador Académico podrá aprobar el curso desde el módulo **Horario**, opción **Crear Horario Complementaria**, donde se asignan los días, horas, ambiente de formación y actividad correspondientes a la programación del curso. Para aprobar el curso complementario, haga clic [Crear Horario Curso Complementario](./horarioCursoComplementario.md).
