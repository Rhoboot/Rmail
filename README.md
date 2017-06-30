<!---[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/infuser)](http://cran.r-project.org/web/packages/Rmail)
[![Downloads](http://cranlogs.r-pkg.org/badges/infuser)](http://cran.rstudio.com/package=Rmail)--->

Resumen
========
  Rmail permite a los usuarios enviar correos desde R.

Es una envoltura (wrapper) de [Apache Commons Email](http://commons.apache.org/proper/commons-email/) que ofrece varias funciones para enviar correos desde R.
- Usa autentificación basada en servidores SMTP
- Envia correos a mutiples fuentes (incluyendo CC, BCC, y ReplyTo)
- Permite adjuntar multiples archivos desde una carpeta o desde URLs
- Permite enviar correos HTML con imagenes en linea

Instrucciones de Instalación
=========================
Puedes instalar el paquete Rmail usando devtools:

```R
devtools::install_github("Rhoboot/Rmail")
library(Rmail)
```
Este paquete se basa en el trabajo de [Rahul Premraj](https://github.com/rpremraj/mailR), incluye las versiones actualizadas de las librerias de [Apache Commom Email 1.4](http://commons.apache.org/proper/commons-email/) y [javamail 1.5.6](https://javaee.github.io/javamail/)
