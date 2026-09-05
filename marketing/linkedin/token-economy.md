# LinkedIn — token-economy

**Fecha sugerida de publicación:** cualquiera, es el más técnico de los 5 (empezar por este si tu red es muy dev-heavy).

**Enlace a incluir en el post:** https://davidgarciagordo.github.io/plugins/token-economy/

---

## Borrador del post

Llevo un tiempo trasteando con agentes de IA trabajando en equipo sobre el mismo código, y me di cuenta de algo tonto: cuatro agentes revisando el mismo PR se leen el repo entero cuatro veces. Mismos ficheros, mismo trabajo, cuatro veces el gasto.

Así que escribí un plugin pequeño para Claude Code, `token-economy`, que hace que ese "leer el repo" pase una sola vez: un script escribe un resumen compartido, y cada agente lo usa en vez de volver a escanear todo. Nada del otro mundo, pero medido en una revisión real: ~2,6× menos tokens por agente, y si vuelves a revisar lo mismo más tarde, casi gratis.

Lo comparto porque es de código abierto y gratis — mi granito de arena a que la IA aplicada a herramientas de desarrollo sea un poco más razonable con el bolsillo de quien la usa, no solo con la demo bonita. Si trabajas con Claude Code y agentes en paralelo, seguro que te suena el problema.

🔗 davidgarciagordo.github.io/plugins/token-economy/

#ClaudeCode #IA #OpenSource #DesarrolloDeSoftware

---

## Notas para David (no publicar)

- Tono: humilde, en primera persona, sin bombo. Evita "revolucionario", "game changer", etc.
- Cifra 2,6× y "casi gratis" están medidas de verdad (ver la landing), no son marketing inventado.
- Puedes acortar el post si LinkedIn se lo come; el gancho es "cuatro agentes leen el mismo repo cuatro veces" — eso no lo toques.
