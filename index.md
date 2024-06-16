---
layout: page
title: Home / Schedule
nav_order: 1
description: A week-to-week description of the content covered in the course.
course:
  edstem: https://edstem.org/us/courses/59974/
currWeekNumber: 1
---

# Data 100: Principles and Techniques of Data Science

{: .mb-2 }
UC Berkeley, Summer 2024
{: .mb-0 .fs-6 .text-grey-dk-000 }

[Ed](https://edstem.org/us/courses/59974/){:target="\_blank" .btn .btn-ed .mr-1 }
[Datahub](http://data100.datahub.berkeley.edu/){:target="\_blank" .btn .btn-datahub .mr-1 }
[Gradescope](https://www.gradescope.com/courses/788548){:target="\_blank" .btn .btn-gradescope .mr-1 }
[Lectures Playlist](https://www.youtube.com/playlist?list=PLQCcNQgUcDfrWFdpg8ww0zx6Q4lKsQkjc&playnext=1&index=1){:target="\_blank" .btn .btn-youtube .mr-1}
[Emergency Accommodations](https://forms.gle/HFdpmHzBu1e7zcF2A){:target="\_blank" .btn .btn-blue .mr-1 }
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
<!--
> Welcome to [Week {{page.currWeekNumber}}](#week-{{page.currWeekNumber}}) of Data 100!
-->

<!-- {: .note }
> <span style="color:red">**Enrollment: As of Jan. 23, 2024, Data C100/200 is closed and no further enrollment is possible.**</span>  -->


<a name="schedule"></a>

## Schedule

{% for module in site.modules %}
{{ module }}
{% endfor %}
