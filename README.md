# k8s_grupoid_2019

## Módulo 1: Despliegue de aplicaciones en contenedores

* Introducción a la tecnología de contenedores
* Arquitectura de microservicios
* Tecnologías que nos ofrecen contenedores: docker, cri-o, ...
* Ciclo de vida en el despliegue de aplicaciones con docker

## Módulo 2: Introducción a kubernetes

* Introducción a kubernetes: características, historia, estado actual del proyecto, ...
* Arquitectura de kubernetes
* Instalación de kubernetes con minikube
* Instalación del cliente kubectl
* Introducción al despliegue de aplicaciones en Kubernetes

## Módulo 3: Desplegando aplicaciones en kubernetes

* Recursos de Kubernetes: Pods
* Recursos de Kubernetes: ReplicaSet
    * Tolerancia a errores
    * Escalabilidad dinámica
* Recursos de Kubernetes: Deployment
    * Actualizaciones continúas
    * Despliegues automáticos (RollBack)

## Módulo 4: Accediendo a nuestras aplicaciones en kubernetes

* Recursos de Kubernetes: Services
* Ejemplo 1: Desplegando la aplicación Mediawiki
* El servicio DNS en Kubernetes
* Ejemplo 2: Desplegando la aplicación GuestBook 
* Ejemplo 3: Desplegando la aplicación LetsChat
* Recursos de Kubernetes: Ingress
* Ejemplo 4: Accediendo a nuestras aplicaciones con Ingress

## Módulo 5: Configurando nuestras aplicaciones en kubernetes

* Configurando nuestras aplicaciones con variables de entorno
* Configurando nuestras aplicaciones con ConfigMaps
* Configurando nuestras aplicaciones con Secrets
* Ejemplo 5: Desplegando WordPress con MariaDB

## Módulo 6: Almacenamiento en kubernetes

* Almacenamiento en Kubernetes
* Almacenamiento disponible en Kubernetes: PersistentVolumen
* Solicitud de almacenamiento en Kubernetes: PersistentVolumenClaims
* Ejemplo 6: Desplegando WordPress con MariaDB con almacenamiento persistente

## Módulo 7: Despliegue avanzado de aplicaciones en kubernetes

* Recurso de Kubernetes: StatefulSets
* Ejemplo 6: Despliegue de aplicaciones con el recurso StatefulSets
* Recurso de Kubernetes: DaemonSets
* Ejemplo 7: Despliegue de aplicaciones con el recurso DaemonSets
* Autoescale ???
* Helm ???

## Módulo 8: Administración de nuestro cluster de kubernetes

* Recursos de Kubernetes: Namespaces
* Gestión de usuarios
* Politicas de acceso: RBAC
* Cuotas y límites en nuestro proyecto
* Políticas de red