---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

Some software I've written:

* [salmon], a library for asking the next "best" triplet query to crowdsourcing
  participants.
* [caption-contest-data], which aggregates human responses from [The New
  Yorker's Caption Contest][tny]. Human responses are collected with the
  [voting interface][cc-vote].
* [adadamp], an implementation of a method that adapts batch size to model
  quality. This method improves the convergence of SGD.
* [swix], the Swift Matrix Library (archived).
* [jem-press], a static site generator inspired by jem-doc with Markdown and
  Mathjax.

I also wrote some code and documentation for Dask-ML's hyper-parameter
optimization:

* [Dask-ML's page on "Hyper-parameter searches"][daskml]. What problems arise in machine
  learning's hyperparameter searches, and what tools can get around those
  problems?


Other software I've written without a dedicated documentation page:

* [drawnow], a small utility to easily create animations in Python. It's a
  almost a drop-in replacement for the `drawnow` command in MATLAB.®
* [talks], slides for talks I've given.
* [templates]. Like how I style slides/my CV/posters/etc? This might be of
  interest.

[tny]:https://www.newyorker.com/cartoons/contest
[caption-contest-data]:http://nextml.github.io/caption-contest-data/
[cc-vote]:http://nextml.org/captioncontest
[daskml]:https://ml.dask.org/hyper-parameter-search.html
[jem-doc]:http://jemdoc.jaboc.net/
[talks]:https://github.com/stsievert/talks
[templates]:https://github.com/stsievert/templates
[salmon]:/salmon
[adadamp]:/adadamp
[swix]:/swix
[drawnow]:https://github.com/stsievert/python-drawnow
[jem-press]:/jem-press
