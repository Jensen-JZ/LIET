# Pre-trained Low-light Image Enhancement Transformer (LIET)

This is the official PyTorch implementation repository for **Pre-trained Low-light Image Enhancement Transformer** (LIET), an efficient Low-light image enhancement transformer.

## Abstract
Low-light image enhancement is a long-standing low-level vision problem because low-light images frequently have serious aesthetic quality flaws. Current low-light image enhancement methods based on deep neural networks have achieved impressive progress on this task. Unlike the mainstream CNN-based methods, we propose an effective low-light enhancement solution inspired by the Transformer that has demonstrated impressive performance in various tasks to address such problems. The key of this solution includes an image synthesis pipeline and a powerful Transformer-based pre-trained model named LIET. Precisely, the image synthesis pipeline consists of illumination simulation and realistic noise simulation, which can simulate more realistic low-light images to alleviate the bottleneck of data scarcity. LIET consists of a pair of streamlined CNN-based encoder- decoders and a Transformer body, which can effectively perform global/local contextual feature extraction with relatively low computational cost. We extensively evaluate the proposed approach through extensive experiments, and the results demonstrate that our solution is highly competitive with state-of-the-art methods. All the codes will be released soon.

## Model Architecture
<img width="762" alt="image" src="https://github.com/Jensen-JZ/LIET/assets/36783874/f6d2a75b-199a-4fe9-b30c-2f4750b83c77">

## Results
**Fig 1** Visual comparison with SOTA low-light image enhancement methods in outdoor scenes with large light ratios. Better with enlarged views to observe the results (same for the following figures).

<img width="393" alt="image" src="https://github.com/Jensen-JZ/LIET/assets/36783874/b34d1902-81fa-46ea-883c-9a12be3fe563">

---

**Fig 2** Visual comparison with SOTA low-light image enhancement methods in dark indoor scenes.

<img width="392" alt="image" src="https://github.com/Jensen-JZ/LIET/assets/36783874/846b62bb-5388-494a-9654-666f9c3f1572">

---

**Fig 3** Visual comparison of noise suppression effects with SOTA low-light image enhancement methods in night scenes with complex lighting.

<img width="393" alt="image" src="https://github.com/Jensen-JZ/LIET/assets/36783874/7ab3fe62-144f-4f40-bfec-a07fd796495f">

More...

## Code
Coming soon...
