# Sublime-Text
### Repositorio dedicado a la documentación de la instalación de Sublime Text en Ubuntu

Para poder instalar Sublime Text en Ubuntu debemos seguir una serie de pasos:

1. Escribir el comando “sudo apt-get upgrade”

 <p align="center">
<img width=55% src="https://i.imgur.com/CNYvIhW.png">
 </p>
 
2. Escribir el comando “wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -”

 <p align="center">
<img width=55% src="https://i.imgur.com/Tnieg7w.png">
 </p>

3. Escribir el comando “sudo apt-get install apt-transport-https”

<p align="center">
<img width=55% src="https://i.imgur.com/L9y1XqV.png">
 </p>
 
4. Escribir el comando “echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list”

<p align="center">
<img width=55% src="https://i.imgur.com/3lsI0SN.png">
 </p>

5. Escribir el comando “sudo apt update”

<p align="center">
<img width=55% src="https://i.imgur.com/frMywQb.png">
 </p>

6. Escribir el comando “sudo apt install sublime-text”

<p align="center">
<img width=55% src="https://i.imgur.com/Psbjwqe.png">
 </p>

Una vez realizados todos estos pasos, ya se podría buscar el programa en el equipo para iniciarlo y hacer uso de él.
