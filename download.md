---
layout: downloads
permalink: download.html
title: "Download MediaConch"
---

# Downloads

## 16.02 Release Notes

### GUI

New page for the results (analyze and update in background, delete/add jobs during the processing of the queue)  
GUI usage is saved and restored when it is restarted  
Dynamic selection of the policy and the display format in the policy viewer  
Dynamic selection of the display format in the implementation viewer  
CAVPP access and preservation policy sets  
Update of implementation checker tests, including some FFV1 checks  
Expanded REST API of the server  

### Online

New page for the results (analyze and update in background, delete/add jobs during the processing of the queue)  
Update of implementation checker tests, including some FFV1 checks  

### CLI

Update of implementation checker tests, including some FFV1 checks  

### Server

Expanded REST API of the server  


### Historical Release Notes

{% for post in site.releasenotes reversed %}
  [{{ post.date }}]({{ post.url | remove_first:'/'}})
{% endfor %}

### Snapshots

You can test ongoing developments for MediaConch by downloading our [daily builds](/MediaConch/downloads/snapshots.html).
