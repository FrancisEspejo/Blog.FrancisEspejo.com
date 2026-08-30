---
title: "El stack que uso día a día"
description: "Móvil, equipos, identidad y cómo publico. Lo que uso y por qué."
pubDate: 2026-08-29
tags: ["sistemas", "privacidad"]
---

Este artículo es un inventario de lo que estoy usando ahora: Pixel, Debian, Proton y hosting para las páginas estáticas. Lo escribo para no repetirlo en cada conversación y para tener una buena excusa para que la gente visite mi blog.

## Móvil: Pixel 10 y GrapheneOS

Llevo un Pixel 10 con [GrapheneOS](https://grapheneos.org/). El sistema trae su propio ciclo de parches, endurecimiento de memoria y sandbox por aplicación; los perfiles de usuario están pensados para aislar datos de verdad y tener el máximo de privacidad en mi dispositivo.

GrapheneOS se mantiene sobre Pixel porque el hardware encaja con ese modelo: Titan M2, arranque verificado y una cadencia de actualizaciones que el proyecto puede seguir. No uso Samsung, ni Xiaomi ni otras marcas ya que no puedo tener el control que tengo en mi GrapheneOS.

El teléfono tiene dos perfiles.

**Perfil limpio.** Owner. F-Droid, las apps de Graphene, Proton, el navegador y lo que pueda correr sin cuenta de Google. Es el perfil con el que paso el día cuando Google Play no hace falta.

**Perfil sandbox.** Usuario secundario con los servicios de Google dentro de su propio almacenamiento. Maps, las apps del banco que exige Play Integrity, instagram, etc. Google sigue en el teléfono, pero en otro usuario y sin estar 24x7 recopilando información de mí.

GrapheneOS ya parte el dispositivo por usuarios. Cerrar sesión del sandbox corta ese entorno sin montar un segundo sistema ni poner un “firewall” encima de un Android de fábrica.

Qué por qué no uso un iPhone o un Mac. Básicamente porque el sistema no se audita como yo quiero, el almacenamiento no se controla igual y la cuenta es parte del producto. Me gusta tener el control absoluto de todos mis dispositivos y con Apple no podría hacer lo que quiera cuando quiera.

## Debian en el portátil y en el sobremesa

El portátil va con Debian. El sobremesa también (ese es el que uso para jugar en Steam y GOG Galaxy).

Me quedo en Debian por los repositorios, el ciclo y el hecho de poder seguir un paquete hasta su origen. Cada seis meses sale otra distro inmutable con otro discurso. Yo quiero un sistema que aguante las actualizaciones sin convertirme en beta tester del instalador de turno.

Además, para jugar uso Steam y GOG Galaxy, dos tiendas de videojuegos y launchers, que tratan muy bien al usuario, no hay que pagar online y de verdad considero que hacen muy bien su trabajo para el consumidor.

## Identidad: Proton y dominio propio

Correo, calendario, drive y contraseñas están en Proton, colgados de `francisespejo.com`. El buzón público es `fran@francisespejo.com`. Para todo uso la suite de Proton, por muy poco precio al año, te llevas VPN, Drive, correos, gestor de contraseñas... Por ahora no me han defraudado.

El dominio es mío. Si Proton cae o me cambio de proveedor, las MX se apuntan a otro sitio y la dirección sigue siendo la misma

## Código y web: GitHub, público

La landing ([francisespejo.com](https://francisespejo.com)) y este blog son estáticos: HTML generado, GitHub y GitHub Pages.

Un artículo es un Markdown y un commit. Me evito WordPress, antes lo usaba bastante pero ya prefiero algo mas sencillo para lo que quiero montar aquí. El repo está público. Si quieres ver cómo está montado, clónalo. El sitio que estás leyendo se puede copiar entero.

## Conclusión

Al final, mi deseo es el mismo en el teléfono, en el portátil y en la web. Quiero saber quién actualiza, dónde se guarda y qué se ejecuta al lado de qué. GrapheneOS parte el Pixel en perfiles. Debian me deja seguir un paquete hasta el repo. Proton cuelga de un dominio que puedo reapuntar. Y con github puedo subir mi código y montar un blog sencillo pero efectivo para compartir cosas interesantes.

Obviamente siempre me van a robar datos y en algún punto alguna de las cosas que uso me defraudarán porque un proveedor puede cambiar condiciones o desaparecer. Si quieres más detalles, escríbeme al mail o a mis redes sociales :)
