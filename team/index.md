---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %} Team

We are building an
interdisciplinary team combining cell biology, cryo-electron tomography, advanced
imaging, and structural approaches to understand how lipid flux and membrane
dynamics shape organelle architecture.

If you are interested in joining the lab, please contact Veijo.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html %}
