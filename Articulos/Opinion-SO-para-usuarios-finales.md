

## Opinión: El mejor sistema operativo para los usuarios finales.
  
### Por @UlisesAlexanderAM 

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Licencia Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Esta obra de <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Ulises Alexander AM</span> está bajo una <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Licencia Creative Commons Atribución-CompartirIgual 4.0 Internacional</a>.

**Nota: Este documento fue escrito como parte de una de mis tareas para la universidad, por lo cual no ahondo mucho, ademas de que se suponía que era un guion para un video de 3 minutos.  
Dejare el planteamiento del ejercicio a continuación:**

>Reflexiona sobre las siguientes preguntas: ¿Cuál es el mejor sistema operativo para los usuarios finales, según tu criterio? Justifica tu respuesta. 
>
> Crea un vídeo de no más de 3 minutos donde defiendas tu respuesta a la pregunta bajo los siguientes requisitos: 
> 
> a. Breve descripción del sistema operativo.  
> b. Posición del sistema operativo en el mercado.  
> c. Principales características de uso del sistema operativo (facilidad) para los usuarios finales.  
> d. Seguridad que ofrece para los datos del usuario. 

**Nota 2: Como algunas fuentes usadas ya tienen nuevos datos, actualizare esos datos fuera de eso el resto del texto lo dejare tal cual fue hecho para mi tarea.**

Para mi el mejor sistema operativo(SO) para los usuarios finales es GNU/Linux o Linux como se le conoce coloquialmente, aunque Linux hacer referencia unicamente al kernel o núcleo del sistema operativo. Linux tiene distintas versiones llamadas distribuciones, para facilitar las cosas mis argumentos serán tomando en cuenta la distribución de Manjaro KDE, que es la que uso. 

Actualmente Linux, según [statcounter en el periodo Octubre del 2019 a Octubre 2020](https://web.archive.org/web/20201104160329/https://gs.statcounter.com/os-market-share/desktop/worldwide/) fue el cuarto SO mas popular con el 1.53% del mercado de escritorio, atrás de Windows, OS X y Chrome OS, en Steam en su [“Encuesta sobre hardware y software de Steam: October 2020”](https://web.archive.org/web/20201106185202/https://store.steampowered.com/hwsurvey/) nos dice que el 0.90% de los usuarios usan Linux como su SO,  0.10% de esos usuarios usan Manjaro como su distribución. Aunque su popularidad en escritorio es muy pequeña, varios servidores, supercomputadoras y grandes empresas usan Linux como SO.

Después del breviario de como se encuentra Linux en el mercado, regresemos a lo que nos importa por qué creo que Linux es el mejor SO para usuarios finales. 

Los sistemas Linux usan gestores de paquetes para gestionar los programas, es decir, instalación, desinstalación, actualización de los programas se hace mediante estos gestores. Esto tiene la ventaja que no necesitas ir a buscar los programas que necesites por internet todo se puede hacer desde la terminal o consola; y si lo prefieres puedes usar la alternativa grafica. En cuanto a seguridad, los gestores requieren la contraseña de super usuario o root, también puedes usar la del usuario si se le dan los permiso de sudo al usuario; esto evita que cualquier persona instale software en la computadora. Manjaro usa pacman y pamac como sus gestores, también se pueden utilizar lo que vienen incluidos con el entorno de escritorio. 

Hablando de entornos de escritorio, Linux no solo tiene diversas distribuciones sino que también distintos entornos de escritorio, los cuales determinan como interactúa el usuario con el SO mediante una interfaz grafica, la que yo uso es KDE/Plasma, pero existen otras como Gnome, Awesome, entre otras.

Debido a la arquitectura del kernel, no todos los módulos del kernel están cargados en memoria, lo que permite que los programas puedan tener mas memoria disponible. Ademas los módulos se cargan conforme son necesitados. Esto beneficia al usuario ya que puede estar seguro que los recursos de su SO no se están malgastando.

Otro beneficio del Linux es que salvo que se actualicen, instalen o remuevan núcleos, la gran mayoría de las veces se puede seguir usando el sistema sin necesidad de reiniciar la computadora después de instalar, desinstalar o actualizar programas.

El kernel permite el uso de varios sistemas de archivos, ext4 es el sistema predeterminado pero también puede detectar y usar NTFS, FAT, entre otros. Si alguien usa Linux junto con Windows puede montar la partición donde esta alojado Windows puede copiar esos archivos a Linux para interactuar con ellos.

Si alguien quiere modificar archivos de configuración u otros archivos que podrían afectar el funcionamiento del sistema, se le pedirá identificarse como root o sudoer, alguien que tiene permiso de sudo.

Linux permite el uso de memoria swap, esto es espacio de disco que puede ser usado como si fuera memoria RAM, si el sistema esta cercano al uso completo de RAM. Esto habilita la opción de hibernación, es decir, en lugar guardar el estado actual del sistema en RAM lo guarda en disco lo cual evita que haya perdida de información en caso de una interrupción en el suministro eléctrico.

Linux gestiona los permisos de usuario con 3 tipos de permisos: escritura, lectura y ejecución; estos se otorgan o deniegan en 3 niveles: dueño, el que creo el archivo, grupo, grupo donde pertenece el dueño, y mundo, el resto.  Así si un usuario crea un archivo pero no quiere que algún otro usuario lo vea, modifique o ejecute, puede quitarle los permisos a grupo y a mundo. Y así modificamos los permisos según nuestra necesidad.

Regresando un poco a los programas, en Linux existen paquetes “universales” independientes de la distribución, pero se preguntaran cual es la necesidad de paquetes universales si los programas nos los ofrecen los gestores de paquetes, bueno esto se debe a que cada distribución empaqueta sus programas de distinta manera, por ejemplo Debian y sus derivados usan paquetes .deb; Fedora y OpenSuse usan .rpm, Manjaro y Arch, de quien deriva Manjaro, pkg.tar.gz o  pkg.tar.xz. Para solucionar este problema y crear programas multiplataforma se crearon alternativas como appimage, flatpak y snap.

Linux analiza los contenidos de un archivo para determinar que tipo y formato de archivo es, por lo que si se te olvida poner la extensión en un archivo aun es posible que los puedas manipular correctamente, hay excepciones a esto, por ejemplo los compiladores buscan la extensión para determinar que tipo de programa es y como compilarlo.

El soporte a hardware a crecido considerablemente en los últimos años, por lo que es probable que conectes lo que conectes a tu computadora puedas usarlo, por ejemplo aunque si tu sistema operativo viene con los controladores libres de nvidia pero tu rendimiento no es el adecuado puedes optar por usar la alternativa privativa. Tanto Intel como AMD y Nvidia han estado preparando código para el kernel Linux versiones 5.9 y 5.10 donde se vislumbra soporte para sus próximos lanzamientos.

Cabe destacar que la gran ventaja de Linux es la habilidad de personalizar nuestra computadora a nuestro gusto y necesidades. 

Finalmente aunque no es una característica del sistema operativo per se sino del entorno Linux/software libre y de código abierto, la gran comunidad existente es un buen motivo para usar Linux, siempre puedes pasearte por las wikis de las distribuciones para ver como instalar, configurar y resolver problemas comunes, o sino pasear por los foros para resolver dudas, problemas o simplemente para aprender y convivir con el resto de usuarios.