# LinkedIn — forge-methodology

**Fecha sugerida de publicación:** bueno para una audiencia de líderes técnicos / PMs, no solo devs — el problema que resuelve (features a medias) lo sufre cualquiera que gestione entregas.

**Enlace a incluir en el post:** https://davidgarciagordo.github.io/plugins/forge-methodology/

---

## Borrador del post

Hay un patrón que he visto repetirse trabajando con IA en desarrollo: pides "quiero algo a la altura de Stripe" y lo que sale cumple la mitad de lo que Stripe realmente hace, porque nadie se sentó a enumerar qué hace Stripe de verdad. Y luego, el mismo agente que construyó la feature es el que dice "está verificado" — que es un poco como calificarte tu propio examen.

Con esa espina clavada escribí `forge-methodology`, un plugin para Claude Code que obliga a que "completo" sea algo mecánico, no una sensación. Cuando le pides que construya algo "a la par de X", primero descompone esa referencia en una lista de capacidades concretas, cada una con su propia fila de seguimiento. Y hay un mecanismo que literalmente bloquea abrir el pull request mientras cualquiera de esas filas no tenga evidencia real — y esa evidencia la tiene que firmar alguien que no sea quien construyó la pieza.

Soy transparente con sus límites: por defecto, si no detecta esa lista de capacidades, avisa pero no bloquea — no quiero venderlo como algo que hace magia donde no la hay.

Es gratis, abierto, y lo comparto porque creo que "hecho" debería significar lo mismo para todos, no lo que cada uno interprete a su conveniencia bajo presión de fecha. Mi granito de arena para que trabajar con IA en equipo se parezca más a ingeniería y menos a fe.

🔗 davidgarciagordo.github.io/plugins/forge-methodology/

#ClaudeCode #IA #Metodología #OpenSource

---

## Notas para David (no publicar)

- Tono: honesto sobre el fail-open por defecto, no lo escondas — es lo que le da credibilidad al resto del post.
- Gancho: "calificarte tu propio examen" es la frase que más se pega, no la quites.
