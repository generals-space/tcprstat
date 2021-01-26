# tcprstat

## 编译方法

环境: CentOS 7

依赖安装

```
yum install -y gcc make patch automake bison flex glibc-static
```

`bootstrap`生成`configure`文件

```
chmod 755 ./bootstrap
./bootstrap
```

`configure`生成`Makefile`文件.

```
./configure
```

然后在工程根目录执行`make`, 会在`src`目录下生成`tcprstat`与`tcprstat-static`两个可执行文件.
