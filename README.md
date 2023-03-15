# Actividad de semillero git y github

##  procedimientos: 
####  1. primero se creo la cuenta en github y se creo el repositorio Practica1Softca, ademas se instalo git bash y se clono este repositorio en nuestro equipo a través del comando ( git clone: comando utilizado para clonar el repositorio Practica1Softca en nuestro equipo de manera local).

![](https://scontent.feoh3-1.fna.fbcdn.net/v/t39.30808-6/335593099_880756359826056_8209454893022385887_n.png?_nc_cat=104&ccb=1-7&_nc_sid=e3f864&_nc_eui2=AeEAYzjlywGn6w_rTJ5D_Ba-h6zU8AUmqDKHrNTwBSaoMtJi-YEoeUpTFIYkYxPiXg9_d8exWVyd8ah6CHS26y7x&_nc_ohc=F3S83M8JKHMAX_B1voR&_nc_zt=23&_nc_ht=scontent.feoh3-1.fna&oh=00_AfA222SUK-Za7ZZddq5uwsLLrb9WwT_lXFzDOVHug1mtrg&oe=6414F692)

#### 2. Estando en el repositorio local se creo un archivo llamado README.md a través del comando (touch README.md : comando utilizado para crear archivos vacíos), así mismo se utilizo el comando ls para verificar la creación del archivo con éxito.

![](https://scontent.feoh3-1.fna.fbcdn.net/v/t39.30808-6/335398958_5969367319825357_3140920715300034246_n.png?_nc_cat=111&ccb=1-7&_nc_sid=e3f864&_nc_eui2=AeF3I5Cpuc9ZM6eEHPGJ-Xk_ueYtwa-oESq55i3Br6gRKsaIolkqh75djIR5Gi4DxKdgyq-LH6BeIDWjMCekd9pj&_nc_ohc=ybODL6gGoLkAX9Fnmyg&_nc_zt=23&_nc_ht=scontent.feoh3-1.fna&oh=00_AfAQmbTtd0J3vrZIwcyTWo5O2qlAGGzAIiCFXlA1oPCdiQ&oe=64154521)


####  3. En el archivo README.md se agrego la información recopilada hasta el momento de lo que se llevaba realizado de la actividad junto con las imágenes necesarias, luego en el git bash al utilizar el comando (git status: este comando muestra el estado del directorio de trabajo y del área del entorno de ensayo. Permite ver los cambios que aun no han sido guardados o si, no hay ningún cambio por guardar) en este caso nos pide guardar información del archivo README.md, se guardo esta información con el comando (git add . : comando para agregar uno o varios archivos al staging área). Luego se procedió a guardar esta información a través del comando Git comit -m como el primer punto de partida o la primera versión del proyecto, con el mensaje "commit inicial".

![](https://scontent.feoh3-1.fna.fbcdn.net/v/t39.30808-6/335398742_1262681677927021_1176339979389473255_n.png?_nc_cat=106&ccb=1-7&_nc_sid=e3f864&_nc_eui2=AeFCrwgQsVasm-5mcS1ld62w_VQ6t4zMc_T9VDq3jMxz9BWJY7nrOxOrYg1DmGv9zQx_sWSIDufIS8Ll3k_tukK6&_nc_ohc=FX87uPMUFlUAX_h9OOP&_nc_zt=23&_nc_ht=scontent.feoh3-1.fna&oh=00_AfAHC2L0BE3uvnpN9fqSa7OwmEfWzFVdGIOAQghUuI-VWA&oe=6415D84A)


#### 4. Seguidamente procedimos a subir el archivo README.md al repositorio remoto github, haciendo uso del comando (git push: comando que es utilizado para subir o cargar repositorios locales a un repositorio remoto)

#### Ejecutamos comando "git push" y cargamos el archivo en el repositorio remoto 
![](https://scontent.feoh1-1.fna.fbcdn.net/v/t39.30808-6/336376692_1184093438967003_4133462951335466346_n.png?_nc_cat=111&ccb=1-7&_nc_sid=e3f864&_nc_eui2=AeE-QCCNgrfVxaapX2ig4IAwlLclRQNqozCUtyVFA2qjMEqG_3r4kjJOtpExUB7IYKyGcZLsM4bvdJ_wiU9xu9bW&_nc_ohc=pdQgHKhHQR8AX_9Q7_b&_nc_zt=23&_nc_ht=scontent.feoh1-1.fna&oh=00_AfCg8JROLW8eA3YjN7DkwSRnO8LOOve4v-mUo9KeED8OFw&oe=6416E2AF)

#### Verificamos en Github, haber subido el archivo README.md
![](https://scontent.feoh1-1.fna.fbcdn.net/v/t39.30808-6/336367618_603889564935797_1199916003294104078_n.png?_nc_cat=107&ccb=1-7&_nc_sid=e3f864&_nc_eui2=AeFRXWDPzgoVDaIoaf7QfoyAQ6xHDgBiHmhDrEcOAGIeaCGXPseeDXjAjZAKRVMp55R1syDy65KOLK_hFPsDRHxC&_nc_ohc=_XZYFDm4Z3UAX--Ckod&_nc_zt=23&_nc_ht=scontent.feoh1-1.fna&oh=00_AfDdWdVRmqpsQdnBgBGX2plqOx9EAdr4XzZUxgbb_rG0yw&oe=64168244)



#### 5. Se creo el archivo privado.txt con el comando (touch: comando utilizado para crear archivos), ademas se creo un fichero llamado privada con el comando (mkdir: comando utilizado para crear carpetas o ficheros), ademas se procedió a crear otro archivo llamado .gitignore, el cual es un archivo de texto que le dice a Git cuales carpeta o archivos debe ignorar en un proyecto, ademas listamos los archivos del proyecto con el comando ls para verificar que hallan sido creados.
![](https://scontent.feoh1-1.fna.fbcdn.net/v/t39.30808-6/335446586_1402753440478641_7037388515417648721_n.png?_nc_cat=100&ccb=1-7&_nc_sid=e3f864&_nc_eui2=AeFVL6Tf5Ta7Cb0AlREa-ofZC3hjsy2kJgkLeGOzLaQmCWMQJSDeUgfUzdaUposPnI0yC_MZ-7UhGBp3GEpb9dV1&_nc_ohc=o2OyX5vQwN4AX9g16WM&_nc_zt=23&_nc_ht=scontent.feoh1-1.fna&oh=00_AfD264LvM1ruo72HjP7oY0BzhVxnADMO0f4pnMKCDzEPrg&oe=641751B2)

#### Se ejecuta el comando (git status: permite verificar el estado del directorio de trabajo y del área del entorno de ensayo, permite ver si algunos cambios no han sido guardados en nuestro directorio), al ejecutarlo podemos ver que tenemos dos archivos que no han sido guardados el cual son los que acabamnos de crear.
![](https://scontent.feoh1-1.fna.fbcdn.net/v/t39.30808-6/335280325_252838990410233_8998378196055803886_n.png?_nc_cat=103&ccb=1-7&_nc_sid=e3f864&_nc_eui2=AeFw_BzYnxAaApTGvpPcVssPfdb8NQpFSN991vw1CkVI3zLCkwRtAcH4oq3QSw1Ady5bGvOLk0D-la7ijQ_mpNEs&_nc_ohc=jRKXhFQN5mUAX_Om50h&_nc_zt=23&_nc_ht=scontent.feoh1-1.fna&oh=00_AfBwdGInew-w_Ep-s5BXfg3LKzIRm71NtxBtfKjd4fIsMw&oe=641677B8)

### En el archivo .gitignmore agregamos los archivos y carpetas que queremos ignorar de nuestro proyecto
![](https://scontent.feoh1-1.fna.fbcdn.net/v/t39.30808-6/336479844_6360385237307839_4588088001938831354_n.png?_nc_cat=107&ccb=1-7&_nc_sid=e3f864&_nc_eui2=AeHdZmutyxIpplrAyDJ8gQBbdsYaeh7aIdF2xhp6Htoh0fLFScst88WcPHt33jwXvNLEJTyLAJtxv12RIJpU9xTd&_nc_ohc=80fhPLan49UAX_6DVwF&_nc_zt=23&_nc_ht=scontent.feoh1-1.fna&oh=00_AfC1oDTEstPyZUmzJbWRU9O_iFbXB9SAuaQqnvNqWSLWvw&oe=64172B95)
#### Al ejecutar nuevamente el comando git status podemos ver que solo nos muestra que no hemos guardado los cambios del archivo .gitignore y no nos dice nada del archivo privado.txt así mismo todo aquello que agregamos en la carpeta privada serán ignoradas
![](https://scontent.feoh1-1.fna.fbcdn.net/v/t39.30808-6/336364553_154497080834405_1725310977717032697_n.png?_nc_cat=110&ccb=1-7&_nc_sid=e3f864&_nc_eui2=AeG5e6TbS5Sx6ZuMcpzZLnktnJGooYgJNJeckaihiAk0lxaRuVqZccEJNviRO6Pcj4V6iWVCTG9ngcGxpjx6imWU&_nc_ohc=HNPI0QLt0mIAX_m1awu&_nc_zt=23&_nc_ht=scontent.feoh1-1.fna&oh=00_AfAZIt5iaQ402bZIQ8HC3sk9yNun9RsjE2ooe2yq5xclgg&oe=6417332D)

#### 6.Creamos el archivo 1.txt con el comando touch utilizado para crear archivos, luego creamos un tag llamado v0.1 ayuda a identificar una versión en especifica del proyecto para ello se utilizo el comando(git tag: este comando permite etiquetar puntos específicos del historial del proyecto como importantes. Esta funcionalidad se usa típicamente para marcar versiones de lanzamiento), luego usamos el comando (git log: comando que permite mostrar un historial de todos los cambios o commit que se han guardado del proyecto) identificamos que se guardo con éxito el tag v0.1, posterior mente pasamos todos los cambios realizados al staging area con el comando "git add .", y procedimos a guardar los cambios en el repositorio local con el comando "git commit", seguidamente se guardaron los cambios en el repositorio remoto con el comando "git push"
![](https://scontent.feoh1-1.fna.fbcdn.net/v/t39.30808-6/335420517_526366626313844_2591360379062577660_n.png?_nc_cat=101&ccb=1-7&_nc_sid=e3f864&_nc_eui2=AeE3aL7sRjYM2kYlbG4KMKGHmcIYrjC2vgCZwhiuMLa-ACpYjYBzCUgF3T5yEaR394J4E46Nyb2JHauBpV--bZjk&_nc_ohc=x8NkGD4lzm0AX-GLXVy&_nc_zt=23&_nc_ht=scontent.feoh1-1.fna&oh=00_AfAqkjngku_D1eMjkGHtR2bvDWaYPc99SY803Gc-HiKnTQ&oe=641741D5)