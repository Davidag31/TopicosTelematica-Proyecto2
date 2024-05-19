# Proyecto 2
# Info de la materia: ST0263 Topicos especiales en Telematica.

## Estudiante(s):
- **David Alvarez Grisales**
- **Julio Cesar Posada Torres** 

## Profesor:
- **Nombre:** Alvaro Enrique Ospina Sanjuan
- **Correo Electrónico:** aeospinas@eafit.edu.co

## Proyecto 2.

## 1. Breve descripción de la actividad.
En este proyecto, desplegaremos una aplicación WordPress utilizando MicroK8s en Google Cloud Platform (GCP). En GCP, configuramos tanto el nodo maestro como los nodos trabajadores para implementar MicroK8s, que nos permite crear un clúster propio de Kubernetes. Además, se configuró una máquina como servidor NFS para garantizar la persistencia de los datos de WordPress y la base de datos, asegurando así la persistencia de los datos.

# 1.1. Que aspectos cumplió o desarrolló de la actividad propuesta por el profesor (requerimientos funcionales y no funcionales)

Se cumplieron todos los requerimientos del proyecto 2:
- Aplicacion wordpress dockerizada con varios pods.
- Configuracion de los servicios, deployment, pv y pv para el wordpress.
- Base de datos MYSQL
- Servidor NFS para la persistencia de los datos
- Uso de ingress para permitir el trafico para wordpress
- Certificado SSL
- App desplegada en un dominio propio

# 1.2. Que aspectos NO cumplió o desarrolló de la actividad propuesta por el profesor (requerimientos funcionales y no funcionales)
Se cumplieron todos los requerimientos necesarios
# 2. información general de diseño de alto nivel, arquitectura, patrones, mejores prácticas utilizadas.
Arquitectura:
![image](https://github.com/Davidrk31/TopicosTelematica-Proyecto2/assets/89051979/53f1472c-cb73-4fbe-81b4-87e426e8c319)


# 3. Descripción del ambiente de desarrollo y técnico: lenguaje de programación, librerias, paquetes, etc, con sus numeros de versiones.
Se uso el software microk8s en GPC, ademas del uso de una base de datos MYSQL y un servidor NFS para la persistencia de los datos.
Se usaron las versiones:
- docker.io/bitnami/mysql:8.0
- Wordpress
- NFS versión 4.1

# 4 Ambiente de ejecucion:
El proyecto se encuentra en https://reto4.construmarket.tech/  

# Resultados del proyecto




# Referencias:

* [Instalación Kubectl](https://docs.aws.amazon.com/eks/latest/userguide/install-kubectl.html)

* https://foolcontrol.org/?p=3754

* [Instalación Helm](https://helm.sh/docs/intro/install/)

# Video:
https://drive.google.com/file/d/1JhPlGCW1mSxTVY-5AEMuLBfF47mYIryB/view?usp=drive_link


