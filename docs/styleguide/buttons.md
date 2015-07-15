---
layout: page
title: Buttons
---

## Contents

* Will be replaced with the ToC, excluding the "Contents" header
{:toc}


## Default

{% example html %}
<button class="btn" type="button">ตกลง</button>
<a class="btn" href="#" role="button">ตกลง</a>
{% endexample %}

{% example html %}
<button class="btn" type="button">ตกลง</button>
<button class="btn btn-sm" type="button">ตกลง</button>
{% endexample %}


## Primary

{% example html %}
<button class="btn btn-primary" type="button">ตกลง</button>
<button class="btn btn-sm btn-primary" type="button">ตกลง</button>
{% endexample %}


## Disabled state

{% example html %}
<button class="btn" type="button" disabled>ตกลง</button>
<a class="btn disabled" href="#" role="button">ตกลง</a>
{% endexample %}

{% example html %}
<button class="btn btn-primary" type="button" disabled>ตกลง</button>
<a class="btn btn-primary disabled" href="#" role="button">ตกลง</a>
{% endexample %}


## Block buttons

{% example html %}
<p><button class="btn btn-block" type="button">ตกลง</button></p>
<p><button class="btn btn-sm btn-block" type="button">ตกลง</button></p>
{% endexample %}


## With icons
{% example html %}
<p>
  <button class="btn btn-icon" type="button"><i class="icon fa fa-thumbs-o-up"></i>ชอบ</button>
  <button class="btn btn-icon" type="button"><i class="icon fa fa-thumbs-o-down"></i>ไม่ชอบ</button>
</p>
<p>
  <button class="btn btn-icon" type="button"><i class="icon fa fa-arrow-left"></i>ย้อนกลับ</button>
  <button class="btn btn-icon" type="button">อ่านต่อ<i class="icon fa fa-arrow-right"></i></button>
</p>
<p>
  <button class="btn btn-sm btn-icon" type="button"><i class="icon fa fa-arrow-left"></i>ย้อนกลับ</button>
  <button class="btn btn-sm btn-icon" type="button">อ่านต่อ<i class="icon fa fa-arrow-right"></i></button>
</p>
{% endexample %}


## Hidden text button

{% example html %}
<span class="hidden-text-expander">
  <a href="#">&hellip;</a>
</span>
{% endexample %}

You can also make the expander appear inline by adding `.inline`.