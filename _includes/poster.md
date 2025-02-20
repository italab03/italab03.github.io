<h2 id="publications" style="margin: 1px 0px -15px">Conference presentations</h2>
<div class="publications">
<ol class="bibliography">
{% for link in site.data.poster.main %}
<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 1px;padding-left: 5px;">
      <div class="title" style="font-family: 'メイリオ', Meiryo;">{{ link.title }}</div>
      <div class="author" style="font-family: 'メイリオ', Meiryo;">{{ link.authors }}</div>
      <div class="periodical" style="font-family: 'メイリオ', Meiryo;">{{ link.conference }}</div>
  </div>
</div>
</li>
{% endfor %}
</ol>
</div>