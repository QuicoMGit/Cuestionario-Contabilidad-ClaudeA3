# Cuestionario asesores — parte 2

Página web estática alojada en GitHub Pages. Recoge respuestas sobre dos flujos de trabajo específicos de gestorías que usan A3 como software contable: el seguimiento de cobros y la preparación del modelo 303.

Es la segunda parte de un proceso de investigación con usuarios iniciado con un cuestionario anterior. Las respuestas determinan si tiene sentido añadir funcionalidades nuevas a un sistema de automatización contable basado en Claude Pro y A3.

## Contenido del repositorio

```
readme_v2.html       — Página introductoria (enlaza al cuestionario)
cuestionario_v2.html — Formulario de dos secciones
```

## Cómo funciona

Las respuestas se envían a Formspree (`/f/xwpbkodq`). Si el envío falla, el formulario muestra un bloque de texto que el usuario puede copiar y enviar manualmente.

No hay backend, no hay base de datos, no hay cookies.

## Desplegar cambios

```bash
git add .
git commit -m "descripción del cambio"
git push
```

GitHub Pages publica automáticamente desde la rama `main`.

## Contexto del proyecto

Este cuestionario forma parte del desarrollo de **Sistema Claude + A3**, un flujo de trabajo para gestorías españolas que integra Claude Pro con el software A3 (a3ASESOR eco/con) para automatizar el procesado de facturas, la reconciliación bancaria y los asientos manuales.

El repositorio principal del sistema es privado.
