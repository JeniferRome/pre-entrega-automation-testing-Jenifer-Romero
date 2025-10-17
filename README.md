 Proyecto de Automatización – SauceDemo (Swag Labs)

## Propósito del Proyecto
Este proyecto tiene como propósito automatizar pruebas funcionales sobre el sitio [SauceDemo](https://www.saucedemo.com/), utilizando Python, Selenium WebDriver y Pytest.

El objetivo principal es comprobar el funcionamiento correcto de los flujos más importantes de la aplicación, como parte de la práctica del curso de Automatización de Pruebas.  
Los casos de prueba implementados son:

1. Inicio de sesión (Login)  
   - Validar el acceso con credenciales válidas e inválidas.

2. Navegación y verificación del catálogo  
   - Comprobar que los productos del catálogo se muestren correctamente luego del login.  
   - Verificar la correcta visualización de los elementos de la página y los títulos.

3. Interacción con productos (Carrito de compras)  
   - Agregar productos al carrito.  
   - Validar que los productos seleccionados aparezcan correctamente en el carrito.


## Tecnologías Utilizadas

| Tecnología | Descripción |
|-------------|-------------|
| Python | Lenguaje principal de desarrollo. |
| Pytest | Framework de testing usado para estructurar y ejecutar las pruebas. |
| Selenium WebDriver | Herramienta para automatizar la interacción con el navegador web. |
| Git y GitHub | Control de versiones y alojamiento del proyecto. |


##  Instalación de Dependencias

###  Clonar el repositorio
```bash
git it clone https://github.com/jeniferromero/pre-entrega-automatizacion-testing-jenifer-romero.git