tiny-elf
========
A very tiny ELF (Executable and Linkable Format) executable, that does exactly the same as
```
int main(void) {
  return 42;
}
```
but a 100 times thinner.

#### Source ####

http://www.muppetlabs.com/~breadbox/software/tiny/teensy.html

([cached version](http://webcache.googleusercontent.com/search?q=cache%3Ahttp%3A%2F%2Fwww.muppetlabs.com%2F~breadbox%2Fsoftware%2Ftiny%2Fteensy.html))

#### Run it ####

```
$ nasm -f bin -o a.out tiny.asm
$ chmod +x a.out
$ ./a.out ; echo $?
  42
$ wc -c a.out
  45 a.out
```

#### Credits ####

All credits to muppetlabs.com
