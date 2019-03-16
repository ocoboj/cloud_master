# PRÁCTICAS MÓDULO CLOUD

## Preparación

* Cuenta de [Docker Hub](https://hub.docker.com/)
* Cuenta de [AWS](http://aws.amazon.com/)
* Haz un fork de este repositorio

## Práctica 1

Dado este proyecto en NodeJS, crea su Dockerfile sabiendo que nos han pedido como imagen base ubuntu:18.04, versión 10 de NodeJS, el 8888 será el puerto donde exponga la comunicación la applicación, la señal de *STOP* debe llegarle a la aplicación y el contenedor podría ser iniciado con cualquier proceso.

## Práctica 2

Sube la imagen de Docker a DockerHub.
https://cloud.docker.com/repository/docker/oconesa80/myimg/general (creo que esta no se abre si no se tiene mi cuenta)
https://hub.docker.com/r/oconesa80/myimg/tags

## Práctica 3

Automatiza el proceso de creación de la imagen de Docker y su subida a Docker Hub después de cada cambio en el repositorio.
https://travis-ci.org/ocoboj/cloud_master

## Práctica 4

Crea un servidor y despliega la imagen de Docker en AWS utilizando Terraform.