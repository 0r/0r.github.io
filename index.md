---
layout: page
title: HC svnt
tagline: dracones
---
{% include JB/setup %}



### Hello

<p><img src='/assets/images/n_oah_marchal.jpg' title='n.oah marchal' alt='Photo of Noah' width='120px' align="right" />

This is the blog for n.oah marchal. I am a technology nerd with a varied, interdisciplinary background in fine art, architecture, writing, psychology, human computer interfaces, electronics, microcomputing, and more.   

During down time I am an avid runner, cyclist, m&m-a-holic, and film buff. I happily married to <a href="http://www.researchgate.net/profile/Lihui_Song/">Lihui Song</a>, Ph.D</p>









### Research

My day job is as a Senior Research Technologist at the <a href="http://freylab.missouri.edu">Rehabilitation Neuroscience Laboratory</a> at the University of Missouri developing and conducting human motor neuroscience research. 

My professional areas of interest are in functional magnetic resonance imaging, transcranial magnetic stimulation, motion kinematics, and their related analysis techniques, particulary with computational pre/post-statistics processing methods, and, as of late, parallelization of software tools for HTCondor and Son of Grid Engine environments (specifically FSL and Bedpost for crunching diffusion tensor imaging data).

Find out more about my work and interests: <a href="http://istics.org">www.Istics.org</a>
    
### Posts



<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

### WIP
1. moves
2. opinions
3. technologies
4. tips
5. interests

