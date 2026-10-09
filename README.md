name: Reportar un bug
description: Reportar un error del programa
title: "[BUG] "
labels: ["bug"]
body:
  - type: textarea
    id: descripcion
    attributes:
      label: ¿Qué error encontraste?
      description: Explica el problema.
    validations:
      required: true

  - type: textarea
    id: pasos
    attributes:
      label: ¿Cómo reproducir el error?
      description: Escribe los pasos para que podamos repetirlo.
      placeholder: |
        1. Abrir el programa
        2. Pulsar un botón
        3. Observar el error
    validations:
      required: true

  - type: textarea
    id: esperado
    attributes:
      label: ¿Qué debería suceder?
    validations:
      required: true

  - type: textarea
    id: ocurrido
    attributes:
      label: ¿Qué sucedió realmente?
    validations:
      required: true

  - type: input
    id: sistema
    attributes:
      label: Sistema operativo
      placeholder: Windows 11, Linux, etc.
    validations:
      required: true
