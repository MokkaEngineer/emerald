## Social Media
<br>
<br>


<script>
  function face()
  {
  document.getElementById('content').style.display='none';
  document.getElementById('content0').style.display='block';
  document.getElementById('content1').style.display='none';
  }
  function twit()
  {
    document.getElementById('content').style.display='block';
    document.getElementById('content0').style.display='none';
      document.getElementById('content1').style.display='none';
  }
  function inst()
  {
    document.getElementById('content').style.display='none';
    document.getElementById('content0').style.display='none';
    document.getElementById('content1').style.display='block';
  }
</script>


<button onclick="face()">
  <span>Facebook</span>
</button>
<button onclick="twit()">
  <span>Twitter</span>
</button>
<button onclick="inst()">
  <span>Instagram</span>
</button>
&nbsp;


<div id="content">
  <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
  <p><a class="twitter-timeline" href="https://twitter.com/MokkaEngineers?ref_src=twsrc%5Etfw">Tweets by MokkaEngineers</a>
</div>

<div id="content0">
<div class="fb-page" data-href="https://www.facebook.com/1852074921741384/" data-tabs="timeline" data-width="600" data-height="" data-small-header="false" data-adapt-container-width="true" data-hide-cover="true" data-show-facepile="true"><blockquote cite="https://www.facebook.com/1852074921741384/" class="fb-xfbml-parse-ignore"><a href="https://www.facebook.com/1852074921741384/">Mokka Engineer</a></blockquote></div>
</div>

<div id="content1">
Instagram
</div>
