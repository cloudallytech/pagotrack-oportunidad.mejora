# PagoTrack — Reportá bugs y proponé mejoras

> **Documentación exclusiva para personal de Nuveo SA.**
> Para reportar bugs, sugerir mejoras o proponer ideas nuevas en PagoTrack **necesitás formar parte de Nuveo SA**. Si no pertenecés a la empresa, no vas a poder cargar incidencias ni acceder al repositorio privado.

---

## ¿Por qué tu reporte importa?

PagoTrack lo usamos todos los días en Nuveo, y **vos sos quien mejor sabe dónde duele**. Cada bug que reportás y cada mejora que proponés:

- Te ahorra tiempo a vos y a tus compañeros.
- Evita errores en imputaciones, comprobantes o datos de clientes.
- Hace que el sistema crezca con las necesidades reales del equipo, no con suposiciones.

**No hace falta ser técnico.** Si algo te molesta, te confunde o te parece que podría ser mejor, **avisanos**. Reportar suma siempre, aunque después resulte que no era un bug.

---

## ¿Encontraste algo que no funciona como debería? ¿Se te ocurrió una mejora?

¡Genial! Acá te contamos cómo avisarnos.

## La forma más simple: avisarle a Juampa por Discord

Si no querés complicarte, **escribile directamente a `juampaweb` por Discord** contándole lo que pasó o lo que querrías que el sistema haga. Él se encarga de cargar la incidencia en el sistema de seguimiento.

Es la opción recomendada si:

- No tenés cuenta de GitHub.
- No querés crear una.
- Te resulta más cómodo charlarlo por Discord.
- Tenés dudas sobre si lo que viste es realmente un bug o no.

## Si preferís cargarlo vos mismo en GitHub

El seguimiento se hace en GitHub. Como el repositorio es privado y de uso interno de Nuveo SA, primero necesitás que te den acceso:

- **Email:** jsosa@nuveo.cloud
- **Discord:** juampaweb

Mandale tu **usuario de GitHub** y te suma. Después podés abrir lo que necesites desde:

- **Listado:** https://github.com/cloudallytech/pagotrack.nuveo/issues
- **Abrir uno nuevo:** https://github.com/cloudallytech/pagotrack.nuveo/issues/new

## ¿Qué tipo de cosa estás reportando?

| Tipo | Cuándo |
|---|---|
| **Bug** | Algo que no anda, o anda distinto a lo esperado (el bot no responde, un dato sale mal, una imputación falla). |
| **Mejora** | Algo que ya funciona pero podría ser más útil, más rápido o más claro. |
| **Idea nueva** | Una funcionalidad que hoy no existe y te gustaría que estuviera. |
| **Pregunta** | No sabés si algo es un bug o así está pensado, o querés saber cómo hacer X. |

Si no estás seguro del tipo, no te preocupes — avisanos igual y entre todos lo ordenamos.

## Cómo describir bien lo que pasó

No hace falta que escribas un ensayo. Cuanta más información des, más rápido lo resolvemos. Lo importante es contestar estas preguntas:

### Si es un bug

1. **¿Qué estabas intentando hacer?** (en una línea)
2. **¿Qué esperabas que pasara?**
3. **¿Qué pasó en realidad?**
4. **¿Cómo podemos reproducirlo?** (paso a paso, desde cero)
5. **Datos del momento:** fecha y hora aproximada, qué empresa elegiste, qué comprobante usaste, tu usuario de Discord.
6. **Capturas de pantalla** del thread de Discord, si tenés.

#### Ejemplo de un buen reporte

> **Qué intentaba hacer:** Imputar un pago a una factura de Allytech.
>
> **Qué esperaba:** Que la factura quedara como pagada.
>
> **Qué pasó:** El bot me mostró las facturas pero al elegir la #12345 me dijo 'error' y no se imputó nada.
>
> **Pasos:** Subí el comprobante, confirmé los datos, elegí Allytech, seleccioné la factura #12345, escribí 'si'.
>
> **Cuándo:** Hoy a las 16:11, soy Juampaweb en Discord.

### Si es una mejora o idea nueva

1. **¿Qué te gustaría poder hacer** que hoy no podés o cuesta?
2. **¿Por qué te serviría?** Qué problema concreto resuelve.
3. **¿Cómo te lo imaginás?** No hace falta que sea la idea final, alcanza con un esbozo.

#### Ejemplo

> **Qué quiero:** Ver cuánto saldo a favor tiene el cliente antes de imputar.
>
> **Por qué:** A veces el cliente ya pagó de más y no me doy cuenta hasta después.
>
> **Cómo me lo imagino:** Que el bot, antes de mostrar las facturas, muestre una línea con 'Saldo actual: $X'.

## Cómo titularlo

Si lo cargás vos en GitHub, el título es lo primero que se ve. Que sea **corto y específico**.

**Mejor evitar:**

- 'No funciona'
- 'Problema con el bot'
- 'Mejoras'

**Mejor así:**

- 'El bot no detecta el monto cuando el comprobante usa $ en vez de ARS'
- 'Agregar saldo del cliente antes del listado de facturas'
- 'La imputación a Allytech falla con transferencias bancarias'

## Antes de abrir uno nuevo

Si te animás, dale una mirada rápida a [los issues existentes](https://github.com/cloudallytech/pagotrack.nuveo/issues?q=is%3Aissue) buscando alguna palabra clave. Si encontrás algo parecido a lo tuyo, sumá un comentario contando tu caso en vez de abrir uno nuevo — así no se duplica el trabajo.

Si no encontrás nada o no estás seguro, abrí uno igual. Mejor que sobre a que falte.

## En resumen

- **Lo más fácil:** decile a `juampaweb` por Discord.
- **Si querés cargarlo vos:** pedí acceso a jsosa@nuveo.cloud con tu usuario de GitHub y abrí un issue.
- **Lo importante:** contar qué pasó (o qué querés), cuándo, y cómo reproducirlo si es un bug.

Cualquier duda, preguntá. **Reportar algo siempre suma**, aunque después resulte que no era un bug — y cada mejora que propongas hace que PagoTrack funcione mejor para todo el equipo de Nuveo.

---

*Documentación interna de Nuveo SA — el acceso al sistema de reportes está reservado a personal de la empresa.*
