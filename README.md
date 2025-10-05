# Simulación de un Ensayo Aleatorizado en R  

Este proyecto muestra cómo **simular una base de datos** en **R** para representar un **ensayo clínico aleatorizado**.  
El objetivo es generar una muestra de **1000 estudiantes** y evaluar si **cambiar el horario de clases de Bioestadística de los sábados a los miércoles** influye en las notas finales del curso.  

---

## Objetivos  
- Simular variables sociodemográficas y académicas (edad, género, procedencia, tercio).  
- Realizar una **aleatorización balanceada 1:1** entre grupos.  
- Generar un archivo **Excel reproducible** con la información simulada.  
- Documentar el proceso en un script `.qmd` totalmente reproducible (`set.seed(2025)`).  

---

## Contenido del repositorio  
```
📁 /
├── base_ensayo_clinico_bioestadistica.qmd   # Script principal en RMarkdown
├── base_ensayo_clinico_bioestadistica.xlsx  # Archivo generado con 4 hojas
└── README.md
```

---

## Requisitos  
Asegúrate de tener instalados los siguientes paquetes antes de ejecutar el script:  

```r
install.packages(c('tidyverse', 'writexl'))
```

---

## Ejecución  
1. Abre el archivo `.qmd` en **RStudio** o tu editor favorito.  
2. Ejecuta todo el código o compila el documento (Render).  
3. Se generará automáticamente un archivo llamado  
   **`base_ensayo_clinico_bioestadistica.xlsx`**, que contiene:  

   - `1_DATOS_CODIFICADOS`: Base de datos numérica  
   - `2_DATOS_ETIQUETADOS`: Base de datos con etiquetas descriptivas  
   - `3_METADATA_VARIABLES`: Descripción de cada variable  
   - `4_INFO_ESTUDIO`: Información general del estudio  

---

## Detalles del estudio  
- **Diseño:** Ensayo clínico aleatorizado (simulado)  
- **Tamaño de muestra:** 1000 individuos  
- **Exposición:** Horario de laboratorio 2 (`0 = sábado`, `1 = miércoles`)  
- **Desenlace:** Nota final del curso (escala 9–20)  
- **Confusores:** Edad, género, procedencia, tercio académico  
- **Semilla reproducible:** `set.seed(2025)`  

---

ence #Bioestadística #EnsayoClinico #SimulaciónDeDatos  
", "README.md")
