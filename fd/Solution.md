
 `int fd = atoi( argv[1] ) - 0x1234;` - fd takes in argument and converts it to int format then sub 0x1234 [4660 in decimal]\
 `len = read(fd, buf, 32);`           - reads and writes 32 bit into buf [fd 0 = stdin]\
 `if(!strcmp("LETMEWIN\n", buf))`     - checks if buf == LETMEWIN\

```
fd@pwnable:~$ ./fd 4660
LETMEWIN
good job :)
mommy! I think I know what a file descriptor is!!
```
