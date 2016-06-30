---
layout: downloads
permalink: download.html
title: "Download MediaConch"
---

# Downloads

## 16.05 Release Notes

### GUI, Online, CLI, Server

Revisited HTML report, more compact and with a summary per test  
Matroska files with CodecPrivate element before CodecID element where not always correctly parsed  
Performance improvement  

### GUI

Create a policy from MediaInfo report  
Revisited Display window  
Minor UI fixes on the main window  

### Online

Create a policy from MediaInfo report  

### Historical Release Notes

{% for post in site.releasenotes reversed %}
  [{{ post.date }}]({{ post.url | remove_first:'/'}})
{% endfor %}

### Snapshots

You can test ongoing developments for MediaConch by downloading our [daily builds](/MediaConch/downloads/snapshots.html).
