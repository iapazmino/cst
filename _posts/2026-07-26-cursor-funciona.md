---
layout: post
title: "Qué quiere decir que Cursor funciona"
date: 2026-07-26 19:30:00 -0500
categories: ia cursor ide programación scot
---

Advertencia: artículo en construcción. 

Para entender que preguntas debo hacer en busca de la herramienta de IA que más se utiliza entre los programadores en Ecuador en la actualidad quiero primero entender qué quiere decir que Cursor funciona desde mi punto de vista. El objetivo no es generalizar si no identificar mi sesgo y poder hacer las preguntas de la encuesta sin que guien la respuesta.

(Aquí va un párrafo que introduzca la flexibilidad interpretativa de la teoría de la construcción social de la tecnología con referencia al libro de la bicicleta de pinch y bijker) la ide es mostrar que esta definición de funciona es mi definición de funciona y no necesariamente se traslada a otras personas y otros grupos; de hecho eso es lo valioso, aquí me voy a dar cuenta de qué condiciones me llevan a tomar esta decisión y buscar cómo afectó de otra forma a otra gente.

## Qué quiere decir que funciona?
Primero y más importante Cursor es un IDE y no una interfaz con un agente, es decir sigue siendo un ambiente en el que escribir código es la meta del objeto.
Luego porque tiene una interfaz conocida, es el VS Code con una ventana para el asistente.
Me evita salir del código, puedo referenciar archivos y carpetas en los prompts.
Puedo elegir los modelos que quiero, por ejemplo en el trabajo utilizo sólo los modelos que paga mi trabajo y en mi casa todos los que paga mi suscripción menos Grok.
Cuesta 20 dólares mensuales, que es algo que puedo pagar.

## Cómo es posible ese funcionamiento?
Constuir un IDE desde cero es una tarea bastante grande, entonces empezaron desde un fork de la versión Open Source de VS Code (Github NixOS 2024).
Esto tampoco es barato. La inversión inicial fue de 8 millones de dólares (TechCrunch 2023) y menos de un año después tuvo otra inversión de 60 millones más (Tech Juice 2025).
Inicialmente los modelos disponibles eran solamente los de OpenAI y Anthropic. Luego se incorporó un modelo propio y posterior a la venta a SpaceX tambien Grok. (referencia de la lista de modelos y de la compra). El entrenamiento de estos modelos requiere de millones de litros de agua (referencia a los centro de datos de OpenAI y demandas por el agua)(referencia a los centros de datos de Amazon, donde corre Anthropic) para disipar el calor generado por millones chips que requieren billones de dolares (referencia a la plata que le entro a NVidia desde Openai y Microsoft) y una cantidad inmesurable de datos publicos y privados tomados sin autorización de todos lados (referencias datos de wikipedia y juicios por derechos de autor NY times). (donde corren los modelos de Cursor, en que infra???)( aws capaz?) 
Y como un servicio tan caro se sostiene con subscripciones de 20 dolares pues gracias a los precios especiales que recibe (referencia al precio especial que le da OpenAi) (referencia a las inversiones circulares entre Nvidia, Oracle, OpenAI y otros: burbuja) 

## Referencias

- [Github NixOS 2024, "This is Code OSS fork with builtin AI code generator"](https://github.com/NixOS/nixpkgs/issues/309541)
- [TechCrunch 2023, "Anysphere raises $8M from OpenAI to build an AI-powered IDE"](https://techcrunch.com/2023/10/11/anysphere-raises-8m-from-openai-to-build-an-ai-powered-ide/)
- [Tech Juice 2025, "Karachi-Born Tech Prodigy Behind $10 Billion “Vibe Coding” AI"](https://www.techjuice.pk/karachi-born-tech-prodigy-behind-10-billion-vibe-coding-ai/)
