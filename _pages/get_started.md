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
conda install -c milagraph graphvite cudatoolkit=$(nvcc -V | grep -Po "(?<=V)\d+\.\d+")
```

By default, this will install all the dependencies.
If you only need embedding training without evaluation, you can use the following alternative.

```bash
conda install -c milagraph graphvite-mini cudatoolkit=$(nvcc -V | grep -Po "(?<=V)\d+\.\d+")
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

Once installed, we can run the following quick-start example of the node embedding application.

```bash
graphvite baseline quick start
```

The example will automatically download a social network dataset called BlogCatalog, where nodes
correspond to blog users. For each node, we learn an embedding vector that preserves its
neighborhood structure. The learned embeddings are evaluated on link prediction and node
classification tasks.

Typically, the example takes no more than 1 minute. We will obtain some output like

```bash
Batch id: 6000
loss = 0.371041

------------- link prediction --------------
AUC: 0.899933

----------- node classification ------------
macro-F1@20%: 0.242114
micro-F1@20%: 0.391342
```

Another interesting example is a synthetic math dataset of arithmetic operations. Check
out this knowledge graph example with

```bash
graphvite baseline math
```