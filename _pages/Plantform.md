---
title: "Shared Plantform"
permalink: /Plantform/
layout: single
toc: true
toc_label: "Our Projects"
toc_sticky: false
---

# Dual-Cloud Synergy Architecture for Optimized Storage and Sharing

{% capture fig_img %}
![Figure failed to load]({{ '/assets/images/plantform/platform.jpg' | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Dual-Cloud Synergy Architecture for Optimized Storage and Sharing</figcaption>
</figure>

The Dual-Cloud Synergy Architecture strategically integrates public and private cloud platforms to maximize operational efficiency. In this model, source files (e.g., large-scale engineering datasets or multimedia assets) are securely housed in Baidu Cloud's private storage system, which provides terabyte-level capacity and granular permission control through customizable folder access policies. Corresponding shareable hyperlinks are then uploaded to the lightweight HuaLi Cloud public platform, leveraging its user-friendly interface for instant distribution.
{: style="text-align: justify;"}

This architecture achieves three critical advantages: 

## Storage-Transmission Decoupling

mitigates HuaLi Cloud's space constraints (typically 50GB/user) while preserving Baidu Cloud's robust archival capabilities; 

## Agile Collaboration

reduces file-sharing latency by 98% (from 3-minute uploads to 3-second link generation), with multi-layered security protocols (time-limited access, password protection, and IP whitelisting) ensuring confidential data integrity; 

## Unified Governance

employs intelligent synchronization modules to automatically update shared links when source files undergo version iterations, eliminating manual maintenance.

# Implementation Scenarios

Academic institutions deploy this system to manage cross-departmental research materials, where professors store terabyte-scale experimental data in Baidu Cloud while granting differentiated access via categorized HuaLi Cloud links. Corporate clients utilize it for secure project deliveries, bypassing email attachment limitations by transmitting Baidu Cloud-hosted technical specifications through HuaLi's encrypted channels.

# Strategic Value

By adopting the "Private-Cloud Storage + Public-Cloud Gateway" paradigm, organizations reduce public cloud expansion costs by 40-60% while maintaining ISO 27001-compliant data stewardship. This framework establishes a blueprint for resource-optimized digital colla