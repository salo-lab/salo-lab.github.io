---
---

# Our mission

To unravel how lipid flux shapes cellular architecture in health and disease. We do this via advanced cell and in-cell structural biology at nanoscale resolution...

{% include section.html %}

## Highlights

{% capture text %}
We study how organelles form, remodel, and coordinate metabolic decisions, using cryo-CLEM, cryo-ET, and live-cell imaging approaches.

{%
  include button.html
  link="research"
  text="Explore our research"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{%
  include feature.html
  image="images/GEMs.png" class="circle-crop"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
Our work spans in-cell structural biology, membrane architecture, and nanoscale regulation of lipid flux in health and disease.

{%
  include button.html
  link="publications"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{%
  include feature.html
  image="images/ER.png" class="circle-crop"
  link="publications"
  title="Publications"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}
The Salo Lab launches in 2026 at Karolinska Institutet and the University of Helsinki. We are currently recruiting—come build the lab with us.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{%
  include feature.html
  image="images/combined-01.png" class="circle-crop"
  link="team"
  title="Our Team"
  text=text
%}

{% include section.html %}

## Latest from the blog

{%
  include list.html
  data="posts"
  component="post-excerpt"
  limit=2
%}
We gratefully acknowledge all past and present funding agencies and institutional partners who support our research and scientific environment.

<style>
  .funding-logos {
    display: flex;
    flex-wrap: wrap;
    gap: 1.5rem;
    align-items: center;
    justify-content: flex-start;
    margin-top: 0.75rem;
  }

  .funding-logos img {
    height: 90px;        /* all logos same visual height */
    object-fit: contain; /* good for transparent PNG/SVG */
  }
</style>

<div class="funding-logos">
  <!-- Replace these src paths with your actual logo files in /images/logos/ -->
  <!-- Just copy-paste more <img> lines to add more funders. -->
  <img src="logos/ssfm.png" alt="SSMF">
  <img src="logos/VR.png" alt="Swedish Research Council (VR)">
  <img src="logos/AOF-01.png" alt="Research Council of Finland">
  <img src="logos/KI.svg" alt="Karolinska Institutet">
  <img src="logos/UH.png" alt="University of Helsinki">
  <img src="logos/HILIFE.jpeg" alt="Hilife">
</div>
