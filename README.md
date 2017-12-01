Requirements
=============
  
 * thrift
 * python thrift lib


To Compile
==========

For compiling the HaHs server 

    g++ -DHAVE_INTTYPES_H -DHAVE_NETINET_IN_H -Wall -I/usr/local/include/thrift *.cpp -L/usr/local/lib -lthrift -lthriftnb -levent -o server

Add flag -lmicrohttpd if you use microhttpd for c++ 

    g++ -DHAVE_INTTYPES_H -DHAVE_NETINET_IN_H -Wall -I/usr/local/include/thrift *.cpp -L/usr/local/lib -lthrift -lthriftnb -lmicrohttpd -levent -o server

To Run
========
./server

Link:
========
<script src="https://gist.github.com/betapcode/4a6c56ba5ff4112a052616caafd57744.js"></script>



