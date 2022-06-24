---
title: Menjalankan Tor dan ProxyChains di MacOS
layout: post
date: '2022-06-24 06:56:46 +0700'
categories:
- etc
---

Install tor dan proxychains menggunakan package manager **brew**
{% highlight bash %}
$ brew install tor
$ brew install proxychains-ng
{% endhighlight %}

Jalankan Tor dan Proxychains4
{% highlight bash %}
$ brew services restart tor
$ proxychains4 -f proxychains.conf curl ipinfo.io
{% endhighlight %}

**Socksify** terminal command:
{% highlight bash %}
$ export http_proxy=socks5://127.0.0.1:9050
$ export https_proxy=socks5://127.0.0.1:9050
{% endhighlight %}

Untuk konfigurasi **proxychains.conf**, cek langsung di [repo github](http://https://github.com/purwowd/tor-proxychains4-mac)
