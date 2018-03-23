# filedump

## Versions

- Homestead 7.3.0
- Vagrant 1.9.7
- Virtualbox 5.1.24
- composer 1.6.3

Files are served from /public

## Config

- Run cmd to genereta Homestead.yaml and change 

```
php vendor/bin/homestead make
```

- In Homestead.yaml change 

```
sites:
    -
        map: filedump.test
```

- Add 192.168.10.10 to /etc/hosts

````
192.168.10.10   filedump.test
````

## Run VM

In root
```
vagrant up
```

Local url

filedump.test
