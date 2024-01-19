### Assemble source file(Using nasm)
```bash
nasm -f win32 main.asm -o main.obj
```

### Link obj file
```bash
ld -m i386pe -s -o main.exe main.obj
```
