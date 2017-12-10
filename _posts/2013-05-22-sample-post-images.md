---
layout: post
title: "Passion Techno 2017"
date: 2013-05-22
excerpt: "Examples and code for displaying images in posts."
tags: [sample post, images, test]
---

Sistem Informasi kembali menggelar acara rutin Parade, Seni Sistem Informasi dan Teknologi (Passion Techno) pada 7-9 November 2017.  Kegiatan ini dilaksanakan di Halaman Fakultas Sains dan Teknologi (FST). Acara ini berlangsung meriah. Acara yang diketuai oleh Sirajuddin Usman ini mengusung tema a Blend of Art and Technology mengandung arti perpaduan acara seni dan teknologi. Passion Techno tahun ini bergandengan dengan acara Olimpiade Teknologi Informasi dan Komunikasi (OTIK).

### Figures (for images or video)

#### One Up

<figure>
	<a href="http://farm9.staticflickr.com/8426/7758832526_cc8f681e48_b.jpg"><img src="http://farm9.staticflickr.com/8426/7758832526_cc8f681e48_c.jpg"></a>
	<figcaption><a href="https://fst.uin-suska.ac.id/2017/11/09/tahun-ke-4-passion-techno-berlangsung-meriah/" title="passion techno"></a>.</figcaption>
</figure>
Perlombaaan yang diselenggarakan dalam acara ini ada delapan, diantaranya; nasyid, tari tradisional, akustik, stand up comedy, vokal solo, selfie contest, poster digital, dan doodle art dalam cakupan peserta se-Riau. Acara ini didukung oleh panitia yang berjumlah 150 orang dari angkatan 2015-2017. Selain itu, acara ini juga di meriahkan oleh bazar kuliner dan komunitas yang menambah kemeriahan acara. Pengumuman pemenang dari semua perlombaan dilakukan di hari terakhir pergelaran acara Passion Techno 2017.

RELATED POSTS


#### Two Up

Apply the `half` class like so to display two images side by side that share the same caption.

{% highlight html %}
<figure class="half">
    <a href="/images/image-filename-1-large.jpg"><img src="/images/image-filename-1.jpg"></a>
    <a href="/images/image-filename-2-large.jpg"><img src="/images/image-filename-2.jpg"></a>
    <figcaption>Caption describing these two images.</figcaption>
</figure>
{% endhighlight %}

And you'll get something that looks like this:

<figure class="half">
	<a href="http://placehold.it/1200x600.JPG"><img src="http://placehold.it/600x300.jpg"></a>
	<a href="http://placehold.it/1200x600.jpeg"><img src="http://placehold.it/600x300.jpg"></a>
	<figcaption>Two images.</figcaption>
</figure>

#### Three Up

Apply the `third` class like so to display three images side by side that share the same caption.

{% highlight html %}
<figure class="third">
	<img src="/images/image-filename-1.jpg">
	<img src="/images/image-filename-2.jpg">
	<img src="/images/image-filename-3.jpg">
	<figcaption>Caption describing these three images.</figcaption>
</figure>
{% endhighlight %}

And you'll get something that looks like this:

<figure class="third">
	<img src="http://placehold.it/600x300.jpg">
	<img src="http://placehold.it/600x300.jpg">
	<img src="http://placehold.it/600x300.jpg">
	<figcaption>Three images.</figcaption>
</figure>
