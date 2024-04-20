# First-assembly-programme
this is the first assembly program I have wrote, and it prints "Hello World!" in console.

To run this project follow these steps,
```
sudo apt-get install nasm
nasm -f elf32 -o hello.o hello.asm
ld -m elf_i386 -o hello hello.o
./hello
```
