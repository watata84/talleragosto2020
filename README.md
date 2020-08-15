## Playbook de Taller 2020

En este repositorio encontraras los playbooks necesarios para poder montar 2 servidores Apache (Centos o Ubuntu) y un servidor que funcionara como Proxy Reverso y balanceador de carga

Se separan en 2 playbooks diferentes (WEBSERVERS Y HAPROXY) para poder tener mas opciones de modificacion
En la carpeta inventory se encuentra el archivo hosts.ini el cual tendras que modificar de acuerdo a tus requerimientos


Pare ejcutarlos solo deberas ejecutar los siguientes comandos:

ansible-playbook servers-apache.yaml -i inventory/hosts.ini

ansible-playbook haproxy.yaml -i inventory/hosts.ini


Aqui podras ver el diagrama de red de nuestra infraestructura

![Screenshot](estructura.jpg)
