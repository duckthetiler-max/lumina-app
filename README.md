# Lumina — published site

This repository holds **only the built output** of Lumina, published to GitHub
Pages. It is public because GitHub Pages on the Free plan cannot serve from a
private repository; the compiled bundle is what a browser downloads anyway.

**The source is private** and lives in `duckthetiler-max/lumina`. Do not edit
anything here by hand — it is overwritten on every publish. Build from source
with `LUMINA_BASE=/lumina-app/ npm run build`, then publish the `dist/` output.

Live: https://duckthetiler-max.github.io/lumina-app/
