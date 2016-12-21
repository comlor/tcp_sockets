# tcp_sockets
Simple messaging program using TCP Socket connections

<p>
This is my first program using TCP Sockets.  It was a class assignment so even though some of the output may seem out of the ordinary it was a requirement.  I am posting this to help anyone else trying to understand TCP sockets and have included in the comments links to sites i used as references during the development of this program that i found helpful.
</p>
<p>
This program is free for anyone to use.
</p>
<p>
This program is an implementation of both a client and a server using TCP Sockets.  This will only run on Linux/OSX.  Since winsock is not used windows is unable to run this program.  
</p>
<p>To compile use the following command</p>
<code>g++ chat.cpp -o chat.o -std=c++11 -lpthread</code>
<p>To compile using makefile</p>
<code>make chat.cpp</code>
</br>
<p>To run, use the following command</p>
<code>./chat.o 12345</code>
<p>NOTE: 12345 is the listening port number for the server</p>
