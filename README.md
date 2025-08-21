# STaR: Multi-Granular Spatio-Temporal Reasoning for Long-Form Dense Video Captioning
<img width="4869" height="1682" alt="overall_00" src="https://github.com/user-attachments/assets/a59a6220-97a8-49e2-baa4-baeaebe1ce85" />
Left illustrates the overall architecture. A frozen anchor-associated video encoder pre-extracts spatio-temporal features from the video, while a spot module classifies local features to determine caption positions and categories. The GCC module enhances localization by integrating local and global information. The SSS module utilizes hash grid encoding to extract positions and learn sparse location features. Local video selection is focused on a ∆-sized window around the previously localized position t_prop. The PCC module fuses spatial, global, and local features, aligns them with a large language model (LLM), and generates captions. As shown in right: 1) The GCC module receives local features, global features, and latents, where latents, as learnable vectors, act as query vectors in the Perceiver Resampler to compress and extract global feature information, producing latents containing both global and local features (G+L). 2) The PCC module uses local features, global features, spatial features, and latents as inputs to extract spatial information via the Perceiver Resampler, resulting in latents enriched with spatial, global, and local features (G+L+S).

## Task
> [!TIP]
> Coming Soon
- [ ] Code
- [ ] Dataset
- [ ] Pre-trained Model
