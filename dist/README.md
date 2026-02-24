# FamilyCell and Phone - GitHub Pages

## Instrucciones de despliegue

### Paso 1: Crear repositorio en GitHub
1. Ve a https://github.com/new
2. Nombra tu repositorio: `familycell` (o el nombre que prefieras)
3. Haz clic en "Create repository"

### Paso 2: Subir archivos
**Opción A - Por web:**
1. En tu nuevo repositorio, haz clic en "uploading an existing file"
2. Arrastra todos los archivos de esta carpeta `dist`
3. Escribe como mensaje: "Initial commit"
4. Haz clic en "Commit changes"

**Opción B - Por terminal (si tienes git instalado):**
```bash
cd dist
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/familycell.git
git push -u origin main
```

### Paso 3: Activar GitHub Pages
1. En tu repositorio, ve a **Settings** (pestaña superior)
2. En el menú lateral izquierdo, haz clic en **Pages**
3. En "Source" selecciona **Deploy from a branch**
4. En "Branch" selecciona **main** y carpeta **/(root)**
5. Haz clic en **Save**

### Paso 4: Esperar y acceder
- Espera 1-2 minutos
- Tu web estará en: `https://TU_USUARIO.github.io/familycell/`
- El enlace aparecerá en la misma página de Settings > Pages

---

## ¿Problemas con las imágenes?

Si las imágenes no cargan, verifica que:
1. Todas las imágenes `.jpg` estén en la raíz del repositorio
2. Los nombres coincidan exactamente:
   - hero_family.jpg
   - estetica_nails.jpg
   - estetica_lashes.jpg
   - ropa_rack.jpg
   - ropa_accessories.jpg
   - celular_repair.jpg
   - celular_accessories.jpg
   - computo_laptop.jpg
   - computo_peripherals.jpg
   - tv_living.jpg
   - tv_box.jpg
   - hogar_kitchen.jpg
   - hogar_cleaning.jpg
   - gadgets_earbuds.jpg
   - gadgets_watch.jpg
   - map_placeholder.jpg

---

## Personalizar dominio (opcional)

Si quieres usar tu propio dominio (ej: familycell.com):
1. Compra el dominio en Namecheap, GoDaddy, etc.
2. En Settings > Pages, escribe tu dominio en "Custom domain"
3. Configura los DNS según las instrucciones de GitHub
