---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Computer Science, DGIST, Feb 2026 – Feb 2028 (expected)
  * Real-Time Computing Lab (RTCL)
* B.S. in Electrical Engineering and Computer Science, DGIST, Feb 2020 – Feb 2026
  * GPA: 3.82 / 4.3

Research experience
======
* Feb 2026 – present: Graduate Research Assistant
  * Real-Time Computing Lab (RTCL), DGIST
  * Real-time systems, with a focus on DNN inference offloading between edge devices and servers
  * Image-adaptive JPEG compression — per-image quality factor and quantization table optimization — for offloaded inference under variable network bandwidth

Skills
======
* Programming languages: C/C++, Python
* Machine learning: PyTorch
* Computer vision: OpenCV
* Tools and infrastructure: Docker

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
