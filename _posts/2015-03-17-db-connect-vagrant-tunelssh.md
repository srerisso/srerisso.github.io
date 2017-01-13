---
title:  "Conexi&oacute;n Base de datos con tunel SSH"
date:   2015-03-23 12:08:00
categories: config,vagrant,sql
tag: how-to
---

C&oacute;mo configurar una conexi&oacute;n a una BD en una MV Vagrant a trav&eacute;s de t&uacute;nel SSH.


### Qué
Configurar una conexi&oacute;n a una BD en una MV Vagrant a trav&eacute;s de t&uacute;nel SSH.

### Parámetros
Conectamos a través de un cliente como [pgAdmin](http://www.pgadmin.org/), [SequelPro](http://www.sequelpro.com) o [MySQL Workbench](https://www.mysql.com/products/workbench/) con un túnel SSH.

***

##### Datos BD

* Host: localhost
* DB User:        root
* DB Password:   root
* DB name:       [dejar en blanco]

***

##### Datos t&uacute;nel SSH

* SSH host: 192.168.33.10 [o la ip de tu MV]
* SSH user: vagrant
* SSH password: vagrant

***

Despu&eacute;s de perder 1 dia entero probando 1000 configuraciones en Ubuntu 14.04 y que no funcionara, la soluci&oacute;n fue actualizar MySQL Workbench :-)
