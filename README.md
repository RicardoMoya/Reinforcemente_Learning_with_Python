# Reinforcement Learning (Aprendizaje por Refuerzo), con Python

* Autor: Ricardo Moya García, PhD
* Fecha última actualización: 22-04-2022
* ![python versions](https://img.shields.io/badge/python-3.6%2C%203.7-blue.svg)


<hr>

En este proyecto de GitHhub podrás encontrar parte del material que utilizo para impartir las clases del módulo introductorio de Reinforcement Learning (Aprendizaje por Refuerzo)


El contenido compartido es el siguiente: 


#### Notebook 1: Aprendizaje por Refuerzo: Introducción

* Notebook: [1_Aprendizaje_Por_Refuerzo.ipynb](https://github.com/RicardoMoya/Reinforcemente_Learning_with_Python/blob/master/1_Aprendizaje_Por_Refuerzo.ipynb)

1. ¿Qué es el Aprendizaje por Refuerzo? - Ciclo de Vida
2. Elementos y Terminología en el Aprendizaje por Refuerzo
3. Explorar vs Explotar<br>
5. Q-Function: State-Action Value Function
6. Q-Table
7. Algoritmos: Q-Learning y SARSA Learning


#### Notebook 2.1: Ejemplo: Algoritmos de Aprendizaje por Refuerzo: Q-Learning y SARSA

* Notebook: [2_01_Ejemplo_Algoritmos_Aprendizaje_Por_Refuerzo_Q_LEARNING_y_SARSA.ipynb](https://github.com/RicardoMoya/Reinforcemente_Learning_with_Python/blob/master/2_01_Ejemplo_Algoritmos_Aprendizaje_Por_Refuerzo_Q_LEARNING_y_SARSA.ipynb)

1. Definición del entorno
2. Implementación de un algoritmo de toma aleatoria de acciones
3. Ejecución: Entorno - Agente
4. Q-Learner: Implementación y Ejecución
5. SARSA-Learner: Implementación y Ejecución
6. Estrategias a corto y largo plazo


#### Notebook 2.2: EDeep Q-Learning

* Notebook: [2_02_Deep_Q-Learning.ipynb](https://github.com/RicardoMoya/Reinforcemente_Learning_with_Python/blob/master/2_02_Deep_Q-Learning.ipynb)

1. Algoritmo del Deep Q-Learning
2. Implementación y Ejemplo del Deep Q-Learning


#### Notebook 3: Multi-Armed Bandit (MAB): Ejemplo

* Notebook: [3_Multi-Armed_Bandit.ipynb](https://github.com/RicardoMoya/Reinforcemente_Learning_with_Python/blob/master/3_Multi-Armed_Bandit.ipynb)


#### Notebook 4: Resolución de juego GYM (Open AI)

* Notebook: [4_01_RL_Lunar_Lander_GYM_Stable_BaseLine.ipynb(https://github.com/RicardoMoya/Reinforcemente_Learning_with_Python/blob/master/4_01_RL_Lunar_Lander_GYM_Stable_BaseLine.ipynb)
* Notebook: [4_02_RL_SpaceInvaders_GYM_KerasRL.ipynb(https://github.com/RicardoMoya/Reinforcemente_Learning_with_Python/blob/master/4_02_RL_SpaceInvaders_GYM_KerasRL.ipynb)



<hr>

## Instalación del entorno

Para ejecutar los notebooks de este proyecto es necesario tener creado un entorno virtual con conda 
(también puede ser con un virtualenv), en el que a parte de tener instaladas las librerías que te instala anaconda 
por defecto al crear el entorno (numpy, scipy, pandas, matplotlib, scikit, etc) hay que instalar una serie de 
librerías específicas que se indican en el fichero requirements.txt.

A continuación se muestran los pasos a seguir para crear el entorno virtual con conda por medio de una consola:


<hr>

## Instalación Entorno Virtual Conda 

* Pasos para la creación de un Virtualenv con conda e instalación de las librerías necesarias

1.- Creación del entorno virtual "*Python37_RL*" con un python 3.7
```
>> conda create -n Python36_RL python=3.7 anaconda
```

2.- Activar el entorno virtual

```
>> conda activate Python37_RL
```
