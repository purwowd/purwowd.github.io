---
title: Install Cmake v3.8.0 di Ubuntu 16.04.x
layout: post
date: '2022-06-24 05:00:00 +0700'
categories:
- linux
---

Hapus atau uninstall cmake yang terinstall pada linux OS.
{% highlight bash %}
$ sudo apt remove cmake
{% endhighlight %}

Download dulu bash script file [cmake](https://cmake.org/files/v3.8/cmake-3.8.0-Linux-x86_64.sh), dan copy ke folder `/opt`
{% highlight bash %}
$ sudo cp cmake-3.8.0-Linux-x86_64.sh /opt
$ sudo chmod +x cmake-3.8.0-Linux-x86_64.sh
{% endhighlight %}

Jalankan script, dan buat symbolic link:
{% highlight bash %}
$ sudo bash cmake-3.8.0-Linux-x86_64.sh
$ sudo ln -s /opt/cmake-3.8.0-Linux-x86_64/bin/* /usr/local/bin
{% endhighlight %}

Terakhir cek versi cmake, pastikan versi nya sudah betul.
{% highlight bash %}
$ cmake --version
{% endhighlight %}
