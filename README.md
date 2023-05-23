# Aprendiendo _Markdown_

<!-- Como generara parrafos-->

Esto es un parrafo.

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

<!-- Aplicando Cursiva a un texto-->

Aplicando _Cursiva_ y **negrita**.

Aplicando **_Cursiva y negrita al tiempo_**

<!--Crear Encabezados, Niveles de encabezado -->

# Encabezado Nivel 1

## Encabezado Nivel 2

### Encabezado Nivel 3

#### Encabezado Nivel 4

##### Encabezado Nivel 5

###### Encabezado Nivel 6

<!--Como colocar Enlaces -->

[Youtube...](https://www.youtube.com)

[Aprendiendo Markdown](#aprendiendo-markdown)

<!--Agregando imagenes -->

<!--Con ruta relativa-->

![logo Python](images/python_images.png)

<!--Con ruta web-->

![This is JavaScript](https://jonmircha.com/img/blog/this-is-javascript.jpg)

<!--Divisiones -->

---

Esto es un texto.

---

Este es otro texto.

<!--Listas -->

# Listas:

## Listas Ordenadas:

<!--Para trabajar con listas ordenadas basta con escribir 1. y markdown asume que es
una lista ordenada, no tienes que llevar la cuenta, el compilador lo hace por ti. -->

1. Primavera
1. Verano
1. Otoño
1. Invierno

<!-- Para trabajar con listas desordenadas hay dos opciones, utilizar asteriscos o
guiones -->

- Primavera
- Verano
- Otoño
- Invierno

* Primavera
* Verano
* Otoño
* Invierno

<!-- Para trabajar con sub-listas se utiliza la identacion. -->

- Primavera:
  - Abril
  - Mayo
  - Junio
    - 32
    - 4
    - 1

<!--Citas -->

<!--Citas de un renglon -->

> Siempre tienes opcion de no tener opinion. -Marco Aurelio.

<!-- Citas en bloque-->

> Todo lo que escuchamos es una opinion, no un hecho.
>
> Todo lo que vemos es una perspectiva, no la verdad.
>
> Marco Aurelio

<!-- Dibujar Tablas-->

| Nombre | Edad    | Correo                   |
| ------ | ------- | ------------------------ |
| Jhon   | 38 años | jonmicha@gmail.com       |
| jeifer | 20 años | jeifermartinez@gmail.com |
| carlos | 32 años | carlos@gmail.com         |

<!--Insertar codigo en Markdown-->

<!-- Insertar codigo en 1 linea-->

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,`let` when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

<!-- Insertar codigo en bloque-->

<!-- Incluso si sabes el lenguaje del codigo, luego de los primeros 3 acentos graves
colocar la extension del lenguaje y markdown le agrega sintasis-->

```py
def fun(a,b):
    sum = a+b
    return sum
```

<!-- Como comentario final sobre esta seccion. markdown tiene la capacidad de detectar  codigo html de forma nativa-->

<!-- Caracter de escape-->

**negrita:** \*\*negrita\*\*
_cursiva:_ \_cursiva\_
