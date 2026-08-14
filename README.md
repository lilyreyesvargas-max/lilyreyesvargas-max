# Lilianne Reyes Vargas

Desarrolladora full-stack. Fundadora de **[Lily Technology Group LLC](https://ltgsoft.com)**, donde construyo software a medida para pequeñas empresas — y me quedo con él después: el servidor, los respaldos y la llamada de las tres de la madrugada también son míos.

Trabajo en español y en inglés · *I work in Spanish and English.*

---

### En qué ando

**[Balancily](https://balancily.com)** — SaaS de gestión financiera para pequeñas empresas. Gastos, facturación, cuentas por cobrar y por pagar, método Profit First y lectura automática de facturas con la visión de la API de Claude. Multiempresa, bilingüe, con suscripciones y verificación en dos pasos. **Se puede probar en [balancily.com](https://balancily.com).**
`FastAPI` · `PostgreSQL` · `Next.js` · `Stripe` · En producción.

**Plataforma de operaciones clínicas** — ERP sanitario multisede sobre Odoo 17: historia clínica electrónica con CIE-10 y submodelos por especialidad, agenda entre sedes, facturación a aseguradoras con ciclo de vida de la reclamación y conciliación de ERA, farmacia con receta electrónica, inventario, RR. HH. y nóminas, y cuadros de mando por rol. Cumple el EDI de EE. UU. (X12 837P/835/270/271) contra un clearinghouse de pruebas propio.
`Odoo 17` · `PostgreSQL` · `Docker` · `FastAPI` · `OWL`

**Portal corporativo con CMS propio** — sitio bilingüe con su panel de administración, sin dependencias de plataforma: el contenido lo edita quien lo escribe, no quien programa.
`Flask` · `PostgreSQL` · `JavaScript` sin framework · En producción.

---

### La parte que no se ve

No sólo escribo el software: **administro lo que lo mantiene en pie.**

- **Servidores** en AWS EC2, con nginx o Apache según el sitio, HTTPS automático, aislamiento por sitio, arranque supervisado y respaldos verificados —restaurados, no sólo generados—.
- **Cloudflare** delante de todo: DNS, proxy, reglas de WAF, TLS estricto y reenvío de correo del dominio.
- **Correo transaccional** con Resend, con SPF y DKIM en regla, porque una factura en la carpeta de spam es una factura que no se cobra.
- **Cobros** con Stripe: suscripciones, prorrateos, webhooks y conciliación cuando un evento se pierde.
- **Observabilidad**: reporte de errores con Sentry, filtrando los datos de clientes ANTES de que salgan del servidor; monitorización externa e integración continua.
- **Respuesta a incidentes**: incluida la parte que nadie enseña — un sitio comprometido, limpiarlo, entender por dónde entraron y cerrarlo.

---

### IA, donde aporta

- **En producción**: lectura automática de facturas con la API de Claude. Se le pasa un PDF o una foto y devuelve el importe, la fecha, el número y quién emite — lo que evita teclear cada comprobante. La persona confirma antes de que nada se guarde, y el sistema aprende el formato de cada proveedor para no volver a gastar cupo con el mismo.
- **En mi flujo de trabajo**: agentes de Claude Code para revisión de arquitectura, QA y seguridad; servidores MCP propios; y automatizaciones con n8n para el trabajo repetitivo.
- **Lo que no hago**: dejar que decida sola. Lo que propone la IA es una propuesta, no una conclusión — se revisa antes de valer, sea una decisión de arquitectura, un cambio que va a producción o un dato que entra en la contabilidad de un cliente. La herramienta acelera el trabajo; la responsabilidad de lo que se entrega no se delega.

---

### Cómo trabajo

- **Tests antes que el código**, y calibrados: un test que no falla cuando reintroduzco el bug no protege nada.
- **Lo que se despliega se verifica en producción**, no en la máquina de quien lo escribió.
- **El porqué se escribe junto al código.** Un comentario que explica la decisión vale más que tres que describen la sintaxis.
- Sin dependencias que no me pueda explicar.

---

### Herramientas

`Python` · `TypeScript` · `Java` · `PHP` · `SQL`
`FastAPI` · `Flask` · `Django` · `Next.js` · `React` · `Spring Boot` · `Odoo` · `WordPress`
`PostgreSQL` · `MySQL` · `AWS` · `Cloudflare` · `nginx` · `Apache` · `Docker` · `Stripe` · `Resend` · `Sentry`
`Claude API` · `Claude Code` · `MCP` · `n8n`

---

📍 Estados Unidos · 📬 **contact@ltgsoft.com** · 🌐 **[ltgsoft.com](https://ltgsoft.com)**

<sub>La mayoría de mi trabajo es de clientes y vive en repositorios privados.</sub>
