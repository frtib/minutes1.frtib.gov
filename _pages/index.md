---
layout: page2
title: Meeting Minutes
styles:
# sidenav:
scripts:
#  - /assets/js/jquery.min.js
permalink: /
return_to_top: true
last_update: April 27, 2022
redirect_from:
  - /MeetingMinutes.html
  - /MeetingMinutes/
#document-ready:
#  - getRate();
---

## Meeting Minutes Archive

This is the meeting minutes archive for the FRTIB monthly board meetings. 

Below are ZIP files containing the main meeting minutes file for each FRTIB advisory board meeting.  The main file for each meeting does contain URL links embedded in the PDF for referenced attachments but they may not work in the years that follow a particular meeting so they are included in the ZIP download.  Any embedded link that works would be to a duplicate copy of the included files.

{% comment -%}
<br>
{% capture body -%}
Board meetings, which can be observed by the public, are generally held the 4<sup>th</sup> Tuesday of each month (except where noted on the current meeting calendar).
{% endcapture -%}
{% capture foot_text -%}
{% include file-list coll="pdf" folder="/board-meetings/2022_Board_Meeting_Calendar_schedule.pdf" reverse=true format='title' dobutton=true count=1 button_style="on-card thin" -%}
{% endcapture -%}
{% include desc-box  card_body=body card_foot=foot_text
      card_img="hero/meetingminutes_headerL.png" altText="Record of FRTIB meeting minutes" -%}
{% endcomment -%}

{% include meeting-minutes/full-list  -%}

<!-- CONTENT END -->
