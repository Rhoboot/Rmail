[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/infuser)](http://cran.r-project.org/web/packages/Rmail)
[![Downloads](http://cranlogs.r-pkg.org/badges/infuser)](http://cran.rstudio.com/package=Rmail)

Resumen
========
  Rmail permite a los usuarios enviar correos desde R.

It is developed as a wrapper around [Apache Commons Email](http://commons.apache.org/proper/commons-email/) and offers several features to send emails from R such as:
- using authentication-based SMTP servers
- sending emails to multiple recipients (including the use of Cc, Bcc, and ReplyTo recipients)
- attaching multiple files from the file system or from URLs
- sending HTML formatted emails with inline images

Instrucciones de Instalación
=========================
Puedes instalar el paquete Rmail usando devtools:

```R
devtools::install_github("rhoboot/Rmail")
library(Rmail)
```
