# Taller 1 – Teoría de juegos

Repositorio plantilla para entregar el taller en formato **Jupyter Notebook** con:
- **Lectura online (nbviewer)** y
- **Ejecución en la nube (Binder)**

---

## Enlaces rápidos
**Ver online (lectura):** https://nbviewer.org/github/Txpaz/Taller_1_Teoria_de_juegos/blob/HEAD/taller.ipynb  
**Ejecutar online (Binder):** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Txpaz/Taller_1_Teoria_de_juegos/HEAD?labpath=taller.ipynb)

> Si el nombre real del repositorio es distinto, actualiza `Txpaz/Taller_1_Teoria_de_juegos` en los enlaces.

---

## Instrucciones para el profesor
1. **Ver** el notebook en el enlace de nbviewer (no requiere instalar nada).
2. **Ejecutar** el notebook con el botón de Binder (abre un entorno con las dependencias).
3. Los datos (si aplica) están en la carpeta `data/` y se cargan con rutas relativas.

---

## Dependencias
Se instalan automáticamente en Binder desde `requirements.txt`:
- numpy
- pandas
- matplotlib

Versión de Python fijada en `runtime.txt`.

---

## Estructura del repo
```
Taller_1_Teoria_de_juegos/
├─ data/
│  └─ (datos opcionales; use muestras pequeñas)
├─ taller.ipynb
├─ requirements.txt
├─ runtime.txt
├─ .gitignore
└─ README.md
```

---

## Notas
- Evite subir archivos grandes (>50 MB). De ser necesario, use una URL pública o Git LFS.
- Para reproducibilidad, se fija `python-3.11`; puede cambiarse en `runtime.txt` si lo requiere.
