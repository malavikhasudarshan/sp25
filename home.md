---
layout: page
title: Welcome!
nav_exclude: true
permalink: /
seo:
  type: Course
  name: Berkeley Class Site
currWeekNumber: 1
---


# Data 100: Principles and Techniques of Data Science

{: .mb-2 }
UC Berkeley, Spring 2025
{: .mb-0 .fs-6 .text-grey-dk-000 }

<!-- [Ed](https://edstem.org/us/courses/62812){:target="\_blank" .btn .btn-ed .mr-1 } -->
[Datahub](http://data100.datahub.berkeley.edu/){:target="\_blank" .btn .btn-datahub .mr-1 }
<!-- [Gradescope](https://www.gradescope.com/courses/827978){:target="\_blank" .btn .btn-gradescope .mr-1 } -->
<!-- [Lectures Playlist](https://www.youtube.com/playlist?list=PLQCcNQgUcDfqlx2UJTlv22jsPAu0Yg_kg){:target="\_blank" .btn .btn-youtube .mr-1} -->
<!-- [Additional Accommodations](https://forms.gle/HYbsLwhtSvmsCefX9){:target="\_blank" .btn .btn-blue .mr-1 } -->
[Office Hours Queue](https://oh.ds100.org/){:target="\_blank" .btn .btn-oh .mr-1}

<div>
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  <div class="role">
    {% for staffer in instructors %}
    {{ staffer }}
    {% endfor %}
  </div>
</div>

{: .highlight }

> Welcome to [Week {{page.currWeekNumber}}](#week-{{page.currWeekNumber}}) of Data 100!
> 
<!-- > Lectures will be webcast at: [https://berkeley.zoom.us/j/91349586134](https://berkeley.zoom.us/j/91349586134){:target="\_blank"}. -->


<!-- {: .note }
> <span style="color:red">**Enrollment: As of Jan. 23, 2024, Data C100/200 is closed and no further enrollment is possible.**</span>  -->


<a name="schedule"></a>

## Schedule

{% for module in site.modules %}
{{ module }}
{% endfor %}