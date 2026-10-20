# Restaurante Hotel Puerta del Parque

Landing editorial «Sabores entre montañas». Propuesta de diseño web no oficial, implementada con HTML5, CSS3 y JavaScript vanilla. Sin npm, frameworks, fuentes remotas ni compilación.

## Visualizar

Abre `index.html` en tu navegador. Todo funciona con rutas relativas, también mediante `file://`. Para comprobar llamadas se necesita un dispositivo o aplicación que admita enlaces `tel:`; Maps requiere conexión a Internet.

## Editar

- **Textos:** edita directamente `index.html`; cada sección tiene un comentario identificativo.
- **Colores y tipografías:** modifica las variables de `:root` al principio de `css/style.css`. Se usan Georgia y Arial del sistema para evitar dependencias externas.
- **Fotografías:** reemplaza los archivos de `img/`, conservando los nombres o actualizando sus rutas en HTML. Ajusta `alt`, dimensiones y `object-position` cuando corresponda. Preferiblemente WebP/AVIF, alrededor de 1600–1800 px para fotos grandes. Mantén la carga diferida excepto en el hero.
- **Contacto:** busca `600 614 268`, `+34600614268`, la dirección y el enlace de Maps en HTML. Actualiza también el bloque JSON-LD y las etiquetas SEO si cambian los datos.
- **Interacciones:** `js/script.js` contiene el menú móvil, el header adaptativo, el año automático y el revelado con Intersection Observer.

## Publicar

Sube el contenido completo de esta carpeta a la raíz pública del hosting estático, conservando `css/`, `js/` e `img/`. `index.html` debe quedar en la raíz servida. No se necesita ejecutar ningún comando de construcción. Activa HTTPS desde el proveedor.

Al disponer de dominio definitivo, añade `link rel="canonical"`, `og:url` y sustituye `og:image` por la URL absoluta de la imagen (actualmente usa una ruta relativa). Comprueba el resultado en el validador de tarjetas de la plataforma de destino: algunas no resuelven imágenes relativas. No se ha inventado un dominio.

Antes de publicar como web oficial, consigue la autorización del establecimiento, confirma sus datos y sustituye la indicación de propuesta no oficial cuando corresponda.

## Fotografías y derechos

Selección corregida el 20 de octubre de 2026. Se han retirado todas las fotografías anteriores. Ninguna fotografía es del establecimiento ni de su carta. Los paisajes y la arquitectura sí corresponden a localizaciones reales de la zona, según la ficha de origen. No hay fotografías de otros hoteles o restaurantes utilizadas como ambiente propio.

Los créditos también se publican en [creditos-imagenes.html](creditos-imagenes.html), accesible desde la nota de imágenes de la landing, para mantener la atribución después del despliegue.

| Archivo local | Autor / origen | Licencia elegida | Función y carácter |
| --- | --- | --- | --- |
| `img/croquetas-cocido.webp` | Juan Emilio Prades Bel · [Croquetas caseras de carne de cocido con allioli.jpg](https://commons.wikimedia.org/wiki/File:Croquetas_caseras_de_carne_de_cocido_con_allioli.jpg) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) | Hero. Gastronomía representativa; no es un plato del restaurante. |
| `img/grazalema-pueblo-y-montanas.webp` | Petra Nesti · [Original en Pexels](https://www.pexels.com/photo/picturesque-white-village-in-spanish-mountains-34340952/) | [Licencia Pexels](https://www.pexels.com/license/) | Presentación. Vista de Grazalema y sus montañas, según la ficha de origen. Fotografía de la zona, no del establecimiento. |
| `img/cocina-croquetas-vajilla-artesanal.webp` | Pablo Rodríguez · [Original en Pexels](https://www.pexels.com/photo/food-on-tray-18041217/) | [Licencia Pexels](https://www.pexels.com/license/) | Cocina 01. Croquetas en vajilla artesanal, fotografiadas en Cádiz. Imagen representativa; no es del establecimiento ni confirma su carta. |
| `img/cocina-tapas-mesa-rustica.webp` | Bas Linders · [Original en Pexels](https://www.pexels.com/photo/top-view-of-a-meal-on-a-wooden-table-14009278/) | [Licencia Pexels](https://www.pexels.com/license/) | Cocina 02. Composición de tapas para compartir sobre madera. Imagen representativa de gastronomía española; no atribuida al restaurante ni a una localización andaluza. |
| `img/cocina-tabla-quesos-artesanos.webp` | Anna Pyshniuk · [Original en Pexels](https://www.pexels.com/photo/assorted-cheese-and-nuts-on-the-wooden-platter-7799695/) | [Licencia Pexels](https://www.pexels.com/license/) | Cocina 03. Tabla de quesos sin envoltorios, con higos, aceitunas y frutos secos. Inspiración representativa; no se afirma que los quesos sean de Cádiz ni que estén disponibles. |
| `img/sierra-grazalema-terrazgos.webp` | Valleuve · [Panorámica Sierra de Grazalema.jpg](https://commons.wikimedia.org/wiki/File:Panor%C3%A1mica_Sierra_de_Grazalema.jpg) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) | Entorno. Paisaje real de Los Terrazgos, Sierra de Grazalema; no vista desde el restaurante. |
| `img/mesa-jamon-embutidos-pimientos.webp` | Nadin Sh · [Original en Pexels](https://www.pexels.com/photo/choice-of-meat-snacks-20644799/) | [Licencia Pexels](https://www.pexels.com/license/) | Galería 01. Mesa con jamón, embutidos y pimientos. Imagen gastronómica representativa; no del restaurante ni de su carta. |
| `img/grazalema-paisaje-rural.webp` | Petra Nesti · [Original en Pexels](https://www.pexels.com/el-gr/photo/grazalema-34340943/) | [Licencia Pexels](https://www.pexels.com/license/) | Galería 02. Paisaje del Parque Natural de Grazalema, según la ficha de origen. No es una vista desde el establecimiento. |

Las licencias permiten el uso comercial respetando sus condiciones. Las adaptaciones fotográficas (redimensionado y conversión a WebP) conservan la licencia de cada original; la presentación aplica recorte por CSS. No se amplían las fuentes. Créditos, enlaces a la fuente y licencia, y descripción de cambios se mantienen también en la página pública de créditos. No se descargaron imágenes de Google Maps, reseñas o redes sociales sin autorización.

### Auditoría de sustitución

- Hero: se retiró `mesa.webp`, una mesa genérica repetida en cocina y galería. Se incorpora una fotografía exclusiva de croquetas de cocido en barro.
- Presentación: se retiró `rural.webp`, arquitectura sin vínculo geográfico confirmado y repetida en galería. Se incorpora arquitectura blanca documentada de El Bosque.
- Cocina: se retiraron `cocina.webp` (utilizada dos veces) y `mesa.webp`. Tras la segunda revisión, cada bloque usa una foto editorial diferente: croquetas en vajilla artesanal, varias tapas en madera y una tabla de quesos sin envases. Son referencias visuales, no una carta.
- Entorno: se retiró `sierra.webp`, paisaje ajeno sin identidad local. Se incorpora Los Terrazgos, Parque Natural Sierra de Grazalema.
- Galería: se eliminaron las dos repeticiones. Hay dos marcadores originales distintos, pendientes de fotos reales autorizadas. No se sustituyen por interiores de otros establecimientos.
- No existen fondos fotográficos adicionales en CSS. Favicon y ornamentos originales se mantienen. Open Graph usa la nueva imagen del hero; no supone una segunda descarga visible en la landing.

Se descartaron también dos candidatos de Commons de El Bosque cuya inspección visual mostraba interiores ajenos, y dos descargas no disponibles por limitación del servidor. No se incluyen en la carpeta de producción.

### Comprobación frente a proyectos anteriores

Se ha inspeccionado el proyecto accesible contiguo `../Cafe-Pub Andalucia/cafe-pub-andalucia/` y sus cinco fotografías (hero, interior, compartir, cerveza y café). Se comparan SHA-256 de los archivos y huellas de imagen decodificada para detectar coincidencias aunque cambie el nombre o la codificación. El informe final de validación detalla los resultados. El alcance se limita a ese proyecto accesible; no se afirma haber revisado proyectos fuera de esta carpeta de trabajo y su directorio contiguo.

## Datos pendientes

Los datos de nombre, dirección, teléfono y contexto comercial proceden del encargo. No se han añadido horarios, precios, email, disponibilidad, redes sociales, reseñas, premios ni servicios turísticos. No se ha verificado que el teléfono admita WhatsApp y por eso no se incluye.

Croquetas, flamenquín y cachopo son referencias de directorios aportadas en el encargo, no una carta confirmada. Se ha optado por no enumerarlas en la web para evitar confusiones sobre disponibilidad. La carta y los horarios se deben confirmar directamente. Tampoco se ofrece reserva de hotel ni formulario de reserva sin backend.

## Accesibilidad y comportamiento

HTML semántico; enlace para saltar al contenido; foco visible; botón móvil con `aria-expanded` y `aria-controls`; cierre por Escape, selección de enlace o clic exterior; navegación por teclado; reducción de movimiento; contenido visible sin JavaScript. El año se actualiza automáticamente. La navegación móvil se adapta a partir de 800 px; hay ajustes para 1100, 800 y 560 px.

## Validación de entrega

Revisión en Chrome sin interfaz, el 20 de octubre de 2026:

- 375, 768 y 1440 px: ocho imágenes cargadas y decodificadas; sin desbordamiento horizontal.
- Menú móvil/tablet: abre, cierra con Escape y se cierra al seleccionar un enlace.
- Todos los elementos de revelado se hacen visibles al desplazarse; con movimiento reducido permanecen visibles. No se modifica JavaScript ni las reglas originales de animación.
- Ocho recursos visuales distintos: seis fotos WebP y dos marcadores SVG originales. No se repite ninguna fotografía en el contenido. Open Graph referencia el hero como vista previa social.
- Comparación con las cinco fotos del proyecto anterior accesible: 40 pares, cero coincidencias de SHA-256 de archivo o de imagen decodificada a 32×32; diferencia media mínima de píxeles de 37,47/255. Se inspeccionaron visualmente los candidatos. Esto no garantiza exclusividad mundial de fotografías públicas ni detecta todos los recortes posibles; el alcance se limita al proyecto mencionado.
- Se retiran los cuatro archivos antiguos y se comprueban las rutas locales y los créditos.
- Solo se modifican referencias, textos alternativos, dimensiones de imagen, encuadres y nota de créditos. Se mantienen estructura, colores, tipografías, comportamiento responsive y animaciones originales.

El informe reproducible de resultados y huellas está en [auditoria-imagenes.json](auditoria-imagenes.json). Las pruebas corresponden a emulación de tamaños en Chrome, no a dispositivos físicos. La web sigue funcionando sin npm ni compilación.

## Segunda revisión: calidad editorial de Nuestra cocina

Se sustituyen únicamente las tres fotografías de esta sección y sus encuadres, alt y dimensiones. Los textos visibles de la landing, el resto de imágenes, la estructura y JavaScript permanecen idénticos. Selección de Pexels con licencia válida para web comercial, revisada el 20 de octubre de 2026; fotografías locales optimizadas a WebP de 1600 px de ancho. No se afirma que representen platos del establecimiento ni que los quesos sean de la Sierra de Cádiz.

Criterio visual: se descartan fotos con comensales comiendo, envases o etiquetas, iluminación deficiente y presentación doméstica. La selección mantiene superficies naturales, tonos cálidos, alimentos completos y composiciones cuidadas. La primera foto utiliza enfoque selectivo intencional sobre la croqueta del primer plano; no es desenfoque por baja resolución. La segunda muestra variedad de tapas; la tercera da protagonismo a una tabla preparada, sin empaquetado comercial. Se ajusta object-position individualmente, manteniendo object-fit: cover y las dimensiones originales de las tarjetas. No se aplican filtros que alteren los colores naturales de los alimentos.

Las tres fotografías sustituidas se retiran de img/. Autoría y fuentes actuales se publican también en creditos-imagenes.html. El informe auditoria-imagenes.json conserva la validación anterior como histórico y añade los resultados de esta revisión.

Validaci?n de la segunda revisi?n: inspecci?n visual de capturas en Chrome a 375 y 1440 px, adem?s de comprobaci?n a 768 px. Las tres fotos cargan con dimensiones correctas y object-fit: cover, sin deformaci?n ni desbordamiento. Los revelados siguen funcionando. Ocho recursos visuales ?nicos en la landing; 40 comparaciones contra las cinco im?genes del proyecto anterior accesible, sin coincidencias de archivo ni de imagen decodificada. Se verifica por comparaci?n que los textos y la estructura HTML fuera de las etiquetas img, el JavaScript y las reglas CSS originales permanecen id?nticos. Solo se a?aden tres reglas de encuadre espec?ficas.

## Tercera revisión: presentación y diario visual

Solo se corrigen «Tradición, paisaje y buena mesa» y «Una pausa. Mucho que sentir». La presentación incorpora una vista vertical de Grazalema con iluminación natural; se retira el glifo vegetal y se equilibra la separación antes de la frase final. La galería sustituye ambos marcadores por fotografías diferentes de mesa gastronómica y paisaje de Grazalema. Se mantienen títulos, pies de foto, distribución asimétrica, dimensiones y puntos de ruptura; las fotos llenan sus espacios mediante object-fit: cover y encuadres individuales. Hover suave de luminosidad, compatible con prefers-reduced-motion.

Fuentes y licencias actuales: las tres nuevas fotografías están detalladas en la tabla superior y creditos-imagenes.html. Licencia Pexels revisada el 20 de octubre de 2026, permite este uso comercial. Se guardan localmente en WebP, sin ampliación, con 1800 px de ancho. Los paisajes se identifican por las fichas del autor como Grazalema; la mesa es representativa, no una foto de la carta o del restaurante. No se atribuye una localización andaluza específica a la fotografía gastronómica. No se usan fotos de otros negocios como si fueran el establecimiento.

Los apartados de las revisiones anteriores son históricos: ya no hay placeholders en la galería ni se utiliza el-bosque-arquitectura-blanca.webp. Estos tres recursos sustituidos se retiran de img/. Las fotos de hero, cocina y entorno permanecen intactas. El JavaScript no cambia.

Validaci?n de la tercera revisi?n: Chrome a 375, 768 y 1440 px, con inspecci?n visual de capturas de las dos secciones. Tres im?genes cargadas, encuadradas con cover, sin deformaci?n ni desplazamiento horizontal. T?tulos y pies conservados fuera de las fotos para mantener contraste. Adorno eliminado. Revelados activos y hover desactivado por la preferencia de movimiento reducido. Ocho fotos diferentes, comparadas por SHA-256 de archivo y de imagen decodificada a 32?32 frente a cinco fotos del proyecto anterior accesible: cero coincidencias. Se confirma por comparaci?n que el HTML fuera de las secciones intro/journal y el JavaScript no han cambiado. El informe actualizado, con los anteriores como hist?rico, est? en auditoria-imagenes.json.
