# tcp_sockets
Simple messaging program using TCP Socket connections

<p>
This is my first program using TCP Sockets.  It was a class assignment so even though some of the output may seem out of the ordinary it was a requirement.  I am posting this to help anyone else trying to understand TCP sockets and have included in the comments links to sites i used as references during the development of this program that i found helpful.
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
<p>
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
</p>
