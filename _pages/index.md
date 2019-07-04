---
layout: splash
class: landing
permalink: /
header:
  #overlay_color: "#018dc6"
  overlay_filter: rgba(28, 150, 207, 0.9)
  overlay_image: "/assets/images/overlay.jpg"
  actions:
    - label: "Get Started"
      url: "/get_started"
excerpt: >
  A general and high-performance graph embedding system that supports various
  applications, including node embeddings, knowledge graph embeddings, and graph
  & high-dimensional data visualization.<br>
  Designed for CPU-GPU hybrid architecture.
# Graph embedding engine<br>
# Dedicated to high speed and large scale
features:
  - title: "Fast Training"
    excerpt: >
      Training on graphs has never been so fast. Taking no more than 15 minutes on
      standard datasets, it enables rapid iteration of algorithms, and brings
      opportunities to new ideas.
  - title: "Billion Scale"
    excerpt: >
      Designed to be scalable, it is capable of dealing with large-scale graphs,
      even with limited GPU memory. With only 4 GPUs, you can get embeddings of 
      a billion-scale graph in 20 hours.
  - title: "Application Pipelines"
    excerpt: >
      Complete pipelines of node embedding, knowledge graph embedding, and graph
      & high-dimensional visualization are supported. It is a ready playground for
      models and evaluation tasks.
benchmark:
  - title: "Models and Benchmarks"
    excerpt: >
      A large collection of models and benchmarks are provided to facilitate fast
      reproducibility. Choose your favourite model and plug it into your research or 
      development.<br><br>
      **Supported models:** DeepWalk, LINE, TransE, DistMult, ComplEx, RotatE, LargeVis
    # Everything is here and no further effort is needed.
    image_path: "/assets/images/benchmark.png"
    url: "/docs/benchmark"
    btn_class: "btn--primary"
    btn_label: "Learn more"
interface:
  - title: "Flexible Interface"
    image_path: "/assets/images/interface.png"
    excerpt: >
      Tailored to different needs, flexible interface brings you great user experience,
      while minimizes the issues you do not care. It is always easy and efficient to
      integrate GraphVite into your environment, no matter you are using Python or C/C++.
    url: "/docs/user/command_line"
    btn_class: "btn--primary"
    btn_label: "Learn more"
---

{% include feature_row id="features" %}

| [Node Embedding][1]    | [Knowledge Graph Embedding][2]    | [Graph & High-dimensional Visualization][3]    |
|------------------------|-----------------------------------|------------------------------------------------|
| [![Node Embedding]][1] | [![Knowledge Graph Embedding]][2] | [![Graph & High-dimensional Visualization]][3] |
{: .page}

[1]: /docs/overview#node-embedding
[2]: /docs/overview#knowledge-graph-embedding
[3]: /docs/overview#graph-high-dimensional-visualization
[Node Embedding]: {{ site.baseurl }}/assets/images/graph.png
[Knowledge Graph Embedding]: {{ site.baseurl }}/assets/images/knowledge_graph.png
[Graph & High-dimensional Visualization]: {{ site.baseurl }}/assets/images/visualization.png

{% include feature_row id="benchmark" type="left" %}
{% include feature_row id="interface" type="right" %}