---
title: Hapus VirtualBox HDDs yang tidak terpakai
layout: post
date: '2022-06-24 05:50:34 +0700'
categories:
- etc
---

Commands VM VirtualBox Command Line Management Interface yang digunakan adalah `vboxmanage`:
{% highlight bash %}
$ vboxmanage list hdds
{% endhighlight %}

Catat `uuid` hdds yang akan di hapus. Selanjutnya jalankan perintah:
{% highlight bash %}
$ vboxmanage closemedium disk {uuid} --delete
{% endhighlight %}
