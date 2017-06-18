# eclipseche-on-vagrant-docker-ubuntu

## Set-up

From the root of this project, up and running the box.

```shellscript
$ vagrant up
```

After launching the VM, go and hit 

```shellscript
$ vagrant ssh
```

Now you are connected to the VM using SSH. You can see the user changed on the CLI.

## Run Eclipse CHE (latest version)

Always from Eclipse CHE home folder and under /bin, start the server

```shellscript
$ ./home/vagrant/eclipse-che-latest/eclipse*/bin/che.sh start 
```

## Test

Open your favourite web browser and go to this URL http://localhost:8080

To inspect the workspace instances, execute this command line.

```shellscript
$ docker ps
```
