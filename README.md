# ANALISIS RENDIMIENTO ACADEMICO
## Descripcion del Proyecto:
![DesafioPropuesto](https://github.com/user-attachments/assets/5c724183-cfa4-48ab-9edb-3a0141daa05f)

 ## <h3 align='left'> Objetivos especificos como Analista De Datos</h3>
![Objetivos1](https://github.com/user-attachments/assets/4b6de322-791f-4895-ae43-416543b1d125)
![Objetivos2](https://github.com/user-attachments/assets/be9de0da-dd80-4703-8fdc-d8ac4e9f6ca9)
![Objetivos3](https://github.com/user-attachments/assets/2e59c0e9-efd9-495a-ab34-7acdaa0aabc8)

## <h3 align='left'> Diccionario </h3>
  Diccionario con sus respectivas variables con las que trabajaremos en este proyecto.
  ![Diccionario](https://github.com/user-attachments/assets/72cbf717-9d2b-4269-ae31-0d9d243c69c7)

## Desarrollo del Proyecto
  ## EDA (Analisis Exploratorio de los Datos)
  Este proceso consta de analizar relaciones y patrones realizando un análisis exploratorio más profundo para identificar relaciones y patrones interesantes entre variables.
  - **Histograma de Notas Finales:** El histograma muestra la distribución de las notas finales en el dataset. Los bins (contenedores) dividen el rango de valores en intervalos, y la altura de cada barra representa la frecuencia de notas en ese intervalo.
![histograma notas finales](https://github.com/user-attachments/assets/a78d3164-315a-486d-99ad-c7f52803e777)

  - **Grafico de Densidad:** El gráfico de densidad muestra una versión suavizada de la distribución de las notas finales, proporcionando una estimación de la densidad de probabilidad de las notas.
![Grafico de densidad](https://github.com/user-attachments/assets/0fc74316-48bc-46bc-94ac-8bee8d51382a)

 - **Boxplot:** El boxplot muestra la distribución de las notas finales según cada periodo académico. Permite identificar la mediana (línea central en la caja), los cuartiles (caja) y los valores atípicos (puntos fuera de los bigotes).
 ![boxplot](https://github.com/user-attachments/assets/8ef6b8dd-a4e5-4b1c-847f-b23bcca88a6e)

 ## Ingenieria de Caracteristicas
 Creamos nuevas caracteriasticas basados en el analisis exploratorio, sugerimos y creamos nuevas columnas que nos ayudaran en nuestra visualizacion.
- total_entregas
- total_examenes
- promedio_parcial
  
  ![columnas nuevas](https://github.com/user-attachments/assets/5db8bf31-7402-483a-9d43-d3551f92eed6)

## Implementacion y Escabilidad
Objetivo: Garantizar que el tablero sea interactivo y escalable, permitiendo una fácil actualización y exploración de los datos.
  
   **1. Resumen General**

- KPI Cards: Métricas clave como el promedio general de notas finales, promedio de notas parciales, total de entregas y total de exámenes.

 **2. Distribucion de Notas**

- Histograma de Notas Finales: Visualiza la distribución de las notas finales.
- Histograma de Notas Parciales: Visualiza la distribución de las notas parciales.
![Dashboard 1](https://github.com/user-attachments/assets/4908406f-1020-4d09-a9a8-858424f32cb0)

**3. Desempeño por Curso**
- Gráfico de Barras: Visualiza el promedio de notas finales y parciales por curso.

**4. Evolución Temporal**
- Gráfico de Líneas: Visualiza la evolución de las notas finales y parciales a lo largo de los diferentes periodos.

**5. Comparaciones y Segmentaciones**
- Segmentación por Periodo: Filtra los datos por semestre y año de cursado.
- Segmentación por Curso: Filtra y compara el rendimiento en diferentes cursos.
  
![dashboard 2](https://github.com/user-attachments/assets/cf471209-42ab-474f-8c8c-c522a9c22cde)


## Conclusiones del Tablero de Rendimiento Académico:
1. Promedios de Notas:

- **Promedio Nota Parcial:** 7.01
- **Promedio Nota Final:** 7.55
- **Conclusión:** Las notas finales son ligeramente superiores a las parciales, indicando una posible mejora en el rendimiento hacia el final del curso.

2. Participación en Actividades:

- **Total Entregas:** 2 millones
- **Total Exámenes:** 464 mil
- **Conclusión:** Alta participación en entregas y una cantidad significativa de exámenes, lo que sugiere un alto compromiso y actividad de los estudiantes.

3. Distribución de Notas:

- **Notas Parciales:** Mayoría entre 5 y 8.
- **Notas Finales:** Pico notable alrededor de 8.
- **Conclusión:** Las notas finales tienden a ser más altas, con menos estudiantes obteniendo calificaciones extremas.

4. Desempeño por Curso:

- **Comparación de Notas:** Promedios de notas finales y parciales son similares para la mayoría de los cursos.
- **Conclusión:** Rendimiento académico uniforme entre los cursos, con algunos cursos mostrando una ligera mejora en las notas finales.

5. Evolución Temporal:

- **Notas Finales:** Fluctuaciones a lo largo del periodo de cursado, con picos en ciertos días.
- **Entregas y Exámenes:** Incremento significativo en entregas hacia el final del curso.
- **Conclusión:** Posible sobrecarga de trabajo al final del curso, lo que puede afectar el rendimiento.

6. Segmentación:

- **Por Curso y Periodo:** Permite un análisis más detallado y específico.
- **Conclusión:** Herramienta útil para identificar áreas de mejora y éxito en el rendimiento académico.

## Resumen Global
**Mejora del Rendimiento:** Las notas finales son generalmente superiores a las parciales, indicando una mejora hacia el final del curso.

**Alta Participación:** La gran cantidad de entregas y exámenes refleja una alta participación y actividad de los estudiantes.

**Rendimiento Uniforme:** La mayoría de los cursos muestran un rendimiento académico consistente.

**Carga de Trabajo:** Hay un aumento significativo en la carga de trabajo hacia el final del curso, lo que podría afectar el rendimiento de los estudiantes.
