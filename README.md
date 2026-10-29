# Sistema de Lluvias

## Archivos
- `index.html`: estructura de la página.
- `styles.css`: estilos y diseño visual.
- `script.js`: validaciones, cálculos, gráfica, clave de seguridad y cámara.

## Cómo ejecutar
1. Descomprime `PARCIAL2.zip`.
2. Abre la carpeta `PARCIAL 2`.
3. Haz doble clic en `index.html` para abrirlo en Chrome o Edge.
4. Para la cámara, algunos navegadores exigen una conexión segura (`localhost` o HTTPS). Si no funciona al abrir el archivo directamente, abre la carpeta en Visual Studio Code e inicia una extensión como Live Server.
5. La gráfica usa Chart.js desde un CDN, por lo que requiere internet.

## Datos de acceso
- Usuario: `Carlos`
- Contraseña: `1234`
- Clave para continuar registrando funciones: `CINE`

## Reglas incluidas
- Tarifa base inicial: $12.000 COP por boleta.
- Recaudación: cantidad de boletas × precio por boleta.
- Efecto de reloj de dos segundos antes de mostrar el resultado.
- Clave `CINE` después de cada cálculo. Si es incorrecta, muestra una alerta y regresa al login.
- Cambio de asiento: recargo del 5 % desde las 15:00 inclusive hasta antes de las 18:00.
- La gráfica de líneas y el historial se actualizan con cada función.
- La cámara permite capturar una foto del operador cuando se otorgan permisos.

## Nota académica
La autenticación es una validación del lado del navegador para fines de práctica; no es un sistema seguro para producción, porque las credenciales se pueden consultar en el código JavaScript. Los registros se guardan en memoria y se pierden al recargar la página.
