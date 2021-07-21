# Jenkis

## Permisos sobre folder  volume

```sh
cd jenkins_home/
chown -R 1000:1000 .
```

## Run Jenkins :

```sh
docker-compose up -d
```
## KEY de inicio de app : 

Se debe ingresar al contenedor y correr un cat Y copair la *'initialAdminPassword'*.

```sh
docker exec -it {id_container} bash
```
```sh
jenkins@CONTAINER:/$ cat /var/jenkins_home/secrets/initialAdminPassword
```
```sh
 {KEY_initialAdminPassword}

```