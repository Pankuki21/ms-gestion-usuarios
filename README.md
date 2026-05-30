# Microservicio Gestión de Usuarios

## Integrantes

* Francisca Acosta
* Cristobal García

## Descripción

Microservicio desarrollado con Spring Boot que implementa un pipeline CI/CD utilizando GitHub Actions, Docker, JaCoCo y Snyk.

## Tecnologías

* Java 17
* Spring Boot
* Maven
* Docker
* Docker Compose
* GitHub Actions
* JaCoCo
* Snyk

## Pipeline CI/CD

El pipeline realiza las siguientes tareas:

* Ejecución de pruebas unitarias.
* Generación de reporte JaCoCo.
* Construcción del proyecto.
* Análisis de seguridad con Snyk.
* Construcción de imagen Docker.
* Levantamiento de artefactos

## Calidad y Trazabilidad

La calidad se asegura mediante pruebas automatizadas, cobertura de código con JaCoCo y análisis de seguridad con Snyk.

La trazabilidad se mantiene mediante Git, GitHub y GitHub Actions, registrando cada cambio y ejecución del pipeline.

## Orquestación

La aplicación utiliza Docker Compose para la gestión y despliegue de contenedores.