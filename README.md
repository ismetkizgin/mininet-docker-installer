# Mininet Docker Installer

To establish a relationship between Onos and Mininet, Onos must first be established. [You can find the Onos installation by clicking here.](https://github.com/ismetkizgin/onos-docker-installer)

Publishing the project on the docker
```
  $ docker-compose up
```

Terminate a project live on Docker
```
  $ docker-compose down
```

The created Mininet is entered into the container and begins to be used.
```
  $ docker exec -ti mininet-project bash
```

For the Onos and Mininet relationship, it provides the relationship after the Onos container string and port address are entered in the Mininet controller.
```
  $ mn --controller remote,ip=192.168.1.247,port=6653
```
