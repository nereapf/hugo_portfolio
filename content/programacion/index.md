+++
title = "Programación"
+++

# Desarrollo web en entorno servidor

En este módulo se imparte el lenguaje de programación de PHP.  
PHP es un lenguaje de scripting que se ejecuta en el servidor y genera HTML, CSS, JavaScript y otros contenidos para enviar al navegador del usuario.
## **PHP**
Es un lenguaje de programación destinado a desarrollar aplicaciones para la web y crear páginas web.
Originalmente, se creó para generar contenido dinámico en sitios web, y hoy en día es una de las tecnologías más comunes para desarrollar aplicaciones y servicios web interactivos.  

- **Desarrollo de sitios web dinámicos:** PHP genera contenido personalizado para cada usuario, como páginas de inicio de sesión, paneles de usuario, y perfiles personalizados.
- **Manejo de bases de datos:** Con PHP, puedes conectarte a bases de datos (como MySQL o PostgreSQL) para almacenar, recuperar y manipular datos de usuarios, productos, comentarios, etc.
- **Automatización de tareas en el servidor:** PHP puede programarse para realizar tareas repetitivas, como enviar correos electrónicos, generar informes o procesar archivos.

Un ejemplo básico de php es generar un mensaje:
```markdown
<?php
    $nombre = "Nerea";
    echo "¡Hola, $nombre! Este mensaje está hecho con PHP.";
?>
```
  
También con php se pueden crear páginas junto con html y css un poco más complejos como 
generadores de números random, imprimir números y textos con formatos y colores y muchas otras cosas.  

Además de esto también se pueden implementar otras funcionalidades.

#### Funciones
Las funciones en PHP son bloques de código que realizan una tarea específica, las cuales pueden conseguir crear 
aplicaciones funcionales para el usuario junto a html y css.  

**INTEGRADAS**  
Existen diferntes funciones tanto para textos, números, arrays, etc...
```markdown
<?php
    //contar números
    $numeros = [1, 2, 3, 4, 5];
    echo count($numeros);

    //tipo fecha (año-mes-día)
    echo date("Y-m-d");

    //número aleatorio
    echo rand(1, 100);
?>
```

**DEFINIDAS POR EL USUARIO**  
Se pueden crear unciones para realizar cosas específicas, este es ejemplo de una básica.
```markdown
<?php
    function suma($numero1, $numero2) {
    $resultado = $numero1 + $numero2;
    return $resultado;
}
?>
```

#### Orientado a objetos  

En PHP orientado a objetos existen unos conceptos básicos.  
- Clase: Plantilla para crear objetos
- Objeto: Instancia de una clase
- Método: Funciones ubicadas dentro de las clases
- Contructor: Método especial para inicializar las propiedades de la clase
- To string: Método especial para mostrar por pantalla la clase

Además de los conceptos básicos también existe la herencia, abtracción y más, pero este es un ejemplo básico.

```markdown
<?php
class Persona {
    public $nombre;
    public $edad;

    public function __construct($nombre, $edad) {
        $this->nombre = $nombre;
        $this->edad = $edad;
    }

    public function __toString() {
        return "Persona con nombre, $this->nombre tiene $this->edad años.";
    }
}

// Crear un objeto de la clase Persona para poder mostrarlo
$persona = new Persona("Nerea", "19");
echo <p>$persona</p>;
?>
```