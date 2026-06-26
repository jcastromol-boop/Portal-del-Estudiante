### 👤 Integrante: Juan Ignacio Castro Molina
**Rol en el Proyecto:** Diseñador de Interfaz y Flujo de Navegación (UI/UX)

#### Componentes y Funcionalidades Desarrolladas (Maquetación)
En cumplimiento con los requerimientos específicos de accesibilidad y gestión del Centro Nacional de Educación Hellen Keller, se conceptualizaron y diseñaron los esquemas estructurales para dos perfiles de usuario:

1. **Módulo de Registro de Progreso (Vista Docente / Terapeuta)**
   * **Funcionalidad:** Formulario estructurado para la recopilación síncrona de datos y seguimiento de los Planes Educativos Individualizados (PEI).
   * **Componentes de UI:** Control de selección (*Dropdown*) para alternar la ficha activa del estudiante, paneles independientes por áreas de terapia (Comunicación, Motricidad Fina, Habilidades Sociales), matriz de verificación (*Checklist*) para registrar las acciones completadas en la sesión diaria y campo de texto lineal para la bitácora de observaciones del especialista.
   * **Mecanismo de acción:** Control de comando (Botón de guardado) para ejecutar la persistencia del informe diario del alumno.

2. **Portal de Consulta de PEI y Avances (Vista Estudiante / Encargado Legal)**
   * **Funcionalidad:** Interfaz síncrona de solo lectura parametrizada bajo criterios de alta visibilidad para la consulta del estado académico y terapéutico.
   * **Componentes de UI:** Indicadores visuales estáticos (iconografía de verificación que sustituye las casillas de edición), panel de lectura centralizado para las observaciones de la sesión y menú de navegación lateral adaptado para el perfil de consulta.

#### Estructura de Navegación e Interacción (Criterio de Rúbrica)
* **Lógica del Flujo:** El entregable plantea la conexión explícita entre ambas pantallas, definiendo la transición de datos donde el estímulo inicial (*Input*) guardado por el Terapeuta en la interfaz de registro impacta y actualiza automáticamente el contenedor de salida (*Output*) en el portal de consulta del estudiante, garantizando la visibilidad síncrona del progreso pedagógico.
