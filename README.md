# Copa Hispánica web

## Estructura
- `index.html`: página principal multi-temporada.
- `results.json`: temporada actual (T61).
- `archive/t60-results.json`: archivo histórico de la T60.
- `t60-results.json`: copia de seguridad/fallback para T60.
- `sanctioned-logo.png`: debe seguir en la raíz del repo.

## Publicación en GitHub Pages
1. Copia `index.html`, `results.json`, `t60-results.json` y la carpeta `archive/` a la raíz del repositorio.
2. Mantén `sanctioned-logo.png` en la raíz.
3. Commit + push a `main`.

## Temporadas
- URL normal: Temporada 61.
- `?season=60`: Temporada 60 archivada.

## Actualizar resultados T61
Edita `results.json`:
- `pL`, `pV`: marcador.
- `tL`, `tV`: tries.
- `estado`: cambiar a `finalizado`.
