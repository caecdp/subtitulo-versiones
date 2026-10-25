# Subtítulo para macOS

Instaladores y versiones públicas de Subtítulo. El código de la aplicación se conserva en un repositorio privado.

## Descargar e instalar

Consultar [la última versión](https://github.com/caecdp/subtitulo-versiones/releases/latest), descargar el archivo DMG, abrirlo y arrastrar Subtitulo a Aplicaciones. Reemplazar la versión anterior y expulsar la imagen de disco.

Requisitos: Mac con Apple Silicon y macOS 26 o posterior.

## Actualizar

En Configuración → Actualizaciones, seleccionar Buscar actualización. Si hay una versión nueva, seleccionar Descargar actualización y elegir dónde guardar el instalador. La primera vez se propone la carpeta Descargas del sistema; después se recuerda la última carpeta elegida. También se puede seleccionar una carpeta preferida desde esta sección. La búsqueda al iniciar es opcional y solo avisa: la descarga requiere una acción del usuario.

Abrir el instalador para completar el reemplazo. La aplicación verifica el tamaño y la huella SHA-256 antes de guardar. El origen de las actualizaciones está incorporado; no es necesario configurar ni introducir un repositorio.

## Firma y componentes de terceros

Esta distribución utiliza una firma local y no está notarizada por Apple. El DMG contiene FFmpeg como proceso separado, junto con su fuente original, la configuración de compilación y la licencia LGPL 2.1 o posterior, en la carpeta Terceros/FFmpeg.

No publicar claves, archivos de subtítulos, datos personales ni el código privado de la aplicación en este repositorio.
