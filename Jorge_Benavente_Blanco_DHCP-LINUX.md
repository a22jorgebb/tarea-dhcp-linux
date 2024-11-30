## Servidores DHCP Linux.

### 1 - Configuración (grep -v "^#" /etc/kea/kea-dhcp4.conf)

![](./images/2024-11-30-18-48-34.png)

![](./images/2024-11-30-18-48-49.png)

![](./images/2024-11-30-18-49-00.png)


### 2 - log de ned visualizando a asignación de enderezos en cada un dos pool e da reserva estática

![](./images/2024-11-30-19-01-06.png)

### 3 - Configuración de servidores DNS, router e enderezo IP de cada cliente

**Fichero db.stark.lan**

![](./images/2024-11-30-19-02-23.png)

**named.conf.local**

![](./images/2024-11-30-19-02-13.png)

**zona inversa**

![](./images/2024-11-30-19-02-29.png)

**router**

![](./images/2024-11-30-19-09-38.png)

### 4 - log de ned e robb (simultáneos) facendo unha actualización mediante chaves en arya.
### 5 - log de ned visualizando asignacións da segunda subrede (lannister) e actualizacións no servidor dns correspondente.
### 6 - Log dos dous servidores failover cando dous clientes obteñen enderezos
### ...

