---
title: "A First Look at Cookies Having Independent Partitioned State"
date: 2025-01-01
publishDate: 2025-01-01
authors: ["Maximilian Zöllner", "Anja Feldmann", "**Ha Dao**"]
publication_types: ["1"]
abstract: "The introduction of Cookies Having Independent Partitioned State (CHIPS) marks a significant step toward balancing user privacy with essential web functionalities. 
CHIPS isolates data within specific contexts, preventing cross-site tracking while maintaining the functionality of websites. 
However, the adoption of CHIPS in real-world web usage remains largely unexplored.
In this paper, we investigate the state of CHIPS deployment, providing an overview of how CHIPS has been integrated into web ecosystems since its introduction.  
Leveraging the HTTP Archive dataset, we first find that the adoption of partitioned cookies remains slow, with most domains still relying on non-partitioned cookies, though a slight increase in both types is observed starting in early 2024, coinciding with Google's phase-out of third-party cookies for 1% of users.
This sudden onset of the third-party cookie phase-out has resulted in a haphazard way of adoption for some domains, which caused them to overlook important configuration requirements, resulting in improper settings due to limited awareness of the specific guidelines such as SameSite=None and Secure.
In addition, we observe a positive signal for privacy as third-party trackers begin adopting partitioned cookies, with a noticeable increase starting in early 2024. 
However, as of September 2024, only a small number of trackers have fully transitioned to using partitioned cookies (up to 0.5% of tracking domains), while some continue to rely on both partitioned and non-partitioned cookies (up to 3.1% of tracking domains), highlighting that the shift is still in its early stages, especially for tracking domains. Finally, we observe stark asymmetry among the early adopter tracking domains: some have already added some partitioned cookies to all sites with a presence, while others, notably Google's doubleclick.com has only deployed partitioned cookies to around 5% of pages where it is present."
featured: true
publication: "Proceedings of the PAM"
links:
  - icon_pack: fas
    icon: scroll
    name: PDF
    url: 'files/papers/ZFD_PAM2025.pdf'
---