---
name: cinematic-streaming-ui
description: Guía para diseñar y desarrollar aplicaciones y páginas de streaming inspiradas en la experiencia cinematográfica de Netflix, con identidad propia, navegación fluida y catálogos visuales.
---

# Skill: Cinematic Streaming UI

## 1. Propósito

Diseña e implementa interfaces para plataformas de streaming de películas, series, documentales, anime y contenido audiovisual.

Inspírate en la experiencia de usuario de Netflix: catálogos visuales, portadas cinematográficas, carruseles horizontales, recomendaciones, navegación intuitiva y continuidad de reproducción.

El resultado debe sentirse como una plataforma de entretenimiento premium: inmersiva, elegante, moderna, fluida y profesional.

Esta skill puede aplicarse a:
- Páginas de streaming.
- Aplicaciones web de películas y series.
- Catálogos multimedia.
- Plataformas VOD.
- Interfaces de reproducción de video.
- Dashboards de administración de contenido audiovisual.
- Prototipos funcionales de servicios de streaming.

La referencia a Netflix es exclusivamente visual y funcional. Crea una identidad de marca propia, sin copiar literalmente sus logotipos, recursos gráficos o identidad comercial.

## 2. Filosofía de diseño

La interfaz debe cumplir los siguientes principios:

1. El contenido audiovisual es el protagonista.
2. La interfaz debe ser oscura, cinematográfica y elegante.
3. La navegación debe resultar intuitiva desde el primer momento.
4. Las portadas deben tener una presentación visual atractiva y consistente.
5. Las animaciones deben ser suaves, rápidas y discretas.
6. La composición debe tener profundidad sin abusar de efectos.
7. Los componentes deben ser funcionales, no meramente decorativos.
8. El diseño debe adaptarse a escritorio, tableta y móvil.
9. La experiencia debe priorizar rendimiento, accesibilidad y facilidad de uso.
10. Cada decisión visual debe contribuir a la experiencia de entretenimiento.

## 3. Identidad visual

### Estética general

Utiliza una estética dark premium con una atmósfera cinematográfica.

Prioriza:
- Fondos negros y tonos carbón.
- Superficies secundarias discretas.
- Texto blanco y gris de alto contraste.
- Imágenes panorámicas de gran impacto visual.
- Pósteres con proporciones correctas.
- Degradados oscuros para mejorar la legibilidad.
- Bordes sutiles y radios moderados.
- Espaciado consistente.
- Transiciones elegantes.
- Jerarquía visual clara.

Evita interfaces excesivamente cargadas, elementos innecesarios y efectos visuales que compitan con las películas y series.

### Paleta de colores

Utiliza esta paleta como referencia inicial:

- Fondo principal: #09090B
- Fondo de navegación: #101014
- Superficie secundaria: #18181D
- Superficie elevada: #24242B
- Bordes sutiles: #303038
- Texto principal: #F5F5F7
- Texto secundario: #B5B5BE
- Texto tenue: #85858F
- Acento rojo de referencia: #E50914
- Acento alternativo dorado: #E6B85C

El rojo es una opción de referencia, no una obligación. Si el proyecto tiene una marca propia, adapta la paleta a ella.

Usa el color de acento principalmente para:
- Botones principales.
- Indicadores de selección.
- Estados activos.
- Barras de progreso.
- Elementos de navegación importantes.

No utilices colores saturados en todos los componentes.

Evita neones, gradientes gratuitos y sombras luminosas excesivas.

## 4. Tipografía

Prioriza tipografías modernas y legibles como:
- Inter.
- Geist.
- Manrope.
- Fuentes equivalentes disponibles en el proyecto.

Los títulos deben tener presencia cinematográfica sin comprometer la legibilidad.

Mantén una jerarquía consistente entre:
- Títulos principales.
- Nombres de películas y series.
- Encabezados de categorías.
- Sinopsis.
- Metadatos.
- Botones.
- Etiquetas secundarias.

Evita utilizar demasiados tamaños, pesos o estilos tipográficos.

Los metadatos deben ser compactos y fáciles de leer.

## 5. Barra de navegación

La navegación debe ser sencilla, elegante y predecible.

Puede incluir:
- Logotipo o nombre de la plataforma.
- Inicio.
- Series.
- Películas.
- Categorías.
- Mi lista.
- Búsqueda.
- Perfil de usuario.
- Configuración.

En escritorio, utiliza una navegación horizontal cuando exista espacio suficiente.

En móvil, adapta la navegación mediante un menú compacto o una barra inferior si mejora la experiencia.

El menú puede comenzar con un fondo transparente sobre el hero y adquirir un fondo oscuro sólido al desplazarse, siempre que se mantenga legible.

Incluye:
- Indicador de sección activa.
- Estados hover.
- Foco visible para teclado.
- Acciones claramente identificables.

No escondas funciones esenciales en menús difíciles de descubrir.

## 6. Hero cinematográfico

El hero es la sección visual principal de la página de inicio.

Debe destacar una película, serie o colección relevante.

### Composición

- Utiliza una imagen panorámica de alta calidad.
- Prioriza proporciones cercanas a 16:9 o más amplias.
- Permite que la imagen ocupe una parte importante de la pantalla.
- Aplica un degradado oscuro lateral o inferior para mejorar la legibilidad.
- Evita colocar texto importante sobre zonas visualmente saturadas.
- Mantén una transición visual natural entre el hero y el catálogo.

### Contenido

Incluye únicamente la información disponible y relevante:

- Título.
- Sinopsis breve.
- Género.
- Año.
- Duración o temporadas.
- Botón de reproducción.
- Botón para consultar detalles.
- Acción para añadir a la lista, si está implementada.

El hero debe captar la atención sin impedir que el usuario acceda rápidamente al catálogo.

No añadas demasiados botones ni descripciones extensas.

No reproduzcas audio automáticamente al cargar la página.

## 7. Catálogo de películas y series

Organiza el contenido mediante filas horizontales.

Categorías posibles:

- Continuar viendo.
- Tendencias.
- Recomendados.
- Estrenos.
- Películas populares.
- Series.
- Anime.
- Documentales.
- Por género.
- Mi lista.

Utiliza únicamente las categorías que tengan sentido para el proyecto y los datos disponibles.

Cada fila debe tener:
- Título identificable.
- Tarjetas consistentes.
- Espaciado uniforme.
- Desplazamiento horizontal cuando corresponda.
- Controles de navegación cuando sean útiles.

Evita repetir categorías sin sentido o llenar la interfaz con contenido de relleno.

## 8. Tarjetas de contenido

Las tarjetas son uno de los componentes más importantes de una plataforma de streaming.

### Proporciones

- Películas y series: formato vertical aproximado de 2:3.
- Avances y episodios: formato panorámico cuando el material lo requiera.
- Banners: formato horizontal amplio.

Nunca deformes las imágenes.

Utiliza `object-fit: cover` cuando sea apropiado y conserva un encuadre visual intencional.

### Interacción

En escritorio:
- Permite una ampliación sutil al pasar el cursor.
- Puedes mostrar detalles adicionales.
- Mantén las animaciones breves.
- Evita que las tarjetas se superpongan de forma caótica.

En dispositivos táctiles:
- No dependas del hover.
- Permite abrir detalles mediante toque.
- Conserva controles accesibles y fáciles de utilizar.

### Información

Muestra solo los metadatos disponibles:
- Título.
- Año.
- Género.
- Clasificación.
- Duración.
- Temporadas.
- Progreso de reproducción.

No sobrecargues la tarjeta con demasiados elementos.

Las tarjetas deben tener estados coherentes para contenido guardado, seleccionado o parcialmente visto.

## 9. Carruseles horizontales

Los carruseles deben ofrecer una experiencia fluida.

Implementa, cuando corresponda:
- Desplazamiento horizontal.
- Navegación mediante flechas.
- Gestos táctiles.
- Compatibilidad con trackpad.
- Espaciado uniforme.
- Foco visible.
- Desplazamiento hasta elementos seleccionados.

No permitas que las flechas oculten las portadas.

No bloquees el desplazamiento vertical de la página para forzar el movimiento horizontal.

En móvil, prioriza los gestos táctiles y deja suficiente contenido visible para indicar que existen más elementos.

Evita saltos de diseño durante la carga de imágenes reservando dimensiones para cada tarjeta.

Los carruseles deben poder utilizarse con teclado y tecnologías de asistencia.

## 10. Detalles de películas y series

Al seleccionar una obra, muestra una página o modal con información relevante.

Puede incluir:
- Portada o imagen principal.
- Título.
- Sinopsis.
- Año.
- Género.
- Duración.
- Temporadas.
- Episodios.
- Acciones de reproducción.
- Acción para añadir a Mi lista.
- Contenido relacionado.

Para las series, organiza los episodios por temporada cuando existan esos datos.

La información debe ser legible y estar organizada visualmente.

No inventes puntuaciones, reparto, disponibilidad ni metadatos presentados como reales.

Si utilizas contenido de demostración, identifícalo como tal.

## 11. Búsqueda y descubrimiento

Implementa una experiencia de búsqueda clara.

Cuando corresponda, incluye:
- Campo de búsqueda.
- Resultados filtrados.
- Búsqueda por título.
- Filtros por género.
- Filtros por tipo de contenido.
- Filtros por año.
- Sugerencias.
- Estado sin resultados.
- Acción para limpiar filtros.

La búsqueda debe funcionar con los datos reales disponibles en el proyecto.

No presentes filtros o sugerencias como funcionales si no modifican los resultados.

Cuando el usuario abra un contenido y vuelva atrás, conserva la consulta y los filtros cuando sea razonable.

## 12. Reproductor de video

El reproductor debe ser coherente con la identidad visual de la plataforma.

Si existe reproducción real, contempla:
- Reproducir y pausar.
- Control de volumen.
- Barra de progreso.
- Tiempo transcurrido.
- Duración.
- Pantalla completa.
- Subtítulos cuando estén disponibles.
- Selección de audio cuando esté implementada.
- Estado de carga.
- Estado de error.
- Reproducción finalizada.
- Acción para regresar a los detalles o al catálogo.

Los controles deben aparecer y desaparecer de manera predecible.

La barra de progreso debe ser fácil de utilizar con ratón y pantallas táctiles.

No declares compatibilidad con DRM, calidad adaptativa o sincronización entre dispositivos si no están implementadas.

No uses recursos de video sin autorización o derechos de uso adecuados.

Si no existe una fuente de video válida, muestra un estado de demostración claramente identificado.

Un botón de reproducción nunca debe aparentar funcionar si no realiza ninguna acción.

## 13. Continuar viendo

Cuando el proyecto incluya persistencia de datos, implementa una experiencia de continuidad.

Debe permitir:
- Retomar una película.
- Continuar un episodio.
- Mostrar el progreso.
- Reproducir nuevamente.
- Distinguir entre contenido empezado y finalizado.

Muestra una barra de progreso discreta en las tarjetas correspondientes.

No inventes el progreso del usuario.

Si la persistencia no está implementada, explica la limitación y no prometas sincronización entre dispositivos.

## 14. Mi lista

Si el producto incluye esta funcionalidad, permite:
- Añadir películas y series.
- Eliminar contenido.
- Consultar la lista guardada.
- Identificar visualmente el estado de cada elemento.

La interfaz debe mostrar retroalimentación después de cada acción.

Si los cambios no se guardan de forma persistente, indícalo claramente.

## 15. Animaciones y microinteracciones

Utiliza animaciones discretas para:
- Hover de tarjetas.
- Apertura de menús.
- Modales.
- Botones.
- Cambios de estado.
- Indicadores de carga.

Las animaciones deben aportar continuidad y retroalimentación.

Evita:
- Partículas decorativas.
- Efectos de cursor innecesarios.
- Brillos permanentes.
- Parallax exagerado.
- Zoom excesivo.
- Fondos animados que compitan con las portadas.
- Reproducción automática de audio.

Respeta la preferencia del sistema `prefers-reduced-motion`.

Mantén una experiencia fluida incluso en dispositivos modestos.

## 16. Diseño responsive

### Escritorio

- Navegación completa.
- Hero panorámico.
- Filas de contenido amplias.
- Tarjetas con hover opcional.
- Controles de carrusel accesibles.

### Tableta

- Ajusta la cantidad de tarjetas visibles.
- Reduce el tamaño del hero cuando sea necesario.
- Conserva el espaciado y la legibilidad.
- Adapta la navegación a la anchura disponible.

### Móvil

- Prioriza el título, la portada y la acción principal.
- Reduce el texto superpuesto.
- Ajusta los degradados al formato de pantalla.
- Utiliza objetivos táctiles cómodos.
- No dependas del hover.
- Adapta el reproductor y los modales al viewport.
- Evita que las barras fijas tapen controles importantes.
- Mantén los carruseles fáciles de recorrer con gestos.

La interfaz debe diseñarse para cada tamaño, no simplemente encogerse.

## 17. Accesibilidad

Aplica las siguientes reglas:

- Utiliza HTML semántico.
- Mantén una jerarquía lógica de encabezados.
- Añade nombres accesibles a los botones que solo tengan iconos.
- Utiliza texto alternativo para imágenes informativas.
- Usa `alt=""` para imágenes decorativas.
- Mantén visible el foco de teclado.
- Permite utilizar menús, carruseles y modales con teclado.
- Gestiona correctamente el foco al abrir y cerrar diálogos.
- No comuniques estados únicamente mediante color.
- Respeta las preferencias de movimiento reducido.
- Incluye subtítulos cuando los recursos y el alcance del proyecto lo permitan.

## 18. Rendimiento

Las imágenes y los videos pueden representar una carga importante.

Por tanto:
- Optimiza las imágenes.
- Utiliza tamaños adecuados para cada dispositivo.
- Aplica carga diferida al contenido fuera de pantalla.
- Evita descargar todos los videos al iniciar.
- Reserva dimensiones para las imágenes.
- Utiliza placeholders discretos.
- Gestiona errores de carga.
- Evita dependencias innecesarias.
- No cargues recursos pesados que no se necesitan inmediatamente.

Usa fuentes de contenido estables y autorizadas.

No dependas de URLs temporales para funciones esenciales.

## 19. Estados de la interfaz

Diseña estados visuales para:
- Catálogo cargando.
- Imagen no disponible.
- Catálogo vacío.
- Búsqueda sin resultados.
- Error de red.
- Reproducción no disponible.
- Contenido añadido a Mi lista.
- Contenido eliminado de Mi lista.
- Reproducción en curso.
- Reproducción finalizada.

Los mensajes deben explicar qué ocurrió y, cuando sea posible, ofrecer una acción para recuperarse.

No dejes zonas vacías sin explicación cuando falten datos.

## 20. Identidad de marca y derechos

Inspírate en los patrones de usabilidad de las plataformas de streaming, pero desarrolla una identidad original.

No copies:
- Logotipos.
- Nombres comerciales.
- Ilustraciones protegidas.
- Textos promocionales.
- Capturas de interfaz presentadas como propias.

Utiliza imágenes y videos propios, con licencia o autorizados para el proyecto.

No sugieras que la plataforma tiene afiliación comercial con Netflix u otro servicio si no existe.

## 21. Criterios de implementación

Antes de programar:

1. Identifica el alcance: landing page, catálogo, detalles, reproductor o plataforma completa.
2. Revisa el framework y la arquitectura existente.
3. Identifica las fuentes de datos y los recursos audiovisuales disponibles.
4. Define las interacciones que deben funcionar.
5. Determina los estados de carga, error, vacío y éxito.
6. Si falta información no crítica, toma decisiones razonables y continúa.
7. Pregunta únicamente cuando una decisión bloqueante pueda cambiar significativamente el resultado.

Durante el desarrollo:

- Respeta el stack y las versiones existentes.
- Reutiliza componentes cuando mejore el mantenimiento.
- Centraliza los tokens de diseño.
- Evita duplicación y estilos contradictorios.
- Separa razonablemente presentación, datos y lógica.
- No elimines funcionalidades existentes durante un rediseño.
- No introduzcas dependencias innecesarias.
- No simules persistencia, autenticación o reproducción sin indicarlo.
- No afirmes haber probado funciones que no ejecutaste.

La skill es independiente del framework. Adáptala a React, Next.js, Vue, Svelte, HTML/CSS/JavaScript, Tailwind CSS o Bootstrap, según el proyecto.

Si se utiliza Bootstrap, personaliza sus componentes para que encajen con la identidad cinematográfica.

## 22. Lista de verificación

Antes de finalizar, comprueba:

- [ ] La interfaz se siente cinematográfica y premium.
- [ ] La marca tiene identidad propia.
- [ ] El hero presenta texto legible y acciones claras.
- [ ] Las portadas conservan sus proporciones.
- [ ] Los carruseles funcionan correctamente.
- [ ] La búsqueda y los filtros realizan acciones reales.
- [ ] Los detalles del contenido son accesibles.
- [ ] Los controles del reproductor funcionan cuando existe reproducción real.
- [ ] Los estados de carga, error y vacío están contemplados.
- [ ] La interfaz funciona en móvil, tableta y escritorio.
- [ ] Las imágenes están optimizadas.
- [ ] La navegación por teclado es posible.
- [ ] Los estados tienen contraste suficiente.
- [ ] No se presenta contenido ficticio como real.
- [ ] Se respetan los derechos de uso de imágenes y videos.
- [ ] Las limitaciones están declaradas.
- [ ] No se han eliminado funcionalidades existentes.

## 23. Prompt corto de activación

Aplica la skill `cinematic-streaming-ui`.

Crea una interfaz de streaming premium inspirada en los patrones de experiencia de Netflix, pero con una identidad de marca propia. Utiliza una estética oscura y cinematográfica, un hero panorámico con degradados sutiles, un catálogo de pósteres con proporciones correctas, carruseles horizontales navegables, búsqueda clara, detalles de contenido y estados de interacción coherentes.

Adapta la experiencia a escritorio, tableta y móvil. Prioriza rendimiento, accesibilidad, navegación fluida y una presentación visual profesional.

Evita las decoraciones genéricas, los efectos excesivos y las interfaces que parezcan plantillas sin personalización.

Implementa las interacciones solicitadas de verdad. No simules reproducción, persistencia, autenticación ni datos reales sin indicarlo.

Respeta el stack existente y entrega código completo, mantenible y ejecutable.
