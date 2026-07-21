# Personalización rápida

## 1. Cambiar el usuario

Reemplaza todas las apariciones de `bi0punk` en:

- `README.md`
- `assets/terminal-profile.svg`

Comando Linux:

```bash
OLD_USER="bi0punk"
NEW_USER="tu_usuario"
find . -type f \( -name '*.md' -o -name '*.svg' \) -print0 \
  | xargs -0 sed -i "s/${OLD_USER}/${NEW_USER}/g"
```

## 2. Paleta de colores

| Uso | Color |
|---|---|
| Fondo principal | `#070B14` |
| Verde terminal | `#39FF14` |
| Cian | `#00E5FF` |
| Morado | `#B026FF` |
| Texto secundario | `#94A3B8` |
| Rojo de alerta | `#FF1744` |

## 3. Instalación como perfil de GitHub

1. Crea un repositorio público con el mismo nombre que tu usuario de GitHub.
2. Copia `README.md` y la carpeta `assets/` a la raíz del repositorio.
3. Haz commit y push.

```bash
git init
git add README.md assets/
git commit -m "feat: add cyberpunk GitHub profile"
git branch -M main
git remote add origin git@github.com:TU_USUARIO/TU_USUARIO.git
git push -u origin main
```

## 4. Compatibilidad

- GitHub renderiza el SVG directamente desde el repositorio.
- La animación del cursor depende del renderizado SVG del navegador.
- Los badges y estadísticas usan servicios externos; pueden tardar unos segundos en cargar.
