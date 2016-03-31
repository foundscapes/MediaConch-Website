---
layout: downloads
permalink: download.html
title: "Download MediaConch"
---

# Downloads

## 16.03 Release Notes

### GUI, Online, CLI, Server

Support of plugins (VeraPDF and DPF Manager)  
Bugfixes  

### GUI

Verbosity selection  
Improved free text editor  


### Historical Release Notes

{% for post in site.releasenotes reversed %}
  [{{ post.date }}]({{ post.url | remove_first:'/'}})
{% endfor %}

### Snapshots

You can test ongoing developments for MediaConch by downloading our [daily builds](/MediaConch/downloads/snapshots.html).
