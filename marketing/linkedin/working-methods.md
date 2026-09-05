# LinkedIn — working-methods

**Fecha sugerida de publicación:** publícalo cerca de forge-methodology (van de la mano) pero no el mismo día — deja 3-4 días entre uno y otro para que no se pisen en el feed.

**Enlace a incluir en el post:** https://davidgarciagordo.github.io/plugins/working-methods/

---

## Borrador del post

Una metodología que el propio agente de IA puede saltarse cuando tiene prisa no es una metodología, es una sugerencia. Me lo he encontrado yo mismo: defines un proceso claro paso a paso, y en la práctica, bajo presión, algún paso se queda en el tintero y nadie se da cuenta hasta más tarde.

`working-methods` es el plugin de Claude Code que hace que eso no dependa de que el agente se acuerde. El orden de las 12 fases de mi metodología (`forge-methodology`) vive literalmente en código, no en una nota — hay una pequeña máquina de estados que rechaza seguir si te saltas una fase, y un hook que se niega a dejar pasar un pull request si no puede comprobar que todo está en orden. A ti, como owner, solo te interrumpe dos veces en todo el proceso, y cada vez con las opciones ya recomendadas para que decidas rápido.

No es la parte más vistosa de lo que hago, lo sé. Pero para mí "que la IA trabaje como un equipo senior" empieza aquí: en que los procesos se cumplan aunque nadie esté mirando. Gratis, abierto, mi granito de arena a que la IA en desarrollo se apoye en mecanismos, no en buena voluntad.

🔗 davidgarciagordo.github.io/plugins/working-methods/

#ClaudeCode #IA #Ingeniería #OpenSource

---

## Notas para David (no publicar)

- Tono: reconoce que es "poco vistoso" — genera credibilidad no vender esto como flashy cuando no lo es.
- Frase ancla: "una metodología que el agente puede saltarse no es una metodología, es una sugerencia".
- Evita explicar la diferencia técnica exacta con forge-methodology en el post — eso queda para quien entre a la landing.
