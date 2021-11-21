---
title: "Tema2"
date: 2021-11-20T21:24:18+01:00
draft: true
weight: 2
---

## TAREA 2

### Proceso de carga de página web

**El proceso de carga y ejecución se ejecuta:**

**1.** El usuario usando el navegador envía la solicictud al servidor. la solicitud normalmente es para aceder a una página web. 

**2.** El servidor recibe la solicitud y comienza el proceso de construir la página web. Si existe código PHP, se ejecuta en este momento, se hacen todas las consultas a la Base de Datos. El resultado es una página con HTML y tal vez JavaScript.

**3.** El navegador recibe la página, interpreta y usa el HTML para construirla. La página web aparece en la pantalla del usuario.



{{< mermaid align="left" >}}
graph LR;
    A[Navegador] -->|Petición de la página| B[Servidor Web]
    B --> C(PHP)
    C -->|Procesar PHP| D(HTML)
    D -->|Resultado HTML| A[Navegador]
{{< /mermaid >}}