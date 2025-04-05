Lógica-2 entrega 2
Sistema de Inventario y Pedidos - Java con listas
Este proyecto Java que simula un sistema básico de inventario y para una tienda. En este se usaron estructuras de datos como listas enlazadas (simples, circulares y doblemente enlazadas).

✅ ¿Qué hace el programa?
Muestra un inventario ya establecido de productos con cantidad y precio.
Permite agregar pedidos si el producto existe y hay suficiente stock.
Al agregar un pedido, puedes elegir guardarlo en en una de estas listas:
Lista simple
Lista circular
Lista doblemente enlazada
Y permite visualizar los pedidos almacenados en cada tipo de lista.
Este ejercicio fue realizado en clase, sin embargo se dejaron ciertos errores para analizar y completar.

🛠️ Correcciones realizadas
Archivo ListaCircularPedidos.java:

❌ Error: el mensaje “Ups! Aún no hay pedidos” se mostraba cuando sí había pedidos.
✅ Solución: se corrigió la condición y se evitó el acceso a ultimo.siguiente cuando ultimo es null.
Archivos ListaDoblePedidos.java y ListaCircularPedidos.java:

⚠️ Al instanciar el objeto Pedido era necesario pasar 4 atributos al constructor cuando anteriormente habían solo 2.
✅ Solución: en la línea de instanciación de pedido, se agregaron dos atributos adicionales null para pasar respectivamente a siguiente y anterior.
Archivo App.java:

❌ Faltaban los casos 2, 3, 4 y 5 del menú principal.
✅ Solución: se completó el menú con las funcionalidades.
➕ Funcionalidades agregadas
Se agregó cierre del objeto Scanner al final del programa.
Se mejoró la legibilidad del menú y los mensajes al usuario.
Nota
Código realizado en clase por el profesor Daniel Felipe Agudelo
Correcciones y entrega hechas por Juan David Estrada Salazar- Estudiante de Técnica Profesional en Sistemas, Tecnológico de Antioquia.
