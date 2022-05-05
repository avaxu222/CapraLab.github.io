---
title: Capra Lab philosophy
layout: default
group: compact
---
<<<<<<< HEAD
# Capra Lab Philosophy
=======

# Lab Manual
>>>>>>> e34326c5e7234446c068dc0d9ce6f4260eb3632f

<div class="accordion" id="accordionCompact">
{% for item in site.philosophy %}
<!-- Item Block -->
<div class="card">
<div class="card-header" id="heading{{item.id}}">
<h2 class="mb-0" type="button" data-toggle="collapse" data-target="#{{item.id}}" aria-expanded="true" aria-controls="{{item.id}}">
{{item.title}}
</h2>
</div>

<div id="{{item.id}}" class="collapse {% if item.show %}show{% endif %}" aria-labelledby="heading{{item.id}}">
<div class="card-body">
{{item.body}}
</div>
</div>
</div>
<!-- End  block -->
{% endfor %}
</div>
