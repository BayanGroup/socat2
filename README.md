# socat 2 docker image on alpine linux

socat version 2 is currently under development. Its main enhancement are so called address chains that concatenate simple addresses. Address chains are similar to command shell pipes, but they work bidirectionally. 

For more information, see:
* http://www.dest-unreach.org/socat/socat-version2.html
* http://www.dest-unreach.org/socat/doc/socat-addresschain.html

## Usage

to run socat:

```
docker run --expose <ports> tahaj/socat2 <args>
```
