---
layout: template
---
# List of Titanic passengers

Check out the names of real Titanic passengers:
{% for item in site.data.titanictest %}
1. {{item.Name}}, {{item.Age}}
{% endfor %}

**What do you want to do next?**
- [I like to read some stories]({{ site.homeURL }})
