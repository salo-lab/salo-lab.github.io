---
---

# Our mission

To unravel how lipid flux shapes cellular architecture in health and disease. We do this via advanced cell and in-cell structural biology at nanoscale resolution.

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
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));  /* always 3 per row on desktop */
    gap: 2rem;
    align-items: center;
    justify-items: center;
    margin-top: 1rem;
  }

  .funding-logo {
    height: 90px;                 /* taller box solves clipping */
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;             /* ensures nothing spills out visually */
  }

  .funding-logo img {
    max-width: 150px;             /* controls wide logos like KI & UH */
    width: 100%;                  
    height: auto;                 /* let height shrink to avoid overflow */
    object-fit: contain;
  }

  @media (max-width: 600px) {
    .funding-logos {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
    .funding-logo {
      height: 70px;
    }
    .funding-logo img {
      max-width: 140px;
    }
  }
</style>


<div class="funding-logos">
  <div class="funding-logo"><img src="logos/SSMF2.svg" alt="SSMF"></div>
  <div class="funding-logo"><img src="logos/VR.png" alt="Swedish Research Council (VR)"></div>
  <div class="funding-logo"><img src="logos/AOF-01.png" alt="Research Council of Finland"></div>
  <div class="funding-logo"><img src="logos/KI.svg" alt="Karolinska Institutet"></div>
  <div class="funding-logo"><img src="logos/UH3-01.png" alt="University of Helsinki"></div>
  <div class="funding-logo"><img src="logos/HILIFE.jpeg" alt="HiLIFE"></div>
</div>
