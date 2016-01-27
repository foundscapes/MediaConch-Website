---
layout: downloads
permalink: download.html
title: "Download MediaConch"
---

# Downloads

## 16.01 Release Notes

### CLI, GUI and Onlinve version

More Matroska validation tests
Improved reports
Verbosity option
MediaConch server, with a REST API
MediaConch CLI and GUI can communicate with MediaConch server
Support of Qt 5.6 (QtWebKit dependancy is replaced by Qt QtWebEngine dependancy)
Matroska: CRC-32 validation
Matroska: support of padding/junk at the start of a segment
Matroska: trace is activated for all elements (but report is still based on the first element met)
Matroska: add an intermediate level in the trace for the raw stream parser
Visual Studio 2015 project files


### Historical Release Notes

{% for post in site.releasenotes reversed %}
  [{{ post.date }}]({{ post.url | remove_first:'/'}})
{% endfor %}

### Snapshots

You can test ongoing developments for MediaConch by downloading our [daily builds](/MediaConch/downloads/snapshots.html).
