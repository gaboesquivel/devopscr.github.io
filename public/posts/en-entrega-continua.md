La entrega continua es la práctica en el desarrollo de software en la cual los equipos de desarrollo trabajan de una manera que permite a las empresas actualizar sus sistemas en cualquier punto en el tiempo o de forma continua a través de procesos automatizados, la base de código del sistema esta siempre probada y puede ser distribuida.

## Por qué es importante?

La entrega continua es una forma más eficiente de construir software, ya que permite a un equipo obtener retroalimentación constante sobre los cambios en la aplicación y las actualizaciones, lo que le permite detectar los problemas en menor tiempo y por lo tanto mejorar la calidad, reducir los costos y fricciones en la distribución. Esta retroalimentación constante también le da al equipo una visión realista de progreso del desarrollo en lugar de basarse en las percepciones.

Entrega continua da una empresa la capacidad de reaccionar con rapidez y responder al cambio. Tener un proceso fluido de desarrollo de software le permite hacer cambios en su estrategia más fácil y rápidamente .

Permite a una empresa para aumentar su capacidad y escalar con mayor facilidad. Un proceso continuo facilita el trabajo en equipos de desarrollo más grandes. Procesos por lotes como la planificación de la iteración, la planificación de la liberación y las pruebas vuelven exponencialmente más difícil la organización ya que involucra a un número creciente de personas. La entrega continua resuelve este problema evitando procesos por lotes.

## Principios básicos

__Visibilidad__ – Todos los aspectos del sistema de administración incluyendo la construcción, la implementación de las pruebas, y la liberación son visibles para todos los miembros del equipo para promover la colaboración.

__Retroalimentación__ –
Los miembros del equipo se enteran de un problema lo antes posible cuando se produzca de manera que sean capaces de solucionarlos lo antes posible.

__Distribución Continua__ – A través de un proceso totalmente automatizado se puede implementar y liberar cualquier versión del software para cualquier entorno.

## La automatización es la fundación de la Entrega Continua

Para lograr la entrega continua se necesita alta automatización del proceso de entrega. Después de que un desarrollador sube cambios, todo debe ser completamente automatizado, incluyendo informes, métricas, notas de la versión, etc.

## Integración Continua

Para poder entregar continuamente también necesita hacer integración continua. Esto significa que los desarrolladores tienen que integrar continuamente su código, por lo menos una vez al día. La integración exitosa es determinada por un servidor de integración que ejecuta las pruebas de integración cada vez que se añade código, si las pruebas fallan el equipo de desarrollo recibe una notificación, esto permite al equipo solucionar el problema tan pronto como aparece.

### Estrategias de Integración
Numerosos modelos de integración diferentes son posibles y que están relacionados a la estrategia de control de versiones. Andy Singleton en su libro [Unblock](http://continuousagile.com/unblock) propuso un categorización en cuatro patrones:

#### Centralizado
El patrón centralizado es el patrón tradicional popularizado por Jez Humble. Pones todos los cambios juntos en una versión del código central, y continuamente se ejecutan pruebas automatizadas en ellos. El objetivo es integrar lo antes posible, encontrar problemas tan pronto como sea posible, y entrenar a su equipo para evitarlos. Es fácil de configurar y escala para apoyar los sistemas de compilación y prueba centralizados complejos.

#### Distribuido
El patrón distribuido es utilizado por muchas empresas SaaS que requieren liberar cada cambio. Cada cambio se prueba en una rama separada y luego puesto en libertad antes de que llegue problemas de integración con otros cambios.

#### Revisión de rama
El sistema de revisión de rama le permite producir código más fiable en los equipos más grandes, probando y revisando cada cambio antes de entrar en una versión compartida centralizado. Esta es una buena práctica.

#### MAXOS
El patrón MAXOS organiza la entrega continua de los sistemas complejos que se construyen a partir de múltiples servidores y servicios que se comunican entre sí. El equipo de mantenimiento de un servicio se acumula y libera cambios a menudo utilizando un sistema de revisión de rama. Antes de que un servicio se promueva a producción se prueba en un sistema de integración continua centralizada para asegurarse de que funciona con la versión pre-lanzamiento de todos los otros servicios.

### Compromiso del equipo y el flujo de trabajo

La integración continua no es sólo acerca de las pruebas automatizadas, sino un proceso de organización. Para integrar con éxito el código de forma continua un equipo de desarrollo debe comprometerse a seguir las mejores prácticas de integración continua y asumir una mayor responsabilidad para la entrega de código y funciones complemente listas y probadas para la liberación.

- La rama principal (master) debe poder ser siempre implementable y lista.
- Rapidez: medir de forma automática y mejorar continuamente.
- Utilizar un "interruptor" de funciones para deshabilitar y habilitar nuevas funciones del software.
- Más comunicación: la comunicación juega un papel primordial en la integración continua .
- Subir código con frecuencia.
- No subir código roto.
- No subir código no probado .
- Siempre verificar que el sistema funciona después de subir código.
