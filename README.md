# Landing de Wallsmith

Página estática autocontenida (index.html + privacy.html + icon.png).
Sin dependencias ni build: se publica copiando los 3 archivos.

**privacy.html es la URL pública de privacidad que exige Partner Center**
(campo "Privacy policy URL" de la ficha de la Store).

## Cómo publicarla (el repo principal es privado; GitHub Pages gratis
requiere repo público)

Opción recomendada — repo público solo para el sitio:

1. Crear repo público `j-paniagua/wallsmith-site`.
2. Copiar `index.html`, `privacy.html` e `icon.png` a su raíz.
3. Settings → Pages → Deploy from branch `main` → `/ (root)`.
4. URLs resultantes:
   - `https://j-paniagua.github.io/wallsmith-site/`
   - `https://j-paniagua.github.io/wallsmith-site/privacy.html` ← para
     Partner Center.

Alternativas equivalentes (también gratis): Cloudflare Pages o Netlify
arrastrando la carpeta.

Pendiente cuando existan (ROADMAP #2): incrustar el GIF demo de 15 s y
las capturas neutras en index.html.
