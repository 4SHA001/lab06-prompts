# Bitacora de prompts

Laboratorio 06: Fundamentos de Ingenieria de Prompts.
Herramienta de IA usada: (google gemini)

## Ejercicio 2: Tokens y ventana de contexto

| Texto | Caracteres | Tokens |
|-------|------------|--------|
| Los estudiantes programan en Java. | 34 | 7 |
| The students program in Java. | 29 | 6 |
| desafortunadamente | 18 | 4 |

## Ejercicio 3: Temperatura

| Temperatura | % de BiblioTec | Nombres en los 5 intentos |
|-------------|----------------|---------------------------|
| 0 | 100 | BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec |
| 0.5 | 65.3 | BiblioTec, LibroYa, BiblioTec, BiblioTec, LibroYa |
| 1 | 44.5 | LibroYa, PrestaLibro, BiblioTec, NubeDeTinta, LectoGo |
| 1.8 | 32.2 | LibroYa, BiblioTec, LibroYa, PrestaLibro, NubeDeTinta |

## Ejercicio 4: Prompt vago vs estructurado

| Criterio | Prompt vago | Prompt estructurado |
|----------|-------------|---------------------|
| Menciona el objetivo del sistema | Si | Si |
| Menciona a los usuarios principales | No | Si |
| Tiene exactamente 3 funcionalidades | No | Si |
| Esta en 3 parrafos | No | Si |
| Lo usaria en un informe real | No | Si |

## Ejercicio 5: Anatomia de un prompt

| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol | Actua como desarrollador Java. Crea un programa en Java. |
| Instruccion |  Actua como desarrollador Java. Crea un programa en Java para gestionar los productos de una tienda usando una clase Producto con los atributos codigo, nombre, precio y stock. |
| Contexto | Actua como desarrollador Java. Crea un programa en Java para gestionar los productos de una tienda. |
| Ejemplo | Actua como desarrollador Java. Crea un programa en Java para gestionar los productos de una tienda  usando una clase Producto con los atributos codigo, nombre, precio y stock. Explica primero la estructura de la clase y luego presenta el codigo Java. Usa este estilo para los metodos: getPrecio(), setPrecio(double precio). |
| Formato | Actua como desarrollador Java. Crea un programa en Java para gestionar los productos de una tienda  usando una clase Producto con los atributos codigo, nombre, precio y stock. Explica primero la estructura de la clase y luego presenta el codigo Java. |

nivel 1 - creo un programa "adivina el numero" de pocas lineas

nivel 2- mostro un programa de mas lineas que el anterior

nivel 3- creo un programa con 3 archivos java y varias lineas de codigo

nivel 4- lo estructuro en un solo archivo java, con menos lineas de codigo que el anterior usando los atributos y clase que se indico

nivel 5- mostro un codigo mas estructurado de acuerdo a las instrucciones y menos lineas que el anterior nivel