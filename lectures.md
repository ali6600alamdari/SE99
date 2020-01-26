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
        <span><a href="&#10;            &#10;              /fc98 &#10;            ">Lab14 - All other programming languages</a>
        </span><br>

        
            <strong>tl;dr:</strong> 
            Our goal for today was to learn and code as many languages as possible. First, we started everyone off by writing a piece of code that involved console input/output, a conditional statement and a loop statement in C++ using STL library. Next, we introduced the most popular programming language, JavaScript. We started by writing some console app using nodejs. Next, we explained that JavaScript is the only programming language that runs inside the browser, and hence its popularity. We demonstrated how the 'document' object is provided by the browser when run inside the browser and how it can be used to access or modify HTML components. After the break, we continued our quest for learning programming languages to Java. We explained how Java is different from both interpreted and compiled languages by way of producing byte-code using javac.exe and java.exe for running the code. After students wrote the same piece of code in Java, we moved onto C-Sharp and repeated the same process for C-Sharp using .NET Core 3.1 and dotnet.exe. Due to student exhaustion we only demonstrated PHP and Go Language without students compiling/coding on their own machine. We also only looked at some Perl, Kotlin, Kotlin Script, F-Sharp and Rust code.
            <br>
        

        <strong>
            <div>
    
    
    
    [<a title="Download video (mp4)" href="&#10;    &#10;      https://drive.iust.ac.ir/index.php/s/Xu0ZXbjx5bsakKV/download?path=%2FVideos&amp;files=lab14a.mp4 &#10;    ">video</a>]
    
    
    [<a title="Download video (mp4)" href="&#10;    &#10;      https://drive.iust.ac.ir/index.php/s/Xu0ZXbjx5bsakKV/download?path=%2FVideos&amp;files=lab14b.mp4 &#10;    ">video2</a>]
    
    
    
    
    [<a title="Download codes (zip)" href="&#10;    &#10;      https://drive.iust.ac.ir/index.php/s/Xu0ZXbjx5bsakKV/download?path=%2FCode&amp;files=Lab14.zip &#10;    ">codes</a>]
    
    
    
    
    
    
    
    
    
    
    
</div>

        </strong>
    </div>
</div>