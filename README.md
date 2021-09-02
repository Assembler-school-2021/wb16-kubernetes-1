# wb17-18-Rancher

Configuración de interfaces:
ens10 interfaz de red privada 10.0.0.2
Mi ip 176.87.11.251
Ip del server 95.216.195.228

Instalar kubectl:
https://kubernetes.io/es/docs/tasks/tools/install-kubectl/
Hay que crear una clave ssh y añadirla a authorized_keys
	ssh_keygen
	cat ./ssh/id_rsa.pub >> .ssh/authorized_keys

Creamos el password para el user admin: cmMM$mXtf!r)bczd
Creamos el usuario enrique con la pass: SQ.Q6q3Bx2zZzpTV
Y desactivamos el admin.

> Pregunta 1: Llegados a este punto y con la documentación de los drivers instalados, adapta los pods de mysql y wordpress del ejercicio anterior para ser autodesplegados con kubernetes en un nuevo namespace wordpress-mysql, usando un Load Balancer como ingress. Si lo has hecho bien deberás ver como se crean solos los 2 discos persistentes en hetzner así como el load balancer. El wordpress tendrá 2 instancias frontales
