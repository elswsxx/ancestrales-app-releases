# Ancestrales MG · Versiones de la app Android

Aquí se publican las versiones de la app **Ancestrales MG**, la app del club Ancestrales Motogrupo
para ver las cuotas, los pagos y las finanzas del club. Es solo para socios: para entrar hace falta
una cuenta que entrega el tesorero.

**Este repositorio no tiene código.** El código de la app es privado; aquí solo están los
instaladores (`.apk`) de cada versión y el archivo `latest.json` que la app consulta para avisar
cuando hay una versión nueva.

## Descargar la última versión

**[Ir a la última versión](https://github.com/elswsxx/ancestrales-app-releases/releases/latest)**
y, en «Assets», tocar el archivo `ancestrales-mg-vX.Y.Z.apk`.

Ábrelo desde el teléfono Android: el enlace descarga directo, sin cuenta de GitHub.

## Instalarla

1. Abre el `.apk` descargado (desde la notificación de descarga o la carpeta Descargas).
2. Si Android avisa que no puede instalar apps de esa fuente, toca **Configuración** y activa
   **Permitir desde esta fuente** para tu navegador. En algunos teléfonos está en Ajustes ›
   Aplicaciones › Acceso especial › Instalar apps desconocidas.
3. Vuelve atrás y toca **Instalar**.
4. Si Play Protect dice «app no reconocida», toca **Más detalles › Instalar de todas formas**. Pasa
   con toda app que no viene de Google Play.

Solo para Android. En iPhone la app todavía no está disponible.

## Actualizaciones

Cuando hay una versión nueva, la app lo avisa al abrirla («Hay una nueva actualización») con un
botón **Actualizar** que descarga el instalador. Se instala encima de la anterior: no pierdes nada,
tus datos están en el servidor del club.

Si tienes una versión anterior a la que trae el aviso, instala la última a mano una vez con los
pasos de arriba.

## Comprobar el archivo (opcional)

Cada versión trae en sus notas el **sha256** del `.apk`. Para comprobar que el archivo descargado
es el publicado:

```bash
shasum -a 256 ancestrales-mg-vX.Y.Z.apk    # macOS o Linux
certutil -hashfile ancestrales-mg-vX.Y.Z.apk SHA256    # Windows
```

Además, Android solo instala una versión nueva encima de la que tienes si está firmada con la misma
llave que la anterior.

## Problemas o dudas

Escríbele al tesorero del club.
