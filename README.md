tiny-elf
========
A very tiny ELF (Executable and Linkable Format) executable, that does exactly the same as
```
int main(void) {
  return 42;
}
```
but a 100 times thinner.

####Source####
http://www.muppetlabs.com/~breadbox/software/tiny/teensy.html

####Run it####
```
$ nasm -f bin -o a.out tiny.asm
$ chmod +x a.out
$ ./a.out ; echo $?
  42
$ wc -c a.out
  45 a.out
```

####Credits####
All credits to muppetlabs.com
