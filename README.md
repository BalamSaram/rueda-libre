# Rueda libre 
El sitio web rueda libre es una simulación de un sitio web que presta servicios de alquiler de bicicletas.
El sitio permite conocer los servicios con tablas, consultar las bicicletas disponibles gracias a su catálogo, así como las rutas posibles ofrecidas. 
Además cuenta con un formulario con validación con navegación y algunas restricciones como fecha y límite de caracteres para documento y celular hechos con javaScript para demostración.

## ¿Qué hace?
Cuenta con:
- página principal con información del servicio (incluye carrusel de imágenes interactivo)
- catálogo de bicicletas y recorridos.
- sección de servicios y tarifas
- fomrulario de reservas con validación
- ventana modal en link de "¿cómo alquilar?"
- info de contacto y ubicación del sitio.

## ¿Cómo abrirlo?
Algunos features particulares como las alertas, se activa al presionar enviar formulario una vez esté "correctamente" diligenciado.
- Las ventanas modales se activan con el link de cómo alquilar.
- Los botones "Resérvala" del catálogo envían al formulario de reservas.
- Los botones como "beneficios", "Reserva tu bici" o "encuéntranos" conducen a diferentes funciones como ventana modal, pantalla de formulario y footer con ubicación respectivamente. 

## Tailwind CSS
La página principal (`index.html`) usa Tailwind CSS para el bloque de reserva que aparece después del catálogo de rutas. El resto del sitio conserva Bootstrap para no afectar el carrusel, el menú y las ventanas modales existentes.

1. Abre `index.html` en un navegador con conexión a internet; Tailwind se carga desde su CDN.
2. Busca `reserva-tailwind` en el HTML para ver el bloque y sus clases utilitarias. No usa estilos en línea.
3. Cambia el ancho de la ventana o usa las herramientas de desarrollador del navegador para probar los prefijos `sm:`, `md:` y `lg:`.

El CDN de navegador es una opción sencilla para este sitio de práctica; para producción, Tailwind recomienda compilar el CSS.

## Sitio publicado
Enlace: pendiente de publicar. Cuando publiques el sitio, reemplaza esta línea con su URL.

## Hecho por: 
Nicolle Duran
Riwi - 2026