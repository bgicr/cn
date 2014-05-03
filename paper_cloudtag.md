---
layout: page
title: Paper
---
{% include JB/setup %}
<div id="whatever">
  <a href="/path" rel="7">peace</a>
  <a href="/path" rel="3">unity</a>
  <a href="/path" rel="10">love</a>
  <a href="/path" rel="5">having fun</a>
</div>
 
<script src="{{ BASE_PATH }}/assets/js/jquery.tagcloud.js" type="text/javascript" charset="utf-8"></script>
<script src="{{ BASE_PATH }}/assets/js/jquery-1.11.1.min.js" type="text/javascript" charset="utf-8"></script>
<script language="javascript">

$.fn.tagcloud.defaults = {
  size: {start: 14, end: 18, unit: 'pt'},
  color: {start: '#cde', end: '#f52'}

};

$(function () {
  $('#whatever a').tagcloud();

		});
</script>
