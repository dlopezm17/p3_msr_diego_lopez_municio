# Práctica 3: Modelado y Simulación de Robots

## Parte A

Imagen de las transformadas del robot  
👉 [Ver transformadas en PDF](data/rover_frames.pdf)  

Imagen del modelo del robot:  
![Modelo del robot](data/rover_model.png)

Imagen de las `tf` del robot:  
![Transformaciones del robot](data/rover_tfs.png)

---

## Parte B

Se puede ver que las ruedas derechas primero están en reposo. Tras esto empiezan a rotar en sentido negativo, con pequeños momentos de pausa dado que estaba colocando el robot y no quería pasarme demasiado. Al final se observa que retrocede un poco dado que había dejado el cubo algo atrás.

**Rueda delantera derecha**  
![Rueda delantera derecha](data/plot_del_der.png)

**Rueda central derecha**  
![Rueda central derecha](data/plot_cen_der.png)

**Rueda trasera derecha**  
![Rueda trasera derecha](data/plot_tras_der.png)

Las ruedas izquierdas siguen el mismo patrón, pero dado que su eje Z apunta en la dirección opuesta, al moverse el signo está invertido con respecto a las ruedas derechas.

**Rueda delantera izquierda**  
![Rueda delantera izquierda](data/plot_del_iz.png)

**Rueda central izquierda**  
![Rueda central izquierda](data/plot_cen_iz.png)

**Rueda trasera izquierda**  
![Rueda trasera izquierda](data/plot_tras_iz.png)


No puedo añadir una imagen del robot cogiendo la caja o de la gráfica que muestre el gasto pracial en el tiempo dado que no he logrado que el robot ejecute las trayectorias una vez planificadas.


[Rosbag de la ejecución de la práctica](https://urjc-my.sharepoint.com/:f:/g/personal/d_lopezm_2022_alumnos_urjc_es/ErMHlDa3HJNNtZf15pczcjMBOtxUywlsjJ3Jw8LkqS-MvA?e=a9YT0R)
