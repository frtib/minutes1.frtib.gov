---
layout: page2
title: Meeting Minutes
styles:
# sidenav:
scripts:
#  - /assets/js/jquery.min.js
permalink: /
return_to_top: true
# last_update: April 27, 2022
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

Below are ZIP files containing the main meeting minutes file and attachments for each FRTIB advisory board meeting.<br>
The main file contains URL links to attachments that no longer work; instead that attachments are included in the ZIP file.<br>

If you have any questions or technical issues accessing the files please email the [FRTIB Webmaster](mailto:webmaster@frtib.gov).

{% include meeting-minutes/full-list maxYear=page.maxYear minYear=page.minYear -%}

<!-- CONTENT END -->
