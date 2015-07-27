---
layout: page
title: Typography
---

Headings, paragraphs, blockquotes, lists,
and more have some global resets. It's worth noting these aren't the same as our Markdown styles.

## Contents

* Will be replaced with the ToC, excluding the "Contents" header
{:toc}


## Font stack

Heading font: [PGVIM](http://www.f0nt.com/release/pgvim/)
Body font: Tahoma

{% example html %}
<!-- PGVIM font for heading text -->
<h3>พระสัมมาสัมพุทธเจ้า</h3>
<!-- Tahoma font for body text -->
<p>พระสัมมาสัมพุทธเจ้า หรือ พระพุทธเจ้า เป็นพระสมัญญานามที่ใช้เรียกพระบรมศาสดาของศาสนาพุทธ พระพุทธศาสนาทั้งฝ่ายเถรวาทและมหายานต่างนับถือพระพุทธเจ้าว่าเป็นศาสดาของตนเหมือนกันแต่รายละเอียดปลีกย่อยต่างกัน ฝ่ายเถรวาทให้ความสำคัญกับพระพุทธเจ้าพระองค์ปัจจุบันคือ "พระโคตมพุทธเจ้า" ซึ่งเชื่อว่าเป็นพระองค์ที่ 4 ในภัทรกัปนี้ และมีกล่าวถึงพระพุทธเจ้าในอดีตกับในอนาคตบ้างแต่ไม่ให้ความสำคัญเท่า ฝ่ายมหายานนับถือพระพุทธเจ้าของฝ่ายเถรวาททั้งหมดและเชื่อว่านอกจากพระพุทธเจ้า 28 พระองค์[1] ที่ระบุในพุทธวงศ์ของพระไตรปิฎกภาษาบาลีแล้ว ยังมีพระพุทธเจ้าอีกมากมายเพิ่มเติมขึ้นมาจากตำนานของเถรวาท</p>
{% endexample %}


## Headings

{% example html %}
<h1>h1. วัดตานีนรสโมสร</h1>
<h2>h2. วัดตานีนรสโมสร</h2>
<h3>h3. วัดตานีนรสโมสร</h3>
<h4>h4. วัดตานีนรสโมสร</h4>
<h5>h5. วัดตานีนรสโมสร</h5>
<h6>h6. วัดตานีนรสโมสร</h6>
{% endexample %}

## Body text

{% example html %}
<p>ผู้ปรารถนาจะเป็นพระพุทธเจ้าต้องบำเพ็ญบารมีเป็นพระโพธิสัตว์ก่อน เมื่อบารมีเต็มแล้วจึงจะได้ตรัสรู้เป็นพระพุทธเจ้าในชาติสุดท้าย</p>
<p>พระพุทธเจ้าทุกพระองค์มีลักษณะพิเศษตรงกันคือ[2] เป็นมนุษย์เพศชายเกิดในวรรณะกษัตริย์หรือพราหมณ์ พร้อมด้วยมหาปุริสลักขณะ ก่อนออกผนวชจะอภิเษกสมรสมีพระโอรสพระองค์หนึ่ง วันออกผนวชจะตรงกับวันเพ็ญเดือนอาสาฬหะ</p>
<p>ตามคัมภีร์ฝ่ายพุทธ ถือกันว่า พระพุทธเจ้า (พระโคตมพุทธเจ้า) พระองค์ดำรงพระชนม์ชีพอยู่ระหว่าง 80 ปีก่อนพุทธศักราช จนถึงเริ่มพุทธศักราชซึ่งเป็นวันปรินิพพาน ตรงกับ 543 ปีก่อนคริสตกาลตามตำราไทยอ้างอิงปฏิทินสุริยคติไทยและปฏิทินจันทรคติไทย และ 483 ปีก่อนคริสตกาลตามปฏิทินสากล</p>
{% endexample %}

## Lead

Make a paragraph stand out by adding `.lead`.

{% example html %}
<p class="lead">
	พระสัมมาสัมพุทธเจ้า หรือ พระพุทธเจ้า เป็นพระสมัญญานามที่ใช้เรียกพระบรมศาสดาของศาสนาพุทธ
</p>
{% endexample %}

## Links

{% example html %}
<a href="https://google.com" title="to Google" target="_blank">กูเกิ้ล</a><br />
{% endexample %}


### Link with icons

{% example html %}
<a href="#" title="to nowhere">อ่านต่อ<i class="icon fa fa-angle-right"></i></a>
<br />
<a href="#" title="to nowhere"><i class="icon fa fa-angle-left"></i>ก่อนหน้า</a>
{% endexample %}