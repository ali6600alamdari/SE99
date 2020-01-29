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
      <th style="text-align: center">Week</th>
      <th style="text-align: center">Saturday</th>
      <th style="text-align: center">Monday</th>
      <th style="text-align: center">Lecture Topic</th>
      <th style="text-align: center">HW Topic</th>
      <th style="text-align: center">HW Release</th>
      <th>Occasion</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: center">1</td>
      <td style="text-align: center">6/31</td>
      <td style="text-align: center">7/02</td>
      <td style="text-align: center">-</td>
      <td style="text-align: center">&nbsp;</td>
      <td style="text-align: center">&nbsp;</td>
      <td>University Orientation</td>
    </tr>
    <tr>
      <td style="text-align: center">2</td>
      <td style="text-align: center">7/7</td>
      <td style="text-align: center">7/09</td>
      <td style="text-align: center">Python:Intro</td>
      <td style="text-align: center">&nbsp;</td>
      <td style="text-align: center">&nbsp;</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td style="text-align: center">3</td>
      <td style="text-align: center">7/14</td>
      <td style="text-align: center">7/16</td>
      <td style="text-align: center">Python:Math/Input/Output/variables</td>
      <td style="text-align: center">&nbsp;</td>
      <td style="text-align: center">&nbsp;</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td style="text-align: center">4</td>
      <td style="text-align: center">7/21</td>
      <td style="text-align: center">7/23</td>
      <td style="text-align: center">Python:Loops/Condition/Stack/Scope</td>
      <td style="text-align: center">&nbsp;</td>
      <td style="text-align: center">&nbsp;</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td style="text-align: center">5</td>
      <td style="text-align: center">7/28</td>
      <td style="text-align: center">7/30</td>
      <td style="text-align: center">Python:Debug/Test/Hackathon Intro</td>
      <td style="text-align: center">&nbsp;</td>
      <td style="text-align: center">&nbsp;</td>
      <td>Saturday Off</td>
    </tr>
    <tr>
      <td style="text-align: center">6</td>
      <td style="text-align: center">8/05</td>
      <td style="text-align: center">8/07</td>
      <td style="text-align: center">Hackathon Week</td>
      <td style="text-align: center">&nbsp;</td>
      <td style="text-align: center">&nbsp;</td>
      <td>Sunday &amp; Tuesday Off</td>
    </tr>
    <tr>
      <td style="text-align: center">7</td>
      <td style="text-align: center">8/12</td>
      <td style="text-align: center">8/14</td>
      <td style="text-align: center">Python:Hackathon Presentation</td>
      <td style="text-align: center">&nbsp;</td>
      <td style="text-align: center">&nbsp;</td>
      <td>Wednesday Off</td>
    </tr>
    <tr>
      <td style="text-align: center">8</td>
      <td style="text-align: center">8/19</td>
      <td style="text-align: center">8/21</td>
      <td style="text-align: center">Python:Turtle Graphics Physics</td>
      <td style="text-align: center">&nbsp;</td>
      <td style="text-align: center">&nbsp;</td>
      <td>Basic Sceince Midterms</td>
    </tr>
    <tr>
      <td style="text-align: center">9</td>
      <td style="text-align: center">8/26</td>
      <td style="text-align: center">8/28</td>
      <td style="text-align: center">Python:VPython, More Physcis</td>
      <td style="text-align: center">&nbsp;</td>
      <td style="text-align: center">&nbsp;</td>
      <td>Basic Sceince Midterms</td>
    </tr>
    <tr>
      <td style="text-align: center">10</td>
      <td style="text-align: center">9/03</td>
      <td style="text-align: center">9/05</td>
      <td style="text-align: center">Python: Matplotlib, Math Problems</td>
      <td style="text-align: center">&nbsp;</td>
      <td style="text-align: center">&nbsp;</td>
      <td>Basic Sceince Midterms</td>
    </tr>
    <tr>
      <td style="text-align: center">11</td>
      <td style="text-align: center">9/10</td>
      <td style="text-align: center">9/12</td>
      <td style="text-align: center">C:Input/Output/Syntax/VSCode/Debug</td>
      <td style="text-align: center">Redoing Python Problems in C</td>
      <td style="text-align: center">&nbsp;</td>
      <td>&nbsp;</td>
    </tr>
 
   
  </tbody>
</table>