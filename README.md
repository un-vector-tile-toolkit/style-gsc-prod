# style-gsc-01
for styling work for UNVT deployment - prototype 1

## usage
```console
git git clone https://github.com/un-vector-tile-toolkit/style-gsc-01
cd style-gsc-01  
docker run -it --rm -v ${PWD}:/data unvt/nanban  
cd /data  
vi hocon/source.conf   (edit source)
rake  
```  

##note
for easy work, there are 8 groups of style layers.