# Test_JoycomGames
 Challenge Test for Joycom Games - Unity Developer

Para el desarrollo de esta prueba se hace uso de la versión de Unity 2019.4.5f1, con un preseteo incial en URP.

En este desarrollo, se integraron e implementaron diferentes tipos de assets de terceros con el fin de dar solución a algunos puntos de la prueba planteada teniendo el cuenta el tiempo que disponía para su desarrollo.

El primero de ellos fue "Realistic Terrain Collection LITE", descargado del asset store, con el fin de integrar un terreno preseteado y a partir de este, realizar ciertas modificaciones, para personalizarlo y adaptarlo a los requisitos, de este paquete tambien se usa el skybox que trae para la escena trabajada.

Se hace uso de un modelo fbx de Arbol gratuito, descargado por mi parte, hace un tiempo de la página Tubosquid.com. Al cual se le realizan algunas modificaciones en texturas y materiales para presentar ciertas variaciones.

En la escena se realiza un pequeño seteo y bake de la navegación, buscando establecer los espacios que podria recorrer tanto los Agents AI como el jugador, sin embargo, esta funcionalidad no quedo plenamente implementada al momento de realizar este documento. Quedaría pendiente implentar la AI que usaran los agentes y el respectivo seteo del componente NavMeshAgent.

Otro packete de assets descargado del asset store, que se usa en este desarrollo es "Karting Microgame", del cual se utilizan los modelos de personaje y carro, asi como las animaciones, sonidos y funcionalidad de estos, para agilizar el desarrollo de estos puntos. Con base en estos con un poco mas de tiempo se podría customizar mejor la funcionalidad buscada, lo cual no fue posible desarrollar hasta el momento por tiempo.

De igual manera, con el fin de desarrollar el requerimiento de smooth follow de la camara al player, se emula la funcionalidad que trae este paquete en una de sus escenas de prueba, usando el paquete de Cinemachine, con el cual, no sólo se logra implementar este requerimiento, sino que adicionalmente, permite pensar en una futura funcionalidad para grabar la carrera o momentos clave del recorrido.

Finalmente, se realizan algunas configuraciones básicas, para los efectos del Postprocessing (Bloom, Color Grading, Anti-Aliasing, Ambient Oclution) y el lighting en la escena (Mixed Lighting, Fog).



