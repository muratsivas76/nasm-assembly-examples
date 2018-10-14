# nasm-assembly-examples

## Getting Started



```bash
#<file>-name of your asm file.

nasm -f elf64 <file>.asm -o <file>.o

gcc <file>.o -o <file>

```
Execute script:
```bash
./<file>
```


see list numbers of interrups 
```bash
cat /usr/include/asm/unistd_64.h
```

Great Books
great reference https://www.felixcloutier.com/x86/index.html
1) http://www.stolyarov.info/books/asm_unix (russian)
2) https://www.ozon.ru/context/detail/id/4579142/ (russian)
3) Linux inside https://0xax.gitbooks.io/linux-insides/content/Theory/linux-theory-2.html
