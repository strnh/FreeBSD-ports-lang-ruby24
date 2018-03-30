# FreeBSD-ports-lang-ruby24
FreeBSD ports local patch

<p> Usage: </p>
<p>
<pre>
$ mkdir foo
$ cd foo
$ git clone https://github.com/strnh/FreeBSD-ports-lang-ruby24.git
$ cd FreeBSD-ports-lang-ruby24/patch
$ sudo patch -d /usr/ports < patch-2.4.3to2.4.4
$ sudo patch -d /usr/ports < patch-2.4.3to2.4.4.mk
$ cd /usr/ports/lang/ruby24
$ sudo make makesum
$ sudo make all
$ sudo make deinstall install
</pre>
<br>
That's all forks!
</p>
