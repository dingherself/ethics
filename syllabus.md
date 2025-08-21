---
layout: toc
title: Syllabus
navtitle: Syllabus
group: syllabus
order: 5
date: 2025-08-20
---

<h2 class="mt-0" style="position:absolute; visibility: hidden;">Course Information</h2>

<p class="mt-2"><strong>{{ site.course_number }}: {{ site.course_title_full | smartify }}</strong><br />
{{ site.institution | smartify }}, {{ site.semester | smartify }}<br />
{{ site.meeting_time }}, {{ site.classroom | smartify }}, <a href="{{ site.learning_site1 }}">CourseWorks</a><br />Discussion section required</p>

<script language="JavaScript" type="text/javascript">
      var g = "edu";
      var o = "barnard";
      var c = ".";
      var a = "dding";
      var t = " ";
      var s = "@";
      document.write("<p><strong>Instructor</strong>: <a href='{{ site.instructor_website }}' target='_blank'>{{ site.instructor | smartify }}</a> (my pronouns are <a href='https://apastyle.apa.org/blog/singular-they' target='_blank' rel='noopener noreferrer'>they/them</a> and she/her)<br /><strong>Email</strong>:" + t + "<a href='" + "mail" + "to:" + a + s + o + c + g + "'>" + a + s + o + c + g + "</a><br /><strong>Office</strong>: {{ site.office }}<br /><strong>Office hours</strong>: {{ site.office_hours }}<br />" + "</p>");
</script>
<noscript><p><strong>Instructor</strong>: <a href='{{ site.instructor_website }}' target='_blank'>{{ site.instructor | smartify }}</a> (my pronouns are <a href='https://apastyle.apa.org/blog/singular-they' target='_blank' rel='noopener noreferrer'>they/them</a> and she/her)<br /><strong>Email</strong>:[you must enable JavaScript in your web browser to view the email address]<br /><strong>Office</strong>: {{ site.office }}<br /><strong>Office hours</strong>: {{ site.office_hours }}<br /></p></noscript>

{% if site.ta_title %}

<p><strong>{{ site.ta_title }}:</strong></p>

<div class="row no-gutters gx-0 mb-0">
      <div class="col-12 col-md-6">
      <script language="JavaScript" type="text/javascript">
            var g = "edu";
            var o = "columbia";
            var c = ".";
            var i = "{{ site.ta1_netid }}";
            var t = " ";
            var s = "@";
            document.write("<p>{{ site.ta1_name | smartify }}<br /><strong>Email</strong>:" + t + "<a href='" + "mail" + "to:" + i + s + o + c + g + "'>" + i + s + o + c + g + "</a><br /><strong>Office</strong>: {{ site.ta1_office }}<br /><strong>Office hours</strong>: {{ site.ta1_office_hours }}<br />" + "</p>");
      </script>
      <noscript><p>{{ site.ta1_name | smartify }}<br /><strong>Email</strong>:[you must enable JavaScript in your web browser to view the email address]<br /><strong>Office</strong>: {{ site.ta1_office }}<br /><strong>Office hours</strong>: {{ site.ta1_office_hours }}<br /></p></noscript>
      </div>

      <div class="col-12 col-md-6">
      <script language="JavaScript" type="text/javascript">
            var g = "edu";
            var o = "columbia";
            var c = ".";
            var i = "{{ site.ta2_netid }}";
            var t = " ";
            var s = "@";
            document.write("<p>{{ site.ta2_name | smartify }}<br /><strong>Email</strong>:" + t + "<a href='" + "mail" + "to:" + i + s + o + c + g + "'>" + i + s + o + c + g + "</a><br /><strong>Office</strong>: {{ site.ta2_office }}<br /><strong>Office hours</strong>: {{ site.ta2_office_hours }}<br />" + "</p>");
      </script>
      <noscript><p>{{ site.ta2_name | smartify }}<br /><strong>Email</strong>:[you must enable JavaScript in your web browser to view the email address]<br /><strong>Office</strong>: {{ site.ta2_office }}<br /><strong>Office hours</strong>: {{ site.ta2_office_hours }}<br /></p></noscript>
      </div>
</div>

{% endif %}

## Course Overview
