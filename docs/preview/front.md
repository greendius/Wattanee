---
layout: preview
title: Front page
---

{% example html %}

<div id="page-wrapper">

  {% include preview/pushy-menu.html %}

  <!-- Site Overlay -->
  <div class="site-overlay"></div>

  <div id="container"><!-- Pushy container -->

    <div class="container">

      {% include preview/site-header.html %}
      {% include preview/front-carousel.html %}
      {% include preview/front-banner-quote.html %}


      <!-- Content -->
      <div class="content">

        <div class="row">
          <div class="col col-half">
            <a href="">
              <img src="{{ site.baseurl }}/img/front-img-03.jpg" />
            </a>
          </div>

          <div class="col col-half col-last">
            <div class="panel panel-default">
              <div class="panel-header">
                <h3 class="panel-title">ข่าวประชาสัมพันธ์</h3>
              </div>
              <div class="panel-body">
                <ul class="media">
                  <li class="media-items">
                    <a href="#">
                      <div class="media-image media-left img-square">
                        <img src="http://loremflickr.com/75/75/flower" />
                      </div>
                      <div class="media-body">
                        <p class="media-title">งานประเพณีแห่เทียนเข้าพรรษา</p>
                      </div>
                    </a>
                  </li>
                  <li class="media-items">
                    <a href="#">
                      <div class="media-image media-left img-square">
                        <img src="http://loremflickr.com/75/75/flower" />
                      </div>
                      <div class="media-body">
                        <p class="media-title">จ.ปัตตานีเชิญชวนร่วมงานประเพณีแห่เทียนเข้าพรรษา 2558</p>
                      </div>
                    </a>
                  </li>
                  <li class="media-items">
                    <a href="#">
                      <div class="media-image media-left img-square">
                        <img src="http://loremflickr.com/75/75/flower" />
                      </div>
                      <div class="media-body">
                        <p class="media-title">ต้องติดตามผลงานกันหน่อยหลังเลสเตอร์ ซิตี้ได้ทำการยืนยันแต่งตั้งเคลาดิโอ รานิเอรี่เข้ามารับหน้าที่กุนซือคนใหม่ของสโมสรด้วยสัญญายาว 3 ปี</p>
                      </div>
                    </a>
                  </li>
                </ul>
              </div>
            </div>
          </div><!-- /.col -->
        </div><!-- /.row -->


        <div class="row">
          <div class="panel panel-default">
            <div class="panel-header">
              <h3 class="panel-title">กิจกรรม</h3>
            </div>
            <div class="panel-body">
              <ul class="media media-grid">
                <li class="media-items media-items-featured">
                  <a href="#">
                    <div class="media-image media-left img-square">
                      <img src="http://loremflickr.com/75/75/flower" />
                    </div>
                    <div class="media-body">
                      <p class="media-title">งานประเพณีแห่เทียนเข้าพรรษา</p>
                    </div>
                  </a>
                </li>
                <li class="media-items">
                  <a href="#">
                    <div class="media-image media-left">
                      <img src="http://loremflickr.com/75/75/flower" />
                    </div>
                    <div class="media-body">
                      <p class="media-title">จ.ปัตตานีเชิญชวนร่วมงานประเพณีแห่เทียนเข้าพรรษา 2558</p>
                    </div>
                  </a>
                </li>
                <li class="media-items">
                  <a href="#">
                    <div class="media-image media-left">
                      <img src="http://loremflickr.com/75/75/flower" />
                    </div>
                    <div class="media-body">
                      <p class="media-title">งดเหล้าเข้าพรรษา ๕๘ งดเหล้าครบพรรษา</p>
                    </div>
                  </a>
                </li>
                <li class="media-items">
                  <a href="#">
                    <div class="media-image media-left">
                      <img src="http://loremflickr.com/75/75/flower" />
                    </div>
                    <div class="media-body">
                      <p class="media-title">งดเหล้าเข้าพรรษา ๕๘ งดเหล้าครบพรรษา</p>
                    </div>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          </div><!-- /.row -->

        <!-- // TODO Image's class and size should be added for better result in small screen -->
        <div class="row">
          <div class="col col-half">
            <a href="">
              <img src="{{ site.baseurl }}/img/front-img-01.jpg" />
            </a>
          </div>

          <div class="col col-half col-last">
            <a href="">
              <img src="{{ site.baseurl }}/img/front-img-02.jpg" />
            </a>
          </div>
        </div><!-- /.row -->

      </div><!-- /.content -->

    </div><!-- /.container -->

    {% include preview/site-footer.html %}

  </div><!-- /#container -->

</div>

{% endexample %}
