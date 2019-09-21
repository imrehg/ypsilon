**NOTE:** This fork of _Ypsilon_ contains a build-fix for _macOS_ version 10.13.6 (_macOS High Sierra_). With the fix, a working _Ypsilon_ can be build using _GCC_ 9.2.0 or _Apple LLVM_ version 10.0.0 (_clang_ 1000.10.44.4).

# Ypsilon

## Overview

Ypsilon is the implementation of Scheme Programming Language, which conforms to the latest standard R6RS. It achieves a remarkably short GC pause time and the best performance in parallel execution as it implements "mostly concurrent garbage collection", which is optimized for the multi-core CPU system.

Ypsilon is easy to use as well as good for applications of any kind that require quick, reliable, and interactive data processing. It implements full features of R6RS and R6RS standard libraries including:

* arbitrary precision integer arithmetic
* rational number
* exact and inexact complex number
* implicitly phased library
* top-level program
* proper tail recursion
* call/cc and dynamic wind
* unicode
* bytevectors
* records
* exceptions and conditions
* i/o
* syntax-case
* hashtables
* enumerations

More libraries are included to support a wide variety of software development. Also it has built-in FFI which is easy to use. Please refer to the following files for FFI overview:

* example/gtk-hello.scm
* example/glut-demo.scm
* sitelib/ypsilon/glut.scm
* sitelib/ypsilon/gl.scm
* sitelib/ypsilon/ffi.scm

## Other Resources

Ypsilon has been developed as a fundamental technology for LittleWing Pinball Construction System.

* [Ypsilon Wiki](http://www.littlewingpinball.net/mediawiki/index.php/Ypsilon)
* [Ypsilon Background Story](http://www.littlewingpinball.com/contents/en/ypsilon.html)
* [Draft documents (r6rs, socket, ffi, c-types)](http://www.littlewing.co.jp/ypsilon/doc-draft/)
* [(Japanese) Ypsilon Background Story](http://www.littlewingpinball.com/contents/ja/ypsilon.html)
* [(Japanese) Ypsilon Wiki](http://www.littlewingpinball.net/mediawiki-ja/index.php/Ypsilon)
* [LittleWing Pinball Home](http://www.littlewingpinball.com/)
