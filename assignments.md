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

<table>
  <thead>
    <tr>
      <th style="text-align: center">practice</th>
      <th style="text-align: center">subject</th>
      <th style="text-align: center">ِDate</th>
      <th style="text-align: center">Delivery Deadline</th>
      <th>Occasion</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: center">--</td>
      <td style="text-align: center">--</td>
      <td style="text-align: center">--</td>
      <td style="text-align: center">-</td>
      <td>University Orientation</td>
    </tr>
    <tr>
      <td style="text-align: center">-</td>
      <td style="text-align: center">--</td>
      <td style="text-align: center">---</td>
      <td style="text-align: center">---</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td style="text-align: center">-</td>
      <td style="text-align: center">---</td>
      <td style="text-align: center">--</td>
      <td style="text-align: center">--</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td style="text-align: center">--</td>
      <td style="text-align: center">---</td>
      <td style="text-align: center">---</td>
      <td style="text-align: center">---</td>
      <td>&nbsp;</td>
    </tr>
 
   
  </tbody>
</table>