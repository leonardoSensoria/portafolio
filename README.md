# Leonardo González · Portafolio

**Elevating the experience.** Portafolio de Leonardo González, Head of UX & Product Design.

Sitio estático de una sola página (HTML, CSS y JavaScript en un archivo). No necesita instalar nada ni compilar.

## Estructura

```
portfolio-leonardo/
├── index.html          Página principal
├── 404.html            Página de error con la misma identidad
├── favicon.svg         Ícono de la pestaña
├── .nojekyll           Le dice a GitHub Pages que sirva los archivos tal cual
└── assets/img/
    └── IMAGENES.md     Lista de imágenes con nombre, contenido y tamaño
```

## Publicar en GitHub Pages (sin usar la terminal)

1. Entra a github.com y crea un repositorio nuevo **público**.
   - Si lo llamas `TU-USUARIO.github.io`, la página queda en `https://TU-USUARIO.github.io`.
   - Si le pones otro nombre, por ejemplo `portafolio`, queda en `https://TU-USUARIO.github.io/portafolio`.
2. En el repositorio, da clic en **Add file → Upload files**.
3. Arrastra **el contenido** de la carpeta `portfolio-leonardo` (no la carpeta en sí) y da clic en **Commit changes**.
   - El archivo `.nojekyll` está oculto en Mac y Windows. Si no se sube, no pasa nada: la página funciona igual.
4. Ve a **Settings → Pages**. En *Source* elige **Deploy from a branch**, en *Branch* elige `main` y `/ (root)`, y guarda.
5. Espera uno o dos minutos y abre el link que aparece arriba en esa misma pantalla.

## Publicar con la terminal (opcional)

```bash
cd portfolio-leonardo
git init
git add .
git commit -m "Portafolio inicial"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
git push -u origin main
```

Después activa Pages como en el paso 4.

## Agregar imágenes

Guarda cada imagen en `assets/img/` con el nombre de `assets/img/IMAGENES.md` (por ejemplo `img-03.jpg`) y súbela al repositorio. La página reemplaza el placeholder sola; no hay que editar el HTML.

## Actualizar textos

Abre `index.html` en GitHub, da clic en el lápiz (*Edit*), cambia el texto y da clic en **Commit changes**. Los cambios se publican en uno o dos minutos.

- Textos de portada, impacto, liderazgo, IA, trayectoria y contacto: están directo en el HTML.
- Casos: están en la lista `CASES` dentro del `<script>`.
- Flujo de experimentación: está en la lista `XP` dentro del `<script>`.
- Pendientes: busca `class="pend"` para encontrar los datos que faltan.

## Dominio propio (opcional)

Si compras un dominio, por ejemplo `leonardogonzalez.com`, agrégalo en **Settings → Pages → Custom domain** y sigue las instrucciones de DNS de GitHub.

---

© 2026 Leonardo González
