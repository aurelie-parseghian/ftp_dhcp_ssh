Nous avons commencé par installer les deux machines debian sans interface, sur l’une nous avons activer le SSH durant l’installation car il nous l’a été demandé.
Ensuite nous avons mis à jour nos machines avec à l’aide des commandes :
```
apt update et apt upgrade.
```

Pour la configuration du serveur DHCP, nous avons commencé par l’installer à l’aide de la commande :
```
apt install isc-dhcp-server
```
Un problème a été rencontré celui de la commande sudo, nous avons dû l’installer en mode root (su -) :
```
apt install sudo
```

Une fois tout cela fait, nous avons configuré le serveur DHCP pour lui attribuer des adresses de classe B aux machines :

<img src="/" alt="Capture d'écran"/>
