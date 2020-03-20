---
title: "Pre-trained Models"
layout: splash
classes: extend-left
permalink: /pretrained_models
header:
  overlay_filter: rgba(28, 150, 207, 0.9)
  overlay_image: "/assets/images/overlay.jpg"
map:
  layers:
    TransE:
      path: "/assets/tiles/transe"
      title: "<a href=https://deepgraphlearning.github.io/project/wikidata5m>Wikidata5m</a> | TransE Embedding"
    RotatE:
      path: "/assets/tiles/rotate"
      title: "<a href=https://deepgraphlearning.github.io/project/wikidata5m>Wikidata5m</a> | RotatE Embedding"
  legend:
    colors: ["#1f77b4", "#ff7f0e", "#2ca02c", "#d62728", "#9467bd", "#8c564b", "#e377c2", "#7f7f7f", "#bcbd22", "#17becf", "#d3d3d3"]
    labels: ["human", "taxon", "film", "human settlement", "album", "village", "enterprise", "book", "single (music release)", "railway station", "else"]
  init:
    layer: RotatE
    scale: 0.7
  zoom: [0, 4]
---

To facilitate the usage of knowledge graph representations in semantic tasks, we provide a bunch of pre-trained embeddings for some common datasets.

Wikidata5m
----------
[Wikidata5m] is a large-scale knowledge graph dataset constructed from [Wikidata] and [Wikipedia]. It contains about 5 million entities in the general domain, such as celebrities, events, concepts and things.

[Download pre-trained models][Download]{: .btn .btn--primary style="margin-right: 50px"}
[Performance benchmark results][Benchmark]{: .btn .btn--primary}

[Wikidata5m]: https://deepgraphlearning.github.io/project/wikidata5m
[Wikidata]: https://www.wikidata.org
[Wikipedia]: https://www.wikipedia.org
[Download]: /docs/latest/pretrained_model
[Benchmark]: /docs/latest/benchmark#knowledge-graph-benchmark

Explore
-------

Here are pre-trained entity embeddings of [TransE] and [RotatE] visualized by GraphVite. You can zoom in the visualization to see more details.

[TransE]: http://papers.nips.cc/paper/5071-translating-embeddings-for-modeling-multi-relational-data.pdf
[RotatE]: https://arxiv.org/pdf/1902.10197.pdf

{% include interactive_map %}