# Javi Linux
# kernel optimizado para  MAGALHAES MG-101A4 - ES10IS2 (CANAIMA) 
Este repositorio contiene un kernel Linux personalizado y optimizado específicamente para las computadoras portátiles Canaimas Magalhães MG-101A4 o ES10IS2 (netbook Argentina) y laptops con procesador intel CELERON . El objetivo principal de este kernel es mejorar el rendimiento general del sistema, la estabilidad y la compatibilidad con el hardware, ofreciendo una experiencia de usuario más fluida y satisfactoria.
![photo_2024-08-10_14-08-43](https://github.com/user-attachments/assets/8f608929-91b2-4b61-b7be-62399dd9ec13)
# instalación
```shell
#! /bin/bash
mkdir j
cd j
wget https://github.com/franckey02/Javi-Linux/releases/download/5.15-RT/linux-headers-5.15.165-javi-rt_5.15.165-javi-rt-1_amd64.deb && wget https://github.com/franckey02/Javi-Linux/releases/download/5.15-RT/linux-image-5.15.165-javi-rt_5.15.165-javi-rt-1_amd64.deb
sudo dpkg -i *
```

