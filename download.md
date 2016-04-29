---
layout: downloads
permalink: download.html
title: "Download MediaConch"
---

# Downloads

## 16.04 Release Notes

### GUI, Online, CLI, Server

FFV1: display of the trace of the slice header  
Display information correctly even if the file disappeared (renamed / not accessible)  

### GUI

Check a directory recursively  
New checker page based on MediaConchOnline  
New settings : default policy, default display, default path for file open  
Remember the last policy used, the last display used, the last path used  

### CLI

Check a directory recursively  
Accepts MediaInfo options  

### Online

Display status/error messages  
Minor UI enhancements  

### Historical Release Notes

{% for post in site.releasenotes reversed %}
  [{{ post.date }}]({{ post.url | remove_first:'/'}})
{% endfor %}

### Snapshots

You can test ongoing developments for MediaConch by downloading our [daily builds](/MediaConch/downloads/snapshots.html).
