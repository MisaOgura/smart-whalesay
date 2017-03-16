### Dockerfile
```
FROM docker/whalesay:latest
MAINTAINER Misa Ogura misa.ogura01@gmail.com

ENTRYPOINT ["cowsay"]
CMD ["SHIP IT!!!"]
```
-----
### Instruction
1. Pull & run the programme without any input - whale will say the default message "SHIP IT!!!"
`$ docker run misaogura/whalesay`
```
 _
 ____________
< SHIP IT!!! >
 ------------
    \
     \
      \
                    ##        .
              ## ## ##       ==
           ## ## ## ##      ===
       /""""""""""""""""___/ ===
  ~~~ {~~ ~~~~ ~~~ ~~~~ ~~ ~ /  ===- ~~~
       \______ o          __/
        \    \        __/
          \____\______/
```

2. Make the whale say something
`$ docker run misaogura/whalesay "SHIP IT REAL GOOD\!\!\!"`

```
 ______________________
< SHIP IT REAL GOOD!!! >
 ----------------------
    \
     \
      \
                    ##        .
              ## ## ##       ==
           ## ## ## ##      ===
       /""""""""""""""""___/ ===
  ~~~ {~~ ~~~~ ~~~ ~~~~ ~~ ~ /  ===- ~~~
       \______ o          __/
        \    \        __/
          \____\______/
```
-----
### Links
- docker/whalesay repo : https://hub.docker.com/r/docker/whalesay/
- Docker tutorial: https://docs.docker.com/engine/getstarted/
-----
### Authour
Misa Ogura
