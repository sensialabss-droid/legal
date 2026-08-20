# SensiaLabss — Legal

Páginas de **política de privacidad** y **condiciones de uso** de las apps publicadas,
servidas como sitio estático (GitHub Pages).

> ⚠️ **Este repositorio es PÚBLICO.** Solo debe contener las páginas de apps **ya publicadas**
> en Google Play. Las páginas de apps sin publicar se guardan fuera del repo, en
> `C:\Proyectos\legal-pendientes\`, y se traen aquí el día que la app sale.
> Motivo: el árbol de archivos, el índice y Google dejarían ver el catálogo de apps futuras.

## Apps incluidas

| App | Bundle ID | Privacidad | Condiciones |
|---|---|---|---|
| Finanzas Hogar | `com.sensialabs.finanzashogar` | `finanzashogar/privacy.html` | `finanzashogar/terms.html` |
| JubilaClaro | `com.sensialabs.jubilaclaro` | `jubilaclaro/privacy.html` | `jubilaclaro/terms.html` |
| RascaEspaña | `com.sensialabs.rascaespana` | `rascaespana/privacy.html` | `rascaespana/terms.html` |

> LuminAura tiene sus propias páginas aparte (suscripción); no se incluye aquí.

## URLs para pegar en Play Console

Base: `https://sensialabss-droid.github.io/legal/`

- Finanzas Hogar — privacidad: `.../finanzashogar/privacy.html` · condiciones: `.../finanzashogar/terms.html`

En Play Console, la **política de privacidad** se pega en *Contenido de la app → Política de privacidad*.

## Añadir una app nueva (el día que se publica)

1. Copiar su carpeta desde `C:\Proyectos\legal-pendientes\<app>\` a este repo.
2. Añadir su tarjeta a `index.html` y su fila a la tabla de arriba.
3. `git add -A && git commit -m "Publicar legal de <app>" && git push`.
4. Esperar 1–2 min a que GitHub Pages redespliegue y comprobar la URL antes de pegarla en Play.

## Publicar (GitHub Pages)

**Settings → Pages → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)`.
Web: `https://sensialabss-droid.github.io/legal/`

## Notas

- Email de contacto: `sensialabss@gmail.com`.
- Actualizar la fecha de "Última actualización" de cada página si se edita su contenido.
- Recomendable una revisión legal si el negocio escala (RGPD/LOPDGDD).
