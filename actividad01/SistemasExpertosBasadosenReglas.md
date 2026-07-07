# Sistemas Expertos Basados en Reglas

Los sistemas expertos basados en reglas son herramientas diseñadas para tratar situaciones complejas que se rigen por leyes deterministas, como el control de tráfico o transacciones bancarias. Su funcionamiento se apoya en una base de conocimiento que contiene las reglas y un motor de inferencia que extrae conclusiones aplicando la lógica.

## Elementos de la Base de Conocimiento

El sistema se organiza en torno a dos componentes principales:
Hechos: Representan la información conocida para una situación particular. 
Son dinámicos, cambian según la aplicación y se almacenan en la memoria de trabajo.
Reglas: Son relaciones generales y estáticas entre objetos que no cambian a menos que el sistema aprenda. 
Tienen la estructura "Si premisa, entonces conclusión".
Premisa (antecedente): Expresión lógica que puede contener múltiples afirmaciones conectadas por operadores (y, o, no).
Conclusión (consecuente): La afirmación lógica que resulta si la premisa es cierta.

## El Motor de Inferencia

Es el componente que utiliza los hechos y las reglas para derivar nuevos conocimientos. 
Sus procesos principales incluyen el reconocimiento de patrones, la resolución de conflictos y la ejecución. 
Utiliza diversas estrategias:
Modus Ponens: Es la regla de inferencia más común; si la premisa es cierta, se acepta la conclusión. 
Se mueve hacia adelante, de la premisa a la conclusión.
Modus Tollens: Si la conclusión es falsa, se deduce que la premisa también lo es. 
Se mueve hacia atrás y requiere información sobre los objetos de la conclusión.
Mecanismo de Resolución: Se utiliza para obtener conclusiones compuestas basadas en dos o más reglas, combinando y simplificando expresiones lógicas.

## Estrategias de Encadenamiento

Para resolver problemas, el motor de inferencia puede seguir dos rutas:
Encadenamiento hacia adelante: Comienza con los hechos conocidos y ejecuta reglas para generar nuevos hechos hasta que no se puedan obtener más conclusiones. 
Se suele usar para diagnosticar resultados (como enfermedades) a partir de síntomas conocidos.
Encadenamiento hacia atrás (orientado a objetivos): El usuario selecciona una variable objetivo y el algoritmo busca en las reglas qué hechos se necesitan para alcanzarla. 
Es útil cuando se quiere determinar qué síntomas deben estar presentes para que una enfermedad sea posible.

## Coherencia y Explicación

Un aspecto crítico es el control de la coherencia, ya que reglas inconsistentes o hechos contradictorios pueden llevar a conclusiones absurdas. 
El sistema debe verificar que las reglas sean coherentes entre sí antes de incorporarlas y que los hechos suministrados por el usuario no contradigan las reglas existentes.
Finalmente, estos sistemas incluyen un subsistema de explicación. 
Dado que el motor conoce de qué regla procede cada conclusión, puede proporcionar al usuario una lista detallada de los hechos y las reglas utilizadas para justificar cómo llegó a un resultado determinado.


