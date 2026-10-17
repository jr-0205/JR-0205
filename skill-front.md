---
description: Guía de diseño e implementación frontend para crear
  interfaces web dark, minimalistas, premium y tecnológicas, con
  jerarquía visual clara y funcionalidad real.
name: dark-premium-frontend
---

# Skill: Dark Premium Frontend

## Propósito

Diseña e implementa interfaces frontend con una identidad visual **dark
premium, minimalista, tecnológica y profesional**. El resultado debe
parecer un producto digital cuidadosamente diseñado ---por ejemplo, una
plataforma SaaS o un panel administrativo de alta calidad--- y no una
plantilla genérica con fondo negro.

Aplica esta guía a landing pages, dashboards, paneles CRUD, herramientas
internas, aplicaciones web, portales administrativos y prototipos
funcionales.

## Dirección visual

### Principios obligatorios

1.  **Minimalismo con intención:** cada elemento debe cumplir una
    función. Evita adornos que no mejoren la comprensión, la navegación
    o la identidad.
2.  **Dark elegante:** prioriza negro suave, grafito y grises neutros.
    No uses negro absoluto en todas las superficies si eso aplana la
    interfaz.
3.  **Acentos controlados:** utiliza azul profundo o azul acero para
    acciones y estados relevantes. El color de acento debe guiar la
    atención, no dominar toda la pantalla.
4.  **Jerarquía clara:** diferencia títulos, subtítulos, contenido,
    metadatos y acciones mediante tamaño, peso, contraste y espaciado.
5.  **Espacio negativo:** deja respirar los componentes. No llenes cada
    zona disponible con tarjetas, líneas o texto.
6.  **Acabado preciso:** cuida alineaciones, alturas, espaciado, radios,
    bordes, estados y consistencia entre componentes.
7.  **Funcionalidad real:** no presentes controles decorativos como si
    funcionaran. Los botones, formularios, filtros, menús y modales
    deben comportarse según lo esperado.
8.  **Responsive por diseño:** la interfaz debe funcionar en móvil,
    tableta y escritorio, no limitarse a encogerse.

## Paleta de referencia

Usa estos valores como punto de partida y ajústalos si el proyecto ya
tiene una identidad de marca definida:

-   Fondo principal: `#0A0A0B`
-   Superficie secundaria: `#111216`
-   Tarjetas y paneles: `#191A1E`
-   Superficie elevada o hover: `#22242A`
-   Borde sutil: `#30323A`
-   Texto principal: `#F2F3F5`
-   Texto secundario: `#A3A7B0`
-   Texto tenue: `#777D88`
-   Azul profundo: `#254A7A`
-   Azul de acción: `#4D8DDB`
-   Plata neutra: `#B5BAC4`

### Uso del color

-   Mantén la mayor parte de la interfaz en tonos neutros.
-   Reserva el azul para acciones primarias, enlaces importantes, foco y
    selección.
-   Usa rojo, ámbar y verde solo para estados semánticos como error,
    advertencia y éxito.
-   Comprueba que el texto tenga contraste suficiente.
-   No uses gradientes brillantes, neones ni sombras coloreadas como
    recurso predeterminado.
-   No conviertas todos los elementos en azul solo para que la interfaz
    parezca tecnológica.

## Tipografía

-   Prioriza familias legibles y contemporáneas como Inter, Geist,
    Manrope o una alternativa disponible en el proyecto.
-   Usa una escala tipográfica consistente.
-   Los títulos deben tener presencia sin ser gigantes por defecto.
-   Evita utilizar demasiados pesos o tamaños distintos.
-   Mantén los textos secundarios legibles; no uses gris tenue para
    información esencial.
-   Para cifras, métricas y tablas, prioriza lectura rápida y alineación
    consistente.

## Composición y layout

-   Define una cuadrícula y un sistema de espaciado coherente.
-   Alinea títulos, controles, tarjetas y tablas con precisión.
-   Utiliza contenedores con un ancho adecuado al contenido.
-   Evita anidar tarjetas dentro de tarjetas sin una razón funcional.
-   No conviertas cada sección en una caja con borde.
-   Prefiere separadores discretos y diferencias sutiles de superficie.
-   Mantén las acciones principales en ubicaciones previsibles.
-   Usa asimetría o composiciones editoriales cuando aporten carácter;
    no sacrifiques usabilidad por originalidad.

## Componentes

### Botones

-   Establece variantes claras: primario, secundario, terciario y
    destructivo.
-   Define estados `hover`, `focus-visible`, `active`, `disabled` y
    `loading`.
-   Mantén alturas, radios y espaciados consistentes.
-   Evita botones gigantes o con efectos innecesarios.
-   El texto debe describir la acción con claridad.

### Formularios

-   Cada campo debe tener una etiqueta visible y comprensible.
-   Incluye estados de foco, error, deshabilitado y validación.
-   Muestra mensajes de error cerca del campo correspondiente.
-   No dependas exclusivamente del color para comunicar errores.
-   Respeta el tipo de dato y utiliza controles adecuados.
-   Conserva los valores introducidos cuando ocurra un error
    recuperable.

### Tarjetas y métricas

-   Úsalas para agrupar información relacionada, no como decoración.
-   Presenta las métricas con etiqueta, valor y contexto cuando sea
    necesario.
-   Evita iconos enormes, sombras fuertes y fondos saturados.
-   Asegura que las tarjetas mantengan una jerarquía coherente.

### Tablas y CRUD

-   Prioriza legibilidad, alineación y densidad apropiada.
-   Distingue encabezados, filas, acciones y estados sin exceso de
    líneas.
-   Añade búsqueda, filtros, ordenamiento, paginación o estados vacíos
    cuando el caso de uso lo requiera.
-   Confirma las acciones destructivas.
-   Ofrece retroalimentación visible tras crear, actualizar o eliminar
    registros.
-   En móvil, usa desplazamiento horizontal controlado o una
    representación alternativa útil.

### Navegación

-   Mantén la navegación predecible y jerárquica.
-   En dashboards, usa una barra lateral o navegación superior solo si
    mejora la estructura.
-   Marca claramente la sección activa.
-   Evita menús saturados y etiquetas ambiguas.
-   Incluye estados accesibles de foco y selección.

### Iconografía

-   Usa una sola familia de iconos siempre que sea posible.
-   Mantén tamaño, grosor y alineación consistentes.
-   Prefiere iconos reconocibles y funcionales.
-   No sustituyas todas las etiquetas por iconos sin texto o ayuda
    contextual.

## Movimiento y microinteracciones

-   Usa animaciones cortas y discretas para hover, apertura de menús,
    modales y cambios de estado.
-   El movimiento debe comunicar respuesta o continuidad, no distraer.
-   Evita parallax, partículas, efectos de cursor, brillos pulsantes y
    animaciones continuas salvo que el proyecto los justifique
    explícitamente.
-   Respeta `prefers-reduced-motion`.
-   No animes propiedades costosas si puede lograrse el mismo efecto con
    `transform` u `opacity`.

## Reglas para evitar resultados genéricos

No hagas lo siguiente por defecto:

-   Usar el típico gradiente morado-azul de plantilla SaaS.
-   Añadir emojis a interfaces profesionales.
-   Llenar el hero con esferas luminosas, blobs, rejillas decorativas o
    efectos de cristal.
-   Aplicar `backdrop-filter: blur()` a todos los paneles.
-   Dar a cada elemento una sombra, borde brillante o radio excesivo.
-   Crear una cuadrícula de tarjetas idénticas para todo tipo de
    contenido.
-   Usar texto de relleno, métricas inventadas o botones sin
    comportamiento.
-   Añadir secciones que el usuario no pidió solo para que la página
    parezca más grande.
-   Introducir dependencias innecesarias para resolver tareas sencillas.
-   Cambiar la arquitectura o el stack existente sin una razón clara.

Los efectos visuales especiales no están prohibidos, pero deben ser
deliberados, escasos y coherentes con la identidad del producto.

## Criterios de implementación

Antes de escribir código:

1.  Identifica el propósito de la pantalla y la acción principal del
    usuario.
2.  Revisa el stack, los componentes y las convenciones existentes.
3.  Define la jerarquía de contenido y los estados que necesita la
    interfaz.
4.  Reutiliza el sistema de diseño del proyecto si existe.
5.  Si falta información no crítica, toma una decisión razonable y
    continúa. Pregunta solo cuando una decisión bloqueante pueda cambiar
    significativamente el resultado.

Durante la implementación:

-   Respeta el stack y las versiones existentes.
-   Separa componentes cuando mejoren la reutilización o la legibilidad;
    no fragmentes en exceso.
-   Usa nombres descriptivos y estructura mantenible.
-   Evita duplicación, estilos contradictorios y valores arbitrarios
    repetidos.
-   Implementa estados de carga, error, vacío y éxito cuando
    corresponda.
-   No finjas persistencia ni conectividad con datos reales si no están
    implementadas.
-   Si utilizas datos de ejemplo, identifícalos como tales.
-   No elimines funcionalidades existentes al rediseñar una pantalla.

### Tecnología

La guía es independiente del framework. Adáptala al proyecto existente:

-   **React / Next.js:** componentes reutilizables y estado bien
    definido.
-   **Tailwind CSS:** tokens y utilidades consistentes; evita clases
    arbitrarias repetidas cuando convenga extraer componentes.
-   **Bootstrap:** personaliza variables, componentes y estados para
    evitar la apariencia predeterminada de Bootstrap.
-   **CSS puro:** utiliza variables CSS para colores, tipografía,
    radios, sombras y espaciado.
-   **HTML, CSS y JavaScript:** prioriza semántica, accesibilidad y
    funcionamiento sin dependencias innecesarias.

No impongas una tecnología si el usuario o el repositorio ya establecen
otra.

## Accesibilidad y calidad

-   Usa HTML semántico y etiquetas asociadas correctamente a sus
    controles.
-   Permite la navegación por teclado.
-   Mantén visible el indicador de foco.
-   Añade nombres accesibles a controles que solo tengan iconos.
-   Usa `alt` útil para imágenes informativas y `alt=""` para imágenes
    decorativas.
-   No dependas exclusivamente del color para transmitir significado.
-   Respeta preferencias de movimiento reducido.
-   Verifica contraste, desbordamientos, formularios y estados
    interactivos.
-   Evita errores de consola y advertencias relevantes.

## Responsive

Comprueba como mínimo:

-   **Móvil:** una columna cuando corresponda, controles utilizables con
    el dedo y navegación adaptada.
-   **Tableta:** uso equilibrado del espacio y componentes sin
    compresión excesiva.
-   **Escritorio:** aprovechamiento del ancho sin líneas de texto
    demasiado largas.
-   Tablas, modales, formularios, barras laterales y menús en tamaños
    estrechos.
-   Ausencia de desbordamiento horizontal accidental.

## Entrega esperada

Cuando se solicite construir una interfaz:

1.  Entrega una solución completa y ejecutable dentro del alcance
    pedido.
2.  Incluye el código necesario, no fragmentos inconexos, salvo que el
    usuario solicite solo una parte.
3.  Explica brevemente cómo ejecutar o integrar el resultado si no es
    obvio.
4.  Señala con claridad cualquier integración simulada, dato de ejemplo
    o requisito pendiente.
5.  No afirmes que probaste, ejecutaste o verificaste algo si no lo
    hiciste.

## Lista de verificación antes de finalizar

-   [ ] La interfaz se ve premium y deliberada, no como una plantilla
    genérica.
-   [ ] La paleta es sobria y el azul se usa con moderación.
-   [ ] La jerarquía visual y los espacios son consistentes.
-   [ ] Los componentes comparten un lenguaje visual.
-   [ ] Los controles importantes funcionan.
-   [ ] Hay estados de carga, vacío, error y éxito cuando corresponden.
-   [ ] La interfaz funciona en móvil y escritorio.
-   [ ] La navegación por teclado y el foco son visibles.
-   [ ] No hay adornos, dependencias ni secciones innecesarias.
-   [ ] No se han eliminado funciones existentes.
-   [ ] Las limitaciones y los datos simulados están declarados.

## Instrucción corta para incorporar en prompts

> Aplica la skill `dark-premium-frontend`: diseña una interfaz dark
> premium, minimalista, tecnológica y profesional, con fondos negros y
> grafito, superficies diferenciadas, tipografía moderna, espaciado
> preciso y acentos azul profundo usados con moderación. Evita la
> estética SaaS genérica, los neones, los gradientes gratuitos y las
> decoraciones innecesarias. Prioriza jerarquía visual, accesibilidad,
> responsive y funcionalidad real. Respeta el stack existente, reutiliza
> componentes y entrega código completo, mantenible y ejecutable. No
> simules funcionalidades sin indicarlo.
