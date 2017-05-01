## Installer OpenBSD 6.0 sur votre serveur Kimsufi
test
### Installer le système d'exploitation et obtenir des informations

Une fois notre serveur Kimsufi en poche, nous devons commencer par installer un système d’exploitation. Nous choisirons donc d’installer Debian 7.10 (Wheezy) (oldstable) 64 bits. Une fois l'installation terminée, nous recevons un mail avec les identifiants de connexion SSH.

Nous nous connectons ensuite à notre serveur en SSH à l'aide du logiciel PuTTY.

```markdown
login as: root
root@5.39.xx.xx's password:
Debian GNU/Linux 7.11

Linux ns30xxxxx.ip-5-39-xx.eu 3.14.32-xxxx-grs-ipv6-64 #9 SMP Thu Oct 20 14:53:52 CEST 2016 x86_64 GNU/Linux

server    : 27xxxx
hostname  : ns30xxxxx.ip-5-39-xx.eu
eth0 IPv4 : 5.39.xx.xx
eth0 IPv6 : 2001:41d0:x:xxxx::1/128
Last login: Thu Mar 16 16:16:21 2017 from cache-ng.ovh.net
```

### Préparation de l'installation

### Installation de OpenBSD
