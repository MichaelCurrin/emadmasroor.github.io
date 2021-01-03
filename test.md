---
layout: page
permalink: /Test/
---

Two-level link:

![result][nextjournal#output#101f646d-64cd-43a3-bf98-9cbc58a5ea90#result]

Direct link:

![result](https://nextjournal.com/data/QmVm2qrqEQxu171s5JKUdzpeqXZsKQaS9scnDtS9vUPyCX?content-type=image/svg%2Bxml&node-id=101f646d-64cd-43a3-bf98-9cbc58a5ea90&node-kind=output)


stuff
[nextjournal#output#101f646d-64cd-43a3-bf98-9cbc58a5ea90#result]: <https://nextjournal.com/data/QmVm2qrqEQxu171s5JKUdzpeqXZsKQaS9scnDtS9vUPyCX?content-type=image/svg%2Bxml&node-id=101f646d-64cd-43a3-bf98-9cbc58a5ea90&node-kind=output>


{% include social-media-links.html %}

{% if site.data.social-media %}
<div id="blah"> Hello, world. We have detected the data file "social-media". </div>
{% assign sm = site.data.social-media %}
{% for entry in sm %}
<div id="blah2"> one entry detected! </div>
{% assign key = entry | first %} 
"sm[key] = {{ sm[key] }} and sm[key].href = {{ sm[key].href }} and sm[key].id = {{ sm[key].id }} and sm[key].title = {{ sm[key].title }}"
{% endfor %}
{% endif %}

<p><a href="https://www.facebook.com/your-facebook-username" title="Facebook"><i class="fa fa-facebook-square"></i></a></p>
