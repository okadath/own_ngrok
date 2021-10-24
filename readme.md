hay que compilarlo con la direccion que tendra el server

con esos tres achivos creados buildeas el ejecutable

```sh
go build
```

le das permiso al ejecutable y lo agregas en una direccion del path

```sh
sudo chmod 755 groktunnel
export PATH=$PATH:/home/okadath/Desktop/asd/
```

en el server lo ejecutas solo
```
./groktunnel 


```


en el cliente lo ejecutas con el puerto a escuchar

```
./groktunnel 8000

```