---
layout: default
title: TeaVA
---

<div class="post">
	<h2 class="pageTitle">TeaVA:</h2>
	<h2 class="pageTitle">Temporal Aligned Video-to-Audio Generation</h2>
    <p align="center">
	<img src="{{ '/assets/img/framework.png' | relative_url }}" alt="">
    </p>
	<p>Video-to-Audio is essentially important for video generation and post-production, but it is challenging to generate high-quality sound for any silent video in the criteria of semantic similarity and temporal synchronization. Previous methods focus on semantic matching only or leverage contrastive audio-visual pretraining to learn that are temporally and semantically aligned in a coarse granularity. In this paper, to ensure more precise correspondence between video and audio, we propose a novel framework that disentangles semantic and temporal encoding and explicitly use both as conditions to control latent diffusion model based generation. We propose a simple but effective tempo layout that can simultaneously supervise the temporal encoder and condition the audio generator. 
Moreover, we propose two new fine-grained metrics to evaluate temporal synchronization, one of which 99\% correlates with human evaluation results. Experiments on large scale Video-to-Audio dataset indicate that our proposed method achieves state-of-the-art performance in various automatic metrics. Subjective evaluation shows it is dramatically superior to all baselines.</p>
</div>
