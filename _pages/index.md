---
layout: splash
class: landing
permalink: /
header:
  #overlay_color: "#018dc6"
  overlay_filter: rgba(28, 150, 207, 0.9)
  overlay_image: /assets/images/overlay.jpg
  actions:
    - label: "Get Started"
      url: docs/quick-start-guide/
excerpt: >
  Graph embedding engine<br>
  Dedicated to high speed and large scale
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
      / high-dimensional visualization are supported. It is a ready playground for
      models and evaluation tasks.
benchmark:
  - title: "Models and Benchmarks"
    excerpt: >
      A large collection of models and benchmarks are provided to facilitate fast
      reproducibility. Choose your favourite model and plug it into your research or 
      development. Everything is there and no further effort is needed.
    image_path: /assets/images/benchmark.png
    url: "benchmarks"
    btn_class: "btn--primary"
    btn_label: "Learn more"
interface:
  - title: "Flexible Interface"
    image_path: /assets/images/interface.png
    excerpt: >
      Tailored to different needs, flexible interface brings you great user experience,
      while minimizes the issues you do not care. It is always easy and efficient to
      integrate GraphVite into your environment, no matter you are using Python or C/C++.
    url: "interface"
    btn_class: "btn--primary"
    btn_label: "Learn more"
---

{% include feature_row id="features" %}
{% include feature_row id="benchmark" type="left" %}
{% include feature_row id="interface" type="right" %}

Application Overview
====================
{: .text-center}
<table style="padding-left:18%; padding-right:18%; text-align:center">
    <tr>
        <td><b>Node Embedding</b></td>
        <td><b>Knowledge Graph Embedding</b></td>
        <td><b>Graph / High-dimensional Visualization</b></td>
    </tr>
    <tr>
        <td><a href="/node_embedding" title="Node Embedding">
            <img src="/assets/images/graph.png" url="node embedding" />
        </a></td>
        <td><a href="/knowledge_graph_embedding" title="Knowledge Graph Embedding">
            <img src="/assets/images/knowledge_graph.png" />
        </a></td>
        <td><a href="/visualization" title="Graph / High-dimensional Visualization">
            <img src="/assets/images/visualization.png" />
        </a></td>
    </tr>
</table>