# 🚛 Aplicación Web: Validación LUP - GASEOSAS LUX SUR

> Una aplicación web **offline**, sin servidor, que reemplaza el formato Excel `4-FORMATO LUP CONDICIONES RECIBO 55 (1).xlsx` para validar condiciones de recepción en zonas.

---

## ✅ Características

- ✅ Valida 9 condiciones por zona (CABINA, CARROCERÍA, ESTIBAS, UBICACIÓN, ARRUMES, CALIDAD, ORDEN, CORTINAS)
- ✅ **Solo 2 imágenes por vehículo**: lado derecho e izquierdo (¡nuevo flujo simplificado!)
- ✅ Guarda datos automáticamente en el navegador (`localStorage`)
- ✅ Previsualiza imágenes cargadas
- ✅ Genera un **PDF profesional en una sola página** con:
  - Tabla completa del Excel
  - Columna "EVIDENCIA" con íconos 📷/⚠️/❌
  - Secciones MB51, ZBVRE230 y MONITORDOC
- ✅ Funciona **sin internet** — solo abre el archivo `.html` en cualquier navegador
- ✅ Compatible con Chrome, Firefox, Edge

---

## 📥 Cómo usarlo

1. Descarga el archivo [`index.html`](index.html)
2. Haz doble clic sobre él → se abrirá en tu navegador
3. Selecciona una zona → marca 1 o 0 en cada condición
4. Sube **dos fotos**:  
   👉 Lado derecho del vehículo  
   👉 Lado izquierdo del vehículo  
5. Haz clic en **"Guardar Validación"**
6. Haz clic en **"Generar Reporte PDF"** → se descargará automáticamente

---

## 💡 ¿Para quién es?

- Supervisores de recepción en bodegas
- Logística y calidad de GASEOSAS LUX SUR
- Auditores internos

---

## 📌 Nota técnica

- No requiere instalación, base de datos ni servidor.
- Todos los datos se almacenan localmente en tu computadora.
- Para compartir resultados: envía el archivo `index.html` y los PDFs generados.

---

© 2025 GASEOSAS LUX SUR – Departamento de Empaque y Producto  
Desarrollado con HTML5, JavaScript y jsPDF.
