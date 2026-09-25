# Trabajo Práctico: HTML y CSS

**Materia:** Diseño UX-UI — 2026


Los 20 ejercicios del TP resueltos, cada uno en su carpeta con index.html
y styles.css.

## Ejercicios

1. Estructura HTML básica — 01-estructura-html
2. Listas y enlaces — 02-listas-enlaces
3. Tabla de datos — 03-Tablas
4. Formulario simple — 04-Formulario
5. Primeros estilos CSS — 01-estructura-html
6. Selectores CSS — 06-selectores
7. Modelo de caja (Box Model) — 07-Boxmodel
8. Flexbox: barra de navegación — 08-flexbox
9. Flexbox: galería de tarjetas — 09-flexbox-galeria
10. CSS Grid: layout de página — 10-grid-layout
11. Pseudo-clases y pseudo-elementos — 11-pseudo-clases
12. Posicionamiento — 12-posicionamiento
13. Formulario estilizado — 13-formulario-estilizado
14. Variables CSS y temas — 13-formulario-estilizado
15. Diseño responsivo con Media Queries — 015-Diseño_responsivo_con_Media_Queries
16. Animaciones con @keyframes — 016-Animacion
17. Menú hamburguesa (solo CSS) — 017-Hamburguesa
18. Grid avanzado: galería mosaico — 018-Grid_avanzado_galería_tipo_mosaico
19. Formulario multi-step con validación visual — 019-Formulario_multi-step_con_validación_visual
20. Proyecto integrador: Landing Page — 020-Landing-Page

## Sobre el ejercicio 20

Hice una landing de una tienda de productos Apple ("Applecdelu"). Además
de lo que pedía la consigna le agregué una sección de productos destacados
(iPhone, cargador, AirPods) porque le quedaba mejor a la temática.

Paleta verde oscuro con detalles en dorado para los testimonios. Los
colores están en variables CSS (:root) para no repetirlos por todos lados.

Para el responsive fui con desktop-first, porque el layout ya lo tenía
armado en grande desde el ejercicio 10 y era más directo ir recortando
con media queries que rehacer todo de cero. Tuve que arreglar la navbar
que se pisaba en mobile (la puse en columna) y la imagen de fondo del
hero que se veía recortada en pantallas angostas.

El menú hamburguesa del ejercicio 17 y los pasos del formulario del
ejercicio 19 están hechos con el truco de checkbox/radio oculto + CSS, pero
sin JavaScript.
