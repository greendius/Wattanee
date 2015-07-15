---
layout: page
title: Alerts
---

<!-- FIXME Need javascript for closing message -->

<div class="alert-messages">
  <div class="alert alert-warn">
    <i class="icon fa fa-warning"></i>Javascript required
  </div>
</div>

## Contents

* Will be replaced with the ToC, excluding the "Contents" header
{:toc}

## Default

{% example html %}
<div class="alert">
  พระสัมมาสัมพุทธเจ้า หรือ พระพุทธเจ้า เป็นพระสมัญญานามที่ใช้เรียกพระบรมศาสดาของศาสนาพุทธ
</div>
{% endexample %}

Add space from surrounding with `.alert-messages`

{% example html %}
<div class="alert-messages">
  <div class="alert">
    พระสัมมาสัมพุทธเจ้า หรือ พระพุทธเจ้า เป็นพระสมัญญานามที่ใช้เรียกพระบรมศาสดาของศาสนาพุทธ
  </div>
</div>
{% endexample %}

## Variations

### Default

{% example html %}
<div class="alert">
  พระสัมมาสัมพุทธเจ้า หรือ พระพุทธเจ้า เป็นพระสมัญญานามที่ใช้เรียกพระบรมศาสดาของศาสนาพุทธ
</div>
{% endexample %}

### Info

{% example html %}
<div class="alert alert-info">
  พระสัมมาสัมพุทธเจ้า หรือ พระพุทธเจ้า เป็นพระสมัญญานามที่ใช้เรียกพระบรมศาสดาของศาสนาพุทธ
</div>
{% endexample %}

### Warn

{% example html %}
<div class="alert alert-warn">
  พระสัมมาสัมพุทธเจ้า หรือ พระพุทธเจ้า เป็นพระสมัญญานามที่ใช้เรียกพระบรมศาสดาของศาสนาพุทธ
</div>
{% endexample %}

### Error
{% example html %}
<div class="alert alert-error">
  พระสัมมาสัมพุทธเจ้า หรือ พระพุทธเจ้า เป็นพระสมัญญานามที่ใช้เรียกพระบรมศาสดาของศาสนาพุทธ
</div>
{% endexample %}


## With icon

{% example html %}
<div class="alert alert-with-icon">
  <span class="icon"><i class="fa fa-info-circle"></i></span>
  พระสัมมาสัมพุทธเจ้า หรือ พระพุทธเจ้า เป็นพระสมัญญานามที่ใช้เรียกพระบรมศาสดาของศาสนาพุทธ
</div>
{% endexample %}


## Dismiss

Add a JavaScript enabled (via Crema) dismiss (close) icon on the right of any flash message.

{% example html %}
<div class="alert">
<span class="alert-close"><i class="fa fa-close"></i></span>
  พระสัมมาสัมพุทธเจ้า หรือ พระพุทธเจ้า เป็นพระสมัญญานามที่ใช้เรียกพระบรมศาสดาของศาสนาพุทธ
</div>
{% endexample %}
