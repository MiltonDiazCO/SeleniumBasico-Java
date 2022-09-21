# SELENIUM

Inicialmente desarrollado por Jason Huggins en 2004, Selenium es un Framework destinado a la automatización de navegación web.

La automatización de navegación web consiste en la construcción de scripts que, mediante algún lenguaje de programación, permite ejecutar un flujo de navegación fijo y, de este modo, garantizar que el comportamiento de dicho flujo se conserva a lo largo de la vida de la página web.

Selenium cuenta con tres variantes disponibles

## Selenium IDE
Destinado a flujos de navegación relativamente sencillos, Selenium IDE nos ofrece un pequeño entorno de desarrollo/grabación donde, realizamos de manera manual la navegación a ejecutar, se irán almacenando los distintos pasos que, posteriormente podremos modificar y/o ajustar para mayor precisión en la búsqueda y acción sobre los elementos web.

## Selenium Webdriver
Selenium Webdriver, sería una evolución de las primeras versiones de Selenium RC donde, mediante un servidor Java, éste ejecutaba acciones JavaScript dentro del navegador.

Selenium Webdriver es una librería, disponible en distintos lenguajes de programación, que a través de un controlador específico para cada navegador (Chromedriver para Chrome, Geckodriver para Firefox, etc.) permite controlar dicha instancia del mismo.

**Nota:** existen navegadores que comparten un mismo motor, como por ejemplo Chrome y Opera (Webkit), por lo cual el controlador de uno puede servir para el otro.
Las posibilidades de realizar múltiples acciones y combinarlas es mucho mayor que las ofrecidas en Selenium IDE. Además de esto nos permitirá acceder a las funcionalidades de Selenium Grid.

## Selenium Grid
Selenium Grid nos ofrece la posibilidad de ejecutar al mismo tiempo nuestras pruebas automatizadas en diferentes entornos.

Si has trabajado con Jenkins o has realizado pruebas de rendimiento, este concepto te resultará familiar. El objetivo es que, una vez desarrollado el script de la prueba y a través de un controlador que orqueste el procedimiento, se enviará el script a distintas máquinas (que podrán ejecutar distintas instancias de navegadores) y se ejecutarán todos al mismo tiempo.

Todo esto podrá ser controlado desde un controlador.

#### Fuentes 
Resumen del curso, Selenium con Java para principiantes de Openwebinars -> [Curso]

[//]: # (Enlaces)
[Curso]: https://openwebinars.net/academia/portada/selenium-principiantes/