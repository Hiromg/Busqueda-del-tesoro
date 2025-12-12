WEB DIANA - Invitación Interactiva

Este repositorio contiene una invitación interactiva en formato web.

Contenido principal:
- INDEX.HTML: interfaz y lógica del juego
- img/: imágenes usadas en la web
- fonts/: fuentes locales (.woff2)
- scripts/: scripts de utilidad (descarga de fuentes, push a GitHub)

Cómo usar:
1. (Opcional) Ejecuta `scripts/download-fonts.ps1` para descargar las fuentes si no están en `fonts/`.
2. Sirve el proyecto localmente:
   ```powershell
   cd "c:\Users\romin\OneDrive\Escritorio\WEB DIANA"
   python -m http.server 8000
   ```
3. Abre `http://localhost:8000/INDEX.HTML`.

Subir a GitHub:
- Usa `scripts/push-to-github.ps1` para crear el repo y hacer push. Necesitas Git y un PAT con permisos `repo`.
- Alternativamente, hazlo manualmente con:
  ```powershell
  git init
  git add .
  git commit -m "Initial commit"
  git remote add origin https://github.com/tu-usuario/tu-repo.git
  git branch -M main
  git push -u origin main
  ```

Licencia: agrega aquí la licencia si corresponde.
