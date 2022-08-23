# sass2-y-seo
Seguimos avanzando en el curso de WebDev de Coder House

<h1>..:: DESAFÍO SASS II Y SEO ::..</h1>
Memoria del trabajo realizado para el Desafío SASS II y SEO - Comisión 37200 de Coder House

<h4>EN ESTE DOCUMENTO:
  
[1. Cambios realizados por tipo función aplicada](#1-cambios-realizados)<br>
&nbsp;  1.1 Mapas<br>
&nbsp;  1.2 Mixins<br>
&nbsp;  1.3 Extend<br>
&nbsp;  1.4 SEO<br>
2.  [Problemas resueltos y aprendizajes](#2-problemas-resueltos-y-aprendizajes)<br>
3.  [Conclusión](#3-conclusi%C3%B3n)
  
------------------------------------------------------
  

<h2>1. Cambios realizados</h2>

A lo largo del sitio pude ir agregando los contenidos vistos en las clases, sumado a las modificaciones de SASS que habíamos visto en la clase anterior: nesting, variables e import de partials.

Con las variables, configuré un set de colores que utilicé para la marca. Con los import pude separar las partes del sitio en partials. No utilicé el método sugerido en el material complementario porque no tenía un volumen significativo de código para organizarlo de esa manera. En cambio prioricé separar los estilos por página, donde intenté plasmar diferentes tipos de contenido basados más que nada en Bootstrap grids.

No encontré la forma de aplicar operaciones matemáticas ni bucles. Intenté utilizar condicionales pero me quedé sin tiempo, como explicaré en el título 2.

<h3>1.1 Mapas</h3>
Utilicé esta funcionalidad para generar una escala cromática que diferencie a golpe de vista un valor aplicado a las tres variables propuestas desde el Diseño Centrado en el Usuario: cantidad de <strong>dinero</strong> a gastar, cantidad de <strong>tiempo</strong> a dedicar y cantidad de personas en <strong>compania</strong> de quienes se dese hacer la experiencia.

<h3>3.0 Mixins</h3>
Apliqué mixins para las páginas donde contaba con Flex dispuestos en columnas.

<h3>1.3. Extend</h3>
Los apliqué dentro de los mapas de diferenciación cromática de las experiencias (página "Aventuras"). Y también en la página "Nosotros".

<h3>1.4. SEO</h3>
Utilicé KEYWORDS que presentaran el sitio desde su marca, utilizando el criterio periodístico de las "5 w": (what) rubro de actividad, (where) ubicación geográfica, (who) quienes somos, (when) temporada de atención, (why) por qué contratar nuestros servicios.
El FAVICON es un recorte del logo que armé de manera provisoria, a la espera del que me pasará el cliente.
La DESCRIPCIÓN es una combinación de las deficiones de Core Business (la misión institucional) y de Core Competence (la ventaja competitiva).
Para los TITLE de las páginas, utilicé el criterio de combinación de elementos constantes (nombre del sitio) y variables (nombre de la página).


<h2>2. Problemas resueltos y aprendizajes</h2>

Desde que comencé a trabajar con SASS I tuve problemas en el uso de Node.js. En concreto, me tiraba errores de instalación y llegué a desistir de usarlo porque no encontraba la manera de hacerlo funcionar. Como alternativa hice uso de la extensión "Live SASS compiler" de Visual Studio Code.
Finalmente, identifiqué la fuente del problema (error en la redacción del código npm) y pude instalarlo con éxito.
Al iniciar el trabajo de SASS II, armé un nuevo repositorio y le agregué el NPM. Volvió a surgir el mismo error y no se logró la instalación. Revisé qué pasaba teniendo en cuenta lo aprendido del desafío de SASS I pero siguió sin funcionar. Opté por clonar esa primera expriencia y recién ahí pude avocarme a la resolución del presente desafío.
Otro aprendizaje que me llevó tiempo y energía resolver surgió cuando de repente vi que se había roto todo el CSS. Era cerca de la fecha y hora de entrega y me ganó la ansiedad. Hice y deshice cambios. Traté de recuperar commits anteriores. Me llamaba la atención que ciertas partes del Bootstrap funcionaran y otras no. Entonces pude identificar el problema: como usé CDN, la parte online no estaba funcionando: se me había caído la conexión.

<h2>3. Conclusión</h2>

La mejor forma de aprovechar todos las técnicas de escritura de código con SASS es codeando sin parar. Entonces se vuelven un mecanismo inconsciente que hace ahorrar tiempo y optimiza el proceso de maquetado y desarrollo.
Si bien me lamenté mucho por los problemas que encontré externos a la realización del sitio en sí, ahora considero que es justamente frente a las situaciones reales y concretas donde se puede realizar un verdadero aprendizaje.
El curso está buenísimo. Lo estoy disfrutando un montón.
