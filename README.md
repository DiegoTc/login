## Instalar Node
Dar permiso a nuestro script
```
chomod +x installnode.sh
```

Ejecutar script
```
sh installnode.sh
```

## Base de datos
Iniciar nuestra base de datos
```
service mysql start
```
Crear Base de datos
```
mysql -u root -p -h localhost nodelogin < DIRECCION DEL ARCHIVO/login/databasescript.sq
```
Comando para conectarse a la base de datos
```
mysql -u root -p -h localhost nodelogin
```
