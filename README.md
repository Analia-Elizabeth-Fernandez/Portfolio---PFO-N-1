# Portfolio Personal — PFO1

Landing de portfolio personal desarrollada con HTML semántico y CSS propio para la
consigna PFO1 de la materia Front End. Presenta mi perfil, mis habilidades, una sección personal
libre y una forma de contacto, con enlace visible a mi perfil de GitHub.

**URL de Vercel:** https://portfolio-analia-fdz.vercel.app/

**Repositorio:** https://github.com/Analia-Elizabeth-Fernandez/Portfolio---PFO-N-1

## Decisiones que tomé

- **Estilo visual:** elegí mezclar dos estéticas: el uso de colores tipo "caramelo"
  saturados (inspirado en sitios como Gumroad) con los bordes negros gruesos y las
  sombras duras (offset, sin blur) características del neobrutalismo. Buscaba un
  resultado divertido pero prolijo, sin perder legibilidad.
- **Tipografía:** combiné tres Google Fonts con roles distintos — *Space Grotesk*
  para títulos (bold, geométrica), *Inter* para el texto de lectura, y *Space Mono*
  para elementos técnicos como la navegación, los chips de habilidades y las
  etiquetas del formulario, reforzando la identidad de desarrolladora.
- **Layout:** usé Grid para el hero (foto + texto) y para la grilla de habilidades,
  y Flexbox para la navegación y el formulario de contacto. El diseño es responsive:
  en pantallas chicas para celulares, el hero pasa a una columna y la navegación se acomoda debajo
  del logo.
- **Interacción:** la animación principal es un efecto de "presión" en botones,
  chips y cards — al pasar el mouse, el elemento se desplaza levemente y su sombra
  se reduce, simulando que se hunde. También agregué un efecto de texto tipeado en
  el hero con JavaScript simple (sin librerías).
- **Sección personal ("Fuera del código"):** la resolví como tres tarjetas con
  estética de ventana de navegador, cada una levemente rotada para dar sensación de collage/sticker.
- **Contenido:** para esta entrega dejé afuera la sección de proyectos y
  certificaciones de mi portfolio completo, ya que la consigna pide una landing
  breve centrada en perfil, habilidades, contacto y una sección libre.

## Imágenes

La foto de perfil (`foto-perfil.png`) es una foto propia, sin intervención de IA.
Los íconos de contacto y de habilidades son íconos de marca de uso estándar, no
generados por IA.

## Declaración de uso de IA

- **Herramienta usada:** Claude (Anthropic), plan Free, modelo Sonnet a través del chat web.
- **Para qué la usé:** para pensar la dirección de estilo (mezcla de referencias
  visuales), generar la estructura inicial del HTML y el CSS a partir de mi
  contenido real, y para armar este mismo README.
- **Experiencia previa:** ya usaba IA generativa con frecuencia para algunas tareas de
  código antes de este trabajo, así que supe qué pedirle y cómo iterar sobre las
  respuestas en vez de usar el primer resultado tal cual.
- **Qué revisé/adapté con criterio propio:** definí yo la referencia estética de
  base (una landing tipo "sticker" que ya conocía) y pedí explícitamente combinarla
  con neobrutalismo por los bordes definidos, que es lo que más me gustaba de ese
  estilo. Revisé el HTML generado para confirmar que cumpliera los requisitos
  técnicos de la consigna (semántica, alt, label, Grid/Flexbox) y fui ajustando los contenidos
  según las animaciones y el texto que queria generar.
