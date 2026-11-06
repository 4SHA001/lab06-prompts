# Tarea: Mi prompt profesional

## Funcionalidad elegida

Software para registro de clientes de una clinica dental

## Version 1 prompt basico
```text
Actua como desarrollador java. Crea un programa de registro de clientes de una clinica dental en java
```
**¿Qué cambió?**
El codigo se estructuro en 3 archivos. Agrupando funciones y en un archivo para el registro de clientes.

**¿Por qué cambió?**
Al indicarle como desarrollador utilizo recursos de uno para evitar escribir el mismo codigo para cada cliente y optimizar la rapidez de ejecucion del codigo

**¿Qué mejoró en la respuesta?**
Optimizo el uso de funciones, un codigo ordenado

## Version 2: 
```text
Actua como desarrollador java. Crea un programa de registro de clientes de una clinica dental usando una clase Cliente con atributos nombre, edad, sexo y motivo de atencion.

```
**¿Qué cambió?**
Ahora volvio a un archivo y un poco menos de codigo, insertando lo requerido para la clase cliente

**¿Por qué cambió?**
Porque al especificarle una clase, adapto el codigo al uso de los atributos

**¿Qué mejoró en la respuesta?**
Optimizo usando los datos requeridos para representar a un cliente y no usar algunos datos extras, adaptando el codigo al uso de funciones para los atributos especificados que busca la clinica

## Version 3: prompt final

```text
Actúa como desarrollador Java. Crea un programa de registro de clientes de una clínica dental usando una clase Cliente con atributos nombre, edad, sexo y motivo de atención. Explica la lógica del programa, luego detalla la estructura de la clase y presenta el código Java . Usa este estilo para los metodos: getnombre(), setNombre(string nombre).  Restricción: No utilices librerías externas ni frameworks 
```
**¿Qué cambió?**
Incluyo una guia y la estructura que sigue el codigo.

**¿Por qué cambió?**
Por los requerimientos que se le pidio y deacuerdo al ejemplo brindado

**¿Qué mejoró en la respuesta?**
Se obtiene una breve explicacion de como va el codigo asi como su estructura, lo que hace entendible.

## Componentes del prompt final

| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol | Actua como desarrollador Java. Crea un programa en Java. |
| Instruccion |  Actua como desarrollador java. Crea un programa de registro de clientes de una clinica dental usando una clase Cliente con atributos nombre, edad, sexo y motivo de atencion. |
| Contexto | Actua como desarrollador java. Crea un programa de registro de clientes de una clinica dental. |
| Ejemplo | Actúa como desarrollador Java. Crea un programa de registro de clientes de una clínica dental usando una clase Cliente con atributos nombre, edad, sexo y motivo de atención. Explica la lógica del programa, luego detalla la estructura de la clase y presenta el código Java . Usa este estilo para los metodos: getnombre(), setNombre(string nombre). Restricción: No utilices librerías externas ni frameworks |
| Formato | Actúa como desarrollador Java. Crea un programa de registro de clientes de una clínica dental usando una clase Cliente con atributos nombre, edad, sexo y motivo de atención. Explica la lógica del programa, luego detalla la estructura de la clase y presenta el código Java. |

## Evaluacion del resultado
| Criterio | Prompt vago | Prompt estructurado |
|----------|-------------|---------------------|
| Menciona la logica del codigo | No | Si |
| Tiene un menu interactivo | Si | Si |
| Esta estructurado el codigo | Si | Si |
| Lo usaria en la vida real | No | Si |

## Errores que evite
- "Dar mas instrucciones de lo necesario". Habia visto que siendo demasiado especifico podria cambiar la estructura del codigo asi que di instrucciones claras sin tanto texto sin agregar funcionalidades extras que talvez podrian verse bien pero no ayudaria al codigo
- "No dar contexto". Explique para quien estaba destinado el programa y datos que se buscaba obtener.
