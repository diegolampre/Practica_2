+++
title = "Ejercicio 1"
date = 2021-09-28T17:53:21+02:00
weight = 5
chapter = true
+++

### Ejercicio 1

# Definición de Cliente-Servidor y lenguaje Mermaid


![Imagen de Cliente-Servidor](/images/maxresdefault.jpg)

El modelo cliente-servidor representa la forma en la que se producen las comunicacion entre dos nodos de una red. Uno de los nodos tiene el rol de **cliente** y el otro el rol de **servidor**.

La mayoria de los casos los elementos que dan uso a este modelo son aplicaciones/programas.

**Aplicación cliente:** Es el elemento de la comunicacion que solicita un servicio de red, por ejemplo el acceso a una pagina web.

**Aplicación servidor:** Es el elemento de comunicacion que responde las peticiones de los clientes, proveyendo los servicios requeridos, por ejemplo enviando la pagina web.

En la siguiente figura se representa la comunicación mas tipica de internet, la conexion a una pagina web.

![Modelo cliente-servidor en el servicio web](/images/modelo.jpg)

En esta imagen se puede observar la comunicacion que sigue el modelo **cliente-servidor**, donde el navegador web con el que queremos acceder a una pagina web seria el **Host A** y el proceso que atiende al cliente seria el **Host B** que tiene el rol de servidor.

{{<mermaid align="center">}}
graph LR;
    A[Cliente 2] --- B(Internet)
    D[Cliente 1] --- B(Internet)
    E[Cliente 3] --- B(Internet)
    B --- C{Equipo Servidor}
{{< /mermaid >}}

![DNS](/images/DNS.jpg)

**DNS:** Es un sistema de nombres de dominios, traduce los nombres de dominios (www.amazon.com) a direcciones IP aptas para lectura por parte de maquinas(192.0.2.44).

El servidor DNS utiliza una base de datos distribuida y jerarquica que almacena informacion asociada a nombres de dominio en redes como Internet.
