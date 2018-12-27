---
layout: page
title: Galeri Foto
excerpt: "Galeri Foto Kegiatan Warga di Alam Citra"
---

<div class="home-gallery">

  <!-- Update 8 Juli 2018 -->
  <figure class="third">
    <h3>Syawalan Warga Alam Citra - 08 Juli 2018</h3>
    {% for i in (1..35) %}
      <a class="image-popup" href="{{ site.url }}/images/2018-juli/syawalan/{{ i }}.jpg">
        <img src="{{ site.url }}/images/2018-juli/syawalan/thumb/{{ i }}.jpg">
      </a>
    {% endfor %}
  </figure>

  <!-- Update 6 Juni 2018 -->
  <figure class="third">
  <h3>Buka Bersama Warga Alam Citra - 3 Juni 2018</h3>
    {% for i in (1..16) %}
      <a class="image-popup" href="{{ site.url }}/images/2018-juni/buka-bersama/{{ i }}.jpg"><img src="{{ site.url }}/images/2018-juni/buka-bersama/thumb/{{ i }}.jpg"></a>
    {% endfor %}
  </figure>

  <!-- Update 17 Mei 2018 -->
  <h3>Bazaar Karang Taruna Alam Citra - 17 Mei 2018</h3>
  <figure class="third">
    {% for i in (1..14) %}
      <a class="image-popup" href="{{ site.url }}/images/2018-mei/bazaar/{{ i }}.jpg"><img src="{{ site.url }}/images/2018-mei/bazaar/thumb/{{ i }}.jpg"></a>
    {% endfor %}
  </figure>

  <!-- Update 10 April 2018 -->
  <h3>Kerja Bakti Warga - 8 April 2018</h3>
  <figure class="third">
    {% for i in (1..51) %}
      <a class="image-popup" href="{{ site.url }}/images/2018-april/kerjabakti/0{{ i }}.jpg"><img src="{{ site.url }}/images/2018-april/kerjabakti/thumb/0{{ i }}.jpg"></a>
    {% endfor %}
  </figure>

  <!-- Update Maret 2018 -->
  <h3>Galeri Lainnya - 2016-2017</h3>
  <figure class="third">
    {% for i in (1..40) %}
      <a class="image-popup" href="{{ site.url }}/images/2016-2017/kegiatan-alcit-({{ i }}).jpeg"><img src="{{ site.url }}/images/2016-2017/thumb/kegiatan-alcit-{{ i }}.jpg"></a>
    {% endfor %}
  </figure>

</div>
