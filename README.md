This simple extension provides two functions to pass and receive file descriptors across UNIX domain sockets, using the BSD-4.3+ `sendmsg()` and `recvmsg()` interfaces.
        
Direct bindings to `sendmsg()` and `recvmsg()` are not provided, as the API does not map nicely into Python.

Please note that this only supports BSD-4.3+ style file descriptor passing, and was only tested on Linux. Patches are welcomed!

For more information, see one of the R. Stevens' books:
 * Richard Stevens: Unix Network Programming, Prentice Hall, 1990; chapter 6.10

 * Richard Stevens: Advanced Programming in the UNIX Environment, Addison-Wesley, 1993; chapter 15.3
