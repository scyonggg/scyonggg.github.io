---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am an AI research engineer with a passion for leveraging artificial intelligence to make the world a better place. My research interests revolve around the transformer architecture, dense prediction tasks (such as segmentation, depth estimation, and frame interpolation), and model acceleration techniques. I'm dedicated to exploring new ways to use these AI methods to solve real-world challenges. If you're interested in this field or want to know more about my research, please feel free to get in touch. I welcome opportunities for talking about AI and share ideas with others.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.11*: &nbsp;🎉🎉 ZIM has been released.
- *2023.07*: &nbsp;🎉🎉 EGformer has been accepted at ICCV 2023.
- *2022.06*: &nbsp;🎉🎉 Presented a real-time frame interpolation demonstration at AICAS 2022.

# 📝 Publications 

* ## ZIM: Zero-Shot Image Matting for Anything <br>
    Beomyoung Kim, **Chanyong Shin**, Joonhyun Jeong, Hyungsik Jung, Se-Yun Lee, Sewhan Chun, Dong-Hyun Hwang, Joonsang Yu <br>
    arXiv preprint. <br>
    [[Project page]](https://naver-ai.github.io/ZIM) [[Paper]](https://arxiv.org/pdf/2411.00626) [[Hugging Face]](https://huggingface.co/spaces/naver-iv/ZIM_Zero-Shot-Image-Matting) [[Code]](https://github.com/naver-ai/ZIM)

* ## Centralized Position Embeddings for Vision Transformers <br>
    **Chanyong Shin**, Ilwi Yun, Hyunku Lee, Chae Eun Rhee <br>
    Under review.

* ## EGformer: Equirectangular Geometry-biased Transformer for 360 Depth Estimation
    Ilwi Yun, **Chanyong Shin**, Hyunku Lee, Hyuk-Jae Lee, Chae Eun Rhee <br>
    IEEE/CVF International Conference on Computer Vision (ICCV), 2023 <br>
    [[Paper]](https://arxiv.org/abs/2304.07803) [[Code]](https://github.com/yuniw18/EGformer)

* ## Redundancy-aware Patch Embeddings for Depth Estimation of 360-degree Images in Vision Transformer <br>
    **Chanyong Shin**, Chae Eun Rhee <br>
    IEEE International Conference on Electronics, Information, and Communication (ICEIC), 2023 <br>


# 🖥️ Academic Demonstrations

* ## Live Demo: Memory-Efficient Hardware Design for a Real-Time Convolutional Encoder-Decoder Network
    Min-Wu Jeong, **Chanyong Shin**, Chae Eun Rhee <br>
    IEEE International Conference on Artificial Intelligence Circuits and Systems (AICAS), 2022 <br>

# 📖 Educations
- *2022.02 - 2024.02*, M.S. in Electrical and Computer Engineering, Inha University.
- *2016.02 - 2022.02*, B.S. in Electronics Engineering, Inha University.

# 🏢 Work Experiences
- *2024.02 - 2024.08*, Research intern in NAVER Cloud
- *2022.01 - 2022.02*, Research intern in ETRI
