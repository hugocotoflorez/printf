# Dumb printf implementation

## About
Just because I was borred.

## How to compile

```sh
nasm -g -f elf64 write.asm
ld write.asm
gcc write.o printf.c
```

## Usability

It only supports %d, %c and %s. (It's easy to expand tho)

