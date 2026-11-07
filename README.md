# 🍺 Cervecera VGB

Aplicación de **recetas y gestión** para cerveceros artesanales: cálculo de receta
(OG, FG, IBU, SRM, color), agua de maceración, inventario con Kardex, cocciones
programadas, equipos y etiquetas de lote.

Disponible para **Windows**, **Linux** (Debian/Ubuntu, Fedora/openSUSE, AppImage),
**macOS** (Apple Silicon) y **Android**. Funciona **sin conexión**.

## 📥 Descarga

Entrá a la pestaña **[Releases](https://github.com/saintwick47/cervecera-vgb/releases/latest)**
y elegí el archivo de tu sistema:

| Sistema | Archivo |
|---|---|
| Windows | `CerveceraVGB-Setup-X.Y.Z.exe` |
| Linux (Debian/Ubuntu/Mint) | `CerveceraVGB-X.Y.Z-x86_64.deb` |
| Linux (Fedora/RHEL/openSUSE) | `CerveceraVGB-X.Y.Z-x86_64.rpm` |
| Linux (otras) | `CerveceraVGB-X.Y.Z-x86_64.AppImage` |
| macOS (Apple Silicon) | `CerveceraVGB-X.Y.Z-macos-arm64.dmg` |
| Android | `CerveceraVGB.apk` |

Cada release incluye **`checksums.txt`** con el SHA-256 de todos los archivos.

## 🔐 Verificar la descarga (recomendado)

```bash
# Linux / macOS
sha256sum -c checksums.txt

# Windows (PowerShell)
Get-FileHash .\CerveceraVGB-Setup-X.Y.Z.exe -Algorithm SHA256
```

## 📱 Android

El APK se instala directamente (no requiere Play Store). Al instalar por primera vez,
Android puede pedir permiso para “instalar apps de origen desconocido”.

La app **avisa sola** cuando hay una versión nueva: descarga el APK, verifica su
SHA-256 y abre el instalador (el sistema pide tocar “Instalar”).

## 💡 Versión Free y versión Pro

- **Free**: probá la app completa con límites (10 recetas propias y 10 cocciones
  programadas). El recetario incluido (66 recetas) no cuenta para el límite.
- **Pro** (1 año): recetas y cocciones ilimitadas, y exportación a **PDF** y
  **BeerXML**.

### Cómo se activa el Pro

1. Abrí la app → **Ayuda → 🔑 Versión / Licencia** (en Android: **Ajustes → 🔑 Versión / Licencia**).
2. Copiá tu **ID de equipo** (botón “Copiar”) y escribinos a **nicoweb45@proton.me**.
3. Te devolvemos un **código de activación** que empieza con `VGBL-…`.
4. En esa misma pantalla pegá el código con **“📋 Pegar y activar”**.

**El año de uso corre desde que activás el código.** La verificación es **offline**:
no hay cuentas, ni nube, ni datos que salgan de tu equipo. Al vencer, la app vuelve
a Free **sin borrar** recetas, lotes ni inventario.

## 🖥️ Actualizaciones en PC

La app comprueba si hay una versión nueva al abrir y muestra un aviso discreto.
En Windows el instalador se ejecuta solo; en Linux/macOS abre el archivo ya
verificado (SHA-256 contra `checksums.txt`).

## 🌐 Idiomas

Español e **inglés**: se elige en **Herramientas → 🌐 Idioma** (PC) o
**Ajustes → 🌐 Idioma** (Android).

## 🆘 Soporte

Errores, dudas o pedidos: **nicoweb45@proton.me** (Asunto: beer_vgb).
En la app, **Ayuda → Manual de Usuario** explica cada función.

---

> Cervecera VGB es un programa propietario. La licencia de uso es personal y está
> atada al equipo; no se permite redistribuir el programa ni las claves.
