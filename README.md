# FinanzasPersonales

Consejo de agentes de finanzas personales para Claude Code, orientado a un
único objetivo: ayudarte a alcanzar la **libertad financiera** y construir un
**patrimonio neto superior a 1.000.000 €**.

## Cómo funciona

El agente principal (definido en [`CLAUDE.md`](./CLAUDE.md)) actúa como
director del consejo y delega en siete subagentes especialistas, definidos en
[`.claude/agents/`](./.claude/agents/):

- **presupuesto-gastos** — presupuesto, control de gastos, tasa de ahorro.
- **ahorro-inversion** — fondos indexados, ETFs, interés compuesto, proyecciones.
- **deudas-credito** — hipotecas, préstamos, amortizar vs invertir.
- **fiscalidad-optimizacion** — impuestos, tributación de inversiones, planes de pensiones.
- **jubilacion-fire** — número FIRE, tasa de retirada segura, independencia financiera.
- **patrimonio-inmobiliario** — inversión inmobiliaria, alquiler vs compra.
- **seguros-riesgos** — fondo de emergencia, seguros, protección patrimonial.

## Cómo empezar

1. Rellena tus datos reales en [`datos/perfil-financiero.md`](./datos/perfil-financiero.md)
   (ingresos, gastos, patrimonio, deudas, edad, horizonte y tolerancia al riesgo).
2. Habla con el agente principal y pídele, por ejemplo:
   - "Revisa mi situación financiera completa y dime por dónde empezar."
   - "Calcula mi proyección hacia 1.000.000 € y mi número FIRE."
   - "Ayúdame a hacer un presupuesto con mis gastos actuales."
3. El plan resultante se guarda y se actualiza en
   [`datos/plan-libertad-financiera.md`](./datos/plan-libertad-financiera.md).

> Este consejo ofrece guía educativa y de planificación general, no
> asesoramiento financiero, fiscal o de seguros regulado. Para decisiones
> grandes o irreversibles, contrasta siempre con un profesional certificado.
