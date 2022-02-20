# Tutorial: Manejo de discos
### Creado por:
* Benjamin Hoyos Herrera 
* Angel Yedid Nacif Mena
* Carlos Abraham Martines Zamora
* Genaro Gonzales Lozada  
Practica 01 de la materia de Sistemas Operativos 2  
Este es un tutoria para poder manejar 


## 1.Que es hda, sda y vda?
### hda es...
Es la unidad maestra en el controlador IDE principal, linux toma el primer disco duro como un disco duro completo 
### sda es...
El (Small computer sistem interface disk) sda es para dispositivos de almacenamiento tales como discos duros mecanicos, memorias ssd, usbs, etc; que soportan comandos SCSI, la conexion es manejada por el subsistema SCSI que tiene el kernel
### vda es...
Es la particion virtualizada de una maquina virtual, el rendimiento es mejor  ya que el hipervisor no tiene que emular ninguna interfaz de hardware

## 2.Como montar y desmontar un usb en el sistema por teminal?
Hay dos formas en las cuales puedes montar una memoria USB, la primera es sin tener permisos de lectura y escritura y la otra es con los permisos, lo unico que va   a cambiar es la linea de comando al momento de montar la memoria USB:

1.Conectar la memoria USB y abrir una terminal    
2.Crear una carpeta donde montar la memoria USB con el comando ```mkdir nombre_del_archivo``` y dentro de esa carpeta creamos otra carpeta donde haremos el montaje    
3.En terminal escribir: ```lsblk``` para ver una lista de particiones e identificar que particion es tu usb    
4.Una vez identificado tienes que escribir ```sudo blkid``` para saber el sistema de archivo que maneja en este ejemplo *sda2* tiene un tipo de sistema *vfat*    
5.Aqui vamos a hacer el montaje de la USB


## 3.Como enlistar la informacion de los dispositivos de bloque conectados aunque no esten conectados?

## 4.Como mostrar la tabla de particiones del disco donde esta instalado el sistema operativo en terminal?

## 5.Como conectar una memoria USB y mostrar su tabla de particiones en terminal?

## 6.Como borrar todas las particiones de un USB en terminal?

## 7.Como crear en el USB tres particiones fisicsa y una extendida en terminal?

## 8.Como crear una particion dentre ode la particion extendida del USB en terminal?

## 9.Como borrar las particiones para que solo exista una particion que abasque toda la usb por la interfaz grafica?

## 10.Como copiar una archivo .iso de distribucion live de linux a una USB por medio del comando "dd"?