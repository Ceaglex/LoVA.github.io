---
layout: default
title: LoVA
---

<div class="post">
	<h2 class="pageTitle">LoVA:</h2>
	<h2 class="pageTitle">Long-Form Video-to-Audio Generation</h2>
    <p align="center">
	<img src="{{ '/assets/img/arch_Tiva.png' | relative_url }}" alt="">
    </p>
	<p>Video-to-audio (V2A) generation is essential for video and film editing, enabling the creation of semantically aligned audio from silent video. Existing methods, however, typically generate fixed-length short audio clips (e.g., 10 seconds) from short video segments, overlooking scenarios involving long-form video input. To address this limitation, we introduce a new task: long-form video-to-audio generation. We propose LoVA, a novel V2A model based on the DiT architecture, as a replacement for the commonly used Unet-based diffusion model. LoVA can generate audio clips up to 30 seconds long at a 44.1kHz sampling rate. Our experimental results demonstrate that LoVA achieves comparable performance on 10-second V2A benchmarks and sets new state-of-the-art results on long-form V2A benchmarks, highlighting the superiority of the DiT structure over Unet in long-form audio generation.</p>
</div>
