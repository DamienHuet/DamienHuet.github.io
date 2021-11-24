* **{{job.title}}**, {{job.start_date | date: "%b %Y"}} -- {% if job.end_date %} {{job.end_date | date: "%b %Y"}} {% else %} present {% endif %}  
*{{job.institution}}*, {{job.location}}  
{% if job.description %}{{job.description}}{% endif %}
