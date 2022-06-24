---
title: 'Python Script: Translator IMSI to MSISDN (Telkomsel)'
layout: post
date: '2022-06-24 06:04:55 +0700'
categories:
- python
---

Skema IMSI normal pada operator seluler: **510  10  AA  BC  D1  D2  D3  D4  D5  D6**.

atau secara generalnya: **IMSI + MNC + MSIN**.

**510**: Kode MCC untuk tsel (kode negara seluler)

**10**: Kode MNC untuk tsel (kode jaringan seluler)

**AA**: Awalan untuk HLR (berisi informasi pelanggan seluler sesuai arsitektur GSM 10 - 99)

**B**: NDC (kode tujuan nasional)

**C**: Identitas produk (ID: Halo, Simpati, AS, dll.)

**D1 D2 D3 D4 D5 D6**: Nomor urut (sequence) untuk IMSI dan ICCID


{% highlight python %}
#! /usr/bin/python3

def translator(imsi, ndc):
    ...
{% endhighlight %}
