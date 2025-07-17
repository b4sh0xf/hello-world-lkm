# hello-world-lkm

## compile and load module:
```bash
➜  git clone https://github.com/b4sh0xf/hello-world-lkm.git
➜  cd hello-world-lkm/
➜  hello-world-lkm make
➜  hello-world-lkm insmod hello.ko
➜  hello-world-lkm dmesg | tail -n5
➜  hello-world-lkm make
```

## remove module
```bash
➜  hello-world-lkm rmmod hello.ko
➜  hello-world-lkm dmesg | tail -n5
```
