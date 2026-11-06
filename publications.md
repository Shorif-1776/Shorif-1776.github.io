---
layout: page
title: Publications
description: >
  My work spans drinking-water contaminants, human-health risk, groundwater quality and rainfall extremes.
redirect_from:
  - /publications.html
---

## Peer-reviewed articles

<div class="pubs">
{% for pub in site.data.publications %}
<article class="pub">
  <h3 class="pub-title" tabindex="0">
    {% if pub.url %}<a href="{{ pub.url }}" class="external">{{ pub.title }}</a>{% else %}{{ pub.title }}{% endif %}
  </h3>
  <p class="pub-meta">{{ pub.authors | replace: "Md Jahim Uddin Shorif", "<strong>Md Jahim Uddin Shorif</strong>" }}<br><em>{{ pub.journal }}</em>, {{ pub.year }}</p>
  <div class="pub-flyout" role="tooltip">
    <dl>
      <dt>Authors</dt><dd>{{ pub.authors }}</dd>
      {% if pub.date %}<dt>Published</dt><dd>{{ pub.date }}</dd>{% endif %}
      <dt>Journal</dt><dd>{{ pub.journal }}{% if pub.volume %}, vol. {{ pub.volume }}{% endif %}{% if pub.pages %}, {{ pub.pages }}{% endif %}</dd>
      {% if pub.publisher %}<dt>Publisher</dt><dd>{{ pub.publisher }}</dd>{% endif %}
      {% if pub.rank %}<dt>Ranking</dt><dd>{{ pub.rank }}</dd>{% endif %}
      {% if pub.doi %}<dt>DOI</dt><dd><a href="https://doi.org/{{ pub.doi }}" class="external">{{ pub.doi }}</a></dd>{% endif %}
    </dl>
    {% if pub.abstract %}<p class="pub-abstract">{{ pub.abstract }}</p>{% endif %}
  </div>
</article>
{% endfor %}
</div>

## Submitted

### Physics-Informed Deep Learning for Flood Inundation Modeling: Architectures, Failure Modes, and the Path Toward Hybrid Digital Twins
Norma Wihdatun Nikmah, **Md Jahim Uddin Shorif**, Ahmed M. Al-Areeq, Hatim O. Sharif, Shakhawat Chowdhury  
*Submitted to Reliability Engineering & System Safety.*

## In preparation

### Electroactive Carbon Brush for Thermophilic Anaerobic Digestion – Kinetic Performance and Economic Analysis
Halima Alhimali, **Md Jahim Uddin Shorif**, Md Atiqur Rahman, Abdullah Al-Mamun, Shakhawat Chowdhury, Abdullah Al Mamun, Mohamed Shafiq Uzzaman, Jagdeep Kumar Nayak, Bashirul Haq

### A Review on Destructive Treatment and Mineralization of PFAS in Drinking Water Treatment
**Md Jahim Uddin Shorif**, Md Atiqur Rahman, Shakhawat Chowdhury

## Conference papers

### Analysis of Groundwater Quality in Dhaka Division, Bangladesh
Md Rezaul Karim, Md Atif Arham, **Md Jahim Uddin Shorif**, Ataur Rahman  
*International Conference on Water and Environmental Engineering*, pp. 162–167. Science Technology and Management Crescent Australia, 2022.

## Further reading
Looking for the full record? [Download my CV](/assets/Md-Jahim-Uddin-Shorif-CV.pdf) for research experience, education, and complete publication details.
