---
title: Graphic Design
layout: collector.njk
tags: navItem
---
<div class="uiux">{% for page in collections.graphic %}
      <div class="pjcard">
         <a href="/#"></a>
         <a href="{{page.url}}"><img src="/images/{{page.data.postImg}}" alt="{{page.data.postImgAlt}}">
          <div class="card_text"></a>
             <h3> <a href="{{page.url}}">{{page.data.title}}</a></h3> 
             <p>{{page.data.Time}} </p>
             <p>{{page.data.Location}}<p> 
         </div>
      </div>{% endfor %}
    </div>