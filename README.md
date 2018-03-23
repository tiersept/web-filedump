# filedump

## Versions

- Homestead 7.3.0
- Vagrant 1.9.7
- Virtualbox 5.1.24
- composer 1.6.3

Files are served from /public

## Config

- Change path in homestead.yaml to project path on your machine

```
folders:
    -
        map: /Users/relic/Sites/web-filedump
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
