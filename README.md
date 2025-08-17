# 🧮 CLASIFICADOR REMASEP

Aplicación web para **clasificar pacientes** por **rango de edad, sexo, embarazadas y migrantes**, considerando la columna **Cantidad** como “pacientes equivalentes”.

## 🚀 Funcionalidades
- Clasificación automática por rangos de edad predefinidos.
- Conteo por **Hombres**, **Mujeres**, **Embarazadas**, **Migrantes**.
- Acepta `Sexo` o `Género` como encabezado.
- **Excluye registros sin edad**.
- Exporta la tabla a **Excel (.xlsx)**.
- Botones: **Clasificar**, **Borrar**, **Subir archivo**.

## 📦 Archivos
- `index.html` → App completa (HTML+CSS+JS).
- `README.md` → Este documento.

## 🛠️ Uso en local
1. Abre `index.html` en tu navegador.
2. Pega tus datos (o sube un CSV/Excel).
3. Clic en **Clasificar** y luego, si quieres, **Descargar Excel**.

## 🌐 Publicación en GitHub Pages
1. Sube `index.html` y `README.md` al repo (público).
2. **Settings → Pages → Build and deployment**  
   - Source: *Deploy from a branch*  
   - Branch: `main` • Folder: `/ (root)` • **Save**
3. Abre la URL que muestra GitHub Pages (ej: `https://tuusuario.github.io/turepo/`).

## ✅ Ejemplo de entrada (CSV)
```csv
Nombre,Sexo,Edad,Embarazada,Migrante,Cantidad
JULIO VERDUGO ORTEGA,Hombre,65,NO,NO,5
YESSENIA URRUTIA,Mujer,33,NO,NO,1
PEDRO BELMAR,Hombre,,NO,NO,1
