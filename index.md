---
layout: home
title: 🏠 Home
nav_exclude: false
nav_order: 1
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<!-- for the old icon: >
 <!-- <img src='favicon.ico' style='vertical-align: text-top' width=37> -->

{{ site.staffersnobio }}

<!-- [Jump to the current week](#week-9-code-sklearn-code-pipelines-generalization-and-cross-validation){: .btn } -->

{: .note }
**This is the website of a previous offering of DSC 80. To see the most recent offering, go to [dsc80.com](https://dsc80.com), and to see other DSC course websites, go to [dsc-courses.github.io](https://dsc-courses.github.io).**

<!-- {: .note }
**Some office hours on Wednesday 3/8, Thursday 3/9, and Tuesday 3/21 are being held in the SDSC Auditorium instead of the 2nd floor – look closely at the [calendar](calendar) for details.** Treat these office hours as study sessions – come to them to work on projects or study for the final exam! -->

{% for module in site.modules %}
{{ module }}
{% endfor %}

<!-- <center>
<iframe src="10-80-enrollment.html" scrolling="no" style="border:none;" seamless="seamless" height="480" width="100%">
</center> -->