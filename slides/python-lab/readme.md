class: center, middle
# Introducción a Python

---

class: left

# Agenda

- Tipos de datos
- Operadores aritméticos
- Operadores lógicos
- Estructuras de datos
- Estructuras de control
  - Condicionales
  - Iterativas
-  Funciones
  - Funciones Lambda
---

class: left

# Tipos de datos

En Python existen tipos de datos básicos: los números, booleanos y las cadenas. Dentro 
de la categoría de números encontramos los **int, float** y las **string**, que son 
secuencias de caracteres envueltas entre comillas simples o dobles.


```python
mi_entero = 5
mi_flotante = 6
mi_cadena_comillas_simples = 'Hola'
mi_cadena_comillas_dobles = "Hola"
```
---

# Operadores aritméticos

En Python encontramos los operadores básicos para realizar operaciones como la suma, 
la resta, multiplicación y división.

💡 Actividad: Realizar una calculadora con las 4 funciones básicas.

---

# Operadores lógicos

En Python tenemos disponibles **and, or y not**

---

# Estructuras de datos

Las estructuras de datos son formas de organizar la información. En Python tenemos 
implementadas por default las **listas, tuplas, diccionarios y conjuntos**

## Listas

Las listas en Python son una secuencia de datos entre corchetes.

```python
mi_lista = [1, 2, 3, 4]
```

---

## Tuplas

Las tuplas son secuencias de datos separadas por coma, para mayor legibilidad se agregan
parentesis a la definición de la tupla. La diferencia entre listas y tuplas es que las 
primeras son mutables y las segundas inmutables.

```python
mi_tupla = (1, 2, 3, 4)
```

## Conjuntos

Un conjunto es una colección de datos no ordenados donde no existen elementos duplicados.

```python
mi_conjunto = {1, 2, 3, 5}
```

---

## Diccionarios

Los diccionarios son colecciones de datos formados por pares de llaves y valores.

```python
fulanito = {"nombre": "Fulanito", "apellido": "de Tal", "color_favorito": "naranja"}
```

---

# Estructuras de control

