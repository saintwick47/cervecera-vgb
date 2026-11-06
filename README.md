# 🍺 Cervecera VGB

Aplicación de **recetas y gestión** para cerveceros artesanales: cálculo de receta
(OG, FG, IBU, SRM, color), agua de maceración, inventario con Kardex, cocciones
programadas, equipos y etiquetas de lote.

Disponible para **Windows**, **Linux** (Debian/Ubuntu, Fedora/openSUSE, AppImage) y
**Android**.

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

## 💡 Versión Free y versión Pro

- **Free**: probá la app completa con límites (10 recetas y 10 cocciones programadas).
- **Pro** (1 año): recetas y cocciones ilimitadas, exportación a PDF y BeerXML.
  Se activa con una **licencia** desde la pantalla “Versión / Licencia” de la app.

Para consultar por la versión Pro escribí a **nicoweb45@proton.me**.

## 🆘 Soporte

Errores, dudas o pedidos: **nicoweb45@proton.me** (Asunto: beer_vgb).
En la app, “Ayuda → Manual de Usuario” explica cada función.
