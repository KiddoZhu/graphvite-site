---
layout: splash
title: "Get Started"
permalink: /get_started.html
header:
  overlay_filter: rgba(28, 150, 207, 0.9)
  overlay_image: "/assets/images/overlay.jpg"
---

Installation
============

From Conda
----------

GraphVite can be installed through conda with only one line.

```bash
conda install -c milagraph graphvite
```

By default, this will install all the dependencies.
If you only need embedding training without evaluation, you can use the following alternative.

```bash
conda install -c milagraph graphvite-mini
```

From Source
-----------

To install GraphVite from source, you need to have `conda` installed.

```bash
git clone {{ site.graphvite.repo }}
cd graphvite
conda install -y --file conda/requirements.txt
mkdir build
cd build && cmake .. && make && cd -
cd python && python setup.py install && cd -
```
<br>

Quick Start
===========

Once installed, you can run the following quick-start example of the node embedding application.

```bash
graphvite baseline quick start
```

The example will automatically download a social network dataset called BlogCatalog, where nodes
correspond to blog users. For each node, we learn an embedding vector, and evaluate the embeddings
on multi-label node classifcation.

Typically, the example takes no more than 1 minute. You will obtain some output like

```bash
Batch id: 6000
loss = 0.371641

macro-F1@20%: 0.236794
micro-F1@20%: 0.388110
```

