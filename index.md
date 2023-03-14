---
layout: page
title: DNB Hackathon
menu_title: Home
menu_icon: house-door
---

{:.secondary}
# {{ site.event_date }}
<!-- REMOVE THIS SECTION when you use this template -->
<div class="lead" markdown="1" style="color: #17479E;">
This Hackathon is organised by [Digital Nasional Berhad](https://www.digital-nasional.com.my/),
for DNB's internal activity.

</div>
<!-- END of section to remove -->
<img src="{{ site.baseurl }}/images/DNB-Leading-5G.jpg">

<div class="aside" style="color: #17479E">
    <h2><i class="bi bi-calendar3"></i> Event timeline</h2>
    <dl style="font-size: 18px;">
        <dt>{{ site.event_date }}</dt>
        <dd>Hackathon Event Schedule</dd>
        {% if site.registration_status == "soon" or site.registration_status == "open" or site.registration_status == "demo" %}
            <dt>{{ site.registration_opens_date }}</dt>
            <dd>
                Applications Open for Registration<br>
                {% if site.registration_status == 'open' %}
                    <a href="{{ site.baseurl }}{% link registration.md %}" class="btn">Register now</a>
                {% elsif site.registration_status == 'closed' %}
                    <a class="btn disabled">Registration has closed</a>
                {% elsif site.registration_status == 'soon' %}
                    <a class="btn disabled">Registration opens soon</a>
                {% endif %}
            </dd>
        {% endif %}

        <dt>{{ site.registration_closes_date }}</dt>
        <dd>Applications Close</dd>

        <dt>{{ site.submission_date }}</dt>
        <dd>Submission Timeline</dd>

        <dt>{{ site.team_semifinal_announcement }}</dt>
        <dd>Review of Submissions by Judges</dd>

        <dt>{{ site.pitch_presentation }}</dt>
        <dd>Jury Pitch Presentation</dd>

        <dt>{{ site.result_date }}</dt>
        <dd>Results Announcement</dd>
    </dl>
</div>


<div class="page-content" aria-label="Content" style="background: white; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; text-align: justify; text-justify: inter-word; color: #159957;">
<section>
<div class="wrapper">
<div>
<h3><b>Rules for joining the DNB Hackathon</b></h3>
<p>1. Participation is only open to DNB employees. The first-, second-, and third-placed winning teams will be rewarded with prizes.</p>
<p>2. Participants are allowed to join multiple teams. However, they are only eligible for one prize if more than one of their teams are selected as the top three winners. In this case, they will receive the prize from the higher-placed team (e.g., if the participant is a member of teams that placed 2nd and 3rd, they will receive the prize for the team placed 2nd).</p>
<p>3. Every team leader is to complete the registration form for their respective teams for the DNB Hackathon program, which will include information of all team members and the team’s chosen problem statement.</p>
<p>4. Each team is to upload their submissions before the DNB Hackathon submission deadline. Only one submission per team is allowed, and any submissions after the deadline will not be considered.</p>
<p>5. Every team’s submission must be presented on a maximum of 8 PowerPoint slides (excluding the cover slide).</p>
<p>6. A panel of five judges (both internal and external) will be responsible for selecting the winners.</p> 
<p>7. The judges will first narrow down the selection to 10 finalists. These 10 finalists will be invited for a Jury Pitch Presentation session, of which the top 3 will be chosen as the winners.</p>
<p>8. The decision made by the panel of judges is final.</p>

</div>
<br>
<div>
<h4><b>Problem Statements</b></h4>
Detailed list of problems statements can be found in <a href="{{ site.baseurl }}{% link projects.md %}"><b>Problem Statements</b></a> page.
</div>
<div>
<br>
<h4><b>Q/A</b></h4>
For futher enquiries, you may refer to <a href="{{ site.baseurl }}{% link faq.md %}"><b>FAQ</b></a> page.
</div>
</div>
</section>
</div>

  

<p></p>
<p></p>
<div style="font-size: 32px; text-align: center; margin: 20px">
<p>Create your team up to a maximum of 4 members right now and</p>
<p><b>stand a chance to win amazing prizes!</b></p>


<a href="https://forms.office.com/r/cHi7NXApVS" target="_blank">
<button class="favorite styled" type="button">
    Submit Your Work
</button>
</a>
</div>

<!--[Submit your Work Here](https://digitalnasionalberhad-my.sharepoint.com/:f:/g/personal/mani_kagita_digital-nasional_com_my/ElranH5gA49Fk5Nll3-EL-cB9lGyHqo-Ln38v08fA2xwOg){:.btn target="_blank"}
-->
 


  
<div class="page-content" aria-label="Content" style="background: white; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; color: #159957;">
<section>
<div class="wrapper">
<h3><b>Prizes for Top 3 Teams</b></h3>
<u2 class="grid">

<li class="imag" markdown="1" style="text-align: center">
{% include imagedisplay.html title="First Prize" image="first.png" %}

<p><b>Samsung Galaxy A73 5G</b></p>
<p>(RRP: RM 2099)</p>
</li>

<li class="imag" markdown="1" style="text-align: center">
{% include imagedisplay.html title="Second Prize" image="second.png" %}

<p><b>Realme Pad X</b></p>
<p>(RRP: RM 1699)</p>
</li>

<li class="imag" markdown="1" style="text-align: center">
{% include imagedisplay.html title="Third Prize" image="third.png" %}

<p><b>Samsung Galaxy A23 5G</b></p>
<p>(RRP: RM 999)</p>
</li>

</u2>

</div>
</section>
</div>

