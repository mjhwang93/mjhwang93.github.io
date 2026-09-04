---
permalink: /
# title: "About Me"
# excerpt: "About me"
author_profile: true
redirect_from: 
  - /home/
  - /home.html
---

{% include base_path %}

# Min-Jae Hwang
I am a research scientist at [Meta AI](https://ai.facebook.com/).
My area of expertise lies in high-quality and expressive speech generation, which has applications in [Text-to-Speech (TTS)](https://www.ncloud.com/product/aiService/css) and [Speech-to-Speech Translation (S2ST)](https://ai.facebook.com/blog/teaching-ai-to-translate-100s-of-spoken-and-written-languages-in-real-time/).
In this field, I've contributed to various projects like [Clova Dubbing](https://clovadubbing.naver.com/) and [Seamless Communication](https://ai.meta.com/research/seamless-communication/).

Prior to Meta AI, I was a research scientist at [Naver Corporation](https://www.navercorp.com/en).
I received my Ph.D. degree in department of Electrical and Electronics at [Yonsei University](https://www.yonsei.ac.kr/en_sc/index.jsp).
During my Ph.D. course, I was fortunate to have research experiences as an intern at [Microsoft Research Asia](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/) and [Naver Corporation](https://www.navercorp.com/en).

I'm open to learn new knowledge and enjoy applying them to solve our society's real-world problems.
If you are interested in me, feel free to [contact me]({{ base_path }}/contacts.html).

<small><i class="fa fa-download" aria-hidden="true"></i> Download my [CV]({{base_path}}/files/cv/cv_latest.pdf)</small>

**<span style="color:green">NEWS!</span>**  
:heavy_check_mark: 9/2026 : Our new paper<sup>[1](https://arxiv.org/abs/2609.03992)</sup> on Alignment-Free Text-Audiobox for voice dubbing and full-duplex dialogue synthesis is now available on [arXiv](https://arxiv.org/abs/2609.03992)!
<br>
:heavy_check_mark: 1/2025 : One paper<sup>[1](https://www.nature.com/articles/s41586-024-08359-z)</sup> has been accepted to [Nature Magazine](https://www.nature.com/).
<br>
:heavy_check_mark: 5/2024 : One paper<sup>[1](https://arxiv.org/abs/2406.02733)</sup> has been accepted to [Findings of ACL 2024](https://2024.aclweb.org/).
<br>
:heavy_check_mark: 5/2024 : I joined [Meta AI, Seattle, USA](https://ai.facebook.com/) as Research Scientist!
<br>
:heavy_check_mark: 2/2024 : I gave guest lectures at [BishBash 2024 event]({{base_path}}/files/slides/2402_bish_bash.pdf) for the topic of expressive S2ST.
<br>
:heavy_check_mark: 11/2023 : We launched [Seamless](https://ai.meta.com/research/seamless-communication/), a new family of AI translation models that preserve expression and deliver near-real time streaming translations.
<br>
:heavy_check_mark: 11/2023 : SeamlessM4T was recognized by [TIME magazine](https://time.com/collection/best-inventions-2023/6326994/meta-seamlessm4t/) among the best inventions of 2023!
<!-- <br> -->
<!-- :heavy_check_mark: 8/2023 : We launched [SeamlessM4T](https://ai.meta.com/blog/seamless-m4t/), a foundational multilingual and multitask model that seamlessly translates and transcribes across speech and text. -->
<!-- <br> -->
<!-- :heavy_check_mark: 9/2022 : Our paper<sup>[1](https://nips.cc/Conferences/2022/Schedule?showEvent=54658)</sup> has been accepted to [NeurIPS 2022](https://nips.cc/). -->
<!-- <br> -->
<!-- :heavy_check_mark: 6/2022 : I\'ll join [Meta AI, Seattle, USA](https://ai.facebook.com/) as a Postdoctoral Researcher for this October! -->
<!-- <br> -->
<!-- :heavy_check_mark: 5/2022 : Our two papers<sup>[1](https://arxiv.org/abs/2206.14984), [2](https://arxiv.org/abs/2206.15067)</sup> have been accepted to [Interspeech 2022](https://interspeech2022.org/). -->
<!-- <br> -->
<!-- :heavy_check_mark: 5/2022 : I gave guest lectures at [KAIST](https://www.kaist.ac.kr/en/) and [SNU](https://en.snu.ac.kr/) (Topic : Voice Synthesis and Applications). -->
<!-- <br> -->
<!-- :heavy_check_mark: 1/2022 : Our two papers<sup>[1](https://ieeexplore.ieee.org/abstract/document/9748515), [2](https://ieeexplore.ieee.org/abstract/document/9748530/)</sup> have been aceepted to [ICEIC 2022](https://iceic.org/2022/). -->
{: .notice--primary}

<!-- {: .notice} -->

***
# Research Interests
- **Speech-to-speech translation (S2ST)**
  - <small>Expressive S2ST system</small>
- **Text-to-speech (TTS) synthesis**
  - <small>High-quality and real-time waveform generation method</small>
  - <small>Expressive and emotional TTS system</small>

***
# Recent Publications
{% for group in site.data.publications %}{% for pub in group.papers %}{% if pub.highlight %}- [{{ pub.title }}]({{ pub.url }})  
  <small>{{ pub.authors | replace: '%ME%', '__Min-Jae Hwang__' }}</small>{% if pub.venue %}  
  <small>{{ pub.status | default: 'Published in' }}{% if pub.venue_prefix %} {{ pub.venue_prefix }}{% endif %} [{{ pub.venue }}]({{ pub.venue_url }}){% if pub.venue_note %} {{ pub.venue_note }}{% endif %}{% if pub.extra %} {{ pub.extra }}{% endif %}</small>{% endif %}

{% endif %}{% endfor %}{% endfor %}
<!-- ***
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fmjhwang93.github.io&count_bg=%2364C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com) -->
