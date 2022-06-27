---
title: 'Python Script: Translator IMSI to MSISDN (Telkomsel)'
layout: post
date: '2022-06-24 06:04:55 +0700'
categories:
- python
---

Skema IMSI normal pada operator seluler: **510  10  AA  BC  D1  D2  D3  D4  D5  D6**.

atau secara generalnya: **IMSI + MNC + MSIN**.

* **510**: Kode MCC untuk tsel (kode negara seluler)

* **10**: Kode MNC untuk tsel (kode jaringan seluler)

* **AA**: Awalan untuk HLR (berisi informasi pelanggan seluler sesuai arsitektur GSM 10 - 99)
 
* **B**: NDC (kode tujuan nasional)

* **C**: Identitas produk (ID: Halo, Simpati, AS, dll.)

* **D1 D2 D3 D4 D5 D6**: Nomor urut (sequence) untuk IMSI dan ICCID


Berikut adalah kode NDC untuk beberapa prefix MSISDN (nomor) pada provider Telkomsel:

 * 1: NDC untuk prefix **0811**

 * 2: NDC untuk prefix **0812**

 * 3: NDC untuk prefix **0813**

 * 4: NDC untuk prefix **0852**

Masing - masing NDC juga menunjukan Produk ID yang berbeda,

**~> NDC 0811 dan NDC 0812**

* 1: untuk **Kartu Halo**
 
* 2: untuk **Kartu Simpati**

* 3:  untuk **Navigator**

* 4 untuk **Normal SIMM**

**~> NDC 0813**

* 0: untuk **Replacement Kartu Halo**

* 1: untuk **Normal Kartu Halo**

* 2: untuk **Normal Simpati**

* 3: untuk **Replacement Simpati**

* 4: untuk **Normal Navigator**

* 5: untuk **Replacement Navigator**

* 6: untuk **Normal Halo Instan**

* 7: untuk **Replacement Halo Instan**

* 8: untuk **Spare**

* 9: untuk **Recycle Number**

**~> NDC 0852**

* 2: untuk **Normal Kartu AS**

* 3: untuk **Replacement Kartu AS**

Dengan mengetahui data tersebut, maka bisa dibuat script python sederhana untuk mengubah IMSI ke MSISDN:

{% highlight python %}
#! /usr/bin/python3

def translator(imsi, ndc):
    ...
{% endhighlight %}
