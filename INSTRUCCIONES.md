# Instrucciones — Activar GitHub Pages

El repositorio ya tiene el workflow en `.github/workflows/pages.yml`. Solo falta activarlo una vez:

1. Entra a https://github.com/diegovargasmkt/propuestas/settings/pages
2. En **Build and deployment**, Source elige **GitHub Actions**.
3. Guarda. GitHub va a correr el workflow automáticamente.
4. En la pestaña **Actions** del repo, espera a que el run termine en verde.
5. Abre https://diegovargasmkt.github.io/propuestas/

Si ya lo activaste y sigue en 404, dale a **Re-run all jobs** en el último workflow run.
