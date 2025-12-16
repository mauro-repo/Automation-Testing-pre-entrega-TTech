# Proyecto de Talento Tech (pre-entrega)

## Proposito del proyecto
El proyecto se centra en la automatización de las interacciones esenciales en el sitio web de comercio electrónico de prueba **`https://www.saucedemo.com`**.
El objetivo es establecer una base sólida para el testing automatizado, cubriendo desde el acceso al sistema hasta la gestión básica del carrito de compras, utilizando las mejores prácticas con Python y Selenium.

## Tecnologias utilizadas
- Python
- Selenium WebDriver
- Pytest
- WebDriver Manager
- Pytest-HTML
- Git & GitHub

## Funcionalidades Automatizadas (Casos de Prueba)

Se han cubierto los siguientes escenarios de usuario:

1)
Módulo: Login  
Escenario de Prueba: Acceso al Sistema  
Objetivo de la Validación: Verificar el inicio de sesión exitoso con credenciales estándar.  

2)
Módulo: Inventario  
Escenario de Prueba: Validación de Interfaz  
Objetivo de la Validación: Comprobar el título de la página y la presencia de productos y elementos clave (filtros, menú).  

3)
Módulo: Carrito  
Escenario de Prueba: Interacción con Productos  
Objetivo de la Validación: Añadir un producto, validar el incremento del contador del carrito y confirmar su presencia en la vista del carrito.  

## Estructura del Repositorio

La organización del proyecto se adhiere a una estructura modular para facilitar la escalabilidad y el mantenimiento:

 test/  
 - test_login.py         # Pruebas relacionadas con el Login.  
 - test_inventory.py     # Pruebas de Inventario y Elementos.  
 - test_productos.py     # Pruebas de Carrito y Flujo de Productos.  
       
 utils.py                   # Funciones Login (Inicialización de Chrome/Driver).  
 conftest.py                # Hooks de Pytest, fixtures.  
 report.html                # Reporte final generado por pytest.  
 README.md                  # Describe las funcionalidades del programa.  
 run_tests.py               # Archivo main para la ejecución de los tests.  
 requirements.txt           # Listado de dependencias del proyecto.  
 
**Reporte de Resultados**

Tras la ejecución, el reporte report.html contendrá un resumen ejecutivo de la corrida de pruebas, incluyendo:

Detalle de los casos de prueba ejecutados.

Resultado de cada prueba (Éxito passed o Falla failed).

Duración de la ejecución.

**Próximos Pasos**

En la entrega final se ampliará el proyecto, ya que esta proyecto es una pre-entrega y está diseñado para ser la base.