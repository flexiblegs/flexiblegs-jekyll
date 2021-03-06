---
layout: flexiblegs
dynamic_title: learn
permalink: /learn/
---

<div class="dn-browser">
  <div class="dn-browser-header">
    <div class="dn-style--title">{{ site.t.[page.language].[page.dynamic_title].title }}</div>
    {% include flexiblegs/logo.html %}
  </div>
  <div class="dn-browser-body">
    <div class="dn-browser-body__item">
      <div class="wrap xl-table xl-gutter-40 xl-top xl-center md-normal">
        <div class="col xl-width-360 md-1-1">
          {% include flexiblegs/social-media.html %}
        </div>
        <div class="col xl-1-1">
          <div class="dn-content">
            {% if page.language == 'en' %}
              <p>Before starting learn you need to know about <b>Grid System</b> and <b>Responive Design</b>.</p>
            {% endif %}
            {% if page.language == 'tr' %}
              <p>Öğrenmeye başlamadan önce <b>Grid System</b> ve <b>Responive Design</b> hakkında bilgi sahibi olmanız gerekmektedir.</p>
            {% endif %}
            <div class="dn-height-16"></div>
            <p><b>Responsive Meta</b></p>
            <div class="dn-height-16"></div>
            <pre><div class="dn-tag dn-tag--gray dn-tag--bottom">.html</div><!--
              --><div class="comment">&lt;head&gt;<br/><!--
              -->&nbsp;&nbsp;&lt;meta name="viewport" content="width=device-width, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no"&gt;<br/><!--
              -->&lt;/head&gt;</div><!--
            --></pre>
            <div class="dn-height-24"></div>
            {% if page.language == 'en' %}
              <p><i class="fa fa-rocket fa-lg"></i>&nbsp;&nbsp;<b>Compiled View</b></p>
            {% endif %}
            {% if page.language == 'tr' %}
              <p><i class="fa fa-rocket fa-lg"></i>&nbsp;&nbsp;<b>Derlenmiş Görünüm</b></p>
            {% endif %}
            <div class="dn-height-8"></div>
            {% if page.language == 'en' %}
              <p>Switching to compile view you view the CSS properties of classes and mixins. Having a knowledge about this topic will improve your usage.</p>
            {% endif %}
            {% if page.language == 'tr' %}
              <p>Derlenmiş görünüme geçiş yaparak class veya mixinlerin oluşturduğu CSS özelliklerini görebilirsiniz. Bu konuda bilgi sahibi olmanız kullanım hakimiyetiniz açısından oldukça faydalı olacaktır.</p>
            {% endif %}
            <div class="dn-height-8"></div>
            {% if page.language == 'en' %}
              <p>On <b>CSS</b> section static, on <b>Sass</b>, <b>Less</b> or <b>Stylus</b> sections dynamic sections are marked as <b>@variable</b>.</p>
            {% endif %}
            {% if page.language == 'tr' %}
              <p><b>CSS</b> kısmında sabit, <b>Sass</b>, <b>Less</b> veya <b>Stylus</b> kısmında dinamik olacak kısımlar <b>@değişken</b> şeklinde belirtilmektedir.</p>
            {% endif %}
            <div class="dn-height-8"></div>
            {% if page.language == 'en' %}
              <p>For browser compatability <b>-ms</b>, <b>-moz</b> and <b>-webkit</b> aren't added to the samples.</p>
            {% endif %}
            {% if page.language == 'tr' %}
              <p>Browser uyumluluğu için gereken <b>-ms</b>, <b>-moz</b> ve <b>-webkit</b> yazımları eklenmemiştir.</p>
            {% endif %}
            <div class="wrap xl-gutter-24 xl-top xl-2 md-1">
              <div class="col">
                <div class="dn-height-24"></div>
                {% if page.language == 'en' %}
                  <p><b>Static</b></p>
                {% endif %}
                {% if page.language == 'tr' %}
                  <p><b>Statik</b></p>
                {% endif %}
                <div class="dn-height-16"></div>
                {% if page.language == 'en' %}
                  <ul>
                    <li><a href="/learn/wrap/?preprocessor=css#wrap-css">CSS</a> or <a href="/learn/wrap/?preprocessor=bem#wrap-bem">BEM</a></li>
                  </ul>
                {% endif %}
                {% if page.language == 'tr' %}
                  <ul>
                    <li><a href="/tr/learn/wrap/?preprocessor=css#wrap-css">CSS</a> veya <a href="/tr/learn/wrap/?preprocessor=bem#wrap-bem">BEM</a></li>
                  </ul>
                {% endif %}
              </div>
              <div class="col">
                <div class="dn-height-24"></div>
                {% if page.language == 'en' %}
                  <p><b>Dynamic</b></p>
                {% endif %}
                {% if page.language == 'tr' %}
                  <p><b>Dinamik</b></p>
                {% endif %}
                <div class="dn-height-16"></div>
                {% if page.language == 'en' %}
                  <ul>
                    <li><a href="/learn/wrap/?preprocessor=scss#wrap-scss">Scss</a></li>
                    <li><a href="/learn/wrap/?preprocessor=sass#wrap-sass">Sass</a></li>
                    <li><a href="/learn/wrap/?preprocessor=less#wrap-less">Less</a></li>
                    <li><a href="/learn/wrap/?preprocessor=stylus#wrap-stylus">Stylus</a></li>
                  </ul>
                {% endif %}
                {% if page.language == 'tr' %}
                  <ul>
                    <li><a href="/tr/learn/wrap/?preprocessor=scss#wrap-scss">Scss</a></li>
                    <li><a href="/tr/learn/wrap/?preprocessor=sass#wrap-sass">Sass</a></li>
                    <li><a href="/tr/learn/wrap/?preprocessor=less#wrap-less">Less</a></li>
                    <li><a href="/tr/learn/wrap/?preprocessor=stylus#wrap-stylus">Stylus</a></li>
                  </ul>
                {% endif %}
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
