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
#document-ready:
#  - getRate();
# minYear: 2007
# maxYear: 2019
---

## Meeting Minutes Archive

<br>
{% comment -%}Get year range of files{% endcomment -%}
{% include meeting-minutes/get-file-list theCollection='meeting_minutes' -%}
{% assign low = filelist.last.name | slice: 0, 4 -%}
{% assign high = filelist.first.name | slice: 0, 4 -%}
#### This is the meeting minutes archive for the FRTIB monthly board meetings and includes files from {{low}} to {{high}}.

The most recent meeting minutes are available on the FRTIB public website [here](https://www.frtib.gov/meeting-minutes/).

Below are ZIP files containing the main meeting minutes file for each FRTIB advisory board meeting.  The main file for each meeting does contain URL links embedded in the PDF for referenced attachments but they may not work in the years that follow a particular meeting so they are included in the ZIP download.  Any embedded link that works would be to a duplicate copy of the included files.

{% include meeting-minutes/full-list maxYear=page.maxYear minYear=page.minYear -%}

<!-- CONTENT END -->
