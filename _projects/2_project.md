---
layout: page
title: That's what Xi Said
description: A Computational Analysis of President Xi Jin Ping's (习近平) speeches
img: assets/img/thats_what_xi_said.jpg
importance: 2
category: work
giscus_comments: false
---

<a href="https://github.com/StLaurentMTL/Xi-Jin-Ping-Speech-Analysis?tab=readme-ov-file" class="btn btn-primary" target="_blank">View on GitHub</a>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/most_common_tokens.jpg" title="2025 Most Used Tokens" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A word cloud of the most commonly used words in Xi's public speeches during 2025. 
</div>

"That's what Xi Said" is an ongoing textual analysis project of the public speeches of President Xi Jinping, the current head of state for the People's Republic of China. The project contains a convienient Mandarin text corpus of Xi's public speeches from 2022-2025 that I scraped from official state sources. 

Using this text corpus, I train a relatively simple k-th order Markov model that allows for probabilistic speaker attribution. While I have primarily adopted my Markov model algorithm from a previous project/assignment I wrote, I am excited to see if these NLP techniques previously trained on an English language corpus will be salient for a Mandarin Chinese corpus.

Additionally, I conduct preliminary analysis using NLP techniques like LDA and Sentiment Analysis.
