---
layout: template
---
# List of Titanic passengers

Check out the names of real Titanic passengers:
{% for item in site.data.titanictest %}
1. {{item.Name}}, {{item.Age}}
{% endfor %}

[Do you like to read some short stories?] go to [home page]({{ site.homeURL }}).
