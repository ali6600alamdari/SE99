---
layout: page
title: Assignments
permalink: /assignments/
---

<ul id="archive">
{% for asg in site.assignments reversed %}
      <li class="archiveposturl" style="background: transparent">
        <span><a href="{{ asg.url | prepend: site.baseurl}}">{{ asg.title }}</a></span>
<strong style="font-size:100%; font-family: 'Titillium Web', sans-serif; float:right">
<a title="Download problems (pdf)" href="{{ asg.pdf | prepend: site.baseurl }}"><i class="fas fa-file-pdf"></i></a> 
{% if asg.attachment %}
&nbsp; <a title="Download attachments (zip)" href="{{ asg.attachment | prepend: site.baseurl }}"><i class="fas fa-file-archive"></i></a>
{% endif %}
</strong> 
      </li>
{% endfor %}
</ul>


Filename                              | Count |      Bytes |    Time
--------------------------------------+-------+------------+--------

# performance on docs.docker.com from ~Feb 2017
_includes/toc.html                    |   813 |    524.17K |  6.422

# performance on the "Minimal Mistakes" Jekyll theme
_includes/toc.html                    |    94 |     29.43K |  0.413