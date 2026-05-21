# LaCoDiff
LaCoDiff:  Structured Layout-Attribute Coupled Diffusion for Controllable Textile Texture Generation

Code will be released later.
## Challenges
As illustrated in Figure 1, generating layout-controllable textures is a non-trivial task. The model must generate objects of appropriate size within each bounding box, while ensuring that object category attributes are consistent with the box labels and that color attributes are aligned with the prompt. While existing methods perform well with a small number of bounding boxes, they face significant challenges when dealing with complex multi-object scenarios with rich semantics, leading to: (i) inaccurate layout and (ii) incorrect attribute binding.

<img width="902" height="697" alt="FIg1" src="https://github.com/user-attachments/assets/7847194c-ab06-4fac-abe9-6d25c7f88079" />
Figure 1. Challenges in textile texture layout control. Given text prompts and bounding box layouts, existing methods struggle with inaccurate layout control and incorrect attribute binding. Our method produces precise layouts with accurately generated patterns.

## The Overall Framework

<img width="1458" height="680" alt="Pipeline-1" src="https://github.com/user-attachments/assets/e7acf6d5-b1ad-4cf7-b207-6eef0a939ba4" />
Figure 2. Overall architecture of the proposed LaCoDiff. The proposed framework supports flexible multi-modal input configurations. Users can specify the desired layout by providing either bounding box maps or layout reference images. Conditioned on these layout inputs and textual prompts, the model can generate textures that faithfully align with the specified spatial layouts while achieving consistent binding across multiple semantic attributes described in the text.

## Qualitative results

<img width="1224" height="757" alt="定性比较" src="https://github.com/user-attachments/assets/05870f1a-8951-480b-bc31-bd054d593196" />
Figure 3. Qualitative comparison of layout control result by different methods. It is evident that our method outperforms other competitors in terms of attribute binding and spatial layout.

## Quantitative results

Table 1. Quantitative results of different methods on the TileVL dataset. The best and second-best results are highlighted in bold and underlined, respectively.

<img width="1401" height="450" alt="image" src="https://github.com/user-attachments/assets/5cc7fc6f-3c6d-400e-8be6-6026abd53c48" />
