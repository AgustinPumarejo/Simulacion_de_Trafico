# Simulación de Tráfico

## Equipo
### Integrantes
#### Fernanda Nava Moya A01023896
* Fortalezas: trabajo en equipo, comunicación, organización, algoritmos
* Áreas de oportunidad: Unity
#### Agustín Pumarejo Ontañón A01028997
* Fortalezas: Unity, Mesa
* Áreas de oportunidad: 
#### Adriana Abella Kuri A01329591
* Fortalezas: comunicación, algoritmos
* Áreas de oportunidad: organización, concentración, manejo de tiempo

### Expectativas
* Dominar el diseño y modelado de objetos 3D en movimiento en Unity
* Aprender a animar los objetos en Unity
* Crear agentes capaces de interactuar entre sí que puedan tomar decisiones con base en su entorno
* Conectar los conocimientos de sistemas multiagentes con el modelado 3D utilizando Unity
* Proponer una solución creativa al reto que se nos presenta

### Compromisos
* Mantener buena comunicación dentro de nuestro equipo de trabajo
* Tener buena organización para trabajar de manera correcta y entregar los trabajos a tiempo
* Dividir la carga de trabajo de manera equitativa entre todos los integrantes del equipo

## Propuesta del reto
### Descripción
Propuesta de solución a problemas de movilidad urbana en la Ciudad de México debido al gran incremento de tráfico de vehículos. Se presentera esta solución a través de una simulación de tráfico con agentes reactivos creados con ayuda de Mesa en Python, con gráficas computacionales 3D creadas en Unity.

### Agentes involucrados
#### Carril
* Estado de congestión (bajo, moderado, alto)
* Longitud en metros
* Se calcula su nivel de congestión dependiendo de su longitud y el número de vehículos encima de él
#### Semáforo
* Estado (rojo, verde)
* Cambia de estado cada determinado tiempo
#### Vehículo
* Estado (andando, detenido)
* Dirección y sentido
* Avanza o se detiene en los carriles dependiendo del estado de los mismos y del estado de los semáforos
