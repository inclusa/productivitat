# Colonias productivas


## 01 Hormigas

Alfons Rovira, [05.03.17 08:36]
#colonias_productivas
#hormigas

En el mundo natural, las homigas, inicialmente, vagan de manera aleatoria. Cuando encuentran la compida regresan a su colonia dejando un rastro de feromonas.

Si otras hormiagas encuentran dicho rastro, es probable que estas no sigan el camino aleatoriamente, puede que sigan el rastro de deromonas, reforándolo, si encuentran comida finalmente.

Con el paso del tiempo, el rastro de feromonoas comienza a evaporarse, reduciéndose así su fuerza de atracción.

Al evaporarse las feromonas se determina un tiempo limitado a la solución.

El flujo de hormigas y su cantidad determinará el camino más corto, optimizando la energia liberada para la recolección de alimento.

Este fenómeno llamado ESTIGMERGIA se utiliza en sociedades de animales.

Es un sistema de resolución de problemas AUTOORGANIZADO, basado en la RETROALIMENTACIÓN POSITIVA (feromonas) y la RETROALIMENTACIÓN NEGATIVA (evaporación).

El algoritmo implica que cada hormiga, de manera incremental, constituye una solución del problema.

Fases:

1. Construcción de la ruta
2. Evaluación de la mejor ruta
3. Modificación de la ruta

#algoritmo

  procedure ACO_MetaHeuristic
    while(not_termination)
       generateSolutions()
       daemonActions()
       pheromoneUpdate()
    end while
  end procedure

https://es.wikipedia.org/wiki/Algoritmo_de_la_colonia_de_hormigas
