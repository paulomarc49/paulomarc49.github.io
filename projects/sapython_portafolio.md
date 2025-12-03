<img src="https://raw.githubusercontent.com/paulomarc49/SAPython/main/assets/Logo_SAPython.png" width="300">
# 🛠 SAPhyton — Sistema de Mantenimiento Preventivo en Python

SAPhyton es una aplicación de escritorio que funciona como un **CMMS liviano**, permitiendo planificar, registrar y reportar mantenimiento preventivo.

# 🛠 1. Interfaces

## 1.1. Interfaz Principal

<img src="https://raw.githubusercontent.com/paulomarc49/SAPython/main/assets/main.png" width="300">

---

## 1.2. Plan de Mantenimiento Preventivo

- Importación de base de equipos desde Excel  
- Normalización automática de columnas  
- Cálculo del estado del equipo (Al día, Próximo, Pendiente)  
- Filtrado por ubicación  
- Asignación de fechas tentativas  
- Guardado en base **SQLite**  

**Vista del módulo:**

<img src="https://raw.githubusercontent.com/paulomarc49/SAPython/main/assets/plan_mantenimiento.png" width="1000">
<img src="https://raw.githubusercontent.com/paulomarc49/SAPython/main/assets/plan_guardado.png" width="1000">

---

## 1.3. Gestión de Cumplimiento

- Lectura del plan desde la BD SQLite  
- Marcar mantenimientos realizados  
- Registro automático de fecha de cumplimiento  
- Eliminación de registros seleccionados  

**Vista del plan guardado:**

<img src="https://raw.githubusercontent.com/paulomarc49/SAPython/main/assets/cumplimiento.png" width="600">

---

## 1.4. Generación de Informe LaTeX

Se carga una plantilla en LaTex con el formato del documento y en la sección de anexos se genera la información del plan de mantenimiento guardado en la base de datos de manera automática, el presente formato está optimizado para compilarse utilizando pdfLaTex con la ayuda de Overleaf:

- Inserta tablas dinámicas en LaTeX  
- Agrupación por ubicación  
- Uso de `\multirow`, tablas limpias y etiquetas  
- Escapa caracteres especiales  
- Inserción automática de:  
  - Período académico  
  - Fecha de presentación (en español)

**Vista del generador de informes:**

<img src="https://raw.githubusercontent.com/paulomarc49/SAPython/main/assets/generador_informe.png" width="500">

**Ejemplo compilado utilizando Overleaf:**

<img src="https://raw.githubusercontent.com/paulomarc49/SAPython/main/assets/ejemplo_informe.png" width="1000">

---

## 1.5. Resumen e Insights

- Totales de equipos  
- Porcentaje de cumplimiento  
- Equipos atrasados  
- Próximos a mantenimiento  
- Programa mensual  
- Vistas filtradas detalladas  

**Vista de la ventana de resumenes e insights:**

<img src="https://raw.githubusercontent.com/paulomarc49/SAPython/main/assets/insights.png" width="500">

<img src="https://raw.githubusercontent.com/paulomarc49/SAPython/main/assets/ver_proximos.png" width="500">


---

## 1.6. Acerca de

- Detalle de los créditos  

**Vista de la ventana acerca de:**

<img src="https://raw.githubusercontent.com/paulomarc49/SAPython/main/assets/acerca_de.png" width="300">

---


## ✔ Funcionalidades
- Plan de mantenimiento preventivo  
- Registro de cumplimiento  
- Resúmenes e insights  
- Informe automático en LaTeX  
- GUI completa en Tkinter  
- Base de datos en SQLite  

## 🔧 Tecnologías
Python · Tkinter · SQLite · Pandas · LaTeX

## 🔗 Repositorio
https://github.com/paulomarc49/sapython
