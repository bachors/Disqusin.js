# Disqusin.js
jQuery plugin disqus feed & stream.

<h3>Sample</h3>
<pre>$(document).ready(function(){
    $(".anu").disqusin(
        disqus_shortname = "bachors", // feed your disqus by disqus_shortname
        username = "icanbachors", // https://disqus.com/by/icanbachors
        limit = 5, // default &amp; max 25
        load_more = true, // true or false
        api_key = "Your API Key" // https://disqus.com/api/applications/
    );
});</pre>
