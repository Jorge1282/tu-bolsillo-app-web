# Política de Privacidad y Términos de Uso — Tu Bolsillo App

*Última actualización: [completar con la fecha real de publicación]*

---

## Aviso importante antes de leer

Este documento fue redactado con ayuda de una IA como punto de partida, basado en el funcionamiento técnico real de la app. **No reemplaza la revisión de un abogado.** Antes de publicarlo, hacelo revisar por un profesional, sobre todo si vas a vender la app fuera de Venezuela o si en el futuro cambiás la arquitectura de datos (por ejemplo, si agregás un servidor propio).

---

## 1. Quiénes somos

Tu Bolsillo App es una aplicación de finanzas personales desarrollada por [tu nombre o razón social], con domicilio en Venezuela. Para consultas sobre privacidad o estos términos, podés escribirnos a: [tu correo de contacto].

## 2. Transparencia sobre cómo funciona la app (lo más importante de este documento)

A diferencia de otras apps similares, **Tu Bolsillo App no tiene un servidor central donde se guarden tus datos financieros.** Concretamente:

- **Tus movimientos, categorías, presupuestos y metas se guardan únicamente en tu propio dispositivo** (en el almacenamiento local del navegador/aplicación — técnicamente llamado `localStorage`).
- **Nosotros, como desarrolladores, no tenemos acceso a esos datos en ningún momento.** No existe una base de datos nuestra con la información financiera de los usuarios.
- Si desinstalás la app o borrás los datos del sitio sin haber hecho un respaldo, **esa información se pierde de forma permanente** — no podemos recuperarla porque nunca pasó por nuestros sistemas.

## 3. Respaldo opcional en tu propia cuenta de Google Drive

La app ofrece, de forma **completamente opcional**, la posibilidad de conectar tu propia cuenta de Google para guardar un respaldo de tus datos en tu Google Drive personal.

- Usamos el permiso más restringido que ofrece Google (`drive.file`): la app **solo puede ver el archivo de respaldo que ella misma crea**, y no tiene acceso a ningún otro archivo de tu Drive.
- Ese respaldo se guarda directamente en tu cuenta de Google — **nosotros no tenemos copia de ese archivo ni acceso a tu Drive** en ningún servidor propio.
- Podés desconectar esta función en cualquier momento desde Ajustes → Respaldo.
- Si no conectás Drive, tus datos existen únicamente en tu dispositivo, y sos vos quien decide si querés exportar un respaldo manual (archivo JSON descargable) por tu cuenta.

## 4. Tu usuario y contraseña dentro de la app

Para proteger el acceso a tus datos en el propio dispositivo, la app te pide crear un usuario y contraseña la primera vez que la abrís.

- Esas credenciales se guardan **cifradas únicamente en tu dispositivo**, nunca se envían a ningún servidor nuestro.
- Al crear la cuenta, se te entrega un **código de recuperación** que debés guardar vos mismo en un lugar seguro. Es la única forma de restablecer tu contraseña si la olvidás — **no existe un proceso de "recuperar contraseña por correo electrónico"**, porque no operamos ningún servidor de autenticación.
- Si perdés tanto la contraseña como el código de recuperación, no hay forma de recuperar el acceso a esos datos.

## 5. Datos que sí podemos recibir (y de cuáles no)

**No recolectamos:**
- Tu ubicación (GPS) — la app no la solicita en ningún momento.
- Tus datos financieros — nunca llegan a nuestros servidores, como se explicó arriba.
- Contactos, fotos, ni ningún otro dato del dispositivo.

**Servicios externos que la app consulta (sin identificarte):**
- Para mostrar la tasa de cambio del día, la app consulta servicios públicos de terceros (bcv.today y un espejo en jsDelivr) que devuelven el valor del dólar oficial. Esta consulta no envía ningún dato personal tuyo, solo pide el valor público del día.
- Si conectás Google Drive, la app se comunica directamente con los servidores de Google (`googleapis.com`) usando tu propia sesión de Google — nosotros no somos intermediarios de esa comunicación.

**Si en el futuro vendemos la app a través de Google Play o Apple App Store:**
- Esas tiendas pueden recolectar datos técnicos básicos de instalación/pago (según sus propias políticas, ajenas a nosotros) para procesar la compra y prevenir fraude.

## 6. Menores de edad

La app no está dirigida a menores de 13 años. Si sos padre/madre/tutor y creés que un menor a tu cargo usó la app sin tu supervisión, podés simplemente desinstalarla y borrar los datos del dispositivo, ya que no existen en ningún servidor nuestro para solicitar su eliminación.

## 7. Tus derechos sobre tus datos

Como tus datos financieros nunca llegan a nuestros sistemas, en la práctica **vos tenés control total y exclusivo sobre ellos** en todo momento:

- **Acceso y portabilidad:** podés exportar tus datos como archivo JSON en cualquier momento desde Ajustes → Respaldo.
- **Eliminación:** desinstalar la app o borrar los datos del sitio elimina inmediatamente y por completo tu información — no necesitás pedírnoslo, porque nosotros no la tenemos.
- **Rectificación:** todos tus datos son editables directamente dentro de la app en cualquier momento.

## 8. Cambios en esta política

Podemos actualizar este documento si cambia la forma en que funciona la app (por ejemplo, si en el futuro agregamos un servidor propio para alguna función). Cualquier cambio relevante se va a anunciar dentro de la propia app o en nuestro sitio web, con la fecha de última actualización visible arriba.

---

# Términos de Uso

## 1. Aceptación

Al usar Tu Bolsillo App, aceptás estos Términos de Uso y la Política de Privacidad descrita arriba.

## 2. Qué es (y qué no es) la app

Tu Bolsillo App es una herramienta de seguimiento y organización de finanzas personales. Incluye un módulo llamado "Coach Financiero" que ofrece diagnósticos y consejos generados por reglas fijas, basados únicamente en los datos que vos mismo cargás.

**Importante:** el Coach Financiero y cualquier otro contenido de la app son **educativos y generales** — no constituyen asesoría financiera, de inversión, tributaria ni legal personalizada. Ninguna sugerencia dentro de la app reemplaza la consulta con un profesional matriculado (contador, asesor financiero, abogado) para decisiones importantes.

## 3. Licencia de uso

Te otorgamos una licencia personal, no exclusiva e intransferible para usar la app según el plan que hayas adquirido (si aplica). No podés revender, redistribuir ni realizar ingeniería inversa de la aplicación.

## 4. Planes pagos y renovación *(completar si vendés suscripciones)*

- [Detallar: precio, duración de cada plan, si se renueva automáticamente o no, cómo cancelar]
- Los pagos se procesan a través de [Google Play Billing / el medio que uses] y están sujetos a sus propias políticas de reembolso.
- [Aclarar si las compras son "pases de tiempo consumibles" como hace tu competencia, o suscripciones recurrentes]

## 5. Responsabilidad limitada

La app se ofrece "tal cual". No garantizamos que esté libre de errores en todo momento. No somos responsables por:
- Pérdida de datos por desinstalación, cambio de dispositivo, o falta de respaldo de tu parte.
- Decisiones financieras que tomes basándote en la información o sugerencias de la app.
- Interrupciones en los servicios externos de terceros (tasa de cambio, Google Drive) que están fuera de nuestro control.

## 6. Terminación

Podés dejar de usar la app en cualquier momento simplemente desinstalándola. Nosotros podemos discontinuar la app o alguna función con aviso previo razonable cuando sea posible.

## 7. Ley aplicable

Estos términos se rigen por las leyes de la República Bolivariana de Venezuela. *[Revisar con un abogado si vas a vender a usuarios de otros países — puede requerir ajustes]*

---

## Contacto

Para cualquier consulta sobre privacidad, tus datos, o estos términos: **[completar correo de contacto]**

*Tu Bolsillo App — Venezuela*
