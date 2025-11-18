1. ¿que ventajas observas en la version orientada a objetos?

La ventaja más notable es el encapsulamiento. Al unificar los datos y las operaciones dentro de la clase Producto, se logra un código mucho más organizado y seguro. Esto permite mantener limpia la lógica principal y evita los errores que suelen ocurrir al manipular variables dispersas de forma manual.

2. ¿que parte del codigo resulto mas clara o facil de mantener?

La clase TiendaApp resulta mucho más sencilla de gestionar porque delega la responsabilidad de mostrar la información directamente a la clase Producto. Esto facilita el mantenimiento, pues si fuera necesario modificar el formato en que se imprimen los datos, bastaría con hacer el ajuste en la clase del objeto sin necesidad de alterar el flujo de control en el programa principal.

3. ¿Cómo podrías extender el programa para manejar más productos?

Para superar la limitación del arreglo fijo, lo más adecuado sería utilizar una colección dinámica como un ArrayList. Esta implementación permitiría registrar una cantidad indefinida de productos según sea necesario, eliminando la restricción de tener que definir un tamaño exacto al inicio del desarrollo.

4. ¿Podrías agregar una clase Tienda que contenga los productos y calcule el total?

Claro, la evolución lógica del sistema sería crear una clase Tienda que administre internamente la lista de productos. Esta clase debería incluir métodos propios para agregar artículos y calcular el total del inventario, lo cual liberaría al método principal de realizar cálculos matemáticos y centralizaría mejor la lógica del negocio.