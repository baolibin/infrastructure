
## URI
URL(Uniform Resource Locator)统一资源定位符，可以直接使用此类找到网络上的资源(比如一个网页)。

## Socket
socket是进程间通信的一种机制。  
在操作系统中，通常会为应用程序提供一组应用程序接口，成为套接字接口(Socket API)。   
应用程序可以通过套接字接口，来使用网络套接字，以进行数据交换。  
在套接字接口中，以IP地址和通信端口组成套接字地址(Socket Address)。  
远程的套接字地址，以及本地的套接字地址完成连线后，再加上使用的协议(protocol)，这个五元组(five-element tuple)，作为套接字对(socket pairs)，之后就可以彼此交换数据。  
例如，在同一台计算机上，TCP协议与UDP协议可以同时使用相同的port而互不干扰。 操作系统根据套接字地址，可以决定应该将数据送达特定的进程或线程。这就像是电话系统中，以电话号码加上分机号码，来决定通话对象一般。
