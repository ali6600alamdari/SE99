---
layout: page
title: Lectures
permalink: /lectures/
---

You can download the lectures here (in PDF format). I will try to upload lectures prior to their corresponding classes.


<ul id="archive">
{% for lecture in site.lectures reversed %}
<li class="archiveposturl" style="background: transparent">
<div class="lecture-container">
    {% if lecture.thumbnail %}
    <div class="thumbnail">
      <div class="center-cropped" style="margin-top:5px;margin-bottom:5px;background-image: url('{{ lecture.thumbnail | prepend: site.baseurl }}');">
        <img src="{{ lecture.thumbnail | prepend: site.baseurl }}"/>
      </div>
    </div>
    {% endif %}
    <div class="content">
        <span><a href="
            {% if lecture.slides contains '://' %}
              {{ lecture.slides }} 
            {% else %}
              {{ lecture.slides | prepend: site.baseurl }} 
            {% endif %}">{{ lecture.title }}</a>
        </span><br>

        {% if lecture.tldr %}
            <strong>tl;dr:</strong> 
            {{ lecture.tldr }}
            <br/>
        {% endif %}

        <strong>
            {% include lecture_links.html lecture=lecture %}
        </strong>
    </div>
</div>
</li>
{% endfor %}
</ul>
<div class="lecture-container">
    
    <div class="content">
        <span><a href="&#10;            &#10;              /fc98 &#10;            ">lable</a>
        </span><br>

        
            <strong>tl;dr:</strong> 
           discribtion
            <br>
        

        <strong>
            <div>
    
    
    
    [<a title="Download video (mp4)" href="&#10;    &#10;      link &#10;    ">video</a>]
    
    
    [<a title="Download video (mp4)" href="&#10;    &#10;     link &#10;    ">txt</a>]
    
    
    
    
    [<a title="Download codes (zip)" href="&#10;    &#10;     link &#10;    ">codes</a>]
    
    
    
    
    
    
    
    
    
    
    
</div>

        </strong>
    </div>
</div>