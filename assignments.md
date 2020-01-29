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

<ul class="section-nav">
  <li class="toc-entry toc-h1"><a href="#heading1">Heading.1</a>
    <ul>
      <li class="toc-entry toc-h2"><a href="#heading1-1">Heading.1-1</a></li>
      <li class="toc-entry toc-h2"><a href="#heading1-2">Heading.1-2</a></li>
    </ul>
  </li>
  <li class="toc-entry toc-h1"><a href="#heading2">Heading.2</a>
    <ul>
      <li class="toc-entry toc-h2"><a href="#heading2-1">Heading.2-1</a>
        <ul>
          <li class="toc-entry toc-h3"><a href="#heading2-1-1">Heading.2-1-1</a></li>
          <li class="toc-entry toc-h3"><a href="#heading2-1-2">Heading.2-1-2</a></li>
        </ul>
      </li>
      <li class="toc-entry toc-h2"><a href="#heading2-2">Heading.2-2</a></li>
    </ul>
  </li>
</ul>