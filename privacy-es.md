---
layout: default
title: Política de Privacidad
permalink: /privacy-es/
---

# MedTime (İlaçVakti) — Política de Privacidad

**Última actualización:** 2 de agosto de 2026

MedTime (İlaçVakti) es una aplicación móvil desarrollada por el Farmacéutico **Mehmet Tuğberk Özsoy**, diseñada para ayudar a los usuarios a hacer un seguimiento de sus medicamentos. Su privacidad es nuestra máxima prioridad; esta política explica de forma transparente qué datos se tratan y cómo.

Otros idiomas: [English](/ilacvakti-legal/privacy-en/) · [Türkçe](/ilacvakti-legal/privacy-tr/)

---

## 1. Datos que no se recopilan

MedTime **no** recopila identificadores personales (nombre, correo electrónico, teléfono, número de identificación, fecha de nacimiento, etc.) de los usuarios, no los envía a nuestros servidores y no los comparte con terceros. No se requiere la creación de una cuenta; la aplicación funciona de forma totalmente **anónima**.

Lista detallada de los datos que no se recopilan:
- ❌ Seguimiento publicitario o analítico
- ❌ Servicios de análisis de terceros (Google Analytics, Facebook Pixel, etc.)
- ❌ Datos de ubicación
- ❌ Contactos, calendario
- ❌ Almacenamiento de grabaciones de audio (el micrófono solo se activa para la entrada por voz opcional, véase 3.6)
- ❌ Creación de cuenta, correo electrónico, teléfono
- ❌ Los datos de Apple Health **nunca se leen** (para la sincronización opcional de solo escritura, ver 3.5)

---

## 2. Almacenamiento local (datos conservados en su dispositivo)

Toda la información que introduzca se almacena **únicamente en la memoria interna de su dispositivo**:

- Nombres de medicamentos, dosis, horarios de los recordatorios
- Nombres de perfil (los nombres que usted proporcione) y foto de perfil opcional
- Información sobre el stock de medicamentos y fotos
- Historial de tratamiento, registros de tomas/omisiones
- Datos de rachas e insignias
- Informes y notas de salud añadidos manualmente
- Preferencias de tema, idioma, sonido de notificación y ajustes

Cuando elimina la aplicación, todos estos datos se eliminan junto con su dispositivo.

---

## 3. Permisos

### 3.1 Notificaciones
El permiso de notificaciones se solicita para los recordatorios de medicamentos. Las notificaciones se programan **localmente en su dispositivo**; no interviene ninguna conexión a un servidor.

### 3.2 Cámara
El acceso a la cámara se solicita únicamente en la pantalla *"Añadir medicamento"*, para escanear códigos de barras/códigos QR de las cajas de medicamentos o para tomar fotos del medicamento. Las imágenes de la cámara no se envían a ningún servidor.

### 3.3 Fotos
El acceso opcional a la fototeca se solicita si desea añadir fotos de medicamentos o de perfil. Las fotos seleccionadas se copian únicamente a la carpeta interna de la aplicación en su dispositivo.

### 3.4 Búsqueda en la base de datos de medicamentos
Cuando escanea el código de barras/código QR de la caja de un medicamento o busca un medicamento por su nombre, solo se envía ese **código de barras/código de producto o el nombre del medicamento** a un servicio oficial de base de datos de medicamentos para obtener el nombre y los detalles del medicamento (prospecto, envase, fecha de caducidad, etc.). El servicio utilizado depende de la región de su dispositivo: **NosyAPI** (Turquía), la base de datos **openFDA de la FDA de EE. UU.** (Estados Unidos) o **AEMPS CIMA** (España). En esta consulta no se incluye ninguna información personal (su nombre, datos de perfil, datos de salud, fotos o imágenes de la cámara); únicamente se transmite el código escaneado o el término de búsqueda. Esta función es opcional; si no la utiliza, no se envía ningún dato.

Puede revocar los permisos en cualquier momento a través de *Ajustes &gt; MedTime* en iOS.

### 3.5 Apple Health (HealthKit) — Escritura opcional
Los usuarios Premium pueden activar opcionalmente *Ajustes → Guardar en Apple Salud* para que las mediciones de **presión arterial, glucosa y pulso** introducidas en la app **también se escriban** en la app Salud de Apple. Esta función es **totalmente opcional** y está **desactivada por defecto**.

- İlaçVakti **nunca lee** sus datos de Salud; el acceso es **solo de escritura** y se aprueba explícitamente mediante la pantalla de permisos de iOS.
- Solo se escriben las mediciones de **su propio perfil**; los perfiles de familiares nunca se sincronizan.
- Los datos van directamente al almacén de Salud de su dispositivo; **no se envía nada a ningún servidor**. Apple cifra sus datos de Salud.
- Si elimina o edita una medición en la app, su copia escrita en Salud se actualiza/elimina en consecuencia.
- Puede revocar el acceso en cualquier momento en iOS *Ajustes → Salud → Acceso a datos y dispositivos → İlaçVakti*.
- Los datos de salud nunca se usan con fines publicitarios, de marketing o analíticos (conforme a la Regla 5.1.3 del App Store).

### 3.6 Micrófono y reconocimiento de voz — Opcional
Al tocar el icono del micrófono en la pantalla de mediciones puede introducir su tensión o su glucosa **hablando**. Esta función es **totalmente opcional**; el micrófono nunca se activa si no toca ese icono.

- Su voz se transcribe **en su dispositivo**; la aplicación **exige** el reconocimiento de voz en el dispositivo de iOS. **No se envía ningún audio a ningún servidor**: la función también funciona en modo avión.
- **No se conserva ninguna grabación.** Una vez transcrita su voz, los datos de audio no se guardan; solo los números reconocidos se escriben en los campos de la pantalla.
- El valor reconocido **no se guarda directamente**: se escribe en el campo y no se registra hasta que usted lo revisa y pulsa **Guardar**.
- El micrófono solo está activo en esta pantalla y solo cuando usted lo inicia; no hay escucha en segundo plano.
- Puede revocar el permiso en cualquier momento desde iOS *Ajustes &gt; MedTime*.

---

## 4. Informes de fallos (Sentry)

Para mejorar la estabilidad de la aplicación, se recopilan informes de fallos anónimos mediante el servicio **Sentry**.

**Datos recopilados:**
- Fecha y hora del fallo, modelo del dispositivo, versión de iOS, versión de la aplicación
- Mensaje de error y traza técnica de la pila (stack trace)
- Contexto técnico previo al fallo (p. ej., pantallas abiertas)

**Datos no recopilados:**
- Nombre de usuario, correo electrónico, dirección IP (`sendDefaultPii` desactivado)
- Capturas de pantalla, datos personales de medicación, datos de salud
- Fotos o contenido de informes

Los datos de Sentry se utilizan exclusivamente para la mejora de la aplicación; **nunca** para fines de marketing o publicidad. Los datos de Sentry se conservan durante un máximo de **90 días**.

Política de privacidad de Sentry: <https://sentry.io/privacy/>

---

## 5. Suscripción Premium y RevenueCat

MedTime ofrece una **suscripción Premium** opcional:

| Plan | Precio | Funciones |
|---|---|---|
| Mensual | aprox. $0.99 | Se renueva automáticamente |
| Anual | aprox. $5.99 | Incluye una **prueba gratuita de 7 días**, se renueva automáticamente |

### Gestión de la suscripción
- Las suscripciones se renuevan automáticamente; el pago se cargará a su cuenta de iTunes si no se cancela al menos **24 horas** antes del final del período en curso.
- Cancelar: *Ajustes → Apple ID → Suscripciones* en iOS.
- **En familia (Family Sharing)** está habilitado: una suscripción puede compartirse con hasta 5 miembros de la familia.
- Los pagos son procesados por Apple; MedTime no tiene acceso a la información de la tarjeta.

### Acceso gratuito de por vida para usuarios anteriores
Los usuarios que instalaron la versión **2.0.1 (build 5) o anterior** reciben automáticamente acceso **Premium gratuito de por vida**. Esto se verifica de forma anónima en el dispositivo mediante el campo `originalApplicationVersion` del recibo de Apple.

### RevenueCat (validación de la suscripción)
El servicio **RevenueCat** se utiliza para validar el estado de la suscripción. A RevenueCat se envían un identificador anónimo (App User ID) derivado de su Apple ID y los datos del recibo de Apple. Su nombre, correo electrónico o información de contacto **no se comparten**.

Política de privacidad de RevenueCat: <https://www.revenuecat.com/privacy/>

### Condiciones de uso
Se aplica el EULA estándar de Apple: <https://www.apple.com/legal/internet-services/itunes/dev/stdeula/>

---

## 6. Compartición de datos

MedTime **no comparte los datos de los usuarios con ningún tercero, no los vende ni los utiliza con fines de marketing**. Las únicas excepciones son:

- Las búsquedas en la base de datos de medicamentos descritas en la Sección 3.4 (NosyAPI / openFDA de la FDA de EE. UU. / AEMPS CIMA): solo se transmite el código escaneado o el nombre del medicamento buscado; no contiene ningún dato personal.
- Los informes de fallos anónimos descritos en la Sección 4 (Sentry).
- Los datos anónimos de validación de la suscripción descritos en la Sección 5 (RevenueCat + Apple).

---

## 7. Sus derechos en virtud del RGPD (usuarios de la UE)

Si reside en la UE, en virtud del Reglamento General de Protección de Datos (RGPD) tiene derecho a **acceder, rectificar, suprimir, oponerse al tratamiento y a la portabilidad de los datos**. Nuestras bases jurídicas son: la necesidad para la prestación del servicio (Artículo 6(1)(b)) y el interés legítimo para la notificación de errores (Artículo 6(1)(f)).

---

## 8. Sus derechos en virtud de la KVKK turca

En virtud del Artículo 11 de la Ley turca de Protección de Datos Personales (KVKK), usted tiene derechos que incluyen: saber si sus datos son tratados, solicitar información, solicitar la rectificación o supresión, conocer a los terceros a quienes se transfirieron los datos, oponerse a los resultados del tratamiento automatizado y reclamar una indemnización. Para ejercer estos derechos, póngase en contacto con <ilacvaktidestek@gmail.com>. Las solicitudes se responden en un plazo de **30 días**.

---

## 9. Privacidad de los menores

La aplicación tiene una clasificación de **4+**. No se recopilan datos a sabiendas de menores de 13 años. Si un progenitor utiliza la aplicación para añadir el perfil de un menor (miembro de la familia), los datos del perfil permanecen almacenados únicamente de forma local en el dispositivo.

---

## 10. Seguridad de los datos

Dado que sus datos se almacenan mayoritariamente en su dispositivo, están protegidos por el cifrado de hardware de iOS (Secure Enclave). La comunicación con los servicios de terceros está cifrada mediante HTTPS.

---

## 11. Cambios en esta política

Es posible que actualicemos esta política de vez en cuando. Los cambios significativos se anunciarán mediante una notificación dentro de la aplicación o en las notas de la versión. Por favor, revise periódicamente la fecha de *Última actualización*.

---

## 12. Contacto

Correo electrónico: <ilacvaktidestek@gmail.com>
