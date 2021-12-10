###

### install ###
mkdir -p /usr/local/include/SimpleSocket/
cp -a -f *h /usr/local/include/SimpleSocket/
make
cmake .
cp -a -f libnetwork.a /usr/local/lib/libsimplesocket.a

### usage ###
gcc -I/usr/local/include/SimpleSocket -lsimplesocket 
