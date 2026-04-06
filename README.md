# AuroralisStar

AuroralisStar es un fork experimental de shaders para Minecraft enfocado en identidad visual, atmosfera y presets ajustados para hardware concreto.

El proyecto parte de trabajo previo de la comunidad shader, pero su intencion no es ser solo una copia reempaquetada. Este repo documenta una linea de personalizacion que empuja la presentacion hacia auroras mas visibles, niebla mas dramatica, color grading mas definido y perfiles pensados para escenarios reales de uso.

## Idea central del repo

AuroralisStar busca responder una pregunta simple: que pasa si en lugar de usar un preset generico se construye una direccion artistica reconocible, con variantes separadas segun el equipo donde realmente se va a jugar.

Por eso el repo esta organizado alrededor de dos ramas practicas del shader:

- una variante para laptop MX450, priorizando rendimiento y estabilidad
- una variante para desktop RTX 4060, priorizando calidad visual y atmosfera

## En que se diferencia del upstream

Este fork se centra en:

- auroras mas protagonistas
- presencia mas fuerte de niebla y haze
- bosques con un tono mas denso y cinematografico
- perfiles artisticos mas visibles dentro del menu del shader
- identidad de marca propia dentro del contenido del pack
- ajustes separados por hardware en vez de un unico perfil universal

## Que contiene el repositorio

```text
AuroralisStar/
|-- README.md
|-- CREDITS.md
|-- desktop-rtx4060/
|   |-- README.md
|   |-- CODEX_PRESET_NOTE.txt
|   `-- shaders/
|-- laptop-mx450/
|   |-- README.md
|   |-- CODEX_PRESET_NOTE.txt
|   `-- shaders/
`-- _workspace_archive/
```

## Variantes incluidas

### `laptop-mx450/`

Perfil orientado a un equipo mas limitado.

Objetivos:

- mantener buena fluidez
- conservar la identidad visual del fork
- limitar costo de efectos donde sea necesario
- permitir presets estilizados sin castigar demasiado el FPS

### `desktop-rtx4060/`

Perfil orientado a una GPU de escritorio mas capaz.

Objetivos:

- niebla mas rica
- auroras mas intensas
- sombras y atmosfera mas ambiciosas
- una lectura mas cinematografica de la escena

## Contenido tecnico

Dentro de cada variante se incluyen archivos tipicos de un shader pack, entre ellos:

- configuraciones `.properties`
- archivos GLSL
- menus y textos localizados
- presets y notas de ajuste
- subcarpetas por mundo o dimension con configuraciones especificas

El repositorio funciona como espacio de trabajo para esas modificaciones, no solo como paquete final listo para publicar en una pagina de mods.

## Direccion artistica

La direccion visual del fork gira alrededor de:

- auroras violetas
- luces calidas y doradas
- verdes mas frios en vegetacion
- niebla mas perceptible
- una atmosfera mas cargada y menos plana
- separacion mas clara entre presets jugables y presets mas cinematograficos

## Uso esperado

Este repo esta pensado para usuarios que:

- quieren estudiar o modificar el fork
- quieren tomar una de las variantes como base
- prefieren trabajar con archivos shader directamente
- necesitan un historial de experimentos visuales y presets

## Loader recomendado

La ruta recomendada para usar AuroralisStar es:

- Minecraft Java Edition
- Iris como cargador principal de shaders
- Sodium para rendimiento

Tambien puede servir como base para otras configuraciones compatibles con el ecosistema de shaders, pero el repo esta organizado con Iris en mente.

## Creditos y lineage

AuroralisStar mantiene visible su procedencia. El punto de partida viene de trabajo previo de la comunidad, especialmente:

- Eclipse Shader de Merlin1809
- Bliss Shader de X0nk
- la tradicion historica de shaders que referencia a Chocapic13

Los detalles estan resumidos en `CREDITS.md`.

## Estado del proyecto

Este repo es un fork en evolucion. No representa un shader pack “cerrado” ni congelado, sino un espacio de ajuste continuo, comparacion entre perfiles y experimentacion artistica.

## Que no intenta ser

- no es un repo generico de Minecraft
- no es una recopilacion de mods
- no es solo un zip final para instalar y olvidar

Es principalmente un repositorio de trabajo para una direccion visual concreta.

## Buen punto de partida para nuevos colaboradores

Si quieres explorar el repo, la forma mas clara es:

1. leer `CREDITS.md` para entender el origen
2. comparar `laptop-mx450/` y `desktop-rtx4060/`
3. revisar los `CODEX_PRESET_NOTE.txt`
4. entrar a las carpetas `shaders/` para ver los ajustes reales

## Futuro posible

- mas presets tematicos por bioma o mood
- mejor documentacion de diferencias exactas entre ambas variantes
- empaquetado formal para distribucion
- notas de rendimiento comparables por escena y hardware
