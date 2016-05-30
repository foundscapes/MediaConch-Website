---
layout: downloads
permalink: download.html
title: "Download MediaConch"
---

# Downloads

## 16.05 Release Notes

### GUI, Online, CLI, Server

MediaConch XML format v0.2  
Improved Matroska tests  
Improved HTML display  
FFV1 parsing speed improvement  

### GUI

Option for applying a policy to all open files  
List of values for several elements in the policy editor  
Minor UI improvements/fixes  

### Online

Option for applying a policy to all open files  
User settings : default policy, default display, default verbosity  
Minor UI improvements/fixes  

### Historical Release Notes

{% for post in site.releasenotes reversed %}
  [{{ post.date }}]({{ post.url | remove_first:'/'}})
{% endfor %}

### Snapshots

You can test ongoing developments for MediaConch by downloading our [daily builds](/MediaConch/downloads/snapshots.html).
