# Lilianne Reyes Vargas

**Entregar el código es la mitad del trabajo.** La otra mitad es que siga en pie a las tres de la madrugada — y de esa también me encargo yo.

Desarrolladora full-stack y fundadora de **[Lily Technology Group LLC](https://ltgsoft.com)**, donde construyo software a medida para pequeñas empresas: lo diseño, lo escribo, lo despliego y lo mantengo funcionando.

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

### Ingeniería de IA

- **Sistemas de agentes.** Los diseño con roles acotados y responsabilidades que no se pisan —arquitectura, QA, seguridad, análisis funcional— y con verificación cruzada: un agente propone, otro intenta refutarlo. Sin eso, un informe de IA es una opinión larga y segura de sí misma.
- **Servidores MCP propios**, para darle a un modelo acceso a herramientas y datos reales sin abrirle la puerta entera.
- **Canalizaciones de extracción**: salida estructurada en vez de texto libre, limpieza de datos sensibles antes de que salgan del servidor, confirmación humana antes de guardar, y aprendizaje del formato de cada proveedor para no volver a pagar por lo mismo.
- **Automatizaciones** con n8n para el trabajo repetitivo.

### IA en producción

- **Lectura automática de facturas** con la API de Claude: se le pasa un PDF o una foto y devuelve el importe, la fecha, el número y quién emite — lo que evita teclear cada comprobante. La persona confirma antes de que nada se guarde.

> **Y lo que no hago, en cualquiera de los dos casos:** dejar que decida sola. Lo que propone la IA es una propuesta, no una conclusión — se revisa antes de valer, sea una decisión de arquitectura, un cambio que va a producción o un dato que entra en la contabilidad de un cliente. La herramienta acelera el trabajo; la responsabilidad de lo que se entrega no se delega.

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
