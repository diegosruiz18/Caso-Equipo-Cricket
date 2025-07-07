# Caso Equipo 11 Ideal de Cricket

📌 Disponible también en [Inglés](README.md) | 📌 Also available in [English](README.md)

Este dashboard permite visualizar las características más resaltantes de jugadores del mundial de cricket del 2022 para seleccionar los 11 mejores.
Las visualizaciones permiten realizar un análisis detallado por jugador, ver su rendimiento individual y también en equipo.

![](dashboard_analisis_jugadores.JPG)

![](dashboard_11ideal.JPG)

## Objetivo:

Analizar a los jugadores que tienen mejores puntuaciones en los indicadores clave, además dichos jugadores deben superar un umbral mínimo para ser considerados en el equipo final, los criterios se encuentran en el siguiente archivo: 📄 [Ver documentación en PDF](./Parametros.pdf). En base a este análisis se seleccionan a los 11 mejores jugadores de cricket.

## Roles de juego:
```
  • Bateador fuerte/Openers:      abren el partido y enfrentan las primeras bolas del juego.       
  • Ancla:                        bateadores más estables, controlan el ritmo del juego. 
  • Finalizador:                  cierran el inning y pueden estabilizar en situaciones críticas.         
  • Todoterreno:                  destacados tanto en bateo como en lanzamiento.                    
  • Lanzador rápido especialista: especializados en velocidad, clave para restringir al rival.
```

## Indicadores clave:
```
  • Promedio de bateo:             promedio de carreras anotadas por el bateador en cada entrada (innings).       
  • Tasa de bateo (strike):        número de carreras anotadas por cada 100 bolas enfrentadas.                    
  • Entradas bateadas:             número total de veces que un jugador ha participado como bateador.             
  • Promedio de bolas enfrentadas: promedio de bolas enfrentadas por el bateador por entrada.                     
  • % límite:                      porcentaje de carreras anotadas mediante límites (4s y 6s).                     
  • Posición de bateo:             posición en la que el jugador entra a batear (menor valor = más arriba).       
  • Entradas lanzadas:             número total de entradas (innings) en las que el jugador ha lanzado.           
  • Economía de lanzamiento:       promedio de carreras permitidas por over (6 bolas) lanzado.                    
  • Tasa de strike de lanzamiento: promedio de bolas que necesita un jugador para conseguir un wicket.            
  • Promedio de lanzamiento:       promedio de carreras permitidas por wicket conseguido.                         
  • Estilo de lanzamiento:         estilo de lanzamiento del lanzador (Fast, Spin, etc.).                           
  • % dot ball:                    porcentaje de bolas lanzadas donde no se concedieron carreras.
```

## Contenido del repositorio:

- `data_preprocessing.ipynb`: preprocesamiento de datos en Python
- `dashboard_cricket.pbix`: dashboard desarrollado en Power BI
- `Parameters.pdf`: documento PDF con los criterios de evaluación
- `📁data/csv`: carpeta con archivos CSV (dataset)
- `📁data/json`: carpeta con archivos JSON (dataset)

## Tecnologías y conocimientos aplicados:
  - Python (Preprocesamiento de datos con Pandas)
  - Google Colab
  - Power BI: ETL
  - Modelado de datos
  - DAX
  - Storytelling
