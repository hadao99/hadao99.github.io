---
title: "Do Cookie Banners Respect My Browsing Privacy? Measuring the Effectiveness of Cookie Rejection for Limiting Behavioral Advertising"
date: 2024-11-08
publishDate: 2024-11-08
authors: ["Mateo Ormeno", "Ha Dao", "Valeria Herskovic", "Kensuke Fukuda"]
publication_types: ["2"]
abstract: "Online behavioral advertising (OBA) is a method within digital advertising that exploits web
users’ interests to tailor ads. Its use has raised privacy concerns among researchers, regulators, and the
media, emphasizing the need for a reliable mechanism to measure its prevalence. However, there is a lack
of systematic research on how user consent choices affect OBA presence, and no open-source frameworks
exist for large-scale automated OBA measurement. To address this, we design and implement OpenOBA,
a new framework for automated OBA discovery on the web. OpenOBA is a general, modular, and scalable
framework to support essentially any OBA measurement. With it, we conduct a study to measure the impact
of three user consent choices for cookies on OBA, uncovering a complex online privacy landscape. We first
confirm the presence of OBA by comparing the increased likelihood of encountering ads from a specific
topic, i.e., Style & Fashion, when browsing with an artificially induced behavior versus when browsing
without any particular behavior. Then, we find that the Accept All choice significantly raises the number
of OBA ads. For the Reject All option, on the other hand, we observe that it reduces the number of unique
third-party tracking cookie hosts (tracker domains) by around 70%, yet it still shows ads related to the user’s
interests. Notably, we also find that OBA ads are only served through Google-related domains across the
three banner interaction configurations used, despite the involvement of up to 191 different tracker domains
in the Accept All configuration. This underscores the dominant role of major players in the OBA ad market.
Finally, to foster reproducibility and further research, we open-sourced our framework and released all data
and analysis scripts."
featured: true
publication: "IEEE Access"
links:
  - icon_pack: fas
    icon: scroll
    name: PDF
    url: 'files/papers/ODHF_IEEEACCESS2024.pdf'
---