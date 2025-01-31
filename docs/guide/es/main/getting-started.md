# Cómo empezar #
**Paso a paso.** Guía sencilla para la configuración de tu ambiente.

##  Utilidades ##
 Toma en cuenta que algunas de estas aplicaciones ya pueden estar instaladas en tu equipo.

### Gestores de paquetes ###
- **Homebrew:** Herramienta que permite instalar complementos, software o aplicaciones que no vienen incluidas en el sistema operativo. Para su instalación, basta ejecutar el siguiente comando en la terminal:
~~~
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
~~~
Más detalles en: https://brew.sh/

- **SDKMAN:** Este gestor facilita la instalación de distintos SDKs y brinda la posibilidad de administrar versiones paralelas de los mismos. Comando de instalación:
~~~~
$ curl -s "https://get.sdkman.io" | bash
~~~~
Más detalles en: http://sdkman.io/

### Herramientas de desarrollo ###
- **Ant** (1.10.9)
- **Gradle** (6.7.1)
- **Grails** (2.5.3)
- **Groovy** (2.5.6)
- **Java** (8.0.282-zulu)
- **Maven** (3.8.1)

Estas aplicaciones pueden instalarse haciendo uso de la herramienta "SDKMAN"; para esto puedes escribir en tu terminal el comando *sdk install* seguido del *nombre de lo que deseas instalar* + la *versión*. Por ejemplo:
~~~~
sdk install grails 2.5.3
~~~~

### Otras herramientas ###

- **Fury:** Esta es la plataforma sobre la cual se desarrollan, deployan y gestionan en producción todas las aplicaciones de MercadoLibre. Si aún no lo has instalado, puedes seguir los pasos de la documentación oficial:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Prerrequisitos](https://furydocs.io/client/1.6.3-doc2/guide/#/furycli/requirements)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Instalación](https://furydocs.io/client/1.6.3-doc2/guide/#/furycli/installation)

Con el gestor de paquetes Homebrew es posible instalar otras tres tecnologías que serán necesarias para tus desarrollos en Payments:

- **Node**
~~~
brew install node
~~~
- **Redis**
~~~
brew install redis
~~~
- **Memcached**
~~~
brew install memcached
~~~

También necesitarás un IDE y una aplicación para probar APIs:

- IntelliJ IDEA
- Postman

**Puedes conseguir estas y otras aplicaciones en la APP 'Intelligent HUB' instalada en tu Mac por el equipo de MELI**

![intelligent-hub](../../img/intelligent-hub.png)
![hub-devs-apps](../../img/hub-devs-apps.png)

**Finalmente, con todas tus herramientas instaladas, estás preparado para dar el [siguiente paso](es/main/advanced-steps.md).**

