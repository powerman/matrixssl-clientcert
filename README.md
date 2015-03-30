# Client certificates support for MatrixSSL

This is a patch for [open MatrixSSL](http://matrixssl.com/download.html)
which add full support for **client certificates** (this feature available
only in [commercial version](http://www.peersec.com/matrixssl.html) of
MatrixSSL).

Supported MatrixSSL versions:

- 1.8.6

To use this patch with perl module
[Crypt::MatrixSSL](http://search.cpan.org/search?query=Crypt::MatrixSSL&mode=all)
just save patch in directory where you unpacked Crypt::MatrixSSL-1.86
using file name "matrixssl-1-8-6-open.patch" and then run as usually:

```
perl Makefile.PL && make && make test && sudo make install
```

Perl module
[IO::Stream::MatrixSSL](http://search.cpan.org/search?query=IO::Stream::MatrixSSL&mode=all)
support client certificates from version 1.1.0.


This patch was sponsored by [AmarCode](http://amarcode.com/) company.

- Programming: [Oleg Zhylin](mailto:oleg.zhylin@gmail.com).
- Testing and support: [Alex Efros](http://powerman.name/about/).

