<h2 id="publications" style="margin: 2px 0px -15px;">Key Publications</h2>

<h3 id="wmb" style="margin: 40px 0px 10px;">First author papers</h3>

X-chromosome inactivation papers, first in T cell development and then across tissues within the same individual.  

<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.wmb %}

<li>
<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if link.image %} 
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.journal }}</em>
      </div>
    <div class="links">
      {% if link.url %} 
      <a href="{{ link.url }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Journal</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.data %} 
      <a href="{{ link.data }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Data</a>
      {% endif %}
      {% if link.browser %} 
      <a href="{{ link.browser }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Browser</a>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

{% endfor %}

</ol>
</div>


<h3 id="hic" style="margin: 40px 0px 10px;">Other papers</h3>

Papers I'm on but not as first author. One paper on spermatogenesis and the Y-chromosome genes in mice, one paper on DNA N6-methyladenine in mammals.

<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.hic %}

<li>
<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if link.image %} 
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.journal }}</em>
      </div>
    <div class="links">
      {% if link.url %} 
      <a href="{{ link.url }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Journal</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.data %} 
      <a href="{{ link.data }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Data</a>
      {% endif %}
      {% if link.browser %} 
      <a href="{{ link.browser }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Browser</a>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

{% endfor %}


</ol>
</div>
