---
layout: page
title: "Team"
permalink: /team/
main_nav: true
---

Introducing the team

<div style=" border: 1px solid #ddd; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); width: 100%;margin: 20px 0;padding: 20px; position: relative; box-sizing: border-box;">     
  <img src="/assets/Klaus.png" alt="Image description" style="width: 150px; height: 150px; object-fit: cover; position: absolute; top: 10px; left: 10px;">
  <div style="margin-left: 180px; text-align: left;">
    <h2 style="margin-bottom: 10px;">Prof. Dr. Klaus Maier-Hein</h2>
    <p style="font-size: 16px; color: #555;">
      – Full Professor (W3) at Heidelberg University, since 2020
      – Head of Division of Medical Image Computing, DKFZ, since 2017 – Head of Pattern Analysis and Learning Group, Heidelberg University Hospital, since 2017.
      – University lecturer at Heilbronn University/Heidelberg University, since 2009
    </p>    
  </div>
</div>

<div style=" border: 1px solid #ddd; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); width: 100%;margin: 20px 0;padding: 20px; position: relative; box-sizing: border-box;">     
  <img src="/assets/Ralf.jpg" alt="Image description" style="width: 150px; height: 150px; object-fit: cover; position: absolute; top: 10px; left: 10px;">
  <div style="margin-left: 180px; text-align: left;">
    <h2 style="margin-bottom: 10px;">Dr. Ralf Floca</h2>
    <p style="font-size: 16px; color: #555;">
      – Group Lead “Software development for Integrated Diagnostics and Therapy”, German Cancer Research Center (since 2010)
      – University lecturer at Heilbronn University/Heidelberg University, since 2006
    </p>    
  </div>
</div>

<div style=" border: 1px solid #ddd; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); width: 100%;margin: 20px 0;padding: 20px; position: relative; box-sizing: border-box; height:200px;">     
  <img src="/assets/franzi.jpg" alt="Image description" style="width: 150px; height: 150px; object-fit: cover; position: absolute; top: 10px; left: 10px;">
  <div style="margin-left: 180px; text-align: left;">
    <h2 style="margin-bottom: 10px;">Dr. Franziska Boenisch</h2>
    <p style="font-size: 16px; color: #555;">
      Tenure-Track Professor at CISPA, since 2023
    </p>    
  </div>
</div>

<div style=" border: 1px solid #ddd; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); width: 100%;margin: 20px 0;padding: 20px; position: relative; box-sizing: border-box;">     
  <img src="/assets/adam.jpg" alt="Image description" style="width: 150px; height: 150px; object-fit: cover; position: absolute; top: 10px; left: 10px;">
  <div style="margin-left: 180px; text-align: left;">
    <h2 style="margin-bottom: 10px;">Dr. Adam Dziedzic</h2>
    <p style="font-size: 16px; color: #555;">
      Adam is a Tenure Track Faculty Member at CISPA Helmholtz Center for Information Security, co-leading the SprintML group. His research is focused on secure and trustworthy Machine Learning as a Service (MLaaS). Adam designs robust and reliable machine learning methods for training and inference of ML models while preserving data privacy and model confidentiality. Adam was a Postdoctoral Fellow at the Vector Institute and the University of Toronto, and a member of the CleverHans Lab, advised by Prof. Nicolas Papernot. He earned his PhD at the University of Chicago, where he was advised by Prof. Sanjay Krishnan and worked on input and model compression for adaptive and robust neural networks. Adam obtained his Bachelor's and Master's degrees from the Warsaw University of Technology in Poland. He was also studying at DTU (Technical University of Denmark) and carried out research at EPFL, Switzerland. Adam also worked at CERN (Geneva, Switzerland), Barclays Investment Bank in London (UK), Microsoft Research (Redmond, USA), and Google (Madison, USA).
    </p>    
  </div>
</div>

<div style=" border: 1px solid #ddd; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); width: 100%;margin: 20px 0;padding: 20px; position: relative; box-sizing: border-box; height:200px;">     
  <img src="/assets/Santhosh.jpeg" alt="Image description" style="width: 150px; height: 150px; object-fit: cover; position: absolute; top: 10px; left: 10px;">
  <div style="margin-left: 180px; text-align: left;">
    <h2 style="margin-bottom: 10px;">Santhosh Parampottupadam</h2>
    <p style="font-size: 16px; color: #555;">
      PhD student at DKFZ
    </p>    
  </div>
</div>

<div style=" border: 1px solid #ddd; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); width: 100%;margin: 20px 0;padding: 20px; position: relative; box-sizing: border-box; height:200px;">     
  <img src="/assets/Wenhao.png" alt="Image description" style="width: 150px; height: 150px; object-fit: cover; position: absolute; top: 10px; left: 10px;">
  <div style="margin-left: 180px; text-align: left;">
    <h2 style="margin-bottom: 10px;">Wenhao Wang</h2>
    <p style="font-size: 16px; color: #555;">
      Ph.D. student at CISPA
    </p>    
  </div>
</div>

<div style=" border: 1px solid #ddd; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); width: 100%;margin: 20px 0;padding: 20px; position: relative; box-sizing: border-box; height:200px;">     
  <img src="/assets/Jyotika.jpg" alt="Image description" style="width: 150px; height: 150px; object-fit: cover; position: absolute; top: 10px; left: 10px;">
  <div style="margin-left: 180px; text-align: left;">
    <h2 style="margin-bottom: 10px;">Jyotika Mahapatra</h2>
    <p style="font-size: 16px; color: #555;">
      Research Assistant at CISPA
    </p>    
  </div>
</div>



{% for category in site.categories %}
  {% capture cat %}{{ category | first }}{% endcapture %}
  <h2 id="{{cat}}">{{ cat | capitalize }}</h2>
  {% for desc in site.descriptions %}
    {% if desc.cat == cat %}
      <p class="desc"><em>{{ desc.desc }}</em></p>
    {% endif %}
  {% endfor %}
  <ul class="posts-list">
  {% for post in site.categories[cat] %}
    <li>
      <strong>
        <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </strong>
      <span class="post-date">- {{ post.date | date_to_long_string }}</span>
    </li>
  {% endfor %}
  </ul>
  {% if forloop.last == false %}<hr>{% endif %}
{% endfor %}
<br>
