---
title: "About"
layout: splash
permalink: /about.html
header:
  overlay_filter: rgba(28, 150, 207, 0.9)
  overlay_image: "/assets/images/overlay.jpg"
---

GraphVite is an open-source graph embedding system, designed for high-speed and
large-scale training. The goal of this system is to provide a general and high-performance
framework for a broad family of embedding methods, which facilitates research and
deployment of graph learning algorithms.

Through the development of GraphVite, it is always targeted to solve extremely large
graphs on CPU-GPU hybrid architectures. Tailored to the nature of graph embeddings,
GraphVite is distinguished from other libraries by fast training and linear scalability.
It is even able to work under very limited GPU memory, where other systems might fail.

With GraphVite, it is easy to reproduce cutting-edge models of many applications,
deploy them on large real-world datasets, and develop new models for graph representation
learning.

Development Team
----------------

GraphVite is developed by [MilaGraph], led by Prof. [Jian Tang].

Authors of this project are [Zhaocheng Zhu], [Shizhen Xu], [Meng Qu] and [Jian Tang].<br>
Contributors include [Kunpeng Wang] and [Zhijian Duan].

[MilaGraph]: https://github.com/DeepGraphLearning
[Zhaocheng Zhu]: https://kiddozhu.github.io
[Shizhen Xu]: https://github.com/xsz
[Meng Qu]: https://mnqu.github.io
[Jian Tang]: https://jian-tang.com
[Kunpeng Wang]: https://github.com/Kwinpeng
[Zhijian Duan]: https://github.com/zjduan

License
-------

GraphVite is released under the [Apache License 2.0].

[Apache License 2.0]: {{ site.graphvite.repo }}/blob/master/LICENSE

Contact
-------

If you have any question about the library, please open an [issue] in the GitHub repo.

You may contact the authors through [Zhaocheng Zhu][Zhaocheng Zhu's Mail], [Jian Tang][Jian Tang's Mail].

[issue]: {{ site.graphvite.repo }}/issues/new
[Zhaocheng Zhu's Mail]: mailto:zhaocheng.zhu@umontreal.ca
[Jian Tang's Mail]: mailto:jian.tang@hec.ca