````ad-LIST
title: Diferencias entre C y C++ 2025-06-23 11:47

```ad-LIST-ITEM
title: C++
1. **Orientacion a objetos:** C++ es un lenguaje orientado a objetos (POO), permitiendo el uso de clases, herencia, polimorfismo, encapsulacion y sobrecarga de operadores

2. **Extensión del lenguaje: ** C++ Es una extension de C, por lo tanto, trae todo lo que contiene el mismo

3. **Bibliotecas estándar: ** Incluye una biblioteca estandar de plantillas (STL) que proporciona contenedores como `vector`, `map`, `sstream`, etc

4. **Gestión de memoria: ** C++ introduce operadores como `new` y `delete` para asignación dinamica de memoria, ademas de soportar el patron RAII (Resource Acquisition Is Initialization) para manejar recursos automaticamente

5. **Plantillas y genéricos: ** C++ soporta plantillas para programacion generica, permitiendo crear funciones o clases que operen con cualquier tipo de dato

6. **Manejo de errores: ** C++ incluye manejo de excepciones con bloques `try`, `catch` y `throw`

7. **Compatibilidad: ** C++ Puede compilar la mayor parte de codigo de C, pero no viceversa, aunque existe diferencias de reglas de sintaxis y semantica

8. **Aplicaciones típicas: ** **C++** es popular en aplicaciones complejas como videojuegos, sistemas de visualización 3D o frameworks que requieren POO y alto rendimiento

```

```ad-LIST-ITEM
title: C
1. **Orientacion a objetos:** C no es orientado a objetos, es un lenguaje procedural, basado en funciones y estructuras de datos, sin soporte nativo para POO

2. **Bibliotecas estándar: ** Carece de una biblioteca tan robusta, contiene nada mas que funciones basicas, y los programadores deben depender de ellas, si se requiere algo mas avanzado, se debe realizar por cuenta propia

3. **Gestión de memoria: ** C utiliza funciones como `malloc`, `calloc` y `free`, requiriendo un control manual mas estricto

4. **Plantillas y genéricos: ** C no tiene una característica equivalente, aunque se pueden simular con macros (`#define`) o punteros genéricos (`void*`)

5. **Manejo de errores: ** **C** no tiene soporte nativo para excepciones y se basa en códigos de retorno o variables globales como `errno`

6. **Aplicaciones típicas: ** - **C** se usa en sistemas embebidos, controladores y software de bajo nivel debido a su cercanía al hardware.
```


````

